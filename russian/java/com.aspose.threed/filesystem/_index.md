---
title: FileSystem
second_title: Справочник API Aspose.3D для Java
description: Инкапсуляция файловой системы.
type: docs
weight: 67
url: /ru/java/com.aspose.threed/filesystem/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.io.Closeable
```
public abstract class FileSystem implements Closeable
```

Инкапсуляция файловой системы. Aspose.3D будет использовать её для чтения/записи зависимостей. **Пример:** Следующий код показывает, как импортировать файл и предоставить зависимые файлы в указанном каталоге

```
var inputFile = "input.fbx";
     var format = FileFormat.detect(inputFile);
     //create a load options instance and specify a zip file system
     var opt = format.createLoadOptions();
     opt.setFileSystem(new LocalFileSystem("textures/"));
     //load the file
     var scene = Scene.fromFile(inputFile, opt);
```
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [FileSystem()](#FileSystem--) |  |
## Методы

| Метод | Описание |
| --- | --- |
| [close()](#close--) | Освободите файловую систему и освободите её ресурсы. |
| [createDummyFileSystem()](#createDummyFileSystem--) | Создать фиктивную файловую систему, операции чтения/записи являются фиктивными. |
| [createLocalFileSystem(String directory)](#createLocalFileSystem-java.lang.String-) | Инициализировать новую [FileSystem](../../com.aspose.threed/filesystem), которая получает доступ только к локальному каталогу. |
| [createMemoryFileSystem()](#createMemoryFileSystem--) | Создать файловую систему, основанную на памяти, которая будет сопоставлять операции чтения/записи с памятью. |
| [createMemoryFileSystem(HashMap<String,MemoryStream> files)](#createMemoryFileSystem-java.util.HashMap-java.lang.String-com.aspose.threed.MemoryStream--) | Создать файловую систему, основанную на памяти, которая будет сопоставлять операции чтения/записи с памятью. |
| [createZipFileSystem(Stream stream)](#createZipFileSystem-com.aspose.threed.Stream-) | Создать файловую систему, предоставляющую только чтение указанного zip‑файла или zip‑потока. |
| [createZipFileSystem(Stream stream, String baseDir)](#createZipFileSystem-com.aspose.threed.Stream-java.lang.String-) | Создать файловую систему, предоставляющую только чтение указанного zip‑файла или zip‑потока. |
| [createZipFileSystem(String fileName)](#createZipFileSystem-java.lang.String-) | Файловая система, предоставляющая доступ только для чтения к указанному zip‑файлу или zip‑потоку. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [readFile(String fileName, IOConfig options)](#readFile-java.lang.String-com.aspose.threed.IOConfig-) | Создайте поток для чтения зависимостей. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
| [writeFile(String fileName, IOConfig options)](#writeFile-java.lang.String-com.aspose.threed.IOConfig-) | Создайте поток для записи зависимостей. |
### FileSystem() {#FileSystem--}
```
public FileSystem()
```


### close() {#close--}
```
public void close()
```


Освободите файловую систему и освободите её ресурсы.

### createDummyFileSystem() {#createDummyFileSystem--}
```
public static FileSystem createDummyFileSystem()
```


Создать фиктивную файловую систему, операции чтения/записи являются фиктивными.

**Returns:**
[FileSystem](../../com.aspose.threed/filesystem) - A dummy file system **Example:** The following code shows how to export file to memory, and ignore all dependent file generation.

```
//create a scene with material
     Scene scene = new Scene();
     scene.getRootNode().createChildNode(new Box()).setMaterial(new LambertMaterial());
     //create a save option and specify the file system, so the dependent file will be written to memory
     var opt = FileFormat.WAVEFRONTOBJ.createSaveOptions();
     var dfs = FileSystem.CreateDummyFileSystem();
     opt.setFileSystem(dfs);
     //obj's material file name is associated with the obj's file name, so we need a explicit name.
     opt.setFileName("test.obj");
     try (var ms = new MemoryStream())
     {
         scene.save(ms, opt);
     }
```
### createLocalFileSystem(String directory) {#createLocalFileSystem-java.lang.String-}
```
public static FileSystem createLocalFileSystem(String directory)
```


Инициализировать новую [FileSystem](../../com.aspose.threed/filesystem), которая получает доступ только к локальному каталогу. Все операции чтения/записи файлов в этом экземпляре FileSystem будут сопоставлены с указанным каталогом.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| каталог | java.lang.String | Каталог в вашей физической файловой системе, используемый в качестве виртуального корневого каталога. |

**Returns:**
[FileSystem](../../com.aspose.threed/filesystem) - A new instance of file system to provide local file access
### createMemoryFileSystem() {#createMemoryFileSystem--}
```
public static FileSystem createMemoryFileSystem()
```


Создать файловую систему, основанную на памяти, которая будет сопоставлять операции чтения/записи с памятью.

**Returns:**
[FileSystem](../../com.aspose.threed/filesystem) - A memory-based file system **Example:** The following code shows how to export file to memory, includes the dependent file by using MemoryFileSystem.

```
//create a scene with material
     Scene scene = new Scene();
     scene.getRootNode().createChildNode(new Box()).setMaterial(new LambertMaterial());
     //create a save option and specify the file system, so the dependent file will be written to memory
     var opt = FileFormat.WAVEFRONTOBJ.createSaveOptions();
     var mfs = new HashMap<String, MemoryStream>();
     opt.setFileSystem(FileSystem.createMemoryFileSystem(mfs));
     //obj's material file name is associated with the obj's file name, so we need a explicit name.
     opt.setFileName("test.obj");
     try (var ms = new MemoryStream())
     {
         scene.save(ms, opt);
     }
     //the test.obj was written to variable ms, and we can also get the test.mtl file content by
     var materialFile = mfs.get("test.mtl");
```
### createMemoryFileSystem(HashMap<String,MemoryStream> files) {#createMemoryFileSystem-java.util.HashMap-java.lang.String-com.aspose.threed.MemoryStream--}
```
public static FileSystem createMemoryFileSystem(HashMap<String,MemoryStream> files)
```


Создать файловую систему, основанную на памяти, которая будет сопоставлять операции чтения/записи с памятью.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| файлы | java.util.HashMap<java.lang.String,com.aspose.threed.MemoryStream> | Это позволяет вам читать/записывать виртуальные файлы. |

**Returns:**
[FileSystem](../../com.aspose.threed/filesystem) - A memory-based file system **Example:** The following code shows how to export file to memory, includes the dependent file by using MemoryFileSystem.

```
//create a scene with material
     Scene scene = new Scene();
     scene.getRootNode().createChildNode(new Box()).setMaterial(new LambertMaterial());
     //create a save option and specify the file system, so the dependent file will be written to memory
     var opt = FileFormat.WAVEFRONTOBJ.createSaveOptions();
     var mfs = new HashMap<String, MemoryStream>();
     opt.setFileSystem(FileSystem.createMemoryFileSystem(mfs));
     //obj's material file name is associated with the obj's file name, so we need a explicit name.
     opt.setFileName("test.obj");
     try (var ms = new MemoryStream())
     {
         scene.save(ms, opt);
     }
     //the test.obj was written to variable ms, and we can also get the test.mtl file content by
     var materialFile = mfs.get("test.mtl");
```
### createZipFileSystem(Stream stream) {#createZipFileSystem-com.aspose.threed.Stream-}
```
public static FileSystem createZipFileSystem(Stream stream)
```


Создать файловую систему, предоставляющую только чтение указанного zip‑файла или zip‑потока. Файловая система будет освобождена после операции открытия/сохранения.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| stream | [Stream](../../com.aspose.threed/stream) | Поток для доступа к zip‑файлу |

**Returns:**
[FileSystem](../../com.aspose.threed/filesystem) - A zip file system
### createZipFileSystem(Stream stream, String baseDir) {#createZipFileSystem-com.aspose.threed.Stream-java.lang.String-}
```
public static FileSystem createZipFileSystem(Stream stream, String baseDir)
```


Создать файловую систему, предоставляющую только чтение указанного zip‑файла или zip‑потока. Файловая система будет освобождена после операции открытия/сохранения.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| stream | [Stream](../../com.aspose.threed/stream) | Поток для доступа к zip‑файлу |
| baseDir | java.lang.String | Базовый каталог внутри zip‑файла. |

**Returns:**
[FileSystem](../../com.aspose.threed/filesystem) - A zip file system
### createZipFileSystem(String fileName) {#createZipFileSystem-java.lang.String-}
```
public static FileSystem createZipFileSystem(String fileName)
```


Файловая система, предоставляющая только чтение указанного zip‑файла или zip‑потока. Файловая система будет освобождена после операции открытия/сохранения.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| fileName | java.lang.String | Имя файла zip‑архива. |

**Returns:**
[FileSystem](../../com.aspose.threed/filesystem) - A zip file system
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### readFile(String fileName, IOConfig options) {#readFile-java.lang.String-com.aspose.threed.IOConfig-}
```
public abstract Stream readFile(String fileName, IOConfig options)
```


Создайте поток для чтения зависимостей.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| fileName | java.lang.String | Имя файла для открытия на чтение |
| options | [IOConfig](../../com.aspose.threed/ioconfig) | Сохранить или загрузить параметры |

**Returns:**
[Stream](../../com.aspose.threed/stream) - Stream for reading the file.
### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final void wait(long arg0)
```




**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

### writeFile(String fileName, IOConfig options) {#writeFile-java.lang.String-com.aspose.threed.IOConfig-}
```
public abstract Stream writeFile(String fileName, IOConfig options)
```


Создайте поток для записи зависимостей.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| fileName | java.lang.String | Имя файла для открытия на запись |
| options | [IOConfig](../../com.aspose.threed/ioconfig) | Сохранить или загрузить параметры |

**Returns:**
[Stream](../../com.aspose.threed/stream) - Stream for writing the file

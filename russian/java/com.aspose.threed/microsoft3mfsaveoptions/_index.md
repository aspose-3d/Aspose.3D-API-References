---
title: Microsoft3MFSaveOptions
second_title: Справочник API Aspose.3D для Java
description: Параметры сохранения для файла Microsoft 3MF.
type: docs
weight: 105
url: /ru/java/com.aspose.threed/microsoft3mfsaveoptions/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.IOConfig](../../com.aspose.threed/ioconfig), [com.aspose.threed.SaveOptions](../../com.aspose.threed/saveoptions)
```
public class Microsoft3MFSaveOptions extends SaveOptions
```

Параметры сохранения для файла Microsoft 3MF.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [Microsoft3MFSaveOptions()](#Microsoft3MFSaveOptions--) | Создать [Microsoft3MFSaveOptions](../../com.aspose.threed/microsoft3mfsaveoptions) |
## Методы

| Метод | Описание |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBuildAll()](#getBuildAll--) | Отметьте все геометрические объекты в сцене как печатаемые. |
| [getClass()](#getClass--) |  |
| [getEnableCompression()](#getEnableCompression--) | Включите сжатие в выходном файле 3mf. Значение по умолчанию — true. |
| [getEncoding()](#getEncoding--) | Получает кодировку по умолчанию для текстовых файлов. |
| [getExportTextures()](#getExportTextures--) | Пытается скопировать текстуры, используемые в сцене, в выходной каталог. |
| [getFileFormat()](#getFileFormat--) | Получает формат файла, указанный в текущей опции сохранения/загрузки. |
| [getFileName()](#getFileName--) | Имя файла экспортируемой/импортируемой сцены. |
| [getFileSystem()](#getFileSystem--) | Позволяет пользователю управлять внешними зависимостями во время загрузки/сохранения. |
| [getFileSystemFactory()](#getFileSystemFactory--) | Получает класс фабрики для FileSystem. |
| [getLookupPaths()](#getLookupPaths--) | Некоторые файлы, такие как OBJ, зависят от внешних файлов; пути поиска позволяют Aspose.3D находить внешние файлы для загрузки. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setBuildAll(boolean value)](#setBuildAll-boolean-) | Отметьте все геометрические объекты в сцене как печатаемые. |
| [setEnableCompression(boolean value)](#setEnableCompression-boolean-) | Включите сжатие в выходном файле 3mf. Значение по умолчанию — true. |
| [setEncoding(Charset value)](#setEncoding-java.nio.charset.Charset-) | Устанавливает кодировку по умолчанию для текстовых файлов. |
| [setExportTextures(boolean value)](#setExportTextures-boolean-) | Пытается скопировать текстуры, используемые в сцене, в выходной каталог. |
| [setFileName(String value)](#setFileName-java.lang.String-) | Имя файла экспортируемой/импортируемой сцены. |
| [setFileSystem(FileSystem value)](#setFileSystem-com.aspose.threed.FileSystem-) | Позволяет пользователю управлять внешними зависимостями во время загрузки/сохранения. |
| [setFileSystemFactory(FileSystemFactory value)](#setFileSystemFactory-com.aspose.threed.FileSystemFactory-) | Устанавливает класс фабрики для FileSystem. |
| [setLookupPaths(ArrayList<String> value)](#setLookupPaths-java.util.ArrayList-java.lang.String--) | Некоторые файлы, такие как OBJ, зависят от внешних файлов; пути поиска позволяют Aspose.3D находить внешние файлы для загрузки. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Microsoft3MFSaveOptions() {#Microsoft3MFSaveOptions--}
```
public Microsoft3MFSaveOptions()
```


Создать [Microsoft3MFSaveOptions](../../com.aspose.threed/microsoft3mfsaveoptions)

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
### getBuildAll() {#getBuildAll--}
```
public boolean getBuildAll()
```


Отметьте все геометрические объекты в сцене как печатаемые. Или вы можете вручную отметить узел как печатаемый с помощью [Microsoft3MFFormat](../../com.aspose.threed/microsoft3mfformat). Значение по умолчанию — true.

**Returns:**
boolean — Отметьте все геометрические объекты в сцене как печатаемые. Или вы можете вручную отметить узел как печатаемый с помощью [Microsoft3MFFormat](../../com.aspose.threed/microsoft3mfformat). Значение по умолчанию — true.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getEnableCompression() {#getEnableCompression--}
```
public boolean getEnableCompression()
```


Включите сжатие в выходном файле 3mf. Значение по умолчанию — true.

**Returns:**
boolean — Включите сжатие в выходном файле 3mf. Значение по умолчанию — true.
### getEncoding() {#getEncoding--}
```
public Charset getEncoding()
```


Получает кодировку по умолчанию для текстовых файлов. Значение по умолчанию — null, что означает, что импортёр/экспортёр определит, какую кодировку использовать.

**Returns:**
java.nio.charset.Charset - кодировка по умолчанию для текстовых файлов. Значение по умолчанию — null, что означает, что импортёр/экспортёр определит, какую кодировку использовать.
### getExportTextures() {#getExportTextures--}
```
public boolean getExportTextures()
```


Пытается скопировать текстуры, используемые в сцене, в выходной каталог.

**Returns:**
boolean — Пытаться копировать текстуры, используемые в сцене, в выходной каталог.
### getFileFormat() {#getFileFormat--}
```
public FileFormat getFileFormat()
```


Получает формат файла, указанный в текущей опции сохранения/загрузки.

**Returns:**
[FileFormat](../../com.aspose.threed/fileformat) - the file format that specified in current Save/Load option.
### getFileName() {#getFileName--}
```
public String getFileName()
```


Имя файла экспортируемой/импортируемой сцены. Это необязательно, но полезно при сериализации внешних ресурсов, таких как материал OBJ.

**Returns:**
java.lang.String - Имя файла экспортируемой/импортируемой сцены. Это необязательно, но полезно при сериализации внешних ресурсов, таких как материал OBJ.
### getFileSystem() {#getFileSystem--}
```
public FileSystem getFileSystem()
```


Позволяет пользователю управлять внешними зависимостями во время загрузки/сохранения.

**Returns:**
[FileSystem](../../com.aspose.threed/filesystem) - Allow user to handle how to manage the external dependencies during load/save. **Example:** The default FileSystem is LocalFileSystem, it is not safe in environment like server side, But you can override the file system access by specifying a different implementation. Aspose.3D provides different FileSystem implementation like:

 *  Memory-based file system
 *  Directory-based file system
 *  Dummy file system
 *  Zip file system

И вы также можете использовать свою собственную реализацию.

```
Scene scene = new Scene();
             var material = new PhongMaterial();
             var boxNode = scene.getRootNode().createChildNode(new Box());
             boxNode.setMaterial(material);
 
             var opt = new ObjSaveOptions();
             var memFs = new HashMap<string, MemoryStream>();
             opt.setFileSystem(FileSystem.createMemoryFileSystem(memFs));
 			opt.setFileName("output.obj");
             try(var output = new ByteArrayOutputStream()) {
 				scene.save(output, opt);
 				//The material will be written to variable memFs named output.mtl
 				var materialInBytes = memFs["output.mtl"].toArray();
             }
```
### getFileSystemFactory() {#getFileSystemFactory--}
```
public static FileSystemFactory getFileSystemFactory()
```


Получает класс фабрики для FileSystem. Фабрика по умолчанию создаст com.aspose.threed.LocalFileSystem, который не подходит для серверной среды.

**Returns:**
[FileSystemFactory](../../com.aspose.threed/filesystemfactory) - the factory class for FileSystem. The default factory will create com.aspose.threed.LocalFileSystem which is not suitable for server environment. **Example:** The default FileSystem in SaveOptions/LoadOptions is directory-based file system, You can override the default implementation by specify it through IOConfig.FileSystemFactory:

```
IOConfig.setFileSystemFactory(new FileSystemFactory() {
 				@Override
 				public FileSystem call() {
 					return FileSystem.createDummyFileSystem();
 				}
 			});
 
             Scene scene = new Scene();
             var material = new PhongMaterial();
             var boxNode = scene.getRootNode().createChildNode(new Box());
             boxNode.setMaterial(material);
 
             //opt.FileSystem would be dummy file system now
             var opt = new ObjSaveOptions();
             scene.Save("output.obj", opt);
             //the material file output.mtl will not be written to any places because we've configured a dummy file system as default implementation.
```
### getLookupPaths() {#getLookupPaths--}
```
public ArrayList<String> getLookupPaths()
```


Некоторые файлы, такие как OBJ, зависят от внешних файлов; пути поиска позволяют Aspose.3D находить внешние файлы для загрузки.

**Returns:**
java.util.ArrayList<java.lang.String> - Некоторые файлы, такие как OBJ, зависят от внешних файлов; пути поиска позволяют Aspose.3D искать внешние файлы для загрузки. **Example:** Следующий код показывает, как вручную указать пути поиска текстур, чтобы импортёр мог их найти

```
var opt = new ObjLoadOptions();
             //Specify the lookup paths, so the textures can be located.
             opt.getLookupPaths().add("textures");
             var scene = Scene.fromFile("input.obj", opt);
             scene.save("output.glb");
```
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




### setBuildAll(boolean value) {#setBuildAll-boolean-}
```
public void setBuildAll(boolean value)
```


Отметьте все геометрические объекты в сцене как печатаемые. Или вы можете вручную отметить узел как печатаемый с помощью [Microsoft3MFFormat](../../com.aspose.threed/microsoft3mfformat). Значение по умолчанию — true.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | boolean | Новое значение |

### setEnableCompression(boolean value) {#setEnableCompression-boolean-}
```
public void setEnableCompression(boolean value)
```


Включите сжатие в выходном файле 3mf. Значение по умолчанию — true.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | boolean | Новое значение |

### setEncoding(Charset value) {#setEncoding-java.nio.charset.Charset-}
```
public void setEncoding(Charset value)
```


Устанавливает кодировку по умолчанию для текстовых файлов. Значение по умолчанию — null, что означает, что импортёр/экспортёр определит, какую кодировку использовать.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.nio.charset.Charset | Новое значение |

### setExportTextures(boolean value) {#setExportTextures-boolean-}
```
public void setExportTextures(boolean value)
```


Пытается скопировать текстуры, используемые в сцене, в выходной каталог.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | boolean | Новое значение |

### setFileName(String value) {#setFileName-java.lang.String-}
```
public void setFileName(String value)
```


Имя файла экспортируемой/импортируемой сцены. Это необязательно, но полезно при сериализации внешних ресурсов, таких как материал OBJ.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.String | Новое значение |

### setFileSystem(FileSystem value) {#setFileSystem-com.aspose.threed.FileSystem-}
```
public void setFileSystem(FileSystem value)
```


Позволяет пользователю управлять внешними зависимостями во время загрузки/сохранения.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | value | [FileSystem](../../com.aspose.threed/filesystem) | Новое значение **Example:** Файловая система по умолчанию — LocalFileSystem, она не безопасна в среде, подобной серверной, но вы можете переопределить доступ к файловой системе, указав другую реализацию. Aspose.3D предоставляет различные реализации FileSystem, такие как: |

 *  Memory-based file system
 *  Directory-based file system
 *  Dummy file system
 *  Zip file system

И вы также можете использовать свою собственную реализацию.

```
Scene scene = new Scene();
             var material = new PhongMaterial();
             var boxNode = scene.getRootNode().createChildNode(new Box());
             boxNode.setMaterial(material);
 
             var opt = new ObjSaveOptions();
             var memFs = new HashMap<string, MemoryStream>();
             opt.setFileSystem(FileSystem.createMemoryFileSystem(memFs));
 			opt.setFileName("output.obj");
             try(var output = new ByteArrayOutputStream()) {
 				scene.save(output, opt);
 				//The material will be written to variable memFs named output.mtl
 				var materialInBytes = memFs["output.mtl"].toArray();
             }
``` |

### setFileSystemFactory(FileSystemFactory value) {#setFileSystemFactory-com.aspose.threed.FileSystemFactory-}
```
public static void setFileSystemFactory(FileSystemFactory value)
```


Устанавливает класс фабрики для FileSystem. Фабрика по умолчанию создаст com.aspose.threed.LocalFileSystem, который не подходит для серверной среды.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | value | [FileSystemFactory](../../com.aspose.threed/filesystemfactory) | Новое значение **Example:** Файловая система по умолчанию в SaveOptions/LoadOptions — файловая система, основанная на каталогах. Вы можете переопределить реализацию по умолчанию, указав её через IOConfig.FileSystemFactory: |

```
IOConfig.setFileSystemFactory(new FileSystemFactory() {
 				@Override
 				public FileSystem call() {
 					return FileSystem.createDummyFileSystem();
 				}
 			});
 
             Scene scene = new Scene();
             var material = new PhongMaterial();
             var boxNode = scene.getRootNode().createChildNode(new Box());
             boxNode.setMaterial(material);
 
             //opt.FileSystem would be dummy file system now
             var opt = new ObjSaveOptions();
             scene.Save("output.obj", opt);
             //the material file output.mtl will not be written to any places because we've configured a dummy file system as default implementation.
``` |

### setLookupPaths(ArrayList<String> value) {#setLookupPaths-java.util.ArrayList-java.lang.String--}
```
public void setLookupPaths(ArrayList<String> value)
```


Некоторые файлы, такие как OBJ, зависят от внешних файлов; пути поиска позволяют Aspose.3D находить внешние файлы для загрузки.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | значение | java.util.ArrayList<java.lang.String> | Новое значение **Example:** Следующий код показывает, как вручную указать пути поиска текстур, чтобы импортёр мог их найти |

```
var opt = new ObjLoadOptions();
             //Specify the lookup paths, so the textures can be located.
             opt.getLookupPaths().add("textures");
             var scene = Scene.fromFile("input.obj", opt);
             scene.save("output.glb");
``` |

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


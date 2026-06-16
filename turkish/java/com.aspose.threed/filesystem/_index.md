---
title: "FileSystem"
second_title: "Aspose.3D for Java API Referansı"
description: "Dosya sistemi kapsülleme."
type: docs
weight: 67
url: /tr/java/com.aspose.threed/filesystem/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.io.Closeable
```
public abstract class FileSystem implements Closeable
```

Dosya sistemi kapsülleme. Aspose.3D bunu bağımlılıkları okuma/yazma için kullanacak. **Example:** Aşağıdaki kod, dosyanın nasıl içe aktarılacağını ve belirli bir dizinde bağımlı dosyaların nasıl sağlanacağını gösterir.

```
var inputFile = "input.fbx";
     var format = FileFormat.detect(inputFile);
     //create a load options instance and specify a zip file system
     var opt = format.createLoadOptions();
     opt.setFileSystem(new LocalFileSystem("textures/"));
     //load the file
     var scene = Scene.fromFile(inputFile, opt);
```
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [FileSystem()](#FileSystem--) |  |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [close()](#close--) | Dosya sistemini kapatın ve kaynaklarını serbest bırakın. |
| [createDummyFileSystem()](#createDummyFileSystem--) | Sahte bir dosya sistemi oluşturun, okuma/yazma işlemleri sahte işlemlerdir. |
| [createLocalFileSystem(String directory)](#createLocalFileSystem-java.lang.String-) | Yalnızca yerel dizine erişen yeni bir [FileSystem](../../com.aspose.threed/filesystem) başlatın. |
| [createMemoryFileSystem()](#createMemoryFileSystem--) | Okuma/yazma işlemlerini belleğe eşleyecek bellek tabanlı bir dosya sistemi oluşturun. |
| [createMemoryFileSystem(HashMap<String,MemoryStream> files)](#createMemoryFileSystem-java.util.HashMap-java.lang.String-com.aspose.threed.MemoryStream--) | Okuma/yazma işlemlerini belleğe eşleyecek bellek tabanlı bir dosya sistemi oluşturun. |
| [createZipFileSystem(Stream stream)](#createZipFileSystem-com.aspose.threed.Stream-) | Belirtilen zip dosyasına veya zip akışına yalnızca okuma erişimi sağlamak için bir dosya sistemi oluşturun. |
| [createZipFileSystem(Stream stream, String baseDir)](#createZipFileSystem-com.aspose.threed.Stream-java.lang.String-) | Belirtilen zip dosyasına veya zip akışına yalnızca okuma erişimi sağlamak için bir dosya sistemi oluşturun. |
| [createZipFileSystem(String fileName)](#createZipFileSystem-java.lang.String-) | Belirtilen zip dosyasına veya zip akışına yalnızca okuma erişimi sağlamak için dosya sistemi. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [readFile(String fileName, IOConfig options)](#readFile-java.lang.String-com.aspose.threed.IOConfig-) | Bağımlılıkları okumak için bir akış oluşturun. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
| [writeFile(String fileName, IOConfig options)](#writeFile-java.lang.String-com.aspose.threed.IOConfig-) | Bağımlılıkları yazmak için bir akış oluşturun. |
### FileSystem() {#FileSystem--}
```
public FileSystem()
```


### close() {#close--}
```
public void close()
```


Dosya sistemini kapatın ve kaynaklarını serbest bırakın.

### createDummyFileSystem() {#createDummyFileSystem--}
```
public static FileSystem createDummyFileSystem()
```


Sahte bir dosya sistemi oluşturun, okuma/yazma işlemleri sahte işlemlerdir.

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


Yalnızca yerel dizine erişen yeni bir [FileSystem](../../com.aspose.threed/filesystem) başlatın. Bu FileSystem örneğindeki tüm dosya okuma/yazma işlemleri belirtilen dizine eşlenecektir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| dizin | java.lang.String | Fiziksel dosya sisteminizdeki dizin, sanal kök dizin olarak kullanılacaktır. |

**Returns:**
[FileSystem](../../com.aspose.threed/filesystem) - A new instance of file system to provide local file access
### createMemoryFileSystem() {#createMemoryFileSystem--}
```
public static FileSystem createMemoryFileSystem()
```


Okuma/yazma işlemlerini belleğe eşleyecek bellek tabanlı bir dosya sistemi oluşturun.

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


Okuma/yazma işlemlerini belleğe eşleyecek bellek tabanlı bir dosya sistemi oluşturun.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| dosyalar | java.util.HashMap<java.lang.String,com.aspose.threed.MemoryStream> | Bu, sanal dosyaları okuma/yazma imkanı sağlar. |

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


Belirtilen zip dosyasına veya zip akışına yalnızca okuma erişimi sağlamak için bir dosya sistemi oluşturun. Dosya sistemi, açma/kaydetme işleminden sonra yok edilecektir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| stream | [Stream](../../com.aspose.threed/stream) | Zip dosyasına erişmek için akış |

**Returns:**
[FileSystem](../../com.aspose.threed/filesystem) - A zip file system
### createZipFileSystem(Stream stream, String baseDir) {#createZipFileSystem-com.aspose.threed.Stream-java.lang.String-}
```
public static FileSystem createZipFileSystem(Stream stream, String baseDir)
```


Belirtilen zip dosyasına veya zip akışına yalnızca okuma erişimi sağlamak için bir dosya sistemi oluşturun. Dosya sistemi, açma/kaydetme işleminden sonra yok edilecektir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| stream | [Stream](../../com.aspose.threed/stream) | Zip dosyasına erişmek için akış |
| baseDir | java.lang.String | Zip dosyasının içindeki temel dizin. |

**Returns:**
[FileSystem](../../com.aspose.threed/filesystem) - A zip file system
### createZipFileSystem(String fileName) {#createZipFileSystem-java.lang.String-}
```
public static FileSystem createZipFileSystem(String fileName)
```


Belirtilen zip dosyasına veya zip akışına yalnızca okuma erişimi sağlamak için dosya sistemi. Dosya sistemi, açma/kaydetme işleminden sonra yok edilecektir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| fileName | java.lang.String | Zip dosyasının dosya adı. |

**Returns:**
[FileSystem](../../com.aspose.threed/filesystem) - A zip file system
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parametre | Tür | Açıklama |
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


Bağımlılıkları okumak için bir akış oluşturun.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| fileName | java.lang.String | Okuma için açılacak dosyanın adı |
| options | [IOConfig](../../com.aspose.threed/ioconfig) | Kaydetme veya yükleme seçenekleri |

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
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

### writeFile(String fileName, IOConfig options) {#writeFile-java.lang.String-com.aspose.threed.IOConfig-}
```
public abstract Stream writeFile(String fileName, IOConfig options)
```


Bağımlılıkları yazmak için bir akış oluşturun.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| fileName | java.lang.String | Yazma için açılacak dosyanın adı |
| options | [IOConfig](../../com.aspose.threed/ioconfig) | Kaydetme veya yükleme seçenekleri |

**Returns:**
[Stream](../../com.aspose.threed/stream) - Stream for writing the file

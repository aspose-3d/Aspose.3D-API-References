---
title: "文件系统"
second_title: "Aspose.3D for Java API 参考"
description: "文件系统封装。"
type: docs
weight: 67
url: /zh/java/com.aspose.threed/filesystem/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.io.Closeable
```
public abstract class FileSystem implements Closeable
```

文件系统封装。Aspose.3D 将使用它来读取/写入依赖项。**Example:** 以下代码展示了如何导入文件，并在给定目录中提供依赖文件

```
var inputFile = "input.fbx";
     var format = FileFormat.detect(inputFile);
     //create a load options instance and specify a zip file system
     var opt = format.createLoadOptions();
     opt.setFileSystem(new LocalFileSystem("textures/"));
     //load the file
     var scene = Scene.fromFile(inputFile, opt);
```
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [FileSystem()](#FileSystem--) |  |
## 方法

| 方法 | 描述 |
| --- | --- |
| [close()](#close--) | 释放文件系统并释放其资源。 |
| [createDummyFileSystem()](#createDummyFileSystem--) | 创建一个虚拟文件系统，读取/写入操作为虚拟操作。 |
| [createLocalFileSystem(String directory)](#createLocalFileSystem-java.lang.String-) | 初始化一个新的 [FileSystem](../../com.aspose.threed/filesystem)，仅访问本地目录。 |
| [createMemoryFileSystem()](#createMemoryFileSystem--) | 创建一个基于内存的文件系统，将读取/写入操作映射到内存。 |
| [createMemoryFileSystem(HashMap<String,MemoryStream> files)](#createMemoryFileSystem-java.util.HashMap-java.lang.String-com.aspose.threed.MemoryStream--) | 创建一个基于内存的文件系统，将读取/写入操作映射到内存。 |
| [createZipFileSystem(Stream stream)](#createZipFileSystem-com.aspose.threed.Stream-) | 创建一个文件系统，以提供对指定 zip 文件或 zip 流的只读访问。 |
| [createZipFileSystem(Stream stream, String baseDir)](#createZipFileSystem-com.aspose.threed.Stream-java.lang.String-) | 创建一个文件系统，以提供对指定 zip 文件或 zip 流的只读访问。 |
| [createZipFileSystem(String fileName)](#createZipFileSystem-java.lang.String-) | 文件系统提供对指定 zip 文件或 zip 流的只读访问。 |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [readFile(String fileName, IOConfig options)](#readFile-java.lang.String-com.aspose.threed.IOConfig-) | 创建用于读取依赖项的流。 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
| [writeFile(String fileName, IOConfig options)](#writeFile-java.lang.String-com.aspose.threed.IOConfig-) | 创建用于写入依赖项的流。 |
### FileSystem() {#FileSystem--}
```
public FileSystem()
```


### close() {#close--}
```
public void close()
```


释放文件系统并释放其资源。

### createDummyFileSystem() {#createDummyFileSystem--}
```
public static FileSystem createDummyFileSystem()
```


创建一个虚拟文件系统，读取/写入操作为虚拟操作。

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


初始化一个新的 [FileSystem](../../com.aspose.threed/filesystem)，仅访问本地目录。此 FileSystem 实例上的所有文件读取/写入将映射到指定目录。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 目录 | java.lang.String | 将您物理文件系统中的目录用作虚拟根目录。 |

**Returns:**
[FileSystem](../../com.aspose.threed/filesystem) - A new instance of file system to provide local file access
### createMemoryFileSystem() {#createMemoryFileSystem--}
```
public static FileSystem createMemoryFileSystem()
```


创建一个基于内存的文件系统，将读取/写入操作映射到内存。

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


创建一个基于内存的文件系统，将读取/写入操作映射到内存。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 文件 | java.util.HashMap<java.lang.String,com.aspose.threed.MemoryStream> | 这允许您读取/写入虚拟文件。 |

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


创建一个文件系统，以提供对指定 zip 文件或 zip 流的只读访问。文件系统将在打开/保存操作后被释放。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| stream | [Stream](../../com.aspose.threed/stream) | 用于访问 zip 文件的流 |

**Returns:**
[FileSystem](../../com.aspose.threed/filesystem) - A zip file system
### createZipFileSystem(Stream stream, String baseDir) {#createZipFileSystem-com.aspose.threed.Stream-java.lang.String-}
```
public static FileSystem createZipFileSystem(Stream stream, String baseDir)
```


创建一个文件系统，以提供对指定 zip 文件或 zip 流的只读访问。文件系统将在打开/保存操作后被释放。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| stream | [Stream](../../com.aspose.threed/stream) | 用于访问 zip 文件的流 |
| baseDir | java.lang.String | zip 文件内部的基目录。 |

**Returns:**
[FileSystem](../../com.aspose.threed/filesystem) - A zip file system
### createZipFileSystem(String fileName) {#createZipFileSystem-java.lang.String-}
```
public static FileSystem createZipFileSystem(String fileName)
```


文件系统，以提供对指定 zip 文件或 zip 流的只读访问。文件系统将在打开/保存操作后被释放。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 文件名 | java.lang.String | zip 文件的文件名。 |

**Returns:**
[FileSystem](../../com.aspose.threed/filesystem) - A zip file system
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
布尔
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


创建用于读取依赖项的流。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 文件名 | java.lang.String | 要打开读取的文件名 |
| options | [IOConfig](../../com.aspose.threed/ioconfig) | 保存或加载选项 |

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
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

### writeFile(String fileName, IOConfig options) {#writeFile-java.lang.String-com.aspose.threed.IOConfig-}
```
public abstract Stream writeFile(String fileName, IOConfig options)
```


创建用于写入依赖项的流。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 文件名 | java.lang.String | 用于写入的文件名 |
| options | [IOConfig](../../com.aspose.threed/ioconfig) | 保存或加载选项 |

**Returns:**
[Stream](../../com.aspose.threed/stream) - Stream for writing the file

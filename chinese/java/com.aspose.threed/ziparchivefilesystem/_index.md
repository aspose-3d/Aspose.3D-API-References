---
title: "ZipArchiveFileSystem"
second_title: "Aspose.3D for Java API 参考"
description: "文件系统提供对指定 zip 文件或 zip 流的只读访问。"
type: docs
weight: 221
url: /zh/java/com.aspose.threed/ziparchivefilesystem/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.FileSystem](../../com.aspose.threed/filesystem)
```
public class ZipArchiveFileSystem extends FileSystem
```

文件系统提供对指定 zip 文件或 zip 流的只读访问。文件系统将在打开/保存操作后被释放。**Example:** 以下代码展示了如何导入文件，并在 zip 存档文件中提供依赖文件。

```
var inputFile = "input.fbx";
     var format = FileFormat.detect(inputFile);
     //create a load options instance and specify a zip file system
     var opt = format.createLoadOptions();
     opt.setFileSystem(new ZipArchiveFileSystem("textures.zip"));
     //load the file
     var scene = Scene.fromFile(inputFile, opt);
```
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [ZipArchiveFileSystem(Stream stream, String baseDir)](#ZipArchiveFileSystem-com.aspose.csporter.helpers.Stream-java.lang.String-) | 通过流构造一个 [ZipArchiveFileSystem](../../com.aspose.threed/ziparchivefilesystem)。 |
| [ZipArchiveFileSystem(Stream stream)](#ZipArchiveFileSystem-com.aspose.csporter.helpers.Stream-) | 通过流构造一个 [ZipArchiveFileSystem](../../com.aspose.threed/ziparchivefilesystem)。 |
| [ZipArchiveFileSystem(String fileName)](#ZipArchiveFileSystem-java.lang.String-) | 通过文件名构造一个 [ZipArchiveFileSystem](../../com.aspose.threed/ziparchivefilesystem)。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [close()](#close--) | 释放 ZipArchiveFileSystem 并释放其内部资源。 |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [readFile(String fileName, IOConfig options)](#readFile-java.lang.String-com.aspose.threed.IOConfig-) | 打开文件以读取 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
| [writeFile(String fileName, IOConfig options)](#writeFile-java.lang.String-com.aspose.threed.IOConfig-) | 打开文件以写入，此类未实现。 |
### ZipArchiveFileSystem(Stream stream, String baseDir) {#ZipArchiveFileSystem-com.aspose.csporter.helpers.Stream-java.lang.String-}
```
public ZipArchiveFileSystem(Stream stream, String baseDir)
```


通过流构造一个 [ZipArchiveFileSystem](../../com.aspose.threed/ziparchivefilesystem)。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 流 | com.aspose.csporter.helpers.Stream |  |
| baseDir | java.lang.String |  |

### ZipArchiveFileSystem(Stream stream) {#ZipArchiveFileSystem-com.aspose.csporter.helpers.Stream-}
```
public ZipArchiveFileSystem(Stream stream)
```


通过流构造一个 [ZipArchiveFileSystem](../../com.aspose.threed/ziparchivefilesystem)。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 流 | com.aspose.csporter.helpers.Stream |  |

### ZipArchiveFileSystem(String fileName) {#ZipArchiveFileSystem-java.lang.String-}
```
public ZipArchiveFileSystem(String fileName)
```


通过文件名构造一个 [ZipArchiveFileSystem](../../com.aspose.threed/ziparchivefilesystem)。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 文件名 | java.lang.String |  |

### close() {#close--}
```
public void close()
```


释放 ZipArchiveFileSystem 并释放其内部资源。

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
public Stream readFile(String fileName, IOConfig options)
```


打开文件以读取

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 文件名 | java.lang.String |  |
| options | [IOConfig](../../com.aspose.threed/ioconfig) |  |

**Returns:**
com.aspose.csporter.helpers.Stream
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
public Stream writeFile(String fileName, IOConfig options)
```


打开文件以写入，此类未实现。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 文件名 | java.lang.String |  |
| options | [IOConfig](../../com.aspose.threed/ioconfig) |  |

**Returns:**
com.aspose.csporter.helpers.Stream

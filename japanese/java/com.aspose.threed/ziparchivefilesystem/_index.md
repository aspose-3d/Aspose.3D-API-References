---
title: ZipArchiveFileSystem
second_title: Aspose.3D for Java API リファレンス
description: 指定された zip ファイルまたは zip ストリームへの読み取り専用アクセスを提供するファイルシステム。
type: docs
weight: 221
url: /ja/java/com.aspose.threed/ziparchivefilesystem/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.FileSystem](../../com.aspose.threed/filesystem)
```
public class ZipArchiveFileSystem extends FileSystem
```

指定された zip ファイルまたは zip ストリームへの読み取り専用アクセスを提供するファイルシステム。ファイルシステムはオープン/保存操作の後に破棄されます。**Example:** 以下のコードはファイルのインポート方法と、zip アーカイブファイル内の依存ファイルを提供する方法を示しています。

```
var inputFile = "input.fbx";
     var format = FileFormat.detect(inputFile);
     //create a load options instance and specify a zip file system
     var opt = format.createLoadOptions();
     opt.setFileSystem(new ZipArchiveFileSystem("textures.zip"));
     //load the file
     var scene = Scene.fromFile(inputFile, opt);
```
## Constructors

| Constructor | 説明 |
| --- | --- |
| [ZipArchiveFileSystem(Stream stream, String baseDir)](#ZipArchiveFileSystem-com.aspose.csporter.helpers.Stream-java.lang.String-) | ストリームを介して [ZipArchiveFileSystem](../../com.aspose.threed/ziparchivefilesystem) を構築します。 |
| [ZipArchiveFileSystem(Stream stream)](#ZipArchiveFileSystem-com.aspose.csporter.helpers.Stream-) | ストリームを介して [ZipArchiveFileSystem](../../com.aspose.threed/ziparchivefilesystem) を構築します。 |
| [ZipArchiveFileSystem(String fileName)](#ZipArchiveFileSystem-java.lang.String-) | ファイル名を介して [ZipArchiveFileSystem](../../com.aspose.threed/ziparchivefilesystem) を構築します。 |
## Methods

| Method | 説明 |
| --- | --- |
| [close()](#close--) | ZipArchiveFileSystem を破棄し、内部リソースを解放します。 |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [readFile(String fileName, IOConfig options)](#readFile-java.lang.String-com.aspose.threed.IOConfig-) | 読み取り用にファイルを開く |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
| [writeFile(String fileName, IOConfig options)](#writeFile-java.lang.String-com.aspose.threed.IOConfig-) | 書き込み用にファイルを開く（このクラスでは実装されていません）。 |
### ZipArchiveFileSystem(Stream stream, String baseDir) {#ZipArchiveFileSystem-com.aspose.csporter.helpers.Stream-java.lang.String-}
```
public ZipArchiveFileSystem(Stream stream, String baseDir)
```


ストリームを介して [ZipArchiveFileSystem](../../com.aspose.threed/ziparchivefilesystem) を構築します。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| ストリーム | com.aspose.csporter.helpers.Stream |  |
| baseDir | java.lang.String |  |

### ZipArchiveFileSystem(Stream stream) {#ZipArchiveFileSystem-com.aspose.csporter.helpers.Stream-}
```
public ZipArchiveFileSystem(Stream stream)
```


ストリームを介して [ZipArchiveFileSystem](../../com.aspose.threed/ziparchivefilesystem) を構築します。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| ストリーム | com.aspose.csporter.helpers.Stream |  |

### ZipArchiveFileSystem(String fileName) {#ZipArchiveFileSystem-java.lang.String-}
```
public ZipArchiveFileSystem(String fileName)
```


ファイル名を介して [ZipArchiveFileSystem](../../com.aspose.threed/ziparchivefilesystem) を構築します。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| fileName | java.lang.String |  |

### close() {#close--}
```
public void close()
```


ZipArchiveFileSystem を破棄し、内部リソースを解放します。

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Type | 説明 |
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
public Stream readFile(String fileName, IOConfig options)
```


読み取り用にファイルを開く

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| fileName | java.lang.String |  |
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
| Parameter | Type | 説明 |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

### writeFile(String fileName, IOConfig options) {#writeFile-java.lang.String-com.aspose.threed.IOConfig-}
```
public Stream writeFile(String fileName, IOConfig options)
```


書き込み用にファイルを開く（このクラスでは実装されていません）。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| fileName | java.lang.String |  |
| options | [IOConfig](../../com.aspose.threed/ioconfig) |  |

**Returns:**
com.aspose.csporter.helpers.Stream

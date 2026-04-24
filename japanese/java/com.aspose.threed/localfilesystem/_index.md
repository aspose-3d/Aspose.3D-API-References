---
title: LocalFileSystem
second_title: Aspose.3D for Java API リファレンス
description: ローカルディレクトリへの読み書き操作をマッピングします。
type: docs
weight: 91
url: /ja/java/com.aspose.threed/localfilesystem/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.FileSystem](../../com.aspose.threed/filesystem)
```
public class LocalFileSystem extends FileSystem
```

[LocalFileSystem](../../com.aspose.threed/localfilesystem) はローカルディレクトリへの読み書き操作をマッピングします。 **Example:** 以下のコードは、ファイルをインポートし、指定ディレクトリ内の依存ファイルを提供する方法を示しています。

```
var inputFile = "input.fbx";
     var format = FileFormat.detect(inputFile);
     //create a load options instance and specify a zip file system
     var opt = format.createLoadOptions();
     opt.setFileSystem(new LocalFileSystem("textures/"));
     //load the file
     var scene = Scene.fromFile(inputFile, opt);
```
## Constructors

| Constructor | 説明 |
| --- | --- |
| [LocalFileSystem(String directory)](#LocalFileSystem-java.lang.String-) | 指定されたベースディレクトリで新しい [LocalFileSystem](../../com.aspose.threed/localfilesystem) を初期化します。 |
## Methods

| Method | 説明 |
| --- | --- |
| [close()](#close--) | ファイルシステムを破棄し、そのリソースを解放します。 |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [readFile(String fileName, IOConfig options)](#readFile-java.lang.String-com.aspose.threed.IOConfig-) | 依存関係を読み取るためのストリームを作成します。 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
| [writeFile(String fileName, IOConfig options)](#writeFile-java.lang.String-com.aspose.threed.IOConfig-) | 依存関係を書き込むためのストリームを作成します。 |
### LocalFileSystem(String directory) {#LocalFileSystem-java.lang.String-}
```
public LocalFileSystem(String directory)
```


指定されたベースディレクトリで新しい [LocalFileSystem](../../com.aspose.threed/localfilesystem) を初期化します。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| ディレクトリ | java.lang.String |  |

### close() {#close--}
```
public void close()
```


ファイルシステムを破棄し、そのリソースを解放します。

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


依存関係を読み取るためのストリームを作成します。

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


依存関係を書き込むためのストリームを作成します。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| fileName | java.lang.String |  |
| options | [IOConfig](../../com.aspose.threed/ioconfig) |  |

**Returns:**
com.aspose.csporter.helpers.Stream

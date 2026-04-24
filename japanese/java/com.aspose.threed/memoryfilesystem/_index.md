---
title: MemoryFileSystem
second_title: Aspose.3D for Java API リファレンス
description: この  は読み書き操作をメモリにマップします。
type: docs
weight: 95
url: /ja/java/com.aspose.threed/memoryfilesystem/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.FileSystem](../../com.aspose.threed/filesystem)
```
public class MemoryFileSystem extends FileSystem
```

この [MemoryFileSystem](../../com.aspose.threed/memoryfilesystem) は読み書き操作をメモリにマップします。 **Example:** 以下のコードは、ファイルをメモリにエクスポートし、MemoryFileSystem を使用して依存ファイルを含める方法を示しています。

```
//create a scene with material
     Scene scene = new Scene();
     scene.getRootNode().createChildNode(new Box()).setMaterial(new LambertMaterial());
     //create a save option and specify the file system, so the dependent file will be written to memory
     var opt = FileFormat.WAVEFRONTOBJ.createSaveOptions();
     var mfs = new MemoryFileSystem();
     opt.setFileSystem(mfs);
     //obj's material file name is associated with the obj's file name, so we need a explicit name.
     opt.setFileName("test.obj");
     try (var ms = new MemoryStream())
     {
         scene.save(ms, opt);
     }
     //the test.obj was written to variable ms, and we can also get the test.mtl file content by
     var materialFile = mfs.getFileContent("test.mtl");
```
## Constructors

| Constructor | 説明 |
| --- | --- |
| [MemoryFileSystem()](#MemoryFileSystem--) |  |
## Methods

| Method | 説明 |
| --- | --- |
| [close()](#close--) | ファイルシステムを破棄し、そのリソースを解放します。 |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getFileContent(String fileName)](#getFileContent-java.lang.String-) | 指定されたファイルの生データを返します。 |
| [getFileNames()](#getFileNames--) | このメモリファイルシステム内のファイル名。 |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [readFile(String fileName, IOConfig options)](#readFile-java.lang.String-com.aspose.threed.IOConfig-) | 依存関係を読み取るためのストリームを作成します。 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
| [writeFile(String fileName, IOConfig options)](#writeFile-java.lang.String-com.aspose.threed.IOConfig-) | 依存関係を書き込むためのストリームを作成します。 |
### MemoryFileSystem() {#MemoryFileSystem--}
```
public MemoryFileSystem()
```


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
### getFileContent(String fileName) {#getFileContent-java.lang.String-}
```
public byte[] getFileContent(String fileName)
```


指定されたファイルの生データを返します。指定されたファイルが存在しない場合は java.io.FileNotFoundException をスローします。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| fileName | java.lang.String |  |

**Returns:**
byte[]
### getFileNames() {#getFileNames--}
```
public List<String> getFileNames()
```


このメモリファイルシステム内のファイル名。

**Returns:**
java.util.List<java.lang.String>
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

---
title: FileSystem
second_title: Aspose.3D for Java API リファレンス
description: ファイルシステムのカプセル化です。
type: docs
weight: 67
url: /ja/java/com.aspose.threed/filesystem/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.io.Closeable
```
public abstract class FileSystem implements Closeable
```

ファイルシステムのカプセル化。Aspose.3D はこれを使用して依存関係の読み書きを行います。**Example:** 以下のコードはファイルのインポート方法と、指定ディレクトリ内の依存ファイルを提供する方法を示しています

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
| [FileSystem()](#FileSystem--) |  |
## Methods

| Method | 説明 |
| --- | --- |
| [close()](#close--) | ファイルシステムを破棄し、そのリソースを解放します。 |
| [createDummyFileSystem()](#createDummyFileSystem--) | ダミーのファイルシステムを作成します。読み書き操作はダミー操作です。 |
| [createLocalFileSystem(String directory)](#createLocalFileSystem-java.lang.String-) | ローカルディレクトリのみアクセス可能な新しい [FileSystem](../../com.aspose.threed/filesystem) を初期化します。 |
| [createMemoryFileSystem()](#createMemoryFileSystem--) | 読み書き操作をメモリにマッピングするメモリベースのファイルシステムを作成します。 |
| [createMemoryFileSystem(HashMap<String,MemoryStream> files)](#createMemoryFileSystem-java.util.HashMap-java.lang.String-com.aspose.threed.MemoryStream--) | 読み書き操作をメモリにマッピングするメモリベースのファイルシステムを作成します。 |
| [createZipFileSystem(Stream stream)](#createZipFileSystem-com.aspose.threed.Stream-) | 指定された zip ファイルまたは zip ストリームへの読み取り専用アクセスを提供するファイルシステムを作成します。 |
| [createZipFileSystem(Stream stream, String baseDir)](#createZipFileSystem-com.aspose.threed.Stream-java.lang.String-) | 指定された zip ファイルまたは zip ストリームへの読み取り専用アクセスを提供するファイルシステムを作成します。 |
| [createZipFileSystem(String fileName)](#createZipFileSystem-java.lang.String-) | 指定された zip ファイルまたは zip ストリームへの読み取り専用アクセスを提供するファイルシステム。 |
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
### FileSystem() {#FileSystem--}
```
public FileSystem()
```


### close() {#close--}
```
public void close()
```


ファイルシステムを破棄し、そのリソースを解放します。

### createDummyFileSystem() {#createDummyFileSystem--}
```
public static FileSystem createDummyFileSystem()
```


ダミーのファイルシステムを作成します。読み書き操作はダミー操作です。

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


ローカルディレクトリのみアクセス可能な新しい [FileSystem](../../com.aspose.threed/filesystem) を初期化します。この FileSystem インスタンス上のすべてのファイルの読み書きは指定ディレクトリにマッピングされます。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| ディレクトリ | java.lang.String | 物理ファイルシステム内のディレクトリを仮想ルートディレクトリとして使用します。 |

**Returns:**
[FileSystem](../../com.aspose.threed/filesystem) - A new instance of file system to provide local file access
### createMemoryFileSystem() {#createMemoryFileSystem--}
```
public static FileSystem createMemoryFileSystem()
```


読み書き操作をメモリにマッピングするメモリベースのファイルシステムを作成します。

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


読み書き操作をメモリにマッピングするメモリベースのファイルシステムを作成します。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| ファイル | java.util.HashMap<java.lang.String,com.aspose.threed.MemoryStream> | これにより仮想ファイルの読み書きが可能になります。 |

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


指定された zip ファイルまたは zip ストリームへの読み取り専用アクセスを提供するファイルシステムを作成します。ファイルシステムはオープン/セーブ操作の後に破棄されます。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| stream | [Stream](../../com.aspose.threed/stream) | zip ファイルにアクセスするためのストリーム |

**Returns:**
[FileSystem](../../com.aspose.threed/filesystem) - A zip file system
### createZipFileSystem(Stream stream, String baseDir) {#createZipFileSystem-com.aspose.threed.Stream-java.lang.String-}
```
public static FileSystem createZipFileSystem(Stream stream, String baseDir)
```


指定された zip ファイルまたは zip ストリームへの読み取り専用アクセスを提供するファイルシステムを作成します。ファイルシステムはオープン/セーブ操作の後に破棄されます。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| stream | [Stream](../../com.aspose.threed/stream) | zip ファイルにアクセスするためのストリーム |
| baseDir | java.lang.String | zip ファイル内のベースディレクトリ。 |

**Returns:**
[FileSystem](../../com.aspose.threed/filesystem) - A zip file system
### createZipFileSystem(String fileName) {#createZipFileSystem-java.lang.String-}
```
public static FileSystem createZipFileSystem(String fileName)
```


指定された zip ファイルまたは zip ストリームへの読み取り専用アクセスを提供するファイルシステムです。ファイルシステムはオープン/セーブ操作の後に破棄されます。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| fileName | java.lang.String | zip ファイルのファイル名。 |

**Returns:**
[FileSystem](../../com.aspose.threed/filesystem) - A zip file system
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
public abstract Stream readFile(String fileName, IOConfig options)
```


依存関係を読み取るためのストリームを作成します。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| fileName | java.lang.String | 読み取り用に開くファイルの名前 |
| options | [IOConfig](../../com.aspose.threed/ioconfig) | 保存またはロードオプション |

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
public abstract Stream writeFile(String fileName, IOConfig options)
```


依存関係を書き込むためのストリームを作成します。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| fileName | java.lang.String | 書き込み用に開くファイルの名前 |
| options | [IOConfig](../../com.aspose.threed/ioconfig) | 保存またはロードオプション |

**Returns:**
[Stream](../../com.aspose.threed/stream) - Stream for writing the file

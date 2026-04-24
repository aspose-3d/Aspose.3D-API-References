---
title: GltfLoadOptions
second_title: Aspose.3D for Java API リファレンス
description: glTF フォーマットのロードオプションです。
type: docs
weight: 73
url: /ja/java/com.aspose.threed/gltfloadoptions/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.IOConfig](../../com.aspose.threed/ioconfig), [com.aspose.threed.LoadOptions](../../com.aspose.threed/loadoptions)
```
public class GltfLoadOptions extends LoadOptions
```

glTF フォーマットのロードオプションです。
## Constructors

| Constructor | 説明 |
| --- | --- |
| [GltfLoadOptions()](#GltfLoadOptions--) | [GltfLoadOptions](../../com.aspose.threed/gltfloadoptions) のコンストラクタ |
## Methods

| Method | 説明 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getEncoding()](#getEncoding--) | テキストベースのファイルのデフォルトエンコーディングを取得します。 |
| [getFileFormat()](#getFileFormat--) | 現在の保存/読み込みオプションで指定されたファイル形式を取得します。 |
| [getFileName()](#getFileName--) | エクスポート/インポートシーンのファイル名。 |
| [getFileSystem()](#getFileSystem--) | ロード/セーブ時に外部依存関係を管理する方法をユーザーが処理できるようにします。 |
| [getFileSystemFactory()](#getFileSystemFactory--) | FileSystem のファクトリークラスを取得します。 |
| [getFlipTexCoordV()](#getFlipTexCoordV--) | メッシュのテクスチャ座標における v(t) 座標を反転します。デフォルト値は true です。 |
| [getLookupPaths()](#getLookupPaths--) | OBJ のような一部のファイルは外部ファイルに依存しており、検索パスにより Aspose.3D が外部ファイルを読み込むために探すことができます。 |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setEncoding(Charset value)](#setEncoding-java.nio.charset.Charset-) | テキストベースのファイルのデフォルトエンコーディングを設定します。 |
| [setFileName(String value)](#setFileName-java.lang.String-) | エクスポート/インポートシーンのファイル名。 |
| [setFileSystem(FileSystem value)](#setFileSystem-com.aspose.threed.FileSystem-) | ロード/セーブ時に外部依存関係を管理する方法をユーザーが処理できるようにします。 |
| [setFileSystemFactory(FileSystemFactory value)](#setFileSystemFactory-com.aspose.threed.FileSystemFactory-) | FileSystem のファクトリークラスを設定します。 |
| [setFlipTexCoordV(boolean value)](#setFlipTexCoordV-boolean-) | メッシュのテクスチャ座標における v(t) 座標を反転します。デフォルト値は true です。 |
| [setLookupPaths(ArrayList<String> value)](#setLookupPaths-java.util.ArrayList-java.lang.String--) | OBJ のような一部のファイルは外部ファイルに依存しており、検索パスにより Aspose.3D が外部ファイルを読み込むために探すことができます。 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### GltfLoadOptions() {#GltfLoadOptions--}
```
public GltfLoadOptions()
```


[GltfLoadOptions](../../com.aspose.threed/gltfloadoptions) のコンストラクタ

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
### getEncoding() {#getEncoding--}
```
public Charset getEncoding()
```


テキストベースのファイルのデフォルトエンコーディングを取得します。デフォルト値は null で、インポーター/エクスポーターが使用するエンコーディングを決定します。

**Returns:**
java.nio.charset.Charset - テキストベースのファイルのデフォルトエンコーディングです。デフォルト値は null で、インポーター/エクスポーターが使用するエンコーディングを決定します。
### getFileFormat() {#getFileFormat--}
```
public FileFormat getFileFormat()
```


現在の保存/読み込みオプションで指定されたファイル形式を取得します。

**Returns:**
[FileFormat](../../com.aspose.threed/fileformat) - the file format that specified in current Save/Load option.
### getFileName() {#getFileName--}
```
public String getFileName()
```


エクスポート/インポートシーンのファイル名です。これはオプションですが、OBJ のマテリアルのような外部アセットをシリアライズする際に便利です。

**Returns:**
java.lang.String - エクスポート/インポートシーンのファイル名です。これはオプションですが、OBJ のマテリアルのような外部アセットをシリアライズする際に便利です。
### getFileSystem() {#getFileSystem--}
```
public FileSystem getFileSystem()
```


ロード/セーブ時に外部依存関係を管理する方法をユーザーが処理できるようにします。

**Returns:**
[FileSystem](../../com.aspose.threed/filesystem) - Allow user to handle how to manage the external dependencies during load/save. **Example:** The default FileSystem is LocalFileSystem, it is not safe in environment like server side, But you can override the file system access by specifying a different implementation. Aspose.3D provides different FileSystem implementation like:

 *  Memory-based file system
 *  Directory-based file system
 *  Dummy file system
 *  Zip file system

また、独自の実装を使用することもできます。

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


FileSystem のファクトリークラスを取得します。デフォルトのファクトリーは com.aspose.threed.LocalFileSystem を作成しますが、サーバー環境には適していません。

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
### getFlipTexCoordV() {#getFlipTexCoordV--}
```
public boolean getFlipTexCoordV()
```


メッシュのテクスチャ座標における v(t) 座標を反転します。デフォルト値は true です。

**Returns:**
boolean - メッシュのテクスチャ座標における v(t) 座標を反転します。デフォルト値は true です。
### getLookupPaths() {#getLookupPaths--}
```
public ArrayList<String> getLookupPaths()
```


OBJ のような一部のファイルは外部ファイルに依存しており、検索パスにより Aspose.3D が外部ファイルを読み込むために探すことができます。

**Returns:**
java.util.ArrayList<java.lang.String> - OBJ のような一部のファイルは外部ファイルに依存しており、検索パスにより Aspose.3D が外部ファイルを探してロードできるようになります。**Example:** 以下のコードは、テクスチャの検索パスを手動で指定する方法を示しており、インポーターが見つけられるようにします

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




### setEncoding(Charset value) {#setEncoding-java.nio.charset.Charset-}
```
public void setEncoding(Charset value)
```


テキストベースのファイルのデフォルトエンコーディングを設定します。デフォルト値は null で、インポーター/エクスポーターが使用するエンコーディングを決定することを意味します。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| 値 | java.nio.charset.Charset | 新しい値 |

### setFileName(String value) {#setFileName-java.lang.String-}
```
public void setFileName(String value)
```


エクスポート/インポートシーンのファイル名です。これはオプションですが、OBJ のマテリアルのような外部アセットをシリアライズする際に便利です。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| 値 | java.lang.String | 新しい値 |

### setFileSystem(FileSystem value) {#setFileSystem-com.aspose.threed.FileSystem-}
```
public void setFileSystem(FileSystem value)
```


ロード/セーブ時に外部依存関係を管理する方法をユーザーが処理できるようにします。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
|  | value | [FileSystem](../../com.aspose.threed/filesystem) | 新しい値 **Example:** デフォルトの FileSystem は LocalFileSystem ですが、サーバー側のような環境では安全ではありません。ただし、別の実装を指定することでファイルシステムへのアクセスをオーバーライドできます。Aspose.3D は次のようなさまざまな FileSystem 実装を提供します： |

 *  Memory-based file system
 *  Directory-based file system
 *  Dummy file system
 *  Zip file system

また、独自の実装を使用することもできます。

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


FileSystem のファクトリークラスを設定します。デフォルトのファクトリーは com.aspose.threed.LocalFileSystem を作成しますが、サーバー環境には適していません。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
|  | value | [FileSystemFactory](../../com.aspose.threed/filesystemfactory) | 新しい値 **Example:** SaveOptions/LoadOptions のデフォルト FileSystem はディレクトリベースのファイルシステムです。IOConfig.FileSystemFactory を介して指定することでデフォルトの実装をオーバーライドできます： |

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

### setFlipTexCoordV(boolean value) {#setFlipTexCoordV-boolean-}
```
public void setFlipTexCoordV(boolean value)
```


メッシュのテクスチャ座標における v(t) 座標を反転します。デフォルト値は true です。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| 値 | boolean | 新しい値 |

### setLookupPaths(ArrayList<String> value) {#setLookupPaths-java.util.ArrayList-java.lang.String--}
```
public void setLookupPaths(ArrayList<String> value)
```


OBJ のような一部のファイルは外部ファイルに依存しており、検索パスにより Aspose.3D が外部ファイルを読み込むために探すことができます。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
|  | 値 | java.util.ArrayList<java.lang.String> | 新しい値 **Example:** 以下のコードは、テクスチャの検索パスを手動で指定する方法を示しており、インポーターが見つけられるようにします |

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


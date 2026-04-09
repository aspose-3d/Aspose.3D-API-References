---
title: Html5SaveOptions
second_title: Aspose.3D for Java API リファレンス
description: HTML5 用の保存オプション
type: docs
weight: 80
url: /ja/java/com.aspose.threed/html5saveoptions/
---

**Inheritance:**
java.lang.Object、[com.aspose.threed.IOConfig](../../com.aspose.threed/ioconfig)、[com.aspose.threed.SaveOptions](../../com.aspose.threed/saveoptions)
```
public class Html5SaveOptions extends SaveOptions
```

HTML5 用の保存オプション
## Constructors

| Constructor | 説明 |
| --- | --- |
| [Html5SaveOptions()](#Html5SaveOptions--) | すべてのデフォルト設定を持つ [Html5SaveOptions](../../com.aspose.threed/html5saveoptions) のコンストラクタです。 |
## Methods

| Method | 説明 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getCameraPosition()](#getCameraPosition--) | カメラの初期位置を取得します。デフォルト値は (10, 10, 10) です。 |
| [getClass()](#getClass--) |  |
| [getEncoding()](#getEncoding--) | テキストベースのファイルのデフォルトエンコーディングを取得します。 |
| [getExportTextures()](#getExportTextures--) | シーンで使用されているテクスチャを出力ディレクトリにコピーしようとします。 |
| [getFarPlane()](#getFarPlane--) | カメラの遠平面を取得します。デフォルト値は 1000 です。 |
| [getFieldOfView()](#getFieldOfView--) | ビューの視野角を取得します。デフォルト値は 45 で、単位は度です。 |
| [getFileFormat()](#getFileFormat--) | 現在の保存/読み込みオプションで指定されたファイル形式を取得します。 |
| [getFileName()](#getFileName--) | エクスポート/インポートシーンのファイル名。 |
| [getFileSystem()](#getFileSystem--) | ロード/セーブ時に外部依存関係を管理する方法をユーザーが処理できるようにします。 |
| [getFileSystemFactory()](#getFileSystemFactory--) | FileSystem のファクトリークラスを取得します。 |
| [getLookAt()](#getLookAt--) | デフォルトの注視点位置を取得します。デフォルト値は (0, 0, 0) です。 |
| [getLookupPaths()](#getLookupPaths--) | OBJ のような一部のファイルは外部ファイルに依存しており、検索パスにより Aspose.3D が外部ファイルを読み込むために探すことができます。 |
| [getNearPlane()](#getNearPlane--) | カメラの近平面を取得します。デフォルト値は 1 です。 |
| [getOrientationBox()](#getOrientationBox--) | オリエンテーションボックスを表示します。 |
| [getShowGrid()](#getShowGrid--) | シーンにグリッドを表示します。 |
| [getShowRulers()](#getShowRulers--) | シーン内でモデルを測定するために x/y/z 軸の定規を表示します。 |
| [getShowUI()](#getShowUI--) | シーンにシンプルな UI を表示します。 |
| [getUpVector()](#getUpVector--) | 上ベクトルを取得します。値は "x"/"y"/"z" のいずれかで、デフォルト値は "y" です。 |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setCameraPosition(Vector3 value)](#setCameraPosition-com.aspose.threed.Vector3-) | カメラの初期位置を設定します。デフォルト値は (10, 10, 10) です。 |
| [setEncoding(Charset value)](#setEncoding-java.nio.charset.Charset-) | テキストベースのファイルのデフォルトエンコーディングを設定します。 |
| [setExportTextures(boolean value)](#setExportTextures-boolean-) | シーンで使用されているテクスチャを出力ディレクトリにコピーしようとします。 |
| [setFarPlane(double value)](#setFarPlane-double-) | カメラの遠平面を設定します。デフォルト値は 1000 です。 |
| [setFieldOfView(double value)](#setFieldOfView-double-) | ビューの視野角を設定します。デフォルト値は 45 で、単位は度です。 |
| [setFileName(String value)](#setFileName-java.lang.String-) | エクスポート/インポートシーンのファイル名。 |
| [setFileSystem(FileSystem value)](#setFileSystem-com.aspose.threed.FileSystem-) | ロード/セーブ時に外部依存関係を管理する方法をユーザーが処理できるようにします。 |
| [setFileSystemFactory(FileSystemFactory value)](#setFileSystemFactory-com.aspose.threed.FileSystemFactory-) | FileSystem のファクトリークラスを設定します。 |
| [setLookAt(Vector3 value)](#setLookAt-com.aspose.threed.Vector3-) | デフォルトの注視点位置を設定します。デフォルト値は (0, 0, 0) です。 |
| [setLookupPaths(ArrayList<String> value)](#setLookupPaths-java.util.ArrayList-java.lang.String--) | OBJ のような一部のファイルは外部ファイルに依存しており、検索パスにより Aspose.3D が外部ファイルを読み込むために探すことができます。 |
| [setNearPlane(double value)](#setNearPlane-double-) | カメラの近平面を設定します。デフォルト値は 1 です。 |
| [setOrientationBox(boolean value)](#setOrientationBox-boolean-) | オリエンテーションボックスを表示します。 |
| [setShowGrid(boolean value)](#setShowGrid-boolean-) | シーンにグリッドを表示します。 |
| [setShowRulers(boolean value)](#setShowRulers-boolean-) | シーン内でモデルを測定するために x/y/z 軸の定規を表示します。 |
| [setShowUI(boolean value)](#setShowUI-boolean-) | シーンにシンプルな UI を表示します。 |
| [setUpVector(String value)](#setUpVector-java.lang.String-) | 上ベクトルを設定します。値は "x"/"y"/"z" のいずれかで、デフォルト値は "y" です。 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Html5SaveOptions() {#Html5SaveOptions--}
```
public Html5SaveOptions()
```


すべてのデフォルト設定を持つ [Html5SaveOptions](../../com.aspose.threed/html5saveoptions) のコンストラクタです。

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
### getCameraPosition() {#getCameraPosition--}
```
public Vector3 getCameraPosition()
```


カメラの初期位置を取得します。デフォルト値は (10, 10, 10) です。

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - the initial position of the camera, default value is (10, 10, 10)
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
### getExportTextures() {#getExportTextures--}
```
public boolean getExportTextures()
```


シーンで使用されているテクスチャを出力ディレクトリにコピーしようとします。

**Returns:**
boolean - シーンで使用されているテクスチャを出力ディレクトリにコピーしようとします。
### getFarPlane() {#getFarPlane--}
```
public double getFarPlane()
```


カメラの遠平面を取得します。デフォルト値は 1000 です。

**Returns:**
double - カメラの遠平面、デフォルト値は 1000 です。
### getFieldOfView() {#getFieldOfView--}
```
public double getFieldOfView()
```


ビューの視野角を取得します。デフォルト値は 45 で、単位は度です。

**Returns:**
double - ビューの視野角、デフォルト値は 45 で、単位は度です。
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
### getLookAt() {#getLookAt--}
```
public Vector3 getLookAt()
```


デフォルトの注視点位置を取得します。デフォルト値は (0, 0, 0) です。

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - the default look at position, default value is (0, 0, 0)
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
### getNearPlane() {#getNearPlane--}
```
public double getNearPlane()
```


カメラの近平面を取得します。デフォルト値は 1 です。

**Returns:**
double - カメラの近平面、デフォルト値は 1 です。
### getOrientationBox() {#getOrientationBox--}
```
public boolean getOrientationBox()
```


方向ボックスを表示します。デフォルト値は true です。

**Returns:**
boolean - 方向ボックスを表示します。デフォルト値は true です。
### getShowGrid() {#getShowGrid--}
```
public boolean getShowGrid()
```


シーンにグリッドを表示します。デフォルト値は true です。

**Returns:**
boolean - シーンにグリッドを表示します。デフォルト値は true です。
### getShowRulers() {#getShowRulers--}
```
public boolean getShowRulers()
```


シーンで x/y/z 軸の定規を表示してモデルを測定します。デフォルト値は false です。

**Returns:**
boolean - シーンで x/y/z 軸の定規を表示してモデルを測定します。デフォルト値は false です。
### getShowUI() {#getShowUI--}
```
public boolean getShowUI()
```


シーンにシンプルな UI を表示します。デフォルト値は true です。

**Returns:**
boolean - シーンにシンプルな UI を表示します。デフォルト値は true です。
### getUpVector() {#getUpVector--}
```
public String getUpVector()
```


上ベクトルを取得します。値は "x"/"y"/"z" のいずれかで、デフォルト値は "y" です。

**Returns:**
java.lang.String - 上ベクトル、値は "x"/"y"/"z" のいずれかで、デフォルト値は "y" です。
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




### setCameraPosition(Vector3 value) {#setCameraPosition-com.aspose.threed.Vector3-}
```
public void setCameraPosition(Vector3 value)
```


カメラの初期位置を設定します。デフォルト値は (10, 10, 10) です。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| value | [Vector3](../../com.aspose.threed/vector3) | 新しい値 |

### setEncoding(Charset value) {#setEncoding-java.nio.charset.Charset-}
```
public void setEncoding(Charset value)
```


テキストベースのファイルのデフォルトエンコーディングを設定します。デフォルト値は null で、インポーター/エクスポーターが使用するエンコーディングを決定することを意味します。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| 値 | java.nio.charset.Charset | 新しい値 |

### setExportTextures(boolean value) {#setExportTextures-boolean-}
```
public void setExportTextures(boolean value)
```


シーンで使用されているテクスチャを出力ディレクトリにコピーしようとします。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| 値 | boolean | 新しい値 |

### setFarPlane(double value) {#setFarPlane-double-}
```
public void setFarPlane(double value)
```


カメラの遠平面を設定します。デフォルト値は 1000 です。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| 値 | double | 新しい値 |

### setFieldOfView(double value) {#setFieldOfView-double-}
```
public void setFieldOfView(double value)
```


ビューの視野角を設定します。デフォルト値は 45 で、単位は度です。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| 値 | double | 新しい値 |

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

### setLookAt(Vector3 value) {#setLookAt-com.aspose.threed.Vector3-}
```
public void setLookAt(Vector3 value)
```


デフォルトの注視点位置を設定します。デフォルト値は (0, 0, 0) です。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| value | [Vector3](../../com.aspose.threed/vector3) | 新しい値 |

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

### setNearPlane(double value) {#setNearPlane-double-}
```
public void setNearPlane(double value)
```


カメラの近平面を設定します。デフォルト値は 1 です。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| 値 | double | 新しい値 |

### setOrientationBox(boolean value) {#setOrientationBox-boolean-}
```
public void setOrientationBox(boolean value)
```


方向ボックスを表示します。デフォルト値は true です。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| 値 | boolean | 新しい値 |

### setShowGrid(boolean value) {#setShowGrid-boolean-}
```
public void setShowGrid(boolean value)
```


シーンにグリッドを表示します。デフォルト値は true です。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| 値 | boolean | 新しい値 |

### setShowRulers(boolean value) {#setShowRulers-boolean-}
```
public void setShowRulers(boolean value)
```


シーンで x/y/z 軸の定規を表示してモデルを測定します。デフォルト値は false です。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| 値 | boolean | 新しい値 |

### setShowUI(boolean value) {#setShowUI-boolean-}
```
public void setShowUI(boolean value)
```


シーンにシンプルな UI を表示します。デフォルト値は true です。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| 値 | boolean | 新しい値 |

### setUpVector(String value) {#setUpVector-java.lang.String-}
```
public void setUpVector(String value)
```


上ベクトルを設定します。値は "x"/"y"/"z" のいずれかで、デフォルト値は "y" です。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| 値 | java.lang.String | 新しい値 |

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


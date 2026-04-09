---
title: PlySaveOptions
second_title: Aspose.3D for Java API リファレンス
description: シーンをPLYファイルとしてエクスポートするための保存オプションです。
type: docs
weight: 131
url: /ja/java/com.aspose.threed/plysaveoptions/
---

**Inheritance:**
java.lang.Object、[com.aspose.threed.IOConfig](../../com.aspose.threed/ioconfig)、[com.aspose.threed.SaveOptions](../../com.aspose.threed/saveoptions)
```
public class PlySaveOptions extends SaveOptions
```

シーンをPLYファイルとしてエクスポートするための保存オプションです。
## Constructors

| Constructor | 説明 |
| --- | --- |
| [PlySaveOptions()](#PlySaveOptions--) | [PlySaveOptions](../../com.aspose.threed/plysaveoptions) のコンストラクタ |
| [PlySaveOptions(FileContentType contentType)](#PlySaveOptions-com.aspose.threed.FileContentType-) | [PlySaveOptions](../../com.aspose.threed/plysaveoptions) のコンストラクタ |
## Methods

| Method | 説明 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAxisSystem()](#getAxisSystem--) | エクスポートされた STL ファイルの軸系を取得します。 |
| [getClass()](#getClass--) |  |
| [getColorComponents()](#getColorComponents--) | 頂点カラーのコンポーネント名で、デフォルト値は ("red", "green", "blue") です。 |
| [getEncoding()](#getEncoding--) | テキストベースのファイルのデフォルトエンコーディングを取得します。 |
| [getExportTextures()](#getExportTextures--) | シーンで使用されているテクスチャを出力ディレクトリにコピーしようとします。 |
| [getFaceElement()](#getFaceElement--) | 面データの要素名、デフォルト値は "face" |
| [getFaceProperty()](#getFaceProperty--) | 面データのプロパティ名、デフォルト値は "vertex\_index" |
| [getFileFormat()](#getFileFormat--) | 現在の保存/読み込みオプションで指定されたファイル形式を取得します。 |
| [getFileName()](#getFileName--) | エクスポート/インポートシーンのファイル名。 |
| [getFileSystem()](#getFileSystem--) | ロード/セーブ時に外部依存関係を管理する方法をユーザーが処理できるようにします。 |
| [getFileSystemFactory()](#getFileSystemFactory--) | FileSystem のファクトリークラスを取得します。 |
| [getFlipCoordinate()](#getFlipCoordinate--) | シーンを保存する際に座標を反転させます、デフォルト値は true |
| [getLookupPaths()](#getLookupPaths--) | OBJ のような一部のファイルは外部ファイルに依存しており、検索パスにより Aspose.3D が外部ファイルを読み込むために探すことができます。 |
| [getNormalComponents()](#getNormalComponents--) | 法線データのコンポーネント名、デフォルト値は ("nx", "ny", "nz") |
| [getPointCloud()](#getPointCloud--) | シーンをポイントクラウドとしてエクスポートします、デフォルト値は false。 |
| [getPositionComponents()](#getPositionComponents--) | 位置データのコンポーネント名、デフォルト値は ("x", "y", "z") |
| [getTextureCoordinateComponents()](#getTextureCoordinateComponents--) | テクスチャ座標データのコンポーネント名、デフォルト値は ("u", "v") |
| [getVertexElement()](#getVertexElement--) | 頂点データの要素名、デフォルト値は "vertex" |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAxisSystem(AxisSystem value)](#setAxisSystem-com.aspose.threed.AxisSystem-) | エクスポートされた STL ファイルの座標系を設定します。 |
| [setColorComponents(Tuple_3<String,String,String> value)](#setColorComponents-com.aspose.threed.Tuple-3-java.lang.String-java.lang.String-java.lang.String--) | 頂点カラーのコンポーネント名で、デフォルト値は ("red", "green", "blue") です。 |
| [setEncoding(Charset value)](#setEncoding-java.nio.charset.Charset-) | テキストベースのファイルのデフォルトエンコーディングを設定します。 |
| [setExportTextures(boolean value)](#setExportTextures-boolean-) | シーンで使用されているテクスチャを出力ディレクトリにコピーしようとします。 |
| [setFaceElement(String value)](#setFaceElement-java.lang.String-) | 面データの要素名、デフォルト値は "face" |
| [setFaceProperty(String value)](#setFaceProperty-java.lang.String-) | 面データのプロパティ名、デフォルト値は "vertex\_index" |
| [setFileName(String value)](#setFileName-java.lang.String-) | エクスポート/インポートシーンのファイル名。 |
| [setFileSystem(FileSystem value)](#setFileSystem-com.aspose.threed.FileSystem-) | ロード/セーブ時に外部依存関係を管理する方法をユーザーが処理できるようにします。 |
| [setFileSystemFactory(FileSystemFactory value)](#setFileSystemFactory-com.aspose.threed.FileSystemFactory-) | FileSystem のファクトリークラスを設定します。 |
| [setFlipCoordinate(boolean value)](#setFlipCoordinate-boolean-) | シーンを保存する際に座標を反転させます、デフォルト値は true |
| [setLookupPaths(ArrayList<String> value)](#setLookupPaths-java.util.ArrayList-java.lang.String--) | OBJ のような一部のファイルは外部ファイルに依存しており、検索パスにより Aspose.3D が外部ファイルを読み込むために探すことができます。 |
| [setNormalComponents(Tuple_3<String,String,String> value)](#setNormalComponents-com.aspose.threed.Tuple-3-java.lang.String-java.lang.String-java.lang.String--) | 法線データのコンポーネント名、デフォルト値は ("nx", "ny", "nz") |
| [setPointCloud(boolean value)](#setPointCloud-boolean-) | シーンをポイントクラウドとしてエクスポートします、デフォルト値は false。 |
| [setPositionComponents(Tuple_3<String,String,String> value)](#setPositionComponents-com.aspose.threed.Tuple-3-java.lang.String-java.lang.String-java.lang.String--) | 位置データのコンポーネント名、デフォルト値は ("x", "y", "z") |
| [setTextureCoordinateComponents(Tuple_2<String,String> value)](#setTextureCoordinateComponents-com.aspose.threed.Tuple-2-java.lang.String-java.lang.String--) | テクスチャ座標データのコンポーネント名、デフォルト値は ("u", "v") |
| [setVertexElement(String value)](#setVertexElement-java.lang.String-) | 頂点データの要素名、デフォルト値は "vertex" |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### PlySaveOptions() {#PlySaveOptions--}
```
public PlySaveOptions()
```


[PlySaveOptions](../../com.aspose.threed/plysaveoptions) のコンストラクタ

### PlySaveOptions(FileContentType contentType) {#PlySaveOptions-com.aspose.threed.FileContentType-}
```
public PlySaveOptions(FileContentType contentType)
```


[PlySaveOptions](../../com.aspose.threed/plysaveoptions) のコンストラクタ

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| contentType | [FileContentType](../../com.aspose.threed/filecontenttype) |  |

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
### getAxisSystem() {#getAxisSystem--}
```
public AxisSystem getAxisSystem()
```


エクスポートされた STL ファイルの軸系を取得します。

**Returns:**
[AxisSystem](../../com.aspose.threed/axissystem) - the axis system in the exported stl file. **Remarks:** FlipCoordinateSystem must be enabled to utilize this feature.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getColorComponents() {#getColorComponents--}
```
public Tuple_3<String,String,String> getColorComponents()
```


頂点カラーのコンポーネント名で、デフォルト値は ("red", "green", "blue") です。

**Returns:**
com.aspose.threed.Tuple_3<java.lang.String,java.lang.String,java.lang.String> - 頂点カラーのコンポーネント名、デフォルト値は ("red", "green", "blue")
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
### getFaceElement() {#getFaceElement--}
```
public String getFaceElement()
```


面データの要素名、デフォルト値は "face"

**Returns:**
java.lang.String - 面データの要素名、デフォルト値は "face"
### getFaceProperty() {#getFaceProperty--}
```
public String getFaceProperty()
```


面データのプロパティ名、デフォルト値は "vertex\_index"

**Returns:**
java.lang.String - 面データのプロパティ名、デフォルト値は "vertex\_index"
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
### getFlipCoordinate() {#getFlipCoordinate--}
```
public boolean getFlipCoordinate()
```


シーンを保存する際に座標を反転させます、デフォルト値は true

**Returns:**
boolean - シーンを保存する際に座標を反転させます、デフォルト値は true
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
### getNormalComponents() {#getNormalComponents--}
```
public Tuple_3<String,String,String> getNormalComponents()
```


法線データのコンポーネント名、デフォルト値は ("nx", "ny", "nz")

**Returns:**
com.aspose.threed.Tuple_3<java.lang.String,java.lang.String,java.lang.String> - 法線データのコンポーネント名、デフォルト値は ("nx", "ny", "nz")
### getPointCloud() {#getPointCloud--}
```
public boolean getPointCloud()
```


シーンをポイントクラウドとしてエクスポートします、デフォルト値は false。

**Returns:**
boolean - シーンをポイントクラウドとしてエクスポートします、デフォルト値は false。
### getPositionComponents() {#getPositionComponents--}
```
public Tuple_3<String,String,String> getPositionComponents()
```


位置データのコンポーネント名、デフォルト値は ("x", "y", "z")

**Returns:**
com.aspose.threed.Tuple_3<java.lang.String,java.lang.String,java.lang.String> - 位置データのコンポーネント名、デフォルト値は ("x", "y", "z")
### getTextureCoordinateComponents() {#getTextureCoordinateComponents--}
```
public Tuple_2<String,String> getTextureCoordinateComponents()
```


テクスチャ座標データのコンポーネント名、デフォルト値は ("u", "v")

**Returns:**
com.aspose.threed.Tuple_2<java.lang.String,java.lang.String> - テクスチャ座標データのコンポーネント名、デフォルト値は ("u", "v")
### getVertexElement() {#getVertexElement--}
```
public String getVertexElement()
```


頂点データの要素名、デフォルト値は "vertex"

**Returns:**
java.lang.String - 頂点データの要素名、デフォルト値は "vertex"
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




### setAxisSystem(AxisSystem value) {#setAxisSystem-com.aspose.threed.AxisSystem-}
```
public void setAxisSystem(AxisSystem value)
```


エクスポートされた STL ファイルの座標系を設定します。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| value | [AxisSystem](../../com.aspose.threed/axissystem) | 新しい値 **備考:** この機能を利用するには FlipCoordinateSystem を有効にする必要があります。 |

### setColorComponents(Tuple_3<String,String,String> value) {#setColorComponents-com.aspose.threed.Tuple-3-java.lang.String-java.lang.String-java.lang.String--}
```
public void setColorComponents(Tuple_3<String,String,String> value)
```


頂点カラーのコンポーネント名で、デフォルト値は ("red", "green", "blue") です。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| 値 | com.aspose.threed.Tuple_3<java.lang.String,java.lang.String,java.lang.String> | 新しい値 |

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

### setFaceElement(String value) {#setFaceElement-java.lang.String-}
```
public void setFaceElement(String value)
```


面データの要素名、デフォルト値は "face"

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| 値 | java.lang.String | 新しい値 |

### setFaceProperty(String value) {#setFaceProperty-java.lang.String-}
```
public void setFaceProperty(String value)
```


面データのプロパティ名、デフォルト値は "vertex\_index"

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| 値 | java.lang.String | 新しい値 |

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

### setFlipCoordinate(boolean value) {#setFlipCoordinate-boolean-}
```
public void setFlipCoordinate(boolean value)
```


シーンを保存する際に座標を反転させます、デフォルト値は true

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

### setNormalComponents(Tuple_3<String,String,String> value) {#setNormalComponents-com.aspose.threed.Tuple-3-java.lang.String-java.lang.String-java.lang.String--}
```
public void setNormalComponents(Tuple_3<String,String,String> value)
```


法線データのコンポーネント名、デフォルト値は ("nx", "ny", "nz")

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| 値 | com.aspose.threed.Tuple_3<java.lang.String,java.lang.String,java.lang.String> | 新しい値 |

### setPointCloud(boolean value) {#setPointCloud-boolean-}
```
public void setPointCloud(boolean value)
```


シーンをポイントクラウドとしてエクスポートします、デフォルト値は false。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| 値 | boolean | 新しい値 |

### setPositionComponents(Tuple_3<String,String,String> value) {#setPositionComponents-com.aspose.threed.Tuple-3-java.lang.String-java.lang.String-java.lang.String--}
```
public void setPositionComponents(Tuple_3<String,String,String> value)
```


位置データのコンポーネント名、デフォルト値は ("x", "y", "z")

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| 値 | com.aspose.threed.Tuple_3<java.lang.String,java.lang.String,java.lang.String> | 新しい値 |

### setTextureCoordinateComponents(Tuple_2<String,String> value) {#setTextureCoordinateComponents-com.aspose.threed.Tuple-2-java.lang.String-java.lang.String--}
```
public void setTextureCoordinateComponents(Tuple_2<String,String> value)
```


テクスチャ座標データのコンポーネント名、デフォルト値は ("u", "v")

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| 値 | com.aspose.threed.Tuple_2<java.lang.String,java.lang.String> | 新しい値 |

### setVertexElement(String value) {#setVertexElement-java.lang.String-}
```
public void setVertexElement(String value)
```


頂点データの要素名、デフォルト値は "vertex"

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


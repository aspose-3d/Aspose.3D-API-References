---
title: GltfSaveOptions
second_title: Aspose.3D for Java API リファレンス
description: glTF フォーマットの保存オプションです。
type: docs
weight: 74
url: /ja/java/com.aspose.threed/gltfsaveoptions/
---

**Inheritance:**
java.lang.Object、[com.aspose.threed.IOConfig](../../com.aspose.threed/ioconfig)、[com.aspose.threed.SaveOptions](../../com.aspose.threed/saveoptions)
```
public class GltfSaveOptions extends SaveOptions
```

glTF フォーマットの保存オプションです。
## Constructors

| Constructor | 説明 |
| --- | --- |
| [GltfSaveOptions(FileContentType contentType)](#GltfSaveOptions-com.aspose.threed.FileContentType-) | [GltfSaveOptions](../../com.aspose.threed/gltfsaveoptions) のコンストラクタ |
| [GltfSaveOptions(FileFormat format)](#GltfSaveOptions-com.aspose.threed.FileFormat-) | [GltfSaveOptions](../../com.aspose.threed/gltfsaveoptions) のコンストラクタ |
## Methods

| Method | 説明 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getApplyUnitScale()](#getApplyUnitScale--) | メッシュに [AssetInfo.getUnitScaleFactor](../../com.aspose.threed/assetinfo\#getUnitScaleFactor) を適用します。 |
| [getBufferFile()](#getBufferFile--) | バイナリデータを保存するために使用される外部バッファファイルのファイル名です。 |
| [getClass()](#getClass--) |  |
| [getDracoCompression()](#getDracoCompression--) | draco 圧縮を有効にするかどうかを取得します |
| [getEmbedAssets()](#getEmbedAssets--) | 外部アセットをすべて base64 でエンコードし、ASCII モードで単一ファイルに埋め込みます。デフォルト値は false です。 |
| [getEncoding()](#getEncoding--) | テキストベースのファイルのデフォルトエンコーディングを取得します。 |
| [getExportTextures()](#getExportTextures--) | シーンで使用されているテクスチャを出力ディレクトリにコピーしようとします。 |
| [getExternalDracoEncoder()](#getExternalDracoEncoder--) | 外部 draco エンコーダーを使用して draco 圧縮速度を高速化します。 |
| [getFallbackNormal()](#getFallbackNormal--) | GLTF2 エクスポーターが無効な法線を検出したとき、検証を回避するために元の値の代わりにこれが使用されます。 |
| [getFileFormat()](#getFileFormat--) | 現在の保存/読み込みオプションで指定されたファイル形式を取得します。 |
| [getFileName()](#getFileName--) | エクスポート/インポートシーンのファイル名。 |
| [getFileSystem()](#getFileSystem--) | ロード/セーブ時に外部依存関係を管理する方法をユーザーが処理できるようにします。 |
| [getFileSystemFactory()](#getFileSystemFactory--) | FileSystem のファクトリークラスを取得します。 |
| [getFlipTexCoordV()](#getFlipTexCoordV--) | テクスチャ座標 v(t) 成分を反転させます。デフォルト値は true です。 |
| [getImageFormat()](#getImageFormat--) | 標準の glTF はテクスチャ形式として PNG/JPG のみをサポートしており、このオプションはエクスポート中に Aspose.3D が非標準画像をサポートされている形式に変換する方法を案内します。 |
| [getLookupPaths()](#getLookupPaths--) | OBJ のような一部のファイルは外部ファイルに依存しており、検索パスにより Aspose.3D が外部ファイルを読み込むために探すことができます。 |
| [getMaterialConverter()](#getMaterialConverter--) | ジオメトリのマテリアルを PBR マテリアルに変換するカスタムコンバータ。このプロパティが未設定の場合、glTF 2.0 エクスポーターは標準マテリアルを自動的に PBR マテリアルに変換します。 |
| [getPrettyPrint()](#getPrettyPrint--) | GLTF ファイルの JSON コンテンツは人間が読みやすいようにインデントされます。デフォルト値は false です。 |
| [getSaveExtras()](#getSaveExtras--) | シーンオブジェクトの動的プロパティを生成された glTF ファイルの 'extra' フィールドに保存します。 |
| [getUseCommonMaterials()](#getUseCommonMaterials--) | マテリアルを KHR 共通マテリアル拡張を使用してシリアライズします。デフォルト値は false です。 |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setApplyUnitScale(boolean value)](#setApplyUnitScale-boolean-) | メッシュに [AssetInfo.getUnitScaleFactor](../../com.aspose.threed/assetinfo\#getUnitScaleFactor) を適用します。 |
| [setBufferFile(String value)](#setBufferFile-java.lang.String-) | バイナリデータを保存するために使用される外部バッファファイルのファイル名です。 |
| [setDracoCompression(boolean value)](#setDracoCompression-boolean-) | draco 圧縮を有効にするかどうかを設定します。 |
| [setEmbedAssets(boolean value)](#setEmbedAssets-boolean-) | 外部アセットをすべて base64 でエンコードし、ASCII モードで単一ファイルに埋め込みます。デフォルト値は false です。 |
| [setEncoding(Charset value)](#setEncoding-java.nio.charset.Charset-) | テキストベースのファイルのデフォルトエンコーディングを設定します。 |
| [setExportTextures(boolean value)](#setExportTextures-boolean-) | シーンで使用されているテクスチャを出力ディレクトリにコピーしようとします。 |
| [setExternalDracoEncoder(String value)](#setExternalDracoEncoder-java.lang.String-) | 外部 draco エンコーダーを使用して draco 圧縮速度を高速化します。 |
| [setFallbackNormal(Vector3 value)](#setFallbackNormal-com.aspose.threed.Vector3-) | GLTF2 エクスポーターが無効な法線を検出したとき、検証を回避するために元の値の代わりにこれが使用されます。 |
| [setFileName(String value)](#setFileName-java.lang.String-) | エクスポート/インポートシーンのファイル名。 |
| [setFileSystem(FileSystem value)](#setFileSystem-com.aspose.threed.FileSystem-) | ロード/セーブ時に外部依存関係を管理する方法をユーザーが処理できるようにします。 |
| [setFileSystemFactory(FileSystemFactory value)](#setFileSystemFactory-com.aspose.threed.FileSystemFactory-) | FileSystem のファクトリークラスを設定します。 |
| [setFlipTexCoordV(boolean value)](#setFlipTexCoordV-boolean-) | テクスチャ座標 v(t) 成分を反転させます。デフォルト値は true です。 |
| [setImageFormat(GltfEmbeddedImageFormat value)](#setImageFormat-com.aspose.threed.GltfEmbeddedImageFormat-) | 標準の glTF はテクスチャ形式として PNG/JPG のみをサポートしており、このオプションはエクスポート中に Aspose.3D が非標準画像をサポートされている形式に変換する方法を案内します。 |
| [setLookupPaths(ArrayList<String> value)](#setLookupPaths-java.util.ArrayList-java.lang.String--) | OBJ のような一部のファイルは外部ファイルに依存しており、検索パスにより Aspose.3D が外部ファイルを読み込むために探すことができます。 |
| [setMaterialConverter(MaterialConverter value)](#setMaterialConverter-com.aspose.threed.MaterialConverter-) | ジオメトリのマテリアルを PBR マテリアルに変換するカスタムコンバータ。このプロパティが未設定の場合、glTF 2.0 エクスポーターは標準マテリアルを自動的に PBR マテリアルに変換します。 |
| [setPrettyPrint(boolean value)](#setPrettyPrint-boolean-) | GLTF ファイルの JSON コンテンツは人間が読みやすいようにインデントされます。デフォルト値は false です。 |
| [setSaveExtras(boolean value)](#setSaveExtras-boolean-) | シーンオブジェクトの動的プロパティを生成された glTF ファイルの 'extra' フィールドに保存します。 |
| [setUseCommonMaterials(boolean value)](#setUseCommonMaterials-boolean-) | マテリアルを KHR 共通マテリアル拡張を使用してシリアライズします。デフォルト値は false です。 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### GltfSaveOptions(FileContentType contentType) {#GltfSaveOptions-com.aspose.threed.FileContentType-}
```
public GltfSaveOptions(FileContentType contentType)
```


[GltfSaveOptions](../../com.aspose.threed/gltfsaveoptions) のコンストラクタ

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| contentType | [FileContentType](../../com.aspose.threed/filecontenttype) |  |

### GltfSaveOptions(FileFormat format) {#GltfSaveOptions-com.aspose.threed.FileFormat-}
```
public GltfSaveOptions(FileFormat format)
```


[GltfSaveOptions](../../com.aspose.threed/gltfsaveoptions) のコンストラクタ

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| format | [FileFormat](../../com.aspose.threed/fileformat) |  |

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
### getApplyUnitScale() {#getApplyUnitScale--}
```
public boolean getApplyUnitScale()
```


メッシュに [AssetInfo.getUnitScaleFactor](../../com.aspose.threed/assetinfo\#getUnitScaleFactor) を適用します。デフォルト値は false です。

**Returns:**
boolean - メッシュに [AssetInfo.getUnitScaleFactor](../../com.aspose.threed/assetinfo\#getUnitScaleFactor) を適用します。デフォルト値は false です。
### getBufferFile() {#getBufferFile--}
```
public String getBufferFile()
```


バイナリデータを格納する外部バッファファイルのファイル名。このファイルが指定されていない場合、Aspose.3D が名前を生成します。バイナリモードで glTF をエクスポートする際は無視されます。

**Returns:**
java.lang.String - バイナリデータを格納する外部バッファファイルのファイル名。このファイルが指定されていない場合、Aspose.3D が名前を生成します。バイナリモードで glTF をエクスポートする際は無視されます。
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getDracoCompression() {#getDracoCompression--}
```
public boolean getDracoCompression()
```


draco 圧縮を有効にするかどうかを取得します

**Returns:**
boolean - draco 圧縮を有効にするかどうか
### getEmbedAssets() {#getEmbedAssets--}
```
public boolean getEmbedAssets()
```


外部アセットをすべて base64 でエンコードし、ASCII モードで単一ファイルに埋め込みます。デフォルト値は false です。

**Returns:**
boolean - すべての外部アセットを base64 でエンコードし、ASCII モードの単一ファイルに埋め込みます。デフォルト値は false です。
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
### getExternalDracoEncoder() {#getExternalDracoEncoder--}
```
public String getExternalDracoEncoder()
```


外部 draco エンコーダーを使用して draco 圧縮速度を高速化します。

**Returns:**
java.lang.String - draco 圧縮速度を高速化するために外部 draco エンコーダを使用します。**Remarks:** Aspose.3D はメッシュを draco 形式にエンコードするために新しいサブプロセスを作成します。自己責任で使用してください。
### getFallbackNormal() {#getFallbackNormal--}
```
public Vector3 getFallbackNormal()
```


GLTF2 エクスポーターが無効な法線を検出した場合、検証を回避するために元の値の代わりにこれが使用されます。デフォルト値は (0, 1, 0) です。

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - When GLTF2 exporter detected an invalid normal, this will be used instead of its original value to bypass the validation. Default value is (0, 1, 0)
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


テクスチャ座標 v(t) 成分を反転させます。デフォルト値は true です。

**Returns:**
boolean - テクスチャ座標の v(t) 成分を反転します。デフォルト値は true です。
### getImageFormat() {#getImageFormat--}
```
public GltfEmbeddedImageFormat getImageFormat()
```


標準の glTF はテクスチャ形式として PNG/JPG のみをサポートしており、このオプションはエクスポート中に Aspose.3D が非標準画像をサポートされている形式に変換する方法を案内します。デフォルト値は [GltfEmbeddedImageFormat.PNG](../../com.aspose.threed/gltfembeddedimageformat\#PNG) です。

**Returns:**
[GltfEmbeddedImageFormat](../../com.aspose.threed/gltfembeddedimageformat) - Standard glTF only supports PNG/JPG as its texture format, this option will guide how Aspose.3D convert the non-standard images to supported format during the exporting. Default value is [GltfEmbeddedImageFormat.PNG](../../com.aspose.threed/gltfembeddedimageformat\#PNG)
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
### getMaterialConverter() {#getMaterialConverter--}
```
public MaterialConverter getMaterialConverter()
```


ジオメトリのマテリアルを PBR マテリアルに変換するカスタムコンバータ。このプロパティが未設定の場合、glTF 2.0 エクスポーターは標準マテリアルを自動的に PBR マテリアルに変換します。デフォルト値は null です。このプロパティはシーンを glTF 2.0 ファイルにエクスポートする際に使用されます。

**Returns:**
[MaterialConverter](../../com.aspose.threed/materialconverter) - Custom converter to convert the geometry's material to PBR material If this is unassigned, glTF 2.0 exporter will automatically convert the standard material to PBR material. Default value is null This property is used when exporting a scene to a glTF 2.0 file.
### getPrettyPrint() {#getPrettyPrint--}
```
public boolean getPrettyPrint()
```


GLTF ファイルの JSON コンテンツは人間が読みやすいようにインデントされます。デフォルト値は false です。

**Returns:**
boolean - GLTF ファイルの JSON コンテンツは人間が読みやすいようにインデントされます。デフォルト値は false です。
### getSaveExtras() {#getSaveExtras--}
```
public boolean getSaveExtras()
```


シーンオブジェクトの動的プロパティを生成された glTF ファイルの 'extra' フィールドに保存します。これはアプリケーション固有のデータを提供するのに便利です。デフォルト値は false です。

**Returns:**
boolean - シーンオブジェクトの動的プロパティを生成された glTF ファイルの 'extra' フィールドに保存します。これはアプリケーション固有のデータを提供するのに便利です。デフォルト値は false です。
### getUseCommonMaterials() {#getUseCommonMaterials--}
```
public boolean getUseCommonMaterials()
```


KHR 共通マテリアル拡張を使用してマテリアルをシリアライズします。デフォルト値は false です。これを false に設定すると、[getExportShaders](../../com.aspose.threed/gltfsaveoptions\#getExportShaders) がある場合に Aspose.3D が頂点/フラグメントシェーダのセットをエクスポートします。

**Returns:**
boolean - KHR 共通マテリアル拡張を使用してマテリアルをシリアライズします。デフォルト値は false です。これを false に設定すると、[getExportShaders](../../com.aspose.threed/gltfsaveoptions\#getExportShaders) がある場合に Aspose.3D が頂点/フラグメントシェーダのセットをエクスポートします。**Remarks:** このプロパティは glTF 1.0 のみで機能します。
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




### setApplyUnitScale(boolean value) {#setApplyUnitScale-boolean-}
```
public void setApplyUnitScale(boolean value)
```


メッシュに [AssetInfo.getUnitScaleFactor](../../com.aspose.threed/assetinfo\#getUnitScaleFactor) を適用します。デフォルト値は false です。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| 値 | boolean | 新しい値 |

### setBufferFile(String value) {#setBufferFile-java.lang.String-}
```
public void setBufferFile(String value)
```


バイナリデータを格納する外部バッファファイルのファイル名。このファイルが指定されていない場合、Aspose.3D が名前を生成します。バイナリモードで glTF をエクスポートする際は無視されます。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| 値 | java.lang.String | 新しい値 |

### setDracoCompression(boolean value) {#setDracoCompression-boolean-}
```
public void setDracoCompression(boolean value)
```


draco 圧縮を有効にするかどうかを設定します。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| 値 | boolean | 新しい値 |

### setEmbedAssets(boolean value) {#setEmbedAssets-boolean-}
```
public void setEmbedAssets(boolean value)
```


外部アセットをすべて base64 でエンコードし、ASCII モードで単一ファイルに埋め込みます。デフォルト値は false です。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| 値 | boolean | 新しい値 |

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

### setExternalDracoEncoder(String value) {#setExternalDracoEncoder-java.lang.String-}
```
public void setExternalDracoEncoder(String value)
```


外部 draco エンコーダーを使用して draco 圧縮速度を高速化します。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| 値 | java.lang.String | 新しい値 **Remarks:** Aspose.3D はメッシュを draco 形式にエンコードするために新しいサブプロセスを作成します。自己責任で使用してください。 |

### setFallbackNormal(Vector3 value) {#setFallbackNormal-com.aspose.threed.Vector3-}
```
public void setFallbackNormal(Vector3 value)
```


GLTF2 エクスポーターが無効な法線を検出した場合、検証を回避するために元の値の代わりにこれが使用されます。デフォルト値は (0, 1, 0) です。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| value | [Vector3](../../com.aspose.threed/vector3) | 新しい値 |

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


テクスチャ座標 v(t) 成分を反転させます。デフォルト値は true です。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| 値 | boolean | 新しい値 |

### setImageFormat(GltfEmbeddedImageFormat value) {#setImageFormat-com.aspose.threed.GltfEmbeddedImageFormat-}
```
public void setImageFormat(GltfEmbeddedImageFormat value)
```


標準の glTF はテクスチャ形式として PNG/JPG のみをサポートしており、このオプションはエクスポート中に Aspose.3D が非標準画像をサポートされている形式に変換する方法を案内します。デフォルト値は [GltfEmbeddedImageFormat.PNG](../../com.aspose.threed/gltfembeddedimageformat\#PNG) です。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| value | [GltfEmbeddedImageFormat](../../com.aspose.threed/gltfembeddedimageformat) | 新しい値 |

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

### setMaterialConverter(MaterialConverter value) {#setMaterialConverter-com.aspose.threed.MaterialConverter-}
```
public void setMaterialConverter(MaterialConverter value)
```


ジオメトリのマテリアルを PBR マテリアルに変換するカスタムコンバータ。このプロパティが未設定の場合、glTF 2.0 エクスポーターは標準マテリアルを自動的に PBR マテリアルに変換します。デフォルト値は null です。このプロパティはシーンを glTF 2.0 ファイルにエクスポートする際に使用されます。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| value | [MaterialConverter](../../com.aspose.threed/materialconverter) | 新しい値 |

### setPrettyPrint(boolean value) {#setPrettyPrint-boolean-}
```
public void setPrettyPrint(boolean value)
```


GLTF ファイルの JSON コンテンツは人間が読みやすいようにインデントされます。デフォルト値は false です。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| 値 | boolean | 新しい値 |

### setSaveExtras(boolean value) {#setSaveExtras-boolean-}
```
public void setSaveExtras(boolean value)
```


シーンオブジェクトの動的プロパティを生成された glTF ファイルの 'extra' フィールドに保存します。これはアプリケーション固有のデータを提供するのに便利です。デフォルト値は false です。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| 値 | boolean | 新しい値 |

### setUseCommonMaterials(boolean value) {#setUseCommonMaterials-boolean-}
```
public void setUseCommonMaterials(boolean value)
```


KHR 共通マテリアル拡張を使用してマテリアルをシリアライズします。デフォルト値は false です。これを false に設定すると、[getExportShaders](../../com.aspose.threed/gltfsaveoptions\#getExportShaders) がある場合に Aspose.3D が頂点/フラグメントシェーダのセットをエクスポートします。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| 値 | boolean | 新しい値 **Remarks:** このプロパティは glTF 1.0 のみで機能します。 |

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


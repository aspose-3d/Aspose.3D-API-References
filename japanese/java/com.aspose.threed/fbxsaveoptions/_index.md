---
title: FbxSaveOptions
second_title: Aspose.3D for Java API リファレンス
description: Fbx ファイルの保存オプションです。
type: docs
weight: 63
url: /ja/java/com.aspose.threed/fbxsaveoptions/
---

**Inheritance:**
java.lang.Object、[com.aspose.threed.IOConfig](../../com.aspose.threed/ioconfig)、[com.aspose.threed.SaveOptions](../../com.aspose.threed/saveoptions)
```
public class FbxSaveOptions extends SaveOptions
```

Fbx ファイルの保存オプションです。
## Constructors

| Constructor | 説明 |
| --- | --- |
| [FbxSaveOptions(FileFormat format)](#FbxSaveOptions-com.aspose.threed.FileFormat-) | [FbxSaveOptions](../../com.aspose.threed/fbxsaveoptions) を初期化します |
| [FbxSaveOptions(FileContentType contentType)](#FbxSaveOptions-com.aspose.threed.FileContentType-) | 最新のサポートバージョンを使用して [FbxSaveOptions](../../com.aspose.threed/fbxsaveoptions) を初期化します。 |
## Methods

| Method | 説明 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getEmbedTextures()](#getEmbedTextures--) | テクスチャを最終出力ファイルに埋め込むかどうかを取得します。 |
| [getEnableCompression()](#getEnableCompression--) | FBX ファイル内の大きなバイナリデータを圧縮します（例: |
| [getEncoding()](#getEncoding--) | テキストベースのファイルのデフォルトエンコーディングを取得します。 |
| [getExportLegacyMaterialProperties()](#getExportLegacyMaterialProperties--) | レガシー マテリアル プロパティをエクスポートするかどうかを取得します（下位互換性のために使用）。 |
| [getExportTextures()](#getExportTextures--) | シーンで使用されているテクスチャを出力ディレクトリにコピーしようとします。 |
| [getFileFormat()](#getFileFormat--) | 現在の保存/読み込みオプションで指定されたファイル形式を取得します。 |
| [getFileName()](#getFileName--) | エクスポート/インポートシーンのファイル名。 |
| [getFileSystem()](#getFileSystem--) | ロード/セーブ時に外部依存関係を管理する方法をユーザーが処理できるようにします。 |
| [getFileSystemFactory()](#getFileSystemFactory--) | FileSystem のファクトリークラスを取得します。 |
| [getFoldRepeatedCurveData()](#getFoldRepeatedCurveData--) | 最後のデータの参照カウントを増やすことで、繰り返し使用される曲線データを再利用するかどうかを取得します。 |
| [getGenerateVertexElementMaterial()](#getGenerateVertexElementMaterial--) | 添付されたノードにマテリアルが含まれている場合、ジオメトリに対して常に [VertexElementMaterial](../../com.aspose.threed/vertexelementmaterial) を生成するかどうかを取得します。 |
| [getLookupPaths()](#getLookupPaths--) | OBJ のような一部のファイルは外部ファイルに依存しており、検索パスにより Aspose.3D が外部ファイルを読み込むために探すことができます。 |
| [getReusePrimitiveMesh()](#getReusePrimitiveMesh--) | 同じパラメータを持つプリミティブに対してメッシュを再利用します。これにより、CAD ファイルからインポートされたような多数のプリミティブ形状で構成されたシーンの FBX 出力サイズが大幅に削減されます。 |
| [getVideoForTexture()](#getVideoForTexture--) | FBX としてエクスポートする際に、[Texture](../../com.aspose.threed/texture) のビデオ インスタンスを生成するかどうかを取得します。 |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setEmbedTextures(boolean value)](#setEmbedTextures-boolean-) | テクスチャを最終出力ファイルに埋め込むかどうかを設定します。 |
| [setEnableCompression(boolean value)](#setEnableCompression-boolean-) | FBX ファイル内の大きなバイナリデータを圧縮します（例: |
| [setEncoding(Charset value)](#setEncoding-java.nio.charset.Charset-) | テキストベースのファイルのデフォルトエンコーディングを設定します。 |
| [setExportLegacyMaterialProperties(boolean value)](#setExportLegacyMaterialProperties-boolean-) | レガシー マテリアル プロパティをエクスポートするかどうかを設定します（下位互換性のために使用）。 |
| [setExportTextures(boolean value)](#setExportTextures-boolean-) | シーンで使用されているテクスチャを出力ディレクトリにコピーしようとします。 |
| [setFileName(String value)](#setFileName-java.lang.String-) | エクスポート/インポートシーンのファイル名。 |
| [setFileSystem(FileSystem value)](#setFileSystem-com.aspose.threed.FileSystem-) | ロード/セーブ時に外部依存関係を管理する方法をユーザーが処理できるようにします。 |
| [setFileSystemFactory(FileSystemFactory value)](#setFileSystemFactory-com.aspose.threed.FileSystemFactory-) | FileSystem のファクトリークラスを設定します。 |
| [setFoldRepeatedCurveData(Boolean value)](#setFoldRepeatedCurveData-java.lang.Boolean-) | 最後のデータの参照カウントを増やすことで、繰り返し使用される曲線データを再利用するかどうかを設定します。 |
| [setGenerateVertexElementMaterial(boolean value)](#setGenerateVertexElementMaterial-boolean-) | 添付されたノードにマテリアルが含まれている場合、ジオメトリに対して常に [VertexElementMaterial](../../com.aspose.threed/vertexelementmaterial) を生成するかどうかを設定します。 |
| [setLookupPaths(ArrayList<String> value)](#setLookupPaths-java.util.ArrayList-java.lang.String--) | OBJ のような一部のファイルは外部ファイルに依存しており、検索パスにより Aspose.3D が外部ファイルを読み込むために探すことができます。 |
| [setReusePrimitiveMesh(boolean value)](#setReusePrimitiveMesh-boolean-) | 同じパラメータを持つプリミティブに対してメッシュを再利用します。これにより、CAD ファイルからインポートされたような多数のプリミティブ形状で構成されたシーンの FBX 出力サイズが大幅に削減されます。 |
| [setVideoForTexture(boolean value)](#setVideoForTexture-boolean-) | FBX としてエクスポートする際に、[Texture](../../com.aspose.threed/texture) のビデオ インスタンスを生成するかどうかを設定します。 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### FbxSaveOptions(FileFormat format) {#FbxSaveOptions-com.aspose.threed.FileFormat-}
```
public FbxSaveOptions(FileFormat format)
```


[FbxSaveOptions](../../com.aspose.threed/fbxsaveoptions) を初期化します

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| format | [FileFormat](../../com.aspose.threed/fileformat) | [getFileFormat](../../com.aspose.threed/fbxsaveoptions\#getFileFormat) のインスタンスで、有効な FBX フォーマットである必要があります。 |

### FbxSaveOptions(FileContentType contentType) {#FbxSaveOptions-com.aspose.threed.FileContentType-}
```
public FbxSaveOptions(FileContentType contentType)
```


最新のサポートバージョンを使用して [FbxSaveOptions](../../com.aspose.threed/fbxsaveoptions) を初期化します。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| contentType | [FileContentType](../../com.aspose.threed/filecontenttype) | バイナリまたは ASCII |

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
### getEmbedTextures() {#getEmbedTextures--}
```
public boolean getEmbedTextures()
```


テクスチャを最終出力ファイルに埋め込むかどうかを取得します。FBX エクスポーターは [IOConfig.getFileSystem](../../com.aspose.threed/ioconfig\#getFileSystem) からテクスチャの生データを検索し、ファイルを最終 FBX ファイルに埋め込みます。デフォルト値は false です。

**Returns:**
boolean - テクスチャを最終出力ファイルに埋め込むかどうか。FBX エクスポーターは [IOConfig.getFileSystem](../../com.aspose.threed/ioconfig\#getFileSystem) からテクスチャの生データを検索し、ファイルを最終 FBX ファイルに埋め込みます。デフォルト値は false です。
### getEnableCompression() {#getEnableCompression--}
```
public boolean getEnableCompression()
```


FBX ファイル内の大きなバイナリデータ（例: アニメーション データ、コントロール ポイント、頂点要素データ、インデックス）を圧縮します。デフォルト値は true です。

**Returns:**
boolean - FBX ファイル内の大きなバイナリデータ（例: アニメーション データ、コントロール ポイント、頂点要素データ、インデックス）を圧縮します。デフォルト値は true です。
### getEncoding() {#getEncoding--}
```
public Charset getEncoding()
```


テキストベースのファイルのデフォルトエンコーディングを取得します。デフォルト値は null で、インポーター/エクスポーターが使用するエンコーディングを決定します。

**Returns:**
java.nio.charset.Charset - テキストベースのファイルのデフォルトエンコーディングです。デフォルト値は null で、インポーター/エクスポーターが使用するエンコーディングを決定します。
### getExportLegacyMaterialProperties() {#getExportLegacyMaterialProperties--}
```
public boolean getExportLegacyMaterialProperties()
```


レガシー マテリアル プロパティをエクスポートするかどうかを取得します（下位互換性のために使用）。このオプションはデフォルトでオンになっています。

**Returns:**
boolean - レガシー マテリアル プロパティをエクスポートするかどうか（下位互換性のために使用）。このオプションはデフォルトでオンになっています。
### getExportTextures() {#getExportTextures--}
```
public boolean getExportTextures()
```


シーンで使用されているテクスチャを出力ディレクトリにコピーしようとします。

**Returns:**
boolean - シーンで使用されているテクスチャを出力ディレクトリにコピーしようとします。
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
### getFoldRepeatedCurveData() {#getFoldRepeatedCurveData--}
```
public Boolean getFoldRepeatedCurveData()
```


最後のデータの参照カウントを増やすことで、繰り返し使用される曲線データを再利用するかどうかを取得します。

**Returns:**
java.lang.Boolean - 最後のデータの参照カウントを増やすことで、繰り返し使用される曲線データを再利用するかどうか
### getGenerateVertexElementMaterial() {#getGenerateVertexElementMaterial--}
```
public boolean getGenerateVertexElementMaterial()
```


添付されたノードにマテリアルが含まれている場合、ジオメトリに対して常に [VertexElementMaterial](../../com.aspose.threed/vertexelementmaterial) を生成するかどうかを取得します。この設定はデフォルトでオフになっています。

**Returns:**
boolean - 添付されたノードにマテリアルが含まれている場合、ジオメトリに対して常に [VertexElementMaterial](../../com.aspose.threed/vertexelementmaterial) を生成するかどうか。この設定はデフォルトでオフになっています。
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
### getReusePrimitiveMesh() {#getReusePrimitiveMesh--}
```
public boolean getReusePrimitiveMesh()
```


同じパラメータを持つプリミティブに対してメッシュを再利用します。これにより、CAD ファイルからインポートされたような多数のプリミティブ形状で構成されたシーンの FBX 出力サイズが大幅に削減されます。デフォルト値は false です。

**Returns:**
boolean - 同じパラメータを持つプリミティブのメッシュを再利用します。これにより、CAD ファイルからインポートされたような多数のプリミティブ形状で構成されたシーンの FBX 出力サイズが大幅に削減されます。デフォルト値は false です
### getVideoForTexture() {#getVideoForTexture--}
```
public boolean getVideoForTexture()
```


FBX としてエクスポートする際に、[Texture](../../com.aspose.threed/texture) のビデオ インスタンスを生成するかどうかを取得します。

**Returns:**
boolean - FBX としてエクスポートする際に [Texture](../../com.aspose.threed/texture) の Video インスタンスを生成するかどうかです。
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




### setEmbedTextures(boolean value) {#setEmbedTextures-boolean-}
```
public void setEmbedTextures(boolean value)
```


テクスチャを最終出力ファイルに埋め込むかどうかを設定します。FBX エクスポーターは [IOConfig.getFileSystem](../../com.aspose.threed/ioconfig\#getFileSystem) からテクスチャの生データを取得し、最終 FBX ファイルに埋め込みます。デフォルト値は false です。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| 値 | boolean | 新しい値 |

### setEnableCompression(boolean value) {#setEnableCompression-boolean-}
```
public void setEnableCompression(boolean value)
```


FBX ファイル内の大きなバイナリデータ（例: アニメーション データ、コントロール ポイント、頂点要素データ、インデックス）を圧縮します。デフォルト値は true です。

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

### setExportLegacyMaterialProperties(boolean value) {#setExportLegacyMaterialProperties-boolean-}
```
public void setExportLegacyMaterialProperties(boolean value)
```


レガシー マテリアル プロパティをエクスポートするかどうかを設定します。これは後方互換性のために使用されます。このオプションはデフォルトで有効になっています。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| 値 | boolean | 新しい値 |

### setExportTextures(boolean value) {#setExportTextures-boolean-}
```
public void setExportTextures(boolean value)
```


シーンで使用されているテクスチャを出力ディレクトリにコピーしようとします。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| 値 | boolean | 新しい値 |

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

### setFoldRepeatedCurveData(Boolean value) {#setFoldRepeatedCurveData-java.lang.Boolean-}
```
public void setFoldRepeatedCurveData(Boolean value)
```


最後のデータの参照カウントを増やすことで、繰り返し使用される曲線データを再利用するかどうかを設定します。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| 値 | java.lang.Boolean | 新しい値 |

### setGenerateVertexElementMaterial(boolean value) {#setGenerateVertexElementMaterial-boolean-}
```
public void setGenerateVertexElementMaterial(boolean value)
```


添付されたノードにマテリアルが含まれている場合、ジオメトリに対して常に [VertexElementMaterial](../../com.aspose.threed/vertexelementmaterial) を生成するかどうかを設定します。デフォルトでは無効になっています。

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

### setReusePrimitiveMesh(boolean value) {#setReusePrimitiveMesh-boolean-}
```
public void setReusePrimitiveMesh(boolean value)
```


同じパラメータを持つプリミティブに対してメッシュを再利用します。これにより、CAD ファイルからインポートされたような多数のプリミティブ形状で構成されたシーンの FBX 出力サイズが大幅に削減されます。デフォルト値は false です。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| 値 | boolean | 新しい値 |

### setVideoForTexture(boolean value) {#setVideoForTexture-boolean-}
```
public void setVideoForTexture(boolean value)
```


FBX としてエクスポートする際に、[Texture](../../com.aspose.threed/texture) のビデオ インスタンスを生成するかどうかを設定します。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| 値 | boolean | 新しい値 |

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


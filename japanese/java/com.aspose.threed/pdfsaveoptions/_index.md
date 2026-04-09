---
title: PdfSaveOptions
second_title: Aspose.3D for Java API リファレンス
description: PDF エクスポート時の保存オプションです。
type: docs
weight: 125
url: /ja/java/com.aspose.threed/pdfsaveoptions/
---

**Inheritance:**
java.lang.Object、[com.aspose.threed.IOConfig](../../com.aspose.threed/ioconfig)、[com.aspose.threed.SaveOptions](../../com.aspose.threed/saveoptions)
```
public class PdfSaveOptions extends SaveOptions
```

PDF エクスポート時の保存オプションです。
## Constructors

| Constructor | 説明 |
| --- | --- |
| [PdfSaveOptions()](#PdfSaveOptions--) | [PdfSaveOptions](../../com.aspose.threed/pdfsaveoptions) のコンストラクタ |
## Methods

| Method | 説明 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAuxiliaryColor()](#getAuxiliaryColor--) | 3D コンテンツのレンダリング時に使用される補助色を取得します。 |
| [getBackgroundColor()](#getBackgroundColor--) | PDF ファイル内の 3D ビューの背景色。 |
| [getClass()](#getClass--) |  |
| [getEmbedTextures()](#getEmbedTextures--) | 外部テクスチャを PDF ファイルに埋め込みます。デフォルト値は false です。 |
| [getEncoding()](#getEncoding--) | テキストベースのファイルのデフォルトエンコーディングを取得します。 |
| [getExportTextures()](#getExportTextures--) | シーンで使用されているテクスチャを出力ディレクトリにコピーしようとします。 |
| [getFaceColor()](#getFaceColor--) | 3D コンテンツのレンダリング時に使用される面の色を取得します。 |
| [getFileFormat()](#getFileFormat--) | 現在の保存/読み込みオプションで指定されたファイル形式を取得します。 |
| [getFileName()](#getFileName--) | エクスポート/インポートシーンのファイル名。 |
| [getFileSystem()](#getFileSystem--) | ロード/セーブ時に外部依存関係を管理する方法をユーザーが処理できるようにします。 |
| [getFileSystemFactory()](#getFileSystemFactory--) | FileSystem のファクトリークラスを取得します。 |
| [getFlipCoordinateSystem()](#getFlipCoordinateSystem--) | エクスポート時にシーンの座標系を反転させるかどうかを取得します。 |
| [getLightingScheme()](#getLightingScheme--) | LightingScheme は 3D アートワークに適用するライティングを指定します。 |
| [getLookupPaths()](#getLookupPaths--) | OBJ のような一部のファイルは外部ファイルに依存しており、検索パスにより Aspose.3D が外部ファイルを読み込むために探すことができます。 |
| [getRenderMode()](#getRenderMode--) | レンダーモードは 3D アートワークがレンダリングされるスタイルを指定します。 |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAuxiliaryColor(Vector3 value)](#setAuxiliaryColor-com.aspose.threed.Vector3-) | 3D コンテンツのレンダリング時に使用される補助色を設定します。 |
| [setBackgroundColor(Vector3 value)](#setBackgroundColor-com.aspose.threed.Vector3-) | PDF ファイル内の 3D ビューの背景色。 |
| [setEmbedTextures(boolean value)](#setEmbedTextures-boolean-) | 外部テクスチャを PDF ファイルに埋め込みます。デフォルト値は false です。 |
| [setEncoding(Charset value)](#setEncoding-java.nio.charset.Charset-) | テキストベースのファイルのデフォルトエンコーディングを設定します。 |
| [setExportTextures(boolean value)](#setExportTextures-boolean-) | シーンで使用されているテクスチャを出力ディレクトリにコピーしようとします。 |
| [setFaceColor(Vector3 value)](#setFaceColor-com.aspose.threed.Vector3-) | 3D コンテンツのレンダリング時に使用される面の色を設定します。 |
| [setFileName(String value)](#setFileName-java.lang.String-) | エクスポート/インポートシーンのファイル名。 |
| [setFileSystem(FileSystem value)](#setFileSystem-com.aspose.threed.FileSystem-) | ロード/セーブ時に外部依存関係を管理する方法をユーザーが処理できるようにします。 |
| [setFileSystemFactory(FileSystemFactory value)](#setFileSystemFactory-com.aspose.threed.FileSystemFactory-) | FileSystem のファクトリークラスを設定します。 |
| [setFlipCoordinateSystem(boolean value)](#setFlipCoordinateSystem-boolean-) | エクスポート時にシーンの座標系を反転させるように設定します。 |
| [setLightingScheme(PdfLightingScheme value)](#setLightingScheme-com.aspose.threed.PdfLightingScheme-) | LightingScheme は 3D アートワークに適用するライティングを指定します。 |
| [setLookupPaths(ArrayList<String> value)](#setLookupPaths-java.util.ArrayList-java.lang.String--) | OBJ のような一部のファイルは外部ファイルに依存しており、検索パスにより Aspose.3D が外部ファイルを読み込むために探すことができます。 |
| [setRenderMode(PdfRenderMode value)](#setRenderMode-com.aspose.threed.PdfRenderMode-) | レンダーモードは 3D アートワークがレンダリングされるスタイルを指定します。 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### PdfSaveOptions() {#PdfSaveOptions--}
```
public PdfSaveOptions()
```


[PdfSaveOptions](../../com.aspose.threed/pdfsaveoptions) のコンストラクタ

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
### getAuxiliaryColor() {#getAuxiliaryColor--}
```
public Vector3 getAuxiliaryColor()
```


3D コンテンツのレンダリング時に使用される補助色を取得します。この色の解釈は [getRenderMode](../../com.aspose.threed/pdfsaveoptions\#getRenderMode) に依存します。

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - the auxiliary color to be used when rendering the 3D content. The interpretation of this color depends on the [getRenderMode](../../com.aspose.threed/pdfsaveoptions\#getRenderMode)
### getBackgroundColor() {#getBackgroundColor--}
```
public Vector3 getBackgroundColor()
```


PDF ファイル内の 3D ビューの背景色。

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - Background color of the 3D view in PDF file.
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


外部テクスチャを PDF ファイルに埋め込みます。デフォルト値は false です。

**Returns:**
boolean - 外部テクスチャを PDF ファイルに埋め込みます。デフォルト値は false です。
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
### getFaceColor() {#getFaceColor--}
```
public Vector3 getFaceColor()
```


3D コンテンツのレンダリング時に使用される面の色を取得します。このプロパティは、[getRenderMode](../../com.aspose.threed/pdfsaveoptions\#getRenderMode) が Illustration の値を持つ場合にのみ関連します。

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - the face color to be used when rendering the 3D content. This is only relevant only when the [getRenderMode](../../com.aspose.threed/pdfsaveoptions\#getRenderMode) has a value of Illustration.
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
### getFlipCoordinateSystem() {#getFlipCoordinateSystem--}
```
public boolean getFlipCoordinateSystem()
```


エクスポート時にシーンの座標系を反転させるかどうかを取得します。

**Returns:**
boolean - エクスポート時にシーンの座標系を反転させます。
### getLightingScheme() {#getLightingScheme--}
```
public PdfLightingScheme getLightingScheme()
```


LightingScheme は 3D アートワークに適用するライティングを指定します。

**Returns:**
[PdfLightingScheme](../../com.aspose.threed/pdflightingscheme) - LightingScheme specifies the lighting to apply to 3D artwork.
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
### getRenderMode() {#getRenderMode--}
```
public PdfRenderMode getRenderMode()
```


レンダーモードは 3D アートワークがレンダリングされるスタイルを指定します。

**Returns:**
[PdfRenderMode](../../com.aspose.threed/pdfrendermode) - Render mode specifies the style in which the 3D artwork is rendered.
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




### setAuxiliaryColor(Vector3 value) {#setAuxiliaryColor-com.aspose.threed.Vector3-}
```
public void setAuxiliaryColor(Vector3 value)
```


3D コンテンツのレンダリング時に使用される補助色を設定します。この色の解釈は [getRenderMode](../../com.aspose.threed/pdfsaveoptions\#getRenderMode) に依存します。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| value | [Vector3](../../com.aspose.threed/vector3) | 新しい値 |

### setBackgroundColor(Vector3 value) {#setBackgroundColor-com.aspose.threed.Vector3-}
```
public void setBackgroundColor(Vector3 value)
```


PDF ファイル内の 3D ビューの背景色。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| value | [Vector3](../../com.aspose.threed/vector3) | 新しい値 |

### setEmbedTextures(boolean value) {#setEmbedTextures-boolean-}
```
public void setEmbedTextures(boolean value)
```


外部テクスチャを PDF ファイルに埋め込みます。デフォルト値は false です。

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

### setFaceColor(Vector3 value) {#setFaceColor-com.aspose.threed.Vector3-}
```
public void setFaceColor(Vector3 value)
```


3D コンテンツのレンダリング時に使用される面の色を設定します。このプロパティは、[getRenderMode](../../com.aspose.threed/pdfsaveoptions\#getRenderMode) が Illustration の値を持つ場合にのみ関連します。

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

### setFlipCoordinateSystem(boolean value) {#setFlipCoordinateSystem-boolean-}
```
public void setFlipCoordinateSystem(boolean value)
```


エクスポート時にシーンの座標系を反転させるように設定します。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| 値 | boolean | 新しい値 |

### setLightingScheme(PdfLightingScheme value) {#setLightingScheme-com.aspose.threed.PdfLightingScheme-}
```
public void setLightingScheme(PdfLightingScheme value)
```


LightingScheme は 3D アートワークに適用するライティングを指定します。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| value | [PdfLightingScheme](../../com.aspose.threed/pdflightingscheme) | 新しい値 |

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

### setRenderMode(PdfRenderMode value) {#setRenderMode-com.aspose.threed.PdfRenderMode-}
```
public void setRenderMode(PdfRenderMode value)
```


レンダーモードは 3D アートワークがレンダリングされるスタイルを指定します。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| value | [PdfRenderMode](../../com.aspose.threed/pdfrendermode) | 新しい値 |

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


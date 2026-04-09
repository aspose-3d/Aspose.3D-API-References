---
title: DracoSaveOptions
second_title: Aspose.3D for Java API リファレンス
description: Google Draco ファイルの保存オプション
type: docs
weight: 47
url: /ja/java/com.aspose.threed/dracosaveoptions/
---

**Inheritance:**
java.lang.Object、[com.aspose.threed.IOConfig](../../com.aspose.threed/ioconfig)、[com.aspose.threed.SaveOptions](../../com.aspose.threed/saveoptions)
```
public class DracoSaveOptions extends SaveOptions
```

Google Draco ファイルの保存オプション
## Constructors

| Constructor | 説明 |
| --- | --- |
| [DracoSaveOptions()](#DracoSaveOptions--) | draco ファイルを保存するためのデフォルト構成を作成する。 |
## Methods

| Method | 説明 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getApplyUnitScale()](#getApplyUnitScale--) | メッシュに [AssetInfo.getUnitScaleFactor](../../com.aspose.threed/assetinfo\#getUnitScaleFactor) を適用します。 |
| [getClass()](#getClass--) |  |
| [getColorBits()](#getColorBits--) | 頂点カラーの量子化ビット数、デフォルト値は 10 です |
| [getCompressionLevel()](#getCompressionLevel--) | 圧縮レベル、デフォルト値は [DracoCompressionLevel.STANDARD](../../com.aspose.threed/dracocompressionlevel\#STANDARD) です |
| [getEncoding()](#getEncoding--) | テキストベースのファイルのデフォルトエンコーディングを取得します。 |
| [getExportTextures()](#getExportTextures--) | シーンで使用されているテクスチャを出力ディレクトリにコピーしようとします。 |
| [getFileFormat()](#getFileFormat--) | 現在の保存/読み込みオプションで指定されたファイル形式を取得します。 |
| [getFileName()](#getFileName--) | エクスポート/インポートシーンのファイル名。 |
| [getFileSystem()](#getFileSystem--) | ロード/セーブ時に外部依存関係を管理する方法をユーザーが処理できるようにします。 |
| [getFileSystemFactory()](#getFileSystemFactory--) | FileSystem のファクトリークラスを取得します。 |
| [getLookupPaths()](#getLookupPaths--) | OBJ のような一部のファイルは外部ファイルに依存しており、検索パスにより Aspose.3D が外部ファイルを読み込むために探すことができます。 |
| [getNormalBits()](#getNormalBits--) | 法線ベクトルの量子化ビット数、デフォルト値は 10 です |
| [getPointCloud()](#getPointCloud--) | シーンを点群としてエクスポートします、デフォルト値は false です。 |
| [getPositionBits()](#getPositionBits--) | 位置の量子化ビット数、デフォルト値は 14 です |
| [getTextureCoordinateBits()](#getTextureCoordinateBits--) | テクスチャ座標の量子化ビット数、デフォルト値は 12 です |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setApplyUnitScale(boolean value)](#setApplyUnitScale-boolean-) | メッシュに [AssetInfo.getUnitScaleFactor](../../com.aspose.threed/assetinfo\#getUnitScaleFactor) を適用します。 |
| [setColorBits(int value)](#setColorBits-int-) | 頂点カラーの量子化ビット数、デフォルト値は 10 です |
| [setCompressionLevel(DracoCompressionLevel value)](#setCompressionLevel-com.aspose.threed.DracoCompressionLevel-) | 圧縮レベル、デフォルト値は [DracoCompressionLevel.STANDARD](../../com.aspose.threed/dracocompressionlevel\#STANDARD) です |
| [setEncoding(Charset value)](#setEncoding-java.nio.charset.Charset-) | テキストベースのファイルのデフォルトエンコーディングを設定します。 |
| [setExportTextures(boolean value)](#setExportTextures-boolean-) | シーンで使用されているテクスチャを出力ディレクトリにコピーしようとします。 |
| [setFileName(String value)](#setFileName-java.lang.String-) | エクスポート/インポートシーンのファイル名。 |
| [setFileSystem(FileSystem value)](#setFileSystem-com.aspose.threed.FileSystem-) | ロード/セーブ時に外部依存関係を管理する方法をユーザーが処理できるようにします。 |
| [setFileSystemFactory(FileSystemFactory value)](#setFileSystemFactory-com.aspose.threed.FileSystemFactory-) | FileSystem のファクトリークラスを設定します。 |
| [setLookupPaths(ArrayList<String> value)](#setLookupPaths-java.util.ArrayList-java.lang.String--) | OBJ のような一部のファイルは外部ファイルに依存しており、検索パスにより Aspose.3D が外部ファイルを読み込むために探すことができます。 |
| [setNormalBits(int value)](#setNormalBits-int-) | 法線ベクトルの量子化ビット数、デフォルト値は 10 です |
| [setPointCloud(boolean value)](#setPointCloud-boolean-) | シーンを点群としてエクスポートします、デフォルト値は false です。 |
| [setPositionBits(int value)](#setPositionBits-int-) | 位置の量子化ビット数、デフォルト値は 14 です |
| [setTextureCoordinateBits(int value)](#setTextureCoordinateBits-int-) | テクスチャ座標の量子化ビット数、デフォルト値は 12 です |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### DracoSaveOptions() {#DracoSaveOptions--}
```
public DracoSaveOptions()
```


draco ファイルを保存するためのデフォルト構成を作成する。

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
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getColorBits() {#getColorBits--}
```
public int getColorBits()
```


頂点カラーの量子化ビット数、デフォルト値は 10 です

**Returns:**
int - 頂点カラーの量子化ビット数、デフォルト値は 10 です
### getCompressionLevel() {#getCompressionLevel--}
```
public DracoCompressionLevel getCompressionLevel()
```


圧縮レベル、デフォルト値は [DracoCompressionLevel.STANDARD](../../com.aspose.threed/dracocompressionlevel\#STANDARD) です

**Returns:**
[DracoCompressionLevel](../../com.aspose.threed/dracocompressionlevel) - Compression level, default value is [DracoCompressionLevel.STANDARD](../../com.aspose.threed/dracocompressionlevel\#STANDARD)
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
### getNormalBits() {#getNormalBits--}
```
public int getNormalBits()
```


法線ベクトルの量子化ビット数、デフォルト値は 10 です

**Returns:**
int - 法線ベクトルの量子化ビット数、デフォルト値は 10 です
### getPointCloud() {#getPointCloud--}
```
public boolean getPointCloud()
```


シーンを点群としてエクスポートします、デフォルト値は false です。

**Returns:**
boolean - シーンを点群としてエクスポートします、デフォルト値は false です。
### getPositionBits() {#getPositionBits--}
```
public int getPositionBits()
```


位置の量子化ビット数、デフォルト値は 14 です

**Returns:**
int - 位置の量子化ビット数、デフォルト値は 14 です
### getTextureCoordinateBits() {#getTextureCoordinateBits--}
```
public int getTextureCoordinateBits()
```


テクスチャ座標の量子化ビット数、デフォルト値は 12 です

**Returns:**
int - テクスチャ座標の量子化ビット数、デフォルト値は 12 です
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

### setColorBits(int value) {#setColorBits-int-}
```
public void setColorBits(int value)
```


頂点カラーの量子化ビット数、デフォルト値は 10 です

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| 値 | int | 新しい値 |

### setCompressionLevel(DracoCompressionLevel value) {#setCompressionLevel-com.aspose.threed.DracoCompressionLevel-}
```
public void setCompressionLevel(DracoCompressionLevel value)
```


圧縮レベル、デフォルト値は [DracoCompressionLevel.STANDARD](../../com.aspose.threed/dracocompressionlevel\#STANDARD) です

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| value | [DracoCompressionLevel](../../com.aspose.threed/dracocompressionlevel) | 新しい値 |

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

### setNormalBits(int value) {#setNormalBits-int-}
```
public void setNormalBits(int value)
```


法線ベクトルの量子化ビット数、デフォルト値は 10 です

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| 値 | int | 新しい値 |

### setPointCloud(boolean value) {#setPointCloud-boolean-}
```
public void setPointCloud(boolean value)
```


シーンを点群としてエクスポートします、デフォルト値は false です。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| 値 | boolean | 新しい値 |

### setPositionBits(int value) {#setPositionBits-int-}
```
public void setPositionBits(int value)
```


位置の量子化ビット数、デフォルト値は 14 です

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| 値 | int | 新しい値 |

### setTextureCoordinateBits(int value) {#setTextureCoordinateBits-int-}
```
public void setTextureCoordinateBits(int value)
```


テクスチャ座標の量子化ビット数、デフォルト値は 12 です

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| 値 | int | 新しい値 |

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


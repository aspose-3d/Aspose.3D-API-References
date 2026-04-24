---
title: Discreet3dsSaveOptions
second_title: Aspose.3D for Java API リファレンス
description: 3DSファイルの保存オプション。
type: docs
weight: 44
url: /ja/java/com.aspose.threed/discreet3dssaveoptions/
---

**Inheritance:**
java.lang.Object、[com.aspose.threed.IOConfig](../../com.aspose.threed/ioconfig)、[com.aspose.threed.SaveOptions](../../com.aspose.threed/saveoptions)
```
public class Discreet3dsSaveOptions extends SaveOptions
```

3DSファイルの保存オプション。
## Constructors

| Constructor | 説明 |
| --- | --- |
| [Discreet3dsSaveOptions()](#Discreet3dsSaveOptions--) | [Discreet3dsSaveOptions](../../com.aspose.threed/discreet3dssaveoptions) のコンストラクタ |
## Methods

| Method | 説明 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getDuplicatedNameCounterBase()](#getDuplicatedNameCounterBase--) | 重複した名前の新しい名前を生成する際に使用されるカウンタで、デフォルト値は 2 です。 |
| [getDuplicatedNameCounterFormat()](#getDuplicatedNameCounterFormat--) | 重複カウンタの形式で、デフォルト値は空文字列です。 |
| [getDuplicatedNameSeparator()](#getDuplicatedNameSeparator--) | オブジェクト名と重複カウンタの間の区切り文字で、デフォルト値は "\_" です。 |
| [getEncoding()](#getEncoding--) | テキストベースのファイルのデフォルトエンコーディングを取得します。 |
| [getExportCamera()](#getExportCamera--) | シーン内のすべてのカメラをエクスポートするかどうかを取得します。 |
| [getExportLight()](#getExportLight--) | シーン内のすべてのライトをエクスポートするかどうかを取得します。 |
| [getExportTextures()](#getExportTextures--) | シーンで使用されているテクスチャを出力ディレクトリにコピーしようとします。 |
| [getFileFormat()](#getFileFormat--) | 現在の保存/読み込みオプションで指定されたファイル形式を取得します。 |
| [getFileName()](#getFileName--) | エクスポート/インポートシーンのファイル名。 |
| [getFileSystem()](#getFileSystem--) | ロード/セーブ時に外部依存関係を管理する方法をユーザーが処理できるようにします。 |
| [getFileSystemFactory()](#getFileSystemFactory--) | FileSystem のファクトリークラスを取得します。 |
| [getFlipCoordinateSystem()](#getFlipCoordinateSystem--) | インポート/エクスポート時に制御点/法線の座標系の反転を取得します。 |
| [getGammaCorrectedColor()](#getGammaCorrectedColor--) | 3ds ファイルは同じ属性に対して元の色とガンマ補正された色の両方を含む場合があります。この設定を true にすると、可能な限りガンマ補正された色が使用され、そうでなければ Aspose.3D は元の色を使用しようとします。 |
| [getHighPreciseColor()](#getHighPreciseColor--) | この設定が true の場合、生成された 3ds ファイルは高精度のカラーを使用します。つまり、赤・緑・青の各チャンネルが 32 ビット浮動小数点で表されます。 |
| [getLookupPaths()](#getLookupPaths--) | OBJ のような一部のファイルは外部ファイルに依存しており、検索パスにより Aspose.3D が外部ファイルを読み込むために探すことができます。 |
| [getMasterScale()](#getMasterScale--) | エクスポート時に使用されるマスタースケールを取得します。 |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setDuplicatedNameCounterBase(int value)](#setDuplicatedNameCounterBase-int-) | 重複した名前の新しい名前を生成する際に使用されるカウンタで、デフォルト値は 2 です。 |
| [setDuplicatedNameCounterFormat(String value)](#setDuplicatedNameCounterFormat-java.lang.String-) | 重複カウンタの形式で、デフォルト値は空文字列です。 |
| [setDuplicatedNameSeparator(String value)](#setDuplicatedNameSeparator-java.lang.String-) | オブジェクト名と重複カウンタの間の区切り文字で、デフォルト値は "\_" です。 |
| [setEncoding(Charset value)](#setEncoding-java.nio.charset.Charset-) | テキストベースのファイルのデフォルトエンコーディングを設定します。 |
| [setExportCamera(boolean value)](#setExportCamera-boolean-) | シーン内のすべてのカメラをエクスポートするかどうかを設定します。 |
| [setExportLight(boolean value)](#setExportLight-boolean-) | シーン内のすべてのライトをエクスポートするかどうかを設定します。 |
| [setExportTextures(boolean value)](#setExportTextures-boolean-) | シーンで使用されているテクスチャを出力ディレクトリにコピーしようとします。 |
| [setFileName(String value)](#setFileName-java.lang.String-) | エクスポート/インポートシーンのファイル名。 |
| [setFileSystem(FileSystem value)](#setFileSystem-com.aspose.threed.FileSystem-) | ロード/セーブ時に外部依存関係を管理する方法をユーザーが処理できるようにします。 |
| [setFileSystemFactory(FileSystemFactory value)](#setFileSystemFactory-com.aspose.threed.FileSystemFactory-) | FileSystem のファクトリークラスを設定します。 |
| [setFlipCoordinateSystem(boolean value)](#setFlipCoordinateSystem-boolean-) | インポート/エクスポート時に制御点/法線の座標系を反転させます。 |
| [setGammaCorrectedColor(boolean value)](#setGammaCorrectedColor-boolean-) | 3ds ファイルは同じ属性に対して元の色とガンマ補正された色の両方を含む場合があります。この設定を true にすると、可能な限りガンマ補正された色が使用され、そうでなければ Aspose.3D は元の色を使用しようとします。 |
| [setHighPreciseColor(boolean value)](#setHighPreciseColor-boolean-) | この設定が true の場合、生成された 3ds ファイルは高精度のカラーを使用します。つまり、赤・緑・青の各チャンネルが 32 ビット浮動小数点で表されます。 |
| [setLookupPaths(ArrayList<String> value)](#setLookupPaths-java.util.ArrayList-java.lang.String--) | OBJ のような一部のファイルは外部ファイルに依存しており、検索パスにより Aspose.3D が外部ファイルを読み込むために探すことができます。 |
| [setMasterScale(double value)](#setMasterScale-double-) | エクスポート時に使用されるマスタースケールを設定します。 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Discreet3dsSaveOptions() {#Discreet3dsSaveOptions--}
```
public Discreet3dsSaveOptions()
```


[Discreet3dsSaveOptions](../../com.aspose.threed/discreet3dssaveoptions) のコンストラクタ

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
### getDuplicatedNameCounterBase() {#getDuplicatedNameCounterBase--}
```
public int getDuplicatedNameCounterBase()
```


重複した名前の新しい名前を生成する際に使用されるカウンタで、デフォルト値は 2 です。

**Returns:**
int - 重複した名前の新しい名前を生成する際に使用されるカウンタで、デフォルト値は 2 です。
### getDuplicatedNameCounterFormat() {#getDuplicatedNameCounterFormat--}
```
public String getDuplicatedNameCounterFormat()
```


重複カウンタの形式で、デフォルト値は空文字列です。

**Returns:**
java.lang.String - 重複カウンタの形式で、デフォルト値は空文字列です。
### getDuplicatedNameSeparator() {#getDuplicatedNameSeparator--}
```
public String getDuplicatedNameSeparator()
```


オブジェクト名と重複カウンタの間の区切り文字で、デフォルト値は "\\_" です。シーンに同じ名前のオブジェクトが存在する場合、Aspose.3D 3DS エクスポーターはオブジェクトに別の名前を生成します。例えば、"Box" という名前のノードが2つあると、最初のノードは "Box" という名前になり、2番目のノードはデフォルト設定を使用して新しい名前 "Box\\_2" が付与されます。

**Returns:**
java.lang.String - オブジェクト名と重複カウンタの間の区切り文字で、デフォルト値は "\\_" です。シーンに同じ名前のオブジェクトが存在する場合、Aspose.3D 3DS エクスポーターはオブジェクトに別の名前を生成します。例えば、"Box" という名前のノードが2つあると、最初のノードは "Box" という名前になり、2番目のノードはデフォルト設定を使用して新しい名前 "Box\\_2" が付与されます。
### getEncoding() {#getEncoding--}
```
public Charset getEncoding()
```


テキストベースのファイルのデフォルトエンコーディングを取得します。デフォルト値は null で、インポーター/エクスポーターが使用するエンコーディングを決定します。

**Returns:**
java.nio.charset.Charset - テキストベースのファイルのデフォルトエンコーディングです。デフォルト値は null で、インポーター/エクスポーターが使用するエンコーディングを決定します。
### getExportCamera() {#getExportCamera--}
```
public boolean getExportCamera()
```


シーン内のすべてのカメラをエクスポートするかどうかを取得します。

**Returns:**
boolean - シーン内のすべてのカメラをエクスポートするかどうか。
### getExportLight() {#getExportLight--}
```
public boolean getExportLight()
```


シーン内のすべてのライトをエクスポートするかどうかを取得します。

**Returns:**
boolean - シーン内のすべてのライトをエクスポートするかどうか。
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
### getFlipCoordinateSystem() {#getFlipCoordinateSystem--}
```
public boolean getFlipCoordinateSystem()
```


インポート/エクスポート時に制御点/法線の座標系の反転を取得します。

**Returns:**
boolean - インポート/エクスポート時に制御点/法線の座標系を反転します。
### getGammaCorrectedColor() {#getGammaCorrectedColor--}
```
public boolean getGammaCorrectedColor()
```


3ds ファイルは同じ属性に対して元の色とガンマ補正された色の両方を含む場合があります。この設定を true にすると、可能な限りガンマ補正された色が使用され、そうでなければ Aspose.3D は元の色を使用しようとします。

**Returns:**
boolean - 3ds ファイルは同じ属性に対して元の色とガンマ補正された色の両方を含む場合があります。この設定を true にすると、可能な限りガンマ補正された色が使用され、そうでなければ Aspose.3D は元の色を使用しようとします。
### getHighPreciseColor() {#getHighPreciseColor--}
```
public boolean getHighPreciseColor()
```


この設定が true の場合、生成された 3ds ファイルは高精度カラーを使用し、赤/緑/青の各チャンネルが 32 ビット浮動小数点になります。false の場合、生成ファイルは 24 ビットカラーを使用し、各チャンネルが 8 ビットバイトになります。デフォルト値は false で、すべてのアプリケーションが高精度カラーをサポートしているわけではないためです。

**Returns:**
boolean - この設定が true の場合、生成された 3ds ファイルは高精度カラーを使用し、赤/緑/青の各チャンネルが 32 ビット浮動小数点になります。false の場合、生成ファイルは 24 ビットカラーを使用し、各チャンネルが 8 ビットバイトになります。デフォルト値は false で、すべてのアプリケーションが高精度カラーをサポートしているわけではありません。
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
### getMasterScale() {#getMasterScale--}
```
public double getMasterScale()
```


エクスポート時に使用されるマスタースケールを取得します。

**Returns:**
double - エクスポート時に使用されるマスタースケールです。
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




### setDuplicatedNameCounterBase(int value) {#setDuplicatedNameCounterBase-int-}
```
public void setDuplicatedNameCounterBase(int value)
```


重複した名前の新しい名前を生成する際に使用されるカウンタで、デフォルト値は 2 です。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| 値 | int | 新しい値 |

### setDuplicatedNameCounterFormat(String value) {#setDuplicatedNameCounterFormat-java.lang.String-}
```
public void setDuplicatedNameCounterFormat(String value)
```


重複カウンタの形式で、デフォルト値は空文字列です。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| 値 | java.lang.String | 新しい値 |

### setDuplicatedNameSeparator(String value) {#setDuplicatedNameSeparator-java.lang.String-}
```
public void setDuplicatedNameSeparator(String value)
```


オブジェクト名と重複カウンタの間の区切り文字で、デフォルト値は "\\_" です。シーンに同じ名前のオブジェクトが存在する場合、Aspose.3D 3DS エクスポーターはオブジェクトに別の名前を生成します。例えば、"Box" という名前のノードが2つあると、最初のノードは "Box" という名前になり、2番目のノードはデフォルト設定を使用して新しい名前 "Box\\_2" が付与されます。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| 値 | java.lang.String | 新しい値 |

### setEncoding(Charset value) {#setEncoding-java.nio.charset.Charset-}
```
public void setEncoding(Charset value)
```


テキストベースのファイルのデフォルトエンコーディングを設定します。デフォルト値は null で、インポーター/エクスポーターが使用するエンコーディングを決定することを意味します。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| 値 | java.nio.charset.Charset | 新しい値 |

### setExportCamera(boolean value) {#setExportCamera-boolean-}
```
public void setExportCamera(boolean value)
```


シーン内のすべてのカメラをエクスポートするかどうかを設定します。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| 値 | boolean | 新しい値 |

### setExportLight(boolean value) {#setExportLight-boolean-}
```
public void setExportLight(boolean value)
```


シーン内のすべてのライトをエクスポートするかどうかを設定します。

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

### setFlipCoordinateSystem(boolean value) {#setFlipCoordinateSystem-boolean-}
```
public void setFlipCoordinateSystem(boolean value)
```


インポート/エクスポート時に制御点/法線の座標系を反転させます。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| 値 | boolean | 新しい値 |

### setGammaCorrectedColor(boolean value) {#setGammaCorrectedColor-boolean-}
```
public void setGammaCorrectedColor(boolean value)
```


3ds ファイルは同じ属性に対して元の色とガンマ補正された色の両方を含む場合があります。この設定を true にすると、可能な限りガンマ補正された色が使用され、そうでなければ Aspose.3D は元の色を使用しようとします。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| 値 | boolean | 新しい値 |

### setHighPreciseColor(boolean value) {#setHighPreciseColor-boolean-}
```
public void setHighPreciseColor(boolean value)
```


この設定が true の場合、生成された 3ds ファイルは高精度カラーを使用し、赤/緑/青の各チャンネルが 32 ビット浮動小数点になります。false の場合、生成ファイルは 24 ビットカラーを使用し、各チャンネルが 8 ビットバイトになります。デフォルト値は false で、すべてのアプリケーションが高精度カラーをサポートしているわけではないためです。

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

### setMasterScale(double value) {#setMasterScale-double-}
```
public void setMasterScale(double value)
```


エクスポート時に使用されるマスタースケールを設定します。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| 値 | double | 新しい値 |

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


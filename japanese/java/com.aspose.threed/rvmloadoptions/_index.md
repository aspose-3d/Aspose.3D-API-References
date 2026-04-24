---
title: RvmLoadOptions
second_title: Aspose.3D for Java API リファレンス
description: AVEVA Plant Design Management Systems の RVM ファイル用ロードオプション。
type: docs
weight: 157
url: /ja/java/com.aspose.threed/rvmloadoptions/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.IOConfig](../../com.aspose.threed/ioconfig), [com.aspose.threed.LoadOptions](../../com.aspose.threed/loadoptions)
```
public class RvmLoadOptions extends LoadOptions
```

AVEVA Plant Design Management System の RVM ファイル用ロードオプションです。 **Example:** 以下のコードは、RvmLoadOptions を使用して RVM ファイルからインポートされたプリミティブジオメトリのテッセレーションパラメータをカスタマイズする方法を示しています。

```
RvmLoadOptions opt = new RvmLoadOptions();
             opt.setRectangularTorusSegments(30);
             opt.setCylinderRadialSegments(20);
             opt.setDishLatitudeSegments(20);
             opt.setDishLongitudeSegments(20);
             opt.setCenterScene(true);
             var scene = Scene.fromFile("input.rvm", opt);
             scene.save("output.obj");
```
## Constructors

| Constructor | 説明 |
| --- | --- |
| [RvmLoadOptions(FileContentType contentType)](#RvmLoadOptions-com.aspose.threed.FileContentType-) | [RvmLoadOptions](../../com.aspose.threed/rvmloadoptions) インスタンスを作成します |
| [RvmLoadOptions()](#RvmLoadOptions--) | [RvmLoadOptions](../../com.aspose.threed/rvmloadoptions) インスタンスを作成します |
## Methods

| Method | 説明 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAttributePrefix()](#getAttributePrefix--) | 外部属性ファイルで定義された属性のプレフィックスを取得します。プレフィックスは名前の競合を避けるために使用され、デフォルト値は "rvm:" です。 |
| [getCenterScene()](#getCenterScene--) | シーンがロードされた後にセンタリングします。 |
| [getClass()](#getClass--) |  |
| [getCylinderRadialSegments()](#getCylinderRadialSegments--) | シリンダーの放射状セグメント数を取得します。デフォルト値は 16 です。 |
| [getDishLatitudeSegments()](#getDishLatitudeSegments--) | ディッシュの緯度セグメント数を取得します。デフォルト値は 8 です。 |
| [getDishLongitudeSegments()](#getDishLongitudeSegments--) | ディッシュの経度セグメント数を取得します。デフォルト値は 12 です。 |
| [getEncoding()](#getEncoding--) | テキストベースのファイルのデフォルトエンコーディングを取得します。 |
| [getFileFormat()](#getFileFormat--) | 現在の保存/読み込みオプションで指定されたファイル形式を取得します。 |
| [getFileName()](#getFileName--) | エクスポート/インポートシーンのファイル名。 |
| [getFileSystem()](#getFileSystem--) | ロード/セーブ時に外部依存関係を管理する方法をユーザーが処理できるようにします。 |
| [getFileSystemFactory()](#getFileSystemFactory--) | FileSystem のファクトリークラスを取得します。 |
| [getGenerateMaterials()](#getGenerateMaterials--) | RVM ファイルにカラーテーブルがエクスポートされていない場合、シーン内の各オブジェクトに対してランダムな色のマテリアルを生成します。 |
| [getLookupAttributes()](#getLookupAttributes--) | 外部属性リストファイル（.att/.attrib/.txt）から属性をロードするかどうかを取得します。デフォルト値は true です。 |
| [getLookupPaths()](#getLookupPaths--) | OBJ のような一部のファイルは外部ファイルに依存しており、検索パスにより Aspose.3D が外部ファイルを読み込むために探すことができます。 |
| [getRectangularTorusSegments()](#getRectangularTorusSegments--) | 矩形トーラスの放射状セグメント数を取得します。デフォルト値は 20 です。 |
| [getTorusTubularSegments()](#getTorusTubularSegments--) | トーラスのチューブ状セグメント数を取得します。デフォルト値は 20 です。 |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAttributePrefix(String value)](#setAttributePrefix-java.lang.String-) | 外部属性ファイルで定義された属性のプレフィックスを設定します。プレフィックスは名前の競合を避けるために使用され、デフォルト値は "rvm:" です。 |
| [setCenterScene(boolean value)](#setCenterScene-boolean-) | シーンがロードされた後にセンタリングします。 |
| [setCylinderRadialSegments(int value)](#setCylinderRadialSegments-int-) | シリンダーの放射状セグメント数を設定します。デフォルト値は 16 です。 |
| [setDishLatitudeSegments(int value)](#setDishLatitudeSegments-int-) | ディッシュの緯度セグメント数を設定します。デフォルト値は 8 です。 |
| [setDishLongitudeSegments(int value)](#setDishLongitudeSegments-int-) | ディッシュの経度セグメント数を設定します。デフォルト値は 12 です。 |
| [setEncoding(Charset value)](#setEncoding-java.nio.charset.Charset-) | テキストベースのファイルのデフォルトエンコーディングを設定します。 |
| [setFileName(String value)](#setFileName-java.lang.String-) | エクスポート/インポートシーンのファイル名。 |
| [setFileSystem(FileSystem value)](#setFileSystem-com.aspose.threed.FileSystem-) | ロード/セーブ時に外部依存関係を管理する方法をユーザーが処理できるようにします。 |
| [setFileSystemFactory(FileSystemFactory value)](#setFileSystemFactory-com.aspose.threed.FileSystemFactory-) | FileSystem のファクトリークラスを設定します。 |
| [setGenerateMaterials(boolean value)](#setGenerateMaterials-boolean-) | RVM ファイルにカラーテーブルがエクスポートされていない場合、シーン内の各オブジェクトに対してランダムな色のマテリアルを生成します。 |
| [setLookupAttributes(boolean value)](#setLookupAttributes-boolean-) | 外部属性リストファイル（.att/.attrib/.txt）から属性をロードするかどうかを設定します。デフォルト値は true です。 |
| [setLookupPaths(ArrayList<String> value)](#setLookupPaths-java.util.ArrayList-java.lang.String--) | OBJ のような一部のファイルは外部ファイルに依存しており、検索パスにより Aspose.3D が外部ファイルを読み込むために探すことができます。 |
| [setRectangularTorusSegments(int value)](#setRectangularTorusSegments-int-) | 矩形トーラスの放射状セグメント数を設定します。デフォルト値は 20 です。 |
| [setTorusTubularSegments(int value)](#setTorusTubularSegments-int-) | トーラスのチューブ状セグメント数を設定します。デフォルト値は 20 です。 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### RvmLoadOptions(FileContentType contentType) {#RvmLoadOptions-com.aspose.threed.FileContentType-}
```
public RvmLoadOptions(FileContentType contentType)
```


[RvmLoadOptions](../../com.aspose.threed/rvmloadoptions) インスタンスを作成します

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| contentType | [FileContentType](../../com.aspose.threed/filecontenttype) |  |

### RvmLoadOptions() {#RvmLoadOptions--}
```
public RvmLoadOptions()
```


[RvmLoadOptions](../../com.aspose.threed/rvmloadoptions) インスタンスを作成します

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
### getAttributePrefix() {#getAttributePrefix--}
```
public String getAttributePrefix()
```


外部属性ファイルで定義された属性のプレフィックスを取得します。プレフィックスは名前の競合を避けるために使用され、デフォルト値は "rvm:" です。

**Returns:**
java.lang.String - 外部属性ファイルで定義された属性のプレフィックス、プレフィックスは名前の衝突を防ぐために使用されます、デフォルト値は "rvm:"
### getCenterScene() {#getCenterScene--}
```
public boolean getCenterScene()
```


シーンがロードされた後にセンタリングします。

**Returns:**
boolean - シーンがロードされた後にセンタリングします。
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getCylinderRadialSegments() {#getCylinderRadialSegments--}
```
public int getCylinderRadialSegments()
```


シリンダーの放射状セグメント数を取得します。デフォルト値は 16 です。

**Returns:**
int - シリンダーの放射状セグメント数、デフォルト値は 16
### getDishLatitudeSegments() {#getDishLatitudeSegments--}
```
public int getDishLatitudeSegments()
```


ディッシュの緯度セグメント数を取得します。デフォルト値は 8 です。

**Returns:**
int - ディッシュの緯度セグメント数、デフォルト値は 8
### getDishLongitudeSegments() {#getDishLongitudeSegments--}
```
public int getDishLongitudeSegments()
```


ディッシュの経度セグメント数を取得します。デフォルト値は 12 です。

**Returns:**
int - ディッシュの経度セグメント数、デフォルト値は 12
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
### getGenerateMaterials() {#getGenerateMaterials--}
```
public boolean getGenerateMaterials()
```


シーン内の各オブジェクトに対して、RVM ファイル内にカラーテーブルがエクスポートされていない場合、ランダムな色でマテリアルを生成します。デフォルト値は true

**Returns:**
boolean - シーン内の各オブジェクトに対して、RVM ファイル内にカラーテーブルがエクスポートされていない場合、ランダムな色でマテリアルを生成します。デフォルト値は true
### getLookupAttributes() {#getLookupAttributes--}
```
public boolean getLookupAttributes()
```


外部属性リストファイル（.att/.attrib/.txt）から属性をロードするかどうかを取得します。デフォルト値は true です。

**Returns:**
boolean - 外部属性リストファイル(.att/.attrib/.txt)から属性をロードするかどうか、デフォルト値は true。
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
### getRectangularTorusSegments() {#getRectangularTorusSegments--}
```
public int getRectangularTorusSegments()
```


矩形トーラスの放射状セグメント数を取得します。デフォルト値は 20 です。

**Returns:**
int - 長方形トーラスの放射状セグメント数、デフォルト値は 20
### getTorusTubularSegments() {#getTorusTubularSegments--}
```
public int getTorusTubularSegments()
```


トーラスのチューブ状セグメント数を取得します。デフォルト値は 20 です。

**Returns:**
int - トーラスのチューブ状セグメント数、デフォルト値は 20
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




### setAttributePrefix(String value) {#setAttributePrefix-java.lang.String-}
```
public void setAttributePrefix(String value)
```


外部属性ファイルで定義された属性のプレフィックスを設定します。プレフィックスは名前の競合を避けるために使用され、デフォルト値は "rvm:" です。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| 値 | java.lang.String | 新しい値 |

### setCenterScene(boolean value) {#setCenterScene-boolean-}
```
public void setCenterScene(boolean value)
```


シーンがロードされた後にセンタリングします。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| 値 | boolean | 新しい値 |

### setCylinderRadialSegments(int value) {#setCylinderRadialSegments-int-}
```
public void setCylinderRadialSegments(int value)
```


シリンダーの放射状セグメント数を設定します。デフォルト値は 16 です。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| 値 | int | 新しい値 |

### setDishLatitudeSegments(int value) {#setDishLatitudeSegments-int-}
```
public void setDishLatitudeSegments(int value)
```


ディッシュの緯度セグメント数を設定します。デフォルト値は 8 です。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| 値 | int | 新しい値 |

### setDishLongitudeSegments(int value) {#setDishLongitudeSegments-int-}
```
public void setDishLongitudeSegments(int value)
```


ディッシュの経度セグメント数を設定します。デフォルト値は 12 です。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| 値 | int | 新しい値 |

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

### setGenerateMaterials(boolean value) {#setGenerateMaterials-boolean-}
```
public void setGenerateMaterials(boolean value)
```


シーン内の各オブジェクトに対して、RVM ファイル内にカラーテーブルがエクスポートされていない場合、ランダムな色でマテリアルを生成します。デフォルト値は true

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| 値 | boolean | 新しい値 |

### setLookupAttributes(boolean value) {#setLookupAttributes-boolean-}
```
public void setLookupAttributes(boolean value)
```


外部属性リストファイル（.att/.attrib/.txt）から属性をロードするかどうかを設定します。デフォルト値は true です。

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

### setRectangularTorusSegments(int value) {#setRectangularTorusSegments-int-}
```
public void setRectangularTorusSegments(int value)
```


矩形トーラスの放射状セグメント数を設定します。デフォルト値は 20 です。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| 値 | int | 新しい値 |

### setTorusTubularSegments(int value) {#setTorusTubularSegments-int-}
```
public void setTorusTubularSegments(int value)
```


トーラスのチューブ状セグメント数を設定します。デフォルト値は 20 です。

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


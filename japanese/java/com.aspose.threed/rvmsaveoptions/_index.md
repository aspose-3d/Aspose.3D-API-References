---
title: RvmSaveOptions
second_title: Aspose.3D for Java API リファレンス
description: Aveva PDMS RVM ファイルの保存オプション。
type: docs
weight: 158
url: /ja/java/com.aspose.threed/rvmsaveoptions/
---

**Inheritance:**
java.lang.Object、[com.aspose.threed.IOConfig](../../com.aspose.threed/ioconfig)、[com.aspose.threed.SaveOptions](../../com.aspose.threed/saveoptions)
```
public class RvmSaveOptions extends SaveOptions
```

Aveva PDMS RVM ファイルの保存オプション。**例:** 以下のコードは、RVM で属性をエクスポートする方法を示しています。

```
Scene scene = new Scene();
             var box = (new Box()).toMesh();
             //node's name is required to export attributes
             var boxNode = scene.getRootNode().createChildNode("box", box);
             boxNode.setProperty("rvm:Price", 12.0);
             boxNode.setProperty("rvm:Weight", 30.0);
             var opt = new RvmSaveOptions();
             //Properties with rvm: prefix will be exported.
             opt.setExportAttributes(true);
             opt.setAttributePrefix("rvm:");
             opt.setAuthor("Aspose.3D");
             opt.setFileNote("Test attribute export");
             scene.save("output.rvm", opt);
```
## Constructors

| Constructor | 説明 |
| --- | --- |
| [RvmSaveOptions()](#RvmSaveOptions--) | [RvmSaveOptions](../../com.aspose.threed/rvmsaveoptions) のコンストラクタ |
| [RvmSaveOptions(FileContentType contentType)](#RvmSaveOptions-com.aspose.threed.FileContentType-) | [RvmSaveOptions](../../com.aspose.threed/rvmsaveoptions) のコンストラクタ |
## Methods

| Method | 説明 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAttributeListFile()](#getAttributeListFile--) | 属性リストファイルのファイル名を取得します。このプロパティが未定義の場合、エクスポーターは .rvm ファイル名に基づいて名前を生成します。デフォルト値は null です。 |
| [getAttributePrefix()](#getAttributePrefix--) | エクスポートされる属性のプレフィックスを取得します。エクスポートされたプロパティにはプレフィックスが含まれず、異なるプレフィックスを持つカスタムプロパティはエクスポートされません。デフォルト値は 'rvm:' です。 |
| [getAuthor()](#getAuthor--) | 作者情報、デフォルト値は '3d@aspose' |
| [getClass()](#getClass--) |  |
| [getCreationTime()](#getCreationTime--) | このファイルがエクスポートされたタイムスタンプ、デフォルト値は現在時刻です |
| [getEncoding()](#getEncoding--) | テキストベースのファイルのデフォルトエンコーディングを取得します。 |
| [getExportAttributes()](#getExportAttributes--) | 属性リストを外部の .att ファイルにエクスポートするかどうかを取得します。デフォルト値は false です。 |
| [getExportTextures()](#getExportTextures--) | シーンで使用されているテクスチャを出力ディレクトリにコピーしようとします。 |
| [getFileFormat()](#getFileFormat--) | 現在の保存/読み込みオプションで指定されたファイル形式を取得します。 |
| [getFileName()](#getFileName--) | エクスポート/インポートシーンのファイル名。 |
| [getFileNote()](#getFileNote--) | ファイルヘッダー内のファイルノートです。 |
| [getFileSystem()](#getFileSystem--) | ロード/セーブ時に外部依存関係を管理する方法をユーザーが処理できるようにします。 |
| [getFileSystemFactory()](#getFileSystemFactory--) | FileSystem のファクトリークラスを取得します。 |
| [getLookupPaths()](#getLookupPaths--) | OBJ のような一部のファイルは外部ファイルに依存しており、検索パスにより Aspose.3D が外部ファイルを読み込むために探すことができます。 |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAttributeListFile(String value)](#setAttributeListFile-java.lang.String-) | 属性リストファイルのファイル名を設定します。このプロパティが未定義の場合、エクスポーターは .rvm ファイル名に基づいて名前を生成します。デフォルト値は null です。 |
| [setAttributePrefix(String value)](#setAttributePrefix-java.lang.String-) | エクスポートされる属性のプレフィックスを設定します。エクスポートされたプロパティにはプレフィックスが含まれず、異なるプレフィックスを持つカスタムプロパティはエクスポートされません。デフォルト値は 'rvm:' です。 |
| [setAuthor(String value)](#setAuthor-java.lang.String-) | 作者情報、デフォルト値は '3d@aspose' |
| [setCreationTime(String value)](#setCreationTime-java.lang.String-) | このファイルがエクスポートされたタイムスタンプ、デフォルト値は現在時刻です |
| [setEncoding(Charset value)](#setEncoding-java.nio.charset.Charset-) | テキストベースのファイルのデフォルトエンコーディングを設定します。 |
| [setExportAttributes(boolean value)](#setExportAttributes-boolean-) | 属性リストを外部の .att ファイルにエクスポートするかどうかを設定します。デフォルト値は false です。 |
| [setExportTextures(boolean value)](#setExportTextures-boolean-) | シーンで使用されているテクスチャを出力ディレクトリにコピーしようとします。 |
| [setFileName(String value)](#setFileName-java.lang.String-) | エクスポート/インポートシーンのファイル名。 |
| [setFileNote(String value)](#setFileNote-java.lang.String-) | ファイルヘッダー内のファイルノートです。 |
| [setFileSystem(FileSystem value)](#setFileSystem-com.aspose.threed.FileSystem-) | ロード/セーブ時に外部依存関係を管理する方法をユーザーが処理できるようにします。 |
| [setFileSystemFactory(FileSystemFactory value)](#setFileSystemFactory-com.aspose.threed.FileSystemFactory-) | FileSystem のファクトリークラスを設定します。 |
| [setLookupPaths(ArrayList<String> value)](#setLookupPaths-java.util.ArrayList-java.lang.String--) | OBJ のような一部のファイルは外部ファイルに依存しており、検索パスにより Aspose.3D が外部ファイルを読み込むために探すことができます。 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### RvmSaveOptions() {#RvmSaveOptions--}
```
public RvmSaveOptions()
```


[RvmSaveOptions](../../com.aspose.threed/rvmsaveoptions) のコンストラクタ

### RvmSaveOptions(FileContentType contentType) {#RvmSaveOptions-com.aspose.threed.FileContentType-}
```
public RvmSaveOptions(FileContentType contentType)
```


[RvmSaveOptions](../../com.aspose.threed/rvmsaveoptions) のコンストラクタ

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| contentType | [FileContentType](../../com.aspose.threed/filecontenttype) | テキストまたはバイナリ RVM ファイルですか？ |

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
### getAttributeListFile() {#getAttributeListFile--}
```
public String getAttributeListFile()
```


属性リストファイルのファイル名を取得します。このプロパティが未定義の場合、エクスポーターは .rvm ファイル名に基づいて名前を生成します。デフォルト値は null です。

**Returns:**
java.lang.String - 属性リストファイルのファイル名。このプロパティが未定義の場合、エクスポーターは .rvm ファイル名に基づいて名前を生成します。デフォルト値は null です。 **Example:** 以下のコードは RVM で属性をエクスポートする方法を示しています。

```
Scene scene = new Scene();
             var box = (new Box()).toMesh();
             //node's name is required to export attributes
             var boxNode = scene.getRootNode().createChildNode("box", box);
             boxNode.setProperty("rvm:Price", 12.0);
             boxNode.setProperty("rvm:Weight", 30.0);
             var opt = new RvmSaveOptions();
             //Properties with rvm: prefix will be exported.
             opt.setExportAttributes(true);
             opt.setAttributePrefix("rvm:");
             opt.setAuthor("Aspose.3D");
             opt.setFileNote("Test attribute export");
             scene.save("output.rvm", opt);
```
### getAttributePrefix() {#getAttributePrefix--}
```
public String getAttributePrefix()
```


エクスポートされる属性のプレフィックスを取得します。エクスポートされたプロパティにはプレフィックスが含まれず、異なるプレフィックスを持つカスタムプロパティはエクスポートされません。デフォルト値は 'rvm:' です。例えば、プロパティが rvm:Refno=345 の場合、エクスポートされた属性は Refno = 345 となり、プレフィックスは除去されます。

**Returns:**
java.lang.String - エクスポートされる属性のプレフィックス。エクスポートされたプロパティにはプレフィックスが含まれず、異なるプレフィックスを持つカスタムプロパティはエクスポートされません。デフォルト値は 'rvm:' です。例えば、プロパティが rvm:Refno=345 の場合、エクスポートされた属性は Refno = 345 となり、プレフィックスは除去されます。 **Example:** 以下のコードは RVM で属性をエクスポートする方法を示しています。

```
Scene scene = new Scene();
             var box = (new Box()).toMesh();
             //node's name is required to export attributes
             var boxNode = scene.getRootNode().createChildNode("box", box);
             boxNode.setProperty("rvm:Price", 12.0);
             boxNode.setProperty("rvm:Weight", 30.0);
             var opt = new RvmSaveOptions();
             //Properties with rvm: prefix will be exported.
             opt.setExportAttributes(true);
             opt.setAttributePrefix("rvm:");
             opt.setAuthor("Aspose.3D");
             opt.setFileNote("Test attribute export");
             scene.save("output.rvm", opt);
```
### getAuthor() {#getAuthor--}
```
public String getAuthor()
```


作者情報、デフォルト値は '3d@aspose'

**Returns:**
java.lang.String - 作者情報、デフォルト値は '3d@aspose' **Example:** 以下のコードは RVM で属性をエクスポートする方法を示しています。

```
Scene scene = new Scene();
             var box = (new Box()).toMesh();
             //node's name is required to export attributes
             var boxNode = scene.getRootNode().createChildNode("box", box);
             boxNode.setProperty("rvm:Price", 12.0);
             boxNode.setProperty("rvm:Weight", 30.0);
             var opt = new RvmSaveOptions();
             //Properties with rvm: prefix will be exported.
             opt.setExportAttributes(true);
             opt.setAttributePrefix("rvm:");
             opt.setAuthor("Aspose.3D");
             opt.setFileNote("Test attribute export");
             scene.save("output.rvm", opt);
```
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getCreationTime() {#getCreationTime--}
```
public String getCreationTime()
```


このファイルがエクスポートされたタイムスタンプ、デフォルト値は現在時刻です

**Returns:**
java.lang.String - このファイルをエクスポートしたタイムスタンプ、デフォルト値は現在時刻です
### getEncoding() {#getEncoding--}
```
public Charset getEncoding()
```


テキストベースのファイルのデフォルトエンコーディングを取得します。デフォルト値は null で、インポーター/エクスポーターが使用するエンコーディングを決定します。

**Returns:**
java.nio.charset.Charset - テキストベースのファイルのデフォルトエンコーディングです。デフォルト値は null で、インポーター/エクスポーターが使用するエンコーディングを決定します。
### getExportAttributes() {#getExportAttributes--}
```
public boolean getExportAttributes()
```


属性リストを外部の .att ファイルにエクスポートするかどうかを取得します。デフォルト値は false です。

**Returns:**
boolean - 属性リストを外部の .att ファイルにエクスポートするかどうか、デフォルト値は false です。 **Example:** 以下のコードは RVM で属性をエクスポートする方法を示しています。

```
Scene scene = new Scene();
             var box = (new Box()).toMesh();
             //node's name is required to export attributes
             var boxNode = scene.getRootNode().createChildNode("box", box);
             boxNode.setProperty("rvm:Price", 12.0);
             boxNode.setProperty("rvm:Weight", 30.0);
             var opt = new RvmSaveOptions();
             //Properties with rvm: prefix will be exported.
             opt.setExportAttributes(true);
             opt.setAttributePrefix("rvm:");
             opt.setAuthor("Aspose.3D");
             opt.setFileNote("Test attribute export");
             scene.save("output.rvm", opt);
```
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
### getFileNote() {#getFileNote--}
```
public String getFileNote()
```


ファイルヘッダー内のファイルノートです。

**Returns:**
java.lang.String - ファイルヘッダー内のファイルノートです。 **Example:** 以下のコードは RVM で属性をエクスポートする方法を示しています。

```
Scene scene = new Scene();
             var box = (new Box()).toMesh();
             //node's name is required to export attributes
             var boxNode = scene.getRootNode().createChildNode("box", box);
             boxNode.setProperty("rvm:Price", 12.0);
             boxNode.setProperty("rvm:Weight", 30.0);
             var opt = new RvmSaveOptions();
             //Properties with rvm: prefix will be exported.
             opt.setExportAttributes(true);
             opt.setAttributePrefix("rvm:");
             opt.setAuthor("Aspose.3D");
             opt.setFileNote("Test attribute export");
             scene.save("output.rvm", opt);
```
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




### setAttributeListFile(String value) {#setAttributeListFile-java.lang.String-}
```
public void setAttributeListFile(String value)
```


属性リストファイルのファイル名を設定します。このプロパティが未定義の場合、エクスポーターは .rvm ファイル名に基づいて名前を生成します。デフォルト値は null です。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
|  | 値 | java.lang.String | 新しい値 **Example:** 以下のコードは RVM で属性をエクスポートする方法を示しています。 |

```
Scene scene = new Scene();
             var box = (new Box()).toMesh();
             //node's name is required to export attributes
             var boxNode = scene.getRootNode().createChildNode("box", box);
             boxNode.setProperty("rvm:Price", 12.0);
             boxNode.setProperty("rvm:Weight", 30.0);
             var opt = new RvmSaveOptions();
             //Properties with rvm: prefix will be exported.
             opt.setExportAttributes(true);
             opt.setAttributePrefix("rvm:");
             opt.setAuthor("Aspose.3D");
             opt.setFileNote("Test attribute export");
             scene.save("output.rvm", opt);
``` |

### setAttributePrefix(String value) {#setAttributePrefix-java.lang.String-}
```
public void setAttributePrefix(String value)
```


エクスポートされる属性のプレフィックスを設定します。エクスポートされたプロパティにはプレフィックスが含まれず、異なるプレフィックスを持つカスタムプロパティはエクスポートされません。デフォルト値は 'rvm:' です。例えば、プロパティが rvm:Refno=345 の場合、エクスポートされた属性は Refno = 345 となり、プレフィックスは除去されます。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
|  | 値 | java.lang.String | 新しい値 **Example:** 以下のコードは RVM で属性をエクスポートする方法を示しています。 |

```
Scene scene = new Scene();
             var box = (new Box()).toMesh();
             //node's name is required to export attributes
             var boxNode = scene.getRootNode().createChildNode("box", box);
             boxNode.setProperty("rvm:Price", 12.0);
             boxNode.setProperty("rvm:Weight", 30.0);
             var opt = new RvmSaveOptions();
             //Properties with rvm: prefix will be exported.
             opt.setExportAttributes(true);
             opt.setAttributePrefix("rvm:");
             opt.setAuthor("Aspose.3D");
             opt.setFileNote("Test attribute export");
             scene.save("output.rvm", opt);
``` |

### setAuthor(String value) {#setAuthor-java.lang.String-}
```
public void setAuthor(String value)
```


作者情報、デフォルト値は '3d@aspose'

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
|  | 値 | java.lang.String | 新しい値 **Example:** 以下のコードは RVM で属性をエクスポートする方法を示しています。 |

```
Scene scene = new Scene();
             var box = (new Box()).toMesh();
             //node's name is required to export attributes
             var boxNode = scene.getRootNode().createChildNode("box", box);
             boxNode.setProperty("rvm:Price", 12.0);
             boxNode.setProperty("rvm:Weight", 30.0);
             var opt = new RvmSaveOptions();
             //Properties with rvm: prefix will be exported.
             opt.setExportAttributes(true);
             opt.setAttributePrefix("rvm:");
             opt.setAuthor("Aspose.3D");
             opt.setFileNote("Test attribute export");
             scene.save("output.rvm", opt);
``` |

### setCreationTime(String value) {#setCreationTime-java.lang.String-}
```
public void setCreationTime(String value)
```


このファイルがエクスポートされたタイムスタンプ、デフォルト値は現在時刻です

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

### setExportAttributes(boolean value) {#setExportAttributes-boolean-}
```
public void setExportAttributes(boolean value)
```


属性リストを外部の .att ファイルにエクスポートするかどうかを設定します。デフォルト値は false です。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
|  | 値 | boolean | 新しい値 **Example:** 以下のコードは RVM で属性をエクスポートする方法を示しています。 |

```
Scene scene = new Scene();
             var box = (new Box()).toMesh();
             //node's name is required to export attributes
             var boxNode = scene.getRootNode().createChildNode("box", box);
             boxNode.setProperty("rvm:Price", 12.0);
             boxNode.setProperty("rvm:Weight", 30.0);
             var opt = new RvmSaveOptions();
             //Properties with rvm: prefix will be exported.
             opt.setExportAttributes(true);
             opt.setAttributePrefix("rvm:");
             opt.setAuthor("Aspose.3D");
             opt.setFileNote("Test attribute export");
             scene.save("output.rvm", opt);
``` |

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

### setFileNote(String value) {#setFileNote-java.lang.String-}
```
public void setFileNote(String value)
```


ファイルヘッダー内のファイルノートです。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
|  | 値 | java.lang.String | 新しい値 **Example:** 以下のコードは RVM で属性をエクスポートする方法を示しています。 |

```
Scene scene = new Scene();
             var box = (new Box()).toMesh();
             //node's name is required to export attributes
             var boxNode = scene.getRootNode().createChildNode("box", box);
             boxNode.setProperty("rvm:Price", 12.0);
             boxNode.setProperty("rvm:Weight", 30.0);
             var opt = new RvmSaveOptions();
             //Properties with rvm: prefix will be exported.
             opt.setExportAttributes(true);
             opt.setAttributePrefix("rvm:");
             opt.setAuthor("Aspose.3D");
             opt.setFileNote("Test attribute export");
             scene.save("output.rvm", opt);
``` |

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


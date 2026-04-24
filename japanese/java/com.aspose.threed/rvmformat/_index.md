---
title: RvmFormat
second_title: Aspose.3D for Java API リファレンス
description: RVM フォーマット
type: docs
weight: 156
url: /ja/java/com.aspose.threed/rvmformat/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.FileFormat](../../com.aspose.threed/fileformat)
```
public class RvmFormat extends FileFormat
```

RVM フォーマット
## フィールド

| フィールド | 説明 |
| --- | --- |
| [AMF](#AMF) | Additive manufacturing file format |
| [ASE](#ASE) | 3D Studio Max's ASCII Scene Exporter format. |
| [ASPOSE3D_WEB](#ASPOSE3D-WEB) | Aspose.3D Web format. |
| [BLENDER](#BLENDER) | Blender's 3D file format |
| [COLLADA](#COLLADA) | Collada file format |
| [DISCREET3DS](#DISCREET3DS) | 3D Studio's file format |
| [DRACO](#DRACO) | Google Draco Mesh |
| [DXF](#DXF) | AutoCAD DXF |
| [FBX6100ASCII](#FBX6100ASCII) | ASCII FBX file format, with 6.1.0 version |
| [FBX6100_BINARY](#FBX6100-BINARY) | Binary FBX file format, with 6.1.0 version |
| [FBX7200ASCII](#FBX7200ASCII) | ASCII FBX file format, with 7.2.0 version |
| [FBX7200_BINARY](#FBX7200-BINARY) | Binary FBX file format, with 7.2.0 version |
| [FBX7300ASCII](#FBX7300ASCII) | ASCII FBX file format, with 7.3.0 version |
| [FBX7300_BINARY](#FBX7300-BINARY) | Binary FBX file format, with 7.3.0 version |
| [FBX7400ASCII](#FBX7400ASCII) | ASCII FBX file format, with 7.4.0 version |
| [FBX7400_BINARY](#FBX7400-BINARY) | Binary FBX file format, with 7.4.0 version |
| [FBX7500ASCII](#FBX7500ASCII) | ASCII FBX ファイル形式、バージョン 7.5.0 |
| [FBX7500_BINARY](#FBX7500-BINARY) | Binary FBX ファイル形式、バージョン 7.5.0 |
| [FBX7600ASCII](#FBX7600ASCII) | ASCII FBX ファイル形式、バージョン 7.6.0 |
| [FBX7600_BINARY](#FBX7600-BINARY) | Binary FBX ファイル形式、バージョン 7.6.0 |
| [FBX7700ASCII](#FBX7700ASCII) | ASCII FBX ファイル形式、バージョン 7.7.0 |
| [FBX7700_BINARY](#FBX7700-BINARY) | Binary FBX ファイル形式、バージョン 7.7.0 |
| [GLTF](#GLTF) | Khronos Group の glTF |
| [GLTF2](#GLTF2) | Khronos Group の glTF バージョン 2.0 |
| [GLTF2_BINARY](#GLTF2-BINARY) | Khronos Group の glTF バージョン 2.0 |
| [GLTF_BINARY](#GLTF-BINARY) | Khronos Group の glTF（バイナリ形式） |
| [HTML5](#HTML5) | HTML5 ファイル |
| [IFC](#IFC) | ISO 16739-1 Industry Foundation Classes データモデル。 |
| [MAYAASCII](#MAYAASCII) | Autodesk Maya（ASCII 形式） |
| [MAYA_BINARY](#MAYA-BINARY) | Autodesk Maya（バイナリ形式） |
| [MICROSOFT3MF](#MICROSOFT3MF) | Microsoft 3D Manufacturing Format |
| [PCD](#PCD) | PCL Point Cloud Data ファイル（ASCII モード） |
| [PCD_BINARY](#PCD-BINARY) | PCL Point Cloud Data ファイル（バイナリモード） |
| [PDF](#PDF) | Adobe の Portable Document Format |
| [PLY](#PLY) | Polygon File Format または Stanford Triangle Format |
| [RVM_BINARY](#RVM-BINARY) | AVEVA Plant Design Management System Model（バイナリ形式） |
| [RVM_TEXT](#RVM-TEXT) | AVEVA Plant Design Management System Model（テキスト形式） |
| [SIEMENSJT8](#SIEMENSJT8) | Siemens JT ファイル バージョン 8 |
| [SIEMENSJT9](#SIEMENSJT9) | Siemens JT ファイル バージョン 9 |
| [STLASCII](#STLASCII) | ASCII STL ファイル形式 |
| [STL_BINARY](#STL-BINARY) | Binary STL ファイル形式 |
| [UNIVERSAL3D](#UNIVERSAL3D) | Universal3D ファイル形式 |
| [USD](#USD) | ユニバーサルシーン記述 |
| [USDA](#USDA) | ASCII形式のユニバーサルシーン記述。 |
| [USDZ](#USDZ) | 圧縮されたユニバーサルシーン記述 |
| [VRML](#VRML) | バーチャルリアリティモデリング言語 |
| [WAVEFRONTOBJ](#WAVEFRONTOBJ) | Wavefront の Obj ファイル形式 |
| [XYZ](#XYZ) | Xyz 点群ファイル |
| [X_BINARY](#X-BINARY) | バイナリ形式の DirectX X ファイル |
| [X_TEXT](#X-TEXT) | バイナリ形式の DirectX X ファイル |
| [ZIP](#ZIP) | 他の 3D ファイル形式を含む Zip アーカイブ。 |
## Methods

| Method | 説明 |
| --- | --- |
| [createLoadOptions()](#createLoadOptions--) | このファイル形式のデフォルト読み込みオプションを作成する |
| [createSaveOptions()](#createSaveOptions--) | このファイル形式のデフォルト保存オプションを作成する |
| [detect(Stream stream, String fileName)](#detect-com.aspose.threed.Stream-java.lang.String-) | データストリームからファイル形式を検出します。マジックヘッダーがないタイプを推測するために、ファイル名はオプションです。 |
| [detect(String fileName)](#detect-java.lang.String-) | ファイル名からファイル形式を検出します。ファイルは読み取り可能である必要があり、Aspose.3D はファイルヘッダーを通じて形式を検出できます。 |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getCanExport()](#getCanExport--) | Aspose.3D が現在のファイル形式へのシーンエクスポートをサポートしているかどうかを取得します。 |
| [getCanImport()](#getCanImport--) | Aspose.3D が現在のファイル形式からのシーンインポートをサポートしているかどうかを取得します。 |
| [getClass()](#getClass--) |  |
| [getContentType()](#getContentType--) | ファイル形式のコンテンツタイプを取得します |
| [getExtension()](#getExtension--) | このタイプの拡張子名を取得します。 |
| [getExtensions()](#getExtensions--) | このタイプの拡張子名一覧を取得します。 |
| [getFileFormatType()](#getFileFormatType--) | ファイル形式のタイプを取得します |
| [getFormatByExtension(String extensionName)](#getFormatByExtension-java.lang.String-) | 拡張子名から優先されるファイル形式を取得します。拡張子名はドット ('.') で始まる必要があります。 |
| [getFormats()](#getFormats--) | すべてのサポートされている形式にアクセスする |
| [getVersion()](#getVersion--) | ファイル形式のバージョンを取得します |
| [hashCode()](#hashCode--) |  |
| [loadAttributes(Scene scene, Stream stream)](#loadAttributes-com.aspose.threed.Scene-com.aspose.threed.Stream-) | 指定されたストリームから属性をロードする |
| [loadAttributes(Scene scene, Stream stream, String prefix)](#loadAttributes-com.aspose.threed.Scene-com.aspose.threed.Stream-java.lang.String-) | 指定されたストリームから属性をロードする |
| [loadAttributes(Scene scene, String fileName)](#loadAttributes-com.aspose.threed.Scene-java.lang.String-) | 指定されたファイル名から属性をロードする |
| [loadAttributes(Scene scene, String fileName, String prefix)](#loadAttributes-com.aspose.threed.Scene-java.lang.String-java.lang.String-) | 指定されたファイル名から属性をロードする |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) | 形式を文字列に変換する |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### AMF {#AMF}
```
public static final FileFormat AMF
```


Additive manufacturing file format

### ASE {#ASE}
```
public static final FileFormat ASE
```


3D Studio Max's ASCII Scene Exporter format.

### ASPOSE3D_WEB {#ASPOSE3D-WEB}
```
public static final FileFormat ASPOSE3D_WEB
```


Aspose.3D Web format.

### BLENDER {#BLENDER}
```
public static final FileFormat BLENDER
```


Blender's 3D file format

### COLLADA {#COLLADA}
```
public static final FileFormat COLLADA
```


Collada file format

### DISCREET3DS {#DISCREET3DS}
```
public static final FileFormat DISCREET3DS
```


3D Studio's file format

### DRACO {#DRACO}
```
public static final DracoFormat DRACO
```


Google Draco Mesh

### DXF {#DXF}
```
public static final FileFormat DXF
```


AutoCAD DXF

### FBX6100ASCII {#FBX6100ASCII}
```
public static final FileFormat FBX6100ASCII
```


ASCII FBX file format, with 6.1.0 version

### FBX6100_BINARY {#FBX6100-BINARY}
```
public static final FileFormat FBX6100_BINARY
```


Binary FBX file format, with 6.1.0 version

### FBX7200ASCII {#FBX7200ASCII}
```
public static final FileFormat FBX7200ASCII
```


ASCII FBX file format, with 7.2.0 version

### FBX7200_BINARY {#FBX7200-BINARY}
```
public static final FileFormat FBX7200_BINARY
```


Binary FBX file format, with 7.2.0 version

### FBX7300ASCII {#FBX7300ASCII}
```
public static final FileFormat FBX7300ASCII
```


ASCII FBX file format, with 7.3.0 version

### FBX7300_BINARY {#FBX7300-BINARY}
```
public static final FileFormat FBX7300_BINARY
```


Binary FBX file format, with 7.3.0 version

### FBX7400ASCII {#FBX7400ASCII}
```
public static final FileFormat FBX7400ASCII
```


ASCII FBX file format, with 7.4.0 version

### FBX7400_BINARY {#FBX7400-BINARY}
```
public static final FileFormat FBX7400_BINARY
```


Binary FBX file format, with 7.4.0 version

### FBX7500ASCII {#FBX7500ASCII}
```
public static final FileFormat FBX7500ASCII
```


ASCII FBX ファイル形式、バージョン 7.5.0

### FBX7500_BINARY {#FBX7500-BINARY}
```
public static final FileFormat FBX7500_BINARY
```


Binary FBX ファイル形式、バージョン 7.5.0

### FBX7600ASCII {#FBX7600ASCII}
```
public static final FileFormat FBX7600ASCII
```


ASCII FBX ファイル形式、バージョン 7.6.0

### FBX7600_BINARY {#FBX7600-BINARY}
```
public static final FileFormat FBX7600_BINARY
```


Binary FBX ファイル形式、バージョン 7.6.0

### FBX7700ASCII {#FBX7700ASCII}
```
public static final FileFormat FBX7700ASCII
```


ASCII FBX ファイル形式、バージョン 7.7.0

### FBX7700_BINARY {#FBX7700-BINARY}
```
public static final FileFormat FBX7700_BINARY
```


Binary FBX ファイル形式、バージョン 7.7.0

### GLTF {#GLTF}
```
public static final FileFormat GLTF
```


Khronos Group の glTF

### GLTF2 {#GLTF2}
```
public static final FileFormat GLTF2
```


Khronos Group の glTF バージョン 2.0

### GLTF2_BINARY {#GLTF2-BINARY}
```
public static final FileFormat GLTF2_BINARY
```


Khronos Group の glTF バージョン 2.0

### GLTF_BINARY {#GLTF-BINARY}
```
public static final FileFormat GLTF_BINARY
```


Khronos Group の glTF（バイナリ形式）

### HTML5 {#HTML5}
```
public static final FileFormat HTML5
```


HTML5 ファイル

### IFC {#IFC}
```
public static final FileFormat IFC
```


ISO 16739-1 Industry Foundation Classes データモデル。

### MAYAASCII {#MAYAASCII}
```
public static final FileFormat MAYAASCII
```


Autodesk Maya（ASCII 形式）

### MAYA_BINARY {#MAYA-BINARY}
```
public static final FileFormat MAYA_BINARY
```


Autodesk Maya（バイナリ形式）

### MICROSOFT3MF {#MICROSOFT3MF}
```
public static final Microsoft3MFFormat MICROSOFT3MF
```


Microsoft 3D Manufacturing Format

### PCD {#PCD}
```
public static final FileFormat PCD
```


PCL Point Cloud Data ファイル（ASCII モード）

### PCD_BINARY {#PCD-BINARY}
```
public static final FileFormat PCD_BINARY
```


PCL Point Cloud Data ファイル（バイナリモード）

### PDF {#PDF}
```
public static final PdfFormat PDF
```


Adobe の Portable Document Format

### PLY {#PLY}
```
public static final PlyFormat PLY
```


Polygon File Format または Stanford Triangle Format

### RVM_BINARY {#RVM-BINARY}
```
public static final RvmFormat RVM_BINARY
```


AVEVA Plant Design Management System Model（バイナリ形式）

### RVM_TEXT {#RVM-TEXT}
```
public static final RvmFormat RVM_TEXT
```


AVEVA Plant Design Management System Model（テキスト形式）

### SIEMENSJT8 {#SIEMENSJT8}
```
public static final FileFormat SIEMENSJT8
```


Siemens JT ファイル バージョン 8

### SIEMENSJT9 {#SIEMENSJT9}
```
public static final FileFormat SIEMENSJT9
```


Siemens JT ファイル バージョン 9

### STLASCII {#STLASCII}
```
public static final FileFormat STLASCII
```


ASCII STL ファイル形式

### STL_BINARY {#STL-BINARY}
```
public static final FileFormat STL_BINARY
```


Binary STL ファイル形式

### UNIVERSAL3D {#UNIVERSAL3D}
```
public static final FileFormat UNIVERSAL3D
```


Universal3D ファイル形式

### USD {#USD}
```
public static final FileFormat USD
```


ユニバーサルシーン記述

### USDA {#USDA}
```
public static final FileFormat USDA
```


ASCII形式のユニバーサルシーン記述。

### USDZ {#USDZ}
```
public static final FileFormat USDZ
```


圧縮されたユニバーサルシーン記述

### VRML {#VRML}
```
public static final FileFormat VRML
```


バーチャルリアリティモデリング言語

### WAVEFRONTOBJ {#WAVEFRONTOBJ}
```
public static final FileFormat WAVEFRONTOBJ
```


Wavefront の Obj ファイル形式

### XYZ {#XYZ}
```
public static final FileFormat XYZ
```


Xyz 点群ファイル

### X_BINARY {#X-BINARY}
```
public static final FileFormat X_BINARY
```


バイナリ形式の DirectX X ファイル

### X_TEXT {#X-TEXT}
```
public static final FileFormat X_TEXT
```


バイナリ形式の DirectX X ファイル

### ZIP {#ZIP}
```
public static final FileFormat ZIP
```


他の 3D ファイル形式を含む Zip アーカイブ。

### createLoadOptions() {#createLoadOptions--}
```
public LoadOptions createLoadOptions()
```


このファイル形式のデフォルト読み込みオプションを作成する

**Returns:**
[LoadOptions](../../com.aspose.threed/loadoptions) - A default load option for current format
### createSaveOptions() {#createSaveOptions--}
```
public SaveOptions createSaveOptions()
```


このファイル形式のデフォルト保存オプションを作成する

**Returns:**
[SaveOptions](../../com.aspose.threed/saveoptions) - A default save option for current format
### detect(Stream stream, String fileName) {#detect-com.aspose.threed.Stream-java.lang.String-}
```
public static FileFormat detect(Stream stream, String fileName)
```


データストリームからファイル形式を検出します。マジックヘッダーがないタイプを推測するために、ファイル名はオプションです。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| stream | [Stream](../../com.aspose.threed/stream) | 検出するデータを含むストリーム |
| fileName | java.lang.String | データの元のファイル名（ヒントとして使用）。 |

**Returns:**
[FileFormat](../../com.aspose.threed/fileformat) - The [FileFormat](../../com.aspose.threed/fileformat) instance of the detected type or null if failed.
### detect(String fileName) {#detect-java.lang.String-}
```
public static FileFormat detect(String fileName)
```


ファイル名からファイル形式を検出します。ファイルは読み取り可能である必要があり、Aspose.3D はファイルヘッダーを通じて形式を検出できます。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| fileName | java.lang.String | ファイル形式を検出するファイルへのパス。 |

**Returns:**
[FileFormat](../../com.aspose.threed/fileformat) - The [FileFormat](../../com.aspose.threed/fileformat) instance of the detected type or null if failed.
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
### getCanExport() {#getCanExport--}
```
public boolean getCanExport()
```


Aspose.3D が現在のファイル形式へのシーンエクスポートをサポートしているかどうかを取得します。

**Returns:**
boolean - Aspose.3D が現在のファイル形式へのシーンエクスポートをサポートしているかどうか。 **Example:** 以下のコードは、指定された形式へのエクスポートがサポートされているかどうかを確認する方法を示しています。

```
var outputFormat = ".glb";
     var format = FileFormat.getFormatByExtension(outputFormat);
     if (format.getCanExport())
         System.out.printf("Can export to %s", outputFormat);
```
### getCanImport() {#getCanImport--}
```
public boolean getCanImport()
```


Aspose.3D が現在のファイル形式からのシーンインポートをサポートしているかどうかを取得します。

**Returns:**
boolean - Aspose.3D が現在のファイル形式からのシーンインポートをサポートしているかどうか。 **Example:** 以下のコードは、指定された形式からのインポートがサポートされているかどうかを確認する方法を示しています。

```
var outputFormat = ".glb";
     var format = FileFormat.getFormatByExtension(outputFormat);
     if (format.getCanImport())
         System.out.printf("Can import from %s", outputFormat);
```
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getContentType() {#getContentType--}
```
public FileContentType getContentType()
```


ファイル形式のコンテンツタイプを取得します

**Returns:**
[FileContentType](../../com.aspose.threed/filecontenttype) - file format content type **Example:**

```
var format = FileFormat.MAYA_BINARY;
     if (format.getContentType() == FileContentType.BINARY)
         System.out.printf("%s is binary format", format);
     else
         System.out.printf("%s is text-based format", format);
```
### getExtension() {#getExtension--}
```
public String getExtension()
```


このタイプの拡張子名を取得します。

**Returns:**
java.lang.String - この型の拡張子名。 **Example:**

```
var format = FileFormat.MAYA_BINARY;
     System.out.printf("Extension of %s is %s", format, format.getExtension());
```
### getExtensions() {#getExtensions--}
```
public String[] getExtensions()
```


このタイプの拡張子名一覧を取得します。

**Returns:**
java.lang.String[] - この型の拡張子名の一覧。
### getFileFormatType() {#getFileFormatType--}
```
public FileFormatType getFileFormatType()
```


ファイル形式のタイプを取得します

**Returns:**
[FileFormatType](../../com.aspose.threed/fileformattype) - file format type
### getFormatByExtension(String extensionName) {#getFormatByExtension-java.lang.String-}
```
public static FileFormat getFormatByExtension(String extensionName)
```


拡張子名から優先されるファイル形式を取得します。拡張子名はドット ('.') で始まる必要があります。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| extensionName | java.lang.String | 拡張子名はクエリのために '.' で始まります。 |

**Returns:**
[FileFormat](../../com.aspose.threed/fileformat) - Instance of [FileFormat](../../com.aspose.threed/fileformat), otherwise null returned. **Example:** The following code shows how to save scene to memory using specified format

```
Scene scene = new Scene(new Box());
     var outputFormat = ".glb";
     var format = FileFormat.getFormatByExtension(outputFormat);
     var output = new ByteArrayOutputStream();
     scene.save(output);
```
### getFormats() {#getFormats--}
```
public static List<FileFormat> getFormats()
```


すべてのサポートされている形式にアクセスする

**Returns:**
java.util.List<com.aspose.threed.FileFormat> - サポートされているすべての形式へのアクセス
### getVersion() {#getVersion--}
```
public Version getVersion()
```


ファイル形式のバージョンを取得します

**Returns:**
[Version](../../com.aspose.threed/version) - file format version
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### loadAttributes(Scene scene, Stream stream) {#loadAttributes-com.aspose.threed.Scene-com.aspose.threed.Stream-}
```
public void loadAttributes(Scene scene, Stream stream)
```


指定されたストリームから属性をロードする

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| scene | [Scene](../../com.aspose.threed/scene) | 属性が適用されるシーン |
| stream | [Stream](../../com.aspose.threed/stream) | 属性を含むストリーム |

### loadAttributes(Scene scene, Stream stream, String prefix) {#loadAttributes-com.aspose.threed.Scene-com.aspose.threed.Stream-java.lang.String-}
```
public void loadAttributes(Scene scene, Stream stream, String prefix)
```


指定されたストリームから属性をロードする

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| scene | [Scene](../../com.aspose.threed/scene) | 属性が適用されるシーン |
| stream | [Stream](../../com.aspose.threed/stream) | 属性を含むストリーム |
| プレフィックス | java.lang.String | 名前の競合を避けるために使用される属性のプレフィックス、デフォルト値は "rvm:" です |

### loadAttributes(Scene scene, String fileName) {#loadAttributes-com.aspose.threed.Scene-java.lang.String-}
```
public void loadAttributes(Scene scene, String fileName)
```


指定されたファイル名から属性をロードする

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| scene | [Scene](../../com.aspose.threed/scene) | 属性が適用されるシーン |
| fileName | java.lang.String | 属性を含むファイル名 |

### loadAttributes(Scene scene, String fileName, String prefix) {#loadAttributes-com.aspose.threed.Scene-java.lang.String-java.lang.String-}
```
public void loadAttributes(Scene scene, String fileName, String prefix)
```


指定されたファイル名から属性をロードする

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| scene | [Scene](../../com.aspose.threed/scene) | 属性が適用されるシーン |
| fileName | java.lang.String | 属性を含むファイル名 |
| プレフィックス | java.lang.String | 名前の競合を避けるために使用される属性のプレフィックス、デフォルト値は "rvm:" です |

### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### toString() {#toString--}
```
public String toString()
```


形式を文字列に変換する

**Returns:**
java.lang.String - オブジェクト文字列
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


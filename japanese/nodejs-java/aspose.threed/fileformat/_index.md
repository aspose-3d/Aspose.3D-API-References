---
title: "ファイル形式"
second_title: "Node.js 用 Java 経由の Aspose.3D API リファレンス"
description: 
type: docs

url: /ja/nodejs-java/aspose.threed/fileformat/
---
## FileFormat class

ファイル形式の定義  @hideconstructor


## プロパティ

| 名前 | 説明 |
| --- | --- |
| MAYA_BINARY | バイナリ形式のAutodesk Maya |
| STL_BINARY | バイナリSTLファイル形式 |
| STLASCII | ASCII STLファイル形式 |
| COLLADA | Colladaファイル形式 |
| GLTF | Khronos GroupのglTF |
| GLTF_BINARY | Khronos Groupのバイナリ形式glTF |
| PDF | Adobeのポータブルドキュメント形式 |
| DXF | AutoCAD DXF |
| PLY | Polygon File FormatまたはStanford Triangle Format |
| X_BINARY | バイナリ形式のDirectX Xファイル |
| X_TEXT | バイナリ形式のDirectX Xファイル |
| DRACO | Google Draco Mesh |
| RVM_TEXT | テキスト形式の AVEVA Plant Design Management System Model |
| RVM_BINARY | バイナリ形式の AVEVA Plant Design Management System Model |
| ASE | 3D Studio Max の ASCII Scene Exporter フォーマット。 |
| IFC | ISO 16739-1 Industry Foundation Classes データモデル。 |
| AMF | 付加製造ファイルフォーマット |
| VRML | バーチャルリアリティモデリング言語 |
| ZIP | 他の 3d ファイル形式を含む Zip アーカイブ。 |
| USD | ユニバーサルシーン記述 |
| USDZ | 圧縮されたユニバーサルシーン記述 |
| XYZ | Xyz 点群ファイル |
| PCD | PCL Point Cloud Data の ASCII モードファイル |
| PCD_BINARY | PCL Point Cloud Data のバイナリモードファイル |

## メソッド

### getVersion{#getVersion}

| 名前 | 説明 |
| --- | --- |
| getVersion() | ファイル形式のバージョンを取得します |

 **Result:**



---


### getExtension{#getExtension}

| 名前 | 説明 |
| --- | --- |
| getExtension() | このタイプの拡張子名を取得します。 |

 **Result:**



---


### getExtensions{#getExtensions}

| 名前 | 説明 |
| --- | --- |
| getExtensions() | このタイプの拡張子名を取得します。 |

 **Result:**



---


### getContentType{#getContentType}

| 名前 | 説明 |
| --- | --- |
| getContentType() | ファイル形式のコンテンツタイプを取得します。このプロパティの値は FileContentType 整数定数です。 |

 **Result:**



---


### getFileFormatType{#getFileFormatType}

| 名前 | 説明 |
| --- | --- |
| getFileFormatType() | ファイル形式のタイプを取得します |

 **Result:**



---


### getFormatByExtension{#getFormatByExtension}

| 名前 | 説明 |
| --- | --- |
| getFormatByExtension(extensionName) | ファイル拡張子名から優先されるファイル形式を取得します。拡張子名はピリオド（'.'）で始まる必要があります。 |

 **Parameters:**

| 名前 | 型 | 説明 |
| --- | --- | --- |
| extensionNam | 文字列 | null |

 **Result:**
ファイル形式


---


### detect{#detect}

| 名前 | 説明 |
| --- | --- |
| detect(fileName) | ファイル名からファイル形式を検出します。ファイルは読み取り可能である必要があり、Aspose.3D はファイルヘッダーを通じてファイル形式を検出できます。 |

 **Parameters:**

| 名前 | 型 | 説明 |
| --- | --- | --- |
| fileNam | 文字列 | null |

 **Result:**
ファイル形式


---


### createLoadOptions{#createLoadOptions}

| 名前 | 説明 |
| --- | --- |
| createLoadOptions() | このファイル形式のデフォルトのロードオプションを作成します |

 **Result:**
LoadOptions


---


### createSaveOptions{#createSaveOptions}

| 名前 | 説明 |
| --- | --- |
| createSaveOptions() | このファイル形式のデフォルトの保存オプションを作成します |

 **Result:**
SaveOptions


---


### toString{#toString}

| 名前 | 説明 |
| --- | --- |
| toString() | フォーマットを文字列に変換 |

 **Result:**
文字列


---




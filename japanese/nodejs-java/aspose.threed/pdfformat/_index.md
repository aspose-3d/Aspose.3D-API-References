---
title: "PdfFormat"
second_title: "Node.js 用 Java 経由の Aspose.3D API リファレンス"
description: 
type: docs

url: /ja/nodejs-java/aspose.threed/pdfformat/
---
## PdfFormat class

AdobeのPortable Document Format  @hideconstructor


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


### extract{#extract}

| 名前 | 説明 |
| --- | --- |
| extract(fileName, password) | PDF ファイルから生の 3D コンテンツを抽出します。 |

 **Parameters:**

| 名前 | 型 | 説明 |
| --- | --- | --- |
| fileNam | 文字列 | null |
| パスワード | byte[] | null |

 **Result:**
0, Culture=neutral, PublicKeyToken=b77a5c561934e089]]


---


### extractScene{#extractScene}

| 名前 | 説明 |
| --- | --- |
| extractScene(fileName) | PDF ファイルから 3D シーンを抽出します。 |

 **Parameters:**

| 名前 | 型 | 説明 |
| --- | --- | --- |
| fileNam | 文字列 | null |

 **Result:**
0, Culture=neutral, PublicKeyToken=f071c641d0b4582b]]


---


### extractScene{#extractScene}

| 名前 | 説明 |
| --- | --- |
| extractScene(fileName, password) | PDF ファイルから 3D シーンを抽出します。 |

 **Parameters:**

| 名前 | 型 | 説明 |
| --- | --- | --- |
| fileNam | 文字列 | null |
| パスワード | byte[] | null |

 **Result:**
0, Culture=neutral, PublicKeyToken=f071c641d0b4582b]]


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




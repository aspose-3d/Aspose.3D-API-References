---
title: "RvmFormat"
second_title: "Node.js 用 Java 経由の Aspose.3D API リファレンス"
description: 
type: docs

url: /ja/nodejs-java/aspose.threed/rvmformat/
---
## RvmFormat class

RVM フォーマット  @hideconstructor


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


### loadAttributes{#loadAttributes}

| 名前 | 説明 |
| --- | --- |
| loadAttributes(scene, fileName, prefix) | 指定されたファイル名から属性をロードします |

 **Parameters:**

| 名前 | 型 | 説明 |
| --- | --- | --- |
| シーン | Scene | 属性が適用されるシーン |
| fileName | 文字列 | 属性を含むファイル名 |
| prefix | 文字列 | 属性名の競合を回避するために使用される属性のプレフィックス。デフォルト値は "rvm:" です |

 **Result:**



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




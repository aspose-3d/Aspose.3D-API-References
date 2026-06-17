---
title: "DracoFormat"
second_title: "Node.js 用 Java 経由の Aspose.3D API リファレンス"
description: 
type: docs

url: /ja/nodejs-java/aspose.threed/dracoformat/
---
## DracoFormat class

Google Draco フォーマット  @hideconstructor


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


### decode{#decode}

| 名前 | 説明 |
| --- | --- |
| decode(fileName) | 指定されたファイル名から点群またはメッシュをデコードします |

 **Parameters:**

| 名前 | 型 | 説明 |
| --- | --- | --- |
| fileName | 文字列 | ファイル名にはdrcファイルが含まれています |

 **Result:**
ジオメトリ


---


### decode{#decode}

| 名前 | 説明 |
| --- | --- |
| decode(data) | メモリデータから点群またはメッシュをデコードします |

 **Parameters:**

| 名前 | 型 | 説明 |
| --- | --- | --- |
| data | byte[] | 生のdrcバイト |

 **Result:**
ジオメトリ


---


### encode{#encode}

| 名前 | 説明 |
| --- | --- |
| encode(entity, fileName, options) | エンティティを指定されたファイルにエンコードします |

 **Parameters:**

| 名前 | 型 | 説明 |
| --- | --- | --- |
| エンティティ | エンティティ | エンコードされるエンティティ |
| fileName | 文字列 | 書き込まれるファイル名 |
| オプション | DracoSaveOptions | 点群をエンコードするための追加オプション |

 **Result:**
ジオメトリ


---


### encode{#encode}

| 名前 | 説明 |
| --- | --- |
| encode(entity, options) | エンティティをDracoの生データにエンコードします |

 **Parameters:**

| 名前 | 型 | 説明 |
| --- | --- | --- |
| エンティティ | エンティティ | エンコードされるエンティティ |
| オプション | DracoSaveOptions | 点群をエンコードするための追加オプション |

 **Result:**
byte[]


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




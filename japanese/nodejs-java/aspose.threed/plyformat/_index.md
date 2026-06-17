---
title: "PlyFormat"
second_title: "Node.js 用 Java 経由の Aspose.3D API リファレンス"
description: 
type: docs

url: /ja/nodejs-java/aspose.threed/plyformat/
---
## PlyFormat class

PLY形式。  @hideconstructor


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


### encode{#encode}

| 名前 | 説明 |
| --- | --- |
| encode(entity, fileName) | エンティティをエンコードし、結果を外部ファイルに保存します。 |

 **Parameters:**

| 名前 | 型 | 説明 |
| --- | --- | --- |
| エンティティ | エンティティ | エンコードするエンティティ |
| fileName | 文字列 | 書き込むファイル |

 **Result:**



---


### encode{#encode}

| 名前 | 説明 |
| --- | --- |
| encode(entity, fileName, opt) | エンティティをエンコードし、結果を外部ファイルに保存します。 |

 **Parameters:**

| 名前 | 型 | 説明 |
| --- | --- | --- |
| エンティティ | エンティティ | エンコードするエンティティ |
| fileName | 文字列 | 書き込むファイル |
| opt | PlySaveOptions | 保存オプション |

 **Result:**



---


### decode{#decode}

| 名前 | 説明 |
| --- | --- |
| decode(fileName) | 指定されたストリームから点群またはメッシュをデコードします。 |

 **Parameters:**

| 名前 | 型 | 説明 |
| --- | --- | --- |
| fileName | 文字列 | 入力ストリーム |

 **Result:**
ジオメトリ


---


### decode{#decode}

| 名前 | 説明 |
| --- | --- |
| decode(fileName, opt) | 指定されたストリームから点群またはメッシュをデコードします。 |

 **Parameters:**

| 名前 | 型 | 説明 |
| --- | --- | --- |
| fileName | 文字列 | 入力ストリーム |
| opt | PlyLoadOptions | PLY形式のロードオプション |

 **Result:**
ジオメトリ


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




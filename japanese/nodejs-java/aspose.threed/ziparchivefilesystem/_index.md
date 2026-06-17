---
title: "ZipArchiveFileSystem"
second_title: "Node.js 用 Java 経由の Aspose.3D API リファレンス"
description: 
type: docs

url: /ja/nodejs-java/aspose.threed/ziparchivefilesystem/
---
## ZipArchiveFileSystem class

指定された zip ファイルまたは zip ストリームへの読み取り専用アクセスを提供するファイルシステムです。ファイルシステムは開く/保存する操作の後に破棄されます。


## メソッド

### constructor{#constructor}

| 名前 | 説明 |
| --- | --- |
| constructor(fileName) | ファイル名を使用して ZipArchiveFileSystem を構築します。 |

 **Parameters:**

| 名前 | 型 | 説明 |
| --- | --- | --- |
| fileNam | 文字列 | null |

 **Result:**



---


### readFile{#readFile}

| 名前 | 説明 |
| --- | --- |
| readFile(fileName, options) | 読み取り用にファイルを開く |

 **Parameters:**

| 名前 | 型 | 説明 |
| --- | --- | --- |
| fileNam | 文字列 | null |
| オプション | IOConfig | null |

 **Result:**
Stream


---


### writeFile{#writeFile}

| 名前 | 説明 |
| --- | --- |
| writeFile(fileName, options) | 書き込み用にファイルを開く（このクラスでは実装されていません）。 |

 **Parameters:**

| 名前 | 型 | 説明 |
| --- | --- | --- |
| fileNam | 文字列 | null |
| オプション | IOConfig | null |

 **Result:**
Stream


---




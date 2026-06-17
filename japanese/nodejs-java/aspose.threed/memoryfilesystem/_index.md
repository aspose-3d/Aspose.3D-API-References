---
title: "MemoryFileSystem"
second_title: "Node.js 用 Java 経由の Aspose.3D API リファレンス"
description: 
type: docs

url: /ja/nodejs-java/aspose.threed/memoryfilesystem/
---
## MemoryFileSystem class

MemoryFileSystem は読み書き操作をメモリにマップします。


## メソッド

### constructor{#constructor}

| 名前 | 説明 |
| --- | --- |
| constructor() |  |

 **Result:**



---


### getFileNames{#getFileNames}

| 名前 | 説明 |
| --- | --- |
| getFileNames() | このメモリファイルシステムに含まれるファイル名。 |

 **Result:**



---


### getFileContent{#getFileContent}

| 名前 | 説明 |
| --- | --- |
| getFileContent(fileName) | 指定されたファイルの生データを返します。指定されたファイルが存在しない場合は System.IO.FileNotFoundException をスローします。 |

 **Parameters:**

| 名前 | 型 | 説明 |
| --- | --- | --- |
| fileNam | 文字列 | null |

 **Result:**
byte[]


---


### readFile{#readFile}

| 名前 | 説明 |
| --- | --- |
| readFile(fileName, options) | 依存関係を読み取るためのストリームを作成します。 |

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
| writeFile(fileName, options) | 依存関係を書き込むためのストリームを作成します。 |

 **Parameters:**

| 名前 | 型 | 説明 |
| --- | --- | --- |
| fileNam | 文字列 | null |
| オプション | IOConfig | null |

 **Result:**
Stream


---




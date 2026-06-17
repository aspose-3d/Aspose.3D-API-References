---
title: "RvmSaveOptions"
second_title: "Node.js 用 Java 経由の Aspose.3D API リファレンス"
description: 
type: docs

url: /ja/nodejs-java/aspose.threed/rvmsaveoptions/
---
## RvmSaveOptions class

Aveva PDMS RVM ファイルの保存オプション。


## メソッド

### constructor{#constructor}

| 名前 | 説明 |
| --- | --- |
| constructor() | RvmSaveOptions のコンストラクタ |

 **Result:**



---


### constructor_overload{#constructor_overload}

| 名前 | 説明 |
| --- | --- |
| constructor_overload(contentType) | RvmSaveOptions のコンストラクタ |

 **Parameters:**

| 名前 | 型 | 説明 |
| --- | --- | --- |
| contentType | FileContentType | FileContentType |

 **Result:**



---


### getFileNote{#getFileNote}

| 名前 | 説明 |
| --- | --- |
| getFileNote() | ファイルヘッダー内のファイルノート。 |

 **Result:**



---


### setFileNote{#setFileNote}

| 名前 | 説明 |
| --- | --- |
| setFileNote(value) | ファイルヘッダー内のファイルノート。 |

 **Result:**



---


### getAuthor{#getAuthor}

| 名前 | 説明 |
| --- | --- |
| getAuthor() |  |

 **Result:**



---


### setAuthor{#setAuthor}

| 名前 | 説明 |
| --- | --- |
| setAuthor(value) |  |

 **Result:**



---


### getCreationTime{#getCreationTime}

| 名前 | 説明 |
| --- | --- |
| getCreationTime() | このファイルをエクスポートしたタイムスタンプ。デフォルト値は現在時刻です。 |

 **Result:**



---


### setCreationTime{#setCreationTime}

| 名前 | 説明 |
| --- | --- |
| setCreationTime(value) | このファイルをエクスポートしたタイムスタンプ。デフォルト値は現在時刻です。 |

 **Result:**



---


### getAttributePrefix{#getAttributePrefix}

| 名前 | 説明 |
| --- | --- |
| getAttributePrefix() | エクスポートされる属性のプレフィックスを取得または設定します。エクスポートされたプロパティにはプレフィックスが含まれません。異なるプレフィックスを持つカスタムプロパティはエクスポートされません。デフォルト値は 'rvm:' です。例えば、プロパティが rvm:Refno=345 の場合、エクスポートされる属性は Refno = 345 となり、プレフィックスは除去されます。 |

 **Result:**



---


### setAttributePrefix{#setAttributePrefix}

| 名前 | 説明 |
| --- | --- |
| setAttributePrefix(value) | エクスポートされる属性のプレフィックスを取得または設定します。エクスポートされたプロパティにはプレフィックスが含まれません。異なるプレフィックスを持つカスタムプロパティはエクスポートされません。デフォルト値は 'rvm:' です。例えば、プロパティが rvm:Refno=345 の場合、エクスポートされる属性は Refno = 345 となり、プレフィックスは除去されます。 |

 **Result:**



---


### getAttributeListFile{#getAttributeListFile}

| 名前 | 説明 |
| --- | --- |
| getAttributeListFile() | 属性リストファイルのファイル名を取得または設定します。プロパティが未定義の場合、エクスポーターは .rvm ファイル名に基づいて名前を生成します。デフォルト値は null です。 |

 **Result:**



---


### setAttributeListFile{#setAttributeListFile}

| 名前 | 説明 |
| --- | --- |
| setAttributeListFile(value) | 属性リストファイルのファイル名を取得または設定します。プロパティが未定義の場合、エクスポーターは .rvm ファイル名に基づいて名前を生成します。デフォルト値は null です。 |

 **Result:**



---


### getExportAttributes{#getExportAttributes}

| 名前 | 説明 |
| --- | --- |
| getExportAttributes() | 属性リストを外部の .att ファイルにエクスポートするかどうかを取得または設定します。デフォルト値は false です。 |

 **Result:**



---


### setExportAttributes{#setExportAttributes}

| 名前 | 説明 |
| --- | --- |
| setExportAttributes(value) | 属性リストを外部の .att ファイルにエクスポートするかどうかを取得または設定します。デフォルト値は false です。 |

 **Result:**



---


### getExportTextures{#getExportTextures}

| 名前 | 説明 |
| --- | --- |
| getExportTextures() | シーンで使用されているテクスチャを出力ディレクトリにコピーしようとします。 |

 **Result:**



---


### setExportTextures{#setExportTextures}

| 名前 | 説明 |
| --- | --- |
| setExportTextures(value) | シーンで使用されているテクスチャを出力ディレクトリにコピーしようとします。 |

 **Result:**



---


### getFileFormat{#getFileFormat}

| 名前 | 説明 |
| --- | --- |
| getFileFormat() | 現在の保存/読み込みオプションで指定されたファイル形式を取得します。 |

 **Result:**



---


### getEncoding{#getEncoding}

| 名前 | 説明 |
| --- | --- |
| getEncoding() | テキストベースのファイルのデフォルトエンコーディングを取得または設定します。デフォルト値は null で、インポーター/エクスポーターが使用するエンコーディングを決定します。 |

 **Result:**



---


### getFileSystem{#getFileSystem}

| 名前 | 説明 |
| --- | --- |
| getFileSystem() | ロード/セーブ時に外部依存関係を管理する方法をユーザーが処理できるようにします。 |

 **Result:**



---


### setFileSystem{#setFileSystem}

| 名前 | 説明 |
| --- | --- |
| setFileSystem(value) | ロード/セーブ時に外部依存関係を管理する方法をユーザーが処理できるようにします。 |

 **Result:**



---


### getLookupPaths{#getLookupPaths}

| 名前 | 説明 |
| --- | --- |
| getLookupPaths() | OBJ のような一部のファイルは外部ファイルに依存しており、検索パスにより Aspose.3D が外部ファイルを探してロードできるようになります。 |

 **Result:**



---


### getFileName{#getFileName}

| 名前 | 説明 |
| --- | --- |
| getFileName() | エクスポート/インポートシーンのファイル名です。これはオプションですが、OBJ のマテリアルなど外部アセットをシリアライズする際に便利です。 |

 **Result:**



---


### setFileName{#setFileName}

| 名前 | 説明 |
| --- | --- |
| setFileName(value) | エクスポート/インポートシーンのファイル名です。これはオプションですが、OBJ のマテリアルなど外部アセットをシリアライズする際に便利です。 |

 **Result:**



---




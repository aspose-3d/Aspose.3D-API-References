---
title: "StlLoadOptions"
second_title: "Node.js 用 Java 経由の Aspose.3D API リファレンス"
description: 
type: docs

url: /ja/nodejs-java/aspose.threed/stlloadoptions/
---
## StlLoadOptions class

STLのロードオプション


## メソッド

### constructor{#constructor}

| 名前 | 説明 |
| --- | --- |
| constructor() | 新しい StlLoadOptions インスタンスを初期化します。 |

 **Result:**



---


### constructor_overload{#constructor_overload}

| 名前 | 説明 |
| --- | --- |
| constructor_overload(contentType) | 新しい StlLoadOptions インスタンスを初期化します。 |

 **Parameters:**

| 名前 | 型 | 説明 |
| --- | --- | --- |
| contentType | FileContentType | FileContentType |

 **Result:**



---


### getFlipCoordinateSystem{#getFlipCoordinateSystem}

| 名前 | 説明 |
| --- | --- |
| getFlipCoordinateSystem() | インポート時に制御点/法線の座標系を反転させるかどうかを取得または設定します。 |

 **Result:**



---


### setFlipCoordinateSystem{#setFlipCoordinateSystem}

| 名前 | 説明 |
| --- | --- |
| setFlipCoordinateSystem(value) | インポート時に制御点/法線の座標系を反転させるかどうかを取得または設定します。 |

 **Result:**



---


### getRecalculateNormal{#getRecalculateNormal}

| 名前 | 説明 |
| --- | --- |
| getRecalculateNormal() | STL ファイルに保存されている法線データを無視し、頂点位置に基づいて法線データを再計算します。デフォルト値は false です。 |

 **Result:**



---


### setRecalculateNormal{#setRecalculateNormal}

| 名前 | 説明 |
| --- | --- |
| setRecalculateNormal(value) | STL ファイルに保存されている法線データを無視し、頂点位置に基づいて法線データを再計算します。デフォルト値は false です。 |

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




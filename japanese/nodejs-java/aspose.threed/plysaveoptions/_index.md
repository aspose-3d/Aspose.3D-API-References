---
title: "PlySaveOptions"
second_title: "Node.js 用 Java 経由の Aspose.3D API リファレンス"
description: 
type: docs

url: /ja/nodejs-java/aspose.threed/plysaveoptions/
---
## PlySaveOptions class

シーンをPLYファイルとしてエクスポートする際の保存オプション。


## メソッド

### constructor{#constructor}

| 名前 | 説明 |
| --- | --- |
| constructor() | PlySaveOptions のコンストラクタ |

 **Result:**



---


### constructor_overload{#constructor_overload}

| 名前 | 説明 |
| --- | --- |
| constructor_overload(contentType) | PlySaveOptions のコンストラクタ |

 **Parameters:**

| 名前 | 型 | 説明 |
| --- | --- | --- |
| contentType | FileContentType | FileContentType |

 **Result:**



---


### getPointCloud{#getPointCloud}

| 名前 | 説明 |
| --- | --- |
| getPointCloud() | シーンを点群としてエクスポートします。デフォルト値は false です。 |

 **Result:**



---


### setPointCloud{#setPointCloud}

| 名前 | 説明 |
| --- | --- |
| setPointCloud(value) | シーンを点群としてエクスポートします。デフォルト値は false です。 |

 **Result:**



---


### getFlipCoordinate{#getFlipCoordinate}

| 名前 | 説明 |
| --- | --- |
| getFlipCoordinate() | シーンを保存する際に座標を反転させます。デフォルト値は true です。 |

 **Result:**



---


### setFlipCoordinate{#setFlipCoordinate}

| 名前 | 説明 |
| --- | --- |
| setFlipCoordinate(value) | シーンを保存する際に座標を反転させます。デフォルト値は true です。 |

 **Result:**



---


### getVertexElement{#getVertexElement}

| 名前 | 説明 |
| --- | --- |
| getVertexElement() | 頂点データの要素名で、デフォルト値は "vertex" です。 |

 **Result:**



---


### setVertexElement{#setVertexElement}

| 名前 | 説明 |
| --- | --- |
| setVertexElement(value) | 頂点データの要素名で、デフォルト値は "vertex" です。 |

 **Result:**



---


### getPositionComponents{#getPositionComponents}

| 名前 | 説明 |
| --- | --- |
| getPositionComponents() | 位置データのコンポーネント名で、デフォルト値は ("x", "y", "z") です。 |

 **Result:**



---


### getNormalComponents{#getNormalComponents}

| 名前 | 説明 |
| --- | --- |
| getNormalComponents() | 法線データのコンポーネント名で、デフォルト値は ("nx", "ny", "nz") です。 |

 **Result:**



---


### getTextureCoordinateComponents{#getTextureCoordinateComponents}

| 名前 | 説明 |
| --- | --- |
| getTextureCoordinateComponents() | テクスチャ座標データのコンポーネント名で、デフォルト値は ("u", "v") です |

 **Result:**



---


### getColorComponents{#getColorComponents}

| 名前 | 説明 |
| --- | --- |
| getColorComponents() | 頂点カラーのコンポーネント名で、デフォルト値は ("red", "green", "blue") です |

 **Result:**



---


### getFaceElement{#getFaceElement}

| 名前 | 説明 |
| --- | --- |
| getFaceElement() | 面データの要素名で、デフォルト値は "face" です |

 **Result:**



---


### setFaceElement{#setFaceElement}

| 名前 | 説明 |
| --- | --- |
| setFaceElement(value) | 面データの要素名で、デフォルト値は "face" です |

 **Result:**



---


### getFaceProperty{#getFaceProperty}

| 名前 | 説明 |
| --- | --- |
| getFaceProperty() | 面データのプロパティ名で、デフォルト値は "vertex_index" です |

 **Result:**



---


### setFaceProperty{#setFaceProperty}

| 名前 | 説明 |
| --- | --- |
| setFaceProperty(value) | 面データのプロパティ名で、デフォルト値は "vertex_index" です |

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




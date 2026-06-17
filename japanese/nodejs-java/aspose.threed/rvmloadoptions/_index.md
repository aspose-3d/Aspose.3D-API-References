---
title: "RvmLoadOptions"
second_title: "Node.js 用 Java 経由の Aspose.3D API リファレンス"
description: 
type: docs

url: /ja/nodejs-java/aspose.threed/rvmloadoptions/
---
## RvmLoadOptions class

AVEVA Plant Design Management System の RVM ファイルのロードオプション。


## メソッド

### constructor{#constructor}

| 名前 | 説明 |
| --- | --- |
| constructor(contentType) | RvmLoadOptions のインスタンスを作成します。 |

 **Parameters:**

| 名前 | 型 | 説明 |
| --- | --- | --- |
| contentType | FileContentType | FileContentType |

 **Result:**



---


### constructor_overload{#constructor_overload}

| 名前 | 説明 |
| --- | --- |
| constructor_overload() | RvmLoadOptions のインスタンスを作成します。 |

 **Result:**



---


### getGenerateMaterials{#getGenerateMaterials}

| 名前 | 説明 |
| --- | --- |
| getGenerateMaterials() | シーン内の各オブジェクトに対して、カラー テーブルが RVM ファイル内にエクスポートされていない場合、ランダムな色でマテリアルを生成します。デフォルト値は true です。 |

 **Result:**



---


### setGenerateMaterials{#setGenerateMaterials}

| 名前 | 説明 |
| --- | --- |
| setGenerateMaterials(value) | シーン内の各オブジェクトに対して、カラー テーブルが RVM ファイル内にエクスポートされていない場合、ランダムな色でマテリアルを生成します。デフォルト値は true です。 |

 **Result:**



---


### getCylinderRadialSegments{#getCylinderRadialSegments}

| 名前 | 説明 |
| --- | --- |
| getCylinderRadialSegments() | シリンダーの放射状セグメント数を取得または設定します。デフォルト値は 16 です。 |

 **Result:**



---


### setCylinderRadialSegments{#setCylinderRadialSegments}

| 名前 | 説明 |
| --- | --- |
| setCylinderRadialSegments(value) | シリンダーの放射状セグメント数を取得または設定します。デフォルト値は 16 です。 |

 **Result:**



---


### getDishLongitudeSegments{#getDishLongitudeSegments}

| 名前 | 説明 |
| --- | --- |
| getDishLongitudeSegments() | ディッシュの経度セグメント数を取得または設定します。デフォルト値は 12 です。 |

 **Result:**



---


### setDishLongitudeSegments{#setDishLongitudeSegments}

| 名前 | 説明 |
| --- | --- |
| setDishLongitudeSegments(value) | ディッシュの経度セグメント数を取得または設定します。デフォルト値は 12 です。 |

 **Result:**



---


### getDishLatitudeSegments{#getDishLatitudeSegments}

| 名前 | 説明 |
| --- | --- |
| getDishLatitudeSegments() | ディッシュの緯度セグメント数を取得または設定します。デフォルト値は 8 です。 |

 **Result:**



---


### setDishLatitudeSegments{#setDishLatitudeSegments}

| 名前 | 説明 |
| --- | --- |
| setDishLatitudeSegments(value) | ディッシュの緯度セグメント数を取得または設定します。デフォルト値は 8 です。 |

 **Result:**



---


### getTorusTubularSegments{#getTorusTubularSegments}

| 名前 | 説明 |
| --- | --- |
| getTorusTubularSegments() | トーラスのチューブ状セグメント数を取得または設定します。デフォルト値は 20 です。 |

 **Result:**



---


### setTorusTubularSegments{#setTorusTubularSegments}

| 名前 | 説明 |
| --- | --- |
| setTorusTubularSegments(value) | トーラスのチューブ状セグメント数を取得または設定します。デフォルト値は 20 です。 |

 **Result:**



---


### getRectangularTorusSegments{#getRectangularTorusSegments}

| 名前 | 説明 |
| --- | --- |
| getRectangularTorusSegments() | 矩形トーラスの放射状セグメント数を取得または設定します。デフォルト値は 20 です。 |

 **Result:**



---


### setRectangularTorusSegments{#setRectangularTorusSegments}

| 名前 | 説明 |
| --- | --- |
| setRectangularTorusSegments(value) | 矩形トーラスの放射状セグメント数を取得または設定します。デフォルト値は 20 です。 |

 **Result:**



---


### getCenterScene{#getCenterScene}

| 名前 | 説明 |
| --- | --- |
| getCenterScene() | シーンがロードされた後に中心に配置します。 |

 **Result:**



---


### setCenterScene{#setCenterScene}

| 名前 | 説明 |
| --- | --- |
| setCenterScene(value) | シーンがロードされた後に中心に配置します。 |

 **Result:**



---


### getAttributePrefix{#getAttributePrefix}

| 名前 | 説明 |
| --- | --- |
| getAttributePrefix() | 外部属性ファイルで定義された属性のプレフィックスを取得または設定します。プレフィックスは名前の衝突を防ぐために使用され、デフォルト値は "rvm:" です。 |

 **Result:**



---


### setAttributePrefix{#setAttributePrefix}

| 名前 | 説明 |
| --- | --- |
| setAttributePrefix(value) | 外部属性ファイルで定義された属性のプレフィックスを取得または設定します。プレフィックスは名前の衝突を防ぐために使用され、デフォルト値は "rvm:" です。 |

 **Result:**



---


### getLookupAttributes{#getLookupAttributes}

| 名前 | 説明 |
| --- | --- |
| getLookupAttributes() | 外部属性リストファイル（.att/.attrib/.txt）から属性をロードするかどうかを取得または設定します。デフォルト値は true です。 |

 **Result:**



---


### setLookupAttributes{#setLookupAttributes}

| 名前 | 説明 |
| --- | --- |
| setLookupAttributes(value) | 外部属性リストファイル（.att/.attrib/.txt）から属性をロードするかどうかを取得または設定します。デフォルト値は true です。 |

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




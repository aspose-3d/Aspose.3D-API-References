---
title: "DracoSaveOptions"
second_title: "Node.js 用 Java 経由の Aspose.3D API リファレンス"
description: 
type: docs

url: /ja/nodejs-java/aspose.threed/dracosaveoptions/
---
## DracoSaveOptions class

Google Draco ファイルの保存オプション


## メソッド

### constructor{#constructor}

| 名前 | 説明 |
| --- | --- |
| constructor() | draco ファイルを保存するためのデフォルト構成を作成します。 |

 **Result:**



---


### getPositionBits{#getPositionBits}

| 名前 | 説明 |
| --- | --- |
| getPositionBits() | 位置の量子化ビット数、デフォルト値は 14 です |

 **Result:**



---


### setPositionBits{#setPositionBits}

| 名前 | 説明 |
| --- | --- |
| setPositionBits(value) | 位置の量子化ビット数、デフォルト値は 14 です |

 **Result:**



---


### getTextureCoordinateBits{#getTextureCoordinateBits}

| 名前 | 説明 |
| --- | --- |
| getTextureCoordinateBits() | テクスチャ座標の量子化ビット数、デフォルト値は 12 です |

 **Result:**



---


### setTextureCoordinateBits{#setTextureCoordinateBits}

| 名前 | 説明 |
| --- | --- |
| setTextureCoordinateBits(value) | テクスチャ座標の量子化ビット数、デフォルト値は 12 です |

 **Result:**



---


### getColorBits{#getColorBits}

| 名前 | 説明 |
| --- | --- |
| getColorBits() | 頂点カラーの量子化ビット数、デフォルト値は 10 です |

 **Result:**



---


### setColorBits{#setColorBits}

| 名前 | 説明 |
| --- | --- |
| setColorBits(value) | 頂点カラーの量子化ビット数、デフォルト値は 10 です |

 **Result:**



---


### getNormalBits{#getNormalBits}

| 名前 | 説明 |
| --- | --- |
| getNormalBits() | 法線ベクトルの量子化ビット数、デフォルト値は 10 です |

 **Result:**



---


### setNormalBits{#setNormalBits}

| 名前 | 説明 |
| --- | --- |
| setNormalBits(value) | 法線ベクトルの量子化ビット数、デフォルト値は 10 です |

 **Result:**



---


### getCompressionLevel{#getCompressionLevel}

| 名前 | 説明 |
| --- | --- |
| getCompressionLevel() | 圧縮レベル、デフォルト値は DracoCompressionLevel.STANDARD です。このプロパティの値は DracoCompressionLevel の整数定数です。 |

 **Result:**



---


### setCompressionLevel{#setCompressionLevel}

| 名前 | 説明 |
| --- | --- |
| setCompressionLevel(value) | 圧縮レベル、デフォルト値は DracoCompressionLevel.STANDARD です。このプロパティの値は DracoCompressionLevel の整数定数です。 |

 **Result:**



---


### getApplyUnitScale{#getApplyUnitScale}

| 名前 | 説明 |
| --- | --- |
| getApplyUnitScale() | AssetInfo.UnitScaleFactor をメッシュに適用します。デフォルト値は false です。 |

 **Result:**



---


### setApplyUnitScale{#setApplyUnitScale}

| 名前 | 説明 |
| --- | --- |
| setApplyUnitScale(value) | AssetInfo.UnitScaleFactor をメッシュに適用します。デフォルト値は false です。 |

 **Result:**



---


### getPointCloud{#getPointCloud}

| 名前 | 説明 |
| --- | --- |
| getPointCloud() | シーンをポイントクラウドとしてエクスポートします。デフォルト値は false です。 |

 **Result:**



---


### setPointCloud{#setPointCloud}

| 名前 | 説明 |
| --- | --- |
| setPointCloud(value) | シーンをポイントクラウドとしてエクスポートします。デフォルト値は false です。 |

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




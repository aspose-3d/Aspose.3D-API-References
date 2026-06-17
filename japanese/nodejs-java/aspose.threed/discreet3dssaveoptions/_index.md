---
title: "Discreet3dsSaveOptions"
second_title: "Node.js 用 Java 経由の Aspose.3D API リファレンス"
description: 
type: docs

url: /ja/nodejs-java/aspose.threed/discreet3dssaveoptions/
---
## Discreet3dsSaveOptions class

3DS ファイルの保存オプションです。


## メソッド

### constructor{#constructor}

| 名前 | 説明 |
| --- | --- |
| constructor() | Discreet3dsSaveOptions のコンストラクタ |

 **Result:**



---


### getExportLight{#getExportLight}

| 名前 | 説明 |
| --- | --- |
| getExportLight() | シーン内のすべてのライトをエクスポートするかどうかを取得または設定します。 |

 **Result:**



---


### setExportLight{#setExportLight}

| 名前 | 説明 |
| --- | --- |
| setExportLight(value) | シーン内のすべてのライトをエクスポートするかどうかを取得または設定します。 |

 **Result:**



---


### getExportCamera{#getExportCamera}

| 名前 | 説明 |
| --- | --- |
| getExportCamera() | シーン内のすべてのカメラをエクスポートするかどうかを取得または設定します。 |

 **Result:**



---


### setExportCamera{#setExportCamera}

| 名前 | 説明 |
| --- | --- |
| setExportCamera(value) | シーン内のすべてのカメラをエクスポートするかどうかを取得または設定します。 |

 **Result:**



---


### getDuplicatedNameSeparator{#getDuplicatedNameSeparator}

| 名前 | 説明 |
| --- | --- |
| getDuplicatedNameSeparator() | オブジェクト名と重複カウンタの間の区切り文字で、デフォルト値は "_" です。シーンに同じ名前を使用するオブジェクトが含まれる場合、Aspose.3D 3DS エクスポーターはオブジェクトに別の名前を生成します。例えば、"Box" という名前のノードが2つある場合、最初のノードは名前 "Box" を持ち、2番目のノードはデフォルト設定を使用して新しい名前 "Box_2" になります。 |

 **Result:**



---


### setDuplicatedNameSeparator{#setDuplicatedNameSeparator}

| 名前 | 説明 |
| --- | --- |
| setDuplicatedNameSeparator(value) | オブジェクト名と重複カウンタの間の区切り文字で、デフォルト値は "_" です。シーンに同じ名前を使用するオブジェクトが含まれる場合、Aspose.3D 3DS エクスポーターはオブジェクトに別の名前を生成します。例えば、"Box" という名前のノードが2つある場合、最初のノードは名前 "Box" を持ち、2番目のノードはデフォルト設定を使用して新しい名前 "Box_2" になります。 |

 **Result:**



---


### getDuplicatedNameCounterBase{#getDuplicatedNameCounterBase}

| 名前 | 説明 |
| --- | --- |
| getDuplicatedNameCounterBase() | 重複した名前の新しい名前を生成する際に使用されるカウンタで、デフォルト値は 2 です。 |

 **Result:**



---


### setDuplicatedNameCounterBase{#setDuplicatedNameCounterBase}

| 名前 | 説明 |
| --- | --- |
| setDuplicatedNameCounterBase(value) | 重複した名前の新しい名前を生成する際に使用されるカウンタで、デフォルト値は 2 です。 |

 **Result:**



---


### getDuplicatedNameCounterFormat{#getDuplicatedNameCounterFormat}

| 名前 | 説明 |
| --- | --- |
| getDuplicatedNameCounterFormat() | 重複カウンタの形式で、デフォルト値は空文字列です。 |

 **Result:**



---


### setDuplicatedNameCounterFormat{#setDuplicatedNameCounterFormat}

| 名前 | 説明 |
| --- | --- |
| setDuplicatedNameCounterFormat(value) | 重複カウンタの形式で、デフォルト値は空文字列です。 |

 **Result:**



---


### getMasterScale{#getMasterScale}

| 名前 | 説明 |
| --- | --- |
| getMasterScale() | エクスポート時に使用されるマスタースケールを取得または設定します。 |

 **Result:**



---


### setMasterScale{#setMasterScale}

| 名前 | 説明 |
| --- | --- |
| setMasterScale(value) | エクスポート時に使用されるマスタースケールを取得または設定します。 |

 **Result:**



---


### getGammaCorrectedColor{#getGammaCorrectedColor}

| 名前 | 説明 |
| --- | --- |
| getGammaCorrectedColor() | 3ds ファイルは同じ属性に対して元の色とガンマ補正された色の両方を含む場合があります。この設定を true にすると、可能な限りガンマ補正された色が使用され、そうでなければ Aspose.3D は元の色を使用しようとします。 |

 **Result:**



---


### setGammaCorrectedColor{#setGammaCorrectedColor}

| 名前 | 説明 |
| --- | --- |
| setGammaCorrectedColor(value) | 3ds ファイルは同じ属性に対して元の色とガンマ補正された色の両方を含む場合があります。この設定を true にすると、可能な限りガンマ補正された色が使用され、そうでなければ Aspose.3D は元の色を使用しようとします。 |

 **Result:**



---


### getFlipCoordinateSystem{#getFlipCoordinateSystem}

| 名前 | 説明 |
| --- | --- |
| getFlipCoordinateSystem() | インポート/エクスポート時にコントロールポイント/法線のフリップ座標系を取得または設定します。 |

 **Result:**



---


### setFlipCoordinateSystem{#setFlipCoordinateSystem}

| 名前 | 説明 |
| --- | --- |
| setFlipCoordinateSystem(value) | インポート/エクスポート時にコントロールポイント/法線のフリップ座標系を取得または設定します。 |

 **Result:**



---


### getHighPreciseColor{#getHighPreciseColor}

| 名前 | 説明 |
| --- | --- |
| getHighPreciseColor() | この値が true の場合、生成された 3ds ファイルは高精度カラーを使用します。つまり、赤/緑/青の各チャンネルが 32 ビット浮動小数点になります。そうでない場合、生成されたファイルは 24 ビットカラーを使用し、各チャンネルは 8 ビットバイトになります。デフォルト値は false です。すべてのアプリケーションが高精度カラーをサポートしているわけではないためです。 |

 **Result:**



---


### setHighPreciseColor{#setHighPreciseColor}

| 名前 | 説明 |
| --- | --- |
| setHighPreciseColor(value) | この値が true の場合、生成された 3ds ファイルは高精度カラーを使用します。つまり、赤/緑/青の各チャンネルが 32 ビット浮動小数点になります。そうでない場合、生成されたファイルは 24 ビットカラーを使用し、各チャンネルは 8 ビットバイトになります。デフォルト値は false です。すべてのアプリケーションが高精度カラーをサポートしているわけではないためです。 |

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




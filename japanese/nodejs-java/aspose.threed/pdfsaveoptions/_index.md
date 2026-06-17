---
title: "PdfSaveOptions"
second_title: "Node.js 用 Java 経由の Aspose.3D API リファレンス"
description: 
type: docs

url: /ja/nodejs-java/aspose.threed/pdfsaveoptions/
---
## PdfSaveOptions class

PDFエクスポート時の保存オプション。


## メソッド

### constructor{#constructor}

| 名前 | 説明 |
| --- | --- |
| constructor() | PdfSaveOptions のコンストラクタ |

 **Result:**



---


### getRenderMode{#getRenderMode}

| 名前 | 説明 |
| --- | --- |
| getRenderMode() | レンダーモードは3Dアートワークがレンダリングされるスタイルを指定します。プロパティの値は PdfRenderMode 整数定数です。 |

 **Result:**



---


### setRenderMode{#setRenderMode}

| 名前 | 説明 |
| --- | --- |
| setRenderMode(value) | レンダーモードは3Dアートワークがレンダリングされるスタイルを指定します。プロパティの値は PdfRenderMode 整数定数です。 |

 **Result:**



---


### getLightingScheme{#getLightingScheme}

| 名前 | 説明 |
| --- | --- |
| getLightingScheme() | LightingScheme は3Dアートワークに適用する照明を指定します。プロパティの値は PdfLightingScheme 整数定数です。 |

 **Result:**



---


### setLightingScheme{#setLightingScheme}

| 名前 | 説明 |
| --- | --- |
| setLightingScheme(value) | LightingScheme は3Dアートワークに適用する照明を指定します。プロパティの値は PdfLightingScheme 整数定数です。 |

 **Result:**



---


### getBackgroundColor{#getBackgroundColor}

| 名前 | 説明 |
| --- | --- |
| getBackgroundColor() | PDFファイル内の3Dビューの背景色。 |

 **Result:**



---


### setBackgroundColor{#setBackgroundColor}

| 名前 | 説明 |
| --- | --- |
| setBackgroundColor(value) | PDFファイル内の3Dビューの背景色。 |

 **Result:**



---


### getFaceColor{#getFaceColor}

| 名前 | 説明 |
| --- | --- |
| getFaceColor() | 3Dコンテンツをレンダリングする際に使用されるフェイスカラーを取得または設定します。これは RenderMode が Illustration の値を持つ場合にのみ関連します。 |

 **Result:**



---


### setFaceColor{#setFaceColor}

| 名前 | 説明 |
| --- | --- |
| setFaceColor(value) | 3Dコンテンツをレンダリングする際に使用されるフェイスカラーを取得または設定します。これは RenderMode が Illustration の値を持つ場合にのみ関連します。 |

 **Result:**



---


### getAuxiliaryColor{#getAuxiliaryColor}

| 名前 | 説明 |
| --- | --- |
| getAuxiliaryColor() | 3Dコンテンツをレンダリングする際に使用される補助カラーを取得または設定します。このカラーの解釈は RenderMode に依存します。 |

 **Result:**



---


### setAuxiliaryColor{#setAuxiliaryColor}

| 名前 | 説明 |
| --- | --- |
| setAuxiliaryColor(value) | 3Dコンテンツをレンダリングする際に使用される補助カラーを取得または設定します。このカラーの解釈は RenderMode に依存します。 |

 **Result:**



---


### getFlipCoordinateSystem{#getFlipCoordinateSystem}

| 名前 | 説明 |
| --- | --- |
| getFlipCoordinateSystem() | エクスポート中にシーンの座標系を反転させるかどうかを取得または設定します。 |

 **Result:**



---


### setFlipCoordinateSystem{#setFlipCoordinateSystem}

| 名前 | 説明 |
| --- | --- |
| setFlipCoordinateSystem(value) | エクスポート中にシーンの座標系を反転させるかどうかを取得または設定します。 |

 **Result:**



---


### getEmbedTextures{#getEmbedTextures}

| 名前 | 説明 |
| --- | --- |
| getEmbedTextures() | 外部テクスチャをPDFファイルに埋め込みます。デフォルト値は false です。 |

 **Result:**



---


### setEmbedTextures{#setEmbedTextures}

| 名前 | 説明 |
| --- | --- |
| setEmbedTextures(value) | 外部テクスチャをPDFファイルに埋め込みます。デフォルト値は false です。 |

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




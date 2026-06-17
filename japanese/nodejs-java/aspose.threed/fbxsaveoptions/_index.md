---
title: "FbxSaveOptions"
second_title: "Node.js 用 Java 経由の Aspose.3D API リファレンス"
description: 
type: docs

url: /ja/nodejs-java/aspose.threed/fbxsaveoptions/
---
## FbxSaveOptions class

Fbx ファイルの保存オプションです。


## メソッド

### constructor{#constructor}

| 名前 | 説明 |
| --- | --- |
| constructor(format) | FbxSaveOptions を初期化します |

 **Parameters:**

| 名前 | 型 | 説明 |
| --- | --- | --- |
| 形式 | ファイル形式 | null |

 **Result:**



---


### constructor_overload{#constructor_overload}

| 名前 | 説明 |
| --- | --- |
| constructor_overload(contentType) | 最新のサポートバージョンを使用して FbxSaveOptions を初期化します。 |

 **Parameters:**

| 名前 | 型 | 説明 |
| --- | --- | --- |
| contentType | FileContentType | FileContentType |

 **Result:**



---


### getReusePrimitiveMesh{#getReusePrimitiveMesh}

| 名前 | 説明 |
| --- | --- |
| getReusePrimitiveMesh() | 同じパラメータを持つプリミティブのメッシュを再利用します。これにより、CAD ファイルからインポートされたような多数のプリミティブ形状で構成されたシーンの FBX 出力サイズが大幅に削減されます。デフォルト値は false です。 |

 **Result:**



---


### setReusePrimitiveMesh{#setReusePrimitiveMesh}

| 名前 | 説明 |
| --- | --- |
| setReusePrimitiveMesh(value) | 同じパラメータを持つプリミティブのメッシュを再利用します。これにより、CAD ファイルからインポートされたような多数のプリミティブ形状で構成されたシーンの FBX 出力サイズが大幅に削減されます。デフォルト値は false です。 |

 **Result:**



---


### getEnableCompression{#getEnableCompression}

| 名前 | 説明 |
| --- | --- |
| getEnableCompression() | FBX ファイル内の大きなバイナリデータ（例: アニメーションデータ、コントロールポイント、頂点要素データ、インデックス）を圧縮します。デフォルト値は true です。 |

 **Result:**



---


### setEnableCompression{#setEnableCompression}

| 名前 | 説明 |
| --- | --- |
| setEnableCompression(value) | FBX ファイル内の大きなバイナリデータ（例: アニメーションデータ、コントロールポイント、頂点要素データ、インデックス）を圧縮します。デフォルト値は true です。 |

 **Result:**



---


### getFoldRepeatedCurveData{#getFoldRepeatedCurveData}

| 名前 | 説明 |
| --- | --- |
| getFoldRepeatedCurveData() | 繰り返し曲線データを再利用するかどうかを取得または設定します。最後のデータの参照カウントを増やすことで再利用する場合は true、そうでない場合は false です。 |

 **Result:**



---


### getExportLegacyMaterialProperties{#getExportLegacyMaterialProperties}

| 名前 | 説明 |
| --- | --- |
| getExportLegacyMaterialProperties() | レガシー素材プロパティをエクスポートするかどうかを取得または設定します。後方互換性のために使用されます。このオプションはデフォルトで有効になっています。 |

 **Result:**



---


### setExportLegacyMaterialProperties{#setExportLegacyMaterialProperties}

| 名前 | 説明 |
| --- | --- |
| setExportLegacyMaterialProperties(value) | レガシー素材プロパティをエクスポートするかどうかを取得または設定します。後方互換性のために使用されます。このオプションはデフォルトで有効になっています。 |

 **Result:**



---


### getVideoForTexture{#getVideoForTexture}

| 名前 | 説明 |
| --- | --- |
| getVideoForTexture() | FBX としてエクスポートする際に、テクスチャ用の Video インスタンスを生成するかどうかを取得または設定します。 |

 **Result:**



---


### setVideoForTexture{#setVideoForTexture}

| 名前 | 説明 |
| --- | --- |
| setVideoForTexture(value) | FBX としてエクスポートする際に、テクスチャ用の Video インスタンスを生成するかどうかを取得または設定します。 |

 **Result:**



---


### getEmbedTextures{#getEmbedTextures}

| 名前 | 説明 |
| --- | --- |
| getEmbedTextures() | テクスチャを最終出力ファイルに埋め込むかどうかを取得または設定します。FBX エクスポーターはファイルシステムからテクスチャの生データを探し、最終 FBX ファイルに埋め込みます。デフォルト値は false です。 |

 **Result:**



---


### setEmbedTextures{#setEmbedTextures}

| 名前 | 説明 |
| --- | --- |
| setEmbedTextures(value) | テクスチャを最終出力ファイルに埋め込むかどうかを取得または設定します。FBX エクスポーターはファイルシステムからテクスチャの生データを探し、最終 FBX ファイルに埋め込みます。デフォルト値は false です。 |

 **Result:**



---


### getGenerateVertexElementMaterial{#getGenerateVertexElementMaterial}

| 名前 | 説明 |
| --- | --- |
| getGenerateVertexElementMaterial() | アタッチされたノードがマテリアルを含む場合、ジオメトリに常に VertexElementMaterial を生成するかどうかを取得または設定します。デフォルトでは無効になっています。 |

 **Result:**



---


### setGenerateVertexElementMaterial{#setGenerateVertexElementMaterial}

| 名前 | 説明 |
| --- | --- |
| setGenerateVertexElementMaterial(value) | アタッチされたノードがマテリアルを含む場合、ジオメトリに常に VertexElementMaterial を生成するかどうかを取得または設定します。デフォルトでは無効になっています。 |

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




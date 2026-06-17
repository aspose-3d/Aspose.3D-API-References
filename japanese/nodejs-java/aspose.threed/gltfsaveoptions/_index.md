---
title: "GltfSaveOptions"
second_title: "Node.js 用 Java 経由の Aspose.3D API リファレンス"
description: 
type: docs

url: /ja/nodejs-java/aspose.threed/gltfsaveoptions/
---
## GltfSaveOptions class

glTF 形式の保存オプションです。


## メソッド

### constructor{#constructor}

| 名前 | 説明 |
| --- | --- |
| constructor(contentType) | GltfSaveOptions のコンストラクタ |

 **Parameters:**

| 名前 | 型 | 説明 |
| --- | --- | --- |
| contentType | FileContentType | FileContentType |

 **Result:**



---


### constructor_overload{#constructor_overload}

| 名前 | 説明 |
| --- | --- |
| constructor_overload(format) | GltfSaveOptions のコンストラクタ |

 **Parameters:**

| 名前 | 型 | 説明 |
| --- | --- | --- |
| 形式 | ファイル形式 | null |

 **Result:**



---


### getPrettyPrint{#getPrettyPrint}

| 名前 | 説明 |
| --- | --- |
| getPrettyPrint() | GLTF ファイルの JSON コンテンツは人間が読みやすいようにインデントされます。デフォルト値は false です。 |

 **Result:**



---


### setPrettyPrint{#setPrettyPrint}

| 名前 | 説明 |
| --- | --- |
| setPrettyPrint(value) | GLTF ファイルの JSON コンテンツは人間が読みやすいようにインデントされます。デフォルト値は false です。 |

 **Result:**



---


### getFallbackNormal{#getFallbackNormal}

| 名前 | 説明 |
| --- | --- |
| getFallbackNormal() | GLTF2 エクスポーターが無効な法線を検出したとき、検証を回避するために元の値の代わりにこれが使用されます。デフォルト値は (0, 1, 0) です。 |

 **Result:**



---


### getEmbedAssets{#getEmbedAssets}

| 名前 | 説明 |
| --- | --- |
| getEmbedAssets() | すべての外部アセットを base64 でエンコードし、ASCII モードで単一ファイルに埋め込みます。デフォルト値は false です。 |

 **Result:**



---


### setEmbedAssets{#setEmbedAssets}

| 名前 | 説明 |
| --- | --- |
| setEmbedAssets(value) | すべての外部アセットを base64 でエンコードし、ASCII モードで単一ファイルに埋め込みます。デフォルト値は false です。 |

 **Result:**



---


### getImageFormat{#getImageFormat}

| 名前 | 説明 |
| --- | --- |
| getImageFormat() | 標準の glTF はテクスチャ形式として PNG/JPG のみをサポートしており、このオプションはエクスポート時に Aspose.3D が非標準画像をサポートされている形式に変換する方法を案内します。デフォルト値は GltfEmbeddedImageFormat.PNG です。このプロパティの値は GltfEmbeddedImageFormat の整数定数です。 |

 **Result:**



---


### setImageFormat{#setImageFormat}

| 名前 | 説明 |
| --- | --- |
| setImageFormat(value) | 標準の glTF はテクスチャ形式として PNG/JPG のみをサポートしており、このオプションはエクスポート時に Aspose.3D が非標準画像をサポートされている形式に変換する方法を案内します。デフォルト値は GltfEmbeddedImageFormat.PNG です。このプロパティの値は GltfEmbeddedImageFormat の整数定数です。 |

 **Result:**



---


### getMaterialConverter{#getMaterialConverter}

| 名前 | 説明 |
| --- | --- |
| getMaterialConverter() | ジオメトリのマテリアルを PBR マテリアルに変換するカスタムコンバータです。これが未設定の場合、glTF 2.0 エクスポーターは標準マテリアルを自動的に PBR マテリアルに変換します。デフォルト値は null です。このプロパティはシーンを glTF 2.0 ファイルにエクスポートする際に使用されます。 |

 **Result:**



---


### setMaterialConverter{#setMaterialConverter}

| 名前 | 説明 |
| --- | --- |
| setMaterialConverter(value) | ジオメトリのマテリアルを PBR マテリアルに変換するカスタムコンバータです。これが未設定の場合、glTF 2.0 エクスポーターは標準マテリアルを自動的に PBR マテリアルに変換します。デフォルト値は null です。このプロパティはシーンを glTF 2.0 ファイルにエクスポートする際に使用されます。 |

 **Result:**



---


### getUseCommonMaterials{#getUseCommonMaterials}

| 名前 | 説明 |
| --- | --- |
| getUseCommonMaterials() | KHR 共通マテリアル拡張を使用してマテリアルをシリアライズします。デフォルト値は false です。これを false に設定すると、#Error Cref: P:Aspose.ThreeD.Formats.GltfSaveOptions.ExportShaders がある場合に Aspose.3D が頂点/フラグメントシェーダのセットをエクスポートします。 |

 **Result:**



---


### setUseCommonMaterials{#setUseCommonMaterials}

| 名前 | 説明 |
| --- | --- |
| setUseCommonMaterials(value) | KHR 共通マテリアル拡張を使用してマテリアルをシリアライズします。デフォルト値は false です。これを false に設定すると、#Error Cref: P:Aspose.ThreeD.Formats.GltfSaveOptions.ExportShaders がある場合に Aspose.3D が頂点/フラグメントシェーダのセットをエクスポートします。 |

 **Result:**



---


### getExternalDracoEncoder{#getExternalDracoEncoder}

| 名前 | 説明 |
| --- | --- |
| getExternalDracoEncoder() | 外部の draco エンコーダを使用して draco 圧縮速度を高速化します。Aspose.3D はメッシュを draco 形式にエンコードするための新しいサブプロセスを作成します。自己責任で使用してください。 |

 **Result:**



---


### setExternalDracoEncoder{#setExternalDracoEncoder}

| 名前 | 説明 |
| --- | --- |
| setExternalDracoEncoder(value) | 外部の draco エンコーダを使用して draco 圧縮速度を高速化します。Aspose.3D はメッシュを draco 形式にエンコードするための新しいサブプロセスを作成します。自己責任で使用してください。 |

 **Result:**



---


### getFlipTexCoordV{#getFlipTexCoordV}

| 名前 | 説明 |
| --- | --- |
| getFlipTexCoordV() | テクスチャ座標 v(t) 成分を反転します。デフォルト値は true です。 |

 **Result:**



---


### setFlipTexCoordV{#setFlipTexCoordV}

| 名前 | 説明 |
| --- | --- |
| setFlipTexCoordV(value) | テクスチャ座標 v(t) 成分を反転します。デフォルト値は true です。 |

 **Result:**



---


### getBufferFile{#getBufferFile}

| 名前 | 説明 |
| --- | --- |
| getBufferFile() | バイナリデータを格納するために使用される外部バッファファイルのファイル名です。このファイルが指定されていない場合、Aspose.3D が名前を自動生成します。glTF をバイナリモードでエクスポートする際は無視されます。 |

 **Result:**



---


### setBufferFile{#setBufferFile}

| 名前 | 説明 |
| --- | --- |
| setBufferFile(value) | バイナリデータを格納するために使用される外部バッファファイルのファイル名です。このファイルが指定されていない場合、Aspose.3D が名前を自動生成します。glTF をバイナリモードでエクスポートする際は無視されます。 |

 **Result:**



---


### getSaveExtras{#getSaveExtras}

| 名前 | 説明 |
| --- | --- |
| getSaveExtras() | シーンオブジェクトの動的プロパティを生成された glTF ファイルの 'extra' フィールドに保存します。アプリケーション固有のデータを提供するのに便利です。デフォルト値は false です。 |

 **Result:**



---


### setSaveExtras{#setSaveExtras}

| 名前 | 説明 |
| --- | --- |
| setSaveExtras(value) | シーンオブジェクトの動的プロパティを生成された glTF ファイルの 'extra' フィールドに保存します。アプリケーション固有のデータを提供するのに便利です。デフォルト値は false です。 |

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


### getDracoCompression{#getDracoCompression}

| 名前 | 説明 |
| --- | --- |
| getDracoCompression() | draco 圧縮を有効にするかどうかを取得または設定します |

 **Result:**



---


### setDracoCompression{#setDracoCompression}

| 名前 | 説明 |
| --- | --- |
| setDracoCompression(value) | draco 圧縮を有効にするかどうかを取得または設定します |

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




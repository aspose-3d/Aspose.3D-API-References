---
title: "UsdSaveOptions"
second_title: "Node.js 用 Java 経由の Aspose.3D API リファレンス"
description: 
type: docs

url: /ja/nodejs-java/aspose.threed/usdsaveoptions/
---
## UsdSaveOptions class

USD/USDZ フォーマットの保存オプション。


## メソッド

### constructor{#constructor}

| 名前 | 説明 |
| --- | --- |
| constructor() | FileFormat.USD フォーマットで新しい UsdSaveOptions を初期化します。 |

 **Result:**



---


### constructor_overload{#constructor_overload}

| 名前 | 説明 |
| --- | --- |
| constructor_overload(fileFormat) | 指定された USD/USDZ フォーマットで新しい UsdSaveOptions を初期化します。 |

 **Result:**



---


### getPrimitiveToMesh{#getPrimitiveToMesh}

| 名前 | 説明 |
| --- | --- |
| getPrimitiveToMesh() | エクスポート時にプリミティブエンティティをメッシュに変換します。または、プリミティブを直接出力ファイルにエンコードします（Dish や Torus などの非公式プリミティブには Aspose の拡張定義が使用されます）。デフォルト値は true です。 |

 **Result:**



---


### setPrimitiveToMesh{#setPrimitiveToMesh}

| 名前 | 説明 |
| --- | --- |
| setPrimitiveToMesh(value) | エクスポート時にプリミティブエンティティをメッシュに変換します。または、プリミティブを直接出力ファイルにエンコードします（Dish や Torus などの非公式プリミティブには Aspose の拡張定義が使用されます）。デフォルト値は true です。 |

 **Result:**



---


### getExportMetaData{#getExportMetaData}

| 名前 | 説明 |
| --- | --- |
| getExportMetaData() | USD の customData フィールドを介してノードのプロパティをエクスポートします。 |

 **Result:**



---


### setExportMetaData{#setExportMetaData}

| 名前 | 説明 |
| --- | --- |
| setExportMetaData(value) | USD の customData フィールドを介してノードのプロパティをエクスポートします。 |

 **Result:**



---


### getMaterialConverter{#getMaterialConverter}

| 名前 | 説明 |
| --- | --- |
| getMaterialConverter() | ジオメトリのマテリアルを PBR マテリアルに変換するカスタムコンバータです。未割り当ての場合、USD エクスポーターは標準マテリアルを自動的に PBR マテリアルに変換します。デフォルト値は null です。 |

 **Result:**



---


### setMaterialConverter{#setMaterialConverter}

| 名前 | 説明 |
| --- | --- |
| setMaterialConverter(value) | ジオメトリのマテリアルを PBR マテリアルに変換するカスタムコンバータです。未割り当ての場合、USD エクスポーターは標準マテリアルを自動的に PBR マテリアルに変換します。デフォルト値は null です。 |

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




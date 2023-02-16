---
title: PlySaveOptions
second_title: Aspose.3D for.NETAPIリファレンス
description: シーンを PLY ファイルとしてエクスポートするための保存オプション.
type: docs
weight: 1300
url: /ja/net/aspose.threed.formats/plysaveoptions/
---
## PlySaveOptions class

シーンを PLY ファイルとしてエクスポートするための保存オプション.

```csharp
public class PlySaveOptions : SaveOptions
```

## コンストラクター

| 名前 | 説明 |
| --- | --- |
| [PlySaveOptions](plysaveoptions/#constructor)() | のコンストラクター`PlySaveOptions` |
| [PlySaveOptions](plysaveoptions/#constructor_1)(FileContentType) | のコンストラクター`PlySaveOptions` |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [ColorComponents](../../aspose.threed.formats/plysaveoptions/colorcomponents/) { get; set; } | 頂点カラーのコンポーネント名、デフォルト値は ("red", "green", "blue") |
| [Encoding](../../aspose.threed.formats/ioconfig/encoding/) { get; set; } | テキストベースのファイルのデフォルト エンコーディングを取得または設定します。 デフォルト値は null です。これは、インポーター/エクスポーターが使用するエンコーディングを決定することを意味します。 |
| [FaceElement](../../aspose.threed.formats/plysaveoptions/faceelement/) { get; set; } | 顔データの要素名、デフォルト値は「顔」 |
| [FaceProperty](../../aspose.threed.formats/plysaveoptions/faceproperty/) { get; set; } | 面データのプロパティ名、デフォルト値は「頂点インデックス」 |
| [FileFormat](../../aspose.threed.formats/ioconfig/fileformat/) { get; } | 現在の保存/読み込みオプションで指定されたファイル形式を取得します。 |
| [FileName](../../aspose.threed.formats/ioconfig/filename/) { get; set; } | エクスポート/インポートするシーンのファイル名. これはオプションですが、OBJ のマテリアルなどの外部アセットをシリアル化するときに役立ちます. |
| [FileSystem](../../aspose.threed.formats/ioconfig/filesystem/) { get; set; } | ロード/保存中に外部依存関係を管理する方法をユーザーが処理できるようにします。 |
| [FlipCoordinate](../../aspose.threed.formats/plysaveoptions/flipcoordinate/) { get; set; } | シーンの保存中に座標を反転します。デフォルト値は true です |
| [LookupPaths](../../aspose.threed.formats/ioconfig/lookuppaths/) { get; set; } | OBJ などの一部のファイルは外部ファイルに依存します。ルックアップ パスにより、Aspose.3D はロードする外部ファイルを検索できます。 |
| [NormalComponents](../../aspose.threed.formats/plysaveoptions/normalcomponents/) { get; set; } | 通常データのコンポーネント名、デフォルト値は ("nx", "ny", "nz") |
| [PointCloud](../../aspose.threed.formats/plysaveoptions/pointcloud/) { get; set; } | シーンをポイント クラウドとしてエクスポートします。デフォルト値は false です。 |
| [PositionComponents](../../aspose.threed.formats/plysaveoptions/positioncomponents/) { get; set; } | 位置データのコンポーネント名、デフォルト値は ("x", "y", "z") |
| [TextureCoordinateComponents](../../aspose.threed.formats/plysaveoptions/texturecoordinatecomponents/) { get; set; } | テクスチャ座標データのコンポーネント名、デフォルト値は ("u", "v") |
| [VertexElement](../../aspose.threed.formats/plysaveoptions/vertexelement/) { get; set; } | 頂点データの要素名、デフォルト値は「頂点」 |

### 関連項目

* class [SaveOptions](../saveoptions/)
* 名前空間 [Aspose.ThreeD.Formats](../../aspose.threed.formats/)
* 組み立て [Aspose.3D](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.3D.dll -->
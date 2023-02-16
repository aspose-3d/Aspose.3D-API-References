---
title: StlLoadOptions
second_title: Aspose.3D for.NETAPIリファレンス
description: STL の読み込みオプション
type: docs
weight: 1350
url: /ja/net/aspose.threed.formats/stlloadoptions/
---
## StlLoadOptions class

STL の読み込みオプション

```csharp
public class StlLoadOptions : LoadOptions
```

## コンストラクター

| 名前 | 説明 |
| --- | --- |
| [StlLoadOptions](stlloadoptions/#constructor)() | 新しいの初期化`StlLoadOptions`インスタンス. |
| [StlLoadOptions](stlloadoptions/#constructor_1)(FileContentType) | 新しいの初期化`StlLoadOptions`インスタンス. |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [Encoding](../../aspose.threed.formats/ioconfig/encoding/) { get; set; } | テキストベースのファイルのデフォルト エンコーディングを取得または設定します。 デフォルト値は null です。これは、インポーター/エクスポーターが使用するエンコーディングを決定することを意味します。 |
| [FileFormat](../../aspose.threed.formats/ioconfig/fileformat/) { get; } | 現在の保存/読み込みオプションで指定されたファイル形式を取得します。 |
| [FileName](../../aspose.threed.formats/ioconfig/filename/) { get; set; } | エクスポート/インポートするシーンのファイル名. これはオプションですが、OBJ のマテリアルなどの外部アセットをシリアル化するときに役立ちます. |
| [FileSystem](../../aspose.threed.formats/ioconfig/filesystem/) { get; set; } | ロード/保存中に外部依存関係を管理する方法をユーザーが処理できるようにします。 |
| [FlipCoordinateSystem](../../aspose.threed.formats/stlloadoptions/flipcoordinatesystem/) { get; set; } | インポート中に制御点/法線の座標系を反転するかどうかを取得または設定します. |
| [LookupPaths](../../aspose.threed.formats/ioconfig/lookuppaths/) { get; set; } | OBJ などの一部のファイルは外部ファイルに依存します。ルックアップ パスにより、Aspose.3D はロードする外部ファイルを検索できます。 |
| [RecalculateNormal](../../aspose.threed.formats/stlloadoptions/recalculatenormal/) { get; set; } | STL ファイルに格納された法線データを無視し、頂点位置に基づいて法線データを再計算します。 デフォルト値は false です。 |

### 関連項目

* class [LoadOptions](../loadoptions/)
* 名前空間 [Aspose.ThreeD.Formats](../../aspose.threed.formats/)
* 組み立て [Aspose.3D](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.3D.dll -->
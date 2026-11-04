---
title: "クラス JtLoadOptions"
second_title: "Aspose.3D for .NET API リファレンス"
description: "Aspose.ThreeD.Formats.JtLoadOptions クラス。Siemens JT 用のロードオプションです。"
type: docs
weight: 1310
url: /ja/net/aspose.threed.formats/jtloadoptions/
---
## JtLoadOptions class

Siemens JT のロードオプション

```csharp
public class JtLoadOptions : LoadOptions
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [JtLoadOptions](jtloadoptions/)() | デフォルトコンストラクタです。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [Encoding](../../aspose.threed.formats/ioconfig/encoding/) { get; set; } | テキストベースのファイルのデフォルトエンコーディングを取得または設定します。デフォルト値は null で、インポーター/エクスポーターが使用するエンコーディングを決定します。 |
| [FileFormat](../../aspose.threed.formats/ioconfig/fileformat/) { get; } | 現在の保存/読み込みオプションで指定されたファイル形式を取得します。 |
| [FileName](../../aspose.threed.formats/ioconfig/filename/) { get; set; } | エクスポート/インポートシーンのファイル名です。これはオプションですが、OBJ のマテリアルなどの外部アセットをシリアライズする際に便利です。 |
| [FileSystem](../../aspose.threed.formats/ioconfig/filesystem/) { get; set; } | ロード/セーブ時に外部依存関係を管理する方法をユーザーが扱えるようにします。 |
| [LoadPMI](../../aspose.threed.formats/jtloadoptions/loadpmi/) { get; set; } | 可能であれば JT ファイルから PMI 情報をロードし、データは [`AssetInfo`](../../aspose.threed/scene/assetinfo/) のプロパティ "PMI" として保存されます。デフォルト値は false です。 |
| [LoadProperties](../../aspose.threed.formats/jtloadoptions/loadproperties/) { get; set; } | JT のプロパティテーブルから Aspose.3D のプロパティとしてロードします。デフォルト値は false です。 |
| [LookupPaths](../../aspose.threed.formats/ioconfig/lookuppaths/) { get; set; } | OBJ のような一部のファイルは外部ファイルに依存しており、検索パスにより Aspose.3D が外部ファイルをロードできるようになります。 |

### 関連項目

* class [LoadOptions](../loadoptions/)
* namespace [Aspose.ThreeD.Formats](../../aspose.threed.formats/)
* assembly [Aspose.3D](../../)



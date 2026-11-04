---
title: "クラス JtLoadOptions"
second_title: "Aspose.3D for .NET API リファレンス"
description: "Aspose.ThreeD.Formats.SiemensJT.JtLoadOptions クラス。Siemens JT のロードオプション"
type: docs
weight: 1380
url: /ja/net/aspose.threed.formats.siemensjt/jtloadoptions/
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
| [Encoding](../../aspose.threed.formats/ioconfig/encoding/) { get; set; } | テキストベースのファイルのデフォルトエンコーディングを取得または設定します。デフォルト値は null で、インポーター/エクスポーターが使用するエンコーディングを決定します。（[`IOConfig`](../../aspose.threed.formats/ioconfig/) から継承） |
| [FileFormat](../../aspose.threed.formats/ioconfig/fileformat/) { get; } | 現在の保存/ロードオプションで指定されたファイル形式を取得します。（[`IOConfig`](../../aspose.threed.formats/ioconfig/) から継承） |
| [FileName](../../aspose.threed.formats/ioconfig/filename/) { get; set; } | エクスポート/インポートシーンのファイル名です。これはオプションですが、OBJ のマテリアルなど外部アセットをシリアライズする際に便利です。（[`IOConfig`](../../aspose.threed.formats/ioconfig/) から継承） |
| [FileSystem](../../aspose.threed.formats/ioconfig/filesystem/) { get; set; } | ロード/セーブ時の外部依存関係の管理方法をユーザーが処理できるようにします。（[`IOConfig`](../../aspose.threed.formats/ioconfig/) から継承） |
| [LoadPMI](../../aspose.threed.formats.siemensjt/jtloadoptions/loadpmi/) { get; set; } | 可能であれば JT ファイルから PMI 情報をロードし、データは [`AssetInfo`](../../aspose.threed/scene/assetinfo/) のプロパティ "PMI" として保存されます。デフォルト値は false です。 |
| [LoadProperties](../../aspose.threed.formats.siemensjt/jtloadoptions/loadproperties/) { get; set; } | JT のプロパティテーブルから Aspose.3D のプロパティとしてロードします。デフォルト値は false です。 |
| [LookupPaths](../../aspose.threed.formats/ioconfig/lookuppaths/) { get; set; } | OBJ のように外部ファイルに依存するファイルもあり、検索パスにより Aspose.3D が外部ファイルを探してロードできるようになります。（[`IOConfig`](../../aspose.threed.formats/ioconfig/) から継承） |

### 関連項目

* class [LoadOptions](../../aspose.threed.formats/loadoptions/)
* namespace [Aspose.ThreeD.Formats.SiemensJT](../../aspose.threed.formats.siemensjt/)
* assembly [Aspose.3D](../../)



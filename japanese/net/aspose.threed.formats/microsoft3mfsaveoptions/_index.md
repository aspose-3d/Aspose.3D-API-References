---
title: "クラス Microsoft3MFSaveOptions"
second_title: "Aspose.3D for .NET API リファレンス"
description: "Aspose.ThreeD.Formats.Microsoft3MFSaveOptions クラス。Microsoft 3MF ファイルの保存オプション"
type: docs
weight: 1350
url: /ja/net/aspose.threed.formats/microsoft3mfsaveoptions/
---
## Microsoft3MFSaveOptions class

Microsoft 3MF ファイルの保存オプション。

```csharp
public class Microsoft3MFSaveOptions : SaveOptions
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [Microsoft3MFSaveOptions](microsoft3mfsaveoptions/)() | `Microsoft3MFSaveOptions` を構築する |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [BuildAll](../../aspose.threed.formats/microsoft3mfsaveoptions/buildall/) { get; set; } | シーン内のすべてのジオメトリを印刷可能としてマークします。または、[`SetBuildable`](../microsoft3mfformat/setbuildable/) を使用してノードを手動で印刷可能にマークできます。デフォルト値は true です |
| [EnableCompression](../../aspose.threed.formats/microsoft3mfsaveoptions/enablecompression/) { get; set; } | 出力 3mf ファイルで圧縮を有効にします。デフォルト値は true です |
| [Encoding](../../aspose.threed.formats/ioconfig/encoding/) { get; set; } | テキストベースのファイルのデフォルトエンコーディングを取得または設定します。デフォルト値は null で、インポーター/エクスポーターが使用するエンコーディングを決定します。 |
| [ExportTextures](../../aspose.threed.formats/saveoptions/exporttextures/) { get; set; } | シーンで使用されているテクスチャを出力ディレクトリにコピーしようとします。 |
| [FileFormat](../../aspose.threed.formats/ioconfig/fileformat/) { get; } | 現在の保存/読み込みオプションで指定されたファイル形式を取得します。 |
| [FileName](../../aspose.threed.formats/ioconfig/filename/) { get; set; } | エクスポート/インポートシーンのファイル名です。これはオプションですが、OBJ のマテリアルなどの外部アセットをシリアライズする際に便利です。 |
| [FileSystem](../../aspose.threed.formats/ioconfig/filesystem/) { get; set; } | ロード/セーブ時に外部依存関係を管理する方法をユーザーが扱えるようにします。 |
| [LookupPaths](../../aspose.threed.formats/ioconfig/lookuppaths/) { get; set; } | OBJ のような一部のファイルは外部ファイルに依存しており、検索パスにより Aspose.3D が外部ファイルをロードできるようになります。 |

### 関連項目

* class [SaveOptions](../saveoptions/)
* namespace [Aspose.ThreeD.Formats](../../aspose.threed.formats/)
* assembly [Aspose.3D](../../)



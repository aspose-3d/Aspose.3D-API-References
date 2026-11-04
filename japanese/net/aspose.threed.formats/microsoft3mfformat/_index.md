---
title: "Microsoft3MFFormat クラス"
second_title: "Aspose.3D for .NET API リファレンス"
description: "Aspose.ThreeD.Formats.Microsoft3MFFormat クラス。3MF 関連ユーティリティを備えた Microsoft 3MF のファイル形式インスタンスです。"
type: docs
weight: 1340
url: /ja/net/aspose.threed.formats/microsoft3mfformat/
---
## Microsoft3MFFormat class

3MF 関連ユーティリティを備えた Microsoft 3MF のファイル形式インスタンスです。

```csharp
public class Microsoft3MFFormat : FileFormat
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [CanExport](../../aspose.threed/fileformat/canexport/) { get; } | Aspose.3D が現在のファイル形式へのシーンエクスポートをサポートしているかどうかを取得します。 |
| [CanImport](../../aspose.threed/fileformat/canimport/) { get; } | Aspose.3D が現在のファイル形式からのシーンインポートをサポートしているかどうかを取得します。 |
| [ContentType](../../aspose.threed/fileformat/contenttype/) { get; } | ファイル形式のコンテンツタイプを取得します |
| [Extension](../../aspose.threed/fileformat/extension/) { get; } | このタイプの拡張子名を取得します。 |
| [Extensions](../../aspose.threed/fileformat/extensions/) { get; } | このタイプの拡張子名一覧を取得します。 |
| [FileFormatType](../../aspose.threed/fileformat/fileformattype/) { get; } | ファイル形式のタイプを取得します |
| [Version](../../aspose.threed/fileformat/version/) { get; } | ファイル形式のバージョンを取得します |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [CreateLoadOptions](../../aspose.threed/fileformat/createloadoptions/)() | このファイル形式のデフォルトロードオプションを作成します |
| [CreateSaveOptions](../../aspose.threed/fileformat/createsaveoptions/)() | このファイル形式のデフォルト保存オプションを作成します |
| [GetObjectType](../../aspose.threed.formats/microsoft3mfformat/getobjecttype/)(Node) | 指定されたノードのモデルタイプを取得します。 |
| [GetTransformForBuild](../../aspose.threed.formats/microsoft3mfformat/gettransformforbuild/)(Node) | ビルドで使用されるノードの変換行列を取得します。 |
| [IsBuildable](../../aspose.threed.formats/microsoft3mfformat/isbuildable/)(Node) | このノードがビルドとしてマークされているか確認します。 |
| [SetBuildable](../../aspose.threed.formats/microsoft3mfformat/setbuildable/)(Node, bool, Matrix4?) |  |
| [SetObjectType](../../aspose.threed.formats/microsoft3mfformat/setobjecttype/)(Node, string) | 指定されたノードのモデルタイプを設定します。可能な値: model surface solidsupport support other |
| override [ToString](../../aspose.threed/fileformat/tostring/)() | フォーマットを文字列に変換します |

### 関連項目

* class [FileFormat](../../aspose.threed/fileformat/)
* namespace [Aspose.ThreeD.Formats](../../aspose.threed.formats/)
* assembly [Aspose.3D](../../)



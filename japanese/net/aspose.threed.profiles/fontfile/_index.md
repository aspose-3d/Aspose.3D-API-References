---
title: "クラス FontFile"
second_title: "Aspose.3D for .NET API リファレンス"
description: "Aspose.ThreeD.Profiles.FontFile クラス。 フォントファイルはグリフの定義を含み、テキストプロファイルの作成に使用されます"
type: docs
weight: 1720
url: /ja/net/aspose.threed.profiles/fontfile/
---
## FontFile class

フォントファイルはグリフの定義を含み、テキストプロファイルの作成に使用されます。

```csharp
public abstract class FontFile : A3DObject
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | 名前を取得または設定します。 |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | すべてのプロパティのコレクションを取得します。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| static [FromFile](../../aspose.threed.profiles/fontfile/fromfile/)(string) | ファイル名から FontFile をロードする |
| static [Parse](../../aspose.threed.profiles/fontfile/parse/)(byte[]) | バイトから FontFile を解析する |
| [FindProperty](../../aspose.threed/a3dobject/findproperty/)(string) | プロパティを検索します。動的プロパティ（CreateDynamicProperty/SetProperty によって作成）またはネイティブプロパティ（名前で識別）になる可能性があります。 |
| [GetProperty](../../aspose.threed/a3dobject/getproperty/)(string) | 指定されたプロパティの値を取得します。 |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(Property) | 動的プロパティを削除します。 |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(string) | 名前で識別される指定されたプロパティを削除します。 |
| [SetProperty](../../aspose.threed/a3dobject/setproperty/)(string, object) | 指定されたプロパティの値を設定します |

## 例

以下のコードは、指定されたフォントファイルを使用してテキストから 3D メッシュを作成する方法を示しています。

```csharp
var font = FontFile.FromFile(@"CascadiaCode-Regular.otf");
var text = new Text();
text.Font = font;
text.Content = "ABC";
text.FontSize = 10;
var linear = new LinearExtrusion(text, 10).ToMesh();
var scene = new Scene(linear);
scene.Save(@"test.stl");
```

### 関連項目

* class [A3DObject](../../aspose.threed/a3dobject/)
* namespace [Aspose.ThreeD.Profiles](../../aspose.threed.profiles/)
* assembly [Aspose.3D](../../)



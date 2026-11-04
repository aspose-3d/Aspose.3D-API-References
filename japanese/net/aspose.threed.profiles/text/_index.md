---
title: "クラス Text"
second_title: "Aspose.3D for .NET API リファレンス"
description: "Aspose.ThreeD.Profiles.Text クラス。 Text プロファイルは、フォントとテキストを使用して輪郭を記述します"
type: docs
weight: 1820
url: /ja/net/aspose.threed.profiles/text/
---
## Text class

Text プロファイルは、フォントとテキストを使用して輪郭を記述します。

```csharp
public class Text : Profile
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [Text](text/)() | デフォルトコンストラクタです。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [Content](../../aspose.threed.profiles/text/content/) { get; set; } | テキストの内容 |
| [Excluded](../../aspose.threed/entity/excluded/) { get; set; } | エクスポート時にこのエンティティを除外するかどうかを取得または設定します。 |
| [Font](../../aspose.threed.profiles/text/font/) { get; set; } | テキストのフォントです。 |
| [FontSize](../../aspose.threed.profiles/text/fontsize/) { get; set; } | フォントサイズのスケール。 |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | 名前を取得または設定します。 |
| [ParentNode](../../aspose.threed/entity/parentnode/) { get; set; } | 最初の親ノードを取得または設定します。最初の親ノードを設定すると、このエンティティは他の親ノードから切り離されます。 |
| [ParentNodes](../../aspose.threed/entity/parentnodes/) { get; } | すべての親ノードを取得します。エンティティはジオメトリインスタンシングのために複数の親ノードにアタッチできます。 |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | すべてのプロパティのコレクションを取得します。 |
| [Scene](../../aspose.threed/sceneobject/scene/) { get; } | このオブジェクトが属するシーンを取得します。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [FindProperty](../../aspose.threed/a3dobject/findproperty/)(string) | プロパティを検索します。動的プロパティ（CreateDynamicProperty/SetProperty によって作成）またはネイティブプロパティ（名前で識別）になる可能性があります。 |
| [GetBoundingBox](../../aspose.threed/entity/getboundingbox/)() | 現在のエンティティのオブジェクト空間座標系におけるバウンディングボックスを取得します。 |
| override [GetEntityRendererKey](../../aspose.threed.profiles/profile/getentityrendererkey/)() | レンダラーに登録されたエンティティレンダラーのキーを取得します。 |
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

* class [Profile](../profile/)
* namespace [Aspose.ThreeD.Profiles](../../aspose.threed.profiles/)
* assembly [Aspose.3D](../../)



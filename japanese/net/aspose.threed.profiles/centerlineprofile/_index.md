---
title: "CenterLineProfile クラス"
second_title: "Aspose.3D for .NET API リファレンス"
description: "Aspose.ThreeD.Profiles.CenterLineProfile クラス。IFC 互換のセンターラインプロファイルです。"
type: docs
weight: 1690
url: /ja/net/aspose.threed.profiles/centerlineprofile/
---
## CenterLineProfile class

IFC 互換のセンターラインプロファイル

```csharp
public class CenterLineProfile : Profile
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [CenterLineProfile](centerlineprofile/)(Curve, double) | 指定された曲線をセンターラインとして使用し、新しい `CenterLineProfile` を構築します。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [Curve](../../aspose.threed.profiles/centerlineprofile/curve/) { get; set; } | プロファイルの中心線曲線 |
| [Excluded](../../aspose.threed/entity/excluded/) { get; set; } | エクスポート時にこのエンティティを除外するかどうかを取得または設定します。 |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | 名前を取得または設定します。 |
| [ParentNode](../../aspose.threed/entity/parentnode/) { get; set; } | 最初の親ノードを取得または設定します。最初の親ノードを設定すると、このエンティティは他の親ノードから切り離されます。 |
| [ParentNodes](../../aspose.threed/entity/parentnodes/) { get; } | すべての親ノードを取得します。エンティティはジオメトリインスタンシングのために複数の親ノードにアタッチできます。 |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | すべてのプロパティのコレクションを取得します。 |
| [Scene](../../aspose.threed/sceneobject/scene/) { get; } | このオブジェクトが属するシーンを取得します。 |
| [Thickness](../../aspose.threed.profiles/centerlineprofile/thickness/) { get; set; } | 中心線に沿って適用される厚さ |

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

### 関連項目

* class [Profile](../profile/)
* namespace [Aspose.ThreeD.Profiles](../../aspose.threed.profiles/)
* assembly [Aspose.3D](../../)



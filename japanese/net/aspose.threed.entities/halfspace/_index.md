---
title: "HalfSpace クラス"
second_title: "Aspose.3D for .NET API リファレンス"
description: "Aspose.ThreeD.Entities.HalfSpace クラス。HalfSpace は平面で分割される無限空間を表し、BooleanOperator と併用できます。"
type: docs
weight: 420
url: /ja/net/aspose.threed.entities/halfspace/
---
## HalfSpace class

`HalfSpace` は平面で分割される無限空間を表し、[`BooleanOperator`](../booleanoperator/) と併用できます。

```csharp
public class HalfSpace : Entity
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [HalfSpace](halfspace/#constructor)() | `HalfSpace` の新しいインスタンスを構築します。 |
| [HalfSpace](halfspace/#constructor_1)(Vector3, Vector3) | 指定された法線ベクトルとカッター平面上の位置を使用して、`HalfSpace` の新しいインスタンスを構築します； |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [Excluded](../../aspose.threed/entity/excluded/) { get; set; } | エクスポート時にこのエンティティを除外するかどうかを取得または設定します。 |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | 名前を取得または設定します。 |
| [Normal](../../aspose.threed.entities/halfspace/normal/) { get; set; } | 分割平面の法線です。平面は N * P + D = 0 と定義され、N は法線、P は平面上の任意の点です。 |
| [ParentNode](../../aspose.threed/entity/parentnode/) { get; set; } | 最初の親ノードを取得または設定します。最初の親ノードを設定すると、このエンティティは他の親ノードから切り離されます。 |
| [ParentNodes](../../aspose.threed/entity/parentnodes/) { get; } | すべての親ノードを取得します。エンティティはジオメトリインスタンシングのために複数の親ノードにアタッチできます。 |
| [Position](../../aspose.threed.entities/halfspace/position/) { get; set; } | 分割平面上の任意の点です。平面は N * P + D = 0 と定義され、N は法線、P は平面上の任意の点です。 |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | すべてのプロパティのコレクションを取得します。 |
| [Scene](../../aspose.threed/sceneobject/scene/) { get; } | このオブジェクトが属するシーンを取得します。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [FindProperty](../../aspose.threed/a3dobject/findproperty/)(string) | プロパティを検索します。動的プロパティ（CreateDynamicProperty/SetProperty によって作成）またはネイティブプロパティ（名前で識別）になる可能性があります。 |
| [GetBoundingBox](../../aspose.threed/entity/getboundingbox/)() | 現在のエンティティのオブジェクト空間座標系におけるバウンディングボックスを取得します。 |
| virtual [GetEntityRendererKey](../../aspose.threed/entity/getentityrendererkey/)() | レンダラーに登録されたエンティティレンダラーのキーを取得します。 |
| [GetProperty](../../aspose.threed/a3dobject/getproperty/)(string) | 指定されたプロパティの値を取得します。 |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(Property) | 動的プロパティを削除します。 |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(string) | 名前で識別される指定されたプロパティを削除します。 |
| [SetProperty](../../aspose.threed/a3dobject/setproperty/)(string, object) | 指定されたプロパティの値を設定します |

### 関連項目

* class [Entity](../../aspose.threed/entity/)
* namespace [Aspose.ThreeD.Entities](../../aspose.threed.entities/)
* assembly [Aspose.3D](../../)



---
title: "クラス BooleanOperator"
second_title: "Aspose.3D for .NET API リファレンス"
description: "Aspose.ThreeD.Entities.BooleanOperator クラス。ブール演算子は、2つの IMeshConvertible インスタンスに対してブール演算を適用できます"
type: docs
weight: 280
url: /ja/net/aspose.threed.entities/booleanoperator/
---
## BooleanOperator class

ブール演算子は、2つの [`IMeshConvertible`](../imeshconvertible/) インスタンスにブール演算を適用できます。

```csharp
public class BooleanOperator : Entity, IMeshConvertible
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [BooleanOperator](booleanoperator/#constructor)() | `BooleanOperator` のコンストラクタ |
| [BooleanOperator](booleanoperator/#constructor_1)(BooleanOperation, A3DObject, A3DObject) | 2つのオペランドで `BooleanOperator` の新しいインスタンスを構築します |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [Excluded](../../aspose.threed/entity/excluded/) { get; set; } | エクスポート時にこのエンティティを除外するかどうかを取得または設定します。 |
| [First](../../aspose.threed.entities/booleanoperator/first/) { get; set; } | ブール演算子の最初のオペランド |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | 名前を取得または設定します。 |
| [Operator](../../aspose.threed.entities/booleanoperator/operator/) { get; set; } | 結果メッシュを作成する操作で使用されるブール演算子。 |
| [ParentNode](../../aspose.threed/entity/parentnode/) { get; set; } | 最初の親ノードを取得または設定します。最初の親ノードを設定すると、このエンティティは他の親ノードから切り離されます。 |
| [ParentNodes](../../aspose.threed/entity/parentnodes/) { get; } | すべての親ノードを取得します。エンティティはジオメトリインスタンシングのために複数の親ノードにアタッチできます。 |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | すべてのプロパティのコレクションを取得します。 |
| [Scene](../../aspose.threed/sceneobject/scene/) { get; } | このオブジェクトが属するシーンを取得します。 |
| [Second](../../aspose.threed.entities/booleanoperator/second/) { get; set; } | ブール演算子の2番目のオペランド |

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
| [ToMesh](../../aspose.threed.entities/booleanoperator/tomesh/)() | 2つのオペランドに対してブール演算を実行します |

### 関連項目

* class [Entity](../../aspose.threed/entity/)
* interface [IMeshConvertible](../imeshconvertible/)
* namespace [Aspose.ThreeD.Entities](../../aspose.threed.entities/)
* assembly [Aspose.3D](../../)



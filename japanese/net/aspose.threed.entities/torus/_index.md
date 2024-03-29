---
title: Torus
second_title: Aspose.3D for.NETAPIリファレンス
description: パラメータ化されたトーラス.
type: docs
weight: 710
url: /ja/net/aspose.threed.entities/torus/
---
## Torus class

パラメータ化されたトーラス.

```csharp
public class Torus : Primitive
```

## コンストラクター

| 名前 | 説明 |
| --- | --- |
| [Torus](torus/#constructor)() | の新しいインスタンスを初期化します`Torus`class. |
| [Torus](torus/#constructor_1)(double, double) | の新しいインスタンスを初期化します`Torus`class. |
| [Torus](torus/#constructor_2)(double, double, double) | の新しいインスタンスを初期化します`Torus`class. |
| [Torus](torus/#constructor_3)(string, double, double, int, int, double) | の新しいインスタンスを初期化します`Torus`class. |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [Arc](../../aspose.threed.entities/torus/arc/) { get; set; } | 円弧を取得または設定します。 |
| [CastShadows](../../aspose.threed.entities/primitive/castshadows/) { get; set; } | このジオメトリがシャドウをキャストできるかどうかを取得または設定します |
| [Excluded](../../aspose.threed/entity/excluded/) { get; set; } | エクスポート中にこのエンティティを除外するかどうかを取得または設定します。 |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | 名前を取得または設定します。 |
| [ParentNode](../../aspose.threed/entity/parentnode/) { get; set; } | 最初の親ノードを取得または設定します。最初の親ノードを設定すると、このエンティティは他の親ノードから切り離されます。 |
| [ParentNodes](../../aspose.threed/entity/parentnodes/) { get; } | すべての親ノードを取得します。ジオメトリのインスタンス化のためにエンティティを複数の親ノードにアタッチできます |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | すべてのプロパティのコレクションを取得します。 |
| [RadialSegments](../../aspose.threed.entities/torus/radialsegments/) { get; set; } | ラジアル セグメントを取得または設定します。 |
| [Radius](../../aspose.threed.entities/torus/radius/) { get; set; } | トーラスの半径を取得または設定します。 |
| [ReceiveShadows](../../aspose.threed.entities/primitive/receiveshadows/) { get; set; } | このジオメトリが影を受け取ることができるかどうかを取得または設定します. |
| [Scene](../../aspose.threed/sceneobject/scene/) { get; } | このオブジェクトが属するシーンを取得します |
| [Tube](../../aspose.threed.entities/torus/tube/) { get; set; } | チューブの半径を取得または設定します。 |
| [TubularSegments](../../aspose.threed.entities/torus/tubularsegments/) { get; set; } | 管状セグメントを取得または設定します。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [FindProperty](../../aspose.threed/a3dobject/findproperty/)(string) | プロパティを検索します。 動的プロパティ (CreateDynamicProperty/SetProperty で作成) またはネイティブ プロパティ (名前で識別) を指定できます。 |
| [GetBoundingBox](../../aspose.threed/entity/getboundingbox/)() | オブジェクト空間座標系で現在のエンティティの境界ボックスを取得します. |
| virtual [GetEntityRendererKey](../../aspose.threed/entity/getentityrendererkey/)() | レンダラーに登録されているエンティティ レンダラーのキーを取得します |
| [GetProperty](../../aspose.threed/a3dobject/getproperty/)(string) | 指定したプロパティの値を取得 |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(Property) | 動的プロパティを削除します。 |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(string) | name で識別される指定されたプロパティを削除します |
| [SetProperty](../../aspose.threed/a3dobject/setproperty/)(string, object) | 指定されたプロパティの値を設定します |
| override [ToMesh](../../aspose.threed.entities/torus/tomesh/)() | 現在のオブジェクトを mesh に変換します |

### 関連項目

* class [Primitive](../primitive/)
* 名前空間 [Aspose.ThreeD.Entities](../../aspose.threed.entities/)
* 組み立て [Aspose.3D](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.3D.dll -->

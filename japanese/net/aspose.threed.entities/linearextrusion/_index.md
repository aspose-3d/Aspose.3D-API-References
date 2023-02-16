---
title: LinearExtrusion
second_title: Aspose.3D for.NETAPIリファレンス
description: 線形押し出しは入力として 2D 形状を取りその形状を 3 次元に拡張します
type: docs
weight: 430
url: /ja/net/aspose.threed.entities/linearextrusion/
---
## LinearExtrusion class

線形押し出しは、入力として 2D 形状を取り、その形状を 3 次元に拡張します。

```csharp
public class LinearExtrusion : Entity, IMeshConvertible
```

## コンストラクター

| 名前 | 説明 |
| --- | --- |
| [LinearExtrusion](linearextrusion/#constructor)() | インスタンスのコンストラクター`LinearExtrusion`. |
| [LinearExtrusion](linearextrusion/#constructor_1)(Profile, double) | インスタンスのコンストラクター`LinearExtrusion`. |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [Center](../../aspose.threed.entities/linearextrusion/center/) { get; set; } | この値が false の場合、線形押し出しの Z 範囲は 0 から高さです。それ以外の場合、範囲は -height/2 から高さ/2 です。 |
| [Direction](../../aspose.threed.entities/linearextrusion/direction/) { get; set; } | 押し出しの方向、デフォルト値は (0, 0, 1) |
| [Excluded](../../aspose.threed/entity/excluded/) { get; set; } | エクスポート中にこのエンティティを除外するかどうかを取得または設定します。 |
| [Height](../../aspose.threed.entities/linearextrusion/height/) { get; set; } | 押し出されたジオメトリの高さ、デフォルト値は 1.0 です |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | 名前を取得または設定します。 |
| [ParentNode](../../aspose.threed/entity/parentnode/) { get; set; } | 最初の親ノードを取得または設定します。最初の親ノードを設定すると、このエンティティは他の親ノードから切り離されます。 |
| [ParentNodes](../../aspose.threed/entity/parentnodes/) { get; } | すべての親ノードを取得します。ジオメトリのインスタンス化のためにエンティティを複数の親ノードにアタッチできます |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | すべてのプロパティのコレクションを取得します。 |
| [Scene](../../aspose.threed/sceneobject/scene/) { get; } | このオブジェクトが属するシーンを取得します |
| [Shape](../../aspose.threed.entities/linearextrusion/shape/) { get; set; } | 押し出す基本形状。 |
| [Slices](../../aspose.threed.entities/linearextrusion/slices/) { get; set; } | ねじれた押し出しジオメトリのスライス。デフォルト値は 1. です。 |
| [Twist](../../aspose.threed.entities/linearextrusion/twist/) { get; set; } | シェイプが押し出される度数。 |
| [TwistOffset](../../aspose.threed.entities/linearextrusion/twistoffset/) { get; set; } | ツイストで使用されるオフセット。デフォルト値は (0, 0, 0). |

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
| [ToMesh](../../aspose.threed.entities/linearextrusion/tomesh/)() | 押し出しをメッシュに変換します。 |

### 関連項目

* class [Entity](../../aspose.threed/entity/)
* interface [IMeshConvertible](../imeshconvertible/)
* 名前空間 [Aspose.ThreeD.Entities](../../aspose.threed.entities/)
* 組み立て [Aspose.3D](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.3D.dll -->
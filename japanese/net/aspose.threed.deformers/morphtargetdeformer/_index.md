---
title: MorphTargetDeformer
second_title: Aspose.3D for.NETAPIリファレンス
description: MorphTargetDeformer は頂点ごとのアニメーションを提供します MorphTargetDeformer はMorphTargetChannel./morphtargetchannel/ 各チャネルは複数のターゲットを編成できます モーフ ターゲット デフォーマの一般的な用途はキャラクターに顔の表情を適用することです. 詳細についてはhttps//en.wikipedia.org/wiki/Morph_target_animation を参照してください
type: docs
weight: 210
url: /ja/net/aspose.threed.deformers/morphtargetdeformer/
---
## MorphTargetDeformer class

MorphTargetDeformer は、頂点ごとのアニメーションを提供します。 MorphTargetDeformer は、[`MorphTargetChannel`](../morphtargetchannel/) 、各チャネルは複数のターゲットを編成できます。 モーフ ターゲット デフォーマの一般的な用途は、キャラクターに顔の表情を適用することです. 詳細については、https://en.wikipedia.org/wiki/Morph_target_animation を参照してください。

```csharp
public class MorphTargetDeformer : Deformer
```

## コンストラクター

| 名前 | 説明 |
| --- | --- |
| [MorphTargetDeformer](morphtargetdeformer/#constructor)() | の新しいインスタンスを初期化します`MorphTargetDeformer`class. |
| [MorphTargetDeformer](morphtargetdeformer/#constructor_1)(string) | の新しいインスタンスを初期化します`MorphTargetDeformer`class. |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [Channels](../../aspose.threed.deformers/morphtargetdeformer/channels/) { get; } | このデフォーマに含まれるすべてのチャネルを取得します |
| [Item](../../aspose.threed.deformers/morphtargetdeformer/item/) { get; set; } |  |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | 名前を取得または設定します。 |
| [Owner](../../aspose.threed.deformers/deformer/owner/) { get; } | このデフォーマを所有するジオメトリを取得します |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | すべてのプロパティのコレクションを取得します。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [FindProperty](../../aspose.threed/a3dobject/findproperty/)(string) | プロパティを検索します。 動的プロパティ (CreateDynamicProperty/SetProperty で作成) またはネイティブ プロパティ (名前で識別) を指定できます。 |
| [GetProperty](../../aspose.threed/a3dobject/getproperty/)(string) | 指定したプロパティの値を取得 |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(Property) | 動的プロパティを削除します。 |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(string) | name で識別される指定されたプロパティを削除します |
| [SetProperty](../../aspose.threed/a3dobject/setproperty/)(string, object) | 指定されたプロパティの値を設定します |

### 関連項目

* class [Deformer](../deformer/)
* 名前空間 [Aspose.ThreeD.Deformers](../../aspose.threed.deformers/)
* 組み立て [Aspose.3D](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.3D.dll -->

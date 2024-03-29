---
title: AnimationNode
second_title: Aspose.3D for.NETAPIリファレンス
description: Aspose.3D はアニメーション階層をサポートしており各アニメーションは複数のアニメーションとアニメーションのキー フレーム定義で構成できます AnimationNode./animationnode/時間の経過に伴うプロパティ値の変換を定義しますたとえばアニメーション ノードを使用してノードの変換などを制御できますA3DObject../aspose.threed/a3dobject/オブジェクトの数値プロパティ.
type: docs
weight: 40
url: /ja/net/aspose.threed.animation/animationnode/
---
## AnimationNode class

Aspose.3D はアニメーション階層をサポートしており、各アニメーションは複数のアニメーションとアニメーションのキー フレーム定義で構成できます。 `AnimationNode`時間の経過に伴うプロパティ値の変換を定義します。たとえば、アニメーション ノードを使用して、ノードの変換などを制御できます。[`A3DObject`](../../aspose.threed/a3dobject/)オブジェクトの数値プロパティ.

```csharp
public class AnimationNode : A3DObject
```

## コンストラクター

| 名前 | 説明 |
| --- | --- |
| [AnimationNode](animationnode/#constructor)() | の新しいインスタンスを初期化します`AnimationNode`class. |
| [AnimationNode](animationnode/#constructor_1)(string) | の新しいインスタンスを初期化します`AnimationNode`class. |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [BindPoints](../../aspose.threed.animation/animationnode/bindpoints/) { get; } | 現在のプロパティ バインド ポイントを取得します |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | 名前を取得または設定します。 |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | すべてのプロパティのコレクションを取得します。 |
| [SubAnimations](../../aspose.threed.animation/animationnode/subanimations/) { get; } | 現在のアニメーションの下にあるサブアニメーション ノードを取得します |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [CreateBindPoint](../../aspose.threed.animation/animationnode/createbindpoint/)(A3DObject, string) | プロパティのデータ型に基づいて BindPoint を作成します。 |
| [FindBindPoint](../../aspose.threed.animation/animationnode/findbindpoint/)(string) | 名前でバインド ポイントを検索します。 |
| [FindProperty](../../aspose.threed/a3dobject/findproperty/)(string) | プロパティを検索します。 動的プロパティ (CreateDynamicProperty/SetProperty で作成) またはネイティブ プロパティ (名前で識別) を指定できます。 |
| [GetBindPoint](../../aspose.threed.animation/animationnode/getbindpoint/)(A3DObject, string, bool) | 指定されたプロパティのアニメーション バインド ポイントを取得します。 |
| [GetKeyframeSequence](../../aspose.threed.animation/animationnode/getkeyframesequence/#getkeyframesequence)(A3DObject, string, bool) | 指定されたプロパティのキーフレーム シーケンスを取得します。 |
| [GetKeyframeSequence](../../aspose.threed.animation/animationnode/getkeyframesequence/#getkeyframesequence_1)(A3DObject, string, string, bool) | 指定されたプロパティとチャネルのキーフレーム シーケンスを取得します。 |
| [GetProperty](../../aspose.threed/a3dobject/getproperty/)(string) | 指定したプロパティの値を取得 |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(Property) | 動的プロパティを削除します。 |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(string) | name で識別される指定されたプロパティを削除します |
| [SetProperty](../../aspose.threed/a3dobject/setproperty/)(string, object) | 指定されたプロパティの値を設定します |

### 関連項目

* class [A3DObject](../../aspose.threed/a3dobject/)
* 名前空間 [Aspose.ThreeD.Animation](../../aspose.threed.animation/)
* 組み立て [Aspose.3D](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.3D.dll -->

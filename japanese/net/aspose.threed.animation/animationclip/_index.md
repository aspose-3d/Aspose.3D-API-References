---
title: AnimationClip
second_title: Aspose.3D for.NETAPIリファレンス
description: アニメーション クリップはアニメーションのコレクションです シーンには1 つまたは複数のアニメーション クリップを含めることができます
type: docs
weight: 30
url: /ja/net/aspose.threed.animation/animationclip/
---
## AnimationClip class

アニメーション クリップは、アニメーションのコレクションです。 シーンには、1 つまたは複数のアニメーション クリップを含めることができます。

```csharp
public class AnimationClip : SceneObject
```

## コンストラクター

| 名前 | 説明 |
| --- | --- |
| [AnimationClip](animationclip/#constructor)() | の新しいインスタンスを初期化します`AnimationClip`class. |
| [AnimationClip](animationclip/#constructor_1)(string) | の新しいインスタンスを初期化します`AnimationClip`class. |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [Animations](../../aspose.threed.animation/animationclip/animations/) { get; } | クリップ内に含まれるアニメーションを取得します。 |
| [Description](../../aspose.threed.animation/animationclip/description/) { get; set; } | このアニメーション クリップの説明を取得または設定します |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | 名前を取得または設定します。 |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | すべてのプロパティのコレクションを取得します。 |
| [Scene](../../aspose.threed/sceneobject/scene/) { get; } | このオブジェクトが属するシーンを取得します |
| [Start](../../aspose.threed.animation/animationclip/start/) { get; set; } | クリップの開始時間を秒単位で取得または設定します。 |
| [Stop](../../aspose.threed.animation/animationclip/stop/) { get; set; } | クリップの終了時間を秒単位で取得または設定します。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [CreateAnimationNode](../../aspose.threed.animation/animationclip/createanimationnode/)(string) | 現在のクリップにアニメーション ノードを作成して登録する簡略関数。 |
| [FindProperty](../../aspose.threed/a3dobject/findproperty/)(string) | プロパティを検索します。 動的プロパティ (CreateDynamicProperty/SetProperty で作成) またはネイティブ プロパティ (名前で識別) を指定できます。 |
| [GetProperty](../../aspose.threed/a3dobject/getproperty/)(string) | 指定したプロパティの値を取得 |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(Property) | 動的プロパティを削除します。 |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(string) | name で識別される指定されたプロパティを削除します |
| [SetProperty](../../aspose.threed/a3dobject/setproperty/)(string, object) | 指定されたプロパティの値を設定します |

### 関連項目

* class [SceneObject](../../aspose.threed/sceneobject/)
* 名前空間 [Aspose.ThreeD.Animation](../../aspose.threed.animation/)
* 組み立て [Aspose.3D](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.3D.dll -->
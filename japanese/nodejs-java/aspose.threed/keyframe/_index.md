---
title: "KeyFrame"
second_title: "Node.js 用 Java 経由の Aspose.3D API リファレンス"
description: 
type: docs

url: /ja/nodejs-java/aspose.threed/keyframe/
---
## KeyFrame class

キーフレームは主に時間と値で定義され、いくつかの補間タイプでは接線/テンション/バイアス/連続性が最終的なサンプル値の計算に使用されます。キーフレーム以外の時間位置のサンプル値は、前後のキーフレーム間で補間されます。最初または最後のキーフレームの前後の値は Extrapolation クラスによって計算されます。


## メソッド

### constructor{#constructor}

| 名前 | 説明 |
| --- | --- |
| constructor(curve, time) | 指定された曲線上に新しいキーフレームを作成する |

 **Parameters:**

| 名前 | 型 | 説明 |
| --- | --- | --- |
| curve | KeyframeSequence | キー フレームが作成される曲線 |
| 時間 | 数 | キー フレームの時間位置 |

 **Result:**



---


### getTime{#getTime}

| 名前 | 説明 |
| --- | --- |
| getTime() | list.data[index] キー フレームの時間位置を取得または設定します（秒単位で測定）。時間。 |

 **Result:**



---


### setTime{#setTime}

| 名前 | 説明 |
| --- | --- |
| setTime(value) | list.data[index] キー フレームの時間位置を取得または設定します（秒単位で測定）。時間。 |

 **Result:**



---


### getValue{#getValue}

| 名前 | 説明 |
| --- | --- |
| getValue() | キー フレームの値を取得または設定します。値。 |

 **Result:**



---


### setValue{#setValue}

| 名前 | 説明 |
| --- | --- |
| setValue(value) | キー フレームの値を取得または設定します。値。 |

 **Result:**



---


### getInterpolation{#getInterpolation}

| 名前 | 説明 |
| --- | --- |
| getInterpolation() | キーの補間タイプを取得または設定します。list.data[index] はサンプリングされた値の計算方法を定義するアルゴリズムです。プロパティの値は Interpolation 整数定数です。補間。 |

 **Result:**



---


### setInterpolation{#setInterpolation}

| 名前 | 説明 |
| --- | --- |
| setInterpolation(value) | キーの補間タイプを取得または設定します。list.data[index] はサンプリングされた値の計算方法を定義するアルゴリズムです。プロパティの値は Interpolation 整数定数です。補間。 |

 **Result:**



---


### getTangentWeightMode{#getTangentWeightMode}

| 名前 | 説明 |
| --- | --- |
| getTangentWeightMode() | キーのタンジェント重みモードを取得または設定します。外部タンジェントまたは次の内部タンジェントは、適切な WeightedMode を選択することでカスタマイズできます。プロパティの値は WeightedMode 整数定数です。タンジェント重みモード。 |

 **Result:**



---


### setTangentWeightMode{#setTangentWeightMode}

| 名前 | 説明 |
| --- | --- |
| setTangentWeightMode(value) | キーのタンジェント重みモードを取得または設定します。外部タンジェントまたは次の内部タンジェントは、適切な WeightedMode を選択することでカスタマイズできます。プロパティの値は WeightedMode 整数定数です。タンジェント重みモード。 |

 **Result:**



---


### getStepMode{#getStepMode}

| 名前 | 説明 |
| --- | --- |
| getStepMode() | キーのステップモードを取得または設定します。補間タイプが Interpolation.CONSTANT の場合、list.data[index] は補間中に使用されるキー フレームの値を決定します。StepMode.PREVIOUS_VALUE は左側のキー フレームの値が使用されることを意味し、StepMode.NEXT_VALUE は右側の次のキー フレームの値が使用されることを意味します。プロパティの値は StepMode 整数定数です。ステップモード。 |

 **Result:**



---


### setStepMode{#setStepMode}

| 名前 | 説明 |
| --- | --- |
| setStepMode(value) | キーのステップモードを取得または設定します。補間タイプが Interpolation.CONSTANT の場合、list.data[index] は補間中に使用されるキー フレームの値を決定します。StepMode.PREVIOUS_VALUE は左側のキー フレームの値が使用されることを意味し、StepMode.NEXT_VALUE は右側の次のキー フレームの値が使用されることを意味します。プロパティの値は StepMode 整数定数です。ステップモード。 |

 **Result:**



---


### getNextInTangent{#getNextInTangent}

| 名前 | 説明 |
| --- | --- |
| getNextInTangent() | このキー フレームの次の内部（左）タンジェントを取得または設定します。 |

 **Result:**



---


### setNextInTangent{#setNextInTangent}

| 名前 | 説明 |
| --- | --- |
| setNextInTangent(value) | このキー フレームの次の内部（左）タンジェントを取得または設定します。 |

 **Result:**



---


### getOutTangent{#getOutTangent}

| 名前 | 説明 |
| --- | --- |
| getOutTangent() | このキー フレームの外部（右）タンジェントを取得または設定します。 |

 **Result:**



---


### setOutTangent{#setOutTangent}

| 名前 | 説明 |
| --- | --- |
| setOutTangent(value) | このキー フレームの外部（右）タンジェントを取得または設定します。 |

 **Result:**



---


### getOutWeight{#getOutWeight}

| 名前 | 説明 |
| --- | --- |
| getOutWeight() | このキー フレームの外部（右）ウェイトを取得または設定します。 |

 **Result:**



---


### setOutWeight{#setOutWeight}

| 名前 | 説明 |
| --- | --- |
| setOutWeight(value) | このキー フレームの外部（右）ウェイトを取得または設定します。 |

 **Result:**



---


### getNextInWeight{#getNextInWeight}

| 名前 | 説明 |
| --- | --- |
| getNextInWeight() | このキーフレームの次のイン（左）ウェイトを取得または設定します。 |

 **Result:**



---


### setNextInWeight{#setNextInWeight}

| 名前 | 説明 |
| --- | --- |
| setNextInWeight(value) | このキーフレームの次のイン（左）ウェイトを取得または設定します。 |

 **Result:**



---


### getTension{#getTension}

| 名前 | 説明 |
| --- | --- |
| getTension() | TCB splineで使用されるテンションを取得または設定します。 |

 **Result:**



---


### setTension{#setTension}

| 名前 | 説明 |
| --- | --- |
| setTension(value) | TCB splineで使用されるテンションを取得または設定します。 |

 **Result:**



---


### getContinuity{#getContinuity}

| 名前 | 説明 |
| --- | --- |
| getContinuity() | TCB splineで使用される連続性を取得または設定します。 |

 **Result:**



---


### setContinuity{#setContinuity}

| 名前 | 説明 |
| --- | --- |
| setContinuity(value) | TCB splineで使用される連続性を取得または設定します。 |

 **Result:**



---


### getBias{#getBias}

| 名前 | 説明 |
| --- | --- |
| getBias() | TCB splineで使用されるバイアスを取得または設定します。 |

 **Result:**



---


### setBias{#setBias}

| 名前 | 説明 |
| --- | --- |
| setBias(value) | TCB splineで使用されるバイアスを取得または設定します。 |

 **Result:**



---


### getIndependentTangent{#getIndependentTangent}

| 名前 | 説明 |
| --- | --- |
| getIndependentTangent() | 外部および次のインタンジェントが独立しているかを取得または設定します。 |

 **Result:**



---


### setIndependentTangent{#setIndependentTangent}

| 名前 | 説明 |
| --- | --- |
| setIndependentTangent(value) | 外部および次のインタンジェントが独立しているかを取得または設定します。 |

 **Result:**



---


### getFlat{#getFlat}

| 名前 | 説明 |
| --- | --- |
| getFlat() | キーフレームがフラットかどうかを取得または設定します。次または前のキーフレームと同じ値の場合、キーフレームはフラットであるべきです。フラットなキーフレームはフラットなタンジェントと固定された補間を持ちます。 |

 **Result:**



---


### setFlat{#setFlat}

| 名前 | 説明 |
| --- | --- |
| setFlat(value) | キーフレームがフラットかどうかを取得または設定します。次または前のキーフレームと同じ値の場合、キーフレームはフラットであるべきです。フラットなキーフレームはフラットなタンジェントと固定された補間を持ちます。 |

 **Result:**



---


### getTimeIndependentTangent{#getTimeIndependentTangent}

| 名前 | 説明 |
| --- | --- |
| getTimeIndependentTangent() | タンジェントが時間に依存しないかを取得または設定します。 |

 **Result:**



---


### setTimeIndependentTangent{#setTimeIndependentTangent}

| 名前 | 説明 |
| --- | --- |
| setTimeIndependentTangent(value) | タンジェントが時間に依存しないかを取得または設定します。 |

 **Result:**



---


### toString{#toString}

| 名前 | 説明 |
| --- | --- |
| toString() | キーフレームの文字列表現を取得します。 |

 **Result:**
文字列


---




---
title: "KeyFrame"
second_title: "Aspose.3D for Java API リファレンス"
description: "キー フレームは主に時間と値で定義され、いくつかの補間タイプ（tangent/​tension/​bias/​continuity）も最終的なサンプル値の計算に使用されます。"
type: docs
weight: 89
url: /ja/java/com.aspose.threed/keyframe/
---

**Inheritance:**
java.lang.Object
```
public class KeyFrame
```

キー フレームは主に時間と値で定義され、いくつかの補間タイプ（tangent/​tension/​bias/​continuity）も最終的なサンプル値の計算に使用されます。非キー フレームの時間位置におけるサンプル値は、前後のキー フレーム間でキー フレームによって補間されます。最初または最後のキー フレームの前後の値は、[Extrapolation](../../com.aspose.threed/extrapolation) クラスによって計算されます。
## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [KeyFrame(KeyframeSequence curve, double time)](#KeyFrame-com.aspose.threed.KeyframeSequence-double-) | 指定された曲線上に新しいキー フレームを作成します。 |
## メソッド

| メソッド | 説明 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBias()](#getBias--) | TCB スプラインで使用されるバイアスを取得します。 |
| [getClass()](#getClass--) |  |
| [getContinuity()](#getContinuity--) | TCB スプラインで使用される連続性を取得します。 |
| [getFlat()](#getFlat--) | キー フレームがフラットかどうかを取得または設定します。 |
| [getIndependentTangent()](#getIndependentTangent--) | 外側と次の内側の接線が独立しているかどうかを取得します。 |
| [getInterpolation()](#getInterpolation--) | キーの補間タイプを取得します。list.data[index] はサンプル値の計算方法を定義するアルゴリズムです。 |
| [getNextInTangent()](#getNextInTangent--) | このキー フレーム上の次の内側（左）接線を取得します。 |
| [getNextInWeight()](#getNextInWeight--) | このキー フレーム上の次の内側（左）ウェイトを取得します。 |
| [getOutTangent()](#getOutTangent--) | このキー フレーム上の外側（右）接線を取得します。 |
| [getOutWeight()](#getOutWeight--) | このキー フレーム上の外側（右）ウェイトを取得します。 |
| [getStepMode()](#getStepMode--) | キーのステップモードを取得します。 |
| [getTangentWeightMode()](#getTangentWeightMode--) | キーの接線ウェイトモードを取得します。 |
| [getTension()](#getTension--) | TCB スプラインで使用されるテンションを取得します。 |
| [getTime()](#getTime--) | list.data[index] キー フレームの時間位置（秒単位）を取得します。 |
| [getTimeIndependentTangent()](#getTimeIndependentTangent--) | 接線が時間に依存しないか取得します。 |
| [getValue()](#getValue--) | キー フレームの値を取得します。 |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setBias(float value)](#setBias-float-) | TCB スプラインで使用されるバイアスを設定します。 |
| [setContinuity(float value)](#setContinuity-float-) | TCB スプラインで使用される連続性を設定します。 |
| [setFlat(boolean value)](#setFlat-boolean-) | キー フレームがフラットかどうかを取得または設定します。 |
| [setIndependentTangent(boolean value)](#setIndependentTangent-boolean-) | アウトと次のインタンジェントが独立していることを設定します。 |
| [setInterpolation(Interpolation value)](#setInterpolation-com.aspose.threed.Interpolation-) | キーの補間タイプを設定します。list.data[index] はサンプリングされた値の計算方法を定義するアルゴリズムです。 |
| [setNextInTangent(Vector2 value)](#setNextInTangent-com.aspose.threed.Vector2-) | このキーフレームの次のイン（左）タンジェントを設定します。 |
| [setNextInWeight(float value)](#setNextInWeight-float-) | このキーフレームの次のイン（左）ウェイトを設定します。 |
| [setOutTangent(Vector2 value)](#setOutTangent-com.aspose.threed.Vector2-) | このキーフレームのアウト（右）タンジェントを設定します。 |
| [setOutWeight(float value)](#setOutWeight-float-) | このキーフレームのアウト（右）ウェイトを設定します。 |
| [setStepMode(StepMode value)](#setStepMode-com.aspose.threed.StepMode-) | キーのステップモードを設定します。 |
| [setTangentWeightMode(int value)](#setTangentWeightMode-int-) | キーのタンジェントウェイトモードを設定します。 |
| [setTension(float value)](#setTension-float-) | TCB スプラインで使用されるテンションを設定します。 |
| [setTime(double value)](#setTime-double-) | list.data[index] キーフレームの時間位置を秒単位で設定します。 |
| [setTimeIndependentTangent(boolean value)](#setTimeIndependentTangent-boolean-) | タンジェントが時間に依存しないように設定します。 |
| [setValue(float value)](#setValue-float-) | キーフレームの値を設定します。 |
| [toString()](#toString--) | キーフレームの文字列表現を取得します。 |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### KeyFrame(KeyframeSequence curve, double time) {#KeyFrame-com.aspose.threed.KeyframeSequence-double-}
```
public KeyFrame(KeyframeSequence curve, double time)
```


指定された曲線上に新しいキー フレームを作成します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| curve | [KeyframeSequence](../../com.aspose.threed/keyframesequence) | キーフレームが作成される曲線。 |
| 時間 | double | キーフレームの時間位置。 |

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getBias() {#getBias--}
```
public float getBias()
```


TCB スプラインで使用されるバイアスを取得します。

**Returns:**
float - TCB スプラインで使用されるバイアス。
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getContinuity() {#getContinuity--}
```
public float getContinuity()
```


TCB スプラインで使用される連続性を取得します。

**Returns:**
float - TCB スプラインで使用される連続性。
### getFlat() {#getFlat--}
```
public boolean getFlat()
```


キーフレームがフラットかどうかを取得または設定します。次または前のキーフレームと同じ値の場合、キーフレームはフラットであるべきです。フラットなキーフレームはフラットなタンジェントと固定された補間を持ちます。

**Returns:**
boolean - キーフレームがフラットかどうかを取得または設定します。次または前のキーフレームと同じ値の場合、キーフレームはフラットであるべきです。フラットなキーフレームはフラットなタンジェントと固定された補間を持ちます。
### getIndependentTangent() {#getIndependentTangent--}
```
public boolean getIndependentTangent()
```


外側と次の内側の接線が独立しているかどうかを取得します。

**Returns:**
boolean - アウトと次のインタンジェントが独立しています。
### getInterpolation() {#getInterpolation--}
```
public Interpolation getInterpolation()
```


キーの補間タイプを取得します。list.data[index] はサンプル値の計算方法を定義するアルゴリズムです。

**Returns:**
[Interpolation](../../com.aspose.threed/interpolation) - the key's interpolation type, list.data[index] defines the algorithm how the sampled value is calculated.
### getNextInTangent() {#getNextInTangent--}
```
public Vector2 getNextInTangent()
```


このキー フレーム上の次の内側（左）接線を取得します。

**Returns:**
[Vector2](../../com.aspose.threed/vector2) - the next in(left) tangent on this key frame.
### getNextInWeight() {#getNextInWeight--}
```
public float getNextInWeight()
```


このキー フレーム上の次の内側（左）ウェイトを取得します。

**Returns:**
float - このキーフレームの次のイン（左）ウェイト。
### getOutTangent() {#getOutTangent--}
```
public Vector2 getOutTangent()
```


このキー フレーム上の外側（右）接線を取得します。

**Returns:**
[Vector2](../../com.aspose.threed/vector2) - the out(right) tangent on this key frame.
### getOutWeight() {#getOutWeight--}
```
public float getOutWeight()
```


このキー フレーム上の外側（右）ウェイトを取得します。

**Returns:**
float - このキーフレームのアウト（右）ウェイト。
### getStepMode() {#getStepMode--}
```
public StepMode getStepMode()
```


キーのステップモードを取得します。補間タイプが [Interpolation.CONSTANT](../../com.aspose.threed/interpolation\#CONSTANT) の場合、list.data[index] は補間中に使用されるキーフレームの値を決定します。[StepMode.PREVIOUS\_VALUE](../../com.aspose.threed/stepmode\#PREVIOUS-VALUE) は左側のキーフレームの値が使用されることを意味し、[StepMode.NEXT\_VALUE](../../com.aspose.threed/stepmode\#NEXT-VALUE) は次の右側のキーフレームの値が使用されることを意味します。

**Returns:**
[StepMode](../../com.aspose.threed/stepmode) - the key's step mode. If the interpolation type is [Interpolation.CONSTANT](../../com.aspose.threed/interpolation\#CONSTANT), list.data[index] decides which key-frame's value will be used during interpolation. A [StepMode.PREVIOUS\_VALUE](../../com.aspose.threed/stepmode\#PREVIOUS-VALUE) means the left key-frame's value will be used A [StepMode.NEXT\_VALUE](../../com.aspose.threed/stepmode\#NEXT-VALUE) means the next right key-frame's value will be used
### getTangentWeightMode() {#getTangentWeightMode--}
```
public int getTangentWeightMode()
```


キーのタンジェントウェイトモードを取得します。アウトタンジェントまたは次のインタンジェントは、適切な [WeightedMode](../../com.aspose.threed/weightedmode) を選択することでカスタマイズできます。

**Returns:**
int - キーのタンジェントウェイトモード。アウトタンジェントまたは次のインタンジェントは、適切な [WeightedMode](../../com.aspose.threed/weightedmode) を選択することでカスタマイズできます。
### getTension() {#getTension--}
```
public float getTension()
```


TCB スプラインで使用されるテンションを取得します。

**Returns:**
float - TCBスプラインで使用されるテンション
### getTime() {#getTime--}
```
public double getTime()
```


list.data[index] キー フレームの時間位置（秒単位）を取得します。

**Returns:**
double - list.data[index] キーフレームの時間位置（秒で測定）
### getTimeIndependentTangent() {#getTimeIndependentTangent--}
```
public boolean getTimeIndependentTangent()
```


接線が時間に依存しないか取得します。

**Returns:**
boolean - 接線は時間に依存しない
### getValue() {#getValue--}
```
public float getValue()
```


キー フレームの値を取得します。

**Returns:**
float - キーフレームの値。
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setBias(float value) {#setBias-float-}
```
public void setBias(float value)
```


TCB スプラインで使用されるバイアスを設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | float | 新しい値 |

### setContinuity(float value) {#setContinuity-float-}
```
public void setContinuity(float value)
```


TCB スプラインで使用される連続性を設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | float | 新しい値 |

### setFlat(boolean value) {#setFlat-boolean-}
```
public void setFlat(boolean value)
```


キーフレームがフラットかどうかを取得または設定します。次または前のキーフレームと同じ値の場合、キーフレームはフラットであるべきです。フラットなキーフレームはフラットなタンジェントと固定された補間を持ちます。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | boolean | 新しい値 |

### setIndependentTangent(boolean value) {#setIndependentTangent-boolean-}
```
public void setIndependentTangent(boolean value)
```


アウトと次のインタンジェントが独立していることを設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | boolean | 新しい値 |

### setInterpolation(Interpolation value) {#setInterpolation-com.aspose.threed.Interpolation-}
```
public void setInterpolation(Interpolation value)
```


キーの補間タイプを設定します。list.data[index] はサンプリングされた値の計算方法を定義するアルゴリズムです。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [Interpolation](../../com.aspose.threed/interpolation) | 新しい値 |

### setNextInTangent(Vector2 value) {#setNextInTangent-com.aspose.threed.Vector2-}
```
public void setNextInTangent(Vector2 value)
```


このキーフレームの次のイン（左）タンジェントを設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [Vector2](../../com.aspose.threed/vector2) | 新しい値 |

### setNextInWeight(float value) {#setNextInWeight-float-}
```
public void setNextInWeight(float value)
```


このキーフレームの次のイン（左）ウェイトを設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | float | 新しい値 |

### setOutTangent(Vector2 value) {#setOutTangent-com.aspose.threed.Vector2-}
```
public void setOutTangent(Vector2 value)
```


このキーフレームのアウト（右）タンジェントを設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [Vector2](../../com.aspose.threed/vector2) | 新しい値 |

### setOutWeight(float value) {#setOutWeight-float-}
```
public void setOutWeight(float value)
```


このキーフレームのアウト（右）ウェイトを設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | float | 新しい値 |

### setStepMode(StepMode value) {#setStepMode-com.aspose.threed.StepMode-}
```
public void setStepMode(StepMode value)
```


キーのステップモードを設定します。補間タイプが [Interpolation.CONSTANT](../../com.aspose.threed/interpolation\\#CONSTANT) の場合、list.data[index] が補間中に使用されるキーフレームの値を決定します。[StepMode.PREVIOUS\\_VALUE](../../com.aspose.threed/stepmode\\#PREVIOUS-VALUE) は左側のキーフレームの値が使用されることを意味し、[StepMode.NEXT\\_VALUE](../../com.aspose.threed/stepmode\\#NEXT-VALUE) は右側の次のキーフレームの値が使用されることを意味します

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [StepMode](../../com.aspose.threed/stepmode) | 新しい値 |

### setTangentWeightMode(int value) {#setTangentWeightMode-int-}
```
public void setTangentWeightMode(int value)
```


キーの接線ウェイトモードを設定します。外部接線または次の内部接線は、正しい [WeightedMode](../../com.aspose.threed/weightedmode) を選択することでカスタマイズできます

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int | 新しい値 |

### setTension(float value) {#setTension-float-}
```
public void setTension(float value)
```


TCB スプラインで使用されるテンションを設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | float | 新しい値 |

### setTime(double value) {#setTime-double-}
```
public void setTime(double value)
```


list.data[index] キーフレームの時間位置を秒単位で設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | double | 新しい値 |

### setTimeIndependentTangent(boolean value) {#setTimeIndependentTangent-boolean-}
```
public void setTimeIndependentTangent(boolean value)
```


タンジェントが時間に依存しないように設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | boolean | 新しい値 |

### setValue(float value) {#setValue-float-}
```
public void setValue(float value)
```


キーフレームの値を設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | float | 新しい値 |

### toString() {#toString--}
```
public String toString()
```


キーフレームの文字列表現を取得します。

**Returns:**
java.lang.String
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final void wait(long arg0)
```




**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |


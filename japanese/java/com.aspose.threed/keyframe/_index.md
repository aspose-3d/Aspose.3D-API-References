---
title: KeyFrame
second_title: Aspose.3D for Java API リファレンス
description: キー フレームは主に時間と値で定義され、いくつかの補間タイプでは、最終的なサンプル値を計算する際に tangent/tension/bias/continuity も使用されます。
type: docs
weight: 89
url: /ja/java/com.aspose.threed/keyframe/
---

**Inheritance:**
java.lang.Object
```
public class KeyFrame
```

キー フレームは主に時間と値で定義され、いくつかの補間タイプでは、最終的なサンプル値を計算する際に tangent/tension/bias/continuity も使用されます。非キー フレームの時間位置におけるサンプル値は、前後のキー フレーム間のキー フレームによって補間されます。最初/最後のキー フレームの前後の値は、[Extrapolation](../../com.aspose.threed/extrapolation) クラスによって計算されます。
## Constructors

| Constructor | 説明 |
| --- | --- |
| [KeyFrame(KeyframeSequence curve, double time)](#KeyFrame-com.aspose.threed.KeyframeSequence-double-) | 指定された曲線上に新しいキー フレームを作成する |
## Methods

| Method | 説明 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBias()](#getBias--) | TCB スプラインで使用されるバイアスを取得する |
| [getClass()](#getClass--) |  |
| [getContinuity()](#getContinuity--) | TCB スプラインで使用される連続性を取得する |
| [getFlat()](#getFlat--) | キー フレームがフラットかどうかを取得または設定する。 |
| [getIndependentTangent()](#getIndependentTangent--) | 外側と次の内側の接線が独立しているかを取得する。 |
| [getInterpolation()](#getInterpolation--) | キーの補間タイプを取得します。list.data[index] はサンプル値の計算方法を定義するアルゴリズムです。 |
| [getNextInTangent()](#getNextInTangent--) | このキー フレーム上の次の内側（左）接線を取得する。 |
| [getNextInWeight()](#getNextInWeight--) | このキー フレーム上の次の内側（左）ウェイトを取得する。 |
| [getOutTangent()](#getOutTangent--) | このキー フレーム上の外側（右）接線を取得する。 |
| [getOutWeight()](#getOutWeight--) | このキー フレーム上の外側（右）ウェイトを取得する。 |
| [getStepMode()](#getStepMode--) | キーのステップモードを取得する。 |
| [getTangentWeightMode()](#getTangentWeightMode--) | キーの接線ウェイトモードを取得する。 |
| [getTension()](#getTension--) | TCB スプラインで使用されるテンションを取得する。 |
| [getTime()](#getTime--) | list.data[index] キー フレームの時間位置を取得します（秒単位）。 |
| [getTimeIndependentTangent()](#getTimeIndependentTangent--) | 接線が時間に依存しないかを取得する。 |
| [getValue()](#getValue--) | キー フレームの値を取得する。 |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setBias(float value)](#setBias-float-) | TCB スプラインで使用されるバイアスを設定する。 |
| [setContinuity(float value)](#setContinuity-float-) | TCB スプラインで使用される連続性を設定する。 |
| [setFlat(boolean value)](#setFlat-boolean-) | キー フレームがフラットかどうかを取得または設定する。 |
| [setIndependentTangent(boolean value)](#setIndependentTangent-boolean-) | アウトと次のイン接線が独立であることを設定します。 |
| [setInterpolation(Interpolation value)](#setInterpolation-com.aspose.threed.Interpolation-) | キーの補間タイプを設定します。list.data[index] はサンプリングされた値の計算方法を定義するアルゴリズムです。 |
| [setNextInTangent(Vector2 value)](#setNextInTangent-com.aspose.threed.Vector2-) | このキー フレームの次のイン（左）接線を設定します。 |
| [setNextInWeight(float value)](#setNextInWeight-float-) | このキー フレームの次のイン（左）ウェイトを設定します。 |
| [setOutTangent(Vector2 value)](#setOutTangent-com.aspose.threed.Vector2-) | このキー フレームのアウト（右）接線を設定します。 |
| [setOutWeight(float value)](#setOutWeight-float-) | このキー フレームのアウト（右）ウェイトを設定します。 |
| [setStepMode(StepMode value)](#setStepMode-com.aspose.threed.StepMode-) | キーのステップモードを設定します。 |
| [setTangentWeightMode(int value)](#setTangentWeightMode-int-) | キーの接線ウェイトモードを設定します。 |
| [setTension(float value)](#setTension-float-) | TCB スプラインで使用されるテンションを設定します。 |
| [setTime(double value)](#setTime-double-) | list.data[index] キーフレームの時間位置を秒単位で設定します。 |
| [setTimeIndependentTangent(boolean value)](#setTimeIndependentTangent-boolean-) | 接線が時間に依存しないように設定します。 |
| [setValue(float value)](#setValue-float-) | キーフレームの値を設定します。 |
| [toString()](#toString--) | キーフレームの文字列表現を取得します。 |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### KeyFrame(KeyframeSequence curve, double time) {#KeyFrame-com.aspose.threed.KeyframeSequence-double-}
```
public KeyFrame(KeyframeSequence curve, double time)
```


指定された曲線上に新しいキー フレームを作成する

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| curve | [KeyframeSequence](../../com.aspose.threed/keyframesequence) | キーフレームが作成される曲線。 |
| 時間 | double | キーフレームの時間位置。 |

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getBias() {#getBias--}
```
public float getBias()
```


TCB スプラインで使用されるバイアスを取得する

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


TCB スプラインで使用される連続性を取得する

**Returns:**
float - TCB スプラインで使用されるコンティニュイティ。
### getFlat() {#getFlat--}
```
public boolean getFlat()
```


キー フレームがフラットかどうかを取得または設定します。次または前のキー フレームと同じ値の場合、キー フレームはフラットであるべきです。フラットなキー フレームはフラットな接線と固定された補間を持ちます。

**Returns:**
boolean - キー フレームがフラットかどうかを取得または設定します。次または前のキー フレームと同じ値の場合、キー フレームはフラットであるべきです。フラットなキー フレームはフラットな接線と固定された補間を持ちます。
### getIndependentTangent() {#getIndependentTangent--}
```
public boolean getIndependentTangent()
```


外側と次の内側の接線が独立しているかを取得する。

**Returns:**
boolean - アウトと次のイン接線が独立です。
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


このキー フレーム上の次の内側（左）接線を取得する。

**Returns:**
[Vector2](../../com.aspose.threed/vector2) - the next in(left) tangent on this key frame.
### getNextInWeight() {#getNextInWeight--}
```
public float getNextInWeight()
```


このキー フレーム上の次の内側（左）ウェイトを取得する。

**Returns:**
float - このキー フレームの次のイン（左）ウェイト。
### getOutTangent() {#getOutTangent--}
```
public Vector2 getOutTangent()
```


このキー フレーム上の外側（右）接線を取得する。

**Returns:**
[Vector2](../../com.aspose.threed/vector2) - the out(right) tangent on this key frame.
### getOutWeight() {#getOutWeight--}
```
public float getOutWeight()
```


このキー フレーム上の外側（右）ウェイトを取得する。

**Returns:**
float - このキー フレームのアウト（右）ウェイト。
### getStepMode() {#getStepMode--}
```
public StepMode getStepMode()
```


キーのステップモードを取得します。補間タイプが [Interpolation.CONSTANT](../../com.aspose.threed/interpolation\#CONSTANT) の場合、list.data[index] は補間中に使用されるキー フレームの値を決定します。[StepMode.PREVIOUS\_VALUE](../../com.aspose.threed/stepmode\#PREVIOUS-VALUE) は左側のキー フレームの値が使用されることを意味し、[StepMode.NEXT\_VALUE](../../com.aspose.threed/stepmode\#NEXT-VALUE) は次の右側のキー フレームの値が使用されることを意味します。

**Returns:**
[StepMode](../../com.aspose.threed/stepmode) - the key's step mode. If the interpolation type is [Interpolation.CONSTANT](../../com.aspose.threed/interpolation\#CONSTANT), list.data[index] decides which key-frame's value will be used during interpolation. A [StepMode.PREVIOUS\_VALUE](../../com.aspose.threed/stepmode\#PREVIOUS-VALUE) means the left key-frame's value will be used A [StepMode.NEXT\_VALUE](../../com.aspose.threed/stepmode\#NEXT-VALUE) means the next right key-frame's value will be used
### getTangentWeightMode() {#getTangentWeightMode--}
```
public int getTangentWeightMode()
```


キーの接線ウェイトモードを取得します。アウト接線または次のイン接線は、適切な [WeightedMode](../../com.aspose.threed/weightedmode) を選択することでカスタマイズできます。

**Returns:**
int - キーの接線ウェイトモード。アウト接線または次のイン接線は、適切な [WeightedMode](../../com.aspose.threed/weightedmode) を選択することでカスタマイズできます。
### getTension() {#getTension--}
```
public float getTension()
```


TCB スプラインで使用されるテンションを取得する。

**Returns:**
float - TCB スプラインで使用されるテンション
### getTime() {#getTime--}
```
public double getTime()
```


list.data[index] キー フレームの時間位置を取得します（秒単位）。

**Returns:**
double - list.data[index] キーフレームの時間位置（秒で測定）
### getTimeIndependentTangent() {#getTimeIndependentTangent--}
```
public boolean getTimeIndependentTangent()
```


接線が時間に依存しないかを取得する。

**Returns:**
boolean - 接線は時間に依存しない
### getValue() {#getValue--}
```
public float getValue()
```


キー フレームの値を取得する。

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


TCB スプラインで使用されるバイアスを設定する。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| 値 | float | 新しい値 |

### setContinuity(float value) {#setContinuity-float-}
```
public void setContinuity(float value)
```


TCB スプラインで使用される連続性を設定する。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| 値 | float | 新しい値 |

### setFlat(boolean value) {#setFlat-boolean-}
```
public void setFlat(boolean value)
```


キー フレームがフラットかどうかを取得または設定します。次または前のキー フレームと同じ値の場合、キー フレームはフラットであるべきです。フラットなキー フレームはフラットな接線と固定された補間を持ちます。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| 値 | boolean | 新しい値 |

### setIndependentTangent(boolean value) {#setIndependentTangent-boolean-}
```
public void setIndependentTangent(boolean value)
```


アウトと次のイン接線が独立であることを設定します。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| 値 | boolean | 新しい値 |

### setInterpolation(Interpolation value) {#setInterpolation-com.aspose.threed.Interpolation-}
```
public void setInterpolation(Interpolation value)
```


キーの補間タイプを設定します。list.data[index] はサンプリングされた値の計算方法を定義するアルゴリズムです。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| value | [Interpolation](../../com.aspose.threed/interpolation) | 新しい値 |

### setNextInTangent(Vector2 value) {#setNextInTangent-com.aspose.threed.Vector2-}
```
public void setNextInTangent(Vector2 value)
```


このキー フレームの次のイン（左）接線を設定します。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| value | [Vector2](../../com.aspose.threed/vector2) | 新しい値 |

### setNextInWeight(float value) {#setNextInWeight-float-}
```
public void setNextInWeight(float value)
```


このキー フレームの次のイン（左）ウェイトを設定します。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| 値 | float | 新しい値 |

### setOutTangent(Vector2 value) {#setOutTangent-com.aspose.threed.Vector2-}
```
public void setOutTangent(Vector2 value)
```


このキー フレームのアウト（右）接線を設定します。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| value | [Vector2](../../com.aspose.threed/vector2) | 新しい値 |

### setOutWeight(float value) {#setOutWeight-float-}
```
public void setOutWeight(float value)
```


このキー フレームのアウト（右）ウェイトを設定します。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| 値 | float | 新しい値 |

### setStepMode(StepMode value) {#setStepMode-com.aspose.threed.StepMode-}
```
public void setStepMode(StepMode value)
```


キーのステップモードを設定します。補間タイプが [Interpolation.CONSTANT](../../com.aspose.threed/interpolation\#CONSTANT) の場合、list.data[index] は補間中に使用されるキーフレームの値を決定します。 [StepMode.PREVIOUS\_VALUE](../../com.aspose.threed/stepmode\#PREVIOUS-VALUE) は左側のキーフレームの値が使用されることを意味します。 [StepMode.NEXT\_VALUE](../../com.aspose.threed/stepmode\#NEXT-VALUE) は右側の次のキーフレームの値が使用されることを意味します

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| value | [StepMode](../../com.aspose.threed/stepmode) | 新しい値 |

### setTangentWeightMode(int value) {#setTangentWeightMode-int-}
```
public void setTangentWeightMode(int value)
```


キーの接線ウェイトモードを設定します。外部接線または次の内部接線は、適切な [WeightedMode](../../com.aspose.threed/weightedmode) を選択することでカスタマイズできます。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| 値 | int | 新しい値 |

### setTension(float value) {#setTension-float-}
```
public void setTension(float value)
```


TCB スプラインで使用されるテンションを設定します。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| 値 | float | 新しい値 |

### setTime(double value) {#setTime-double-}
```
public void setTime(double value)
```


list.data[index] キーフレームの時間位置を秒単位で設定します。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| 値 | double | 新しい値 |

### setTimeIndependentTangent(boolean value) {#setTimeIndependentTangent-boolean-}
```
public void setTimeIndependentTangent(boolean value)
```


接線が時間に依存しないように設定します。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| 値 | boolean | 新しい値 |

### setValue(float value) {#setValue-float-}
```
public void setValue(float value)
```


キーフレームの値を設定します。

**Parameters:**
| Parameter | Type | 説明 |
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
| Parameter | Type | 説明 |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |


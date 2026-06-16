---
title: "KeyFrame"
second_title: "Aspose.3D for Java API 参考"
description: "关键帧主要由时间和数值定义，对于某些插值类型，还会使用切线/张力/偏差/连续性来计算最终的采样值。"
type: docs
weight: 89
url: /zh/java/com.aspose.threed/keyframe/
---

**Inheritance:**
java.lang.Object
```
public class KeyFrame
```

关键帧主要由时间和数值定义，对于某些插值类型，切线/张力/偏差/连续性也用于计算最终的采样值。非关键帧时间位置的采样值由前后关键帧之间的关键帧进行插值。首个/最后一个关键帧之前或之后的数值由 [Extrapolation](../../com.aspose.threed/extrapolation) 类计算。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [KeyFrame(KeyframeSequence curve, double time)](#KeyFrame-com.aspose.threed.KeyframeSequence-double-) | 在指定曲线上创建新的关键帧 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBias()](#getBias--) | 获取在 TCB 样条中使用的偏差 |
| [getClass()](#getClass--) |  |
| [getContinuity()](#getContinuity--) | 获取在 TCB 样条中使用的连续性 |
| [getFlat()](#getFlat--) | 获取或设置关键帧是否为平坦。 |
| [getIndependentTangent()](#getIndependentTangent--) | 获取出切线和下一个入切线是否独立。 |
| [getInterpolation()](#getInterpolation--) | 获取关键帧的插值类型，list.data[index] 定义了计算采样值的算法。 |
| [getNextInTangent()](#getNextInTangent--) | 获取此关键帧的下一个左入切线。 |
| [getNextInWeight()](#getNextInWeight--) | 获取此关键帧的下一个左入权重。 |
| [getOutTangent()](#getOutTangent--) | 获取此关键帧的右出切线。 |
| [getOutWeight()](#getOutWeight--) | 获取此关键帧的右出权重。 |
| [getStepMode()](#getStepMode--) | 获取关键帧的步进模式。 |
| [getTangentWeightMode()](#getTangentWeightMode--) | 获取关键帧的切线权重模式。 |
| [getTension()](#getTension--) | 获取在 TCB 样条中使用的张力 |
| [getTime()](#getTime--) | 获取 list.data[index] 关键帧的时间位置（以秒为单位）。 |
| [getTimeIndependentTangent()](#getTimeIndependentTangent--) | 获取切线是否与时间无关 |
| [getValue()](#getValue--) | 获取关键帧的数值。 |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setBias(float value)](#setBias-float-) | 设置在 TCB 样条中使用的偏差 |
| [setContinuity(float value)](#setContinuity-float-) | 设置在 TCB 样条中使用的连续性 |
| [setFlat(boolean value)](#setFlat-boolean-) | 获取或设置关键帧是否为平坦。 |
| [setIndependentTangent(boolean value)](#setIndependentTangent-boolean-) | 设置出切线和下一个入切线为独立。 |
| [setInterpolation(Interpolation value)](#setInterpolation-com.aspose.threed.Interpolation-) | 设置键的插值类型，list.data[index] 定义了计算采样值的算法。 |
| [setNextInTangent(Vector2 value)](#setNextInTangent-com.aspose.threed.Vector2-) | 设置此关键帧上的下一个入（左）切线。 |
| [setNextInWeight(float value)](#setNextInWeight-float-) | 设置此关键帧上的下一个入（左）权重。 |
| [setOutTangent(Vector2 value)](#setOutTangent-com.aspose.threed.Vector2-) | 设置此关键帧上的出（右）切线。 |
| [setOutWeight(float value)](#setOutWeight-float-) | 设置此关键帧上的出（右）权重。 |
| [setStepMode(StepMode value)](#setStepMode-com.aspose.threed.StepMode-) | 设置键的步进模式。 |
| [setTangentWeightMode(int value)](#setTangentWeightMode-int-) | 设置键的切线权重模式。 |
| [setTension(float value)](#setTension-float-) | 设置 TCB 样条中使用的张力 |
| [setTime(double value)](#setTime-double-) | 设置 list.data[index] 关键帧的时间位置，单位为秒。 |
| [setTimeIndependentTangent(boolean value)](#setTimeIndependentTangent-boolean-) | 设置切线为时间无关。 |
| [setValue(float value)](#setValue-float-) | 设置关键帧的值。 |
| [toString()](#toString--) | 获取关键帧的字符串表示 |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### KeyFrame(KeyframeSequence curve, double time) {#KeyFrame-com.aspose.threed.KeyframeSequence-double-}
```
public KeyFrame(KeyframeSequence curve, double time)
```


在指定曲线上创建新的关键帧

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| curve | [KeyframeSequence](../../com.aspose.threed/keyframesequence) | 关键帧将被创建在的曲线 |
| 时间 | double | 关键帧的时间位置 |

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
布尔
### getBias() {#getBias--}
```
public float getBias()
```


获取在 TCB 样条中使用的偏差

**Returns:**
float - TCB 样条中使用的偏差
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


获取在 TCB 样条中使用的连续性

**Returns:**
float - TCB 样条中使用的连续性
### getFlat() {#getFlat--}
```
public boolean getFlat()
```


获取或设置关键帧是否平坦。如果下一个或上一个关键帧具有相同的值，则关键帧应为平坦。平坦的关键帧具有平坦的切线和固定的插值。

**Returns:**
boolean - 获取或设置关键帧是否平坦。如果下一个或上一个关键帧具有相同的值，则关键帧应为平坦。平坦的关键帧具有平坦的切线和固定的插值。
### getIndependentTangent() {#getIndependentTangent--}
```
public boolean getIndependentTangent()
```


获取出切线和下一个入切线是否独立。

**Returns:**
boolean - 出切线和下一个入切线是独立的。
### getInterpolation() {#getInterpolation--}
```
public Interpolation getInterpolation()
```


获取关键帧的插值类型，list.data[index] 定义了计算采样值的算法。

**Returns:**
[Interpolation](../../com.aspose.threed/interpolation) - the key's interpolation type, list.data[index] defines the algorithm how the sampled value is calculated.
### getNextInTangent() {#getNextInTangent--}
```
public Vector2 getNextInTangent()
```


获取此关键帧的下一个左入切线。

**Returns:**
[Vector2](../../com.aspose.threed/vector2) - the next in(left) tangent on this key frame.
### getNextInWeight() {#getNextInWeight--}
```
public float getNextInWeight()
```


获取此关键帧的下一个左入权重。

**Returns:**
float - 此关键帧上下一个入（左）权重。
### getOutTangent() {#getOutTangent--}
```
public Vector2 getOutTangent()
```


获取此关键帧的右出切线。

**Returns:**
[Vector2](../../com.aspose.threed/vector2) - the out(right) tangent on this key frame.
### getOutWeight() {#getOutWeight--}
```
public float getOutWeight()
```


获取此关键帧的右出权重。

**Returns:**
float - 此关键帧上出（右）权重。
### getStepMode() {#getStepMode--}
```
public StepMode getStepMode()
```


获取键的步进模式。如果插值类型是 [Interpolation.CONSTANT](../../com.aspose.threed/interpolation\#CONSTANT)，list.data[index] 决定在插值期间使用哪个关键帧的值。 [StepMode.PREVIOUS\_VALUE](../../com.aspose.threed/stepmode\#PREVIOUS-VALUE) 表示使用左侧关键帧的值， [StepMode.NEXT\_VALUE](../../com.aspose.threed/stepmode\#NEXT-VALUE) 表示使用下一个右侧关键帧的值。

**Returns:**
[StepMode](../../com.aspose.threed/stepmode) - the key's step mode. If the interpolation type is [Interpolation.CONSTANT](../../com.aspose.threed/interpolation\#CONSTANT), list.data[index] decides which key-frame's value will be used during interpolation. A [StepMode.PREVIOUS\_VALUE](../../com.aspose.threed/stepmode\#PREVIOUS-VALUE) means the left key-frame's value will be used A [StepMode.NEXT\_VALUE](../../com.aspose.threed/stepmode\#NEXT-VALUE) means the next right key-frame's value will be used
### getTangentWeightMode() {#getTangentWeightMode--}
```
public int getTangentWeightMode()
```


获取键的切线权重模式。可以通过选择正确的 [WeightedMode](../../com.aspose.threed/weightedmode) 来自定义出切线或下一个入切线。

**Returns:**
int - 键的切线权重模式。可以通过选择正确的 [WeightedMode](../../com.aspose.threed/weightedmode) 来自定义出切线或下一个入切线。
### getTension() {#getTension--}
```
public float getTension()
```


获取在 TCB 样条中使用的张力

**Returns:**
float - 在 TCB 样条中使用的张力
### getTime() {#getTime--}
```
public double getTime()
```


获取 list.data[index] 关键帧的时间位置（以秒为单位）。

**Returns:**
double - list.data[index] 关键帧的时间位置，以秒为单位。
### getTimeIndependentTangent() {#getTimeIndependentTangent--}
```
public boolean getTimeIndependentTangent()
```


获取切线是否与时间无关

**Returns:**
boolean - 切线与时间无关
### getValue() {#getValue--}
```
public float getValue()
```


获取关键帧的数值。

**Returns:**
float - 关键帧的值。
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


设置在 TCB 样条中使用的偏差

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | float | 新值 |

### setContinuity(float value) {#setContinuity-float-}
```
public void setContinuity(float value)
```


设置在 TCB 样条中使用的连续性

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | float | 新值 |

### setFlat(boolean value) {#setFlat-boolean-}
```
public void setFlat(boolean value)
```


获取或设置关键帧是否平坦。如果下一个或上一个关键帧具有相同的值，则关键帧应为平坦。平坦的关键帧具有平坦的切线和固定的插值。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | 布尔 | 新值 |

### setIndependentTangent(boolean value) {#setIndependentTangent-boolean-}
```
public void setIndependentTangent(boolean value)
```


设置出切线和下一个入切线为独立。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | 布尔 | 新值 |

### setInterpolation(Interpolation value) {#setInterpolation-com.aspose.threed.Interpolation-}
```
public void setInterpolation(Interpolation value)
```


设置键的插值类型，list.data[index] 定义了计算采样值的算法。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [Interpolation](../../com.aspose.threed/interpolation) | 新值 |

### setNextInTangent(Vector2 value) {#setNextInTangent-com.aspose.threed.Vector2-}
```
public void setNextInTangent(Vector2 value)
```


设置此关键帧上的下一个入（左）切线。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [Vector2](../../com.aspose.threed/vector2) | 新值 |

### setNextInWeight(float value) {#setNextInWeight-float-}
```
public void setNextInWeight(float value)
```


设置此关键帧上的下一个入（左）权重。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | float | 新值 |

### setOutTangent(Vector2 value) {#setOutTangent-com.aspose.threed.Vector2-}
```
public void setOutTangent(Vector2 value)
```


设置此关键帧上的出（右）切线。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [Vector2](../../com.aspose.threed/vector2) | 新值 |

### setOutWeight(float value) {#setOutWeight-float-}
```
public void setOutWeight(float value)
```


设置此关键帧上的出（右）权重。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | float | 新值 |

### setStepMode(StepMode value) {#setStepMode-com.aspose.threed.StepMode-}
```
public void setStepMode(StepMode value)
```


设置键的步进模式。如果插值类型是 [Interpolation.CONSTANT](../../com.aspose.threed/interpolation\#CONSTANT)，list.data[index] 决定在插值期间使用哪个关键帧的值。一个 [StepMode.PREVIOUS\_VALUE](../../com.aspose.threed/stepmode\#PREVIOUS-VALUE) 表示使用左侧关键帧的值；一个 [StepMode.NEXT\_VALUE](../../com.aspose.threed/stepmode\#NEXT-VALUE) 表示使用右侧下一个关键帧的值。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [StepMode](../../com.aspose.threed/stepmode) | 新值 |

### setTangentWeightMode(int value) {#setTangentWeightMode-int-}
```
public void setTangentWeightMode(int value)
```


设置键的切线权重模式。可以通过选择正确的 [WeightedMode](../../com.aspose.threed/weightedmode) 来自定义出切线或下一个入切线。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int | 新值 |

### setTension(float value) {#setTension-float-}
```
public void setTension(float value)
```


设置 TCB 样条中使用的张力

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | float | 新值 |

### setTime(double value) {#setTime-double-}
```
public void setTime(double value)
```


设置 list.data[index] 关键帧的时间位置，单位为秒。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | double | 新值 |

### setTimeIndependentTangent(boolean value) {#setTimeIndependentTangent-boolean-}
```
public void setTimeIndependentTangent(boolean value)
```


设置切线为时间无关。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | 布尔 | 新值 |

### setValue(float value) {#setValue-float-}
```
public void setValue(float value)
```


设置关键帧的值。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | float | 新值 |

### toString() {#toString--}
```
public String toString()
```


获取关键帧的字符串表示

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
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |


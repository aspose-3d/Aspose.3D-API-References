---
title: KeyFrame
second_title: Aspose.3D for Java API 레퍼런스
description: 키 프레임은 주로 시간과 값으로 정의되며, 일부 보간 유형에 대해 최종 샘플링 값을 계산할 때 접선/장력/바이어스/연속성도 사용됩니다.
type: docs
weight: 89
url: /ko/java/com.aspose.threed/keyframe/
---

**Inheritance:**
java.lang.Object
```
public class KeyFrame
```

키 프레임은 주로 시간과 값으로 정의되며, 일부 보간 유형에 대해 최종 샘플링 값을 계산할 때 접선/장력/바이어스/연속성도 사용됩니다. 비키프레임 시간 위치의 샘플링 값은 이전 및 다음 키프레임 사이의 키프레임에 의해 보간됩니다. 첫 번째/마지막 키프레임 이전/이후의 값은 [Extrapolation](../../com.aspose.threed/extrapolation) 클래스를 사용하여 계산됩니다.
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [KeyFrame(KeyframeSequence curve, double time)](#KeyFrame-com.aspose.threed.KeyframeSequence-double-) | 지정된 곡선에 새로운 키 프레임을 생성합니다. |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBias()](#getBias--) | TCB 스플라인에서 사용되는 바이어스를 가져옵니다. |
| [getClass()](#getClass--) |  |
| [getContinuity()](#getContinuity--) | TCB 스플라인에서 사용되는 연속성을 가져옵니다. |
| [getFlat()](#getFlat--) | 키 프레임이 평평한지 여부를 가져오거나 설정합니다. |
| [getIndependentTangent()](#getIndependentTangent--) | 외부 접선과 다음 내부 접선이 독립임을 가져옵니다. |
| [getInterpolation()](#getInterpolation--) | 키의 보간 유형을 가져옵니다. list.data[index]는 샘플링 값이 계산되는 알고리즘을 정의합니다. |
| [getNextInTangent()](#getNextInTangent--) | 이 키 프레임에서 다음 내부(왼쪽) 접선을 가져옵니다. |
| [getNextInWeight()](#getNextInWeight--) | 이 키 프레임에서 다음 내부(왼쪽) 가중치를 가져옵니다. |
| [getOutTangent()](#getOutTangent--) | 이 키 프레임에서 외부(오른쪽) 접선을 가져옵니다. |
| [getOutWeight()](#getOutWeight--) | 이 키 프레임에서 외부(오른쪽) 가중치를 가져옵니다. |
| [getStepMode()](#getStepMode--) | 키의 단계 모드를 가져옵니다. |
| [getTangentWeightMode()](#getTangentWeightMode--) | 키의 접선 가중치 모드를 가져옵니다. |
| [getTension()](#getTension--) | TCB 스플라인에서 사용되는 장력을 가져옵니다. |
| [getTime()](#getTime--) | list.data[index] 키 프레임의 시간 위치를 초 단위로 가져옵니다. |
| [getTimeIndependentTangent()](#getTimeIndependentTangent--) | 접선이 시간에 독립적임을 가져옵니다. |
| [getValue()](#getValue--) | 키 프레임의 값을 가져옵니다. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setBias(float value)](#setBias-float-) | TCB 스플라인에서 사용되는 바이어스를 설정합니다. |
| [setContinuity(float value)](#setContinuity-float-) | TCB 스플라인에서 사용되는 연속성을 설정합니다. |
| [setFlat(boolean value)](#setFlat-boolean-) | 키 프레임이 평평한지 여부를 가져오거나 설정합니다. |
| [setIndependentTangent(boolean value)](#setIndependentTangent-boolean-) | 출력 및 다음 입력 탄젠트가 독립적임을 설정합니다. |
| [setInterpolation(Interpolation value)](#setInterpolation-com.aspose.threed.Interpolation-) | 키의 보간 유형을 설정합니다. list.data[index]는 샘플링된 값이 계산되는 알고리즘을 정의합니다. |
| [setNextInTangent(Vector2 value)](#setNextInTangent-com.aspose.threed.Vector2-) | 이 키 프레임의 다음 입력(왼쪽) 탄젠트를 설정합니다. |
| [setNextInWeight(float value)](#setNextInWeight-float-) | 이 키 프레임의 다음 입력(왼쪽) 가중치를 설정합니다. |
| [setOutTangent(Vector2 value)](#setOutTangent-com.aspose.threed.Vector2-) | 이 키 프레임의 출력(오른쪽) 탄젠트를 설정합니다. |
| [setOutWeight(float value)](#setOutWeight-float-) | 이 키 프레임의 출력(오른쪽) 가중치를 설정합니다. |
| [setStepMode(StepMode value)](#setStepMode-com.aspose.threed.StepMode-) | 키의 단계 모드를 설정합니다. |
| [setTangentWeightMode(int value)](#setTangentWeightMode-int-) | 키의 탄젠트 가중치 모드를 설정합니다. |
| [setTension(float value)](#setTension-float-) | TCB 스플라인에 사용되는 장력을 설정합니다. |
| [setTime(double value)](#setTime-double-) | list.data[index] 키 프레임의 시간 위치를 초 단위로 설정합니다. |
| [setTimeIndependentTangent(boolean value)](#setTimeIndependentTangent-boolean-) | 탄젠트가 시간에 독립적임을 설정합니다. |
| [setValue(float value)](#setValue-float-) | 키 프레임의 값을 설정합니다. |
| [toString()](#toString--) | 키 프레임의 문자열 표현을 가져옵니다. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### KeyFrame(KeyframeSequence curve, double time) {#KeyFrame-com.aspose.threed.KeyframeSequence-double-}
```
public KeyFrame(KeyframeSequence curve, double time)
```


지정된 곡선에 새로운 키 프레임을 생성합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| curve | [KeyframeSequence](../../com.aspose.threed/keyframesequence) | 키 프레임이 생성될 곡선 |
| 시간 | double | 키 프레임의 시간 위치 |

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getBias() {#getBias--}
```
public float getBias()
```


TCB 스플라인에서 사용되는 바이어스를 가져옵니다.

**Returns:**
float - TCB 스플라인에 사용되는 바이어스
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


TCB 스플라인에서 사용되는 연속성을 가져옵니다.

**Returns:**
float - TCB 스플라인에 사용되는 연속성
### getFlat() {#getFlat--}
```
public boolean getFlat()
```


키 프레임이 평평한지 여부를 가져오거나 설정합니다. 다음 또는 이전 키 프레임이 동일한 값을 갖는 경우 키 프레임은 평평해야 합니다. 평평한 키 프레임은 평평한 탄젠트와 고정된 보간을 가집니다.

**Returns:**
boolean - 키 프레임이 평평한지 여부를 가져오거나 설정합니다. 다음 또는 이전 키 프레임이 동일한 값을 갖는 경우 키 프레임은 평평해야 합니다. 평평한 키 프레임은 평평한 탄젠트와 고정된 보간을 가집니다.
### getIndependentTangent() {#getIndependentTangent--}
```
public boolean getIndependentTangent()
```


외부 접선과 다음 내부 접선이 독립임을 가져옵니다.

**Returns:**
boolean - 출력 및 다음 입력 탄젠트가 독립적입니다.
### getInterpolation() {#getInterpolation--}
```
public Interpolation getInterpolation()
```


키의 보간 유형을 가져옵니다. list.data[index]는 샘플링 값이 계산되는 알고리즘을 정의합니다.

**Returns:**
[Interpolation](../../com.aspose.threed/interpolation) - the key's interpolation type, list.data[index] defines the algorithm how the sampled value is calculated.
### getNextInTangent() {#getNextInTangent--}
```
public Vector2 getNextInTangent()
```


이 키 프레임에서 다음 내부(왼쪽) 접선을 가져옵니다.

**Returns:**
[Vector2](../../com.aspose.threed/vector2) - the next in(left) tangent on this key frame.
### getNextInWeight() {#getNextInWeight--}
```
public float getNextInWeight()
```


이 키 프레임에서 다음 내부(왼쪽) 가중치를 가져옵니다.

**Returns:**
float - 이 키 프레임의 다음 입력(왼쪽) 가중치.
### getOutTangent() {#getOutTangent--}
```
public Vector2 getOutTangent()
```


이 키 프레임에서 외부(오른쪽) 접선을 가져옵니다.

**Returns:**
[Vector2](../../com.aspose.threed/vector2) - the out(right) tangent on this key frame.
### getOutWeight() {#getOutWeight--}
```
public float getOutWeight()
```


이 키 프레임에서 외부(오른쪽) 가중치를 가져옵니다.

**Returns:**
float - 이 키 프레임의 출력(오른쪽) 가중치.
### getStepMode() {#getStepMode--}
```
public StepMode getStepMode()
```


키의 단계 모드를 가져옵니다. 보간 유형이 [Interpolation.CONSTANT](../../com.aspose.threed/interpolation\#CONSTANT)인 경우, list.data[index]가 보간 중에 사용할 키 프레임 값을 결정합니다. [StepMode.PREVIOUS\_VALUE](../../com.aspose.threed/stepmode\#PREVIOUS-VALUE)는 왼쪽 키 프레임의 값이 사용됨을 의미하고, [StepMode.NEXT\_VALUE](../../com.aspose.threed/stepmode\#NEXT-VALUE)는 다음 오른쪽 키 프레임의 값이 사용됨을 의미합니다.

**Returns:**
[StepMode](../../com.aspose.threed/stepmode) - the key's step mode. If the interpolation type is [Interpolation.CONSTANT](../../com.aspose.threed/interpolation\#CONSTANT), list.data[index] decides which key-frame's value will be used during interpolation. A [StepMode.PREVIOUS\_VALUE](../../com.aspose.threed/stepmode\#PREVIOUS-VALUE) means the left key-frame's value will be used A [StepMode.NEXT\_VALUE](../../com.aspose.threed/stepmode\#NEXT-VALUE) means the next right key-frame's value will be used
### getTangentWeightMode() {#getTangentWeightMode--}
```
public int getTangentWeightMode()
```


키의 탄젠트 가중치 모드를 가져옵니다. 출력 탄젠트 또는 다음 입력 탄젠트는 올바른 [WeightedMode](../../com.aspose.threed/weightedmode)을 선택하여 사용자 정의할 수 있습니다.

**Returns:**
int - 키의 탄젠트 가중치 모드. 출력 탄젠트 또는 다음 입력 탄젠트는 올바른 [WeightedMode](../../com.aspose.threed/weightedmode)을 선택하여 사용자 정의할 수 있습니다.
### getTension() {#getTension--}
```
public float getTension()
```


TCB 스플라인에서 사용되는 장력을 가져옵니다.

**Returns:**
float - TCB 스플라인에서 사용되는 장력
### getTime() {#getTime--}
```
public double getTime()
```


list.data[index] 키 프레임의 시간 위치를 초 단위로 가져옵니다.

**Returns:**
double - list.data[index] 키 프레임의 시간 위치(초 단위).
### getTimeIndependentTangent() {#getTimeIndependentTangent--}
```
public boolean getTimeIndependentTangent()
```


접선이 시간에 독립적임을 가져옵니다.

**Returns:**
boolean - 접선은 시간에 독립적입니다
### getValue() {#getValue--}
```
public float getValue()
```


키 프레임의 값을 가져옵니다.

**Returns:**
float - 키 프레임의 값.
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


TCB 스플라인에서 사용되는 바이어스를 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | float | 새 값 |

### setContinuity(float value) {#setContinuity-float-}
```
public void setContinuity(float value)
```


TCB 스플라인에서 사용되는 연속성을 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | float | 새 값 |

### setFlat(boolean value) {#setFlat-boolean-}
```
public void setFlat(boolean value)
```


키 프레임이 평평한지 여부를 가져오거나 설정합니다. 다음 또는 이전 키 프레임이 동일한 값을 갖는 경우 키 프레임은 평평해야 합니다. 평평한 키 프레임은 평평한 탄젠트와 고정된 보간을 가집니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | boolean | 새 값 |

### setIndependentTangent(boolean value) {#setIndependentTangent-boolean-}
```
public void setIndependentTangent(boolean value)
```


출력 및 다음 입력 탄젠트가 독립적임을 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | boolean | 새 값 |

### setInterpolation(Interpolation value) {#setInterpolation-com.aspose.threed.Interpolation-}
```
public void setInterpolation(Interpolation value)
```


키의 보간 유형을 설정합니다. list.data[index]는 샘플링된 값이 계산되는 알고리즘을 정의합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [Interpolation](../../com.aspose.threed/interpolation) | 새 값 |

### setNextInTangent(Vector2 value) {#setNextInTangent-com.aspose.threed.Vector2-}
```
public void setNextInTangent(Vector2 value)
```


이 키 프레임의 다음 입력(왼쪽) 탄젠트를 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [Vector2](../../com.aspose.threed/vector2) | 새 값 |

### setNextInWeight(float value) {#setNextInWeight-float-}
```
public void setNextInWeight(float value)
```


이 키 프레임의 다음 입력(왼쪽) 가중치를 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | float | 새 값 |

### setOutTangent(Vector2 value) {#setOutTangent-com.aspose.threed.Vector2-}
```
public void setOutTangent(Vector2 value)
```


이 키 프레임의 출력(오른쪽) 탄젠트를 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [Vector2](../../com.aspose.threed/vector2) | 새 값 |

### setOutWeight(float value) {#setOutWeight-float-}
```
public void setOutWeight(float value)
```


이 키 프레임의 출력(오른쪽) 가중치를 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | float | 새 값 |

### setStepMode(StepMode value) {#setStepMode-com.aspose.threed.StepMode-}
```
public void setStepMode(StepMode value)
```


키의 단계 모드를 설정합니다. 보간 유형이 [Interpolation.CONSTANT](../../com.aspose.threed/interpolation\\#CONSTANT)인 경우, list.data[index]가 보간 중에 사용할 키 프레임 값을 결정합니다. [StepMode.PREVIOUS\\_VALUE](../../com.aspose.threed/stepmode\\#PREVIOUS-VALUE)는 왼쪽 키 프레임의 값을 사용함을 의미하고, [StepMode.NEXT\\_VALUE](../../com.aspose.threed/stepmode\\#NEXT-VALUE)는 오른쪽 다음 키 프레임의 값을 사용함을 의미합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [StepMode](../../com.aspose.threed/stepmode) | 새 값 |

### setTangentWeightMode(int value) {#setTangentWeightMode-int-}
```
public void setTangentWeightMode(int value)
```


키의 접선 가중치 모드를 설정합니다. 외부 접선 또는 다음 내부 접선은 올바른 [WeightedMode](../../com.aspose.threed/weightedmode)을 선택하여 사용자 정의할 수 있습니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int | 새 값 |

### setTension(float value) {#setTension-float-}
```
public void setTension(float value)
```


TCB 스플라인에 사용되는 장력을 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | float | 새 값 |

### setTime(double value) {#setTime-double-}
```
public void setTime(double value)
```


list.data[index] 키 프레임의 시간 위치를 초 단위로 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | double | 새 값 |

### setTimeIndependentTangent(boolean value) {#setTimeIndependentTangent-boolean-}
```
public void setTimeIndependentTangent(boolean value)
```


탄젠트가 시간에 독립적임을 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | boolean | 새 값 |

### setValue(float value) {#setValue-float-}
```
public void setValue(float value)
```


키 프레임의 값을 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | float | 새 값 |

### toString() {#toString--}
```
public String toString()
```


키 프레임의 문자열 표현을 가져옵니다.

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
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |


---
title: KeyFrame
second_title: Справочник API Aspose.3D для Java
description: Ключевой кадр в основном определяется временем и значением; для некоторых типов интерполяции также используется tangent/tension/bias/continuity при вычислении окончательного выборочного значения.
type: docs
weight: 89
url: /ru/java/com.aspose.threed/keyframe/
---

**Inheritance:**
java.lang.Object
```
public class KeyFrame
```

Ключевой кадр в основном определяется временем и значением; для некоторых типов интерполяции также используется tangent/tension/bias/continuity при вычислении окончательного выборочного значения. Выборочные значения в позиции времени, не являющейся ключевым кадром, интерполируются ключевыми кадрами между предыдущим и следующим ключевыми кадрами. Значения до/после первого/последнего ключевого кадра вычисляются классом [Extrapolation](../../com.aspose.threed/extrapolation).
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [KeyFrame(KeyframeSequence curve, double time)](#KeyFrame-com.aspose.threed.KeyframeSequence-double-) | Создать новый ключевой кадр на указанной кривой |
## Методы

| Метод | Описание |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBias()](#getBias--) | Получает bias, используемый в сплайне TCB |
| [getClass()](#getClass--) |  |
| [getContinuity()](#getContinuity--) | Получает continuity, используемый в сплайне TCB |
| [getFlat()](#getFlat--) | Получить или установить, является ли ключевой кадр плоским. |
| [getIndependentTangent()](#getIndependentTangent--) | Получает, что выходные и последующие входные тангенты независимы. |
| [getInterpolation()](#getInterpolation--) | Получает тип интерполяции ключа; list.data[index] определяет алгоритм расчёта выборочного значения. |
| [getNextInTangent()](#getNextInTangent--) | Получает следующий входной (левый) тангенс этого ключевого кадра. |
| [getNextInWeight()](#getNextInWeight--) | Получает следующий входной (левый) вес этого ключевого кадра. |
| [getOutTangent()](#getOutTangent--) | Получает выходной (правый) тангенс этого ключевого кадра. |
| [getOutWeight()](#getOutWeight--) | Получает выходной (правый) вес этого ключевого кадра. |
| [getStepMode()](#getStepMode--) | Получает режим шага ключа. |
| [getTangentWeightMode()](#getTangentWeightMode--) | Получает режим веса тангенса ключа. |
| [getTension()](#getTension--) | Получает tension, используемый в сплайне TCB |
| [getTime()](#getTime--) | Получает временную позицию ключевого кадра list.data[index], измеренную в секундах. |
| [getTimeIndependentTangent()](#getTimeIndependentTangent--) | Получает, что тангенс не зависит от времени. |
| [getValue()](#getValue--) | Получает значение ключевого кадра. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setBias(float value)](#setBias-float-) | Устанавливает bias, используемый в сплайне TCB |
| [setContinuity(float value)](#setContinuity-float-) | Устанавливает continuity, используемый в сплайне TCB |
| [setFlat(boolean value)](#setFlat-boolean-) | Получить или установить, является ли ключевой кадр плоским. |
| [setIndependentTangent(boolean value)](#setIndependentTangent-boolean-) | Устанавливает, что выходные и последующие входные касательные независимы. |
| [setInterpolation(Interpolation value)](#setInterpolation-com.aspose.threed.Interpolation-) | Устанавливает тип интерполяции ключа, list.data[index] определяет алгоритм расчёта выборочного значения. |
| [setNextInTangent(Vector2 value)](#setNextInTangent-com.aspose.threed.Vector2-) | Устанавливает следующую входную (левую) касательную для этого ключевого кадра. |
| [setNextInWeight(float value)](#setNextInWeight-float-) | Устанавливает вес следующей входной (левой) касательной для этого ключевого кадра. |
| [setOutTangent(Vector2 value)](#setOutTangent-com.aspose.threed.Vector2-) | Устанавливает выходную (правую) касательную для этого ключевого кадра. |
| [setOutWeight(float value)](#setOutWeight-float-) | Устанавливает вес выходной (правой) касательной для этого ключевого кадра. |
| [setStepMode(StepMode value)](#setStepMode-com.aspose.threed.StepMode-) | Устанавливает режим шага ключа. |
| [setTangentWeightMode(int value)](#setTangentWeightMode-int-) | Устанавливает режим веса касательной ключа. |
| [setTension(float value)](#setTension-float-) | Устанавливает натяжение, используемое в сплайне TCB |
| [setTime(double value)](#setTime-double-) | Устанавливает временную позицию ключевого кадра list.data[index], измеряемую в секундах. |
| [setTimeIndependentTangent(boolean value)](#setTimeIndependentTangent-boolean-) | Устанавливает, что касательная не зависит от времени |
| [setValue(float value)](#setValue-float-) | Устанавливает значение ключевого кадра. |
| [toString()](#toString--) | Получает строковое представление ключевого кадра |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### KeyFrame(KeyframeSequence curve, double time) {#KeyFrame-com.aspose.threed.KeyframeSequence-double-}
```
public KeyFrame(KeyframeSequence curve, double time)
```


Создать новый ключевой кадр на указанной кривой

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| curve | [KeyframeSequence](../../com.aspose.threed/keyframesequence) | Кривая, на которой будет создан ключевой кадр |
| время | double | Временная позиция ключевого кадра |

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getBias() {#getBias--}
```
public float getBias()
```


Получает bias, используемый в сплайне TCB

**Returns:**
float — смещение, используемое в сплайне TCB
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


Получает continuity, используемый в сплайне TCB

**Returns:**
float — непрерывность, используемая в сплайне TCB
### getFlat() {#getFlat--}
```
public boolean getFlat()
```


Получить или установить, является ли ключевой кадр плоским. Ключевой кадр должен быть плоским, если следующий или предыдущий кадр имеет то же значение. Плоский ключевой кадр имеет плоские касательные и фиксированную интерполяцию.

**Returns:**
boolean — получить или установить, является ли ключевой кадр плоским. Ключевой кадр должен быть плоским, если следующий или предыдущий кадр имеет то же значение. Плоский ключевой кадр имеет плоские касательные и фиксированную интерполяцию.
### getIndependentTangent() {#getIndependentTangent--}
```
public boolean getIndependentTangent()
```


Получает, что выходные и последующие входные тангенты независимы.

**Returns:**
boolean — выходные и последующие входные касательные независимы.
### getInterpolation() {#getInterpolation--}
```
public Interpolation getInterpolation()
```


Получает тип интерполяции ключа; list.data[index] определяет алгоритм расчёта выборочного значения.

**Returns:**
[Interpolation](../../com.aspose.threed/interpolation) - the key's interpolation type, list.data[index] defines the algorithm how the sampled value is calculated.
### getNextInTangent() {#getNextInTangent--}
```
public Vector2 getNextInTangent()
```


Получает следующий входной (левый) тангенс этого ключевого кадра.

**Returns:**
[Vector2](../../com.aspose.threed/vector2) - the next in(left) tangent on this key frame.
### getNextInWeight() {#getNextInWeight--}
```
public float getNextInWeight()
```


Получает следующий входной (левый) вес этого ключевого кадра.

**Returns:**
float — вес следующей входной (левой) касательной для этого ключевого кадра.
### getOutTangent() {#getOutTangent--}
```
public Vector2 getOutTangent()
```


Получает выходной (правый) тангенс этого ключевого кадра.

**Returns:**
[Vector2](../../com.aspose.threed/vector2) - the out(right) tangent on this key frame.
### getOutWeight() {#getOutWeight--}
```
public float getOutWeight()
```


Получает выходной (правый) вес этого ключевого кадра.

**Returns:**
float — вес выходной (правой) касательной для этого ключевого кадра.
### getStepMode() {#getStepMode--}
```
public StepMode getStepMode()
```


Получает режим шага ключа. Если тип интерполяции — [Interpolation.CONSTANT](../../com.aspose.threed/interpolation\\#CONSTANT), list.data[index] определяет, значение какого ключевого кадра будет использоваться при интерполяции. [StepMode.PREVIOUS\\_VALUE](../../com.aspose.threed/stepmode\\#PREVIOUS-VALUE) означает, что будет использовано значение левого ключевого кадра. [StepMode.NEXT\\_VALUE](../../com.aspose.threed/stepmode\\#NEXT-VALUE) означает, что будет использовано значение следующего правого ключевого кадра.

**Returns:**
[StepMode](../../com.aspose.threed/stepmode) - the key's step mode. If the interpolation type is [Interpolation.CONSTANT](../../com.aspose.threed/interpolation\#CONSTANT), list.data[index] decides which key-frame's value will be used during interpolation. A [StepMode.PREVIOUS\_VALUE](../../com.aspose.threed/stepmode\#PREVIOUS-VALUE) means the left key-frame's value will be used A [StepMode.NEXT\_VALUE](../../com.aspose.threed/stepmode\#NEXT-VALUE) means the next right key-frame's value will be used
### getTangentWeightMode() {#getTangentWeightMode--}
```
public int getTangentWeightMode()
```


Получает режим веса касательной ключа. Выходную касательную или следующую входную касательную можно настроить, выбрав правильный [WeightedMode](../../com.aspose.threed/weightedmode).

**Returns:**
int — режим веса касательной ключа. Выходную касательную или следующую входную касательную можно настроить, выбрав правильный [WeightedMode](../../com.aspose.threed/weightedmode).
### getTension() {#getTension--}
```
public float getTension()
```


Получает tension, используемый в сплайне TCB

**Returns:**
float - натяжение, используемое в сплайне TCB
### getTime() {#getTime--}
```
public double getTime()
```


Получает временную позицию ключевого кадра list.data[index], измеренную в секундах.

**Returns:**
double - позиция во времени ключевого кадра list.data[index], измеренная в секундах.
### getTimeIndependentTangent() {#getTimeIndependentTangent--}
```
public boolean getTimeIndependentTangent()
```


Получает, что тангенс не зависит от времени.

**Returns:**
boolean - касательная не зависит от времени
### getValue() {#getValue--}
```
public float getValue()
```


Получает значение ключевого кадра.

**Returns:**
float - значение ключевого кадра.
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


Устанавливает bias, используемый в сплайне TCB

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | float | Новое значение |

### setContinuity(float value) {#setContinuity-float-}
```
public void setContinuity(float value)
```


Устанавливает continuity, используемый в сплайне TCB

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | float | Новое значение |

### setFlat(boolean value) {#setFlat-boolean-}
```
public void setFlat(boolean value)
```


Получить или установить, является ли ключевой кадр плоским. Ключевой кадр должен быть плоским, если следующий или предыдущий кадр имеет то же значение. Плоский ключевой кадр имеет плоские касательные и фиксированную интерполяцию.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | boolean | Новое значение |

### setIndependentTangent(boolean value) {#setIndependentTangent-boolean-}
```
public void setIndependentTangent(boolean value)
```


Устанавливает, что выходные и последующие входные касательные независимы.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | boolean | Новое значение |

### setInterpolation(Interpolation value) {#setInterpolation-com.aspose.threed.Interpolation-}
```
public void setInterpolation(Interpolation value)
```


Устанавливает тип интерполяции ключа, list.data[index] определяет алгоритм расчёта выборочного значения.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [Interpolation](../../com.aspose.threed/interpolation) | Новое значение |

### setNextInTangent(Vector2 value) {#setNextInTangent-com.aspose.threed.Vector2-}
```
public void setNextInTangent(Vector2 value)
```


Устанавливает следующую входную (левую) касательную для этого ключевого кадра.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [Vector2](../../com.aspose.threed/vector2) | Новое значение |

### setNextInWeight(float value) {#setNextInWeight-float-}
```
public void setNextInWeight(float value)
```


Устанавливает вес следующей входной (левой) касательной для этого ключевого кадра.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | float | Новое значение |

### setOutTangent(Vector2 value) {#setOutTangent-com.aspose.threed.Vector2-}
```
public void setOutTangent(Vector2 value)
```


Устанавливает выходную (правую) касательную для этого ключевого кадра.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [Vector2](../../com.aspose.threed/vector2) | Новое значение |

### setOutWeight(float value) {#setOutWeight-float-}
```
public void setOutWeight(float value)
```


Устанавливает вес выходной (правой) касательной для этого ключевого кадра.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | float | Новое значение |

### setStepMode(StepMode value) {#setStepMode-com.aspose.threed.StepMode-}
```
public void setStepMode(StepMode value)
```


Устанавливает режим шага ключа. Если тип интерполяции — [Interpolation.CONSTANT](../../com.aspose.threed/interpolation\#CONSTANT), list.data[index] определяет, значение какого ключевого кадра будет использоваться во время интерполяции. [StepMode.PREVIOUS\_VALUE](../../com.aspose.threed/stepmode\#PREVIOUS-VALUE) означает, что будет использоваться значение левого ключевого кадра. [StepMode.NEXT\_VALUE](../../com.aspose.threed/stepmode\#NEXT-VALUE) означает, что будет использоваться значение следующего правого ключевого кадра.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [StepMode](../../com.aspose.threed/stepmode) | Новое значение |

### setTangentWeightMode(int value) {#setTangentWeightMode-int-}
```
public void setTangentWeightMode(int value)
```


Устанавливает режим веса касательной ключа. Выходная касательная или следующая входная касательная могут быть настроены путем выбора правильного [WeightedMode](../../com.aspose.threed/weightedmode).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int | Новое значение |

### setTension(float value) {#setTension-float-}
```
public void setTension(float value)
```


Устанавливает натяжение, используемое в сплайне TCB

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | float | Новое значение |

### setTime(double value) {#setTime-double-}
```
public void setTime(double value)
```


Устанавливает временную позицию ключевого кадра list.data[index], измеряемую в секундах.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | double | Новое значение |

### setTimeIndependentTangent(boolean value) {#setTimeIndependentTangent-boolean-}
```
public void setTimeIndependentTangent(boolean value)
```


Устанавливает, что касательная не зависит от времени

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | boolean | Новое значение |

### setValue(float value) {#setValue-float-}
```
public void setValue(float value)
```


Устанавливает значение ключевого кадра.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | float | Новое значение |

### toString() {#toString--}
```
public String toString()
```


Получает строковое представление ключевого кадра

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
| Параметр | Тип | Описание |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |


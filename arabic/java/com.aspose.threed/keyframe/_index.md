---
title: "KeyFrame"
second_title: "مرجع API لـ Aspose.3D for Java"
description: "الإطار الرئيسي يُعرَّف أساسًا بالوقت والقيمة، بالنسبة لبعض أنواع الاستيفاء تُستخدم tangent/tension/bias/continuity أيضًا عند حساب القيمة النهائية المأخوذة."
type: docs
weight: 89
url: /ar/java/com.aspose.threed/keyframe/
---

**Inheritance:**
java.lang.Object
```
public class KeyFrame
```

الإطار الرئيسي يُعرَّف أساسًا بالوقت والقيمة، بالنسبة لبعض أنواع الاستيفاء تُستخدم tangent/tension/bias/continuity أيضًا عند حساب القيمة النهائية المأخوذة. القيم المأخوذة في موضع زمني غير إطار رئيسي يتم استيفاؤها بواسطة الأطر الرئيسية بين الإطار السابق واللاحق. القيم قبل/بعد الإطار الرئيسي الأول/الأخير تُحسب بواسطة الفئة [Extrapolation](../../com.aspose.threed/extrapolation).
## المنشئات

| منشئ | الوصف |
| --- | --- |
| [KeyFrame(KeyframeSequence curve, double time)](#KeyFrame-com.aspose.threed.KeyframeSequence-double-) | إنشاء إطار رئيسي جديد على المنحنى المحدد |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBias()](#getBias--) | يحصل على الانحياز المستخدم في منحنى TCB |
| [getClass()](#getClass--) |  |
| [getContinuity()](#getContinuity--) | يحصل على الاستمرارية المستخدمة في منحنى TCB |
| [getFlat()](#getFlat--) | احصل أو عيّن ما إذا كان الإطار الرئيسي مسطحًا. |
| [getIndependentTangent()](#getIndependentTangent--) | يحصل على أن المماس الخارج والمماس الداخل التالي مستقلان. |
| [getInterpolation()](#getInterpolation--) | يحصل على نوع الاستيفاء للإطار، حيث يحدد list.data[index] الخوارزمية التي تُحسب بها القيمة المأخوذة. |
| [getNextInTangent()](#getNextInTangent--) | يحصل على المماس الداخل (اليسار) التالي في هذا الإطار الرئيسي. |
| [getNextInWeight()](#getNextInWeight--) | يحصل على الوزن الداخل (اليسار) التالي في هذا الإطار الرئيسي. |
| [getOutTangent()](#getOutTangent--) | يحصل على المماس الخارج (اليمين) في هذا الإطار الرئيسي. |
| [getOutWeight()](#getOutWeight--) | يحصل على الوزن الخارج (اليمين) في هذا الإطار الرئيسي. |
| [getStepMode()](#getStepMode--) | يحصل على وضع خطوة الإطار. |
| [getTangentWeightMode()](#getTangentWeightMode--) | يحصل على وضع وزن المماس للإطار. |
| [getTension()](#getTension--) | يحصل على التوتر المستخدم في منحنى TCB |
| [getTime()](#getTime--) | يحصل على موضع الوقت لإطار list.data[index]، مقاسًا بالثواني. |
| [getTimeIndependentTangent()](#getTimeIndependentTangent--) | يحصل على أن المماس غير معتمد على الوقت. |
| [getValue()](#getValue--) | يحصل على قيمة الإطار الرئيسي. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setBias(float value)](#setBias-float-) | يضبط الانحياز المستخدم في منحنى TCB |
| [setContinuity(float value)](#setContinuity-float-) | يضبط الاستمرارية المستخدمة في منحنى TCB |
| [setFlat(boolean value)](#setFlat-boolean-) | احصل أو عيّن ما إذا كان الإطار الرئيسي مسطحًا. |
| [setIndependentTangent(boolean value)](#setIndependentTangent-boolean-) | يضبط أن المماس الخارجي والمماس الداخلي التالي مستقلان. |
| [setInterpolation(Interpolation value)](#setInterpolation-com.aspose.threed.Interpolation-) | يضبط نوع الاستيفاء للمفتاح، حيث يحدد list.data[index] الخوارزمية التي يتم بها حساب القيمة المأخوذة. |
| [setNextInTangent(Vector2 value)](#setNextInTangent-com.aspose.threed.Vector2-) | يضبط المماس الداخلي (اليسار) التالي في إطار المفتاح هذا. |
| [setNextInWeight(float value)](#setNextInWeight-float-) | يضبط وزن المماس الداخلي (اليسار) التالي في إطار المفتاح هذا. |
| [setOutTangent(Vector2 value)](#setOutTangent-com.aspose.threed.Vector2-) | يضبط المماس الخارجي (اليمين) في إطار المفتاح هذا. |
| [setOutWeight(float value)](#setOutWeight-float-) | يضبط وزن المماس الخارجي (اليمين) في إطار المفتاح هذا. |
| [setStepMode(StepMode value)](#setStepMode-com.aspose.threed.StepMode-) | يضبط وضع خطوة المفتاح. |
| [setTangentWeightMode(int value)](#setTangentWeightMode-int-) | يضبط وضع وزن المماس للمفتاح. |
| [setTension(float value)](#setTension-float-) | يضبط الشد المستخدم في المنحنى TCB. |
| [setTime(double value)](#setTime-double-) | يضبط موضع الوقت لإطار المفتاح list.data[index]، مقاسًا بالثواني. |
| [setTimeIndependentTangent(boolean value)](#setTimeIndependentTangent-boolean-) | يضبط أن المماس غير معتمد على الوقت. |
| [setValue(float value)](#setValue-float-) | يضبط قيمة إطار المفتاح. |
| [toString()](#toString--) | يحصل على تمثيل السلسلة لإطار المفتاح. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### KeyFrame(KeyframeSequence curve, double time) {#KeyFrame-com.aspose.threed.KeyframeSequence-double-}
```
public KeyFrame(KeyframeSequence curve, double time)
```


إنشاء إطار رئيسي جديد على المنحنى المحدد

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| curve | [KeyframeSequence](../../com.aspose.threed/keyframesequence) | المنحنى الذي سيتم إنشاء إطار المفتاح عليه. |
| الوقت | double | موضع الوقت لإطار المفتاح. |

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getBias() {#getBias--}
```
public float getBias()
```


يحصل على الانحياز المستخدم في منحنى TCB

**Returns:**
float - الانحياز المستخدم في منحنى TCB.
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


يحصل على الاستمرارية المستخدمة في منحنى TCB

**Returns:**
float - الاستمرارية المستخدمة في منحنى TCB.
### getFlat() {#getFlat--}
```
public boolean getFlat()
```


احصل أو اضبط ما إذا كان إطار المفتاح مسطحًا. يجب أن يكون إطار المفتاح مسطحًا إذا كان إطار المفتاح التالي أو السابق له نفس القيمة. إطار المفتاح المسطح له مسايس مسطحة واستيفاء ثابت.

**Returns:**
boolean - احصل أو اضبط ما إذا كان إطار المفتاح مسطحًا. يجب أن يكون إطار المفتاح مسطحًا إذا كان إطار المفتاح التالي أو السابق له نفس القيمة. إطار المفتاح المسطح له مسايس مسطحة واستيفاء ثابت.
### getIndependentTangent() {#getIndependentTangent--}
```
public boolean getIndependentTangent()
```


يحصل على أن المماس الخارج والمماس الداخل التالي مستقلان.

**Returns:**
boolean - المماس الخارجي والمماس الداخلي التالي مستقلان.
### getInterpolation() {#getInterpolation--}
```
public Interpolation getInterpolation()
```


يحصل على نوع الاستيفاء للإطار، حيث يحدد list.data[index] الخوارزمية التي تُحسب بها القيمة المأخوذة.

**Returns:**
[Interpolation](../../com.aspose.threed/interpolation) - the key's interpolation type, list.data[index] defines the algorithm how the sampled value is calculated.
### getNextInTangent() {#getNextInTangent--}
```
public Vector2 getNextInTangent()
```


يحصل على المماس الداخل (اليسار) التالي في هذا الإطار الرئيسي.

**Returns:**
[Vector2](../../com.aspose.threed/vector2) - the next in(left) tangent on this key frame.
### getNextInWeight() {#getNextInWeight--}
```
public float getNextInWeight()
```


يحصل على الوزن الداخل (اليسار) التالي في هذا الإطار الرئيسي.

**Returns:**
float - وزن المماس الداخلي (اليسار) التالي في إطار المفتاح هذا.
### getOutTangent() {#getOutTangent--}
```
public Vector2 getOutTangent()
```


يحصل على المماس الخارج (اليمين) في هذا الإطار الرئيسي.

**Returns:**
[Vector2](../../com.aspose.threed/vector2) - the out(right) tangent on this key frame.
### getOutWeight() {#getOutWeight--}
```
public float getOutWeight()
```


يحصل على الوزن الخارج (اليمين) في هذا الإطار الرئيسي.

**Returns:**
float - وزن المماس الخارجي (اليمين) في إطار المفتاح هذا.
### getStepMode() {#getStepMode--}
```
public StepMode getStepMode()
```


يحصل على وضع خطوة المفتاح. إذا كان نوع الاستيفاء هو [Interpolation.CONSTANT](../../com.aspose.threed/interpolation\#CONSTANT)، فإن list.data[index] يقرر أي قيمة لإطار المفتاح ستُستخدم أثناء الاستيفاء. يعني [StepMode.PREVIOUS\_VALUE](../../com.aspose.threed/stepmode\#PREVIOUS-VALUE) أن قيمة إطار المفتاح الأيسر ستُستخدم. يعني [StepMode.NEXT\_VALUE](../../com.aspose.threed/stepmode\#NEXT-VALUE) أن قيمة إطار المفتاح الأيمن التالي ستُستخدم.

**Returns:**
[StepMode](../../com.aspose.threed/stepmode) - the key's step mode. If the interpolation type is [Interpolation.CONSTANT](../../com.aspose.threed/interpolation\#CONSTANT), list.data[index] decides which key-frame's value will be used during interpolation. A [StepMode.PREVIOUS\_VALUE](../../com.aspose.threed/stepmode\#PREVIOUS-VALUE) means the left key-frame's value will be used A [StepMode.NEXT\_VALUE](../../com.aspose.threed/stepmode\#NEXT-VALUE) means the next right key-frame's value will be used
### getTangentWeightMode() {#getTangentWeightMode--}
```
public int getTangentWeightMode()
```


يحصل على وضع وزن المماس للمفتاح. يمكن تخصيص المماس الخارجي أو المماس الداخلي التالي عن طريق اختيار [WeightedMode](../../com.aspose.threed/weightedmode) الصحيح.

**Returns:**
int - وضع وزن المماس للمفتاح. يمكن تخصيص المماس الخارجي أو المماس الداخلي التالي عن طريق اختيار [WeightedMode](../../com.aspose.threed/weightedmode) الصحيح.
### getTension() {#getTension--}
```
public float getTension()
```


يحصل على التوتر المستخدم في منحنى TCB

**Returns:**
float - التوتر المستخدم في منحنى TCB
### getTime() {#getTime--}
```
public double getTime()
```


يحصل على موضع الوقت لإطار list.data[index]، مقاسًا بالثواني.

**Returns:**
double - موضع الوقت لإطار المفتاح list.data[index]، مقاسًا بالثواني.
### getTimeIndependentTangent() {#getTimeIndependentTangent--}
```
public boolean getTimeIndependentTangent()
```


يحصل على أن المماس غير معتمد على الوقت.

**Returns:**
boolean - المماس غير معتمد على الوقت
### getValue() {#getValue--}
```
public float getValue()
```


يحصل على قيمة الإطار الرئيسي.

**Returns:**
float - قيمة إطار المفتاح.
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


يضبط الانحياز المستخدم في منحنى TCB

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | float | القيمة الجديدة |

### setContinuity(float value) {#setContinuity-float-}
```
public void setContinuity(float value)
```


يضبط الاستمرارية المستخدمة في منحنى TCB

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | float | القيمة الجديدة |

### setFlat(boolean value) {#setFlat-boolean-}
```
public void setFlat(boolean value)
```


احصل أو اضبط ما إذا كان إطار المفتاح مسطحًا. يجب أن يكون إطار المفتاح مسطحًا إذا كان إطار المفتاح التالي أو السابق له نفس القيمة. إطار المفتاح المسطح له مسايس مسطحة واستيفاء ثابت.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | boolean | القيمة الجديدة |

### setIndependentTangent(boolean value) {#setIndependentTangent-boolean-}
```
public void setIndependentTangent(boolean value)
```


يضبط أن المماس الخارجي والمماس الداخلي التالي مستقلان.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | boolean | القيمة الجديدة |

### setInterpolation(Interpolation value) {#setInterpolation-com.aspose.threed.Interpolation-}
```
public void setInterpolation(Interpolation value)
```


يضبط نوع الاستيفاء للمفتاح، حيث يحدد list.data[index] الخوارزمية التي يتم بها حساب القيمة المأخوذة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [Interpolation](../../com.aspose.threed/interpolation) | القيمة الجديدة |

### setNextInTangent(Vector2 value) {#setNextInTangent-com.aspose.threed.Vector2-}
```
public void setNextInTangent(Vector2 value)
```


يضبط المماس الداخلي (اليسار) التالي في إطار المفتاح هذا.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [Vector2](../../com.aspose.threed/vector2) | القيمة الجديدة |

### setNextInWeight(float value) {#setNextInWeight-float-}
```
public void setNextInWeight(float value)
```


يضبط وزن المماس الداخلي (اليسار) التالي في إطار المفتاح هذا.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | float | القيمة الجديدة |

### setOutTangent(Vector2 value) {#setOutTangent-com.aspose.threed.Vector2-}
```
public void setOutTangent(Vector2 value)
```


يضبط المماس الخارجي (اليمين) في إطار المفتاح هذا.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [Vector2](../../com.aspose.threed/vector2) | القيمة الجديدة |

### setOutWeight(float value) {#setOutWeight-float-}
```
public void setOutWeight(float value)
```


يضبط وزن المماس الخارجي (اليمين) في إطار المفتاح هذا.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | float | القيمة الجديدة |

### setStepMode(StepMode value) {#setStepMode-com.aspose.threed.StepMode-}
```
public void setStepMode(StepMode value)
```


يضبط وضع خطوة المفتاح. إذا كان نوع الاستيفاء هو [Interpolation.CONSTANT](../../com.aspose.threed/interpolation\#CONSTANT)، فإن list.data[index] يحدد أي قيمة لإطار المفتاح ستُستخدم أثناء الاستيفاء. يعني [StepMode.PREVIOUS\_VALUE](../../com.aspose.threed/stepmode\#PREVIOUS-VALUE) أن قيمة إطار المفتاح الأيسر ستُستخدم. يعني [StepMode.NEXT\_VALUE](../../com.aspose.threed/stepmode\#NEXT-VALUE) أن قيمة إطار المفتاح الأيمن التالي ستُستخدم.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [StepMode](../../com.aspose.threed/stepmode) | القيمة الجديدة |

### setTangentWeightMode(int value) {#setTangentWeightMode-int-}
```
public void setTangentWeightMode(int value)
```


يضبط وضع وزن المماس للمفتاح. يمكن تخصيص المماس الخارج أو المماس الداخل التالي عن طريق اختيار [WeightedMode](../../com.aspose.threed/weightedmode) الصحيح.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int | القيمة الجديدة |

### setTension(float value) {#setTension-float-}
```
public void setTension(float value)
```


يضبط الشد المستخدم في المنحنى TCB.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | float | القيمة الجديدة |

### setTime(double value) {#setTime-double-}
```
public void setTime(double value)
```


يضبط موضع الوقت لإطار المفتاح list.data[index]، مقاسًا بالثواني.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | double | القيمة الجديدة |

### setTimeIndependentTangent(boolean value) {#setTimeIndependentTangent-boolean-}
```
public void setTimeIndependentTangent(boolean value)
```


يضبط أن المماس غير معتمد على الوقت.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | boolean | القيمة الجديدة |

### setValue(float value) {#setValue-float-}
```
public void setValue(float value)
```


يضبط قيمة إطار المفتاح.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | float | القيمة الجديدة |

### toString() {#toString--}
```
public String toString()
```


يحصل على تمثيل السلسلة لإطار المفتاح.

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
| معامل | نوع | الوصف |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |


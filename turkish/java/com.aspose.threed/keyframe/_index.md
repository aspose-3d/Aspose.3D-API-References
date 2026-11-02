---
title: "KeyFrame"
second_title: "Aspose.3D for Java API Referansı"
description: "Bir anahtar çerçeve, esas olarak bir zaman ve bir değer ile tanımlanır; bazı ara değerleme türleri için tangent/tension/bias/continuity da son örneklenmiş değerin hesaplanmasında kullanılır."
type: docs
weight: 89
url: /tr/java/com.aspose.threed/keyframe/
---

**Inheritance:**
java.lang.Object
```
public class KeyFrame
```

Bir anahtar çerçeve, esas olarak bir zaman ve bir değer ile tanımlanır; bazı ara değerleme türleri için tangent/tension/bias/continuity da son örneklenmiş değerin hesaplanmasında kullanılır. Anahtar çerçeve olmayan bir zaman konumundaki örneklenmiş değerler, önceki ve sonraki anahtar çerçeveler arasındaki anahtar çerçeveler tarafından ara değerlenir. İlk/son anahtar çerçeveden önceki/sonraki değerler, [Extrapolation](../../com.aspose.threed/extrapolation) sınıfı tarafından hesaplanır.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [KeyFrame(KeyframeSequence curve, double time)](#KeyFrame-com.aspose.threed.KeyframeSequence-double-) | Belirtilen eğri üzerinde yeni bir anahtar çerçeve oluştur. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBias()](#getBias--) | TCB spline'ında kullanılan sapmayı alır. |
| [getClass()](#getClass--) |  |
| [getContinuity()](#getContinuity--) | TCB spline'ında kullanılan sürekliliği alır. |
| [getFlat()](#getFlat--) | Anahtar çerçevenin düz olup olmadığını al veya ayarla. |
| [getIndependentTangent()](#getIndependentTangent--) | Çıkış ve sonraki giriş teğetlerinin bağımsız olduğunu alır. |
| [getInterpolation()](#getInterpolation--) | Anahtarın ara değerleme türünü alır, list.data[index] örneklenmiş değerin nasıl hesaplandığını belirleyen algoritmayı tanımlar. |
| [getNextInTangent()](#getNextInTangent--) | Bu anahtar çerçevedeki sonraki giriş (sol) teğetini alır. |
| [getNextInWeight()](#getNextInWeight--) | Bu anahtar çerçevedeki sonraki giriş (sol) ağırlığını alır. |
| [getOutTangent()](#getOutTangent--) | Bu anahtar çerçevedeki çıkış (sağ) teğetini alır. |
| [getOutWeight()](#getOutWeight--) | Bu anahtar çerçevedeki çıkış (sağ) ağırlığını alır. |
| [getStepMode()](#getStepMode--) | Anahtarın adım modunu alır. |
| [getTangentWeightMode()](#getTangentWeightMode--) | Anahtarın teğet ağırlık modunu alır. |
| [getTension()](#getTension--) | TCB spline'ında kullanılan gerilimi alır. |
| [getTime()](#getTime--) | list.data[index] anahtar çerçevenin zaman konumunu alır, saniye cinsinden ölçülür. |
| [getTimeIndependentTangent()](#getTimeIndependentTangent--) | Teğetin zaman bağımsız olduğunu alır. |
| [getValue()](#getValue--) | Anahtar çerçevenin değerini alır. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setBias(float value)](#setBias-float-) | TCB spline'ında kullanılan sapmayı ayarlar. |
| [setContinuity(float value)](#setContinuity-float-) | TCB spline'ında kullanılan sürekliliği ayarlar. |
| [setFlat(boolean value)](#setFlat-boolean-) | Anahtar çerçevenin düz olup olmadığını al veya ayarla. |
| [setIndependentTangent(boolean value)](#setIndependentTangent-boolean-) | Dış ve bir sonraki giriş teğetlerinin bağımsız olduğunu ayarlar. |
| [setInterpolation(Interpolation value)](#setInterpolation-com.aspose.threed.Interpolation-) | Anahtarın ara değerleme tipini ayarlar, list.data[index] örneklenen değerin nasıl hesaplandığını belirleyen algoritmayı tanımlar. |
| [setNextInTangent(Vector2 value)](#setNextInTangent-com.aspose.threed.Vector2-) | Bu anahtar çerçevede bir sonraki giriş (sol) teğetini ayarlar. |
| [setNextInWeight(float value)](#setNextInWeight-float-) | Bu anahtar çerçevede bir sonraki giriş (sol) ağırlığını ayarlar. |
| [setOutTangent(Vector2 value)](#setOutTangent-com.aspose.threed.Vector2-) | Bu anahtar çerçevede dış (sağ) teğeti ayarlar. |
| [setOutWeight(float value)](#setOutWeight-float-) | Bu anahtar çerçevede dış (sağ) ağırlığı ayarlar. |
| [setStepMode(StepMode value)](#setStepMode-com.aspose.threed.StepMode-) | Anahtarın adım modunu ayarlar. |
| [setTangentWeightMode(int value)](#setTangentWeightMode-int-) | Anahtarın teğet ağırlık modunu ayarlar. |
| [setTension(float value)](#setTension-float-) | TCB spline içinde kullanılan gerilimi ayarlar. |
| [setTime(double value)](#setTime-double-) | list.data[index] anahtar çerçevesinin zaman konumunu, saniye cinsinden ayarlar. |
| [setTimeIndependentTangent(boolean value)](#setTimeIndependentTangent-boolean-) | Teğetin zaman bağımsız olduğunu ayarlar. |
| [setValue(float value)](#setValue-float-) | Anahtar çerçevenin değerini ayarlar. |
| [toString()](#toString--) | Anahtar çerçevenin dize temsilini alır. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### KeyFrame(KeyframeSequence curve, double time) {#KeyFrame-com.aspose.threed.KeyframeSequence-double-}
```
public KeyFrame(KeyframeSequence curve, double time)
```


Belirtilen eğri üzerinde yeni bir anahtar çerçeve oluştur.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| curve | [KeyframeSequence](../../com.aspose.threed/keyframesequence) | Anahtar çerçevenin oluşturulacağı eğri. |
| zaman | double | Anahtar çerçevenin zaman konumu. |

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getBias() {#getBias--}
```
public float getBias()
```


TCB spline'ında kullanılan sapmayı alır.

**Returns:**
float - TCB spline içinde kullanılan sapma
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


TCB spline'ında kullanılan sürekliliği alır.

**Returns:**
float - TCB spline içinde kullanılan süreklilik
### getFlat() {#getFlat--}
```
public boolean getFlat()
```


Anahtar çerçevenin düz olup olmadığını al veya ayarla. Bir sonraki veya önceki anahtar çerçeve aynı değere sahipse anahtar çerçeve düz olmalıdır. Düz anahtar çerçeve düz teğetlere ve sabit ara değerlemeye sahiptir.

**Returns:**
boolean - Anahtar çerçevenin düz olup olmadığını al veya ayarla. Bir sonraki veya önceki anahtar çerçeve aynı değere sahipse anahtar çerçeve düz olmalıdır. Düz anahtar çerçeve düz teğetlere ve sabit ara değerlemeye sahiptir.
### getIndependentTangent() {#getIndependentTangent--}
```
public boolean getIndependentTangent()
```


Çıkış ve sonraki giriş teğetlerinin bağımsız olduğunu alır.

**Returns:**
boolean - dış ve bir sonraki giriş teğetlerinin bağımsız olduğunu.
### getInterpolation() {#getInterpolation--}
```
public Interpolation getInterpolation()
```


Anahtarın ara değerleme türünü alır, list.data[index] örneklenmiş değerin nasıl hesaplandığını belirleyen algoritmayı tanımlar.

**Returns:**
[Interpolation](../../com.aspose.threed/interpolation) - the key's interpolation type, list.data[index] defines the algorithm how the sampled value is calculated.
### getNextInTangent() {#getNextInTangent--}
```
public Vector2 getNextInTangent()
```


Bu anahtar çerçevedeki sonraki giriş (sol) teğetini alır.

**Returns:**
[Vector2](../../com.aspose.threed/vector2) - the next in(left) tangent on this key frame.
### getNextInWeight() {#getNextInWeight--}
```
public float getNextInWeight()
```


Bu anahtar çerçevedeki sonraki giriş (sol) ağırlığını alır.

**Returns:**
float - bu anahtar çerçevede bir sonraki giriş (sol) ağırlığı.
### getOutTangent() {#getOutTangent--}
```
public Vector2 getOutTangent()
```


Bu anahtar çerçevedeki çıkış (sağ) teğetini alır.

**Returns:**
[Vector2](../../com.aspose.threed/vector2) - the out(right) tangent on this key frame.
### getOutWeight() {#getOutWeight--}
```
public float getOutWeight()
```


Bu anahtar çerçevedeki çıkış (sağ) ağırlığını alır.

**Returns:**
float - bu anahtar çerçevede dış (sağ) ağırlığı.
### getStepMode() {#getStepMode--}
```
public StepMode getStepMode()
```


Anahtarın adım modunu alır. Eğer ara değerleme tipi [Interpolation.CONSTANT](../../com.aspose.threed/interpolation\#CONSTANT) ise, list.data[index] ara değerleme sırasında hangi anahtar‑çerçevenin değerinin kullanılacağını belirler. Bir [StepMode.PREVIOUS\_VALUE](../../com.aspose.threed/stepmode\#PREVIOUS-VALUE) sol anahtar‑çerçevenin değerinin kullanılacağını, bir [StepMode.NEXT\_VALUE](../../com.aspose.threed/stepmode\#NEXT-VALUE) ise bir sonraki sağ anahtar‑çerçevenin değerinin kullanılacağını ifade eder.

**Returns:**
[StepMode](../../com.aspose.threed/stepmode) - the key's step mode. If the interpolation type is [Interpolation.CONSTANT](../../com.aspose.threed/interpolation\#CONSTANT), list.data[index] decides which key-frame's value will be used during interpolation. A [StepMode.PREVIOUS\_VALUE](../../com.aspose.threed/stepmode\#PREVIOUS-VALUE) means the left key-frame's value will be used A [StepMode.NEXT\_VALUE](../../com.aspose.threed/stepmode\#NEXT-VALUE) means the next right key-frame's value will be used
### getTangentWeightMode() {#getTangentWeightMode--}
```
public int getTangentWeightMode()
```


Anahtarın teğet ağırlık modunu alır. Dış teğet veya bir sonraki giriş teğeti, doğru [WeightedMode](../../com.aspose.threed/weightedmode) seçilerek özelleştirilebilir.

**Returns:**
int - anahtarın teğet ağırlık modu. Dış teğet veya bir sonraki giriş teğeti, doğru [WeightedMode](../../com.aspose.threed/weightedmode) seçilerek özelleştirilebilir.
### getTension() {#getTension--}
```
public float getTension()
```


TCB spline'ında kullanılan gerilimi alır.

**Returns:**
float - TCB spline'inde kullanılan gerilim
### getTime() {#getTime--}
```
public double getTime()
```


list.data[index] anahtar çerçevenin zaman konumunu alır, saniye cinsinden ölçülür.

**Returns:**
double - list.data[index] anahtar çerçevesinin zaman konumu, saniye cinsinden ölçülür.
### getTimeIndependentTangent() {#getTimeIndependentTangent--}
```
public boolean getTimeIndependentTangent()
```


Teğetin zaman bağımsız olduğunu alır.

**Returns:**
boolean - teğet zaman bağımsızdır
### getValue() {#getValue--}
```
public float getValue()
```


Anahtar çerçevenin değerini alır.

**Returns:**
float - anahtar çerçevenin değeri.
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


TCB spline'ında kullanılan sapmayı ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | float | Yeni değer |

### setContinuity(float value) {#setContinuity-float-}
```
public void setContinuity(float value)
```


TCB spline'ında kullanılan sürekliliği ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | float | Yeni değer |

### setFlat(boolean value) {#setFlat-boolean-}
```
public void setFlat(boolean value)
```


Anahtar çerçevenin düz olup olmadığını al veya ayarla. Bir sonraki veya önceki anahtar çerçeve aynı değere sahipse anahtar çerçeve düz olmalıdır. Düz anahtar çerçeve düz teğetlere ve sabit ara değerlemeye sahiptir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean | Yeni değer |

### setIndependentTangent(boolean value) {#setIndependentTangent-boolean-}
```
public void setIndependentTangent(boolean value)
```


Dış ve bir sonraki giriş teğetlerinin bağımsız olduğunu ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean | Yeni değer |

### setInterpolation(Interpolation value) {#setInterpolation-com.aspose.threed.Interpolation-}
```
public void setInterpolation(Interpolation value)
```


Anahtarın ara değerleme tipini ayarlar, list.data[index] örneklenen değerin nasıl hesaplandığını belirleyen algoritmayı tanımlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [Interpolation](../../com.aspose.threed/interpolation) | Yeni değer |

### setNextInTangent(Vector2 value) {#setNextInTangent-com.aspose.threed.Vector2-}
```
public void setNextInTangent(Vector2 value)
```


Bu anahtar çerçevede bir sonraki giriş (sol) teğetini ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [Vector2](../../com.aspose.threed/vector2) | Yeni değer |

### setNextInWeight(float value) {#setNextInWeight-float-}
```
public void setNextInWeight(float value)
```


Bu anahtar çerçevede bir sonraki giriş (sol) ağırlığını ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | float | Yeni değer |

### setOutTangent(Vector2 value) {#setOutTangent-com.aspose.threed.Vector2-}
```
public void setOutTangent(Vector2 value)
```


Bu anahtar çerçevede dış (sağ) teğeti ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [Vector2](../../com.aspose.threed/vector2) | Yeni değer |

### setOutWeight(float value) {#setOutWeight-float-}
```
public void setOutWeight(float value)
```


Bu anahtar çerçevede dış (sağ) ağırlığı ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | float | Yeni değer |

### setStepMode(StepMode value) {#setStepMode-com.aspose.threed.StepMode-}
```
public void setStepMode(StepMode value)
```


Anahtarın adım modunu ayarlar. Eğer ara değerleme türü [Interpolation.CONSTANT](../../com.aspose.threed/interpolation\#CONSTANT) ise, list.data[index] ara değerleme sırasında hangi anahtar çerçevenin değerinin kullanılacağını belirler. Bir [StepMode.PREVIOUS\_VALUE](../../com.aspose.threed/stepmode\#PREVIOUS-VALUE) sol anahtar çerçevenin değerinin kullanılacağı anlamına gelir. Bir [StepMode.NEXT\_VALUE](../../com.aspose.threed/stepmode\#NEXT-VALUE) ise sağdaki bir sonraki anahtar çerçevenin değerinin kullanılacağı anlamına gelir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [StepMode](../../com.aspose.threed/stepmode) | Yeni değer |

### setTangentWeightMode(int value) {#setTangentWeightMode-int-}
```
public void setTangentWeightMode(int value)
```


Anahtarın teğet ağırlık modunu ayarlar. Çıkış teğeti veya bir sonraki giriş teğeti, doğru [WeightedMode](../../com.aspose.threed/weightedmode) seçilerek özelleştirilebilir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int | Yeni değer |

### setTension(float value) {#setTension-float-}
```
public void setTension(float value)
```


TCB spline içinde kullanılan gerilimi ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | float | Yeni değer |

### setTime(double value) {#setTime-double-}
```
public void setTime(double value)
```


list.data[index] anahtar çerçevesinin zaman konumunu, saniye cinsinden ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | double | Yeni değer |

### setTimeIndependentTangent(boolean value) {#setTimeIndependentTangent-boolean-}
```
public void setTimeIndependentTangent(boolean value)
```


Teğetin zaman bağımsız olduğunu ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean | Yeni değer |

### setValue(float value) {#setValue-float-}
```
public void setValue(float value)
```


Anahtar çerçevenin değerini ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | float | Yeni değer |

### toString() {#toString--}
```
public String toString()
```


Anahtar çerçevenin dize temsilini alır.

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
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |


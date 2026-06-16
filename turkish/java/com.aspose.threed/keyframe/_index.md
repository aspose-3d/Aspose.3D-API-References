---
title: "KeyFrame"
second_title: "Aspose.3D for Java API Referansı"
description: "Bir anahtar kare, temel olarak bir zaman ve bir değer ile tanımlanır; bazı ara değerleme türleri için teğet/gerginlik/eğilim/süreklilik de son örneklenmiş değerin hesaplanmasında kullanılır."
type: docs
weight: 89
url: /tr/java/com.aspose.threed/keyframe/
---

**Inheritance:**
java.lang.Object
```
public class KeyFrame
```

Bir anahtar kare, temel olarak bir zaman ve bir değer ile tanımlanır; bazı ara değerleme türleri için teğet/gerginlik/eğilim/süreklilik de son örneklenmiş değerin hesaplanmasında kullanılır. Anahtar kare olmayan bir zaman konumundaki örneklenmiş değerler, önceki ve sonraki anahtar kareler arasındaki anahtar kareler tarafından ara değerlenir. İlk/son anahtar karenin öncesi/sonrası değerler, [Extrapolation](../../com.aspose.threed/extrapolation) sınıfı tarafından hesaplanır.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [KeyFrame(KeyframeSequence curve, double time)](#KeyFrame-com.aspose.threed.KeyframeSequence-double-) | Belirtilen eğri üzerinde yeni bir anahtar kare oluştur. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBias()](#getBias--) | TCB spline'ında kullanılan bias'ı alır. |
| [getClass()](#getClass--) |  |
| [getContinuity()](#getContinuity--) | TCB spline'ında kullanılan continuity'yi alır. |
| [getFlat()](#getFlat--) | Anahtar karenin düz olup olmadığını al veya ayarla. |
| [getIndependentTangent()](#getIndependentTangent--) | Çıkış ve bir sonraki giriş teğetlerinin bağımsız olup olmadığını alır. |
| [getInterpolation()](#getInterpolation--) | Anahtarın ara değerleme tipini alır, list.data[index] örneklenmiş değerin nasıl hesaplandığını belirleyen algoritmayı tanımlar. |
| [getNextInTangent()](#getNextInTangent--) | Bu anahtar karede bir sonraki giriş (sol) teğetini alır. |
| [getNextInWeight()](#getNextInWeight--) | Bu anahtar karede bir sonraki giriş (sol) ağırlığını alır. |
| [getOutTangent()](#getOutTangent--) | Bu anahtar karede çıkış (sağ) teğetini alır. |
| [getOutWeight()](#getOutWeight--) | Bu anahtar karede çıkış (sağ) ağırlığını alır. |
| [getStepMode()](#getStepMode--) | Anahtarın adım modunu alır. |
| [getTangentWeightMode()](#getTangentWeightMode--) | Anahtarın teğet ağırlık modunu alır. |
| [getTension()](#getTension--) | TCB spline'ında kullanılan tension'ı alır. |
| [getTime()](#getTime--) | list.data[index] anahtar karenin zaman konumunu, saniye cinsinden alır. |
| [getTimeIndependentTangent()](#getTimeIndependentTangent--) | Teğetin zaman bağımsız olup olmadığını alır. |
| [getValue()](#getValue--) | Anahtar karenin değerini alır. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setBias(float value)](#setBias-float-) | TCB spline'ında kullanılan bias'ı ayarlar. |
| [setContinuity(float value)](#setContinuity-float-) | TCB spline'ında kullanılan continuity'yi ayarlar. |
| [setFlat(boolean value)](#setFlat-boolean-) | Anahtar karenin düz olup olmadığını al veya ayarla. |
| [setIndependentTangent(boolean value)](#setIndependentTangent-boolean-) | Çıkış ve bir sonraki giriş teğetlerinin bağımsız olduğunu ayarlar. |
| [setInterpolation(Interpolation value)](#setInterpolation-com.aspose.threed.Interpolation-) | Anahtarın ara değerleme tipini ayarlar, list.data[index] örneklenen değerin nasıl hesaplandığını tanımlayan algoritmayı belirler. |
| [setNextInTangent(Vector2 value)](#setNextInTangent-com.aspose.threed.Vector2-) | Bu anahtar karede bir sonraki giriş (sol) teğetini ayarlar. |
| [setNextInWeight(float value)](#setNextInWeight-float-) | Bu anahtar karede bir sonraki giriş (sol) ağırlığını ayarlar. |
| [setOutTangent(Vector2 value)](#setOutTangent-com.aspose.threed.Vector2-) | Bu anahtar karede çıkış (sağ) teğetini ayarlar. |
| [setOutWeight(float value)](#setOutWeight-float-) | Bu anahtar karede çıkış (sağ) ağırlığını ayarlar. |
| [setStepMode(StepMode value)](#setStepMode-com.aspose.threed.StepMode-) | Anahtarın adım modunu ayarlar. |
| [setTangentWeightMode(int value)](#setTangentWeightMode-int-) | Anahtarın teğet ağırlık modunu ayarlar. |
| [setTension(float value)](#setTension-float-) | TCB spline'ında kullanılan gerilimi ayarlar |
| [setTime(double value)](#setTime-double-) | list.data[index] anahtar karesinin zaman konumunu saniye cinsinden ayarlar. |
| [setTimeIndependentTangent(boolean value)](#setTimeIndependentTangent-boolean-) | Teğetin zaman bağımsız olduğunu ayarlar |
| [setValue(float value)](#setValue-float-) | Anahtar karenin değerini ayarlar. |
| [toString()](#toString--) | Anahtar karenin dize temsilini alır |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### KeyFrame(KeyframeSequence curve, double time) {#KeyFrame-com.aspose.threed.KeyframeSequence-double-}
```
public KeyFrame(KeyframeSequence curve, double time)
```


Belirtilen eğri üzerinde yeni bir anahtar kare oluştur.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| curve | [KeyframeSequence](../../com.aspose.threed/keyframesequence) | Anahtar karenin oluşturulacağı eğri |
| zaman | double | Anahtar karenin zaman konumu |

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


TCB spline'ında kullanılan bias'ı alır.

**Returns:**
float - TCB spline'ında kullanılan önyargı
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


TCB spline'ında kullanılan continuity'yi alır.

**Returns:**
float - TCB spline'ında kullanılan süreklilik
### getFlat() {#getFlat--}
```
public boolean getFlat()
```


Anahtar karenin düz olup olmadığını al veya ayarla. Anahtar kare, bir sonraki veya önceki anahtar kare aynı değere sahipse düz olmalıdır. Düz anahtar kare düz teğetlere ve sabit ara değerlemeye sahiptir.

**Returns:**
boolean - Anahtar karenin düz olup olmadığını al veya ayarla. Anahtar kare, bir sonraki veya önceki anahtar kare aynı değere sahipse düz olmalıdır. Düz anahtar kare düz teğetlere ve sabit ara değerlemeye sahiptir.
### getIndependentTangent() {#getIndependentTangent--}
```
public boolean getIndependentTangent()
```


Çıkış ve bir sonraki giriş teğetlerinin bağımsız olup olmadığını alır.

**Returns:**
boolean - çıkış ve bir sonraki giriş teğetleri bağımsızdır.
### getInterpolation() {#getInterpolation--}
```
public Interpolation getInterpolation()
```


Anahtarın ara değerleme tipini alır, list.data[index] örneklenmiş değerin nasıl hesaplandığını belirleyen algoritmayı tanımlar.

**Returns:**
[Interpolation](../../com.aspose.threed/interpolation) - the key's interpolation type, list.data[index] defines the algorithm how the sampled value is calculated.
### getNextInTangent() {#getNextInTangent--}
```
public Vector2 getNextInTangent()
```


Bu anahtar karede bir sonraki giriş (sol) teğetini alır.

**Returns:**
[Vector2](../../com.aspose.threed/vector2) - the next in(left) tangent on this key frame.
### getNextInWeight() {#getNextInWeight--}
```
public float getNextInWeight()
```


Bu anahtar karede bir sonraki giriş (sol) ağırlığını alır.

**Returns:**
float - bu anahtar karede bir sonraki giriş (sol) ağırlığı.
### getOutTangent() {#getOutTangent--}
```
public Vector2 getOutTangent()
```


Bu anahtar karede çıkış (sağ) teğetini alır.

**Returns:**
[Vector2](../../com.aspose.threed/vector2) - the out(right) tangent on this key frame.
### getOutWeight() {#getOutWeight--}
```
public float getOutWeight()
```


Bu anahtar karede çıkış (sağ) ağırlığını alır.

**Returns:**
float - bu anahtar karede çıkış (sağ) ağırlığı.
### getStepMode() {#getStepMode--}
```
public StepMode getStepMode()
```


Anahtarın adım modunu alır. Eğer ara değerleme tipi [Interpolation.CONSTANT](../../com.aspose.threed/interpolation\#CONSTANT) ise, list.data[index] ara değerleme sırasında hangi anahtar kare değerinin kullanılacağını belirler. Bir [StepMode.PREVIOUS\_VALUE](../../com.aspose.threed/stepmode\#PREVIOUS-VALUE) sol anahtar karenin değerinin kullanılacağı anlamına gelir. Bir [StepMode.NEXT\_VALUE](../../com.aspose.threed/stepmode\#NEXT-VALUE) ise bir sonraki sağ anahtar karenin değerinin kullanılacağı anlamına gelir.

**Returns:**
[StepMode](../../com.aspose.threed/stepmode) - the key's step mode. If the interpolation type is [Interpolation.CONSTANT](../../com.aspose.threed/interpolation\#CONSTANT), list.data[index] decides which key-frame's value will be used during interpolation. A [StepMode.PREVIOUS\_VALUE](../../com.aspose.threed/stepmode\#PREVIOUS-VALUE) means the left key-frame's value will be used A [StepMode.NEXT\_VALUE](../../com.aspose.threed/stepmode\#NEXT-VALUE) means the next right key-frame's value will be used
### getTangentWeightMode() {#getTangentWeightMode--}
```
public int getTangentWeightMode()
```


Anahtarın teğet ağırlık modunu alır. Çıkış teğeti veya bir sonraki giriş teğeti, doğru [WeightedMode](../../com.aspose.threed/weightedmode) seçilerek özelleştirilebilir.

**Returns:**
int - anahtarın teğet ağırlık modu. Çıkış teğeti veya bir sonraki giriş teğeti, doğru [WeightedMode](../../com.aspose.threed/weightedmode) seçilerek özelleştirilebilir.
### getTension() {#getTension--}
```
public float getTension()
```


TCB spline'ında kullanılan tension'ı alır.

**Returns:**
float - TCB spline'ında kullanılan gerilim
### getTime() {#getTime--}
```
public double getTime()
```


list.data[index] anahtar karenin zaman konumunu, saniye cinsinden alır.

**Returns:**
double - list.data[index] anahtar çerçevesinin zaman konumu, saniye cinsinden ölçülür.
### getTimeIndependentTangent() {#getTimeIndependentTangent--}
```
public boolean getTimeIndependentTangent()
```


Teğetin zaman bağımsız olup olmadığını alır.

**Returns:**
boolean - teğet zaman bağımsızdır
### getValue() {#getValue--}
```
public float getValue()
```


Anahtar karenin değerini alır.

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


TCB spline'ında kullanılan bias'ı ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | float | Yeni değer |

### setContinuity(float value) {#setContinuity-float-}
```
public void setContinuity(float value)
```


TCB spline'ında kullanılan continuity'yi ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | float | Yeni değer |

### setFlat(boolean value) {#setFlat-boolean-}
```
public void setFlat(boolean value)
```


Anahtar karenin düz olup olmadığını al veya ayarla. Anahtar kare, bir sonraki veya önceki anahtar kare aynı değere sahipse düz olmalıdır. Düz anahtar kare düz teğetlere ve sabit ara değerlemeye sahiptir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean | Yeni değer |

### setIndependentTangent(boolean value) {#setIndependentTangent-boolean-}
```
public void setIndependentTangent(boolean value)
```


Çıkış ve bir sonraki giriş teğetlerinin bağımsız olduğunu ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean | Yeni değer |

### setInterpolation(Interpolation value) {#setInterpolation-com.aspose.threed.Interpolation-}
```
public void setInterpolation(Interpolation value)
```


Anahtarın ara değerleme tipini ayarlar, list.data[index] örneklenen değerin nasıl hesaplandığını tanımlayan algoritmayı belirler.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [Interpolation](../../com.aspose.threed/interpolation) | Yeni değer |

### setNextInTangent(Vector2 value) {#setNextInTangent-com.aspose.threed.Vector2-}
```
public void setNextInTangent(Vector2 value)
```


Bu anahtar karede bir sonraki giriş (sol) teğetini ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [Vector2](../../com.aspose.threed/vector2) | Yeni değer |

### setNextInWeight(float value) {#setNextInWeight-float-}
```
public void setNextInWeight(float value)
```


Bu anahtar karede bir sonraki giriş (sol) ağırlığını ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | float | Yeni değer |

### setOutTangent(Vector2 value) {#setOutTangent-com.aspose.threed.Vector2-}
```
public void setOutTangent(Vector2 value)
```


Bu anahtar karede çıkış (sağ) teğetini ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [Vector2](../../com.aspose.threed/vector2) | Yeni değer |

### setOutWeight(float value) {#setOutWeight-float-}
```
public void setOutWeight(float value)
```


Bu anahtar karede çıkış (sağ) ağırlığını ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | float | Yeni değer |

### setStepMode(StepMode value) {#setStepMode-com.aspose.threed.StepMode-}
```
public void setStepMode(StepMode value)
```


Anahtarın adım modunu ayarlar. Eğer enterpolasyon türü [Interpolation.CONSTANT](../../com.aspose.threed/interpolation\#CONSTANT) ise, list.data[index] hangi anahtar çerçevenin değerinin enterpolasyon sırasında kullanılacağını belirler. Bir [StepMode.PREVIOUS\_VALUE](../../com.aspose.threed/stepmode\#PREVIOUS-VALUE) sol anahtar çerçevenin değerinin kullanılacağı anlamına gelir. Bir [StepMode.NEXT\_VALUE](../../com.aspose.threed/stepmode\#NEXT-VALUE) ise sonraki sağ anahtar çerçevenin değerinin kullanılacağı anlamına gelir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [StepMode](../../com.aspose.threed/stepmode) | Yeni değer |

### setTangentWeightMode(int value) {#setTangentWeightMode-int-}
```
public void setTangentWeightMode(int value)
```


Anahtarın teğet ağırlık modunu ayarlar. Çıkış teğeti veya sonraki giriş teğeti, doğru [WeightedMode](../../com.aspose.threed/weightedmode) seçilerek özelleştirilebilir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int | Yeni değer |

### setTension(float value) {#setTension-float-}
```
public void setTension(float value)
```


TCB spline'ında kullanılan gerilimi ayarlar

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | float | Yeni değer |

### setTime(double value) {#setTime-double-}
```
public void setTime(double value)
```


list.data[index] anahtar karesinin zaman konumunu saniye cinsinden ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | double | Yeni değer |

### setTimeIndependentTangent(boolean value) {#setTimeIndependentTangent-boolean-}
```
public void setTimeIndependentTangent(boolean value)
```


Teğetin zaman bağımsız olduğunu ayarlar

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean | Yeni değer |

### setValue(float value) {#setValue-float-}
```
public void setValue(float value)
```


Anahtar karenin değerini ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | float | Yeni değer |

### toString() {#toString--}
```
public String toString()
```


Anahtar karenin dize temsilini alır

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


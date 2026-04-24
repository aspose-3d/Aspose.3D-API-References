---
title: KeyFrame
second_title: Referensi API Aspose.3D untuk Java
description: Sebuah key frame terutama didefinisikan oleh waktu dan nilai; untuk beberapa tipe interpolasi, tangent/tension/bias/continuity juga digunakan dalam menghitung nilai sampel akhir.
type: docs
weight: 89
url: /id/java/com.aspose.threed/keyframe/
---

**Inheritance:**
java.lang.Object
```
public class KeyFrame
```

Sebuah key frame terutama didefinisikan oleh waktu dan nilai; untuk beberapa tipe interpolasi, tangent/tension/bias/continuity juga digunakan dalam menghitung nilai sampel akhir. Nilai yang disampel pada posisi waktu yang bukan key-frame diinterpolasi oleh key-frame antara key-frame sebelumnya dan berikutnya. Nilai sebelum/setelah key-frame pertama/terakhir dihitung oleh kelas [Extrapolation](../../com.aspose.threed/extrapolation).
## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [KeyFrame(KeyframeSequence curve, double time)](#KeyFrame-com.aspose.threed.KeyframeSequence-double-) | Buat key frame baru pada kurva yang ditentukan |
## Metode

| Metode | Deskripsi |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBias()](#getBias--) | Mendapatkan bias yang digunakan dalam spline TCB |
| [getClass()](#getClass--) |  |
| [getContinuity()](#getContinuity--) | Mendapatkan kontinuitas yang digunakan dalam spline TCB |
| [getFlat()](#getFlat--) | Dapatkan atau atur apakah key frame datar. |
| [getIndependentTangent()](#getIndependentTangent--) | Mendapatkan bahwa out dan next in tangents independen. |
| [getInterpolation()](#getInterpolation--) | Mendapatkan tipe interpolasi key, list.data[index] menentukan algoritma bagaimana nilai sampel dihitung. |
| [getNextInTangent()](#getNextInTangent--) | Mendapatkan tangent in (kiri) berikutnya pada key frame ini. |
| [getNextInWeight()](#getNextInWeight--) | Mendapatkan bobot in (kiri) berikutnya pada key frame ini. |
| [getOutTangent()](#getOutTangent--) | Mendapatkan tangent out (kanan) pada key frame ini. |
| [getOutWeight()](#getOutWeight--) | Mendapatkan bobot out (kanan) pada key frame ini. |
| [getStepMode()](#getStepMode--) | Mendapatkan mode langkah key. |
| [getTangentWeightMode()](#getTangentWeightMode--) | Mendapatkan mode bobot tangent key. |
| [getTension()](#getTension--) | Mendapatkan tension yang digunakan dalam spline TCB |
| [getTime()](#getTime--) | Mendapatkan posisi waktu key frame list.data[index], diukur dalam detik. |
| [getTimeIndependentTangent()](#getTimeIndependentTangent--) | Mendapatkan bahwa tangent tidak bergantung pada waktu |
| [getValue()](#getValue--) | Mendapatkan nilai key-frame. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setBias(float value)](#setBias-float-) | Mengatur bias yang digunakan dalam spline TCB |
| [setContinuity(float value)](#setContinuity-float-) | Mengatur kontinuitas yang digunakan dalam spline TCB |
| [setFlat(boolean value)](#setFlat-boolean-) | Dapatkan atau atur apakah key frame datar. |
| [setIndependentTangent(boolean value)](#setIndependentTangent-boolean-) | Mengatur out dan next in tangents menjadi independen. |
| [setInterpolation(Interpolation value)](#setInterpolation-com.aspose.threed.Interpolation-) | Mengatur tipe interpolasi key, list.data[index] menentukan algoritma bagaimana nilai yang di-sample dihitung. |
| [setNextInTangent(Vector2 value)](#setNextInTangent-com.aspose.threed.Vector2-) | Mengatur next in (kiri) tangent pada key frame ini. |
| [setNextInWeight(float value)](#setNextInWeight-float-) | Mengatur next in (kiri) weight pada key frame ini. |
| [setOutTangent(Vector2 value)](#setOutTangent-com.aspose.threed.Vector2-) | Mengatur out (kanan) tangent pada key frame ini. |
| [setOutWeight(float value)](#setOutWeight-float-) | Mengatur out (kanan) weight pada key frame ini. |
| [setStepMode(StepMode value)](#setStepMode-com.aspose.threed.StepMode-) | Mengatur step mode key. |
| [setTangentWeightMode(int value)](#setTangentWeightMode-int-) | Mengatur mode berat tangent key. |
| [setTension(float value)](#setTension-float-) | Mengatur tension yang digunakan dalam TCB spline |
| [setTime(double value)](#setTime-double-) | Mengatur posisi waktu key frame list.data[index], diukur dalam detik. |
| [setTimeIndependentTangent(boolean value)](#setTimeIndependentTangent-boolean-) | Mengatur tangent menjadi time-independent |
| [setValue(float value)](#setValue-float-) | Mengatur nilai key-frame. |
| [toString()](#toString--) | Mendapatkan representasi string dari key frame |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### KeyFrame(KeyframeSequence curve, double time) {#KeyFrame-com.aspose.threed.KeyframeSequence-double-}
```
public KeyFrame(KeyframeSequence curve, double time)
```


Buat key frame baru pada kurva yang ditentukan

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| curve | [KeyframeSequence](../../com.aspose.threed/keyframesequence) | Kurva tempat key frame akan dibuat |
| waktu | double | Posisi waktu key frame |

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getBias() {#getBias--}
```
public float getBias()
```


Mendapatkan bias yang digunakan dalam spline TCB

**Returns:**
float - bias yang digunakan dalam TCB spline
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


Mendapatkan kontinuitas yang digunakan dalam spline TCB

**Returns:**
float - continuity yang digunakan dalam TCB spline
### getFlat() {#getFlat--}
```
public boolean getFlat()
```


Dapatkan atau atur apakah key frame datar. Key frame harus datar jika next atau previous key frame memiliki nilai yang sama. Key frame datar memiliki tangents datar dan interpolasi tetap.

**Returns:**
boolean - Dapatkan atau atur apakah key frame datar. Key frame harus datar jika next atau previous key frame memiliki nilai yang sama. Key frame datar memiliki tangents datar dan interpolasi tetap.
### getIndependentTangent() {#getIndependentTangent--}
```
public boolean getIndependentTangent()
```


Mendapatkan bahwa out dan next in tangents independen.

**Returns:**
boolean - out dan next in tangents independen.
### getInterpolation() {#getInterpolation--}
```
public Interpolation getInterpolation()
```


Mendapatkan tipe interpolasi key, list.data[index] menentukan algoritma bagaimana nilai sampel dihitung.

**Returns:**
[Interpolation](../../com.aspose.threed/interpolation) - the key's interpolation type, list.data[index] defines the algorithm how the sampled value is calculated.
### getNextInTangent() {#getNextInTangent--}
```
public Vector2 getNextInTangent()
```


Mendapatkan tangent in (kiri) berikutnya pada key frame ini.

**Returns:**
[Vector2](../../com.aspose.threed/vector2) - the next in(left) tangent on this key frame.
### getNextInWeight() {#getNextInWeight--}
```
public float getNextInWeight()
```


Mendapatkan bobot in (kiri) berikutnya pada key frame ini.

**Returns:**
float - next in (kiri) weight pada key frame ini.
### getOutTangent() {#getOutTangent--}
```
public Vector2 getOutTangent()
```


Mendapatkan tangent out (kanan) pada key frame ini.

**Returns:**
[Vector2](../../com.aspose.threed/vector2) - the out(right) tangent on this key frame.
### getOutWeight() {#getOutWeight--}
```
public float getOutWeight()
```


Mendapatkan bobot out (kanan) pada key frame ini.

**Returns:**
float - out (kanan) weight pada key frame ini.
### getStepMode() {#getStepMode--}
```
public StepMode getStepMode()
```


Mendapatkan step mode key. Jika tipe interpolasi adalah [Interpolation.CONSTANT](../../com.aspose.threed/interpolation\#CONSTANT), list.data[index] menentukan nilai key-frame mana yang akan digunakan selama interpolasi. Sebuah [StepMode.PREVIOUS\_VALUE](../../com.aspose.threed/stepmode\#PREVIOUS-VALUE) berarti nilai key-frame kiri yang akan digunakan. Sebuah [StepMode.NEXT\_VALUE](../../com.aspose.threed/stepmode\#NEXT-VALUE) berarti nilai key-frame kanan berikutnya yang akan digunakan

**Returns:**
[StepMode](../../com.aspose.threed/stepmode) - the key's step mode. If the interpolation type is [Interpolation.CONSTANT](../../com.aspose.threed/interpolation\#CONSTANT), list.data[index] decides which key-frame's value will be used during interpolation. A [StepMode.PREVIOUS\_VALUE](../../com.aspose.threed/stepmode\#PREVIOUS-VALUE) means the left key-frame's value will be used A [StepMode.NEXT\_VALUE](../../com.aspose.threed/stepmode\#NEXT-VALUE) means the next right key-frame's value will be used
### getTangentWeightMode() {#getTangentWeightMode--}
```
public int getTangentWeightMode()
```


Mendapatkan mode berat tangent key. Out tangent atau next in tangent dapat disesuaikan dengan memilih [WeightedMode](../../com.aspose.threed/weightedmode) yang tepat

**Returns:**
int - mode berat tangent key. Out tangent atau next in tangent dapat disesuaikan dengan memilih [WeightedMode](../../com.aspose.threed/weightedmode) yang tepat
### getTension() {#getTension--}
```
public float getTension()
```


Mendapatkan tension yang digunakan dalam spline TCB

**Returns:**
float - ketegangan yang digunakan dalam spline TCB
### getTime() {#getTime--}
```
public double getTime()
```


Mendapatkan posisi waktu key frame list.data[index], diukur dalam detik.

**Returns:**
double - posisi waktu dari key frame list.data[index], diukur dalam detik.
### getTimeIndependentTangent() {#getTimeIndependentTangent--}
```
public boolean getTimeIndependentTangent()
```


Mendapatkan bahwa tangent tidak bergantung pada waktu

**Returns:**
boolean - tangent tidak bergantung pada waktu
### getValue() {#getValue--}
```
public float getValue()
```


Mendapatkan nilai key-frame.

**Returns:**
float - nilai key-frame.
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


Mengatur bias yang digunakan dalam spline TCB

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | float | Nilai baru |

### setContinuity(float value) {#setContinuity-float-}
```
public void setContinuity(float value)
```


Mengatur kontinuitas yang digunakan dalam spline TCB

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | float | Nilai baru |

### setFlat(boolean value) {#setFlat-boolean-}
```
public void setFlat(boolean value)
```


Dapatkan atau atur apakah key frame datar. Key frame harus datar jika next atau previous key frame memiliki nilai yang sama. Key frame datar memiliki tangents datar dan interpolasi tetap.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | boolean | Nilai baru |

### setIndependentTangent(boolean value) {#setIndependentTangent-boolean-}
```
public void setIndependentTangent(boolean value)
```


Mengatur out dan next in tangents menjadi independen.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | boolean | Nilai baru |

### setInterpolation(Interpolation value) {#setInterpolation-com.aspose.threed.Interpolation-}
```
public void setInterpolation(Interpolation value)
```


Mengatur tipe interpolasi key, list.data[index] menentukan algoritma bagaimana nilai yang di-sample dihitung.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [Interpolation](../../com.aspose.threed/interpolation) | Nilai baru |

### setNextInTangent(Vector2 value) {#setNextInTangent-com.aspose.threed.Vector2-}
```
public void setNextInTangent(Vector2 value)
```


Mengatur next in (kiri) tangent pada key frame ini.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [Vector2](../../com.aspose.threed/vector2) | Nilai baru |

### setNextInWeight(float value) {#setNextInWeight-float-}
```
public void setNextInWeight(float value)
```


Mengatur next in (kiri) weight pada key frame ini.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | float | Nilai baru |

### setOutTangent(Vector2 value) {#setOutTangent-com.aspose.threed.Vector2-}
```
public void setOutTangent(Vector2 value)
```


Mengatur out (kanan) tangent pada key frame ini.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [Vector2](../../com.aspose.threed/vector2) | Nilai baru |

### setOutWeight(float value) {#setOutWeight-float-}
```
public void setOutWeight(float value)
```


Mengatur out (kanan) weight pada key frame ini.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | float | Nilai baru |

### setStepMode(StepMode value) {#setStepMode-com.aspose.threed.StepMode-}
```
public void setStepMode(StepMode value)
```


Mengatur mode langkah kunci. Jika tipe interpolasi adalah [Interpolation.CONSTANT](../../com.aspose.threed/interpolation\#CONSTANT), list.data[index] menentukan nilai key-frame mana yang akan digunakan selama interpolasi. Sebuah [StepMode.PREVIOUS\_VALUE](../../com.aspose.threed/stepmode\#PREVIOUS-VALUE) berarti nilai key-frame kiri yang akan digunakan. Sebuah [StepMode.NEXT\_VALUE](../../com.aspose.threed/stepmode\#NEXT-VALUE) berarti nilai key-frame kanan berikutnya yang akan digunakan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [StepMode](../../com.aspose.threed/stepmode) | Nilai baru |

### setTangentWeightMode(int value) {#setTangentWeightMode-int-}
```
public void setTangentWeightMode(int value)
```


Mengatur mode bobot tangent kunci. Out tangent atau in tangent berikutnya dapat disesuaikan dengan memilih [WeightedMode](../../com.aspose.threed/weightedmode)

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int | Nilai baru |

### setTension(float value) {#setTension-float-}
```
public void setTension(float value)
```


Mengatur tension yang digunakan dalam TCB spline

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | float | Nilai baru |

### setTime(double value) {#setTime-double-}
```
public void setTime(double value)
```


Mengatur posisi waktu key frame list.data[index], diukur dalam detik.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | double | Nilai baru |

### setTimeIndependentTangent(boolean value) {#setTimeIndependentTangent-boolean-}
```
public void setTimeIndependentTangent(boolean value)
```


Mengatur tangent menjadi time-independent

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | boolean | Nilai baru |

### setValue(float value) {#setValue-float-}
```
public void setValue(float value)
```


Mengatur nilai key-frame.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | float | Nilai baru |

### toString() {#toString--}
```
public String toString()
```


Mendapatkan representasi string dari key frame

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
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |


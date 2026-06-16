---
title: "Quaternion"
second_title: "Aspose.3D for Java API Referansı"
description: "Quaternion genellikle bilgisayar grafiklerinde dönüşüm gerçekleştirmek için kullanılır."
type: docs
weight: 143
url: /tr/java/com.aspose.threed/quaternion/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.threed.Struct, java.io.Serializable
```
public final class Quaternion implements Struct<Quaternion>, Serializable
```

Quaternion genellikle bilgisayar grafiklerinde dönüşüm gerçekleştirmek için kullanılır.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [Quaternion(double w, double x, double y, double z)](#Quaternion-double-double-double-double-) | Yeni bir [Quaternion](../../com.aspose.threed/quaternion) sınıfının örneğini başlatır. |
| [Quaternion()](#Quaternion--) |  |
## Alanlar

| Alan | Açıklama |
| --- | --- |
| [IDENTITY](#IDENTITY) | Kimlik quaternion'ı. |
| [w](#w) | w bileşeni. |
| [x](#x) | x bileşeni. |
| [y](#y) | y bileşeni. |
| [z](#z) | z bileşeni. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [add(Quaternion lhs, Quaternion rhs)](#add-com.aspose.threed.Quaternion-com.aspose.threed.Quaternion-) | + operatörü için aşırı yükleme |
| [clone()](#clone--) |  |
| [concat(Quaternion rhs)](#concat-com.aspose.threed.Quaternion-) | İki quaternion'ı birleştir. |
| [conjugate()](#conjugate--) | Mevcut quaternion'ın eşleniğini döndürür. |
| [copyFrom(Quaternion src)](#copyFrom-com.aspose.threed.Quaternion-) |  |
| [div(Quaternion lhs, double rhs)](#div-com.aspose.threed.Quaternion-double-) | / operatörü için aşırı yükleme |
| [dot(Quaternion q)](#dot-com.aspose.threed.Quaternion-) | Nokta çarpımı. |
| [equals(Object obj)](#equals-java.lang.Object-) | İki quaternion'ın eşit olup olmadığını kontrol et. |
| [eulerAngles()](#eulerAngles--) | Quaternion'ı Euler açılarıyla temsil edilen rotasyona dönüştürür. Tüm bileşenler radyan cinsindendir. |
| [fromAngleAxis(double a, Vector3 axis)](#fromAngleAxis-double-com.aspose.threed.Vector3-) | Verilen eksen etrafında bir quaternion oluşturur ve saat yönünde döndürür. |
| [fromEulerAngle(Vector3 eulerAngle)](#fromEulerAngle-com.aspose.threed.Vector3-) | Verilen Euler açısından quaternion oluşturur. |
| [fromEulerAngle(double pitch, double yaw, double roll)](#fromEulerAngle-double-double-double-) | Verilen Euler açısından quaternion oluşturur. |
| [fromRotation(Vector3 orig, Vector3 dest)](#fromRotation-com.aspose.threed.Vector3-com.aspose.threed.Vector3-) | Orijinal yönünden hedef yönüne dönen bir quaternion oluşturur. |
| [getClass()](#getClass--) |  |
| [getLength()](#getLength--) | Quaternion'ın uzunluğunu alır. |
| [hashCode()](#hashCode--) | Quaternion'ın karma kodunu alır. |
| [interpolate(float t, Quaternion from, Quaternion to)](#interpolate-float-com.aspose.threed.Quaternion-com.aspose.threed.Quaternion-) | Bu quaternion'ı, verilen quaternion argümanları arasında, from ve to arasında bir t değeri için ara değerle doldurur. |
| [inverse()](#inverse--) | Mevcut quaternion'ın tersini döndürür. |
| [mul(Quaternion lhs, Quaternion rhs)](#mul-com.aspose.threed.Quaternion-com.aspose.threed.Quaternion-) | \* operatörü için aşırı yükleme |
| [mul(Quaternion q, Vector3 v)](#mul-com.aspose.threed.Quaternion-com.aspose.threed.Vector3-) | \* operatörü için aşırı yükleme |
| [mul(Quaternion q, Vector4 v)](#mul-com.aspose.threed.Quaternion-com.aspose.threed.Vector4-) | \* operatörü için aşırı yükleme |
| [mul(Quaternion lhs, double rhs)](#mul-com.aspose.threed.Quaternion-double-) | \* operatörü için aşırı yükleme |
| [mul(Vector3 v, Quaternion q)](#mul-com.aspose.threed.Vector3-com.aspose.threed.Quaternion-) | \* operatörü için aşırı yükleme |
| [normalize()](#normalize--) | Quaternion'ı normalleştir. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [op_eq(Quaternion lhs, Quaternion rhs)](#op-eq-com.aspose.threed.Quaternion-com.aspose.threed.Quaternion-) | Quaternion için eşitlik operatörü. |
| [op_ne(Quaternion lhs, Quaternion rhs)](#op-ne-com.aspose.threed.Quaternion-com.aspose.threed.Quaternion-) | Quaternion için eşitsizlik operatörü. |
| [slerp(double t, Quaternion v1, Quaternion v2)](#slerp-double-com.aspose.threed.Quaternion-com.aspose.threed.Quaternion-) | İki değer arasında küresel doğrusal ara değerleme (slerp) gerçekleştir. |
| [toAngleAxis(double[] angle, Vector3 axis)](#toAngleAxis-double---com.aspose.threed.Vector3-) | Quaternion'ı açı ve eksene ayır. |
| [toMatrix()](#toMatrix--) | Quaternion tarafından sunulan rotasyonu dönüşüm matrisine çevir. |
| [toMatrix(Vector3 translation)](#toMatrix-com.aspose.threed.Vector3-) | Quaternion tarafından sunulan rotasyonu dönüşüm matrisine çevir. |
| [toString()](#toString--) | Quaternion'ın dizedeki temsilini alır. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Quaternion(double w, double x, double y, double z) {#Quaternion-double-double-double-double-}
```
public Quaternion(double w, double x, double y, double z)
```


Yeni bir [Quaternion](../../com.aspose.threed/quaternion) sınıfının örneğini başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| w | double | kuaternionun w bileşeni |
| x | double | kuaternionun x bileşeni |
| y | double | kuaternionun y bileşeni |
| z | double | kuaternionun z bileşeni |

### Quaternion() {#Quaternion--}
```
public Quaternion()
```


### IDENTITY {#IDENTITY}
```
public static final Quaternion IDENTITY
```


Kimlik quaternion'ı.

### w {#w}
```
public double w
```


w bileşeni.

### x {#x}
```
public double x
```


x bileşeni.

### y {#y}
```
public double y
```


y bileşeni.

### z {#z}
```
public double z
```


z bileşeni.

### add(Quaternion lhs, Quaternion rhs) {#add-com.aspose.threed.Quaternion-com.aspose.threed.Quaternion-}
```
public static Quaternion add(Quaternion lhs, Quaternion rhs)
```


+ operatörü için aşırı yükleme

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| lhs | [Quaternion](../../com.aspose.threed/quaternion) | Sol kuaternion |
| rhs | [Quaternion](../../com.aspose.threed/quaternion) | Sağ kuaternion |

**Returns:**
[Quaternion](../../com.aspose.threed/quaternion) - Result quaternion
### clone() {#clone--}
```
public Quaternion clone()
```


Mevcut örneği kopyala

**Returns:**
[Quaternion](../../com.aspose.threed/quaternion)
### concat(Quaternion rhs) {#concat-com.aspose.threed.Quaternion-}
```
public Quaternion concat(Quaternion rhs)
```


İki quaternion'ı birleştir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| rhs | [Quaternion](../../com.aspose.threed/quaternion) |  |

**Returns:**
[Quaternion](../../com.aspose.threed/quaternion)
### conjugate() {#conjugate--}
```
public Quaternion conjugate()
```


Mevcut quaternion'ın eşleniğini döndürür.

**Returns:**
[Quaternion](../../com.aspose.threed/quaternion) - The conjugate quaternion.
### copyFrom(Quaternion src) {#copyFrom-com.aspose.threed.Quaternion-}
```
public void copyFrom(Quaternion src)
```




**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| src | [Quaternion](../../com.aspose.threed/quaternion) |  |

### div(Quaternion lhs, double rhs) {#div-com.aspose.threed.Quaternion-double-}
```
public static Quaternion div(Quaternion lhs, double rhs)
```


/ operatörü için aşırı yükleme

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| lhs | [Quaternion](../../com.aspose.threed/quaternion) | Sol kuaternion |
| rhs | double | Sağ kuaternion |

**Returns:**
[Quaternion](../../com.aspose.threed/quaternion) - Result quaternion
### dot(Quaternion q) {#dot-com.aspose.threed.Quaternion-}
```
public double dot(Quaternion q)
```


Nokta çarpımı.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| q | [Quaternion](../../com.aspose.threed/quaternion) | Kuaternion |

**Returns:**
double - Nokta değeri
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


İki quaternion'ın eşit olup olmadığını kontrol et.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| obj | java.lang.Object | Eşitliği kontrol etmek için nesne. |

**Returns:**
boolean - Tüm bileşenler aynıysa doğru.
### eulerAngles() {#eulerAngles--}
```
public Vector3 eulerAngles()
```


Quaternion'ı Euler açılarıyla temsil edilen rotasyona dönüştürür. Tüm bileşenler radyan cinsindendir.

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - Result vector
### fromAngleAxis(double a, Vector3 axis) {#fromAngleAxis-double-com.aspose.threed.Vector3-}
```
public static Quaternion fromAngleAxis(double a, Vector3 axis)
```


Verilen eksen etrafında bir quaternion oluşturur ve saat yönünde döndürür.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| a | double | Radyan cinsinden saat yönünde dönüş |
| axis | [Vector3](../../com.aspose.threed/vector3) | Eksen |

**Returns:**
[Quaternion](../../com.aspose.threed/quaternion) - Created quaternion
### fromEulerAngle(Vector3 eulerAngle) {#fromEulerAngle-com.aspose.threed.Vector3-}
```
public static Quaternion fromEulerAngle(Vector3 eulerAngle)
```


Verilen Euler açısından quaternion oluşturur.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| eulerAngle | [Vector3](../../com.aspose.threed/vector3) | Radyan cinsinden Euler açısı |

**Returns:**
[Quaternion](../../com.aspose.threed/quaternion) - Created quaternion
### fromEulerAngle(double pitch, double yaw, double roll) {#fromEulerAngle-double-double-double-}
```
public static Quaternion fromEulerAngle(double pitch, double yaw, double roll)
```


Verilen Euler açısından quaternion oluşturur.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| eğim | double | Radyan cinsinden eğim |
| yaw | double | Radyan cinsinden yaw |
| yuvarlanma | double | Radyan cinsinden yuvarlanma |

**Returns:**
[Quaternion](../../com.aspose.threed/quaternion) - Created quaternion
### fromRotation(Vector3 orig, Vector3 dest) {#fromRotation-com.aspose.threed.Vector3-com.aspose.threed.Vector3-}
```
public static Quaternion fromRotation(Vector3 orig, Vector3 dest)
```


Orijinal yönünden hedef yönüne dönen bir quaternion oluşturur.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| orig | [Vector3](../../com.aspose.threed/vector3) | Orijinal yön |
| dest | [Vector3](../../com.aspose.threed/vector3) | Hedef yön |

**Returns:**
[Quaternion](../../com.aspose.threed/quaternion) - Created quaternion
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getLength() {#getLength--}
```
public double getLength()
```


Quaternion'ın uzunluğunu alır.

**Returns:**
double - kuaternionun uzunluğu
### hashCode() {#hashCode--}
```
public int hashCode()
```


Quaternion'ın karma kodunu alır.

**Returns:**
int - [Quaternion](../../com.aspose.threed/quaternion) hash kodu
### interpolate(float t, Quaternion from, Quaternion to) {#interpolate-float-com.aspose.threed.Quaternion-com.aspose.threed.Quaternion-}
```
public static Quaternion interpolate(float t, Quaternion from, Quaternion to)
```


Bu quaternion'ı, verilen quaternion argümanları arasında, from ve to arasında bir t değeri için ara değerle doldurur.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| t | float | Enterpolasyon katsayısı. |
| from | [Quaternion](../../com.aspose.threed/quaternion) | Kaynak kuaternion. |
| to | [Quaternion](../../com.aspose.threed/quaternion) | Hedef kuaternion. |

**Returns:**
[Quaternion](../../com.aspose.threed/quaternion) - The interpolated quaternion.
### inverse() {#inverse--}
```
public Quaternion inverse()
```


Mevcut quaternion'ın tersini döndürür.

**Returns:**
[Quaternion](../../com.aspose.threed/quaternion) - Inverse quaternion.
### mul(Quaternion lhs, Quaternion rhs) {#mul-com.aspose.threed.Quaternion-com.aspose.threed.Quaternion-}
```
public static Quaternion mul(Quaternion lhs, Quaternion rhs)
```


\* operatörü için aşırı yükleme

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| lhs | [Quaternion](../../com.aspose.threed/quaternion) | Sol kuaternion |
| rhs | [Quaternion](../../com.aspose.threed/quaternion) | Sağ kuaternion |

**Returns:**
[Quaternion](../../com.aspose.threed/quaternion) - Result quaternion
### mul(Quaternion q, Vector3 v) {#mul-com.aspose.threed.Quaternion-com.aspose.threed.Vector3-}
```
public static Vector3 mul(Quaternion q, Vector3 v)
```


\* operatörü için aşırı yükleme

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| q | [Quaternion](../../com.aspose.threed/quaternion) | Dönüş kuaternionu |
| v | [Vector3](../../com.aspose.threed/vector3) | Döndürülecek vektör |

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - Rotated vector
### mul(Quaternion q, Vector4 v) {#mul-com.aspose.threed.Quaternion-com.aspose.threed.Vector4-}
```
public static Vector4 mul(Quaternion q, Vector4 v)
```


\* operatörü için aşırı yükleme

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| q | [Quaternion](../../com.aspose.threed/quaternion) | Dönüş kuaternionu |
| v | [Vector4](../../com.aspose.threed/vector4) | Döndürülecek vektör |

**Returns:**
[Vector4](../../com.aspose.threed/vector4) - Rotated vector
### mul(Quaternion lhs, double rhs) {#mul-com.aspose.threed.Quaternion-double-}
```
public static Quaternion mul(Quaternion lhs, double rhs)
```


\* operatörü için aşırı yükleme

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| lhs | [Quaternion](../../com.aspose.threed/quaternion) | Sol kuaternion |
| rhs | double | Sağ kuaternion |

**Returns:**
[Quaternion](../../com.aspose.threed/quaternion) - Result quaternion
### mul(Vector3 v, Quaternion q) {#mul-com.aspose.threed.Vector3-com.aspose.threed.Quaternion-}
```
public static Vector3 mul(Vector3 v, Quaternion q)
```


\* operatörü için aşırı yükleme

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| v | [Vector3](../../com.aspose.threed/vector3) | Dönüş kuaternionu |
| q | [Quaternion](../../com.aspose.threed/quaternion) | Döndürülecek vektör |

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - Rotated vector
### normalize() {#normalize--}
```
public Quaternion normalize()
```


Quaternion'ı normalleştir.

**Returns:**
[Quaternion](../../com.aspose.threed/quaternion) - Normalized quaternion.
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### op_eq(Quaternion lhs, Quaternion rhs) {#op-eq-com.aspose.threed.Quaternion-com.aspose.threed.Quaternion-}
```
public static boolean op_eq(Quaternion lhs, Quaternion rhs)
```


Quaternion için eşitlik operatörü.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| lhs | [Quaternion](../../com.aspose.threed/quaternion) | Sol taraf değeri. |
| rhs | [Quaternion](../../com.aspose.threed/quaternion) | Sağ taraf değeri. |

**Returns:**
boolean - Tüm bileşenler aynıysa doğru.
### op_ne(Quaternion lhs, Quaternion rhs) {#op-ne-com.aspose.threed.Quaternion-com.aspose.threed.Quaternion-}
```
public static boolean op_ne(Quaternion lhs, Quaternion rhs)
```


Quaternion için eşitsizlik operatörü.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| lhs | [Quaternion](../../com.aspose.threed/quaternion) | Sol taraf değeri. |
| rhs | [Quaternion](../../com.aspose.threed/quaternion) | Sağ taraf değeri. |

**Returns:**
boolean - İki kuaterniyon eşit değilse True.
### slerp(double t, Quaternion v1, Quaternion v2) {#slerp-double-com.aspose.threed.Quaternion-com.aspose.threed.Quaternion-}
```
public static Quaternion slerp(double t, Quaternion v1, Quaternion v2)
```


İki değer arasında küresel doğrusal ara değerleme (slerp) gerçekleştir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| t | double | t 0 ile 1 arasındadır |
| v1 | [Quaternion](../../com.aspose.threed/quaternion) | İlk değer |
| v2 | [Quaternion](../../com.aspose.threed/quaternion) | İkinci değer |

**Returns:**
[Quaternion](../../com.aspose.threed/quaternion)
### toAngleAxis(double[] angle, Vector3 axis) {#toAngleAxis-double---com.aspose.threed.Vector3-}
```
public void toAngleAxis(double[] angle, Vector3 axis)
```


Quaternion'ı açı ve eksene ayır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| açı | double[] | Radyan cinsinden döndürme açısı. |
| axis | [Vector3](../../com.aspose.threed/vector3) | Dönüş ekseni. |

### toMatrix() {#toMatrix--}
```
public Matrix4 toMatrix()
```


Quaternion tarafından sunulan rotasyonu dönüşüm matrisine çevir.

**Returns:**
[Matrix4](../../com.aspose.threed/matrix4) - The matrix representation of current quaternion.
### toMatrix(Vector3 translation) {#toMatrix-com.aspose.threed.Vector3-}
```
public Matrix4 toMatrix(Vector3 translation)
```


Quaternion tarafından sunulan rotasyonu dönüşüm matrisine çevir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| translation | [Vector3](../../com.aspose.threed/vector3) | Matrisin çeviri kısmı. |

**Returns:**
[Matrix4](../../com.aspose.threed/matrix4) - The matrix representation of current quaternion.
### toString() {#toString--}
```
public String toString()
```


Quaternion'ın dizedeki temsilini alır.

**Returns:**
java.lang.String - Nesne dizesi
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


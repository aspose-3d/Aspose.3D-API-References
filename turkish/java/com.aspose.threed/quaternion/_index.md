---
title: "Quaternion"
second_title: "Aspose.3D for Java API Referansı"
description: "Kuataternion genellikle bilgisayar grafiklerinde dönüşüm gerçekleştirmek için kullanılır."
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

Kuataternion genellikle bilgisayar grafiklerinde dönüşüm gerçekleştirmek için kullanılır.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [Quaternion(double w, double x, double y, double z)](#Quaternion-double-double-double-double-) | Yeni bir [Quaternion](../../com.aspose.threed/quaternion) sınıfının örneğini başlatır. |
| [Quaternion()](#Quaternion--) |  |
## Alanlar

| Alan | Açıklama |
| --- | --- |
| [IDENTITY](#IDENTITY) | Kimlik kuaterniyonu. |
| [w](#w) | w bileşeni. |
| [x](#x) | x bileşeni. |
| [y](#y) | y bileşeni. |
| [z](#z) | z bileşeni. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [add(Quaternion lhs, Quaternion rhs)](#add-com.aspose.threed.Quaternion-com.aspose.threed.Quaternion-) | + için operatör aşırı yükleme |
| [clone()](#clone--) |  |
| [concat(Quaternion rhs)](#concat-com.aspose.threed.Quaternion-) | İki kuaterniyonu birleştir. |
| [conjugate()](#conjugate--) | Mevcut kuaterniyonun eşleniğini döndürür. |
| [copyFrom(Quaternion src)](#copyFrom-com.aspose.threed.Quaternion-) |  |
| [div(Quaternion lhs, double rhs)](#div-com.aspose.threed.Quaternion-double-) | / için operatör aşırı yükleme |
| [dot(Quaternion q)](#dot-com.aspose.threed.Quaternion-) | Nokta çarpımı. |
| [equals(Object obj)](#equals-java.lang.Object-) | İki kuaterniyonun eşit olup olmadığını kontrol et. |
| [eulerAngles()](#eulerAngles--) | Kuaterniyonu Euler açılarıyla temsil edilen rotasyona dönüştürür. Tüm bileşenler radyan cinsindendir. |
| [fromAngleAxis(double a, Vector3 axis)](#fromAngleAxis-double-com.aspose.threed.Vector3-) | Verilen eksen etrafında bir kuaterniyon oluşturur ve saat yönünde döndürür. |
| [fromEulerAngle(Vector3 eulerAngle)](#fromEulerAngle-com.aspose.threed.Vector3-) | Verilen Euler açısından kuaterniyon oluşturur. |
| [fromEulerAngle(double pitch, double yaw, double roll)](#fromEulerAngle-double-double-double-) | Verilen Euler açısından kuaterniyon oluşturur. |
| [fromRotation(Vector3 orig, Vector3 dest)](#fromRotation-com.aspose.threed.Vector3-com.aspose.threed.Vector3-) | Orijinal yönünden hedef yönüne dönen bir kuaterniyon oluşturur. |
| [getClass()](#getClass--) |  |
| [getLength()](#getLength--) | Kuaterniyonun uzunluğunu alır. |
| [hashCode()](#hashCode--) | Kuaterniyonun karma kodunu alır. |
| [interpolate(float t, Quaternion from, Quaternion to)](#interpolate-float-com.aspose.threed.Quaternion-com.aspose.threed.Quaternion-) | Bu kuaterniyonu, verilen kuaterniyon argümanları arasında, from ve to arasında bir t değeri için ara değerle doldurur. |
| [inverse()](#inverse--) | Mevcut kuaterniyonun tersini döndürür. |
| [mul(Quaternion lhs, Quaternion rhs)](#mul-com.aspose.threed.Quaternion-com.aspose.threed.Quaternion-) | * için operatör aşırı yükleme |
| [mul(Quaternion q, Vector3 v)](#mul-com.aspose.threed.Quaternion-com.aspose.threed.Vector3-) | * için operatör aşırı yükleme |
| [mul(Quaternion q, Vector4 v)](#mul-com.aspose.threed.Quaternion-com.aspose.threed.Vector4-) | * için operatör aşırı yükleme |
| [mul(Quaternion lhs, double rhs)](#mul-com.aspose.threed.Quaternion-double-) | * için operatör aşırı yükleme |
| [mul(Vector3 v, Quaternion q)](#mul-com.aspose.threed.Vector3-com.aspose.threed.Quaternion-) | * için operatör aşırı yükleme |
| [normalize()](#normalize--) | Kuaterniyonu normalleştir. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [op_eq(Quaternion lhs, Quaternion rhs)](#op-eq-com.aspose.threed.Quaternion-com.aspose.threed.Quaternion-) | Kuaterniyon için eşitlik operatörü. |
| [op_ne(Quaternion lhs, Quaternion rhs)](#op-ne-com.aspose.threed.Quaternion-com.aspose.threed.Quaternion-) | Kuaterniyon için eşitsizlik operatörü. |
| [slerp(double t, Quaternion v1, Quaternion v2)](#slerp-double-com.aspose.threed.Quaternion-com.aspose.threed.Quaternion-) | İki değer arasında küresel doğrusal ara değerleme gerçekleştir. |
| [toAngleAxis(double[] angle, Vector3 axis)](#toAngleAxis-double---com.aspose.threed.Vector3-) | Kuaterniyonu açı ve eksene ayır. |
| [toMatrix()](#toMatrix--) | Kuaterniyonun temsil ettiği rotasyonu dönüşüm matrisine çevir. |
| [toMatrix(Vector3 translation)](#toMatrix-com.aspose.threed.Vector3-) | Kuaterniyonun temsil ettiği rotasyonu dönüşüm matrisine çevir. |
| [toString()](#toString--) | Kuaterniyonun dizedeki temsilini alır. |
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
| w | double | kuaterniyonun w bileşeni |
| x | double | kuaterniyonun x bileşeni |
| y | double | kuaterniyonun y bileşeni |
| z | double | kuaterniyonun z bileşeni |

### Quaternion() {#Quaternion--}
```
public Quaternion()
```


### IDENTITY {#IDENTITY}
```
public static final Quaternion IDENTITY
```


Kimlik kuaterniyonu.

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


+ için operatör aşırı yükleme

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| lhs | [Quaternion](../../com.aspose.threed/quaternion) | Sol kuaterniyon |
| rhs | [Quaternion](../../com.aspose.threed/quaternion) | Sağ kuaterniyon |

**Returns:**
[Quaternion](../../com.aspose.threed/quaternion) - Result quaternion
### clone() {#clone--}
```
public Quaternion clone()
```


Geçerli örneği kopyala

**Returns:**
[Quaternion](../../com.aspose.threed/quaternion)
### concat(Quaternion rhs) {#concat-com.aspose.threed.Quaternion-}
```
public Quaternion concat(Quaternion rhs)
```


İki kuaterniyonu birleştir.

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


Mevcut kuaterniyonun eşleniğini döndürür.

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


/ için operatör aşırı yükleme

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| lhs | [Quaternion](../../com.aspose.threed/quaternion) | Sol kuaterniyon |
| rhs | double | Sağ kuaterniyon |

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
| q | [Quaternion](../../com.aspose.threed/quaternion) | Kuaterniyon |

**Returns:**
double - Nokta değeri
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


İki kuaterniyonun eşit olup olmadığını kontrol et.

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


Kuaterniyonu Euler açılarıyla temsil edilen rotasyona dönüştürür. Tüm bileşenler radyan cinsindendir.

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - Result vector
### fromAngleAxis(double a, Vector3 axis) {#fromAngleAxis-double-com.aspose.threed.Vector3-}
```
public static Quaternion fromAngleAxis(double a, Vector3 axis)
```


Verilen eksen etrafında bir kuaterniyon oluşturur ve saat yönünde döndürür.

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


Verilen Euler açısından kuaterniyon oluşturur.

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


Verilen Euler açısından kuaterniyon oluşturur.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| eğim | double | Radyan cinsinden eğim |
| sapma | double | Radyan cinsinden sapma |
| yuvarlanma | double | Radyan cinsinden yuvarlanma |

**Returns:**
[Quaternion](../../com.aspose.threed/quaternion) - Created quaternion
### fromRotation(Vector3 orig, Vector3 dest) {#fromRotation-com.aspose.threed.Vector3-com.aspose.threed.Vector3-}
```
public static Quaternion fromRotation(Vector3 orig, Vector3 dest)
```


Orijinal yönünden hedef yönüne dönen bir kuaterniyon oluşturur.

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


Kuaterniyonun uzunluğunu alır.

**Returns:**
double - kuaterniyonun uzunluğu
### hashCode() {#hashCode--}
```
public int hashCode()
```


Kuaterniyonun karma kodunu alır.

**Returns:**
int - [Quaternion](../../com.aspose.threed/quaternion) öğesinin karma kodu
### interpolate(float t, Quaternion from, Quaternion to) {#interpolate-float-com.aspose.threed.Quaternion-com.aspose.threed.Quaternion-}
```
public static Quaternion interpolate(float t, Quaternion from, Quaternion to)
```


Bu kuaterniyonu, verilen kuaterniyon argümanları arasında, from ve to arasında bir t değeri için ara değerle doldurur.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| t | float | Aralığa girmek için katsayı. |
| from | [Quaternion](../../com.aspose.threed/quaternion) | Kaynak kuaterniyon. |
| to | [Quaternion](../../com.aspose.threed/quaternion) | Hedef kuaterniyon. |

**Returns:**
[Quaternion](../../com.aspose.threed/quaternion) - The interpolated quaternion.
### inverse() {#inverse--}
```
public Quaternion inverse()
```


Mevcut kuaterniyonun tersini döndürür.

**Returns:**
[Quaternion](../../com.aspose.threed/quaternion) - Inverse quaternion.
### mul(Quaternion lhs, Quaternion rhs) {#mul-com.aspose.threed.Quaternion-com.aspose.threed.Quaternion-}
```
public static Quaternion mul(Quaternion lhs, Quaternion rhs)
```


* için operatör aşırı yükleme

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| lhs | [Quaternion](../../com.aspose.threed/quaternion) | Sol kuaterniyon |
| rhs | [Quaternion](../../com.aspose.threed/quaternion) | Sağ kuaterniyon |

**Returns:**
[Quaternion](../../com.aspose.threed/quaternion) - Result quaternion
### mul(Quaternion q, Vector3 v) {#mul-com.aspose.threed.Quaternion-com.aspose.threed.Vector3-}
```
public static Vector3 mul(Quaternion q, Vector3 v)
```


* için operatör aşırı yükleme

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| q | [Quaternion](../../com.aspose.threed/quaternion) | Rotasyon kuaterniyonu |
| v | [Vector3](../../com.aspose.threed/vector3) | Döndürülecek vektör |

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - Rotated vector
### mul(Quaternion q, Vector4 v) {#mul-com.aspose.threed.Quaternion-com.aspose.threed.Vector4-}
```
public static Vector4 mul(Quaternion q, Vector4 v)
```


* için operatör aşırı yükleme

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| q | [Quaternion](../../com.aspose.threed/quaternion) | Rotasyon kuaterniyonu |
| v | [Vector4](../../com.aspose.threed/vector4) | Döndürülecek vektör |

**Returns:**
[Vector4](../../com.aspose.threed/vector4) - Rotated vector
### mul(Quaternion lhs, double rhs) {#mul-com.aspose.threed.Quaternion-double-}
```
public static Quaternion mul(Quaternion lhs, double rhs)
```


* için operatör aşırı yükleme

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| lhs | [Quaternion](../../com.aspose.threed/quaternion) | Sol kuaterniyon |
| rhs | double | Sağ kuaterniyon |

**Returns:**
[Quaternion](../../com.aspose.threed/quaternion) - Result quaternion
### mul(Vector3 v, Quaternion q) {#mul-com.aspose.threed.Vector3-com.aspose.threed.Quaternion-}
```
public static Vector3 mul(Vector3 v, Quaternion q)
```


* için operatör aşırı yükleme

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| v | [Vector3](../../com.aspose.threed/vector3) | Rotasyon kuaterniyonu |
| q | [Quaternion](../../com.aspose.threed/quaternion) | Döndürülecek vektör |

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - Rotated vector
### normalize() {#normalize--}
```
public Quaternion normalize()
```


Kuaterniyonu normalleştir.

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


Kuaterniyon için eşitlik operatörü.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| lhs | [Quaternion](../../com.aspose.threed/quaternion) | Sol taraftaki değer. |
| rhs | [Quaternion](../../com.aspose.threed/quaternion) | Sağ taraftaki değer. |

**Returns:**
boolean - Tüm bileşenler aynıysa doğru.
### op_ne(Quaternion lhs, Quaternion rhs) {#op-ne-com.aspose.threed.Quaternion-com.aspose.threed.Quaternion-}
```
public static boolean op_ne(Quaternion lhs, Quaternion rhs)
```


Kuaterniyon için eşitsizlik operatörü.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| lhs | [Quaternion](../../com.aspose.threed/quaternion) | Sol taraftaki değer. |
| rhs | [Quaternion](../../com.aspose.threed/quaternion) | Sağ taraftaki değer. |

**Returns:**
boolean - İki quaternion eşit değilse True.
### slerp(double t, Quaternion v1, Quaternion v2) {#slerp-double-com.aspose.threed.Quaternion-com.aspose.threed.Quaternion-}
```
public static Quaternion slerp(double t, Quaternion v1, Quaternion v2)
```


İki değer arasında küresel doğrusal ara değerleme gerçekleştir.

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


Kuaterniyonu açı ve eksene ayır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| açı | double[] | Döndürme açısı, radyan cinsinden. |
| axis | [Vector3](../../com.aspose.threed/vector3) | Dönüş ekseni. |

### toMatrix() {#toMatrix--}
```
public Matrix4 toMatrix()
```


Kuaterniyonun temsil ettiği rotasyonu dönüşüm matrisine çevir.

**Returns:**
[Matrix4](../../com.aspose.threed/matrix4) - The matrix representation of current quaternion.
### toMatrix(Vector3 translation) {#toMatrix-com.aspose.threed.Vector3-}
```
public Matrix4 toMatrix(Vector3 translation)
```


Kuaterniyonun temsil ettiği rotasyonu dönüşüm matrisine çevir.

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


Kuaterniyonun dizedeki temsilini alır.

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


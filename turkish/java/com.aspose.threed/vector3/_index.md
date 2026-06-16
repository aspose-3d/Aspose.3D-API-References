---
title: "Vector3"
second_title: "Aspose.3D for Java API Referansı"
description: "Üç bileşenli bir vektör."
type: docs
weight: 202
url: /tr/java/com.aspose.threed/vector3/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.lang.Comparable, com.aspose.threed.Struct, java.io.Serializable
```
public final class Vector3 implements Comparable<Vector3>, Struct<Vector3>, Serializable
```

Üç bileşenli bir vektör.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [Vector3(double x, double y, double z)](#Vector3-double-double-double-) | Yeni bir [Vector3](../../com.aspose.threed/vector3) yapısının bir örneğini başlatır. |
| [Vector3(FVector3 vec)](#Vector3-com.aspose.threed.FVector3-) | Yeni bir [Vector3](../../com.aspose.threed/vector3) yapısının bir örneğini başlatır. |
| [Vector3(double v)](#Vector3-double-) | Yeni bir [Vector3](../../com.aspose.threed/vector3) yapısının bir örneğini başlatır. |
| [Vector3(Vector4 vec4)](#Vector3-com.aspose.threed.Vector4-) | Yeni bir [Vector3](../../com.aspose.threed/vector3) yapısının bir örneğini başlatır. |
| [Vector3()](#Vector3--) |  |
## Alanlar

| Alan | Açıklama |
| --- | --- |
| [x](#x) | x bileşeni. |
| [y](#y) | y bileşeni. |
| [z](#z) | z bileşeni. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [add(Vector3 lhs, Vector3 rhs)](#add-com.aspose.threed.Vector3-com.aspose.threed.Vector3-) | + operatörü için aşırı yükleme |
| [angleBetween(Vector3 dir)](#angleBetween-com.aspose.threed.Vector3-) | İki yön arasındaki iç açıyı hesaplayın. İki yön, normalleştirilmemiş vektörler olabilir. |
| [angleBetween(Vector3 dir, Vector3 up)](#angleBetween-com.aspose.threed.Vector3-com.aspose.threed.Vector3-) | İki yön arasındaki iç açıyı hesaplayın. İki yön, normalleştirilmemiş vektörler olabilir. |
| [clone()](#clone--) |  |
| [compareTo(Vector3 other)](#compareTo-com.aspose.threed.Vector3-) | Mevcut vektörü başka bir örnek ile karşılaştırın. |
| [copyFrom(Vector3 src)](#copyFrom-com.aspose.threed.Vector3-) |  |
| [cos()](#cos--) | Her bileşende kosinüsü hesaplar |
| [create(Vector3 v)](#create-com.aspose.threed.Vector3-) | Vector3'ü FVector3'e dönüştürmek için açık dönüşüm operatörü |
| [cross(Vector3 rhs)](#cross-com.aspose.threed.Vector3-) | İki vektörün çapraz çarpımı |
| [div(Vector3 lhs, Vector3 rhs)](#div-com.aspose.threed.Vector3-com.aspose.threed.Vector3-) | / operatörü için aşırı yükleme |
| [div(Vector3 lhs, double rhs)](#div-com.aspose.threed.Vector3-double-) | / operatörü için aşırı yükleme |
| [dot(Vector3 rhs)](#dot-com.aspose.threed.Vector3-) | İki vektörün nokta çarpımını alır |
| [equals(Object obj)](#equals-java.lang.Object-) | İki vector3'ün eşit olup olmadığını kontrol eder |
| [get(int idx)](#get-int-) | Vektörün bileşenini indeksle alır. |
| [getClass()](#getClass--) |  |
| [getLength()](#getLength--) | Bu vektörün uzunluğunu alır. |
| [getLength2()](#getLength2--) | Uzunluğun karesini alır. |
| [getOne()](#getOne--) | Birim vektörü (1, 1, 1) alır |
| [getUnitX()](#getUnitX--) | Birim vektörü (1, 0, 0) alır |
| [getUnitY()](#getUnitY--) | Birim vektörü (0, 1, 0) alır |
| [getUnitZ()](#getUnitZ--) | Birim vektörü (0, 0, 1) alır |
| [getZero()](#getZero--) | Birim vektörü (0, 0, 0) alır |
| [hashCode()](#hashCode--) | Vector3'ün hash kodunu alır |
| [mul(Vector3 lhs, Vector3 rhs)](#mul-com.aspose.threed.Vector3-com.aspose.threed.Vector3-) | \* operatörü için aşırı yükleme |
| [mul(Vector3 lhs, double rhs)](#mul-com.aspose.threed.Vector3-double-) | \* operatörü için aşırı yükleme |
| [mul(double lhs, Vector3 rhs)](#mul-double-com.aspose.threed.Vector3-) | \* operatörü için aşırı yükleme |
| [negative(Vector3 v)](#negative-com.aspose.threed.Vector3-) | - için operatör aşırı yüklemesi |
| [normalize()](#normalize--) | Bu örneği normallaştırır. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [op_eq(Vector3 lhs, Vector3 rhs)](#op-eq-com.aspose.threed.Vector3-com.aspose.threed.Vector3-) | Vector3 için eşitlik operatörü |
| [op_ne(Vector3 lhs, Vector3 rhs)](#op-ne-com.aspose.threed.Vector3-com.aspose.threed.Vector3-) | Vector3 için eşitsizlik operatörü |
| [set(double newX, double newY, double newZ)](#set-double-double-double-) | x/y/z bileşenini tek bir çağrıda ayarlar. |
| [set(int idx, double value)](#set-int-double-) | Vektörün bileşenini indeksle ayarlar. |
| [sin()](#sin--) | Her bileşenin sinüsünü hesaplar |
| [sub(Vector3 lhs, Vector3 rhs)](#sub-com.aspose.threed.Vector3-com.aspose.threed.Vector3-) | - (eksi) için operatör aşırı yüklemesi |
| [toString()](#toString--) | Geçerli [Vector3](../../com.aspose.threed/vector3) öğesini temsil eden bir java.lang.String döndürür. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Vector3(double x, double y, double z) {#Vector3-double-double-double-}
```
public Vector3(double x, double y, double z)
```


Yeni bir [Vector3](../../com.aspose.threed/vector3) yapısının bir örneğini başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| x | double | x koordinatı. |
| y | double | y koordinatı. |
| z | double | z koordinatı. |

### Vector3(FVector3 vec) {#Vector3-com.aspose.threed.FVector3-}
```
public Vector3(FVector3 vec)
```


Yeni bir [Vector3](../../com.aspose.threed/vector3) yapısının bir örneğini başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| vec | [FVector3](../../com.aspose.threed/fvector3) | x koordinatı. |

### Vector3(double v) {#Vector3-double-}
```
public Vector3(double v)
```


Yeni bir [Vector3](../../com.aspose.threed/vector3) yapısının bir örneğini başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| v | double | V. |

### Vector3(Vector4 vec4) {#Vector3-com.aspose.threed.Vector4-}
```
public Vector3(Vector4 vec4)
```


Yeni bir [Vector3](../../com.aspose.threed/vector3) yapısının bir örneğini başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| vec4 | [Vector4](../../com.aspose.threed/vector4) | Vec4. |

### Vector3() {#Vector3--}
```
public Vector3()
```


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

### add(Vector3 lhs, Vector3 rhs) {#add-com.aspose.threed.Vector3-com.aspose.threed.Vector3-}
```
public static Vector3 add(Vector3 lhs, Vector3 rhs)
```


+ operatörü için aşırı yükleme

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| lhs | [Vector3](../../com.aspose.threed/vector3) | Sol vektör |
| rhs | [Vector3](../../com.aspose.threed/vector3) | Sağ vektör |

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - Result vector
### angleBetween(Vector3 dir) {#angleBetween-com.aspose.threed.Vector3-}
```
public double angleBetween(Vector3 dir)
```


İki yön arasındaki iç açıyı hesaplayın. İki yön, normalleştirilmemiş vektörler olabilir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| dir | [Vector3](../../com.aspose.threed/vector3) | Karşılaştırılacak yön vektörü |

**Returns:**
double - radyan cinsinden iç açı
### angleBetween(Vector3 dir, Vector3 up) {#angleBetween-com.aspose.threed.Vector3-com.aspose.threed.Vector3-}
```
public double angleBetween(Vector3 dir, Vector3 up)
```


İki yön arasındaki iç açıyı hesaplayın. İki yön, normalleştirilmemiş vektörler olabilir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| dir | [Vector3](../../com.aspose.threed/vector3) | Karşılaştırılacak yön vektörü |
| up | [Vector3](../../com.aspose.threed/vector3) | İki yönün ortak düzlemindeki yukarı vektör |

**Returns:**
double - radyan cinsinden iç açı
### clone() {#clone--}
```
public Vector3 clone()
```


Mevcut örneği kopyala

**Returns:**
[Vector3](../../com.aspose.threed/vector3)
### compareTo(Vector3 other) {#compareTo-com.aspose.threed.Vector3-}
```
public int compareTo(Vector3 other)
```


Mevcut vektörü başka bir örnek ile karşılaştırın.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| other | [Vector3](../../com.aspose.threed/vector3) |  |

**Returns:**
int
### copyFrom(Vector3 src) {#copyFrom-com.aspose.threed.Vector3-}
```
public void copyFrom(Vector3 src)
```




**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| src | [Vector3](../../com.aspose.threed/vector3) |  |

### cos() {#cos--}
```
public Vector3 cos()
```


Her bileşende kosinüsü hesaplar

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - Calculated [Vector3](../../com.aspose.threed/vector3).
### create(Vector3 v) {#create-com.aspose.threed.Vector3-}
```
public static FVector3 create(Vector3 v)
```


Vector3'ü FVector3'e dönüştürmek için açık dönüşüm operatörü

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| v | [Vector3](../../com.aspose.threed/vector3) |  |

**Returns:**
[FVector3](../../com.aspose.threed/fvector3)
### cross(Vector3 rhs) {#cross-com.aspose.threed.Vector3-}
```
public Vector3 cross(Vector3 rhs)
```


İki vektörün çapraz çarpımı

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| rhs | [Vector3](../../com.aspose.threed/vector3) | Sağ taraf değeri. |

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - Cross product of two [Vector3](../../com.aspose.threed/vector3)s.
### div(Vector3 lhs, Vector3 rhs) {#div-com.aspose.threed.Vector3-com.aspose.threed.Vector3-}
```
public static Vector3 div(Vector3 lhs, Vector3 rhs)
```


/ operatörü için aşırı yükleme

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| lhs | [Vector3](../../com.aspose.threed/vector3) | Sol vektör |
| rhs | [Vector3](../../com.aspose.threed/vector3) | Sağ vektör |

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - Result vector
### div(Vector3 lhs, double rhs) {#div-com.aspose.threed.Vector3-double-}
```
public static Vector3 div(Vector3 lhs, double rhs)
```


/ operatörü için aşırı yükleme

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| lhs | [Vector3](../../com.aspose.threed/vector3) | Sol vektör |
| rhs | double | Sağ çift değeri |

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - Result vector
### dot(Vector3 rhs) {#dot-com.aspose.threed.Vector3-}
```
public double dot(Vector3 rhs)
```


İki vektörün nokta çarpımını alır

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| rhs | [Vector3](../../com.aspose.threed/vector3) | Sağ taraf değeri. |

**Returns:**
double - İki vektörün noktasal çarpımı.
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


İki vector3'ün eşit olup olmadığını kontrol eder

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| obj | java.lang.Object | Eşitliği kontrol etmek için nesne. |

**Returns:**
boolean - Tüm bileşenler aynıysa doğru.
### get(int idx) {#get-int-}
```
public double get(int idx)
```


Vektörün bileşenini indeksle alır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| idx | int |  |

**Returns:**
double - vektörün indeksine göre bileşeni.
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


Bu vektörün uzunluğunu alır.

**Returns:**
double - bu vektörün uzunluğu.
### getLength2() {#getLength2--}
```
public double getLength2()
```


Uzunluğun karesini alır.

**Returns:**
double - uzunluğun karesi.
### getOne() {#getOne--}
```
public static Vector3 getOne()
```


Birim vektörü (1, 1, 1) alır

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - unit vector (1, 1, 1)
### getUnitX() {#getUnitX--}
```
public static Vector3 getUnitX()
```


Birim vektörü (1, 0, 0) alır

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - unit vector (1, 0, 0)
### getUnitY() {#getUnitY--}
```
public static Vector3 getUnitY()
```


Birim vektörü (0, 1, 0) alır

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - unit vector (0, 1, 0)
### getUnitZ() {#getUnitZ--}
```
public static Vector3 getUnitZ()
```


Birim vektörü (0, 0, 1) alır

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - unit vector (0, 0, 1)
### getZero() {#getZero--}
```
public static Vector3 getZero()
```


Birim vektörü (0, 0, 0) alır

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - unit vector (0, 0, 0)
### hashCode() {#hashCode--}
```
public int hashCode()
```


Vector3'ün hash kodunu alır

**Returns:**
int - [Vector3](../../com.aspose.threed/vector3) öğesinin hash kodu
### mul(Vector3 lhs, Vector3 rhs) {#mul-com.aspose.threed.Vector3-com.aspose.threed.Vector3-}
```
public static Vector3 mul(Vector3 lhs, Vector3 rhs)
```


\* operatörü için aşırı yükleme

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| lhs | [Vector3](../../com.aspose.threed/vector3) | Sol vektör |
| rhs | [Vector3](../../com.aspose.threed/vector3) | Sağ vektör |

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - Result vector
### mul(Vector3 lhs, double rhs) {#mul-com.aspose.threed.Vector3-double-}
```
public static Vector3 mul(Vector3 lhs, double rhs)
```


\* operatörü için aşırı yükleme

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| lhs | [Vector3](../../com.aspose.threed/vector3) | Sol vektör |
| rhs | double | Sağ çift değeri |

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - Result vector
### mul(double lhs, Vector3 rhs) {#mul-double-com.aspose.threed.Vector3-}
```
public static Vector3 mul(double lhs, Vector3 rhs)
```


\* operatörü için aşırı yükleme

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| lhs | double | Sol skaler |
| rhs | [Vector3](../../com.aspose.threed/vector3) | Sağ vektör |

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - Result vector
### negative(Vector3 v) {#negative-com.aspose.threed.Vector3-}
```
public static Vector3 negative(Vector3 v)
```


- için operatör aşırı yüklemesi

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| v | [Vector3](../../com.aspose.threed/vector3) | Orijin vektör |

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - Result vector
### normalize() {#normalize--}
```
public Vector3 normalize()
```


Bu örneği normallaştırır.

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - Normalized vector.
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### op_eq(Vector3 lhs, Vector3 rhs) {#op-eq-com.aspose.threed.Vector3-com.aspose.threed.Vector3-}
```
public static boolean op_eq(Vector3 lhs, Vector3 rhs)
```


Vector3 için eşitlik operatörü

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| lhs | [Vector3](../../com.aspose.threed/vector3) | Sol taraf değeri. |
| rhs | [Vector3](../../com.aspose.threed/vector3) | Sağ taraf değeri. |

**Returns:**
boolean - Tüm bileşenler aynıysa doğru.
### op_ne(Vector3 lhs, Vector3 rhs) {#op-ne-com.aspose.threed.Vector3-com.aspose.threed.Vector3-}
```
public static boolean op_ne(Vector3 lhs, Vector3 rhs)
```


Vector3 için eşitsizlik operatörü

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| lhs | [Vector3](../../com.aspose.threed/vector3) | Sol taraf değeri. |
| rhs | [Vector3](../../com.aspose.threed/vector3) | Sağ taraf değeri. |

**Returns:**
boolean - İki vektör eşit değilse doğru.
### set(double newX, double newY, double newZ) {#set-double-double-double-}
```
public void set(double newX, double newY, double newZ)
```


x/y/z bileşenini tek bir çağrıda ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| newX | double | x bileşeni. |
| newY | double | y bileşeni. |
| newZ | double | z bileşeni. |

### set(int idx, double value) {#set-int-double-}
```
public void set(int idx, double value)
```


Vektörün bileşenini indeksle ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| idx | int |  |
| değer | double | Yeni değer |

### sin() {#sin--}
```
public Vector3 sin()
```


Her bileşenin sinüsünü hesaplar

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - Calculated [Vector3](../../com.aspose.threed/vector3).
### sub(Vector3 lhs, Vector3 rhs) {#sub-com.aspose.threed.Vector3-com.aspose.threed.Vector3-}
```
public static Vector3 sub(Vector3 lhs, Vector3 rhs)
```


- (eksi) için operatör aşırı yüklemesi

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| lhs | [Vector3](../../com.aspose.threed/vector3) | Sol vektör |
| rhs | [Vector3](../../com.aspose.threed/vector3) | Sağ vektör |

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - Result vector
### toString() {#toString--}
```
public String toString()
```


Geçerli [Vector3](../../com.aspose.threed/vector3) öğesini temsil eden bir java.lang.String döndürür.

**Returns:**
java.lang.String - Geçerli [Vector3](../../com.aspose.threed/vector3) öğesini temsil eden bir java.lang.String.
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


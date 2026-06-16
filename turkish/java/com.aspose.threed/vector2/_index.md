---
title: "Vector2"
second_title: "Aspose.3D for Java API Referansı"
description: "İki bileşenli bir vektör."
type: docs
weight: 201
url: /tr/java/com.aspose.threed/vector2/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.lang.Comparable, com.aspose.threed.Struct, java.io.Serializable
```
public final class Vector2 implements Comparable<Vector2>, Struct<Vector2>, Serializable
```

İki bileşenli bir vektör.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [Vector2(double s)](#Vector2-double-) | Yeni bir [Vector2](../../com.aspose.threed/vector2) yapısı örneği başlatır. |
| [Vector2(Vector3 s)](#Vector2-com.aspose.threed.Vector3-) | Yeni bir [Vector2](../../com.aspose.threed/vector2) yapısı örneği başlatır. |
| [Vector2(FVector2 vec)](#Vector2-com.aspose.threed.FVector2-) | Yeni bir [Vector2](../../com.aspose.threed/vector2) yapısı örneği başlatır. |
| [Vector2(double x, double y)](#Vector2-double-double-) | Yeni bir [Vector2](../../com.aspose.threed/vector2) yapısı örneği başlatır. |
| [Vector2()](#Vector2--) |  |
## Alanlar

| Alan | Açıklama |
| --- | --- |
| [x](#x) | x bileşeni. |
| [y](#y) | y bileşeni. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [add(Vector2 lhs, Vector2 rhs)](#add-com.aspose.threed.Vector2-com.aspose.threed.Vector2-) | Vector2 için toplama operatörü. |
| [clone()](#clone--) |  |
| [compareTo(Vector2 other)](#compareTo-com.aspose.threed.Vector2-) | Mevcut vektörü başka bir örnek ile karşılaştırın. |
| [copyFrom(Vector2 src)](#copyFrom-com.aspose.threed.Vector2-) |  |
| [create(Vector2 v)](#create-com.aspose.threed.Vector2-) | Vector2'yi FVector2'ye dönüştürmek için açık dönüşüm operatörü. |
| [cross(Vector2 v)](#cross-com.aspose.threed.Vector2-) | İki vektörün çapraz çarpımı |
| [div(Vector2 lhs, double rhs)](#div-com.aspose.threed.Vector2-double-) | Vector2 için bölme operatörü. |
| [dot(Vector2 rhs)](#dot-com.aspose.threed.Vector2-) | İki vektörün nokta çarpımını alır |
| [equals(Vector2 rhs)](#equals-com.aspose.threed.Vector2-) | İki vector2'nin eşit olup olmadığını kontrol et. |
| [equals(Object obj)](#equals-java.lang.Object-) | İki vector2'nin eşit olup olmadığını kontrol et. |
| [getClass()](#getClass--) |  |
| [getLength()](#getLength--) | Uzunluğu alır. |
| [getU()](#getU--) | [Vector2](../../com.aspose.threed/vector2) bir eşleme koordinatı olarak kullanılıyorsa U bileşenini alır. |
| [getV()](#getV--) | [Vector2](../../com.aspose.threed/vector2) bir eşleme koordinatı olarak kullanılıyorsa V bileşenini alır. |
| [hashCode()](#hashCode--) | Vector2'nin hash kodunu alır. |
| [mul(Vector2 lhs, double rhs)](#mul-com.aspose.threed.Vector2-double-) | Vector2 için çarpma operatörü. |
| [mul(double lhs, Vector2 rhs)](#mul-double-com.aspose.threed.Vector2-) | Vector2 için çarpma operatörü. |
| [normalize()](#normalize--) | Bu örneği normallaştırır. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [op_eq(Vector2 lhs, Vector2 rhs)](#op-eq-com.aspose.threed.Vector2-com.aspose.threed.Vector2-) | Vector2 için eşitlik operatörü |
| [op_ne(Vector2 lhs, Vector2 rhs)](#op-ne-com.aspose.threed.Vector2-com.aspose.threed.Vector2-) | Vector2 için eşit olmayan operatör |
| [setU(double value)](#setU-double-) | Eğer [Vector2](../../com.aspose.threed/vector2) bir eşleme koordinatı olarak kullanılıyorsa U bileşenini ayarlar. |
| [setV(double value)](#setV-double-) | Eğer [Vector2](../../com.aspose.threed/vector2) bir eşleme koordinatı olarak kullanılıyorsa V bileşenini ayarlar. |
| [sub(Vector2 lhs, Vector2 rhs)](#sub-com.aspose.threed.Vector2-com.aspose.threed.Vector2-) | Vector2 için çıkarma operatörü |
| [toString()](#toString--) | Geçerli [Vector2](../../com.aspose.threed/vector2) nesnesini temsil eden bir java.lang.String döndürür. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Vector2(double s) {#Vector2-double-}
```
public Vector2(double s)
```


Yeni bir [Vector2](../../com.aspose.threed/vector2) yapısı örneği başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| s | double | S. |

### Vector2(Vector3 s) {#Vector2-com.aspose.threed.Vector3-}
```
public Vector2(Vector3 s)
```


Yeni bir [Vector2](../../com.aspose.threed/vector2) yapısı örneği başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| s | [Vector3](../../com.aspose.threed/vector3) | S. |

### Vector2(FVector2 vec) {#Vector2-com.aspose.threed.FVector2-}
```
public Vector2(FVector2 vec)
```


Yeni bir [Vector2](../../com.aspose.threed/vector2) yapısı örneği başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| vec | [FVector2](../../com.aspose.threed/fvector2) | Float tipinde vektör. |

### Vector2(double x, double y) {#Vector2-double-double-}
```
public Vector2(double x, double y)
```


Yeni bir [Vector2](../../com.aspose.threed/vector2) yapısı örneği başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| x | double | x koordinatı. |
| y | double | y koordinatı. |

### Vector2() {#Vector2--}
```
public Vector2()
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

### add(Vector2 lhs, Vector2 rhs) {#add-com.aspose.threed.Vector2-com.aspose.threed.Vector2-}
```
public static Vector2 add(Vector2 lhs, Vector2 rhs)
```


Vector2 için toplama operatörü.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| lhs | [Vector2](../../com.aspose.threed/vector2) | Sol taraf değeri. |
| rhs | [Vector2](../../com.aspose.threed/vector2) | Sağ taraf değeri. |

**Returns:**
[Vector2](../../com.aspose.threed/vector2) - The result of addition.
### clone() {#clone--}
```
public Vector2 clone()
```


Mevcut örneği kopyala

**Returns:**
[Vector2](../../com.aspose.threed/vector2)
### compareTo(Vector2 other) {#compareTo-com.aspose.threed.Vector2-}
```
public int compareTo(Vector2 other)
```


Mevcut vektörü başka bir örnek ile karşılaştırın.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| other | [Vector2](../../com.aspose.threed/vector2) |  |

**Returns:**
int
### copyFrom(Vector2 src) {#copyFrom-com.aspose.threed.Vector2-}
```
public void copyFrom(Vector2 src)
```




**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| src | [Vector2](../../com.aspose.threed/vector2) |  |

### create(Vector2 v) {#create-com.aspose.threed.Vector2-}
```
public static FVector2 create(Vector2 v)
```


Vector2'yi FVector2'ye dönüştürmek için açık dönüşüm operatörü.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| v | [Vector2](../../com.aspose.threed/vector2) |  |

**Returns:**
[FVector2](../../com.aspose.threed/fvector2)
### cross(Vector2 v) {#cross-com.aspose.threed.Vector2-}
```
public double cross(Vector2 v)
```


İki vektörün çapraz çarpımı

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| v | [Vector2](../../com.aspose.threed/vector2) |  |

**Returns:**
double
### div(Vector2 lhs, double rhs) {#div-com.aspose.threed.Vector2-double-}
```
public static Vector2 div(Vector2 lhs, double rhs)
```


Vector2 için bölme operatörü.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| lhs | [Vector2](../../com.aspose.threed/vector2) | Sol taraf değeri. |
| rhs | double | Sağ taraf değeri. |

**Returns:**
[Vector2](../../com.aspose.threed/vector2) - The result of division.
### dot(Vector2 rhs) {#dot-com.aspose.threed.Vector2-}
```
public double dot(Vector2 rhs)
```


İki vektörün nokta çarpımını alır

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| rhs | [Vector2](../../com.aspose.threed/vector2) | Sağ taraf değeri. |

**Returns:**
double - İki vektörün noktasal çarpımı.
### equals(Vector2 rhs) {#equals-com.aspose.threed.Vector2-}
```
public boolean equals(Vector2 rhs)
```


İki vector2'nin eşit olup olmadığını kontrol et.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| rhs | [Vector2](../../com.aspose.threed/vector2) | Sağ taraftaki değer. |

**Returns:**
boolean - Tüm bileşenler aynıysa doğru.
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


İki vector2'nin eşit olup olmadığını kontrol et.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| obj | java.lang.Object | Karşılaştırılacak nesne. |

**Returns:**
boolean - Tüm bileşenler aynıysa doğru.
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


Uzunluğu alır.

**Returns:**
double - uzunluk.
### getU() {#getU--}
```
public double getU()
```


[Vector2](../../com.aspose.threed/vector2) bir eşleme koordinatı olarak kullanılıyorsa U bileşenini alır. x bileşeninin bir takma adıdır.

**Returns:**
double - [Vector2](../../com.aspose.threed/vector2) bir eşleme koordinatı olarak kullanılıyorsa U bileşeni. x bileşeninin bir takma adıdır.
### getV() {#getV--}
```
public double getV()
```


[Vector2](../../com.aspose.threed/vector2) bir eşleme koordinatı olarak kullanılıyorsa V bileşenini alır. y bileşeninin bir takma adıdır.

**Returns:**
double - [Vector2](../../com.aspose.threed/vector2) bir eşleme koordinatı olarak kullanılıyorsa V bileşeni. y bileşeninin bir takma adıdır.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Vector2'nin hash kodunu alır.

**Returns:**
int - [Vector2](../../com.aspose.threed/vector2) nesnesinin karma kodu
### mul(Vector2 lhs, double rhs) {#mul-com.aspose.threed.Vector2-double-}
```
public static Vector2 mul(Vector2 lhs, double rhs)
```


Vector2 için çarpma operatörü.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| lhs | [Vector2](../../com.aspose.threed/vector2) | Sol taraf değeri. |
| rhs | double | Sağ taraf değeri. |

**Returns:**
[Vector2](../../com.aspose.threed/vector2) - The result of multiply.
### mul(double lhs, Vector2 rhs) {#mul-double-com.aspose.threed.Vector2-}
```
public static Vector2 mul(double lhs, Vector2 rhs)
```


Vector2 için çarpma operatörü.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| lhs | double | Sol taraf değeri. |
| rhs | [Vector2](../../com.aspose.threed/vector2) | Sağ taraf değeri. |

**Returns:**
[Vector2](../../com.aspose.threed/vector2) - The result of multiply.
### normalize() {#normalize--}
```
public Vector2 normalize()
```


Bu örneği normallaştırır.

**Returns:**
[Vector2](../../com.aspose.threed/vector2) - Normalized vector.
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### op_eq(Vector2 lhs, Vector2 rhs) {#op-eq-com.aspose.threed.Vector2-com.aspose.threed.Vector2-}
```
public static boolean op_eq(Vector2 lhs, Vector2 rhs)
```


Vector2 için eşitlik operatörü

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| lhs | [Vector2](../../com.aspose.threed/vector2) | Sol taraf değeri. |
| rhs | [Vector2](../../com.aspose.threed/vector2) | Sağ taraf değeri. |

**Returns:**
boolean - Tüm bileşenler aynıysa doğru.
### op_ne(Vector2 lhs, Vector2 rhs) {#op-ne-com.aspose.threed.Vector2-com.aspose.threed.Vector2-}
```
public static boolean op_ne(Vector2 lhs, Vector2 rhs)
```


Vector2 için eşit olmayan operatör

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| lhs | [Vector2](../../com.aspose.threed/vector2) | Sol taraf değeri. |
| rhs | [Vector2](../../com.aspose.threed/vector2) | Sağ taraf değeri. |

**Returns:**
boolean - İki vektör eşit değilse doğru.
### setU(double value) {#setU-double-}
```
public void setU(double value)
```


Eğer [Vector2](../../com.aspose.threed/vector2) bir eşleme koordinatı olarak kullanılıyorsa U bileşenini ayarlar. x bileşeninin bir takma adıdır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | double | Yeni değer |

### setV(double value) {#setV-double-}
```
public void setV(double value)
```


Eğer [Vector2](../../com.aspose.threed/vector2) bir eşleme koordinatı olarak kullanılıyorsa V bileşenini ayarlar. y bileşeninin bir takma adıdır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | double | Yeni değer |

### sub(Vector2 lhs, Vector2 rhs) {#sub-com.aspose.threed.Vector2-com.aspose.threed.Vector2-}
```
public static Vector2 sub(Vector2 lhs, Vector2 rhs)
```


Vector2 için çıkarma operatörü

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| lhs | [Vector2](../../com.aspose.threed/vector2) | Sol taraf değeri. |
| rhs | [Vector2](../../com.aspose.threed/vector2) | Sağ taraf değeri. |

**Returns:**
[Vector2](../../com.aspose.threed/vector2) - The result of substraction.
### toString() {#toString--}
```
public String toString()
```


Geçerli [Vector2](../../com.aspose.threed/vector2) nesnesini temsil eden bir java.lang.String döndürür.

**Returns:**
java.lang.String - Geçerli [Vector2](../../com.aspose.threed/vector2) nesnesini temsil eden bir java.lang.String.
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


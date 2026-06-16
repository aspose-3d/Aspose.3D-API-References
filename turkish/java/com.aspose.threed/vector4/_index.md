---
title: "Vector4"
second_title: "Aspose.3D for Java API Referansı"
description: "Dört bileşenli bir vektör."
type: docs
weight: 203
url: /tr/java/com.aspose.threed/vector4/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.lang.Comparable, com.aspose.threed.Struct, java.io.Serializable
```
public final class Vector4 implements Comparable<Vector4>, Struct<Vector4>, Serializable
```

Dört bileşenli bir vektör.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [Vector4(Vector3 vec, double w)](#Vector4-com.aspose.threed.Vector3-double-) | Yeni bir [Vector4](../../com.aspose.threed/vector4) yapısının örneğini başlatır. |
| [Vector4(Vector3 vec)](#Vector4-com.aspose.threed.Vector3-) | Yeni bir [Vector4](../../com.aspose.threed/vector4) yapısının örneğini başlatır. |
| [Vector4(FVector4 vec)](#Vector4-com.aspose.threed.FVector4-) | Yeni bir [Vector4](../../com.aspose.threed/vector4) yapısının örneğini başlatır. |
| [Vector4(double x, double y, double z)](#Vector4-double-double-double-) | Yeni bir [Vector4](../../com.aspose.threed/vector4) yapısının örneğini başlatır. |
| [Vector4(double x, double y, double z, double w)](#Vector4-double-double-double-double-) | Yeni bir [Vector4](../../com.aspose.threed/vector4) yapısının örneğini başlatır. |
| [Vector4()](#Vector4--) |  |
## Alanlar

| Alan | Açıklama |
| --- | --- |
| [w](#w) | w bileşeni. |
| [x](#x) | x bileşeni. |
| [y](#y) | y bileşeni. |
| [z](#z) | z bileşeni. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [add(Vector4 lhs, Vector4 rhs)](#add-com.aspose.threed.Vector4-com.aspose.threed.Vector4-) | + operatörü için aşırı yükleme |
| [clone()](#clone--) |  |
| [compareTo(Vector4 other)](#compareTo-com.aspose.threed.Vector4-) | Mevcut vektörü başka bir örnek ile karşılaştırın. |
| [copyFrom(Vector4 src)](#copyFrom-com.aspose.threed.Vector4-) |  |
| [create(Vector4 v)](#create-com.aspose.threed.Vector4-) | Vector4'ü FVector4'e dönüştürmek için açık dönüşüm operatörü |
| [equals(Object obj)](#equals-java.lang.Object-) | İki vektörün eşit olup olmadığını kontrol et |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) | Bu vektörün karma kodunu alır |
| [mul(Vector4 lhs, Vector4 rhs)](#mul-com.aspose.threed.Vector4-com.aspose.threed.Vector4-) | \* operatörü için aşırı yükleme |
| [mul(Vector4 lhs, double rhs)](#mul-com.aspose.threed.Vector4-double-) | \* operatörü için aşırı yükleme |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [set(double newX, double newY, double newZ)](#set-double-double-double-) | Vektörün xyz bileşenlerini bir anda ayarlar, w 1 olarak ayarlanacak |
| [set(double newX, double newY, double newZ, double newW)](#set-double-double-double-double-) | Vektörün tüm bileşenlerini bir anda ayarlar |
| [sub(Vector4 lhs, Vector4 rhs)](#sub-com.aspose.threed.Vector4-com.aspose.threed.Vector4-) | - (eksi) için operatör aşırı yüklemesi |
| [toString()](#toString--) | Geçerli [Vector4](../../com.aspose.threed/vector4) nesnesini temsil eden bir java.lang.String döndürür. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Vector4(Vector3 vec, double w) {#Vector4-com.aspose.threed.Vector3-double-}
```
public Vector4(Vector3 vec, double w)
```


Yeni bir [Vector4](../../com.aspose.threed/vector4) yapısının örneğini başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| vec | [Vector3](../../com.aspose.threed/vector3) | Vektör. |
| w | double | Genişlik. |

### Vector4(Vector3 vec) {#Vector4-com.aspose.threed.Vector3-}
```
public Vector4(Vector3 vec)
```


Yeni bir [Vector4](../../com.aspose.threed/vector4) yapısının örneğini başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| vec | [Vector3](../../com.aspose.threed/vector3) | Vektör. |

### Vector4(FVector4 vec) {#Vector4-com.aspose.threed.FVector4-}
```
public Vector4(FVector4 vec)
```


Yeni bir [Vector4](../../com.aspose.threed/vector4) yapısının örneğini başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| vec | [FVector4](../../com.aspose.threed/fvector4) | Vektör. |

### Vector4(double x, double y, double z) {#Vector4-double-double-double-}
```
public Vector4(double x, double y, double z)
```


Yeni bir [Vector4](../../com.aspose.threed/vector4) yapısının örneğini başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| x | double | x koordinatı. |
| y | double | y koordinatı. |
| z | double | z koordinatı. |

### Vector4(double x, double y, double z, double w) {#Vector4-double-double-double-double-}
```
public Vector4(double x, double y, double z, double w)
```


Yeni bir [Vector4](../../com.aspose.threed/vector4) yapısının örneğini başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| x | double | x koordinatı. |
| y | double | y koordinatı. |
| z | double | z koordinatı. |
| w | double | Genişlik. |

### Vector4() {#Vector4--}
```
public Vector4()
```


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

### add(Vector4 lhs, Vector4 rhs) {#add-com.aspose.threed.Vector4-com.aspose.threed.Vector4-}
```
public static Vector4 add(Vector4 lhs, Vector4 rhs)
```


+ operatörü için aşırı yükleme

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| lhs | [Vector4](../../com.aspose.threed/vector4) | Sol vektör |
| rhs | [Vector4](../../com.aspose.threed/vector4) | Sağ vektör |

**Returns:**
[Vector4](../../com.aspose.threed/vector4) - Result vector
### clone() {#clone--}
```
public Vector4 clone()
```


Mevcut örneği kopyala

**Returns:**
[Vector4](../../com.aspose.threed/vector4)
### compareTo(Vector4 other) {#compareTo-com.aspose.threed.Vector4-}
```
public int compareTo(Vector4 other)
```


Mevcut vektörü başka bir örnek ile karşılaştırın.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| other | [Vector4](../../com.aspose.threed/vector4) |  |

**Returns:**
int
### copyFrom(Vector4 src) {#copyFrom-com.aspose.threed.Vector4-}
```
public void copyFrom(Vector4 src)
```




**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| src | [Vector4](../../com.aspose.threed/vector4) |  |

### create(Vector4 v) {#create-com.aspose.threed.Vector4-}
```
public static FVector4 create(Vector4 v)
```


Vector4'ü FVector4'e dönüştürmek için açık dönüşüm operatörü

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| v | [Vector4](../../com.aspose.threed/vector4) |  |

**Returns:**
[FVector4](../../com.aspose.threed/fvector4)
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


İki vektörün eşit olup olmadığını kontrol et

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| obj | java.lang.Object |  |

**Returns:**
boolean
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### hashCode() {#hashCode--}
```
public int hashCode()
```


Bu vektörün karma kodunu alır

**Returns:**
int
### mul(Vector4 lhs, Vector4 rhs) {#mul-com.aspose.threed.Vector4-com.aspose.threed.Vector4-}
```
public static Vector4 mul(Vector4 lhs, Vector4 rhs)
```


\* operatörü için aşırı yükleme

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| lhs | [Vector4](../../com.aspose.threed/vector4) | Sol vektör |
| rhs | [Vector4](../../com.aspose.threed/vector4) | Sağ vektör |

**Returns:**
[Vector4](../../com.aspose.threed/vector4) - Result vector
### mul(Vector4 lhs, double rhs) {#mul-com.aspose.threed.Vector4-double-}
```
public static Vector4 mul(Vector4 lhs, double rhs)
```


\* operatörü için aşırı yükleme

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| lhs | [Vector4](../../com.aspose.threed/vector4) | Sol vektör |
| rhs | double | Sağ çift değeri |

**Returns:**
[Vector4](../../com.aspose.threed/vector4) - Result vector
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### set(double newX, double newY, double newZ) {#set-double-double-double-}
```
public void set(double newX, double newY, double newZ)
```


Vektörün xyz bileşenlerini bir anda ayarlar, w 1 olarak ayarlanacak

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| newX | double | Yeni X bileşeni. |
| newY | double | Yeni Y bileşeni. |
| newZ | double | Yeni Z bileşeni. |

### set(double newX, double newY, double newZ, double newW) {#set-double-double-double-double-}
```
public void set(double newX, double newY, double newZ, double newW)
```


Vektörün tüm bileşenlerini bir anda ayarlar

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| newX | double | Yeni X bileşeni. |
| newY | double | Yeni Y bileşeni. |
| newZ | double | Yeni Z bileşeni. |
| newW | double | Yeni W bileşeni. |

### sub(Vector4 lhs, Vector4 rhs) {#sub-com.aspose.threed.Vector4-com.aspose.threed.Vector4-}
```
public static Vector4 sub(Vector4 lhs, Vector4 rhs)
```


- (eksi) için operatör aşırı yüklemesi

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| lhs | [Vector4](../../com.aspose.threed/vector4) | Sol vektör |
| rhs | [Vector4](../../com.aspose.threed/vector4) | Sağ vektör |

**Returns:**
[Vector4](../../com.aspose.threed/vector4) - Result vector
### toString() {#toString--}
```
public String toString()
```


Geçerli [Vector4](../../com.aspose.threed/vector4) nesnesini temsil eden bir java.lang.String döndürür.

**Returns:**
java.lang.String - Geçerli [Vector4](../../com.aspose.threed/vector4) öğesini temsil eden bir java.lang.String.
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


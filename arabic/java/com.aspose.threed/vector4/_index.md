---
title: "Vector4"
second_title: "مرجع API لـ Aspose.3D for Java"
description: "متجه ذو أربعة مكوّنات."
type: docs
weight: 203
url: /ar/java/com.aspose.threed/vector4/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.lang.Comparable, com.aspose.threed.Struct, java.io.Serializable
```
public final class Vector4 implements Comparable<Vector4>, Struct<Vector4>, Serializable
```

متجه ذو أربعة مكوّنات.
## المنشئات

| منشئ | الوصف |
| --- | --- |
| [Vector4(Vector3 vec, double w)](#Vector4-com.aspose.threed.Vector3-double-) | ينشئ مثالا جديدًا من البنية [Vector4](../../com.aspose.threed/vector4). |
| [Vector4(Vector3 vec)](#Vector4-com.aspose.threed.Vector3-) | ينشئ مثالا جديدًا من البنية [Vector4](../../com.aspose.threed/vector4). |
| [Vector4(FVector4 vec)](#Vector4-com.aspose.threed.FVector4-) | ينشئ مثالا جديدًا من البنية [Vector4](../../com.aspose.threed/vector4). |
| [Vector4(double x, double y, double z)](#Vector4-double-double-double-) | ينشئ مثالا جديدًا من البنية [Vector4](../../com.aspose.threed/vector4). |
| [Vector4(double x, double y, double z, double w)](#Vector4-double-double-double-double-) | ينشئ مثالا جديدًا من البنية [Vector4](../../com.aspose.threed/vector4). |
| [Vector4()](#Vector4--) |  |
## الحقول

| حقل | الوصف |
| --- | --- |
| [w](#w) | المكوّن w. |
| [x](#x) | المكوّن x. |
| [y](#y) | المكوّن y. |
| [z](#z) | المكوّن z. |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [add(Vector4 lhs, Vector4 rhs)](#add-com.aspose.threed.Vector4-com.aspose.threed.Vector4-) | إعادة تعريف المشغل لـ + |
| [clone()](#clone--) |  |
| [compareTo(Vector4 other)](#compareTo-com.aspose.threed.Vector4-) | قارن المتجه الحالي بمثيل آخر. |
| [copyFrom(Vector4 src)](#copyFrom-com.aspose.threed.Vector4-) |  |
| [create(Vector4 v)](#create-com.aspose.threed.Vector4-) | عامل تحويل صريح لتحويل Vector4 إلى FVector4 |
| [equals(Object obj)](#equals-java.lang.Object-) | تحقق مما إذا كان المتجهان متساويين |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) | يحصل على رمز التجزئة لهذا المتجه |
| [mul(Vector4 lhs, Vector4 rhs)](#mul-com.aspose.threed.Vector4-com.aspose.threed.Vector4-) | إعادة تعريف المشغل لـ \* |
| [mul(Vector4 lhs, double rhs)](#mul-com.aspose.threed.Vector4-double-) | إعادة تعريف المشغل لـ \* |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [set(double newX, double newY, double newZ)](#set-double-double-double-) | يضبط مكونات المتجه xyz مرة واحدة، وسيتم ضبط w إلى 1 |
| [set(double newX, double newY, double newZ, double newW)](#set-double-double-double-double-) | يضبط جميع مكونات المتجه مرة واحدة |
| [sub(Vector4 lhs, Vector4 rhs)](#sub-com.aspose.threed.Vector4-com.aspose.threed.Vector4-) | تجاوز المشغل للـ - (ناقص) |
| [toString()](#toString--) | يرجع java.lang.String يمثل الـ [Vector4](../../com.aspose.threed/vector4) الحالي. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Vector4(Vector3 vec, double w) {#Vector4-com.aspose.threed.Vector3-double-}
```
public Vector4(Vector3 vec, double w)
```


ينشئ مثالا جديدًا من البنية [Vector4](../../com.aspose.threed/vector4).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| vec | [Vector3](../../com.aspose.threed/vector3) | متجه. |
| w | double | العرض. |

### Vector4(Vector3 vec) {#Vector4-com.aspose.threed.Vector3-}
```
public Vector4(Vector3 vec)
```


ينشئ مثالا جديدًا من البنية [Vector4](../../com.aspose.threed/vector4).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| vec | [Vector3](../../com.aspose.threed/vector3) | متجه. |

### Vector4(FVector4 vec) {#Vector4-com.aspose.threed.FVector4-}
```
public Vector4(FVector4 vec)
```


ينشئ مثالا جديدًا من البنية [Vector4](../../com.aspose.threed/vector4).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| vec | [FVector4](../../com.aspose.threed/fvector4) | متجه. |

### Vector4(double x, double y, double z) {#Vector4-double-double-double-}
```
public Vector4(double x, double y, double z)
```


ينشئ مثالا جديدًا من البنية [Vector4](../../com.aspose.threed/vector4).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| x | double | الإحداثي x. |
| y | double | الإحداثي y. |
| z | double | الإحداثي z. |

### Vector4(double x, double y, double z, double w) {#Vector4-double-double-double-double-}
```
public Vector4(double x, double y, double z, double w)
```


ينشئ مثالا جديدًا من البنية [Vector4](../../com.aspose.threed/vector4).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| x | double | الإحداثي x. |
| y | double | الإحداثي y. |
| z | double | الإحداثي z. |
| w | double | العرض. |

### Vector4() {#Vector4--}
```
public Vector4()
```


### w {#w}
```
public double w
```


المكوّن w.

### x {#x}
```
public double x
```


المكوّن x.

### y {#y}
```
public double y
```


المكوّن y.

### z {#z}
```
public double z
```


المكوّن z.

### add(Vector4 lhs, Vector4 rhs) {#add-com.aspose.threed.Vector4-com.aspose.threed.Vector4-}
```
public static Vector4 add(Vector4 lhs, Vector4 rhs)
```


إعادة تعريف المشغل لـ +

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| lhs | [Vector4](../../com.aspose.threed/vector4) | المتجه الأيسر |
| rhs | [Vector4](../../com.aspose.threed/vector4) | المتجه الأيمن |

**Returns:**
[Vector4](../../com.aspose.threed/vector4) - Result vector
### clone() {#clone--}
```
public Vector4 clone()
```


استنساخ النسخة الحالية

**Returns:**
[Vector4](../../com.aspose.threed/vector4)
### compareTo(Vector4 other) {#compareTo-com.aspose.threed.Vector4-}
```
public int compareTo(Vector4 other)
```


قارن المتجه الحالي بمثيل آخر.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| other | [Vector4](../../com.aspose.threed/vector4) |  |

**Returns:**
int
### copyFrom(Vector4 src) {#copyFrom-com.aspose.threed.Vector4-}
```
public void copyFrom(Vector4 src)
```




**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| src | [Vector4](../../com.aspose.threed/vector4) |  |

### create(Vector4 v) {#create-com.aspose.threed.Vector4-}
```
public static FVector4 create(Vector4 v)
```


عامل تحويل صريح لتحويل Vector4 إلى FVector4

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| v | [Vector4](../../com.aspose.threed/vector4) |  |

**Returns:**
[FVector4](../../com.aspose.threed/fvector4)
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


تحقق مما إذا كان المتجهان متساويين

**Parameters:**
| معامل | نوع | الوصف |
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


يحصل على رمز التجزئة لهذا المتجه

**Returns:**
int
### mul(Vector4 lhs, Vector4 rhs) {#mul-com.aspose.threed.Vector4-com.aspose.threed.Vector4-}
```
public static Vector4 mul(Vector4 lhs, Vector4 rhs)
```


إعادة تعريف المشغل لـ \*

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| lhs | [Vector4](../../com.aspose.threed/vector4) | المتجه الأيسر |
| rhs | [Vector4](../../com.aspose.threed/vector4) | المتجه الأيمن |

**Returns:**
[Vector4](../../com.aspose.threed/vector4) - Result vector
### mul(Vector4 lhs, double rhs) {#mul-com.aspose.threed.Vector4-double-}
```
public static Vector4 mul(Vector4 lhs, double rhs)
```


إعادة تعريف المشغل لـ \*

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| lhs | [Vector4](../../com.aspose.threed/vector4) | المتجه الأيسر |
| rhs | double | القيمة المزدوجة اليمنى |

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


يضبط مكونات المتجه xyz مرة واحدة، وسيتم ضبط w إلى 1

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| newX | double | المكوّن X الجديد. |
| newY | double | المكوّن Y الجديد. |
| newZ | double | المكوّن Z الجديد. |

### set(double newX, double newY, double newZ, double newW) {#set-double-double-double-double-}
```
public void set(double newX, double newY, double newZ, double newW)
```


يضبط جميع مكونات المتجه مرة واحدة

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| newX | double | المكوّن X الجديد. |
| newY | double | المكوّن Y الجديد. |
| newZ | double | المكوّن Z الجديد. |
| newW | double | المكوّن الجديد W. |

### sub(Vector4 lhs, Vector4 rhs) {#sub-com.aspose.threed.Vector4-com.aspose.threed.Vector4-}
```
public static Vector4 sub(Vector4 lhs, Vector4 rhs)
```


تجاوز المشغل للـ - (ناقص)

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| lhs | [Vector4](../../com.aspose.threed/vector4) | المتجه الأيسر |
| rhs | [Vector4](../../com.aspose.threed/vector4) | المتجه الأيمن |

**Returns:**
[Vector4](../../com.aspose.threed/vector4) - Result vector
### toString() {#toString--}
```
public String toString()
```


يرجع java.lang.String يمثل الـ [Vector4](../../com.aspose.threed/vector4) الحالي.

**Returns:**
java.lang.String - java.lang.String الذي يمثل الـ [Vector4](../../com.aspose.threed/vector4) الحالي.
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


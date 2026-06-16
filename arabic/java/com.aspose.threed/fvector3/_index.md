---
title: "FVector3"
second_title: "مرجع API لـ Aspose.3D for Java"
description: "متجه float مكوّن من ثلاثة عناصر."
type: docs
weight: 60
url: /ar/java/com.aspose.threed/fvector3/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.threed.Struct, java.io.Serializable
```
public final class FVector3 implements Struct<FVector3>, Serializable
```

متجه float مكوّن من ثلاثة عناصر.
## المنشئات

| منشئ | الوصف |
| --- | --- |
| [FVector3(float x, float y, float z)](#FVector3-float-float-float-) | ينشئ نسخة جديدة من [FVector3](../../com.aspose.threed/fvector3). |
| [FVector3(Vector3 vec)](#FVector3-com.aspose.threed.Vector3-) | ينشئ نسخة جديدة من [FVector3](../../com.aspose.threed/fvector3). |
| [FVector3(Vector4 vec)](#FVector3-com.aspose.threed.Vector4-) | ينشئ مثيلًا جديدًا من [FVector4](../../com.aspose.threed/fvector4). |
| [FVector3()](#FVector3--) |  |
## الحقول

| حقل | الوصف |
| --- | --- |
| [x](#x) | المكوّن x. |
| [y](#y) | المكوّن y. |
| [z](#z) | المكوّن y. |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [add(FVector3 a, FVector3 b)](#add-com.aspose.threed.FVector3-com.aspose.threed.FVector3-) | \+ تحميل المشغل |
| [clone()](#clone--) |  |
| [copyFrom(FVector3 src)](#copyFrom-com.aspose.threed.FVector3-) |  |
| [create(FVector3 v)](#create-com.aspose.threed.FVector3-) | عامل تحويل صريح لتحويل FVector3 إلى Vector3 |
| [cross(FVector3 rhs)](#cross-com.aspose.threed.FVector3-) | حاصل الضرب المتقاطع لمتجهين. |
| [equals(Object obj)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getOne()](#getOne--) | متجه مقياس الوحدة حيث جميع المكونات تساوي 1 |
| [getZero()](#getZero--) | متجه الصفر. |
| [hashCode()](#hashCode--) |  |
| [mul(FVector3 a, float b)](#mul-com.aspose.threed.FVector3-float-) | \* تحميل المشغل |
| [negative(FVector3 a)](#negative-com.aspose.threed.FVector3-) | \- تحميل المشغل |
| [normalize()](#normalize--) | يقوم بتطبيع هذه الحالة. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [sub(FVector3 a, FVector3 b)](#sub-com.aspose.threed.FVector3-com.aspose.threed.FVector3-) | \- تحميل المشغل |
| [toString()](#toString--) | يرجع سلسلة تمثل [FVector3](../../com.aspose.threed/fvector3) |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### FVector3(float x, float y, float z) {#FVector3-float-float-float-}
```
public FVector3(float x, float y, float z)
```


ينشئ نسخة جديدة من [FVector3](../../com.aspose.threed/fvector3).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| x | float | المكوّن X للمتجه |
| y | float | المكوّن Y للمتجه |
| z | float | المكوّن Z للمتجه |

### FVector3(Vector3 vec) {#FVector3-com.aspose.threed.Vector3-}
```
public FVector3(Vector3 vec)
```


ينشئ نسخة جديدة من [FVector3](../../com.aspose.threed/fvector3).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| vec | [Vector3](../../com.aspose.threed/vector3) | Vector3 بنوع double |

### FVector3(Vector4 vec) {#FVector3-com.aspose.threed.Vector4-}
```
public FVector3(Vector4 vec)
```


ينشئ مثيلًا جديدًا من [FVector4](../../com.aspose.threed/fvector4).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| vec | [Vector4](../../com.aspose.threed/vector4) | Vector4 بنوع double |

### FVector3() {#FVector3--}
```
public FVector3()
```


### x {#x}
```
public float x
```


المكوّن x.

### y {#y}
```
public float y
```


المكوّن y.

### z {#z}
```
public float z
```


المكوّن y.

### add(FVector3 a, FVector3 b) {#add-com.aspose.threed.FVector3-com.aspose.threed.FVector3-}
```
public static FVector3 add(FVector3 a, FVector3 b)
```


\+ تحميل المشغل

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| a | [FVector3](../../com.aspose.threed/fvector3) | المتجه الأول |
| b | [FVector3](../../com.aspose.threed/fvector3) | المتجه الثاني |

**Returns:**
[FVector3](../../com.aspose.threed/fvector3)
### clone() {#clone--}
```
public FVector3 clone()
```


استنساخ النسخة الحالية

**Returns:**
[FVector3](../../com.aspose.threed/fvector3)
### copyFrom(FVector3 src) {#copyFrom-com.aspose.threed.FVector3-}
```
public void copyFrom(FVector3 src)
```




**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| src | [FVector3](../../com.aspose.threed/fvector3) |  |

### create(FVector3 v) {#create-com.aspose.threed.FVector3-}
```
public static Vector3 create(FVector3 v)
```


عامل تحويل صريح لتحويل FVector3 إلى Vector3

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| v | [FVector3](../../com.aspose.threed/fvector3) | Vector3 بنوع float |

**Returns:**
[Vector3](../../com.aspose.threed/vector3)
### cross(FVector3 rhs) {#cross-com.aspose.threed.FVector3-}
```
public FVector3 cross(FVector3 rhs)
```


حاصل الضرب المتقاطع لمتجهين.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| rhs | [FVector3](../../com.aspose.threed/fvector3) | قيمة الطرف الأيمن. |

**Returns:**
[FVector3](../../com.aspose.threed/fvector3) - Cross product of two [FVector3](../../com.aspose.threed/fvector3)s.
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```




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
### getOne() {#getOne--}
```
public static FVector3 getOne()
```


متجه مقياس الوحدة حيث جميع المكونات تساوي 1

**Returns:**
[FVector3](../../com.aspose.threed/fvector3) - The unit scale vector with all components are all 1
### getZero() {#getZero--}
```
public static FVector3 getZero()
```


متجه الصفر.

**Returns:**
[FVector3](../../com.aspose.threed/fvector3) - The Zero vector.
### hashCode() {#hashCode--}
```
public int hashCode()
```




**Returns:**
int
### mul(FVector3 a, float b) {#mul-com.aspose.threed.FVector3-float-}
```
public static FVector3 mul(FVector3 a, float b)
```


\* تحميل المشغل

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| a | [FVector3](../../com.aspose.threed/fvector3) | المتجه الأول |
| b | float | المتجه الثاني |

**Returns:**
[FVector3](../../com.aspose.threed/fvector3) - The product of two vectors
### negative(FVector3 a) {#negative-com.aspose.threed.FVector3-}
```
public static FVector3 negative(FVector3 a)
```


\- تحميل المشغل

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| a | [FVector3](../../com.aspose.threed/fvector3) | متجه الإدخال |

**Returns:**
[FVector3](../../com.aspose.threed/fvector3) - The negative vector
### normalize() {#normalize--}
```
public FVector3 normalize()
```


يقوم بتطبيع هذه الحالة.

**Returns:**
[FVector3](../../com.aspose.threed/fvector3) - Normalized vector.
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### sub(FVector3 a, FVector3 b) {#sub-com.aspose.threed.FVector3-com.aspose.threed.FVector3-}
```
public static FVector3 sub(FVector3 a, FVector3 b)
```


\- تحميل المشغل

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| a | [FVector3](../../com.aspose.threed/fvector3) | المتجه الأول |
| b | [FVector3](../../com.aspose.threed/fvector3) | المتجه الثاني |

**Returns:**
[FVector3](../../com.aspose.threed/fvector3) - The difference of two vectors
### toString() {#toString--}
```
public String toString()
```


يرجع سلسلة تمثل [FVector3](../../com.aspose.threed/fvector3)

**Returns:**
java.lang.String - تمثيل النص لهذا المتجه.
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


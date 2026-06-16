---
title: "Vector2"
second_title: "مرجع API لـ Aspose.3D for Java"
description: "متجه ذو مكوّنين."
type: docs
weight: 201
url: /ar/java/com.aspose.threed/vector2/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.lang.Comparable, com.aspose.threed.Struct, java.io.Serializable
```
public final class Vector2 implements Comparable<Vector2>, Struct<Vector2>, Serializable
```

متجه ذو مكوّنين.
## المنشئات

| منشئ | الوصف |
| --- | --- |
| [Vector2(double s)](#Vector2-double-) | إنشاء نسخة جديدة من بنية [Vector2](../../com.aspose.threed/vector2). |
| [Vector2(Vector3 s)](#Vector2-com.aspose.threed.Vector3-) | إنشاء نسخة جديدة من بنية [Vector2](../../com.aspose.threed/vector2). |
| [Vector2(FVector2 vec)](#Vector2-com.aspose.threed.FVector2-) | إنشاء نسخة جديدة من بنية [Vector2](../../com.aspose.threed/vector2). |
| [Vector2(double x, double y)](#Vector2-double-double-) | إنشاء نسخة جديدة من بنية [Vector2](../../com.aspose.threed/vector2). |
| [Vector2()](#Vector2--) |  |
## الحقول

| حقل | الوصف |
| --- | --- |
| [x](#x) | المكوّن x. |
| [y](#y) | المكوّن y. |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [add(Vector2 lhs, Vector2 rhs)](#add-com.aspose.threed.Vector2-com.aspose.threed.Vector2-) | عامل الجمع لـ Vector2 |
| [clone()](#clone--) |  |
| [compareTo(Vector2 other)](#compareTo-com.aspose.threed.Vector2-) | قارن المتجه الحالي بمثيل آخر. |
| [copyFrom(Vector2 src)](#copyFrom-com.aspose.threed.Vector2-) |  |
| [create(Vector2 v)](#create-com.aspose.threed.Vector2-) | عامل التحويل الصريح لتحويل Vector2 إلى FVector2 |
| [cross(Vector2 v)](#cross-com.aspose.threed.Vector2-) | حاصل الضرب المتقاطع لمتجهين. |
| [div(Vector2 lhs, double rhs)](#div-com.aspose.threed.Vector2-double-) | عامل القسمة لـ Vector2 |
| [dot(Vector2 rhs)](#dot-com.aspose.threed.Vector2-) | يحصل على حاصل الضرب النقطي لمتجهين. |
| [equals(Vector2 rhs)](#equals-com.aspose.threed.Vector2-) | تحقق مما إذا كان متجهين vector2 متساويين |
| [equals(Object obj)](#equals-java.lang.Object-) | تحقق مما إذا كان متجهين vector2 متساويين |
| [getClass()](#getClass--) |  |
| [getLength()](#getLength--) | يحصل على الطول. |
| [getU()](#getU--) | يحصل على المكوّن U إذا تم استخدام [Vector2](../../com.aspose.threed/vector2) كإحداثي تخطيط. |
| [getV()](#getV--) | يحصل على المكوّن V إذا تم استخدام [Vector2](../../com.aspose.threed/vector2) كإحداثي تخطيط. |
| [hashCode()](#hashCode--) | يحصل على قيمة التجزئة لـ Vector2 |
| [mul(Vector2 lhs, double rhs)](#mul-com.aspose.threed.Vector2-double-) | عامل الضرب لـ Vector2 |
| [mul(double lhs, Vector2 rhs)](#mul-double-com.aspose.threed.Vector2-) | عامل الضرب لـ Vector2 |
| [normalize()](#normalize--) | يقوم بتطبيع هذه الحالة. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [op_eq(Vector2 lhs, Vector2 rhs)](#op-eq-com.aspose.threed.Vector2-com.aspose.threed.Vector2-) | عامل المساواة لـ Vector2 |
| [op_ne(Vector2 lhs, Vector2 rhs)](#op-ne-com.aspose.threed.Vector2-com.aspose.threed.Vector2-) | عامل عدم المساواة لـ Vector2 |
| [setU(double value)](#setU-double-) | يضبط المكوّن U إذا تم استخدام [Vector2](../../com.aspose.threed/vector2) كإحداثي تخطيط. |
| [setV(double value)](#setV-double-) | يضبط المكوّن V إذا تم استخدام [Vector2](../../com.aspose.threed/vector2) كإحداثي تخطيط. |
| [sub(Vector2 lhs, Vector2 rhs)](#sub-com.aspose.threed.Vector2-com.aspose.threed.Vector2-) | عامل الطرح لـ Vector2 |
| [toString()](#toString--) | يرجع java.lang.String يمثل الـ [Vector2](../../com.aspose.threed/vector2) الحالي. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Vector2(double s) {#Vector2-double-}
```
public Vector2(double s)
```


إنشاء نسخة جديدة من بنية [Vector2](../../com.aspose.threed/vector2).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| s | double | S. |

### Vector2(Vector3 s) {#Vector2-com.aspose.threed.Vector3-}
```
public Vector2(Vector3 s)
```


إنشاء نسخة جديدة من بنية [Vector2](../../com.aspose.threed/vector2).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| s | [Vector3](../../com.aspose.threed/vector3) | S. |

### Vector2(FVector2 vec) {#Vector2-com.aspose.threed.FVector2-}
```
public Vector2(FVector2 vec)
```


إنشاء نسخة جديدة من بنية [Vector2](../../com.aspose.threed/vector2).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| vec | [FVector2](../../com.aspose.threed/fvector2) | متجه بنوع float. |

### Vector2(double x, double y) {#Vector2-double-double-}
```
public Vector2(double x, double y)
```


إنشاء نسخة جديدة من بنية [Vector2](../../com.aspose.threed/vector2).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| x | double | الإحداثي x. |
| y | double | الإحداثي y. |

### Vector2() {#Vector2--}
```
public Vector2()
```


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

### add(Vector2 lhs, Vector2 rhs) {#add-com.aspose.threed.Vector2-com.aspose.threed.Vector2-}
```
public static Vector2 add(Vector2 lhs, Vector2 rhs)
```


عامل الجمع لـ Vector2

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| lhs | [Vector2](../../com.aspose.threed/vector2) | قيمة الطرف الأيسر. |
| rhs | [Vector2](../../com.aspose.threed/vector2) | قيمة الطرف الأيمن. |

**Returns:**
[Vector2](../../com.aspose.threed/vector2) - The result of addition.
### clone() {#clone--}
```
public Vector2 clone()
```


استنساخ النسخة الحالية

**Returns:**
[Vector2](../../com.aspose.threed/vector2)
### compareTo(Vector2 other) {#compareTo-com.aspose.threed.Vector2-}
```
public int compareTo(Vector2 other)
```


قارن المتجه الحالي بمثيل آخر.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| other | [Vector2](../../com.aspose.threed/vector2) |  |

**Returns:**
int
### copyFrom(Vector2 src) {#copyFrom-com.aspose.threed.Vector2-}
```
public void copyFrom(Vector2 src)
```




**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| src | [Vector2](../../com.aspose.threed/vector2) |  |

### create(Vector2 v) {#create-com.aspose.threed.Vector2-}
```
public static FVector2 create(Vector2 v)
```


عامل التحويل الصريح لتحويل Vector2 إلى FVector2

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| v | [Vector2](../../com.aspose.threed/vector2) |  |

**Returns:**
[FVector2](../../com.aspose.threed/fvector2)
### cross(Vector2 v) {#cross-com.aspose.threed.Vector2-}
```
public double cross(Vector2 v)
```


حاصل الضرب المتقاطع لمتجهين.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| v | [Vector2](../../com.aspose.threed/vector2) |  |

**Returns:**
double
### div(Vector2 lhs, double rhs) {#div-com.aspose.threed.Vector2-double-}
```
public static Vector2 div(Vector2 lhs, double rhs)
```


عامل القسمة لـ Vector2

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| lhs | [Vector2](../../com.aspose.threed/vector2) | قيمة الطرف الأيسر. |
| rhs | double | قيمة الطرف الأيمن. |

**Returns:**
[Vector2](../../com.aspose.threed/vector2) - The result of division.
### dot(Vector2 rhs) {#dot-com.aspose.threed.Vector2-}
```
public double dot(Vector2 rhs)
```


يحصل على حاصل الضرب النقطي لمتجهين.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| rhs | [Vector2](../../com.aspose.threed/vector2) | قيمة الطرف الأيمن. |

**Returns:**
double - حاصل الضرب النقطي للمتجهين.
### equals(Vector2 rhs) {#equals-com.aspose.threed.Vector2-}
```
public boolean equals(Vector2 rhs)
```


تحقق مما إذا كان متجهين vector2 متساويين

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| rhs | [Vector2](../../com.aspose.threed/vector2) | قيمة الطرف الأيمن. |

**Returns:**
boolean - صحيح إذا كانت جميع المكوّنات متساوية تمامًا.
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


تحقق مما إذا كان متجهين vector2 متساويين

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| obj | java.lang.Object | الكائن للمقارنة. |

**Returns:**
boolean - صحيح إذا كانت جميع المكوّنات متساوية تمامًا.
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


يحصل على الطول.

**Returns:**
double - الطول.
### getU() {#getU--}
```
public double getU()
```


يحصل على المكوّن U إذا تم استخدام [Vector2](../../com.aspose.threed/vector2) كإحداثي تخطيط. وهو مرادف للمكوّن x.

**Returns:**
double - المكوّن U إذا تم استخدام [Vector2](../../com.aspose.threed/vector2) كإحداثي تخطيط. وهو مرادف للمكوّن x.
### getV() {#getV--}
```
public double getV()
```


يحصل على المكوّن V إذا تم استخدام [Vector2](../../com.aspose.threed/vector2) كإحداثي تخطيط. وهو مرادف للمكوّن y.

**Returns:**
double - المكوّن V إذا تم استخدام [Vector2](../../com.aspose.threed/vector2) كإحداثي تخطيط. وهو مرادف للمكوّن y.
### hashCode() {#hashCode--}
```
public int hashCode()
```


يحصل على قيمة التجزئة لـ Vector2

**Returns:**
int - رمز التجزئة للـ [Vector2](../../com.aspose.threed/vector2)
### mul(Vector2 lhs, double rhs) {#mul-com.aspose.threed.Vector2-double-}
```
public static Vector2 mul(Vector2 lhs, double rhs)
```


عامل الضرب لـ Vector2

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| lhs | [Vector2](../../com.aspose.threed/vector2) | قيمة الطرف الأيسر. |
| rhs | double | قيمة الطرف الأيمن. |

**Returns:**
[Vector2](../../com.aspose.threed/vector2) - The result of multiply.
### mul(double lhs, Vector2 rhs) {#mul-double-com.aspose.threed.Vector2-}
```
public static Vector2 mul(double lhs, Vector2 rhs)
```


عامل الضرب لـ Vector2

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| lhs | double | قيمة الطرف الأيسر. |
| rhs | [Vector2](../../com.aspose.threed/vector2) | قيمة الطرف الأيمن. |

**Returns:**
[Vector2](../../com.aspose.threed/vector2) - The result of multiply.
### normalize() {#normalize--}
```
public Vector2 normalize()
```


يقوم بتطبيع هذه الحالة.

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


عامل المساواة لـ Vector2

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| lhs | [Vector2](../../com.aspose.threed/vector2) | قيمة الطرف الأيسر. |
| rhs | [Vector2](../../com.aspose.threed/vector2) | قيمة الطرف الأيمن. |

**Returns:**
boolean - صحيح إذا كانت جميع المكوّنات متساوية تمامًا.
### op_ne(Vector2 lhs, Vector2 rhs) {#op-ne-com.aspose.threed.Vector2-com.aspose.threed.Vector2-}
```
public static boolean op_ne(Vector2 lhs, Vector2 rhs)
```


عامل عدم المساواة لـ Vector2

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| lhs | [Vector2](../../com.aspose.threed/vector2) | قيمة الطرف الأيسر. |
| rhs | [Vector2](../../com.aspose.threed/vector2) | قيمة الطرف الأيمن. |

**Returns:**
boolean - صحيح إذا كان المتجهان غير متساويين.
### setU(double value) {#setU-double-}
```
public void setU(double value)
```


يضبط المكوّن U إذا تم استخدام [Vector2](../../com.aspose.threed/vector2) كإحداثي تخطيط. وهو مرادف للمكوّن x.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | double | القيمة الجديدة |

### setV(double value) {#setV-double-}
```
public void setV(double value)
```


يضبط المكوّن V إذا تم استخدام [Vector2](../../com.aspose.threed/vector2) كإحداثي تخطيط. وهو مرادف للمكوّن y.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | double | القيمة الجديدة |

### sub(Vector2 lhs, Vector2 rhs) {#sub-com.aspose.threed.Vector2-com.aspose.threed.Vector2-}
```
public static Vector2 sub(Vector2 lhs, Vector2 rhs)
```


عامل الطرح لـ Vector2

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| lhs | [Vector2](../../com.aspose.threed/vector2) | قيمة الطرف الأيسر. |
| rhs | [Vector2](../../com.aspose.threed/vector2) | قيمة الطرف الأيمن. |

**Returns:**
[Vector2](../../com.aspose.threed/vector2) - The result of substraction.
### toString() {#toString--}
```
public String toString()
```


يرجع java.lang.String يمثل الـ [Vector2](../../com.aspose.threed/vector2) الحالي.

**Returns:**
java.lang.String - java.lang.String يمثل الـ [Vector2](../../com.aspose.threed/vector2) الحالي.
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


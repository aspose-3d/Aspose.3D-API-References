---
title: "Vector3"
second_title: "مرجع API لـ Aspose.3D for Java"
description: "متجه ذو ثلاثة مكوّنات."
type: docs
weight: 202
url: /ar/java/com.aspose.threed/vector3/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.lang.Comparable, com.aspose.threed.Struct, java.io.Serializable
```
public final class Vector3 implements Comparable<Vector3>, Struct<Vector3>, Serializable
```

متجه ذو ثلاثة مكوّنات.
## المنشئات

| منشئ | الوصف |
| --- | --- |
| [Vector3(double x, double y, double z)](#Vector3-double-double-double-) | يُنشئ مثلاً جديدًا من بنية [Vector3](../../com.aspose.threed/vector3). |
| [Vector3(FVector3 vec)](#Vector3-com.aspose.threed.FVector3-) | يُنشئ مثلاً جديدًا من بنية [Vector3](../../com.aspose.threed/vector3). |
| [Vector3(double v)](#Vector3-double-) | يُنشئ مثلاً جديدًا من بنية [Vector3](../../com.aspose.threed/vector3). |
| [Vector3(Vector4 vec4)](#Vector3-com.aspose.threed.Vector4-) | يُنشئ مثلاً جديدًا من بنية [Vector3](../../com.aspose.threed/vector3). |
| [Vector3()](#Vector3--) |  |
## الحقول

| حقل | الوصف |
| --- | --- |
| [x](#x) | المكوّن x. |
| [y](#y) | المكوّن y. |
| [z](#z) | المكوّن z. |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [add(Vector3 lhs, Vector3 rhs)](#add-com.aspose.threed.Vector3-com.aspose.threed.Vector3-) | إعادة تعريف المشغل لـ + |
| [angleBetween(Vector3 dir)](#angleBetween-com.aspose.threed.Vector3-) | احسب الزاوية الداخلية بين اتجاهين. يمكن أن يكون الاتجاهان متجهات غير مُعَدَّلة. |
| [angleBetween(Vector3 dir, Vector3 up)](#angleBetween-com.aspose.threed.Vector3-com.aspose.threed.Vector3-) | احسب الزاوية الداخلية بين اتجاهين. يمكن أن يكون الاتجاهان متجهات غير مُعَدَّلة. |
| [clone()](#clone--) |  |
| [compareTo(Vector3 other)](#compareTo-com.aspose.threed.Vector3-) | قارن المتجه الحالي بمثيل آخر. |
| [copyFrom(Vector3 src)](#copyFrom-com.aspose.threed.Vector3-) |  |
| [cos()](#cos--) | يحسب جيب التمام لكل مكوّن. |
| [create(Vector3 v)](#create-com.aspose.threed.Vector3-) | مشغل تحويل صريح لتحويل Vector3 إلى FVector3 |
| [cross(Vector3 rhs)](#cross-com.aspose.threed.Vector3-) | حاصل الضرب المتقاطع لمتجهين. |
| [div(Vector3 lhs, Vector3 rhs)](#div-com.aspose.threed.Vector3-com.aspose.threed.Vector3-) | إعادة تعريف المشغل لـ / |
| [div(Vector3 lhs, double rhs)](#div-com.aspose.threed.Vector3-double-) | إعادة تعريف المشغل لـ / |
| [dot(Vector3 rhs)](#dot-com.aspose.threed.Vector3-) | يحصل على حاصل الضرب النقطي لمتجهين. |
| [equals(Object obj)](#equals-java.lang.Object-) | تحقق مما إذا كان متجهان من النوع vector3 متساويين. |
| [get(int idx)](#get-int-) | يحصل على مكوّن المتجه حسب الفهرس. |
| [getClass()](#getClass--) |  |
| [getLength()](#getLength--) | يحصل على طول هذا المتجه. |
| [getLength2()](#getLength2--) | يحصل على مربع الطول. |
| [getOne()](#getOne--) | يحصل على المتجه الوحدوي (1, 1, 1) |
| [getUnitX()](#getUnitX--) | يحصل على المتجه الوحدوي (1, 0, 0) |
| [getUnitY()](#getUnitY--) | يحصل على المتجه الوحدوي (0, 1, 0) |
| [getUnitZ()](#getUnitZ--) | يحصل على المتجه الوحدوي (0, 0, 1) |
| [getZero()](#getZero--) | يحصل على المتجه الوحدوي (0, 0, 0) |
| [hashCode()](#hashCode--) | يحصل على رمز التجزئة لـ Vector3 |
| [mul(Vector3 lhs, Vector3 rhs)](#mul-com.aspose.threed.Vector3-com.aspose.threed.Vector3-) | إعادة تعريف المشغل لـ \* |
| [mul(Vector3 lhs, double rhs)](#mul-com.aspose.threed.Vector3-double-) | إعادة تعريف المشغل لـ \* |
| [mul(double lhs, Vector3 rhs)](#mul-double-com.aspose.threed.Vector3-) | إعادة تعريف المشغل لـ \* |
| [negative(Vector3 v)](#negative-com.aspose.threed.Vector3-) | إعادة تعريف المشغل لـ - |
| [normalize()](#normalize--) | يقوم بتطبيع هذه الحالة. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [op_eq(Vector3 lhs, Vector3 rhs)](#op-eq-com.aspose.threed.Vector3-com.aspose.threed.Vector3-) | عامل المساواة لـ Vector3 |
| [op_ne(Vector3 lhs, Vector3 rhs)](#op-ne-com.aspose.threed.Vector3-com.aspose.threed.Vector3-) | عامل عدم المساواة لـ Vector3 |
| [set(double newX, double newY, double newZ)](#set-double-double-double-) | يضبط مكوّنات x/y/z في استدعاء واحد. |
| [set(int idx, double value)](#set-int-double-) | يضبط مكوّن المتجه حسب الفهرس. |
| [sin()](#sin--) | يحسب جيب الزاوية لكل مكوّن |
| [sub(Vector3 lhs, Vector3 rhs)](#sub-com.aspose.threed.Vector3-com.aspose.threed.Vector3-) | تجاوز المشغل للـ - (ناقص) |
| [toString()](#toString--) | يعيد java.lang.String يمثل الـ [Vector3](../../com.aspose.threed/vector3) الحالي. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Vector3(double x, double y, double z) {#Vector3-double-double-double-}
```
public Vector3(double x, double y, double z)
```


يُنشئ مثلاً جديدًا من بنية [Vector3](../../com.aspose.threed/vector3).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| x | double | الإحداثي x. |
| y | double | الإحداثي y. |
| z | double | الإحداثي z. |

### Vector3(FVector3 vec) {#Vector3-com.aspose.threed.FVector3-}
```
public Vector3(FVector3 vec)
```


يُنشئ مثلاً جديدًا من بنية [Vector3](../../com.aspose.threed/vector3).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| vec | [FVector3](../../com.aspose.threed/fvector3) | الإحداثي x. |

### Vector3(double v) {#Vector3-double-}
```
public Vector3(double v)
```


يُنشئ مثلاً جديدًا من بنية [Vector3](../../com.aspose.threed/vector3).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| v | double | V. |

### Vector3(Vector4 vec4) {#Vector3-com.aspose.threed.Vector4-}
```
public Vector3(Vector4 vec4)
```


يُنشئ مثلاً جديدًا من بنية [Vector3](../../com.aspose.threed/vector3).

**Parameters:**
| معامل | نوع | الوصف |
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

### add(Vector3 lhs, Vector3 rhs) {#add-com.aspose.threed.Vector3-com.aspose.threed.Vector3-}
```
public static Vector3 add(Vector3 lhs, Vector3 rhs)
```


إعادة تعريف المشغل لـ +

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| lhs | [Vector3](../../com.aspose.threed/vector3) | المتجه الأيسر |
| rhs | [Vector3](../../com.aspose.threed/vector3) | المتجه الأيمن |

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - Result vector
### angleBetween(Vector3 dir) {#angleBetween-com.aspose.threed.Vector3-}
```
public double angleBetween(Vector3 dir)
```


احسب الزاوية الداخلية بين اتجاهين. يمكن أن يكون الاتجاهان متجهات غير مُعَدَّلة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| dir | [Vector3](../../com.aspose.threed/vector3) | متجه الاتجاه للمقارنة معه |

**Returns:**
double - الزاوية الداخلية بالراديان
### angleBetween(Vector3 dir, Vector3 up) {#angleBetween-com.aspose.threed.Vector3-com.aspose.threed.Vector3-}
```
public double angleBetween(Vector3 dir, Vector3 up)
```


احسب الزاوية الداخلية بين اتجاهين. يمكن أن يكون الاتجاهان متجهات غير مُعَدَّلة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| dir | [Vector3](../../com.aspose.threed/vector3) | متجه الاتجاه للمقارنة معه |
| up | [Vector3](../../com.aspose.threed/vector3) | متجه الصعود للسطح المشترك بين الاتجاهين |

**Returns:**
double - الزاوية الداخلية بالراديان
### clone() {#clone--}
```
public Vector3 clone()
```


استنساخ النسخة الحالية

**Returns:**
[Vector3](../../com.aspose.threed/vector3)
### compareTo(Vector3 other) {#compareTo-com.aspose.threed.Vector3-}
```
public int compareTo(Vector3 other)
```


قارن المتجه الحالي بمثيل آخر.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| other | [Vector3](../../com.aspose.threed/vector3) |  |

**Returns:**
int
### copyFrom(Vector3 src) {#copyFrom-com.aspose.threed.Vector3-}
```
public void copyFrom(Vector3 src)
```




**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| src | [Vector3](../../com.aspose.threed/vector3) |  |

### cos() {#cos--}
```
public Vector3 cos()
```


يحسب جيب التمام لكل مكوّن.

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - Calculated [Vector3](../../com.aspose.threed/vector3).
### create(Vector3 v) {#create-com.aspose.threed.Vector3-}
```
public static FVector3 create(Vector3 v)
```


مشغل تحويل صريح لتحويل Vector3 إلى FVector3

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| v | [Vector3](../../com.aspose.threed/vector3) |  |

**Returns:**
[FVector3](../../com.aspose.threed/fvector3)
### cross(Vector3 rhs) {#cross-com.aspose.threed.Vector3-}
```
public Vector3 cross(Vector3 rhs)
```


حاصل الضرب المتقاطع لمتجهين.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| rhs | [Vector3](../../com.aspose.threed/vector3) | قيمة الطرف الأيمن. |

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - Cross product of two [Vector3](../../com.aspose.threed/vector3)s.
### div(Vector3 lhs, Vector3 rhs) {#div-com.aspose.threed.Vector3-com.aspose.threed.Vector3-}
```
public static Vector3 div(Vector3 lhs, Vector3 rhs)
```


إعادة تعريف المشغل لـ /

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| lhs | [Vector3](../../com.aspose.threed/vector3) | المتجه الأيسر |
| rhs | [Vector3](../../com.aspose.threed/vector3) | المتجه الأيمن |

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - Result vector
### div(Vector3 lhs, double rhs) {#div-com.aspose.threed.Vector3-double-}
```
public static Vector3 div(Vector3 lhs, double rhs)
```


إعادة تعريف المشغل لـ /

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| lhs | [Vector3](../../com.aspose.threed/vector3) | المتجه الأيسر |
| rhs | double | القيمة المزدوجة اليمنى |

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - Result vector
### dot(Vector3 rhs) {#dot-com.aspose.threed.Vector3-}
```
public double dot(Vector3 rhs)
```


يحصل على حاصل الضرب النقطي لمتجهين.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| rhs | [Vector3](../../com.aspose.threed/vector3) | قيمة الطرف الأيمن. |

**Returns:**
double - حاصل الضرب النقطي للمتجهين.
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


تحقق مما إذا كان متجهان من النوع vector3 متساويين.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| obj | java.lang.Object | الكائن للتحقق من المساواة. |

**Returns:**
boolean - صحيح إذا كانت جميع المكوّنات متساوية تمامًا.
### get(int idx) {#get-int-}
```
public double get(int idx)
```


يحصل على مكوّن المتجه حسب الفهرس.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| idx | int |  |

**Returns:**
double - مكوّن المتجه حسب الفهرس.
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


يحصل على طول هذا المتجه.

**Returns:**
double - طول هذا المتجه.
### getLength2() {#getLength2--}
```
public double getLength2()
```


يحصل على مربع الطول.

**Returns:**
double - مربع الطول.
### getOne() {#getOne--}
```
public static Vector3 getOne()
```


يحصل على المتجه الوحدوي (1, 1, 1)

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - unit vector (1, 1, 1)
### getUnitX() {#getUnitX--}
```
public static Vector3 getUnitX()
```


يحصل على المتجه الوحدوي (1, 0, 0)

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - unit vector (1, 0, 0)
### getUnitY() {#getUnitY--}
```
public static Vector3 getUnitY()
```


يحصل على المتجه الوحدوي (0, 1, 0)

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - unit vector (0, 1, 0)
### getUnitZ() {#getUnitZ--}
```
public static Vector3 getUnitZ()
```


يحصل على المتجه الوحدوي (0, 0, 1)

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - unit vector (0, 0, 1)
### getZero() {#getZero--}
```
public static Vector3 getZero()
```


يحصل على المتجه الوحدوي (0, 0, 0)

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - unit vector (0, 0, 0)
### hashCode() {#hashCode--}
```
public int hashCode()
```


يحصل على رمز التجزئة لـ Vector3

**Returns:**
int - رمز التجزئة لـ [Vector3](../../com.aspose.threed/vector3)
### mul(Vector3 lhs, Vector3 rhs) {#mul-com.aspose.threed.Vector3-com.aspose.threed.Vector3-}
```
public static Vector3 mul(Vector3 lhs, Vector3 rhs)
```


إعادة تعريف المشغل لـ \*

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| lhs | [Vector3](../../com.aspose.threed/vector3) | المتجه الأيسر |
| rhs | [Vector3](../../com.aspose.threed/vector3) | المتجه الأيمن |

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - Result vector
### mul(Vector3 lhs, double rhs) {#mul-com.aspose.threed.Vector3-double-}
```
public static Vector3 mul(Vector3 lhs, double rhs)
```


إعادة تعريف المشغل لـ \*

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| lhs | [Vector3](../../com.aspose.threed/vector3) | المتجه الأيسر |
| rhs | double | القيمة المزدوجة اليمنى |

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - Result vector
### mul(double lhs, Vector3 rhs) {#mul-double-com.aspose.threed.Vector3-}
```
public static Vector3 mul(double lhs, Vector3 rhs)
```


إعادة تعريف المشغل لـ \*

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| lhs | double | المقياس الأيسر |
| rhs | [Vector3](../../com.aspose.threed/vector3) | المتجه الأيمن |

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - Result vector
### negative(Vector3 v) {#negative-com.aspose.threed.Vector3-}
```
public static Vector3 negative(Vector3 v)
```


إعادة تعريف المشغل لـ -

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| v | [Vector3](../../com.aspose.threed/vector3) | متجه الأصل |

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - Result vector
### normalize() {#normalize--}
```
public Vector3 normalize()
```


يقوم بتطبيع هذه الحالة.

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


عامل المساواة لـ Vector3

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| lhs | [Vector3](../../com.aspose.threed/vector3) | قيمة الطرف الأيسر. |
| rhs | [Vector3](../../com.aspose.threed/vector3) | قيمة الطرف الأيمن. |

**Returns:**
boolean - صحيح إذا كانت جميع المكوّنات متساوية تمامًا.
### op_ne(Vector3 lhs, Vector3 rhs) {#op-ne-com.aspose.threed.Vector3-com.aspose.threed.Vector3-}
```
public static boolean op_ne(Vector3 lhs, Vector3 rhs)
```


عامل عدم المساواة لـ Vector3

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| lhs | [Vector3](../../com.aspose.threed/vector3) | قيمة الطرف الأيسر. |
| rhs | [Vector3](../../com.aspose.threed/vector3) | قيمة الطرف الأيمن. |

**Returns:**
boolean - صحيح إذا كان المتجهان غير متساويين.
### set(double newX, double newY, double newZ) {#set-double-double-double-}
```
public void set(double newX, double newY, double newZ)
```


يضبط مكوّنات x/y/z في استدعاء واحد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| newX | double | المكوّن x. |
| newY | double | المكوّن y. |
| newZ | double | المكوّن z. |

### set(int idx, double value) {#set-int-double-}
```
public void set(int idx, double value)
```


يضبط مكوّن المتجه حسب الفهرس.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| idx | int |  |
| القيمة | double | القيمة الجديدة |

### sin() {#sin--}
```
public Vector3 sin()
```


يحسب جيب الزاوية لكل مكوّن

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - Calculated [Vector3](../../com.aspose.threed/vector3).
### sub(Vector3 lhs, Vector3 rhs) {#sub-com.aspose.threed.Vector3-com.aspose.threed.Vector3-}
```
public static Vector3 sub(Vector3 lhs, Vector3 rhs)
```


تجاوز المشغل للـ - (ناقص)

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| lhs | [Vector3](../../com.aspose.threed/vector3) | المتجه الأيسر |
| rhs | [Vector3](../../com.aspose.threed/vector3) | المتجه الأيمن |

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - Result vector
### toString() {#toString--}
```
public String toString()
```


يعيد java.lang.String يمثل الـ [Vector3](../../com.aspose.threed/vector3) الحالي.

**Returns:**
java.lang.String - java.lang.String تمثل الـ [Vector3](../../com.aspose.threed/vector3) الحالي.
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


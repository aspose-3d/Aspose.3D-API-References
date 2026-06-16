---
title: "Quaternion"
second_title: "مرجع API لـ Aspose.3D for Java"
description: "عادةً ما يُستخدم الكواترن لتطبيق الدوران في الرسومات الحاسوبية."
type: docs
weight: 143
url: /ar/java/com.aspose.threed/quaternion/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.threed.Struct, java.io.Serializable
```
public final class Quaternion implements Struct<Quaternion>, Serializable
```

عادةً ما يُستخدم الكواترن لتطبيق الدوران في الرسومات الحاسوبية.
## المنشئات

| منشئ | الوصف |
| --- | --- |
| [Quaternion(double w, double x, double y, double z)](#Quaternion-double-double-double-double-) | يُنشئ مثيلًا جديدًا من الفئة [Quaternion](../../com.aspose.threed/quaternion). |
| [Quaternion()](#Quaternion--) |  |
## الحقول

| حقل | الوصف |
| --- | --- |
| [IDENTITY](#IDENTITY) | الكوaternion الهوية. |
| [w](#w) | المكوّن w. |
| [x](#x) | المكوّن x. |
| [y](#y) | المكوّن y. |
| [z](#z) | المكوّن z. |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [add(Quaternion lhs, Quaternion rhs)](#add-com.aspose.threed.Quaternion-com.aspose.threed.Quaternion-) | إعادة تعريف المشغل لـ + |
| [clone()](#clone--) |  |
| [concat(Quaternion rhs)](#concat-com.aspose.threed.Quaternion-) | دمج اثنين من الـ quaternion |
| [conjugate()](#conjugate--) | يرجع quaternion مرافق للـ quaternion الحالي |
| [copyFrom(Quaternion src)](#copyFrom-com.aspose.threed.Quaternion-) |  |
| [div(Quaternion lhs, double rhs)](#div-com.aspose.threed.Quaternion-double-) | إعادة تعريف المشغل لـ / |
| [dot(Quaternion q)](#dot-com.aspose.threed.Quaternion-) | ناتج الضرب النقطي |
| [equals(Object obj)](#equals-java.lang.Object-) | تحقق مما إذا كان اثنان من الـ quaternion متساويين |
| [eulerAngles()](#eulerAngles--) | يحوّل quaternion إلى دوران ممثل بزاويات إيلر. جميع المكونات بالراديان |
| [fromAngleAxis(double a, Vector3 axis)](#fromAngleAxis-double-com.aspose.threed.Vector3-) | ينشئ quaternion حول المحور المعطى ويدور باتجاه عقارب الساعة |
| [fromEulerAngle(Vector3 eulerAngle)](#fromEulerAngle-com.aspose.threed.Vector3-) | ينشئ quaternion من زاوية إيلر المعطاة |
| [fromEulerAngle(double pitch, double yaw, double roll)](#fromEulerAngle-double-double-double-) | ينشئ quaternion من زاوية إيلر المعطاة |
| [fromRotation(Vector3 orig, Vector3 dest)](#fromRotation-com.aspose.threed.Vector3-com.aspose.threed.Vector3-) | ينشئ quaternion يدور من الاتجاه الأصلي إلى الاتجاه الوجهة |
| [getClass()](#getClass--) |  |
| [getLength()](#getLength--) | يحصل على طول الـ quaternion |
| [hashCode()](#hashCode--) | يحصل على رمز التجزئة للـ Quaternion |
| [interpolate(float t, Quaternion from, Quaternion to)](#interpolate-float-com.aspose.threed.Quaternion-com.aspose.threed.Quaternion-) | يملأ هذا الـ quaternion بالقيمة المتوسطة بين معطيات الـ quaternion المعطاة عند قيمة t بين البداية والنهاية |
| [inverse()](#inverse--) | يرجع quaternion عكسي للـ quaternion الحالي |
| [mul(Quaternion lhs, Quaternion rhs)](#mul-com.aspose.threed.Quaternion-com.aspose.threed.Quaternion-) | إعادة تعريف المشغل لـ \* |
| [mul(Quaternion q, Vector3 v)](#mul-com.aspose.threed.Quaternion-com.aspose.threed.Vector3-) | إعادة تعريف المشغل لـ \* |
| [mul(Quaternion q, Vector4 v)](#mul-com.aspose.threed.Quaternion-com.aspose.threed.Vector4-) | إعادة تعريف المشغل لـ \* |
| [mul(Quaternion lhs, double rhs)](#mul-com.aspose.threed.Quaternion-double-) | إعادة تعريف المشغل لـ \* |
| [mul(Vector3 v, Quaternion q)](#mul-com.aspose.threed.Vector3-com.aspose.threed.Quaternion-) | إعادة تعريف المشغل لـ \* |
| [normalize()](#normalize--) | قم بتطبيع الـ quaternion |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [op_eq(Quaternion lhs, Quaternion rhs)](#op-eq-com.aspose.threed.Quaternion-com.aspose.threed.Quaternion-) | عامل المساواة للكوaternion |
| [op_ne(Quaternion lhs, Quaternion rhs)](#op-ne-com.aspose.threed.Quaternion-com.aspose.threed.Quaternion-) | عامل عدم المساواة للكوaternion |
| [slerp(double t, Quaternion v1, Quaternion v2)](#slerp-double-com.aspose.threed.Quaternion-com.aspose.threed.Quaternion-) | أجرِ استيفاء خطي كروي بين قيمتين |
| [toAngleAxis(double[] angle, Vector3 axis)](#toAngleAxis-double---com.aspose.threed.Vector3-) | تحليل الكواترنيون إلى زاوية ومحور |
| [toMatrix()](#toMatrix--) | حوّل الدوران الممثل بالـ quaternion إلى مصفوفة تحويل. |
| [toMatrix(Vector3 translation)](#toMatrix-com.aspose.threed.Vector3-) | حوّل الدوران الممثل بالـ quaternion إلى مصفوفة تحويل. |
| [toString()](#toString--) | يحصل على تمثيل الـ quaternion كسلسلة |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Quaternion(double w, double x, double y, double z) {#Quaternion-double-double-double-double-}
```
public Quaternion(double w, double x, double y, double z)
```


يُنشئ مثيلًا جديدًا من الفئة [Quaternion](../../com.aspose.threed/quaternion).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| w | double | المكوّن w للـ quaternion |
| x | double | المكوّن x للـ quaternion |
| y | double | المكوّن y للـ quaternion |
| z | double | المكوّن z للـ quaternion |

### Quaternion() {#Quaternion--}
```
public Quaternion()
```


### IDENTITY {#IDENTITY}
```
public static final Quaternion IDENTITY
```


الكوaternion الهوية.

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

### add(Quaternion lhs, Quaternion rhs) {#add-com.aspose.threed.Quaternion-com.aspose.threed.Quaternion-}
```
public static Quaternion add(Quaternion lhs, Quaternion rhs)
```


إعادة تعريف المشغل لـ +

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| lhs | [Quaternion](../../com.aspose.threed/quaternion) | الكواترنيون الأيسر |
| rhs | [Quaternion](../../com.aspose.threed/quaternion) | الكواترنيون الأيمن |

**Returns:**
[Quaternion](../../com.aspose.threed/quaternion) - Result quaternion
### clone() {#clone--}
```
public Quaternion clone()
```


استنساخ النسخة الحالية

**Returns:**
[Quaternion](../../com.aspose.threed/quaternion)
### concat(Quaternion rhs) {#concat-com.aspose.threed.Quaternion-}
```
public Quaternion concat(Quaternion rhs)
```


دمج اثنين من الـ quaternion

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| rhs | [Quaternion](../../com.aspose.threed/quaternion) |  |

**Returns:**
[Quaternion](../../com.aspose.threed/quaternion)
### conjugate() {#conjugate--}
```
public Quaternion conjugate()
```


يرجع quaternion مرافق للـ quaternion الحالي

**Returns:**
[Quaternion](../../com.aspose.threed/quaternion) - The conjugate quaternion.
### copyFrom(Quaternion src) {#copyFrom-com.aspose.threed.Quaternion-}
```
public void copyFrom(Quaternion src)
```




**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| src | [Quaternion](../../com.aspose.threed/quaternion) |  |

### div(Quaternion lhs, double rhs) {#div-com.aspose.threed.Quaternion-double-}
```
public static Quaternion div(Quaternion lhs, double rhs)
```


إعادة تعريف المشغل لـ /

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| lhs | [Quaternion](../../com.aspose.threed/quaternion) | الكواترنيون الأيسر |
| rhs | double | الكواترنيون الأيمن |

**Returns:**
[Quaternion](../../com.aspose.threed/quaternion) - Result quaternion
### dot(Quaternion q) {#dot-com.aspose.threed.Quaternion-}
```
public double dot(Quaternion q)
```


ناتج الضرب النقطي

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| q | [Quaternion](../../com.aspose.threed/quaternion) | الكواترنيون |

**Returns:**
double - قيمة النقطة
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


تحقق مما إذا كان اثنان من الـ quaternion متساويين

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| obj | java.lang.Object | الكائن للتحقق من المساواة. |

**Returns:**
boolean - صحيح إذا كانت جميع المكوّنات متساوية تمامًا.
### eulerAngles() {#eulerAngles--}
```
public Vector3 eulerAngles()
```


يحوّل quaternion إلى دوران ممثل بزاويات إيلر. جميع المكونات بالراديان

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - Result vector
### fromAngleAxis(double a, Vector3 axis) {#fromAngleAxis-double-com.aspose.threed.Vector3-}
```
public static Quaternion fromAngleAxis(double a, Vector3 axis)
```


ينشئ quaternion حول المحور المعطى ويدور باتجاه عقارب الساعة

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| a | double | دوران باتجاه عقارب الساعة بالراديان |
| axis | [Vector3](../../com.aspose.threed/vector3) | المحور |

**Returns:**
[Quaternion](../../com.aspose.threed/quaternion) - Created quaternion
### fromEulerAngle(Vector3 eulerAngle) {#fromEulerAngle-com.aspose.threed.Vector3-}
```
public static Quaternion fromEulerAngle(Vector3 eulerAngle)
```


ينشئ quaternion من زاوية إيلر المعطاة

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| eulerAngle | [Vector3](../../com.aspose.threed/vector3) | زاوية أويلر بالراديان |

**Returns:**
[Quaternion](../../com.aspose.threed/quaternion) - Created quaternion
### fromEulerAngle(double pitch, double yaw, double roll) {#fromEulerAngle-double-double-double-}
```
public static Quaternion fromEulerAngle(double pitch, double yaw, double roll)
```


ينشئ quaternion من زاوية إيلر المعطاة

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| ميل | double | الميل بالراديان |
| انحراف | double | الانحراف بالراديان |
| دوران | double | الدوران بالراديان |

**Returns:**
[Quaternion](../../com.aspose.threed/quaternion) - Created quaternion
### fromRotation(Vector3 orig, Vector3 dest) {#fromRotation-com.aspose.threed.Vector3-com.aspose.threed.Vector3-}
```
public static Quaternion fromRotation(Vector3 orig, Vector3 dest)
```


ينشئ quaternion يدور من الاتجاه الأصلي إلى الاتجاه الوجهة

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| orig | [Vector3](../../com.aspose.threed/vector3) | الاتجاه الأصلي |
| dest | [Vector3](../../com.aspose.threed/vector3) | الاتجاه المستهدف |

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


يحصل على طول الـ quaternion

**Returns:**
double - طول الكواترنيون
### hashCode() {#hashCode--}
```
public int hashCode()
```


يحصل على رمز التجزئة للـ Quaternion

**Returns:**
int - رمز التجزئة للـ [Quaternion](../../com.aspose.threed/quaternion)
### interpolate(float t, Quaternion from, Quaternion to) {#interpolate-float-com.aspose.threed.Quaternion-com.aspose.threed.Quaternion-}
```
public static Quaternion interpolate(float t, Quaternion from, Quaternion to)
```


يملأ هذا الـ quaternion بالقيمة المتوسطة بين معطيات الـ quaternion المعطاة عند قيمة t بين البداية والنهاية

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| t | float | المعامل للاستيفاء. |
| from | [Quaternion](../../com.aspose.threed/quaternion) | كواتيرنيون المصدر. |
| to | [Quaternion](../../com.aspose.threed/quaternion) | كواتيرنيون الهدف. |

**Returns:**
[Quaternion](../../com.aspose.threed/quaternion) - The interpolated quaternion.
### inverse() {#inverse--}
```
public Quaternion inverse()
```


يرجع quaternion عكسي للـ quaternion الحالي

**Returns:**
[Quaternion](../../com.aspose.threed/quaternion) - Inverse quaternion.
### mul(Quaternion lhs, Quaternion rhs) {#mul-com.aspose.threed.Quaternion-com.aspose.threed.Quaternion-}
```
public static Quaternion mul(Quaternion lhs, Quaternion rhs)
```


إعادة تعريف المشغل لـ \*

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| lhs | [Quaternion](../../com.aspose.threed/quaternion) | الكواترنيون الأيسر |
| rhs | [Quaternion](../../com.aspose.threed/quaternion) | الكواترنيون الأيمن |

**Returns:**
[Quaternion](../../com.aspose.threed/quaternion) - Result quaternion
### mul(Quaternion q, Vector3 v) {#mul-com.aspose.threed.Quaternion-com.aspose.threed.Vector3-}
```
public static Vector3 mul(Quaternion q, Vector3 v)
```


إعادة تعريف المشغل لـ \*

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| q | [Quaternion](../../com.aspose.threed/quaternion) | الكواترنيون الدوراني |
| v | [Vector3](../../com.aspose.threed/vector3) | المتجه للدوران |

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - Rotated vector
### mul(Quaternion q, Vector4 v) {#mul-com.aspose.threed.Quaternion-com.aspose.threed.Vector4-}
```
public static Vector4 mul(Quaternion q, Vector4 v)
```


إعادة تعريف المشغل لـ \*

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| q | [Quaternion](../../com.aspose.threed/quaternion) | الكواترنيون الدوراني |
| v | [Vector4](../../com.aspose.threed/vector4) | المتجه للدوران |

**Returns:**
[Vector4](../../com.aspose.threed/vector4) - Rotated vector
### mul(Quaternion lhs, double rhs) {#mul-com.aspose.threed.Quaternion-double-}
```
public static Quaternion mul(Quaternion lhs, double rhs)
```


إعادة تعريف المشغل لـ \*

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| lhs | [Quaternion](../../com.aspose.threed/quaternion) | الكواترنيون الأيسر |
| rhs | double | الكواترنيون الأيمن |

**Returns:**
[Quaternion](../../com.aspose.threed/quaternion) - Result quaternion
### mul(Vector3 v, Quaternion q) {#mul-com.aspose.threed.Vector3-com.aspose.threed.Quaternion-}
```
public static Vector3 mul(Vector3 v, Quaternion q)
```


إعادة تعريف المشغل لـ \*

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| v | [Vector3](../../com.aspose.threed/vector3) | الكواترنيون الدوراني |
| q | [Quaternion](../../com.aspose.threed/quaternion) | المتجه للدوران |

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - Rotated vector
### normalize() {#normalize--}
```
public Quaternion normalize()
```


قم بتطبيع الـ quaternion

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


عامل المساواة للكوaternion

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| lhs | [Quaternion](../../com.aspose.threed/quaternion) | قيمة الطرف الأيسر. |
| rhs | [Quaternion](../../com.aspose.threed/quaternion) | قيمة الطرف الأيمن. |

**Returns:**
boolean - صحيح إذا كانت جميع المكوّنات متساوية تمامًا.
### op_ne(Quaternion lhs, Quaternion rhs) {#op-ne-com.aspose.threed.Quaternion-com.aspose.threed.Quaternion-}
```
public static boolean op_ne(Quaternion lhs, Quaternion rhs)
```


عامل عدم المساواة للكوaternion

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| lhs | [Quaternion](../../com.aspose.threed/quaternion) | قيمة الطرف الأيسر. |
| rhs | [Quaternion](../../com.aspose.threed/quaternion) | قيمة الطرف الأيمن. |

**Returns:**
منطقي - صحيح إذا كان اثنان من الكواتيرنيونات غير متساويين.
### slerp(double t, Quaternion v1, Quaternion v2) {#slerp-double-com.aspose.threed.Quaternion-com.aspose.threed.Quaternion-}
```
public static Quaternion slerp(double t, Quaternion v1, Quaternion v2)
```


أجرِ استيفاء خطي كروي بين قيمتين

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| t | double | t بين 0 إلى 1 |
| v1 | [Quaternion](../../com.aspose.threed/quaternion) | القيمة الأولى |
| v2 | [Quaternion](../../com.aspose.threed/quaternion) | القيمة الثانية |

**Returns:**
[Quaternion](../../com.aspose.threed/quaternion)
### toAngleAxis(double[] angle, Vector3 axis) {#toAngleAxis-double---com.aspose.threed.Vector3-}
```
public void toAngleAxis(double[] angle, Vector3 axis)
```


تحليل الكواترنيون إلى زاوية ومحور

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| زاوية | double[] | زاوية الدوران، بالراديان. |
| axis | [Vector3](../../com.aspose.threed/vector3) | المحور الذي يدور حوله. |

### toMatrix() {#toMatrix--}
```
public Matrix4 toMatrix()
```


حوّل الدوران الممثل بالـ quaternion إلى مصفوفة تحويل.

**Returns:**
[Matrix4](../../com.aspose.threed/matrix4) - The matrix representation of current quaternion.
### toMatrix(Vector3 translation) {#toMatrix-com.aspose.threed.Vector3-}
```
public Matrix4 toMatrix(Vector3 translation)
```


حوّل الدوران الممثل بالـ quaternion إلى مصفوفة تحويل.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| translation | [Vector3](../../com.aspose.threed/vector3) | جزء الإزاحة في المصفوفة. |

**Returns:**
[Matrix4](../../com.aspose.threed/matrix4) - The matrix representation of current quaternion.
### toString() {#toString--}
```
public String toString()
```


يحصل على تمثيل الـ quaternion كسلسلة

**Returns:**
java.lang.String - سلسلة الكائن
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


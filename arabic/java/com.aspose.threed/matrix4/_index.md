---
title: "Matrix4"
second_title: "مرجع API لـ Aspose.3D for Java"
description: "تنفيذ مصفوفة 4×4."
type: docs
weight: 100
url: /ar/java/com.aspose.threed/matrix4/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.threed.Struct, java.io.Serializable
```
public final class Matrix4 implements Struct<Matrix4>, Serializable
```

تنفيذ مصفوفة 4x4. **مثال:**

```
Matrix4 mat = Matrix4.rotateFromEuler(90, 0, 0);
      Matrix4 mat2 = Matrix4.translate(0, 10, -50);
      Matrix4 transform = Matrix4.mul(mat2, mat);
      Vector4 pos = new Vector4(10, 9, 0, 1);
      Vector4 transformed = Matrix4.mul(transform, pos);
```
## المنشئات

| منشئ | الوصف |
| --- | --- |
| [Matrix4(Vector4 r0, Vector4 r1, Vector4 r2, Vector4 r3)](#Matrix4-com.aspose.threed.Vector4-com.aspose.threed.Vector4-com.aspose.threed.Vector4-com.aspose.threed.Vector4-) | يبني المصفوفة من 4 صفوف. |
| [Matrix4(double m00, double m01, double m02, double m03, double m10, double m11, double m12, double m13, double m20, double m21, double m22, double m23, double m30, double m31, double m32, double m33)](#Matrix4-double-double-double-double-double-double-double-double-double-double-double-double-double-double-double-double-) | يُنشئ مثيلاً جديدًا للهيكل [Matrix4](../../com.aspose.threed/matrix4). |
| [Matrix4(FMatrix4 m)](#Matrix4-com.aspose.threed.FMatrix4-) | أنشئ [Matrix4](../../com.aspose.threed/matrix4) من مثيل [FMatrix4](../../com.aspose.threed/fmatrix4) |
| [Matrix4(double[] m)](#Matrix4-double---) | يُنشئ مثيلاً جديدًا للهيكل [Matrix4](../../com.aspose.threed/matrix4). |
| [Matrix4()](#Matrix4--) |  |
## الحقول

| حقل | الوصف |
| --- | --- |
| [m00](#m00) | الـ m00. |
| [m01](#m01) | الـ m01. |
| [m02](#m02) | الـ m02. |
| [m03](#m03) | الـ m03. |
| [m10](#m10) | الـ m10. |
| [m11](#m11) | الـ m11. |
| [m12](#m12) | العنصر m12. |
| [m13](#m13) | العنصر m13. |
| [m20](#m20) | العنصر m20. |
| [m21](#m21) | العنصر m21. |
| [m22](#m22) | العنصر m22. |
| [m23](#m23) | العنصر m23. |
| [m30](#m30) | العنصر m30. |
| [m31](#m31) | العنصر m31. |
| [m32](#m32) | العنصر m32. |
| [m33](#m33) | العنصر m33. |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [clone()](#clone--) |  |
| [concatenate(Matrix4 m2)](#concatenate-com.aspose.threed.Matrix4-) | يجمع المصفوفتين |
| [copyFrom(Matrix4 src)](#copyFrom-com.aspose.threed.Matrix4-) |  |
| [decompose(Vector3 translation, Vector3 scaling, Quaternion rotation)](#decompose-com.aspose.threed.Vector3-com.aspose.threed.Vector3-com.aspose.threed.Quaternion-) | فك تجميع مصفوفة التحويل. |
| [equals(Object obj)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getDeterminant()](#getDeterminant--) | يحصل على محدد المصفوفة. |
| [getIdentity()](#getIdentity--) | يحصل على مصفوفة الهوية. |
| [hashCode()](#hashCode--) |  |
| [inverse()](#inverse--) | يعكس هذا المثيل. |
| [mul(Matrix4 lhs, Matrix4 rhs)](#mul-com.aspose.threed.Matrix4-com.aspose.threed.Matrix4-) | ضرب المصفوفتين |
| [mul(Matrix4 lhs, Vector3 v)](#mul-com.aspose.threed.Matrix4-com.aspose.threed.Vector3-) | ضرب المصفوفة والمتجه3 |
| [mul(Matrix4 lhs, Vector4 v)](#mul-com.aspose.threed.Matrix4-com.aspose.threed.Vector4-) | ضرب المصفوفة والمتجه4 |
| [mul(Matrix4 lhs, double v)](#mul-com.aspose.threed.Matrix4-double-) | ضرب المصفوفة والقيمة المزدوجة |
| [normalize()](#normalize--) | يقوم بتطبيع هذه الحالة. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [rotate(Quaternion q)](#rotate-com.aspose.threed.Quaternion-) | إنشاء مصفوفة دوران من quaternion |
| [rotate(double angle, Vector3 axis)](#rotate-double-com.aspose.threed.Vector3-) | إنشاء مصفوفة دوران بزاوية الدوران والمحور |
| [rotateFromEuler(Vector3 eul)](#rotateFromEuler-com.aspose.threed.Vector3-) | إنشاء مصفوفة دوران من زاوية أويلر |
| [rotateFromEuler(double rx, double ry, double rz)](#rotateFromEuler-double-double-double-) | إنشاء مصفوفة دوران من زاوية أويلر |
| [scale(Vector3 s)](#scale-com.aspose.threed.Vector3-) | ينشئ مصفوفة تُقِيس على المحور x والمحور y والمحور z |
| [scale(double s)](#scale-double-) | ينشئ مصفوفة تُقِيس على المحور x والمحور y والمحور z |
| [scale(double sx, double sy, double sz)](#scale-double-double-double-) | ينشئ مصفوفة تُقِيس على المحور x والمحور y والمحور z |
| [setTRS(Vector3 translation, Vector3 rotation, Vector3 scale)](#setTRS-com.aspose.threed.Vector3-com.aspose.threed.Vector3-com.aspose.threed.Vector3-) | يُهيئ المصفوفة بالترجمة/الدوران/التحجيم |
| [toArray()](#toArray--) | يحوِّل المصفوفة إلى مصفوفة. |
| [toString()](#toString--) | يرجع java.lang.String الذي يمثل الـ [Matrix4](../../com.aspose.threed/matrix4) الحالي. |
| [translate(Vector3 t)](#translate-com.aspose.threed.Vector3-) | ينشئ مصفوفة تُترجم على المحور x والمحور y والمحور z |
| [translate(double tx, double ty, double tz)](#translate-double-double-double-) | ينشئ مصفوفة تُترجم على المحور x والمحور y والمحور z |
| [transpose()](#transpose--) | يقلب هذا الكائن. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Matrix4(Vector4 r0, Vector4 r1, Vector4 r2, Vector4 r3) {#Matrix4-com.aspose.threed.Vector4-com.aspose.threed.Vector4-com.aspose.threed.Vector4-com.aspose.threed.Vector4-}
```
public Matrix4(Vector4 r0, Vector4 r1, Vector4 r2, Vector4 r3)
```


يبني المصفوفة من 4 صفوف.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| r0 | [Vector4](../../com.aspose.threed/vector4) | R0. |
| r1 | [Vector4](../../com.aspose.threed/vector4) | R1. |
| r2 | [Vector4](../../com.aspose.threed/vector4) | R2. |
| r3 | [Vector4](../../com.aspose.threed/vector4) | R3. |

### Matrix4(double m00, double m01, double m02, double m03, double m10, double m11, double m12, double m13, double m20, double m21, double m22, double m23, double m30, double m31, double m32, double m33) {#Matrix4-double-double-double-double-double-double-double-double-double-double-double-double-double-double-double-double-}
```
public Matrix4(double m00, double m01, double m02, double m03, double m10, double m11, double m12, double m13, double m20, double m21, double m22, double m23, double m30, double m31, double m32, double m33)
```


يُنشئ مثيلاً جديدًا للهيكل [Matrix4](../../com.aspose.threed/matrix4).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| m00 | double | M00. |
| m01 | double | M01. |
| m02 | double | M02. |
| m03 | double | M03. |
| m10 | double | M10. |
| m11 | double | M11. |
| m12 | double | M12. |
| m13 | double | M13. |
| m20 | double | M20. |
| m21 | double | M21. |
| m22 | double | M22. |
| m23 | double | M23. |
| m30 | double | M30. |
| m31 | double | M31. |
| m32 | double | M32. |
|  | m33 | double | M33. **مثال:** |

```
var mat = new Matrix4(
         1, 0, 0, 0,
         0, 1, 0, 0,
         0, 0, 1, 0,
         10, 20, 0, 1);
     var pos = new Vector3(10, 0, -1);
     var transformed = Matrix4.mul(mat, pos);
``` |

### Matrix4(FMatrix4 m) {#Matrix4-com.aspose.threed.FMatrix4-}
```
public Matrix4(FMatrix4 m)
```


أنشئ [Matrix4](../../com.aspose.threed/matrix4) من مثيل [FMatrix4](../../com.aspose.threed/fmatrix4)

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| m | [FMatrix4](../../com.aspose.threed/fmatrix4) |  |

### Matrix4(double[] m) {#Matrix4-double---}
```
public Matrix4(double[] m)
```


يُنشئ مثيلاً جديدًا للهيكل [Matrix4](../../com.aspose.threed/matrix4).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| m | double[] | M. |

### Matrix4() {#Matrix4--}
```
public Matrix4()
```


### m00 {#m00}
```
public double m00
```


الـ m00.

### m01 {#m01}
```
public double m01
```


الـ m01.

### m02 {#m02}
```
public double m02
```


الـ m02.

### m03 {#m03}
```
public double m03
```


الـ m03.

### m10 {#m10}
```
public double m10
```


الـ m10.

### m11 {#m11}
```
public double m11
```


الـ m11.

### m12 {#m12}
```
public double m12
```


العنصر m12.

### m13 {#m13}
```
public double m13
```


العنصر m13.

### m20 {#m20}
```
public double m20
```


العنصر m20.

### m21 {#m21}
```
public double m21
```


العنصر m21.

### m22 {#m22}
```
public double m22
```


العنصر m22.

### m23 {#m23}
```
public double m23
```


العنصر m23.

### m30 {#m30}
```
public double m30
```


العنصر m30.

### m31 {#m31}
```
public double m31
```


العنصر m31.

### m32 {#m32}
```
public double m32
```


العنصر m32.

### m33 {#m33}
```
public double m33
```


العنصر m33.

### clone() {#clone--}
```
public Matrix4 clone()
```


استنساخ النسخة الحالية

**Returns:**
[Matrix4](../../com.aspose.threed/matrix4)
### concatenate(Matrix4 m2) {#concatenate-com.aspose.threed.Matrix4-}
```
public Matrix4 concatenate(Matrix4 m2)
```


يجمع المصفوفتين

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| m2 | [Matrix4](../../com.aspose.threed/matrix4) | M2. |

**Returns:**
[Matrix4](../../com.aspose.threed/matrix4) - New matrix4 **Example:**

```
Matrix4 t = Matrix4.translate(0, 10, 9);
     Matrix4 s = Matrix4.scale(10, 10, 10);
     Matrix4 transform = t.concatenate(s);
     Vector3 pos = new Vector3(10, 0, -1);
     Vector3 transformed = Matrix4.mul(transform, pos);
```
### copyFrom(Matrix4 src) {#copyFrom-com.aspose.threed.Matrix4-}
```
public void copyFrom(Matrix4 src)
```




**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| src | [Matrix4](../../com.aspose.threed/matrix4) |  |

### decompose(Vector3 translation, Vector3 scaling, Quaternion rotation) {#decompose-com.aspose.threed.Vector3-com.aspose.threed.Vector3-com.aspose.threed.Quaternion-}
```
public boolean decompose(Vector3 translation, Vector3 scaling, Quaternion rotation)
```


فك تجميع مصفوفة التحويل.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| translation | [Vector3](../../com.aspose.threed/vector3) | الإزاحة. |
| scaling | [Vector3](../../com.aspose.threed/vector3) | التحجيم. |
| rotation | [Quaternion](../../com.aspose.threed/quaternion) | الدوران. |

**Returns:**
boolean - صحيح إذا نجح.
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
### getDeterminant() {#getDeterminant--}
```
public double getDeterminant()
```


يحصل على محدد المصفوفة.

**Returns:**
double - محدد المصفوفة.
### getIdentity() {#getIdentity--}
```
public static Matrix4 getIdentity()
```


يحصل على مصفوفة الهوية.

**Returns:**
[Matrix4](../../com.aspose.threed/matrix4) - the identity matrix.
### hashCode() {#hashCode--}
```
public int hashCode()
```




**Returns:**
int
### inverse() {#inverse--}
```
public Matrix4 inverse()
```


يعكس هذا المثيل.

**Returns:**
[Matrix4](../../com.aspose.threed/matrix4) - Inverse matrix4 **Example:** The following code shows how to inverse a matrix

```
Matrix4 t = Matrix4.translate(0, 10, 9);
     Matrix4 mat = t.inverse();
     System.out.printf("Inversed Matrix: %s", mat);
```
### mul(Matrix4 lhs, Matrix4 rhs) {#mul-com.aspose.threed.Matrix4-com.aspose.threed.Matrix4-}
```
public static Matrix4 mul(Matrix4 lhs, Matrix4 rhs)
```


ضرب المصفوفتين

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| lhs | [Matrix4](../../com.aspose.threed/matrix4) | Lhs. |
| rhs | [Matrix4](../../com.aspose.threed/matrix4) | الجانب الأيمن. |

**Returns:**
[Matrix4](../../com.aspose.threed/matrix4) - Result matrix
### mul(Matrix4 lhs, Vector3 v) {#mul-com.aspose.threed.Matrix4-com.aspose.threed.Vector3-}
```
public static Vector3 mul(Matrix4 lhs, Vector3 v)
```


ضرب المصفوفة والمتجه3

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| lhs | [Matrix4](../../com.aspose.threed/matrix4) | Lhs. |
| v | [Vector3](../../com.aspose.threed/vector3) | V. |

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - Result matrix
### mul(Matrix4 lhs, Vector4 v) {#mul-com.aspose.threed.Matrix4-com.aspose.threed.Vector4-}
```
public static Vector4 mul(Matrix4 lhs, Vector4 v)
```


ضرب المصفوفة والمتجه4

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| lhs | [Matrix4](../../com.aspose.threed/matrix4) | Lhs. |
| v | [Vector4](../../com.aspose.threed/vector4) | V. |

**Returns:**
[Vector4](../../com.aspose.threed/vector4) - Result matrix
### mul(Matrix4 lhs, double v) {#mul-com.aspose.threed.Matrix4-double-}
```
public static Matrix4 mul(Matrix4 lhs, double v)
```


ضرب المصفوفة والقيمة المزدوجة

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| lhs | [Matrix4](../../com.aspose.threed/matrix4) | Lhs. |
| v | double | V. |

**Returns:**
[Matrix4](../../com.aspose.threed/matrix4) - Result matrix
### normalize() {#normalize--}
```
public Matrix4 normalize()
```


يقوم بتطبيع هذه الحالة.

**Returns:**
[Matrix4](../../com.aspose.threed/matrix4) - Normalize matrix4
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### rotate(Quaternion q) {#rotate-com.aspose.threed.Quaternion-}
```
public static Matrix4 rotate(Quaternion q)
```


إنشاء مصفوفة دوران من quaternion

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | q | [Quaternion](../../com.aspose.threed/quaternion) | كواترن الدوران **مثال:** يوضح الشيفرة التالية كيفية إنشاء مصفوفة لعملية الدوران. |

```
var t = Matrix4.rotate(Quaternion.fromAngleAxis(Math.PI, Vector3.getUnitY()));
     var pos = new Vector3(1, 1, 10);
     System.out.printf("Transformed: %s", Matrix4.mul(t, pos));
``` |

**Returns:**
[Matrix4](../../com.aspose.threed/matrix4)
### rotate(double angle, Vector3 axis) {#rotate-double-com.aspose.threed.Vector3-}
```
public static Matrix4 rotate(double angle, Vector3 axis)
```


إنشاء مصفوفة دوران بزاوية الدوران والمحور

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| زاوية | double | زاوية الدوران بالراديان |
|  | axis | [Vector3](../../com.aspose.threed/vector3) | محور الدوران **مثال:** يوضح الشيفرة التالية كيفية إنشاء مصفوفة لعملية الدوران. |

```
var t = Matrix4.rotate(Math.PI, new Vector3(0, 1, 0));
     var pos = new Vector3(1, 1, 10);
     System.out.printf("Transformed: %s", Matrix4.mul(t, pos));
``` |

**Returns:**
[Matrix4](../../com.aspose.threed/matrix4)
### rotateFromEuler(Vector3 eul) {#rotateFromEuler-com.aspose.threed.Vector3-}
```
public static Matrix4 rotateFromEuler(Vector3 eul)
```


إنشاء مصفوفة دوران من زاوية أويلر

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | eul | [Vector3](../../com.aspose.threed/vector3) | الدوران بالراديان **مثال:** يوضح الكود التالي كيفية إنشاء مصفوفة لعملية الدوران. |

```
var t = Matrix4.rotateFromEuler(new Vector3(0, Math.PI, 0));
     var pos = new Vector3(1, 1, 10);
     System.out.printf("Transformed: %s", Matrix4.mul(t, pos));
``` |

**Returns:**
[Matrix4](../../com.aspose.threed/matrix4)
### rotateFromEuler(double rx, double ry, double rz) {#rotateFromEuler-double-double-double-}
```
public static Matrix4 rotateFromEuler(double rx, double ry, double rz)
```


إنشاء مصفوفة دوران من زاوية أويلر

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| rx | double | دوران حول محور x بالراديان |
| ry | double | دوران حول محور y بالراديان |
|  | rz | double | دوران حول محور z بالراديان **مثال:** يوضح الكود التالي كيفية إنشاء مصفوفة لعملية الدوران. |

```
var t = Matrix4.rotateFromEuler(0, Math.PI, 0);
     var pos = new Vector3(1, 1, 10);
     System.out.printf("Transformed: %s", Matrix4.mul(t, pos));
``` |

**Returns:**
[Matrix4](../../com.aspose.threed/matrix4)
### scale(Vector3 s) {#scale-com.aspose.threed.Vector3-}
```
public static Matrix4 scale(Vector3 s)
```


ينشئ مصفوفة تُقِيس على المحور x والمحور y والمحور z

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | s | [Vector3](../../com.aspose.threed/vector3) | تطبيقات التحجيم تنطبق على محور x، ومحور y، ومحور z **مثال:** يوضح الكود التالي كيفية إنشاء مصفوفة لعملية التحجيم. |

```
var t = Matrix4.scale(new Vector3(10, 10, 10));
     var pos = new Vector3(1, 1, 10);
     System.out.printf("Transformed: %s", Matrix4.mul(t, pos));
``` |

**Returns:**
[Matrix4](../../com.aspose.threed/matrix4)
### scale(double s) {#scale-double-}
```
public static Matrix4 scale(double s)
```


ينشئ مصفوفة تُقِيس على المحور x والمحور y والمحور z

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | s | double | تطبيقات التحجيم تنطبق على جميع المحاور **مثال:** يوضح الكود التالي كيفية إنشاء مصفوفة لعملية التحجيم. |

```
var t = Matrix4.scale(10);
     var pos = new Vector3(1, 1, 10);
     System.out.printf("Transformed: %s", Matrix4.mul(t, pos));
``` |

**Returns:**
[Matrix4](../../com.aspose.threed/matrix4)
### scale(double sx, double sy, double sz) {#scale-double-double-double-}
```
public static Matrix4 scale(double sx, double sy, double sz)
```


ينشئ مصفوفة تُقِيس على المحور x والمحور y والمحور z

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| sx | double | تطبيقات التحجيم تنطبق على محور x |
| sy | double | تطبيقات التحجيم تنطبق على محور y |
|  | sz | double | تطبيقات التحجيم تنطبق على محور z **مثال:** يوضح الكود التالي كيفية إنشاء مصفوفة لعملية التحجيم. |

```
var t = Matrix4.scale(10, 20, 10);
     var pos = new Vector3(1, 1, 10);
     System.out.printf("Transformed: %s", Matrix4.mul(t, pos));
``` |

**Returns:**
[Matrix4](../../com.aspose.threed/matrix4)
### setTRS(Vector3 translation, Vector3 rotation, Vector3 scale) {#setTRS-com.aspose.threed.Vector3-com.aspose.threed.Vector3-com.aspose.threed.Vector3-}
```
public void setTRS(Vector3 translation, Vector3 rotation, Vector3 scale)
```


يُهيئ المصفوفة بالترجمة/الدوران/التحجيم

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| translation | [Vector3](../../com.aspose.threed/vector3) | تحويل. |
| rotation | [Vector3](../../com.aspose.threed/vector3) | زوايا أويلر للدوران، القيم بالدرجة. |
| scale | [Vector3](../../com.aspose.threed/vector3) | تحجيم. |

### toArray() {#toArray--}
```
public double[] toArray()
```


يحوِّل المصفوفة إلى مصفوفة.

**Returns:**
double[] - المصفوفة.
### toString() {#toString--}
```
public String toString()
```


يرجع java.lang.String الذي يمثل الـ [Matrix4](../../com.aspose.threed/matrix4) الحالي.

**Returns:**
java.lang.String - سلسلة java.lang.String تمثل الـ [Matrix4](../../com.aspose.threed/matrix4) الحالي.
### translate(Vector3 t) {#translate-com.aspose.threed.Vector3-}
```
public static Matrix4 translate(Vector3 t)
```


ينشئ مصفوفة تُترجم على المحور x والمحور y والمحور z

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | t | [Vector3](../../com.aspose.threed/vector3) | إزاحة الترجمة **مثال:** يوضح الكود التالي كيفية إنشاء مصفوفة لعملية الترجمة. |

```
Matrix4 t = Matrix4.translate(new Vector3(10, 0, 0));
     Vector3 pos = new Vector3(1, 1, 10);
     System.out.printf("Transformed: %s", Matrix4.mul(t, pos));
``` |

**Returns:**
[Matrix4](../../com.aspose.threed/matrix4)
### translate(double tx, double ty, double tz) {#translate-double-double-double-}
```
public static Matrix4 translate(double tx, double ty, double tz)
```


ينشئ مصفوفة تُترجم على المحور x والمحور y والمحور z

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| tx | double | إزاحة إحداثي X |
| ty | double | إزاحة إحداثي Y |
|  | tz | double | إزاحة إحداثي Z **Example:** يوضح الكود التالي كيفية إنشاء مصفوفة لعملية الترجمة. |

```
var t = Matrix4.translate(10, 0, 0);
     var pos = new Vector3(1, 1, 10);
     System.out.printf("Transformed: %s", Matrix4.mul(t, pos));
``` |

**Returns:**
[Matrix4](../../com.aspose.threed/matrix4)
### transpose() {#transpose--}
```
public Matrix4 transpose()
```


يقلب هذا الكائن.

**Returns:**
[Matrix4](../../com.aspose.threed/matrix4) - The transposed matrix. **Example:** The following code shows how to transpose a matrix

```
Matrix4 t = Matrix4.translate(0, 10, 9);
     Matrix4 mat = t.transpose();
     System.out.printf("Transposed Matrix: %s", mat);
```
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


---
title: "FMatrix4"
second_title: "مرجع Aspose.3D لـ Java API"
description: "مصفوفة 4×4 بجميع المكونات من نوع float"
type: docs
weight: 58
url: /ar/java/com.aspose.threed/fmatrix4/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.threed.Struct, java.io.Serializable
```
public final class FMatrix4 implements Struct<FMatrix4>, Serializable
```

مصفوفة 4×4 بجميع المكونات من نوع float
## المنشئات

| منشئ | الوصف |
| --- | --- |
| [FMatrix4(float m00, float m01, float m02, float m03, float m10, float m11, float m12, float m13, float m20, float m21, float m22, float m23, float m30, float m31, float m32, float m33)](#FMatrix4-float-float-float-float-float-float-float-float-float-float-float-float-float-float-float-float-) | تهيئة المثيل من [FMatrix4](../../com.aspose.threed/fmatrix4) |
| [FMatrix4(Matrix4 mat)](#FMatrix4-com.aspose.threed.Matrix4-) | تهيئة المثيل من [FMatrix4](../../com.aspose.threed/fmatrix4) من مثيل [Matrix4](../../com.aspose.threed/matrix4). |
| [FMatrix4(FVector4 r0, FVector4 r1, FVector4 r2, FVector4 r3)](#FMatrix4-com.aspose.threed.FVector4-com.aspose.threed.FVector4-com.aspose.threed.FVector4-com.aspose.threed.FVector4-) | يبني المصفوفة من 4 صفوف. |
| [FMatrix4()](#FMatrix4--) |  |
## الحقول

| حقل | الوصف |
| --- | --- |
| [m00](#m00) | الـ m00. |
| [m01](#m01) | الـ m01. |
| [m02](#m02) | الـ m02. |
| [m03](#m03) | الـ m03. |
| [m10](#m10) | الـ m10. |
| [m11](#m11) | الـ m11. |
| [m12](#m12) | الـ m12. |
| [m13](#m13) | الـ m13. |
| [m20](#m20) | الـ m20. |
| [m21](#m21) | الـ m21. |
| [m22](#m22) | الـ m22. |
| [m23](#m23) | الـ m23. |
| [m30](#m30) | الـ m30. |
| [m31](#m31) | الـ m31. |
| [m32](#m32) | الـ m32. |
| [m33](#m33) | الـ m33. |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [clone()](#clone--) |  |
| [concatenate(FMatrix4 m2)](#concatenate-com.aspose.threed.FMatrix4-) | يدمج المصفوفتين |
| [concatenate(Matrix4 m2)](#concatenate-com.aspose.threed.Matrix4-) | يدمج المصفوفتين |
| [copyFrom(FMatrix4 src)](#copyFrom-com.aspose.threed.FMatrix4-) |  |
| [equals(Object obj)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getIdentity()](#getIdentity--) | مصفوفة الهوية |
| [hashCode()](#hashCode--) |  |
| [inverse()](#inverse--) | احسب المصفوفة العكسية للمثيل الحالي. |
| [mul(FMatrix4 left, FMatrix4 right)](#mul-com.aspose.threed.FMatrix4-com.aspose.threed.FMatrix4-) | دمج المصفوفتين |
| [mul(FMatrix4 lhs, float v)](#mul-com.aspose.threed.FMatrix4-float-) | ضرب المصفوفة بالقيمة المزدوجة |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [transpose()](#transpose--) | ينقل هذا المثيل. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### FMatrix4(float m00, float m01, float m02, float m03, float m10, float m11, float m12, float m13, float m20, float m21, float m22, float m23, float m30, float m31, float m32, float m33) {#FMatrix4-float-float-float-float-float-float-float-float-float-float-float-float-float-float-float-float-}
```
public FMatrix4(float m00, float m01, float m02, float m03, float m10, float m11, float m12, float m13, float m20, float m21, float m22, float m23, float m30, float m31, float m32, float m33)
```


تهيئة المثيل من [FMatrix4](../../com.aspose.threed/fmatrix4)

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| m00 | float | ال m[0, 0] |
| m01 | float | ال m[0, 1] |
| m02 | float | ال m[0, 2] |
| m03 | float | ال m[0, 3] |
| m10 | float | ال m[1, 0] |
| m11 | float | ال m[1, 1] |
| m12 | float | ال m[1, 2] |
| m13 | float | ال m[1, 3] |
| m20 | float | ال m[2, 0] |
| m21 | float | ال m[2, 1] |
| m22 | float | ال m[2, 2] |
| m23 | float | ال m[2, 3] |
| m30 | float | ال m[3, 0] |
| m31 | float | ال m[3, 1] |
| m32 | float | ال m[3, 2] |
| m33 | float | ال m[3, 3] |

### FMatrix4(Matrix4 mat) {#FMatrix4-com.aspose.threed.Matrix4-}
```
public FMatrix4(Matrix4 mat)
```


تهيئة المثيل من [FMatrix4](../../com.aspose.threed/fmatrix4) من مثيل [Matrix4](../../com.aspose.threed/matrix4).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| mat | [Matrix4](../../com.aspose.threed/matrix4) | الـ [Matrix4](../../com.aspose.threed/matrix4) مثال. |

### FMatrix4(FVector4 r0, FVector4 r1, FVector4 r2, FVector4 r3) {#FMatrix4-com.aspose.threed.FVector4-com.aspose.threed.FVector4-com.aspose.threed.FVector4-com.aspose.threed.FVector4-}
```
public FMatrix4(FVector4 r0, FVector4 r1, FVector4 r2, FVector4 r3)
```


يبني المصفوفة من 4 صفوف.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| r0 | [FVector4](../../com.aspose.threed/fvector4) | R0. |
| r1 | [FVector4](../../com.aspose.threed/fvector4) | R1. |
| r2 | [FVector4](../../com.aspose.threed/fvector4) | R2. |
| r3 | [FVector4](../../com.aspose.threed/fvector4) | R3. |

### FMatrix4() {#FMatrix4--}
```
public FMatrix4()
```


### m00 {#m00}
```
public float m00
```


الـ m00.

### m01 {#m01}
```
public float m01
```


الـ m01.

### m02 {#m02}
```
public float m02
```


الـ m02.

### m03 {#m03}
```
public float m03
```


الـ m03.

### m10 {#m10}
```
public float m10
```


الـ m10.

### m11 {#m11}
```
public float m11
```


الـ m11.

### m12 {#m12}
```
public float m12
```


الـ m12.

### m13 {#m13}
```
public float m13
```


الـ m13.

### m20 {#m20}
```
public float m20
```


الـ m20.

### m21 {#m21}
```
public float m21
```


الـ m21.

### m22 {#m22}
```
public float m22
```


الـ m22.

### m23 {#m23}
```
public float m23
```


الـ m23.

### m30 {#m30}
```
public float m30
```


الـ m30.

### m31 {#m31}
```
public float m31
```


الـ m31.

### m32 {#m32}
```
public float m32
```


الـ m32.

### m33 {#m33}
```
public float m33
```


الـ m33.

### clone() {#clone--}
```
public FMatrix4 clone()
```


استنساخ الكائن الحالي

**Returns:**
[FMatrix4](../../com.aspose.threed/fmatrix4)
### concatenate(FMatrix4 m2) {#concatenate-com.aspose.threed.FMatrix4-}
```
public FMatrix4 concatenate(FMatrix4 m2)
```


يدمج المصفوفتين

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| m2 | [FMatrix4](../../com.aspose.threed/fmatrix4) | M2. |

**Returns:**
[FMatrix4](../../com.aspose.threed/fmatrix4) - New matrix4
### concatenate(Matrix4 m2) {#concatenate-com.aspose.threed.Matrix4-}
```
public FMatrix4 concatenate(Matrix4 m2)
```


يدمج المصفوفتين

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| m2 | [Matrix4](../../com.aspose.threed/matrix4) | M2. |

**Returns:**
[FMatrix4](../../com.aspose.threed/fmatrix4) - New matrix4
### copyFrom(FMatrix4 src) {#copyFrom-com.aspose.threed.FMatrix4-}
```
public void copyFrom(FMatrix4 src)
```




**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| src | [FMatrix4](../../com.aspose.threed/fmatrix4) |  |

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
### getIdentity() {#getIdentity--}
```
public static FMatrix4 getIdentity()
```


مصفوفة الهوية

**Returns:**
[FMatrix4](../../com.aspose.threed/fmatrix4) - The identity matrix
### hashCode() {#hashCode--}
```
public int hashCode()
```




**Returns:**
int
### inverse() {#inverse--}
```
public FMatrix4 inverse()
```


احسب المصفوفة العكسية للمثيل الحالي.

**Returns:**
[FMatrix4](../../com.aspose.threed/fmatrix4) - Inverse matrix4
### mul(FMatrix4 left, FMatrix4 right) {#mul-com.aspose.threed.FMatrix4-com.aspose.threed.FMatrix4-}
```
public static FMatrix4 mul(FMatrix4 left, FMatrix4 right)
```


دمج المصفوفتين

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| left | [FMatrix4](../../com.aspose.threed/fmatrix4) | المصفوفة اليسرى للدمج |
| right | [FMatrix4](../../com.aspose.threed/fmatrix4) | المصفوفة اليمنى للدمج |

**Returns:**
[FMatrix4](../../com.aspose.threed/fmatrix4) - The concatenated matrix.
### mul(FMatrix4 lhs, float v) {#mul-com.aspose.threed.FMatrix4-float-}
```
public static FMatrix4 mul(FMatrix4 lhs, float v)
```


ضرب المصفوفة بالقيمة المزدوجة

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| lhs | [FMatrix4](../../com.aspose.threed/fmatrix4) | Lhs. |
| v | float | V. |

**Returns:**
[FMatrix4](../../com.aspose.threed/fmatrix4) - Result matrix
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### transpose() {#transpose--}
```
public FMatrix4 transpose()
```


ينقل هذا المثيل.

**Returns:**
[FMatrix4](../../com.aspose.threed/fmatrix4) - The transposed matrix.
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


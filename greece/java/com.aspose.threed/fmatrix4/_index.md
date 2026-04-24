---
title: FMatrix4
second_title: Aspose.3D for Java API Reference
description: Μήτρα 4x4 με όλα τα στοιχεία τύπου float
type: docs
weight: 58
url: /el/java/com.aspose.threed/fmatrix4/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.threed.Struct, java.io.Serializable
```
public final class FMatrix4 implements Struct<FMatrix4>, Serializable
```

Μήτρα 4x4 με όλα τα στοιχεία τύπου float
## Constructors

| Constructor | Περιγραφή |
| --- | --- |
| [FMatrix4(float m00, float m01, float m02, float m03, float m10, float m11, float m12, float m13, float m20, float m21, float m22, float m23, float m30, float m31, float m32, float m33)](#FMatrix4-float-float-float-float-float-float-float-float-float-float-float-float-float-float-float-float-) | Αρχικοποιήστε την παρουσία του [FMatrix4](../../com.aspose.threed/fmatrix4) |
| [FMatrix4(Matrix4 mat)](#FMatrix4-com.aspose.threed.Matrix4-) | Αρχικοποιήστε το αντικείμενο του [FMatrix4](../../com.aspose.threed/fmatrix4) από ένα αντικείμενο του [Matrix4](../../com.aspose.threed/matrix4). |
| [FMatrix4(FVector4 r0, FVector4 r1, FVector4 r2, FVector4 r3)](#FMatrix4-com.aspose.threed.FVector4-com.aspose.threed.FVector4-com.aspose.threed.FVector4-com.aspose.threed.FVector4-) | Δημιουργεί μήτρα από 4 σειρές. |
| [FMatrix4()](#FMatrix4--) |  |
## Πεδία

| Πεδίο | Περιγραφή |
| --- | --- |
| [m00](#m00) | Το m00. |
| [m01](#m01) | Το m01. |
| [m02](#m02) | Το m02. |
| [m03](#m03) | Το m03. |
| [m10](#m10) | Το m10. |
| [m11](#m11) | Το m11. |
| [m12](#m12) | Το m12. |
| [m13](#m13) | Το m13. |
| [m20](#m20) | Το m20. |
| [m21](#m21) | Το m21. |
| [m22](#m22) | Το m22. |
| [m23](#m23) | Το m23. |
| [m30](#m30) | Το m30. |
| [m31](#m31) | Το m31. |
| [m32](#m32) | Το m32. |
| [m33](#m33) | Το m33. |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [clone()](#clone--) |  |
| [concatenate(FMatrix4 m2)](#concatenate-com.aspose.threed.FMatrix4-) | Συνενώνει τις δύο μήτρες |
| [concatenate(Matrix4 m2)](#concatenate-com.aspose.threed.Matrix4-) | Συνενώνει τις δύο μήτρες |
| [copyFrom(FMatrix4 src)](#copyFrom-com.aspose.threed.FMatrix4-) |  |
| [equals(Object obj)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getIdentity()](#getIdentity--) | Η μοναδιαία μήτρα |
| [hashCode()](#hashCode--) |  |
| [inverse()](#inverse--) | Υπολογίστε την αντίστροφη μήτρα του τρέχοντος αντικειμένου. |
| [mul(FMatrix4 left, FMatrix4 right)](#mul-com.aspose.threed.FMatrix4-com.aspose.threed.FMatrix4-) | Συνενώστε τις δύο μήτρες |
| [mul(FMatrix4 lhs, float v)](#mul-com.aspose.threed.FMatrix4-float-) | Πολλαπλασιάστε τη μήτρα με διπλή τιμή |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [transpose()](#transpose--) | Αντιστρέφει αυτήν την περίπτωση. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### FMatrix4(float m00, float m01, float m02, float m03, float m10, float m11, float m12, float m13, float m20, float m21, float m22, float m23, float m30, float m31, float m32, float m33) {#FMatrix4-float-float-float-float-float-float-float-float-float-float-float-float-float-float-float-float-}
```
public FMatrix4(float m00, float m01, float m02, float m03, float m10, float m11, float m12, float m13, float m20, float m21, float m22, float m23, float m30, float m31, float m32, float m33)
```


Αρχικοποιήστε την παρουσία του [FMatrix4](../../com.aspose.threed/fmatrix4)

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| m00 | float | Το m[0, 0] |
| m01 | float | Το m[0, 1] |
| m02 | float | Το m[0, 2] |
| m03 | float | Το m[0, 3] |
| m10 | float | Το m[1, 0] |
| m11 | float | Το m[1, 1] |
| m12 | float | Το m[1, 2] |
| m13 | float | Το m[1, 3] |
| m20 | float | Το m[2, 0] |
| m21 | float | Το m[2, 1] |
| m22 | float | Το m[2, 2] |
| m23 | float | Το m[2, 3] |
| m30 | float | Το m[3, 0] |
| m31 | float | Το m[3, 1] |
| m32 | float | Το m[3, 2] |
| m33 | float | Το m[3, 3] |

### FMatrix4(Matrix4 mat) {#FMatrix4-com.aspose.threed.Matrix4-}
```
public FMatrix4(Matrix4 mat)
```


Αρχικοποιήστε το αντικείμενο του [FMatrix4](../../com.aspose.threed/fmatrix4) από ένα αντικείμενο του [Matrix4](../../com.aspose.threed/matrix4).

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| mat | [Matrix4](../../com.aspose.threed/matrix4) | Το [Matrix4](../../com.aspose.threed/matrix4) αντίγραφο. |

### FMatrix4(FVector4 r0, FVector4 r1, FVector4 r2, FVector4 r3) {#FMatrix4-com.aspose.threed.FVector4-com.aspose.threed.FVector4-com.aspose.threed.FVector4-com.aspose.threed.FVector4-}
```
public FMatrix4(FVector4 r0, FVector4 r1, FVector4 r2, FVector4 r3)
```


Δημιουργεί μήτρα από 4 σειρές.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
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


Το m00.

### m01 {#m01}
```
public float m01
```


Το m01.

### m02 {#m02}
```
public float m02
```


Το m02.

### m03 {#m03}
```
public float m03
```


Το m03.

### m10 {#m10}
```
public float m10
```


Το m10.

### m11 {#m11}
```
public float m11
```


Το m11.

### m12 {#m12}
```
public float m12
```


Το m12.

### m13 {#m13}
```
public float m13
```


Το m13.

### m20 {#m20}
```
public float m20
```


Το m20.

### m21 {#m21}
```
public float m21
```


Το m21.

### m22 {#m22}
```
public float m22
```


Το m22.

### m23 {#m23}
```
public float m23
```


Το m23.

### m30 {#m30}
```
public float m30
```


Το m30.

### m31 {#m31}
```
public float m31
```


Το m31.

### m32 {#m32}
```
public float m32
```


Το m32.

### m33 {#m33}
```
public float m33
```


Το m33.

### clone() {#clone--}
```
public FMatrix4 clone()
```


Clone current instance

**Returns:**
[FMatrix4](../../com.aspose.threed/fmatrix4)
### concatenate(FMatrix4 m2) {#concatenate-com.aspose.threed.FMatrix4-}
```
public FMatrix4 concatenate(FMatrix4 m2)
```


Συνενώνει τις δύο μήτρες

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| m2 | [FMatrix4](../../com.aspose.threed/fmatrix4) | M2. |

**Returns:**
[FMatrix4](../../com.aspose.threed/fmatrix4) - New matrix4
### concatenate(Matrix4 m2) {#concatenate-com.aspose.threed.Matrix4-}
```
public FMatrix4 concatenate(Matrix4 m2)
```


Συνενώνει τις δύο μήτρες

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| m2 | [Matrix4](../../com.aspose.threed/matrix4) | M2. |

**Returns:**
[FMatrix4](../../com.aspose.threed/fmatrix4) - New matrix4
### copyFrom(FMatrix4 src) {#copyFrom-com.aspose.threed.FMatrix4-}
```
public void copyFrom(FMatrix4 src)
```




**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| src | [FMatrix4](../../com.aspose.threed/fmatrix4) |  |

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```




**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
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


Η μοναδιαία μήτρα

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


Υπολογίστε την αντίστροφη μήτρα του τρέχοντος αντικειμένου.

**Returns:**
[FMatrix4](../../com.aspose.threed/fmatrix4) - Inverse matrix4
### mul(FMatrix4 left, FMatrix4 right) {#mul-com.aspose.threed.FMatrix4-com.aspose.threed.FMatrix4-}
```
public static FMatrix4 mul(FMatrix4 left, FMatrix4 right)
```


Συνενώστε τις δύο μήτρες

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| left | [FMatrix4](../../com.aspose.threed/fmatrix4) | Ο αριστερός πίνακας για συνένωση |
| right | [FMatrix4](../../com.aspose.threed/fmatrix4) | Ο δεξιός πίνακας για συνένωση |

**Returns:**
[FMatrix4](../../com.aspose.threed/fmatrix4) - The concatenated matrix.
### mul(FMatrix4 lhs, float v) {#mul-com.aspose.threed.FMatrix4-float-}
```
public static FMatrix4 mul(FMatrix4 lhs, float v)
```


Πολλαπλασιάστε τη μήτρα με διπλή τιμή

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
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


Αντιστρέφει αυτήν την περίπτωση.

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
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |


---
title: "FMatrix4"
second_title: "Aspose.3D for Java API-referentie"
description: "Matrix 4x4 met alle componenten van het type float"
type: docs
weight: 58
url: /nl/java/com.aspose.threed/fmatrix4/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.threed.Struct, java.io.Serializable
```
public final class FMatrix4 implements Struct<FMatrix4>, Serializable
```

Matrix 4x4 met alle componenten van het type float
## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [FMatrix4(float m00, float m01, float m02, float m03, float m10, float m11, float m12, float m13, float m20, float m21, float m22, float m23, float m30, float m31, float m32, float m33)](#FMatrix4-float-float-float-float-float-float-float-float-float-float-float-float-float-float-float-float-) | Initialiseer de instantie van [FMatrix4](../../com.aspose.threed/fmatrix4) |
| [FMatrix4(Matrix4 mat)](#FMatrix4-com.aspose.threed.Matrix4-) | Initialiseer de instantie van [FMatrix4](../../com.aspose.threed/fmatrix4) vanuit een [Matrix4](../../com.aspose.threed/matrix4) instantie. |
| [FMatrix4(FVector4 r0, FVector4 r1, FVector4 r2, FVector4 r3)](#FMatrix4-com.aspose.threed.FVector4-com.aspose.threed.FVector4-com.aspose.threed.FVector4-com.aspose.threed.FVector4-) | Construeert matrix uit 4 rijen. |
| [FMatrix4()](#FMatrix4--) |  |
## Velden

| Veld | Beschrijving |
| --- | --- |
| [m00](#m00) | De m00. |
| [m01](#m01) | De m01. |
| [m02](#m02) | De m02. |
| [m03](#m03) | De m03. |
| [m10](#m10) | De m10. |
| [m11](#m11) | De m11. |
| [m12](#m12) | De m12. |
| [m13](#m13) | De m13. |
| [m20](#m20) | De m20. |
| [m21](#m21) | De m21. |
| [m22](#m22) | De m22. |
| [m23](#m23) | De m23. |
| [m30](#m30) | De m30. |
| [m31](#m31) | De m31. |
| [m32](#m32) | De m32. |
| [m33](#m33) | De m33. |
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [clone()](#clone--) |  |
| [concatenate(FMatrix4 m2)](#concatenate-com.aspose.threed.FMatrix4-) | Voegt de twee matrices samen |
| [concatenate(Matrix4 m2)](#concatenate-com.aspose.threed.Matrix4-) | Voegt de twee matrices samen |
| [copyFrom(FMatrix4 src)](#copyFrom-com.aspose.threed.FMatrix4-) |  |
| [equals(Object obj)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getIdentity()](#getIdentity--) | De identiteitsmatrix |
| [hashCode()](#hashCode--) |  |
| [inverse()](#inverse--) | Bereken de inverse matrix van de huidige instantie. |
| [mul(FMatrix4 left, FMatrix4 right)](#mul-com.aspose.threed.FMatrix4-com.aspose.threed.FMatrix4-) | Concateneer de twee matrices |
| [mul(FMatrix4 lhs, float v)](#mul-com.aspose.threed.FMatrix4-float-) | Vermenigvuldig de matrix met een double-waarde |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [transpose()](#transpose--) | Transponeert deze instantie. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### FMatrix4(float m00, float m01, float m02, float m03, float m10, float m11, float m12, float m13, float m20, float m21, float m22, float m23, float m30, float m31, float m32, float m33) {#FMatrix4-float-float-float-float-float-float-float-float-float-float-float-float-float-float-float-float-}
```
public FMatrix4(float m00, float m01, float m02, float m03, float m10, float m11, float m12, float m13, float m20, float m21, float m22, float m23, float m30, float m31, float m32, float m33)
```


Initialiseer de instantie van [FMatrix4](../../com.aspose.threed/fmatrix4)

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| m00 | float | De m[0, 0] |
| m01 | float | De m[0, 1] |
| m02 | float | De m[0, 2] |
| m03 | float | De m[0, 3] |
| m10 | float | De m[1, 0] |
| m11 | float | De m[1, 1] |
| m12 | float | De m[1, 2] |
| m13 | float | De m[1, 3] |
| m20 | float | De m[2, 0] |
| m21 | float | De m[2, 1] |
| m22 | float | De m[2, 2] |
| m23 | float | De m[2, 3] |
| m30 | float | De m[3, 0] |
| m31 | float | De m[3, 1] |
| m32 | float | De m[3, 2] |
| m33 | float | De m[3, 3] |

### FMatrix4(Matrix4 mat) {#FMatrix4-com.aspose.threed.Matrix4-}
```
public FMatrix4(Matrix4 mat)
```


Initialiseer de instantie van [FMatrix4](../../com.aspose.threed/fmatrix4) vanuit een [Matrix4](../../com.aspose.threed/matrix4) instantie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| mat | [Matrix4](../../com.aspose.threed/matrix4) | De [Matrix4](../../com.aspose.threed/matrix4) instantie. |

### FMatrix4(FVector4 r0, FVector4 r1, FVector4 r2, FVector4 r3) {#FMatrix4-com.aspose.threed.FVector4-com.aspose.threed.FVector4-com.aspose.threed.FVector4-com.aspose.threed.FVector4-}
```
public FMatrix4(FVector4 r0, FVector4 r1, FVector4 r2, FVector4 r3)
```


Construeert matrix uit 4 rijen.

**Parameters:**
| Parameter | Type | Beschrijving |
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


De m00.

### m01 {#m01}
```
public float m01
```


De m01.

### m02 {#m02}
```
public float m02
```


De m02.

### m03 {#m03}
```
public float m03
```


De m03.

### m10 {#m10}
```
public float m10
```


De m10.

### m11 {#m11}
```
public float m11
```


De m11.

### m12 {#m12}
```
public float m12
```


De m12.

### m13 {#m13}
```
public float m13
```


De m13.

### m20 {#m20}
```
public float m20
```


De m20.

### m21 {#m21}
```
public float m21
```


De m21.

### m22 {#m22}
```
public float m22
```


De m22.

### m23 {#m23}
```
public float m23
```


De m23.

### m30 {#m30}
```
public float m30
```


De m30.

### m31 {#m31}
```
public float m31
```


De m31.

### m32 {#m32}
```
public float m32
```


De m32.

### m33 {#m33}
```
public float m33
```


De m33.

### clone() {#clone--}
```
public FMatrix4 clone()
```


Kloon huidige instantie

**Returns:**
[FMatrix4](../../com.aspose.threed/fmatrix4)
### concatenate(FMatrix4 m2) {#concatenate-com.aspose.threed.FMatrix4-}
```
public FMatrix4 concatenate(FMatrix4 m2)
```


Voegt de twee matrices samen

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| m2 | [FMatrix4](../../com.aspose.threed/fmatrix4) | M2. |

**Returns:**
[FMatrix4](../../com.aspose.threed/fmatrix4) - New matrix4
### concatenate(Matrix4 m2) {#concatenate-com.aspose.threed.Matrix4-}
```
public FMatrix4 concatenate(Matrix4 m2)
```


Voegt de twee matrices samen

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| m2 | [Matrix4](../../com.aspose.threed/matrix4) | M2. |

**Returns:**
[FMatrix4](../../com.aspose.threed/fmatrix4) - New matrix4
### copyFrom(FMatrix4 src) {#copyFrom-com.aspose.threed.FMatrix4-}
```
public void copyFrom(FMatrix4 src)
```




**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| src | [FMatrix4](../../com.aspose.threed/fmatrix4) |  |

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```




**Parameters:**
| Parameter | Type | Beschrijving |
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


De identiteitsmatrix

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


Bereken de inverse matrix van de huidige instantie.

**Returns:**
[FMatrix4](../../com.aspose.threed/fmatrix4) - Inverse matrix4
### mul(FMatrix4 left, FMatrix4 right) {#mul-com.aspose.threed.FMatrix4-com.aspose.threed.FMatrix4-}
```
public static FMatrix4 mul(FMatrix4 left, FMatrix4 right)
```


Concateneer de twee matrices

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| left | [FMatrix4](../../com.aspose.threed/fmatrix4) | De linkermatrix om te concatenaten |
| right | [FMatrix4](../../com.aspose.threed/fmatrix4) | De rechtermatrix om te concatenaten |

**Returns:**
[FMatrix4](../../com.aspose.threed/fmatrix4) - The concatenated matrix.
### mul(FMatrix4 lhs, float v) {#mul-com.aspose.threed.FMatrix4-float-}
```
public static FMatrix4 mul(FMatrix4 lhs, float v)
```


Vermenigvuldig de matrix met een double-waarde

**Parameters:**
| Parameter | Type | Beschrijving |
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


Transponeert deze instantie.

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
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |


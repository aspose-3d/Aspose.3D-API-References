---
title: "FMatrix4"
second_title: "Référence d'API Aspose.3D pour Java"
description: "Matrice 4x4 avec tous les composants de type flottant"
type: docs
weight: 58
url: /fr/java/com.aspose.threed/fmatrix4/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.threed.Struct, java.io.Serializable
```
public final class FMatrix4 implements Struct<FMatrix4>, Serializable
```

Matrice 4x4 avec tous les composants de type flottant
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [FMatrix4(float m00, float m01, float m02, float m03, float m10, float m11, float m12, float m13, float m20, float m21, float m22, float m23, float m30, float m31, float m32, float m33)](#FMatrix4-float-float-float-float-float-float-float-float-float-float-float-float-float-float-float-float-) | Initialise l'instance de [FMatrix4](../../com.aspose.threed/fmatrix4) |
| [FMatrix4(Matrix4 mat)](#FMatrix4-com.aspose.threed.Matrix4-) | Initialisez l'instance de [FMatrix4](../../com.aspose.threed/fmatrix4) à partir d'une instance de [Matrix4](../../com.aspose.threed/matrix4). |
| [FMatrix4(FVector4 r0, FVector4 r1, FVector4 r2, FVector4 r3)](#FMatrix4-com.aspose.threed.FVector4-com.aspose.threed.FVector4-com.aspose.threed.FVector4-com.aspose.threed.FVector4-) | Construit la matrice à partir de 4 lignes. |
| [FMatrix4()](#FMatrix4--) |  |
## Champs

| Champ | Description |
| --- | --- |
| [m00](#m00) | Le m00. |
| [m01](#m01) | Le m01. |
| [m02](#m02) | Le m02. |
| [m03](#m03) | Le m03. |
| [m10](#m10) | Le m10. |
| [m11](#m11) | Le m11. |
| [m12](#m12) | Le m12. |
| [m13](#m13) | Le m13. |
| [m20](#m20) | Le m20. |
| [m21](#m21) | Le m21. |
| [m22](#m22) | Le m22. |
| [m23](#m23) | Le m23. |
| [m30](#m30) | Le m30. |
| [m31](#m31) | Le m31. |
| [m32](#m32) | Le m32. |
| [m33](#m33) | Le m33. |
## Méthodes

| Méthode | Description |
| --- | --- |
| [clone()](#clone--) |  |
| [concatenate(FMatrix4 m2)](#concatenate-com.aspose.threed.FMatrix4-) | Concatène les deux matrices |
| [concatenate(Matrix4 m2)](#concatenate-com.aspose.threed.Matrix4-) | Concatène les deux matrices |
| [copyFrom(FMatrix4 src)](#copyFrom-com.aspose.threed.FMatrix4-) |  |
| [equals(Object obj)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getIdentity()](#getIdentity--) | La matrice identité |
| [hashCode()](#hashCode--) |  |
| [inverse()](#inverse--) | Calcule la matrice inverse de l'instance actuelle. |
| [mul(FMatrix4 left, FMatrix4 right)](#mul-com.aspose.threed.FMatrix4-com.aspose.threed.FMatrix4-) | Concaténer les deux matrices |
| [mul(FMatrix4 lhs, float v)](#mul-com.aspose.threed.FMatrix4-float-) | Multiplie la matrice par une valeur double |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [transpose()](#transpose--) | Transpose cette instance. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### FMatrix4(float m00, float m01, float m02, float m03, float m10, float m11, float m12, float m13, float m20, float m21, float m22, float m23, float m30, float m31, float m32, float m33) {#FMatrix4-float-float-float-float-float-float-float-float-float-float-float-float-float-float-float-float-}
```
public FMatrix4(float m00, float m01, float m02, float m03, float m10, float m11, float m12, float m13, float m20, float m21, float m22, float m23, float m30, float m31, float m32, float m33)
```


Initialise l'instance de [FMatrix4](../../com.aspose.threed/fmatrix4)

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| m00 | float | Le m[0, 0] |
| m01 | float | Le m[0, 1] |
| m02 | float | Le m[0, 2] |
| m03 | float | Le m[0, 3] |
| m10 | float | Le m[1, 0] |
| m11 | float | Le m[1, 1] |
| m12 | float | Le m[1, 2] |
| m13 | float | Le m[1, 3] |
| m20 | float | Le m[2, 0] |
| m21 | float | Le m[2, 1] |
| m22 | float | Le m[2, 2] |
| m23 | float | Le m[2, 3] |
| m30 | float | Le m[3, 0] |
| m31 | float | Le m[3, 1] |
| m32 | float | Le m[3, 2] |
| m33 | float | Le m[3, 3] |

### FMatrix4(Matrix4 mat) {#FMatrix4-com.aspose.threed.Matrix4-}
```
public FMatrix4(Matrix4 mat)
```


Initialisez l'instance de [FMatrix4](../../com.aspose.threed/fmatrix4) à partir d'une instance de [Matrix4](../../com.aspose.threed/matrix4).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| mat | [Matrix4](../../com.aspose.threed/matrix4) | L'instance [Matrix4](../../com.aspose.threed/matrix4). |

### FMatrix4(FVector4 r0, FVector4 r1, FVector4 r2, FVector4 r3) {#FMatrix4-com.aspose.threed.FVector4-com.aspose.threed.FVector4-com.aspose.threed.FVector4-com.aspose.threed.FVector4-}
```
public FMatrix4(FVector4 r0, FVector4 r1, FVector4 r2, FVector4 r3)
```


Construit la matrice à partir de 4 lignes.

**Parameters:**
| Paramètre | Type | Description |
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


Le m00.

### m01 {#m01}
```
public float m01
```


Le m01.

### m02 {#m02}
```
public float m02
```


Le m02.

### m03 {#m03}
```
public float m03
```


Le m03.

### m10 {#m10}
```
public float m10
```


Le m10.

### m11 {#m11}
```
public float m11
```


Le m11.

### m12 {#m12}
```
public float m12
```


Le m12.

### m13 {#m13}
```
public float m13
```


Le m13.

### m20 {#m20}
```
public float m20
```


Le m20.

### m21 {#m21}
```
public float m21
```


Le m21.

### m22 {#m22}
```
public float m22
```


Le m22.

### m23 {#m23}
```
public float m23
```


Le m23.

### m30 {#m30}
```
public float m30
```


Le m30.

### m31 {#m31}
```
public float m31
```


Le m31.

### m32 {#m32}
```
public float m32
```


Le m32.

### m33 {#m33}
```
public float m33
```


Le m33.

### clone() {#clone--}
```
public FMatrix4 clone()
```


Cloner l'instance actuelle

**Returns:**
[FMatrix4](../../com.aspose.threed/fmatrix4)
### concatenate(FMatrix4 m2) {#concatenate-com.aspose.threed.FMatrix4-}
```
public FMatrix4 concatenate(FMatrix4 m2)
```


Concatène les deux matrices

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| m2 | [FMatrix4](../../com.aspose.threed/fmatrix4) | M2. |

**Returns:**
[FMatrix4](../../com.aspose.threed/fmatrix4) - New matrix4
### concatenate(Matrix4 m2) {#concatenate-com.aspose.threed.Matrix4-}
```
public FMatrix4 concatenate(Matrix4 m2)
```


Concatène les deux matrices

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| m2 | [Matrix4](../../com.aspose.threed/matrix4) | M2. |

**Returns:**
[FMatrix4](../../com.aspose.threed/fmatrix4) - New matrix4
### copyFrom(FMatrix4 src) {#copyFrom-com.aspose.threed.FMatrix4-}
```
public void copyFrom(FMatrix4 src)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| src | [FMatrix4](../../com.aspose.threed/fmatrix4) |  |

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```




**Parameters:**
| Paramètre | Type | Description |
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


La matrice identité

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


Calcule la matrice inverse de l'instance actuelle.

**Returns:**
[FMatrix4](../../com.aspose.threed/fmatrix4) - Inverse matrix4
### mul(FMatrix4 left, FMatrix4 right) {#mul-com.aspose.threed.FMatrix4-com.aspose.threed.FMatrix4-}
```
public static FMatrix4 mul(FMatrix4 left, FMatrix4 right)
```


Concaténer les deux matrices

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| left | [FMatrix4](../../com.aspose.threed/fmatrix4) | La matrice gauche à concaténer |
| right | [FMatrix4](../../com.aspose.threed/fmatrix4) | La matrice droite à concaténer |

**Returns:**
[FMatrix4](../../com.aspose.threed/fmatrix4) - The concatenated matrix.
### mul(FMatrix4 lhs, float v) {#mul-com.aspose.threed.FMatrix4-float-}
```
public static FMatrix4 mul(FMatrix4 lhs, float v)
```


Multiplie la matrice par une valeur double

**Parameters:**
| Paramètre | Type | Description |
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


Transpose cette instance.

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
| Paramètre | Type | Description |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |


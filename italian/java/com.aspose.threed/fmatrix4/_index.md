---
title: "FMatrix4"
second_title: "Aspose.3D for Java API Reference"
description: "Matrice 4x4 con tutti i componenti di tipo float"
type: docs
weight: 58
url: /it/java/com.aspose.threed/fmatrix4/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.threed.Struct, java.io.Serializable
```
public final class FMatrix4 implements Struct<FMatrix4>, Serializable
```

Matrice 4x4 con tutti i componenti di tipo float
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [FMatrix4(float m00, float m01, float m02, float m03, float m10, float m11, float m12, float m13, float m20, float m21, float m22, float m23, float m30, float m31, float m32, float m33)](#FMatrix4-float-float-float-float-float-float-float-float-float-float-float-float-float-float-float-float-) | Inizializza l'istanza di [FMatrix4](../../com.aspose.threed/fmatrix4) |
| [FMatrix4(Matrix4 mat)](#FMatrix4-com.aspose.threed.Matrix4-) | Inizializza l'istanza di [FMatrix4](../../com.aspose.threed/fmatrix4) da un'istanza di [Matrix4](../../com.aspose.threed/matrix4). |
| [FMatrix4(FVector4 r0, FVector4 r1, FVector4 r2, FVector4 r3)](#FMatrix4-com.aspose.threed.FVector4-com.aspose.threed.FVector4-com.aspose.threed.FVector4-com.aspose.threed.FVector4-) | Costruisce la matrice da 4 righe. |
| [FMatrix4()](#FMatrix4--) |  |
## Campi

| Campo | Descrizione |
| --- | --- |
| [m00](#m00) | Il m00. |
| [m01](#m01) | Il m01. |
| [m02](#m02) | Il m02. |
| [m03](#m03) | Il m03. |
| [m10](#m10) | Il m10. |
| [m11](#m11) | Il m11. |
| [m12](#m12) | Il m12. |
| [m13](#m13) | Il m13. |
| [m20](#m20) | Il m20. |
| [m21](#m21) | Il m21. |
| [m22](#m22) | Il m22. |
| [m23](#m23) | Il m23. |
| [m30](#m30) | Il m30. |
| [m31](#m31) | Il m31. |
| [m32](#m32) | Il m32. |
| [m33](#m33) | Il m33. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [clone()](#clone--) |  |
| [concatenate(FMatrix4 m2)](#concatenate-com.aspose.threed.FMatrix4-) | Concatena le due matrici |
| [concatenate(Matrix4 m2)](#concatenate-com.aspose.threed.Matrix4-) | Concatena le due matrici |
| [copyFrom(FMatrix4 src)](#copyFrom-com.aspose.threed.FMatrix4-) |  |
| [equals(Object obj)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getIdentity()](#getIdentity--) | La matrice identità |
| [hashCode()](#hashCode--) |  |
| [inverse()](#inverse--) | Calcola la matrice inversa dell'istanza corrente. |
| [mul(FMatrix4 left, FMatrix4 right)](#mul-com.aspose.threed.FMatrix4-com.aspose.threed.FMatrix4-) | Concatena le due matrici |
| [mul(FMatrix4 lhs, float v)](#mul-com.aspose.threed.FMatrix4-float-) | Moltiplica la matrice per un valore double |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [transpose()](#transpose--) | Trasponi questa istanza. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### FMatrix4(float m00, float m01, float m02, float m03, float m10, float m11, float m12, float m13, float m20, float m21, float m22, float m23, float m30, float m31, float m32, float m33) {#FMatrix4-float-float-float-float-float-float-float-float-float-float-float-float-float-float-float-float-}
```
public FMatrix4(float m00, float m01, float m02, float m03, float m10, float m11, float m12, float m13, float m20, float m21, float m22, float m23, float m30, float m31, float m32, float m33)
```


Inizializza l'istanza di [FMatrix4](../../com.aspose.threed/fmatrix4)

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| m00 | float | Il m[0, 0] |
| m01 | float | Il m[0, 1] |
| m02 | float | Il m[0, 2] |
| m03 | float | Il m[0, 3] |
| m10 | float | Il m[1, 0] |
| m11 | float | Il m[1, 1] |
| m12 | float | Il m[1, 2] |
| m13 | float | Il m[1, 3] |
| m20 | float | Il m[2, 0] |
| m21 | float | Il m[2, 1] |
| m22 | float | Il m[2, 2] |
| m23 | float | Il m[2, 3] |
| m30 | float | Il m[3, 0] |
| m31 | float | Il m[3, 1] |
| m32 | float | Il m[3, 2] |
| m33 | float | Il m[3, 3] |

### FMatrix4(Matrix4 mat) {#FMatrix4-com.aspose.threed.Matrix4-}
```
public FMatrix4(Matrix4 mat)
```


Inizializza l'istanza di [FMatrix4](../../com.aspose.threed/fmatrix4) da un'istanza di [Matrix4](../../com.aspose.threed/matrix4).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| mat | [Matrix4](../../com.aspose.threed/matrix4) | L'istanza [Matrix4](../../com.aspose.threed/matrix4). |

### FMatrix4(FVector4 r0, FVector4 r1, FVector4 r2, FVector4 r3) {#FMatrix4-com.aspose.threed.FVector4-com.aspose.threed.FVector4-com.aspose.threed.FVector4-com.aspose.threed.FVector4-}
```
public FMatrix4(FVector4 r0, FVector4 r1, FVector4 r2, FVector4 r3)
```


Costruisce la matrice da 4 righe.

**Parameters:**
| Parametro | Tipo | Descrizione |
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


Il m00.

### m01 {#m01}
```
public float m01
```


Il m01.

### m02 {#m02}
```
public float m02
```


Il m02.

### m03 {#m03}
```
public float m03
```


Il m03.

### m10 {#m10}
```
public float m10
```


Il m10.

### m11 {#m11}
```
public float m11
```


Il m11.

### m12 {#m12}
```
public float m12
```


Il m12.

### m13 {#m13}
```
public float m13
```


Il m13.

### m20 {#m20}
```
public float m20
```


Il m20.

### m21 {#m21}
```
public float m21
```


Il m21.

### m22 {#m22}
```
public float m22
```


Il m22.

### m23 {#m23}
```
public float m23
```


Il m23.

### m30 {#m30}
```
public float m30
```


Il m30.

### m31 {#m31}
```
public float m31
```


Il m31.

### m32 {#m32}
```
public float m32
```


Il m32.

### m33 {#m33}
```
public float m33
```


Il m33.

### clone() {#clone--}
```
public FMatrix4 clone()
```


Clona l'istanza corrente

**Returns:**
[FMatrix4](../../com.aspose.threed/fmatrix4)
### concatenate(FMatrix4 m2) {#concatenate-com.aspose.threed.FMatrix4-}
```
public FMatrix4 concatenate(FMatrix4 m2)
```


Concatena le due matrici

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| m2 | [FMatrix4](../../com.aspose.threed/fmatrix4) | M2. |

**Returns:**
[FMatrix4](../../com.aspose.threed/fmatrix4) - New matrix4
### concatenate(Matrix4 m2) {#concatenate-com.aspose.threed.Matrix4-}
```
public FMatrix4 concatenate(Matrix4 m2)
```


Concatena le due matrici

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| m2 | [Matrix4](../../com.aspose.threed/matrix4) | M2. |

**Returns:**
[FMatrix4](../../com.aspose.threed/fmatrix4) - New matrix4
### copyFrom(FMatrix4 src) {#copyFrom-com.aspose.threed.FMatrix4-}
```
public void copyFrom(FMatrix4 src)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| src | [FMatrix4](../../com.aspose.threed/fmatrix4) |  |

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
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


La matrice identità

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


Calcola la matrice inversa dell'istanza corrente.

**Returns:**
[FMatrix4](../../com.aspose.threed/fmatrix4) - Inverse matrix4
### mul(FMatrix4 left, FMatrix4 right) {#mul-com.aspose.threed.FMatrix4-com.aspose.threed.FMatrix4-}
```
public static FMatrix4 mul(FMatrix4 left, FMatrix4 right)
```


Concatena le due matrici

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| left | [FMatrix4](../../com.aspose.threed/fmatrix4) | La matrice sinistra da concatenare |
| right | [FMatrix4](../../com.aspose.threed/fmatrix4) | La matrice destra da concatenare |

**Returns:**
[FMatrix4](../../com.aspose.threed/fmatrix4) - The concatenated matrix.
### mul(FMatrix4 lhs, float v) {#mul-com.aspose.threed.FMatrix4-float-}
```
public static FMatrix4 mul(FMatrix4 lhs, float v)
```


Moltiplica la matrice per un valore double

**Parameters:**
| Parametro | Tipo | Descrizione |
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


Trasponi questa istanza.

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
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |


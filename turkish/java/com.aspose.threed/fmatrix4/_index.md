---
title: "FMatrix4"
second_title: "Aspose.3D for Java API Referansı"
description: "Tüm bileşenleri float tipinde olan 4x4 matris"
type: docs
weight: 58
url: /tr/java/com.aspose.threed/fmatrix4/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.threed.Struct, java.io.Serializable
```
public final class FMatrix4 implements Struct<FMatrix4>, Serializable
```

Tüm bileşenleri float tipinde olan 4x4 matris
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [FMatrix4(float m00, float m01, float m02, float m03, float m10, float m11, float m12, float m13, float m20, float m21, float m22, float m23, float m30, float m31, float m32, float m33)](#FMatrix4-float-float-float-float-float-float-float-float-float-float-float-float-float-float-float-float-) | [FMatrix4](../../com.aspose.threed/fmatrix4) örneğini başlat. |
| [FMatrix4(Matrix4 mat)](#FMatrix4-com.aspose.threed.Matrix4-) | Bir [Matrix4](../../com.aspose.threed/matrix4) örneğinden [FMatrix4](../../com.aspose.threed/fmatrix4) örneğini başlatın. |
| [FMatrix4(FVector4 r0, FVector4 r1, FVector4 r2, FVector4 r3)](#FMatrix4-com.aspose.threed.FVector4-com.aspose.threed.FVector4-com.aspose.threed.FVector4-com.aspose.threed.FVector4-) | Matrisi 4 satırdan oluşturur. |
| [FMatrix4()](#FMatrix4--) |  |
## Alanlar

| Alan | Açıklama |
| --- | --- |
| [m00](#m00) | m00. |
| [m01](#m01) | m01. |
| [m02](#m02) | m02. |
| [m03](#m03) | m03. |
| [m10](#m10) | m10. |
| [m11](#m11) | m11. |
| [m12](#m12) | m12. |
| [m13](#m13) | m13. |
| [m20](#m20) | m20. |
| [m21](#m21) | m21. |
| [m22](#m22) | m22. |
| [m23](#m23) | m23. |
| [m30](#m30) | m30. |
| [m31](#m31) | m31. |
| [m32](#m32) | m32. |
| [m33](#m33) | m33. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [clone()](#clone--) |  |
| [concatenate(FMatrix4 m2)](#concatenate-com.aspose.threed.FMatrix4-) | İki matrisi birleştirir |
| [concatenate(Matrix4 m2)](#concatenate-com.aspose.threed.Matrix4-) | İki matrisi birleştirir |
| [copyFrom(FMatrix4 src)](#copyFrom-com.aspose.threed.FMatrix4-) |  |
| [equals(Object obj)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getIdentity()](#getIdentity--) | Birim matris |
| [hashCode()](#hashCode--) |  |
| [inverse()](#inverse--) | Geçerli örneğin ters matrisini hesaplar. |
| [mul(FMatrix4 left, FMatrix4 right)](#mul-com.aspose.threed.FMatrix4-com.aspose.threed.FMatrix4-) | İki matrisi birleştir |
| [mul(FMatrix4 lhs, float v)](#mul-com.aspose.threed.FMatrix4-float-) | Matrisi ve çift değeri çarpar |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [transpose()](#transpose--) | Bu örneği transpoze eder. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### FMatrix4(float m00, float m01, float m02, float m03, float m10, float m11, float m12, float m13, float m20, float m21, float m22, float m23, float m30, float m31, float m32, float m33) {#FMatrix4-float-float-float-float-float-float-float-float-float-float-float-float-float-float-float-float-}
```
public FMatrix4(float m00, float m01, float m02, float m03, float m10, float m11, float m12, float m13, float m20, float m21, float m22, float m23, float m30, float m31, float m32, float m33)
```


[FMatrix4](../../com.aspose.threed/fmatrix4) örneğini başlat.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| m00 | float | Bu m[0, 0] |
| m01 | float | Bu m[0, 1] |
| m02 | float | Bu m[0, 2] |
| m03 | float | Bu m[0, 3] |
| m10 | float | Bu m[1, 0] |
| m11 | float | Bu m[1, 1] |
| m12 | float | Bu m[1, 2] |
| m13 | float | Bu m[1, 3] |
| m20 | float | Bu m[2, 0] |
| m21 | float | Bu m[2, 1] |
| m22 | float | Bu m[2, 2] |
| m23 | float | Bu m[2, 3] |
| m30 | float | Bu m[3, 0] |
| m31 | float | m[3, 1] |
| m32 | float | m[3, 2] |
| m33 | float | m[3, 3] |

### FMatrix4(Matrix4 mat) {#FMatrix4-com.aspose.threed.Matrix4-}
```
public FMatrix4(Matrix4 mat)
```


Bir [Matrix4](../../com.aspose.threed/matrix4) örneğinden [FMatrix4](../../com.aspose.threed/fmatrix4) örneğini başlatın.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| mat | [Matrix4](../../com.aspose.threed/matrix4) | Bu [Matrix4](../../com.aspose.threed/matrix4) örneği. |

### FMatrix4(FVector4 r0, FVector4 r1, FVector4 r2, FVector4 r3) {#FMatrix4-com.aspose.threed.FVector4-com.aspose.threed.FVector4-com.aspose.threed.FVector4-com.aspose.threed.FVector4-}
```
public FMatrix4(FVector4 r0, FVector4 r1, FVector4 r2, FVector4 r3)
```


Matrisi 4 satırdan oluşturur.

**Parameters:**
| Parametre | Tür | Açıklama |
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


m00.

### m01 {#m01}
```
public float m01
```


m01.

### m02 {#m02}
```
public float m02
```


m02.

### m03 {#m03}
```
public float m03
```


m03.

### m10 {#m10}
```
public float m10
```


m10.

### m11 {#m11}
```
public float m11
```


m11.

### m12 {#m12}
```
public float m12
```


m12.

### m13 {#m13}
```
public float m13
```


m13.

### m20 {#m20}
```
public float m20
```


m20.

### m21 {#m21}
```
public float m21
```


m21.

### m22 {#m22}
```
public float m22
```


m22.

### m23 {#m23}
```
public float m23
```


m23.

### m30 {#m30}
```
public float m30
```


m30.

### m31 {#m31}
```
public float m31
```


m31.

### m32 {#m32}
```
public float m32
```


m32.

### m33 {#m33}
```
public float m33
```


m33.

### clone() {#clone--}
```
public FMatrix4 clone()
```


Mevcut örneği kopyala

**Returns:**
[FMatrix4](../../com.aspose.threed/fmatrix4)
### concatenate(FMatrix4 m2) {#concatenate-com.aspose.threed.FMatrix4-}
```
public FMatrix4 concatenate(FMatrix4 m2)
```


İki matrisi birleştirir

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| m2 | [FMatrix4](../../com.aspose.threed/fmatrix4) | M2. |

**Returns:**
[FMatrix4](../../com.aspose.threed/fmatrix4) - New matrix4
### concatenate(Matrix4 m2) {#concatenate-com.aspose.threed.Matrix4-}
```
public FMatrix4 concatenate(Matrix4 m2)
```


İki matrisi birleştirir

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| m2 | [Matrix4](../../com.aspose.threed/matrix4) | M2. |

**Returns:**
[FMatrix4](../../com.aspose.threed/fmatrix4) - New matrix4
### copyFrom(FMatrix4 src) {#copyFrom-com.aspose.threed.FMatrix4-}
```
public void copyFrom(FMatrix4 src)
```




**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| src | [FMatrix4](../../com.aspose.threed/fmatrix4) |  |

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```




**Parameters:**
| Parametre | Tür | Açıklama |
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


Birim matris

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


Geçerli örneğin ters matrisini hesaplar.

**Returns:**
[FMatrix4](../../com.aspose.threed/fmatrix4) - Inverse matrix4
### mul(FMatrix4 left, FMatrix4 right) {#mul-com.aspose.threed.FMatrix4-com.aspose.threed.FMatrix4-}
```
public static FMatrix4 mul(FMatrix4 left, FMatrix4 right)
```


İki matrisi birleştir

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| left | [FMatrix4](../../com.aspose.threed/fmatrix4) | Birleştirilecek sol matris |
| right | [FMatrix4](../../com.aspose.threed/fmatrix4) | Birleştirilecek sağ matris |

**Returns:**
[FMatrix4](../../com.aspose.threed/fmatrix4) - The concatenated matrix.
### mul(FMatrix4 lhs, float v) {#mul-com.aspose.threed.FMatrix4-float-}
```
public static FMatrix4 mul(FMatrix4 lhs, float v)
```


Matrisi ve çift değeri çarpar

**Parameters:**
| Parametre | Tür | Açıklama |
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


Bu örneği transpoze eder.

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
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |


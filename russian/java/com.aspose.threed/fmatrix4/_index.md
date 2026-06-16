---
title: "FMatrix4"
second_title: "Справочник API Aspose.3D для Java"
description: "Матрица 4x4 со всеми компонентами типа float"
type: docs
weight: 58
url: /ru/java/com.aspose.threed/fmatrix4/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.threed.Struct, java.io.Serializable
```
public final class FMatrix4 implements Struct<FMatrix4>, Serializable
```

Матрица 4x4 со всеми компонентами типа float
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [FMatrix4(float m00, float m01, float m02, float m03, float m10, float m11, float m12, float m13, float m20, float m21, float m22, float m23, float m30, float m31, float m32, float m33)](#FMatrix4-float-float-float-float-float-float-float-float-float-float-float-float-float-float-float-float-) | Инициализировать экземпляр [FMatrix4](../../com.aspose.threed/fmatrix4) |
| [FMatrix4(Matrix4 mat)](#FMatrix4-com.aspose.threed.Matrix4-) | Инициализировать экземпляр [FMatrix4](../../com.aspose.threed/fmatrix4) из экземпляра [Matrix4](../../com.aspose.threed/matrix4). |
| [FMatrix4(FVector4 r0, FVector4 r1, FVector4 r2, FVector4 r3)](#FMatrix4-com.aspose.threed.FVector4-com.aspose.threed.FVector4-com.aspose.threed.FVector4-com.aspose.threed.FVector4-) | Создаёт матрицу из 4 строк. |
| [FMatrix4()](#FMatrix4--) |  |
## Поля

| Поле | Описание |
| --- | --- |
| [m00](#m00) | Элемент m00. |
| [m01](#m01) | Элемент m01. |
| [m02](#m02) | Элемент m02. |
| [m03](#m03) | Элемент m03. |
| [m10](#m10) | Элемент m10. |
| [m11](#m11) | Элемент m11. |
| [m12](#m12) | Элемент m12. |
| [m13](#m13) | Элемент m13. |
| [m20](#m20) | Элемент m20. |
| [m21](#m21) | Элемент m21. |
| [m22](#m22) | Элемент m22. |
| [m23](#m23) | Элемент m23. |
| [m30](#m30) | Элемент m30. |
| [m31](#m31) | Элемент m31. |
| [m32](#m32) | Элемент m32. |
| [m33](#m33) | Элемент m33. |
## Методы

| Метод | Описание |
| --- | --- |
| [clone()](#clone--) |  |
| [concatenate(FMatrix4 m2)](#concatenate-com.aspose.threed.FMatrix4-) | Конкатенирует две матрицы |
| [concatenate(Matrix4 m2)](#concatenate-com.aspose.threed.Matrix4-) | Конкатенирует две матрицы |
| [copyFrom(FMatrix4 src)](#copyFrom-com.aspose.threed.FMatrix4-) |  |
| [equals(Object obj)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getIdentity()](#getIdentity--) | Единичная матрица |
| [hashCode()](#hashCode--) |  |
| [inverse()](#inverse--) | Вычислить обратную матрицу текущего экземпляра. |
| [mul(FMatrix4 left, FMatrix4 right)](#mul-com.aspose.threed.FMatrix4-com.aspose.threed.FMatrix4-) | Конкатенировать две матрицы |
| [mul(FMatrix4 lhs, float v)](#mul-com.aspose.threed.FMatrix4-float-) | Умножить матрицу на значение double |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [transpose()](#transpose--) | Транспонирует этот экземпляр. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### FMatrix4(float m00, float m01, float m02, float m03, float m10, float m11, float m12, float m13, float m20, float m21, float m22, float m23, float m30, float m31, float m32, float m33) {#FMatrix4-float-float-float-float-float-float-float-float-float-float-float-float-float-float-float-float-}
```
public FMatrix4(float m00, float m01, float m02, float m03, float m10, float m11, float m12, float m13, float m20, float m21, float m22, float m23, float m30, float m31, float m32, float m33)
```


Инициализировать экземпляр [FMatrix4](../../com.aspose.threed/fmatrix4)

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| m00 | float | Элемент m[0, 0] |
| m01 | float | Элемент m[0, 1] |
| m02 | float | Элемент m[0, 2] |
| m03 | float | Элемент m[0, 3] |
| m10 | float | Элемент m[1, 0] |
| m11 | float | Элемент m[1, 1] |
| m12 | float | Элемент m[1, 2] |
| m13 | float | Элемент m[1, 3] |
| m20 | float | Элемент m[2, 0] |
| m21 | float | Элемент m[2, 1] |
| m22 | float | Элемент m[2, 2] |
| m23 | float | Элемент m[2, 3] |
| m30 | float | Элемент m[3, 0] |
| m31 | float | Элемент m[3, 1] |
| m32 | float | Элемент m[3, 2] |
| m33 | float | Элемент m[3, 3] |

### FMatrix4(Matrix4 mat) {#FMatrix4-com.aspose.threed.Matrix4-}
```
public FMatrix4(Matrix4 mat)
```


Инициализировать экземпляр [FMatrix4](../../com.aspose.threed/fmatrix4) из экземпляра [Matrix4](../../com.aspose.threed/matrix4).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| mat | [Matrix4](../../com.aspose.threed/matrix4) | Экземпляр [Matrix4](../../com.aspose.threed/matrix4). |

### FMatrix4(FVector4 r0, FVector4 r1, FVector4 r2, FVector4 r3) {#FMatrix4-com.aspose.threed.FVector4-com.aspose.threed.FVector4-com.aspose.threed.FVector4-com.aspose.threed.FVector4-}
```
public FMatrix4(FVector4 r0, FVector4 r1, FVector4 r2, FVector4 r3)
```


Создаёт матрицу из 4 строк.

**Parameters:**
| Параметр | Тип | Описание |
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


Элемент m00.

### m01 {#m01}
```
public float m01
```


Элемент m01.

### m02 {#m02}
```
public float m02
```


Элемент m02.

### m03 {#m03}
```
public float m03
```


Элемент m03.

### m10 {#m10}
```
public float m10
```


Элемент m10.

### m11 {#m11}
```
public float m11
```


Элемент m11.

### m12 {#m12}
```
public float m12
```


Элемент m12.

### m13 {#m13}
```
public float m13
```


Элемент m13.

### m20 {#m20}
```
public float m20
```


Элемент m20.

### m21 {#m21}
```
public float m21
```


Элемент m21.

### m22 {#m22}
```
public float m22
```


Элемент m22.

### m23 {#m23}
```
public float m23
```


Элемент m23.

### m30 {#m30}
```
public float m30
```


Элемент m30.

### m31 {#m31}
```
public float m31
```


Элемент m31.

### m32 {#m32}
```
public float m32
```


Элемент m32.

### m33 {#m33}
```
public float m33
```


Элемент m33.

### clone() {#clone--}
```
public FMatrix4 clone()
```


Клонировать текущий экземпляр

**Returns:**
[FMatrix4](../../com.aspose.threed/fmatrix4)
### concatenate(FMatrix4 m2) {#concatenate-com.aspose.threed.FMatrix4-}
```
public FMatrix4 concatenate(FMatrix4 m2)
```


Конкатенирует две матрицы

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| m2 | [FMatrix4](../../com.aspose.threed/fmatrix4) | M2. |

**Returns:**
[FMatrix4](../../com.aspose.threed/fmatrix4) - New matrix4
### concatenate(Matrix4 m2) {#concatenate-com.aspose.threed.Matrix4-}
```
public FMatrix4 concatenate(Matrix4 m2)
```


Конкатенирует две матрицы

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| m2 | [Matrix4](../../com.aspose.threed/matrix4) | M2. |

**Returns:**
[FMatrix4](../../com.aspose.threed/fmatrix4) - New matrix4
### copyFrom(FMatrix4 src) {#copyFrom-com.aspose.threed.FMatrix4-}
```
public void copyFrom(FMatrix4 src)
```




**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| src | [FMatrix4](../../com.aspose.threed/fmatrix4) |  |

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```




**Parameters:**
| Параметр | Тип | Описание |
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


Единичная матрица

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


Вычислить обратную матрицу текущего экземпляра.

**Returns:**
[FMatrix4](../../com.aspose.threed/fmatrix4) - Inverse matrix4
### mul(FMatrix4 left, FMatrix4 right) {#mul-com.aspose.threed.FMatrix4-com.aspose.threed.FMatrix4-}
```
public static FMatrix4 mul(FMatrix4 left, FMatrix4 right)
```


Конкатенировать две матрицы

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| left | [FMatrix4](../../com.aspose.threed/fmatrix4) | Левая матрица для конкатенации |
| right | [FMatrix4](../../com.aspose.threed/fmatrix4) | Правая матрица для конкатенации |

**Returns:**
[FMatrix4](../../com.aspose.threed/fmatrix4) - The concatenated matrix.
### mul(FMatrix4 lhs, float v) {#mul-com.aspose.threed.FMatrix4-float-}
```
public static FMatrix4 mul(FMatrix4 lhs, float v)
```


Умножить матрицу на значение double

**Parameters:**
| Параметр | Тип | Описание |
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


Транспонирует этот экземпляр.

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
| Параметр | Тип | Описание |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |


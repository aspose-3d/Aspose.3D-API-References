---
title: "FMatrix4"
second_title: "Aspose.3D for Java API 参考"
description: "所有分量为 float 类型的 4x4 矩阵"
type: docs
weight: 58
url: /zh/java/com.aspose.threed/fmatrix4/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.threed.Struct, java.io.Serializable
```
public final class FMatrix4 implements Struct<FMatrix4>, Serializable
```

所有分量为 float 类型的 4x4 矩阵
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [FMatrix4(float m00, float m01, float m02, float m03, float m10, float m11, float m12, float m13, float m20, float m21, float m22, float m23, float m30, float m31, float m32, float m33)](#FMatrix4-float-float-float-float-float-float-float-float-float-float-float-float-float-float-float-float-) | 初始化 [FMatrix4](../../com.aspose.threed/fmatrix4) 的实例 |
| [FMatrix4(Matrix4 mat)](#FMatrix4-com.aspose.threed.Matrix4-) | 从 [Matrix4](../../com.aspose.threed/matrix4) 实例初始化 [FMatrix4](../../com.aspose.threed/fmatrix4) 实例。 |
| [FMatrix4(FVector4 r0, FVector4 r1, FVector4 r2, FVector4 r3)](#FMatrix4-com.aspose.threed.FVector4-com.aspose.threed.FVector4-com.aspose.threed.FVector4-com.aspose.threed.FVector4-) | 从 4 行构造矩阵。 |
| [FMatrix4()](#FMatrix4--) |  |
## 字段

| 字段 | 描述 |
| --- | --- |
| [m00](#m00) | m00。 |
| [m01](#m01) | m01。 |
| [m02](#m02) | m02。 |
| [m03](#m03) | m03。 |
| [m10](#m10) | m10。 |
| [m11](#m11) | m11。 |
| [m12](#m12) | m12。 |
| [m13](#m13) | 第 m13。 |
| [m20](#m20) | 第 m20。 |
| [m21](#m21) | 第 m21。 |
| [m22](#m22) | 第 m22。 |
| [m23](#m23) | 第 m23。 |
| [m30](#m30) | 第 m30。 |
| [m31](#m31) | 第 m31。 |
| [m32](#m32) | 第 m32。 |
| [m33](#m33) | 第 m33。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [clone()](#clone--) |  |
| [concatenate(FMatrix4 m2)](#concatenate-com.aspose.threed.FMatrix4-) | 连接两个矩阵 |
| [concatenate(Matrix4 m2)](#concatenate-com.aspose.threed.Matrix4-) | 连接两个矩阵 |
| [copyFrom(FMatrix4 src)](#copyFrom-com.aspose.threed.FMatrix4-) |  |
| [equals(Object obj)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getIdentity()](#getIdentity--) | 单位矩阵 |
| [hashCode()](#hashCode--) |  |
| [inverse()](#inverse--) | 计算当前实例的逆矩阵。 |
| [mul(FMatrix4 left, FMatrix4 right)](#mul-com.aspose.threed.FMatrix4-com.aspose.threed.FMatrix4-) | 连接两个矩阵 |
| [mul(FMatrix4 lhs, float v)](#mul-com.aspose.threed.FMatrix4-float-) | 将矩阵与双精度值相乘 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [transpose()](#transpose--) | 转置此实例。 |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### FMatrix4(float m00, float m01, float m02, float m03, float m10, float m11, float m12, float m13, float m20, float m21, float m22, float m23, float m30, float m31, float m32, float m33) {#FMatrix4-float-float-float-float-float-float-float-float-float-float-float-float-float-float-float-float-}
```
public FMatrix4(float m00, float m01, float m02, float m03, float m10, float m11, float m12, float m13, float m20, float m21, float m22, float m23, float m30, float m31, float m32, float m33)
```


初始化 [FMatrix4](../../com.aspose.threed/fmatrix4) 的实例

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| m00 | float | 第 m[0, 0] |
| m01 | float | 第 m[0, 1] |
| m02 | float | 第 m[0, 2] |
| m03 | float | 第 m[0, 3] |
| m10 | float | 第 m[1, 0] |
| m11 | float | 第 m[1, 1] |
| m12 | float | 第 m[1, 2] |
| m13 | float | 第 m[1, 3] |
| m20 | float | 第 m[2, 0] |
| m21 | float | 第 m[2, 1] |
| m22 | float | 第 m[2, 2] |
| m23 | float | 第 m[2, 3] |
| m30 | float | 第 m[3, 0] |
| m31 | float | 该 m[3, 1] |
| m32 | float | 该 m[3, 2] |
| m33 | float | 该 m[3, 3] |

### FMatrix4(Matrix4 mat) {#FMatrix4-com.aspose.threed.Matrix4-}
```
public FMatrix4(Matrix4 mat)
```


从 [Matrix4](../../com.aspose.threed/matrix4) 实例初始化 [FMatrix4](../../com.aspose.threed/fmatrix4) 实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| mat | [Matrix4](../../com.aspose.threed/matrix4) | 该 [Matrix4](../../com.aspose.threed/matrix4) 实例。 |

### FMatrix4(FVector4 r0, FVector4 r1, FVector4 r2, FVector4 r3) {#FMatrix4-com.aspose.threed.FVector4-com.aspose.threed.FVector4-com.aspose.threed.FVector4-com.aspose.threed.FVector4-}
```
public FMatrix4(FVector4 r0, FVector4 r1, FVector4 r2, FVector4 r3)
```


从 4 行构造矩阵。

**Parameters:**
| 参数 | 类型 | 描述 |
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


m00。

### m01 {#m01}
```
public float m01
```


m01。

### m02 {#m02}
```
public float m02
```


m02。

### m03 {#m03}
```
public float m03
```


m03。

### m10 {#m10}
```
public float m10
```


m10。

### m11 {#m11}
```
public float m11
```


m11。

### m12 {#m12}
```
public float m12
```


m12。

### m13 {#m13}
```
public float m13
```


第 m13。

### m20 {#m20}
```
public float m20
```


第 m20。

### m21 {#m21}
```
public float m21
```


第 m21。

### m22 {#m22}
```
public float m22
```


第 m22。

### m23 {#m23}
```
public float m23
```


第 m23。

### m30 {#m30}
```
public float m30
```


第 m30。

### m31 {#m31}
```
public float m31
```


第 m31。

### m32 {#m32}
```
public float m32
```


第 m32。

### m33 {#m33}
```
public float m33
```


第 m33。

### clone() {#clone--}
```
public FMatrix4 clone()
```


克隆当前实例

**Returns:**
[FMatrix4](../../com.aspose.threed/fmatrix4)
### concatenate(FMatrix4 m2) {#concatenate-com.aspose.threed.FMatrix4-}
```
public FMatrix4 concatenate(FMatrix4 m2)
```


连接两个矩阵

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| m2 | [FMatrix4](../../com.aspose.threed/fmatrix4) | M2. |

**Returns:**
[FMatrix4](../../com.aspose.threed/fmatrix4) - New matrix4
### concatenate(Matrix4 m2) {#concatenate-com.aspose.threed.Matrix4-}
```
public FMatrix4 concatenate(Matrix4 m2)
```


连接两个矩阵

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| m2 | [Matrix4](../../com.aspose.threed/matrix4) | M2. |

**Returns:**
[FMatrix4](../../com.aspose.threed/fmatrix4) - New matrix4
### copyFrom(FMatrix4 src) {#copyFrom-com.aspose.threed.FMatrix4-}
```
public void copyFrom(FMatrix4 src)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| src | [FMatrix4](../../com.aspose.threed/fmatrix4) |  |

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| obj | java.lang.Object |  |

**Returns:**
布尔
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


单位矩阵

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


计算当前实例的逆矩阵。

**Returns:**
[FMatrix4](../../com.aspose.threed/fmatrix4) - Inverse matrix4
### mul(FMatrix4 left, FMatrix4 right) {#mul-com.aspose.threed.FMatrix4-com.aspose.threed.FMatrix4-}
```
public static FMatrix4 mul(FMatrix4 left, FMatrix4 right)
```


连接两个矩阵

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| left | [FMatrix4](../../com.aspose.threed/fmatrix4) | 要连接的左矩阵 |
| right | [FMatrix4](../../com.aspose.threed/fmatrix4) | 要连接的右矩阵 |

**Returns:**
[FMatrix4](../../com.aspose.threed/fmatrix4) - The concatenated matrix.
### mul(FMatrix4 lhs, float v) {#mul-com.aspose.threed.FMatrix4-float-}
```
public static FMatrix4 mul(FMatrix4 lhs, float v)
```


将矩阵与双精度值相乘

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| lhs | [FMatrix4](../../com.aspose.threed/fmatrix4) | 左侧。 |
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


转置此实例。

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
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |


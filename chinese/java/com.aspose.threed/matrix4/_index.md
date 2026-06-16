---
title: "Matrix4"
second_title: "Aspose.3D for Java API 参考"
description: "4x4 矩阵实现。"
type: docs
weight: 100
url: /zh/java/com.aspose.threed/matrix4/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.threed.Struct, java.io.Serializable
```
public final class Matrix4 implements Struct<Matrix4>, Serializable
```

4x4 矩阵实现。 **示例:**

```
Matrix4 mat = Matrix4.rotateFromEuler(90, 0, 0);
      Matrix4 mat2 = Matrix4.translate(0, 10, -50);
      Matrix4 transform = Matrix4.mul(mat2, mat);
      Vector4 pos = new Vector4(10, 9, 0, 1);
      Vector4 transformed = Matrix4.mul(transform, pos);
```
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [Matrix4(Vector4 r0, Vector4 r1, Vector4 r2, Vector4 r3)](#Matrix4-com.aspose.threed.Vector4-com.aspose.threed.Vector4-com.aspose.threed.Vector4-com.aspose.threed.Vector4-) | 从 4 行构造矩阵。 |
| [Matrix4(double m00, double m01, double m02, double m03, double m10, double m11, double m12, double m13, double m20, double m21, double m22, double m23, double m30, double m31, double m32, double m33)](#Matrix4-double-double-double-double-double-double-double-double-double-double-double-double-double-double-double-double-) | 初始化一个新的 [Matrix4](../../com.aspose.threed/matrix4) 结构体实例。 |
| [Matrix4(FMatrix4 m)](#Matrix4-com.aspose.threed.FMatrix4-) | 从 [FMatrix4](../../com.aspose.threed/fmatrix4) 实例构造 [Matrix4](../../com.aspose.threed/matrix4) |
| [Matrix4(double[] m)](#Matrix4-double---) | 初始化一个新的 [Matrix4](../../com.aspose.threed/matrix4) 结构体实例。 |
| [Matrix4()](#Matrix4--) |  |
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
| [concatenate(Matrix4 m2)](#concatenate-com.aspose.threed.Matrix4-) | 连接两个矩阵 |
| [copyFrom(Matrix4 src)](#copyFrom-com.aspose.threed.Matrix4-) |  |
| [decompose(Vector3 translation, Vector3 scaling, Quaternion rotation)](#decompose-com.aspose.threed.Vector3-com.aspose.threed.Vector3-com.aspose.threed.Quaternion-) | 分解变换矩阵。 |
| [equals(Object obj)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getDeterminant()](#getDeterminant--) | 获取矩阵的行列式。 |
| [getIdentity()](#getIdentity--) | 获取单位矩阵。 |
| [hashCode()](#hashCode--) |  |
| [inverse()](#inverse--) | 对该实例求逆。 |
| [mul(Matrix4 lhs, Matrix4 rhs)](#mul-com.aspose.threed.Matrix4-com.aspose.threed.Matrix4-) | 将两个矩阵相乘 |
| [mul(Matrix4 lhs, Vector3 v)](#mul-com.aspose.threed.Matrix4-com.aspose.threed.Vector3-) | 将矩阵与 vector3 相乘 |
| [mul(Matrix4 lhs, Vector4 v)](#mul-com.aspose.threed.Matrix4-com.aspose.threed.Vector4-) | 将矩阵与 vector4 相乘 |
| [mul(Matrix4 lhs, double v)](#mul-com.aspose.threed.Matrix4-double-) | 将矩阵与双精度值相乘 |
| [normalize()](#normalize--) | 归一化此实例。 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [rotate(Quaternion q)](#rotate-com.aspose.threed.Quaternion-) | 从四元数创建旋转矩阵 |
| [rotate(double angle, Vector3 axis)](#rotate-double-com.aspose.threed.Vector3-) | 通过旋转角度和轴创建旋转矩阵 |
| [rotateFromEuler(Vector3 eul)](#rotateFromEuler-com.aspose.threed.Vector3-) | 从欧拉角创建旋转矩阵 |
| [rotateFromEuler(double rx, double ry, double rz)](#rotateFromEuler-double-double-double-) | 从欧拉角创建旋转矩阵 |
| [scale(Vector3 s)](#scale-com.aspose.threed.Vector3-) | 创建一个在 x 轴、y 轴和 z 轴上缩放的矩阵。 |
| [scale(double s)](#scale-double-) | 创建一个在 x 轴、y 轴和 z 轴上缩放的矩阵。 |
| [scale(double sx, double sy, double sz)](#scale-double-double-double-) | 创建一个在 x 轴、y 轴和 z 轴上缩放的矩阵。 |
| [setTRS(Vector3 translation, Vector3 rotation, Vector3 scale)](#setTRS-com.aspose.threed.Vector3-com.aspose.threed.Vector3-com.aspose.threed.Vector3-) | 使用平移/旋转/缩放初始化矩阵 |
| [toArray()](#toArray--) | 将矩阵转换为数组。 |
| [toString()](#toString--) | 返回一个表示当前 [Matrix4](../../com.aspose.threed/matrix4) 的 java.lang.String。 |
| [translate(Vector3 t)](#translate-com.aspose.threed.Vector3-) | 创建一个在 x 轴、y 轴和 z 轴上平移的矩阵 |
| [translate(double tx, double ty, double tz)](#translate-double-double-double-) | 创建一个在 x 轴、y 轴和 z 轴上平移的矩阵 |
| [transpose()](#transpose--) | 转置此实例。 |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Matrix4(Vector4 r0, Vector4 r1, Vector4 r2, Vector4 r3) {#Matrix4-com.aspose.threed.Vector4-com.aspose.threed.Vector4-com.aspose.threed.Vector4-com.aspose.threed.Vector4-}
```
public Matrix4(Vector4 r0, Vector4 r1, Vector4 r2, Vector4 r3)
```


从 4 行构造矩阵。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| r0 | [Vector4](../../com.aspose.threed/vector4) | R0. |
| r1 | [Vector4](../../com.aspose.threed/vector4) | R1. |
| r2 | [Vector4](../../com.aspose.threed/vector4) | R2. |
| r3 | [Vector4](../../com.aspose.threed/vector4) | R3. |

### Matrix4(double m00, double m01, double m02, double m03, double m10, double m11, double m12, double m13, double m20, double m21, double m22, double m23, double m30, double m31, double m32, double m33) {#Matrix4-double-double-double-double-double-double-double-double-double-double-double-double-double-double-double-double-}
```
public Matrix4(double m00, double m01, double m02, double m03, double m10, double m11, double m12, double m13, double m20, double m21, double m22, double m23, double m30, double m31, double m32, double m33)
```


初始化一个新的 [Matrix4](../../com.aspose.threed/matrix4) 结构体实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| m00 | double | M00。 |
| m01 | double | M01。 |
| m02 | double | M02。 |
| m03 | double | M03。 |
| m10 | double | M10。 |
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
|  | m33 | double | M33. **Example:** |

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


从 [FMatrix4](../../com.aspose.threed/fmatrix4) 实例构造 [Matrix4](../../com.aspose.threed/matrix4)

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| m | [FMatrix4](../../com.aspose.threed/fmatrix4) |  |

### Matrix4(double[] m) {#Matrix4-double---}
```
public Matrix4(double[] m)
```


初始化一个新的 [Matrix4](../../com.aspose.threed/matrix4) 结构体实例。

**Parameters:**
| 参数 | 类型 | 描述 |
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


m00。

### m01 {#m01}
```
public double m01
```


m01。

### m02 {#m02}
```
public double m02
```


m02。

### m03 {#m03}
```
public double m03
```


m03。

### m10 {#m10}
```
public double m10
```


m10。

### m11 {#m11}
```
public double m11
```


m11。

### m12 {#m12}
```
public double m12
```


m12。

### m13 {#m13}
```
public double m13
```


第 m13。

### m20 {#m20}
```
public double m20
```


第 m20。

### m21 {#m21}
```
public double m21
```


第 m21。

### m22 {#m22}
```
public double m22
```


第 m22。

### m23 {#m23}
```
public double m23
```


第 m23。

### m30 {#m30}
```
public double m30
```


第 m30。

### m31 {#m31}
```
public double m31
```


第 m31。

### m32 {#m32}
```
public double m32
```


第 m32。

### m33 {#m33}
```
public double m33
```


第 m33。

### clone() {#clone--}
```
public Matrix4 clone()
```


克隆当前实例

**Returns:**
[Matrix4](../../com.aspose.threed/matrix4)
### concatenate(Matrix4 m2) {#concatenate-com.aspose.threed.Matrix4-}
```
public Matrix4 concatenate(Matrix4 m2)
```


连接两个矩阵

**Parameters:**
| 参数 | 类型 | 描述 |
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
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| src | [Matrix4](../../com.aspose.threed/matrix4) |  |

### decompose(Vector3 translation, Vector3 scaling, Quaternion rotation) {#decompose-com.aspose.threed.Vector3-com.aspose.threed.Vector3-com.aspose.threed.Quaternion-}
```
public boolean decompose(Vector3 translation, Vector3 scaling, Quaternion rotation)
```


分解变换矩阵。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| translation | [Vector3](../../com.aspose.threed/vector3) | 翻译。 |
| scaling | [Vector3](../../com.aspose.threed/vector3) | 缩放。 |
| rotation | [Quaternion](../../com.aspose.threed/quaternion) | 旋转。 |

**Returns:**
布尔 - 成功时为 True。
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
### getDeterminant() {#getDeterminant--}
```
public double getDeterminant()
```


获取矩阵的行列式。

**Returns:**
double - 矩阵的行列式。
### getIdentity() {#getIdentity--}
```
public static Matrix4 getIdentity()
```


获取单位矩阵。

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


对该实例求逆。

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


将两个矩阵相乘

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| lhs | [Matrix4](../../com.aspose.threed/matrix4) | 左侧。 |
| rhs | [Matrix4](../../com.aspose.threed/matrix4) | Rhs. |

**Returns:**
[Matrix4](../../com.aspose.threed/matrix4) - Result matrix
### mul(Matrix4 lhs, Vector3 v) {#mul-com.aspose.threed.Matrix4-com.aspose.threed.Vector3-}
```
public static Vector3 mul(Matrix4 lhs, Vector3 v)
```


将矩阵与 vector3 相乘

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| lhs | [Matrix4](../../com.aspose.threed/matrix4) | 左侧。 |
| v | [Vector3](../../com.aspose.threed/vector3) | V. |

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - Result matrix
### mul(Matrix4 lhs, Vector4 v) {#mul-com.aspose.threed.Matrix4-com.aspose.threed.Vector4-}
```
public static Vector4 mul(Matrix4 lhs, Vector4 v)
```


将矩阵与 vector4 相乘

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| lhs | [Matrix4](../../com.aspose.threed/matrix4) | 左侧。 |
| v | [Vector4](../../com.aspose.threed/vector4) | V. |

**Returns:**
[Vector4](../../com.aspose.threed/vector4) - Result matrix
### mul(Matrix4 lhs, double v) {#mul-com.aspose.threed.Matrix4-double-}
```
public static Matrix4 mul(Matrix4 lhs, double v)
```


将矩阵与双精度值相乘

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| lhs | [Matrix4](../../com.aspose.threed/matrix4) | 左侧。 |
| v | double | V. |

**Returns:**
[Matrix4](../../com.aspose.threed/matrix4) - Result matrix
### normalize() {#normalize--}
```
public Matrix4 normalize()
```


归一化此实例。

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


从四元数创建旋转矩阵

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | q | [Quaternion](../../com.aspose.threed/quaternion) | 旋转四元数 **Example:** 以下代码展示了如何创建用于旋转操作的矩阵。 |

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


通过旋转角度和轴创建旋转矩阵

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| angle | double | 以弧度旋转角度 |
|  | axis | [Vector3](../../com.aspose.threed/vector3) | 旋转轴 **Example:** 以下代码展示了如何创建用于旋转操作的矩阵。 |

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


从欧拉角创建旋转矩阵

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | eul | [Vector3](../../com.aspose.threed/vector3) | 以弧度表示的旋转 **Example:** 以下代码展示了如何创建用于旋转操作的矩阵。 |

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


从欧拉角创建旋转矩阵

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| rx | double | x 轴的旋转（弧度） |
| ry | double | y 轴的旋转（弧度） |
|  | rz | double | z 轴的旋转（弧度） **Example:** 以下代码展示了如何创建用于旋转操作的矩阵。 |

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


创建一个在 x 轴、y 轴和 z 轴上缩放的矩阵。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | s | [Vector3](../../com.aspose.threed/vector3) | 缩放因子适用于 x 轴、y 轴和 z 轴 **Example:** 以下代码展示了如何创建用于缩放操作的矩阵。 |

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


创建一个在 x 轴、y 轴和 z 轴上缩放的矩阵。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | s | double | 缩放因子适用于所有轴 **Example:** 以下代码展示了如何创建用于缩放操作的矩阵。 |

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


创建一个在 x 轴、y 轴和 z 轴上缩放的矩阵。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| sx | double | 缩放因子适用于 x 轴 |
| sy | double | 缩放因子适用于 y 轴 |
|  | sz | double | 缩放因子适用于 z 轴 **Example:** 以下代码展示了如何创建用于缩放操作的矩阵。 |

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


使用平移/旋转/缩放初始化矩阵

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| translation | [Vector3](../../com.aspose.threed/vector3) | 平移。 |
| rotation | [Vector3](../../com.aspose.threed/vector3) | 用于旋转的欧拉角，字段单位为度。 |
| scale | [Vector3](../../com.aspose.threed/vector3) | 缩放。 |

### toArray() {#toArray--}
```
public double[] toArray()
```


将矩阵转换为数组。

**Returns:**
double[] - 数组。
### toString() {#toString--}
```
public String toString()
```


返回一个表示当前 [Matrix4](../../com.aspose.threed/matrix4) 的 java.lang.String。

**Returns:**
java.lang.String - 表示当前 [Matrix4](../../com.aspose.threed/matrix4) 的 java.lang.String。
### translate(Vector3 t) {#translate-com.aspose.threed.Vector3-}
```
public static Matrix4 translate(Vector3 t)
```


创建一个在 x 轴、y 轴和 z 轴上平移的矩阵

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | t | [Vector3](../../com.aspose.threed/vector3) | 平移偏移 **Example:** 以下代码展示了如何创建用于平移操作的矩阵。 |

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


创建一个在 x 轴、y 轴和 z 轴上平移的矩阵

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| tx | double | X 坐标偏移 |
| ty | double | Y 坐标偏移 |
|  | tz | double | Z 坐标偏移 **示例：** 以下代码展示了如何创建用于平移操作的矩阵。 |

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


转置此实例。

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


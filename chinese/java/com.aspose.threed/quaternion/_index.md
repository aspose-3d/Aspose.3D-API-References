---
title: "Quaternion"
second_title: "Aspose.3D for Java API 参考"
description: "四元数通常用于在计算机图形学中执行旋转。"
type: docs
weight: 143
url: /zh/java/com.aspose.threed/quaternion/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.threed.Struct, java.io.Serializable
```
public final class Quaternion implements Struct<Quaternion>, Serializable
```

四元数通常用于在计算机图形学中执行旋转。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [Quaternion(double w, double x, double y, double z)](#Quaternion-double-double-double-double-) | 初始化 [Quaternion](../../com.aspose.threed/quaternion) 类的新实例。 |
| [Quaternion()](#Quaternion--) |  |
## 字段

| 字段 | 描述 |
| --- | --- |
| [IDENTITY](#IDENTITY) | 单位四元数。 |
| [w](#w) | w 分量。 |
| [x](#x) | x 分量。 |
| [y](#y) | y 分量。 |
| [z](#z) | z 分量。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [add(Quaternion lhs, Quaternion rhs)](#add-com.aspose.threed.Quaternion-com.aspose.threed.Quaternion-) | 运算符重载 + |
| [clone()](#clone--) |  |
| [concat(Quaternion rhs)](#concat-com.aspose.threed.Quaternion-) | 连接两个四元数 |
| [conjugate()](#conjugate--) | 返回当前四元数的共轭四元数 |
| [copyFrom(Quaternion src)](#copyFrom-com.aspose.threed.Quaternion-) |  |
| [div(Quaternion lhs, double rhs)](#div-com.aspose.threed.Quaternion-double-) | 运算符重载 / |
| [dot(Quaternion q)](#dot-com.aspose.threed.Quaternion-) | 点积 |
| [equals(Object obj)](#equals-java.lang.Object-) | 检查两个四元数是否相等 |
| [eulerAngles()](#eulerAngles--) | 将四元数转换为由欧拉角表示的旋转，所有分量均为弧度。 |
| [fromAngleAxis(double a, Vector3 axis)](#fromAngleAxis-double-com.aspose.threed.Vector3-) | 围绕给定轴创建四元数并顺时针旋转 |
| [fromEulerAngle(Vector3 eulerAngle)](#fromEulerAngle-com.aspose.threed.Vector3-) | 从给定的欧拉角创建四元数 |
| [fromEulerAngle(double pitch, double yaw, double roll)](#fromEulerAngle-double-double-double-) | 从给定的欧拉角创建四元数 |
| [fromRotation(Vector3 orig, Vector3 dest)](#fromRotation-com.aspose.threed.Vector3-com.aspose.threed.Vector3-) | 创建一个从原始方向旋转到目标方向的四元数 |
| [getClass()](#getClass--) |  |
| [getLength()](#getLength--) | 获取四元数的长度 |
| [hashCode()](#hashCode--) | 获取四元数的哈希码 |
| [interpolate(float t, Quaternion from, Quaternion to)](#interpolate-float-com.aspose.threed.Quaternion-com.aspose.threed.Quaternion-) | 在 from 与 to 之间的 t 值下，对给定的四元数参数进行插值，以填充此四元数。 |
| [inverse()](#inverse--) | 返回当前四元数的逆四元数 |
| [mul(Quaternion lhs, Quaternion rhs)](#mul-com.aspose.threed.Quaternion-com.aspose.threed.Quaternion-) | 运算符重载 \* |
| [mul(Quaternion q, Vector3 v)](#mul-com.aspose.threed.Quaternion-com.aspose.threed.Vector3-) | 运算符重载 \* |
| [mul(Quaternion q, Vector4 v)](#mul-com.aspose.threed.Quaternion-com.aspose.threed.Vector4-) | 运算符重载 \* |
| [mul(Quaternion lhs, double rhs)](#mul-com.aspose.threed.Quaternion-double-) | 运算符重载 \* |
| [mul(Vector3 v, Quaternion q)](#mul-com.aspose.threed.Vector3-com.aspose.threed.Quaternion-) | 运算符重载 \* |
| [normalize()](#normalize--) | 归一化四元数 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [op_eq(Quaternion lhs, Quaternion rhs)](#op-eq-com.aspose.threed.Quaternion-com.aspose.threed.Quaternion-) | 四元数的等于运算符 |
| [op_ne(Quaternion lhs, Quaternion rhs)](#op-ne-com.aspose.threed.Quaternion-com.aspose.threed.Quaternion-) | 四元数的不等于运算符 |
| [slerp(double t, Quaternion v1, Quaternion v2)](#slerp-double-com.aspose.threed.Quaternion-com.aspose.threed.Quaternion-) | 在两个值之间执行球面线性插值 |
| [toAngleAxis(double[] angle, Vector3 axis)](#toAngleAxis-double---com.aspose.threed.Vector3-) | 将四元数分解为角度和轴 |
| [toMatrix()](#toMatrix--) | 将四元数表示的旋转转换为变换矩阵。 |
| [toMatrix(Vector3 translation)](#toMatrix-com.aspose.threed.Vector3-) | 将四元数表示的旋转转换为变换矩阵。 |
| [toString()](#toString--) | 获取四元数的字符串表示 |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Quaternion(double w, double x, double y, double z) {#Quaternion-double-double-double-double-}
```
public Quaternion(double w, double x, double y, double z)
```


初始化 [Quaternion](../../com.aspose.threed/quaternion) 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| w | double | 四元数的 w 分量 |
| x | double | 四元数的 x 分量 |
| y | double | 四元数的 y 分量 |
| z | double | 四元数的 z 分量 |

### Quaternion() {#Quaternion--}
```
public Quaternion()
```


### IDENTITY {#IDENTITY}
```
public static final Quaternion IDENTITY
```


单位四元数。

### w {#w}
```
public double w
```


w 分量。

### x {#x}
```
public double x
```


x 分量。

### y {#y}
```
public double y
```


y 分量。

### z {#z}
```
public double z
```


z 分量。

### add(Quaternion lhs, Quaternion rhs) {#add-com.aspose.threed.Quaternion-com.aspose.threed.Quaternion-}
```
public static Quaternion add(Quaternion lhs, Quaternion rhs)
```


运算符重载 +

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| lhs | [Quaternion](../../com.aspose.threed/quaternion) | 左四元数 |
| rhs | [Quaternion](../../com.aspose.threed/quaternion) | 右四元数 |

**Returns:**
[Quaternion](../../com.aspose.threed/quaternion) - Result quaternion
### clone() {#clone--}
```
public Quaternion clone()
```


克隆当前实例

**Returns:**
[Quaternion](../../com.aspose.threed/quaternion)
### concat(Quaternion rhs) {#concat-com.aspose.threed.Quaternion-}
```
public Quaternion concat(Quaternion rhs)
```


连接两个四元数

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| rhs | [Quaternion](../../com.aspose.threed/quaternion) |  |

**Returns:**
[Quaternion](../../com.aspose.threed/quaternion)
### conjugate() {#conjugate--}
```
public Quaternion conjugate()
```


返回当前四元数的共轭四元数

**Returns:**
[Quaternion](../../com.aspose.threed/quaternion) - The conjugate quaternion.
### copyFrom(Quaternion src) {#copyFrom-com.aspose.threed.Quaternion-}
```
public void copyFrom(Quaternion src)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| src | [Quaternion](../../com.aspose.threed/quaternion) |  |

### div(Quaternion lhs, double rhs) {#div-com.aspose.threed.Quaternion-double-}
```
public static Quaternion div(Quaternion lhs, double rhs)
```


运算符重载 /

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| lhs | [Quaternion](../../com.aspose.threed/quaternion) | 左四元数 |
| rhs | double | 右四元数 |

**Returns:**
[Quaternion](../../com.aspose.threed/quaternion) - Result quaternion
### dot(Quaternion q) {#dot-com.aspose.threed.Quaternion-}
```
public double dot(Quaternion q)
```


点积

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| q | [Quaternion](../../com.aspose.threed/quaternion) | 该四元数 |

**Returns:**
double - 点积值
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


检查两个四元数是否相等

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| obj | java.lang.Object | 用于检查相等性的对象。 |

**Returns:**
boolean - 如果所有组件完全相等则为 true。
### eulerAngles() {#eulerAngles--}
```
public Vector3 eulerAngles()
```


将四元数转换为由欧拉角表示的旋转，所有分量均为弧度。

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - Result vector
### fromAngleAxis(double a, Vector3 axis) {#fromAngleAxis-double-com.aspose.threed.Vector3-}
```
public static Quaternion fromAngleAxis(double a, Vector3 axis)
```


围绕给定轴创建四元数并顺时针旋转

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| a | double | 顺时针旋转（弧度） |
| axis | [Vector3](../../com.aspose.threed/vector3) | 轴 |

**Returns:**
[Quaternion](../../com.aspose.threed/quaternion) - Created quaternion
### fromEulerAngle(Vector3 eulerAngle) {#fromEulerAngle-com.aspose.threed.Vector3-}
```
public static Quaternion fromEulerAngle(Vector3 eulerAngle)
```


从给定的欧拉角创建四元数

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| eulerAngle | [Vector3](../../com.aspose.threed/vector3) | 欧拉角（弧度） |

**Returns:**
[Quaternion](../../com.aspose.threed/quaternion) - Created quaternion
### fromEulerAngle(double pitch, double yaw, double roll) {#fromEulerAngle-double-double-double-}
```
public static Quaternion fromEulerAngle(double pitch, double yaw, double roll)
```


从给定的欧拉角创建四元数

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 俯仰 | double | 俯仰（弧度） |
| 偏航 | double | 偏航（弧度） |
| 滚转 | double | 滚转（弧度） |

**Returns:**
[Quaternion](../../com.aspose.threed/quaternion) - Created quaternion
### fromRotation(Vector3 orig, Vector3 dest) {#fromRotation-com.aspose.threed.Vector3-com.aspose.threed.Vector3-}
```
public static Quaternion fromRotation(Vector3 orig, Vector3 dest)
```


创建一个从原始方向旋转到目标方向的四元数

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| orig | [Vector3](../../com.aspose.threed/vector3) | 原始方向 |
| dest | [Vector3](../../com.aspose.threed/vector3) | 目标方向 |

**Returns:**
[Quaternion](../../com.aspose.threed/quaternion) - Created quaternion
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getLength() {#getLength--}
```
public double getLength()
```


获取四元数的长度

**Returns:**
double - 四元数的长度
### hashCode() {#hashCode--}
```
public int hashCode()
```


获取四元数的哈希码

**Returns:**
int - [Quaternion](../../com.aspose.threed/quaternion) 的哈希码
### interpolate(float t, Quaternion from, Quaternion to) {#interpolate-float-com.aspose.threed.Quaternion-com.aspose.threed.Quaternion-}
```
public static Quaternion interpolate(float t, Quaternion from, Quaternion to)
```


在 from 与 to 之间的 t 值下，对给定的四元数参数进行插值，以填充此四元数。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| t | float | 用于插值的系数。 |
| from | [Quaternion](../../com.aspose.threed/quaternion) | 源四元数。 |
| to | [Quaternion](../../com.aspose.threed/quaternion) | 目标四元数。 |

**Returns:**
[Quaternion](../../com.aspose.threed/quaternion) - The interpolated quaternion.
### inverse() {#inverse--}
```
public Quaternion inverse()
```


返回当前四元数的逆四元数

**Returns:**
[Quaternion](../../com.aspose.threed/quaternion) - Inverse quaternion.
### mul(Quaternion lhs, Quaternion rhs) {#mul-com.aspose.threed.Quaternion-com.aspose.threed.Quaternion-}
```
public static Quaternion mul(Quaternion lhs, Quaternion rhs)
```


运算符重载 \*

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| lhs | [Quaternion](../../com.aspose.threed/quaternion) | 左四元数 |
| rhs | [Quaternion](../../com.aspose.threed/quaternion) | 右四元数 |

**Returns:**
[Quaternion](../../com.aspose.threed/quaternion) - Result quaternion
### mul(Quaternion q, Vector3 v) {#mul-com.aspose.threed.Quaternion-com.aspose.threed.Vector3-}
```
public static Vector3 mul(Quaternion q, Vector3 v)
```


运算符重载 \*

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| q | [Quaternion](../../com.aspose.threed/quaternion) | 旋转四元数 |
| v | [Vector3](../../com.aspose.threed/vector3) | 要旋转的向量 |

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - Rotated vector
### mul(Quaternion q, Vector4 v) {#mul-com.aspose.threed.Quaternion-com.aspose.threed.Vector4-}
```
public static Vector4 mul(Quaternion q, Vector4 v)
```


运算符重载 \*

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| q | [Quaternion](../../com.aspose.threed/quaternion) | 旋转四元数 |
| v | [Vector4](../../com.aspose.threed/vector4) | 要旋转的向量 |

**Returns:**
[Vector4](../../com.aspose.threed/vector4) - Rotated vector
### mul(Quaternion lhs, double rhs) {#mul-com.aspose.threed.Quaternion-double-}
```
public static Quaternion mul(Quaternion lhs, double rhs)
```


运算符重载 \*

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| lhs | [Quaternion](../../com.aspose.threed/quaternion) | 左四元数 |
| rhs | double | 右四元数 |

**Returns:**
[Quaternion](../../com.aspose.threed/quaternion) - Result quaternion
### mul(Vector3 v, Quaternion q) {#mul-com.aspose.threed.Vector3-com.aspose.threed.Quaternion-}
```
public static Vector3 mul(Vector3 v, Quaternion q)
```


运算符重载 \*

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| v | [Vector3](../../com.aspose.threed/vector3) | 旋转四元数 |
| q | [Quaternion](../../com.aspose.threed/quaternion) | 要旋转的向量 |

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - Rotated vector
### normalize() {#normalize--}
```
public Quaternion normalize()
```


归一化四元数

**Returns:**
[Quaternion](../../com.aspose.threed/quaternion) - Normalized quaternion.
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### op_eq(Quaternion lhs, Quaternion rhs) {#op-eq-com.aspose.threed.Quaternion-com.aspose.threed.Quaternion-}
```
public static boolean op_eq(Quaternion lhs, Quaternion rhs)
```


四元数的等于运算符

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| lhs | [Quaternion](../../com.aspose.threed/quaternion) | 左侧值。 |
| rhs | [Quaternion](../../com.aspose.threed/quaternion) | 右侧值。 |

**Returns:**
boolean - 如果所有组件完全相等则为 true。
### op_ne(Quaternion lhs, Quaternion rhs) {#op-ne-com.aspose.threed.Quaternion-com.aspose.threed.Quaternion-}
```
public static boolean op_ne(Quaternion lhs, Quaternion rhs)
```


四元数的不等于运算符

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| lhs | [Quaternion](../../com.aspose.threed/quaternion) | 左侧值。 |
| rhs | [Quaternion](../../com.aspose.threed/quaternion) | 右侧值。 |

**Returns:**
布尔 - 如果两个四元数不相等则为 True。
### slerp(double t, Quaternion v1, Quaternion v2) {#slerp-double-com.aspose.threed.Quaternion-com.aspose.threed.Quaternion-}
```
public static Quaternion slerp(double t, Quaternion v1, Quaternion v2)
```


在两个值之间执行球面线性插值

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| t | double | t 在 0 到 1 之间 |
| v1 | [Quaternion](../../com.aspose.threed/quaternion) | 第一个值 |
| v2 | [Quaternion](../../com.aspose.threed/quaternion) | 第二个值 |

**Returns:**
[Quaternion](../../com.aspose.threed/quaternion)
### toAngleAxis(double[] angle, Vector3 axis) {#toAngleAxis-double---com.aspose.threed.Vector3-}
```
public void toAngleAxis(double[] angle, Vector3 axis)
```


将四元数分解为角度和轴

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| angle | double[] | 旋转角度，以弧度为单位。 |
| axis | [Vector3](../../com.aspose.threed/vector3) | 旋转轴。 |

### toMatrix() {#toMatrix--}
```
public Matrix4 toMatrix()
```


将四元数表示的旋转转换为变换矩阵。

**Returns:**
[Matrix4](../../com.aspose.threed/matrix4) - The matrix representation of current quaternion.
### toMatrix(Vector3 translation) {#toMatrix-com.aspose.threed.Vector3-}
```
public Matrix4 toMatrix(Vector3 translation)
```


将四元数表示的旋转转换为变换矩阵。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| translation | [Vector3](../../com.aspose.threed/vector3) | 矩阵的平移部分。 |

**Returns:**
[Matrix4](../../com.aspose.threed/matrix4) - The matrix representation of current quaternion.
### toString() {#toString--}
```
public String toString()
```


获取四元数的字符串表示

**Returns:**
java.lang.String - 对象字符串
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


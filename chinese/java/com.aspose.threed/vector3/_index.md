---
title: "Vector3"
second_title: "Aspose.3D for Java API 参考"
description: "一个具有三个分量的向量。"
type: docs
weight: 202
url: /zh/java/com.aspose.threed/vector3/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.lang.Comparable, com.aspose.threed.Struct, java.io.Serializable
```
public final class Vector3 implements Comparable<Vector3>, Struct<Vector3>, Serializable
```

一个具有三个分量的向量。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [Vector3(double x, double y, double z)](#Vector3-double-double-double-) | 初始化一个新的 [Vector3](../../com.aspose.threed/vector3) 结构体实例。 |
| [Vector3(FVector3 vec)](#Vector3-com.aspose.threed.FVector3-) | 初始化一个新的 [Vector3](../../com.aspose.threed/vector3) 结构体实例。 |
| [Vector3(double v)](#Vector3-double-) | 初始化一个新的 [Vector3](../../com.aspose.threed/vector3) 结构体实例。 |
| [Vector3(Vector4 vec4)](#Vector3-com.aspose.threed.Vector4-) | 初始化一个新的 [Vector3](../../com.aspose.threed/vector3) 结构体实例。 |
| [Vector3()](#Vector3--) |  |
## 字段

| 字段 | 描述 |
| --- | --- |
| [x](#x) | x 分量。 |
| [y](#y) | y 分量。 |
| [z](#z) | z 分量。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [add(Vector3 lhs, Vector3 rhs)](#add-com.aspose.threed.Vector3-com.aspose.threed.Vector3-) | 运算符重载 + |
| [angleBetween(Vector3 dir)](#angleBetween-com.aspose.threed.Vector3-) | 计算两个方向之间的内角。两个方向可以是未归一化的向量。 |
| [angleBetween(Vector3 dir, Vector3 up)](#angleBetween-com.aspose.threed.Vector3-com.aspose.threed.Vector3-) | 计算两个方向之间的内角。两个方向可以是未归一化的向量。 |
| [clone()](#clone--) |  |
| [compareTo(Vector3 other)](#compareTo-com.aspose.threed.Vector3-) | 将当前向量与另一个实例进行比较。 |
| [copyFrom(Vector3 src)](#copyFrom-com.aspose.threed.Vector3-) |  |
| [cos()](#cos--) | 对每个分量计算余弦 |
| [create(Vector3 v)](#create-com.aspose.threed.Vector3-) | 显式转换运算符，将 Vector3 转换为 FVector3 |
| [cross(Vector3 rhs)](#cross-com.aspose.threed.Vector3-) | 两个向量的叉积 |
| [div(Vector3 lhs, Vector3 rhs)](#div-com.aspose.threed.Vector3-com.aspose.threed.Vector3-) | 运算符重载 / |
| [div(Vector3 lhs, double rhs)](#div-com.aspose.threed.Vector3-double-) | 运算符重载 / |
| [dot(Vector3 rhs)](#dot-com.aspose.threed.Vector3-) | 获取两个向量的点积 |
| [equals(Object obj)](#equals-java.lang.Object-) | 检查两个 vector3 是否相等 |
| [get(int idx)](#get-int-) | 通过索引获取向量的分量。 |
| [getClass()](#getClass--) |  |
| [getLength()](#getLength--) | 获取此向量的长度。 |
| [getLength2()](#getLength2--) | 获取长度的平方。 |
| [getOne()](#getOne--) | 获取单位向量 (1, 1, 1) |
| [getUnitX()](#getUnitX--) | 获取单位向量 (1, 0, 0) |
| [getUnitY()](#getUnitY--) | 获取单位向量 (0, 1, 0) |
| [getUnitZ()](#getUnitZ--) | 获取单位向量 (0, 0, 1) |
| [getZero()](#getZero--) | 获取单位向量 (0, 0, 0) |
| [hashCode()](#hashCode--) | 获取 Vector3 的哈希码 |
| [mul(Vector3 lhs, Vector3 rhs)](#mul-com.aspose.threed.Vector3-com.aspose.threed.Vector3-) | 运算符重载 \* |
| [mul(Vector3 lhs, double rhs)](#mul-com.aspose.threed.Vector3-double-) | 运算符重载 \* |
| [mul(double lhs, Vector3 rhs)](#mul-double-com.aspose.threed.Vector3-) | 运算符重载 \* |
| [negative(Vector3 v)](#negative-com.aspose.threed.Vector3-) | 用于 - 的运算符重载 |
| [normalize()](#normalize--) | 归一化此实例。 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [op_eq(Vector3 lhs, Vector3 rhs)](#op-eq-com.aspose.threed.Vector3-com.aspose.threed.Vector3-) | Vector3 的相等运算符 |
| [op_ne(Vector3 lhs, Vector3 rhs)](#op-ne-com.aspose.threed.Vector3-com.aspose.threed.Vector3-) | Vector3 的不等运算符 |
| [set(double newX, double newY, double newZ)](#set-double-double-double-) | 一次调用设置 x/y/z 分量。 |
| [set(int idx, double value)](#set-int-double-) | 按索引设置向量的分量。 |
| [sin()](#sin--) | 计算每个分量的正弦 |
| [sub(Vector3 lhs, Vector3 rhs)](#sub-com.aspose.threed.Vector3-com.aspose.threed.Vector3-) | 针对 -（减号）的运算符重载 |
| [toString()](#toString--) | 返回一个 java.lang.String，表示当前的 [Vector3](../../com.aspose.threed/vector3)。 |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Vector3(double x, double y, double z) {#Vector3-double-double-double-}
```
public Vector3(double x, double y, double z)
```


初始化一个新的 [Vector3](../../com.aspose.threed/vector3) 结构体实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| x | double | x 坐标。 |
| y | double | y 坐标。 |
| z | double | z 坐标。 |

### Vector3(FVector3 vec) {#Vector3-com.aspose.threed.FVector3-}
```
public Vector3(FVector3 vec)
```


初始化一个新的 [Vector3](../../com.aspose.threed/vector3) 结构体实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| vec | [FVector3](../../com.aspose.threed/fvector3) | x 坐标。 |

### Vector3(double v) {#Vector3-double-}
```
public Vector3(double v)
```


初始化一个新的 [Vector3](../../com.aspose.threed/vector3) 结构体实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| v | double | V. |

### Vector3(Vector4 vec4) {#Vector3-com.aspose.threed.Vector4-}
```
public Vector3(Vector4 vec4)
```


初始化一个新的 [Vector3](../../com.aspose.threed/vector3) 结构体实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| vec4 | [Vector4](../../com.aspose.threed/vector4) | Vec4. |

### Vector3() {#Vector3--}
```
public Vector3()
```


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

### add(Vector3 lhs, Vector3 rhs) {#add-com.aspose.threed.Vector3-com.aspose.threed.Vector3-}
```
public static Vector3 add(Vector3 lhs, Vector3 rhs)
```


运算符重载 +

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| lhs | [Vector3](../../com.aspose.threed/vector3) | 左向量 |
| rhs | [Vector3](../../com.aspose.threed/vector3) | 右向量 |

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - Result vector
### angleBetween(Vector3 dir) {#angleBetween-com.aspose.threed.Vector3-}
```
public double angleBetween(Vector3 dir)
```


计算两个方向之间的内角。两个方向可以是未归一化的向量。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| dir | [Vector3](../../com.aspose.threed/vector3) | 用于比较的方向向量 |

**Returns:**
double - 以弧度表示的内部角度
### angleBetween(Vector3 dir, Vector3 up) {#angleBetween-com.aspose.threed.Vector3-com.aspose.threed.Vector3-}
```
public double angleBetween(Vector3 dir, Vector3 up)
```


计算两个方向之间的内角。两个方向可以是未归一化的向量。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| dir | [Vector3](../../com.aspose.threed/vector3) | 用于比较的方向向量 |
| up | [Vector3](../../com.aspose.threed/vector3) | 两个方向共享平面的上向量 |

**Returns:**
double - 以弧度表示的内部角度
### clone() {#clone--}
```
public Vector3 clone()
```


克隆当前实例

**Returns:**
[Vector3](../../com.aspose.threed/vector3)
### compareTo(Vector3 other) {#compareTo-com.aspose.threed.Vector3-}
```
public int compareTo(Vector3 other)
```


将当前向量与另一个实例进行比较。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| other | [Vector3](../../com.aspose.threed/vector3) |  |

**Returns:**
int
### copyFrom(Vector3 src) {#copyFrom-com.aspose.threed.Vector3-}
```
public void copyFrom(Vector3 src)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| src | [Vector3](../../com.aspose.threed/vector3) |  |

### cos() {#cos--}
```
public Vector3 cos()
```


对每个分量计算余弦

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - Calculated [Vector3](../../com.aspose.threed/vector3).
### create(Vector3 v) {#create-com.aspose.threed.Vector3-}
```
public static FVector3 create(Vector3 v)
```


显式转换运算符，将 Vector3 转换为 FVector3

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| v | [Vector3](../../com.aspose.threed/vector3) |  |

**Returns:**
[FVector3](../../com.aspose.threed/fvector3)
### cross(Vector3 rhs) {#cross-com.aspose.threed.Vector3-}
```
public Vector3 cross(Vector3 rhs)
```


两个向量的叉积

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| rhs | [Vector3](../../com.aspose.threed/vector3) | 右侧值。 |

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - Cross product of two [Vector3](../../com.aspose.threed/vector3)s.
### div(Vector3 lhs, Vector3 rhs) {#div-com.aspose.threed.Vector3-com.aspose.threed.Vector3-}
```
public static Vector3 div(Vector3 lhs, Vector3 rhs)
```


运算符重载 /

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| lhs | [Vector3](../../com.aspose.threed/vector3) | 左向量 |
| rhs | [Vector3](../../com.aspose.threed/vector3) | 右向量 |

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - Result vector
### div(Vector3 lhs, double rhs) {#div-com.aspose.threed.Vector3-double-}
```
public static Vector3 div(Vector3 lhs, double rhs)
```


运算符重载 /

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| lhs | [Vector3](../../com.aspose.threed/vector3) | 左向量 |
| rhs | double | 右侧的 double 值 |

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - Result vector
### dot(Vector3 rhs) {#dot-com.aspose.threed.Vector3-}
```
public double dot(Vector3 rhs)
```


获取两个向量的点积

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| rhs | [Vector3](../../com.aspose.threed/vector3) | 右侧值。 |

**Returns:**
double - 两个向量的点积。
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


检查两个 vector3 是否相等

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| obj | java.lang.Object | 用于检查相等性的对象。 |

**Returns:**
boolean - 如果所有组件完全相等则为 true。
### get(int idx) {#get-int-}
```
public double get(int idx)
```


通过索引获取向量的分量。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| idx | int |  |

**Returns:**
double - 按索引获取向量的分量。
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


获取此向量的长度。

**Returns:**
double - 此向量的长度。
### getLength2() {#getLength2--}
```
public double getLength2()
```


获取长度的平方。

**Returns:**
double - 长度的平方。
### getOne() {#getOne--}
```
public static Vector3 getOne()
```


获取单位向量 (1, 1, 1)

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - unit vector (1, 1, 1)
### getUnitX() {#getUnitX--}
```
public static Vector3 getUnitX()
```


获取单位向量 (1, 0, 0)

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - unit vector (1, 0, 0)
### getUnitY() {#getUnitY--}
```
public static Vector3 getUnitY()
```


获取单位向量 (0, 1, 0)

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - unit vector (0, 1, 0)
### getUnitZ() {#getUnitZ--}
```
public static Vector3 getUnitZ()
```


获取单位向量 (0, 0, 1)

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - unit vector (0, 0, 1)
### getZero() {#getZero--}
```
public static Vector3 getZero()
```


获取单位向量 (0, 0, 0)

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - unit vector (0, 0, 0)
### hashCode() {#hashCode--}
```
public int hashCode()
```


获取 Vector3 的哈希码

**Returns:**
int - [Vector3](../../com.aspose.threed/vector3) 的哈希码
### mul(Vector3 lhs, Vector3 rhs) {#mul-com.aspose.threed.Vector3-com.aspose.threed.Vector3-}
```
public static Vector3 mul(Vector3 lhs, Vector3 rhs)
```


运算符重载 \*

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| lhs | [Vector3](../../com.aspose.threed/vector3) | 左向量 |
| rhs | [Vector3](../../com.aspose.threed/vector3) | 右向量 |

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - Result vector
### mul(Vector3 lhs, double rhs) {#mul-com.aspose.threed.Vector3-double-}
```
public static Vector3 mul(Vector3 lhs, double rhs)
```


运算符重载 \*

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| lhs | [Vector3](../../com.aspose.threed/vector3) | 左向量 |
| rhs | double | 右侧的 double 值 |

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - Result vector
### mul(double lhs, Vector3 rhs) {#mul-double-com.aspose.threed.Vector3-}
```
public static Vector3 mul(double lhs, Vector3 rhs)
```


运算符重载 \*

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| lhs | double | 左标量 |
| rhs | [Vector3](../../com.aspose.threed/vector3) | 右向量 |

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - Result vector
### negative(Vector3 v) {#negative-com.aspose.threed.Vector3-}
```
public static Vector3 negative(Vector3 v)
```


用于 - 的运算符重载

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| v | [Vector3](../../com.aspose.threed/vector3) | 原点向量 |

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - Result vector
### normalize() {#normalize--}
```
public Vector3 normalize()
```


归一化此实例。

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - Normalized vector.
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### op_eq(Vector3 lhs, Vector3 rhs) {#op-eq-com.aspose.threed.Vector3-com.aspose.threed.Vector3-}
```
public static boolean op_eq(Vector3 lhs, Vector3 rhs)
```


Vector3 的相等运算符

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| lhs | [Vector3](../../com.aspose.threed/vector3) | 左侧值。 |
| rhs | [Vector3](../../com.aspose.threed/vector3) | 右侧值。 |

**Returns:**
boolean - 如果所有组件完全相等则为 true。
### op_ne(Vector3 lhs, Vector3 rhs) {#op-ne-com.aspose.threed.Vector3-com.aspose.threed.Vector3-}
```
public static boolean op_ne(Vector3 lhs, Vector3 rhs)
```


Vector3 的不等运算符

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| lhs | [Vector3](../../com.aspose.threed/vector3) | 左侧值。 |
| rhs | [Vector3](../../com.aspose.threed/vector3) | 右侧值。 |

**Returns:**
boolean - 如果两个向量不相等则为 true。
### set(double newX, double newY, double newZ) {#set-double-double-double-}
```
public void set(double newX, double newY, double newZ)
```


一次调用设置 x/y/z 分量。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| newX | double | x 分量。 |
| newY | double | y 分量。 |
| newZ | double | z 分量。 |

### set(int idx, double value) {#set-int-double-}
```
public void set(int idx, double value)
```


按索引设置向量的分量。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| idx | int |  |
| 值 | double | 新值 |

### sin() {#sin--}
```
public Vector3 sin()
```


计算每个分量的正弦

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - Calculated [Vector3](../../com.aspose.threed/vector3).
### sub(Vector3 lhs, Vector3 rhs) {#sub-com.aspose.threed.Vector3-com.aspose.threed.Vector3-}
```
public static Vector3 sub(Vector3 lhs, Vector3 rhs)
```


针对 -（减号）的运算符重载

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| lhs | [Vector3](../../com.aspose.threed/vector3) | 左向量 |
| rhs | [Vector3](../../com.aspose.threed/vector3) | 右向量 |

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - Result vector
### toString() {#toString--}
```
public String toString()
```


返回一个 java.lang.String，表示当前的 [Vector3](../../com.aspose.threed/vector3)。

**Returns:**
java.lang.String - 表示当前 [Vector3](../../com.aspose.threed/vector3) 的 java.lang.String。
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


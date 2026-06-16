---
title: "Vector4"
second_title: "Aspose.3D for Java API 参考"
description: "一个具有四个分量的向量。"
type: docs
weight: 203
url: /zh/java/com.aspose.threed/vector4/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.lang.Comparable, com.aspose.threed.Struct, java.io.Serializable
```
public final class Vector4 implements Comparable<Vector4>, Struct<Vector4>, Serializable
```

一个具有四个分量的向量。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [Vector4(Vector3 vec, double w)](#Vector4-com.aspose.threed.Vector3-double-) | 初始化 [Vector4](../../com.aspose.threed/vector4) 结构的新实例。 |
| [Vector4(Vector3 vec)](#Vector4-com.aspose.threed.Vector3-) | 初始化 [Vector4](../../com.aspose.threed/vector4) 结构的新实例。 |
| [Vector4(FVector4 vec)](#Vector4-com.aspose.threed.FVector4-) | 初始化 [Vector4](../../com.aspose.threed/vector4) 结构的新实例。 |
| [Vector4(double x, double y, double z)](#Vector4-double-double-double-) | 初始化 [Vector4](../../com.aspose.threed/vector4) 结构的新实例。 |
| [Vector4(double x, double y, double z, double w)](#Vector4-double-double-double-double-) | 初始化 [Vector4](../../com.aspose.threed/vector4) 结构的新实例。 |
| [Vector4()](#Vector4--) |  |
## 字段

| 字段 | 描述 |
| --- | --- |
| [w](#w) | w 分量。 |
| [x](#x) | x 分量。 |
| [y](#y) | y 分量。 |
| [z](#z) | z 分量。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [add(Vector4 lhs, Vector4 rhs)](#add-com.aspose.threed.Vector4-com.aspose.threed.Vector4-) | 运算符重载 + |
| [clone()](#clone--) |  |
| [compareTo(Vector4 other)](#compareTo-com.aspose.threed.Vector4-) | 将当前向量与另一个实例进行比较。 |
| [copyFrom(Vector4 src)](#copyFrom-com.aspose.threed.Vector4-) |  |
| [create(Vector4 v)](#create-com.aspose.threed.Vector4-) | 显式转换运算符，将 Vector4 转换为 FVector4 |
| [equals(Object obj)](#equals-java.lang.Object-) | 检查两个向量是否相等 |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) | 获取此向量的哈希码。 |
| [mul(Vector4 lhs, Vector4 rhs)](#mul-com.aspose.threed.Vector4-com.aspose.threed.Vector4-) | 运算符重载 \* |
| [mul(Vector4 lhs, double rhs)](#mul-com.aspose.threed.Vector4-double-) | 运算符重载 \* |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [set(double newX, double newY, double newZ)](#set-double-double-double-) | 一次性设置向量的 xyz 分量，w 将被设为 1。 |
| [set(double newX, double newY, double newZ, double newW)](#set-double-double-double-double-) | 一次性设置向量的所有分量。 |
| [sub(Vector4 lhs, Vector4 rhs)](#sub-com.aspose.threed.Vector4-com.aspose.threed.Vector4-) | 针对 -（减号）的运算符重载 |
| [toString()](#toString--) | 返回一个 java.lang.String，表示当前的 [Vector4](../../com.aspose.threed/vector4)。 |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Vector4(Vector3 vec, double w) {#Vector4-com.aspose.threed.Vector3-double-}
```
public Vector4(Vector3 vec, double w)
```


初始化 [Vector4](../../com.aspose.threed/vector4) 结构的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| vec | [Vector3](../../com.aspose.threed/vector3) | 向量。 |
| w | double | 宽度。 |

### Vector4(Vector3 vec) {#Vector4-com.aspose.threed.Vector3-}
```
public Vector4(Vector3 vec)
```


初始化 [Vector4](../../com.aspose.threed/vector4) 结构的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| vec | [Vector3](../../com.aspose.threed/vector3) | 向量。 |

### Vector4(FVector4 vec) {#Vector4-com.aspose.threed.FVector4-}
```
public Vector4(FVector4 vec)
```


初始化 [Vector4](../../com.aspose.threed/vector4) 结构的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| vec | [FVector4](../../com.aspose.threed/fvector4) | 向量。 |

### Vector4(double x, double y, double z) {#Vector4-double-double-double-}
```
public Vector4(double x, double y, double z)
```


初始化 [Vector4](../../com.aspose.threed/vector4) 结构的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| x | double | x 坐标。 |
| y | double | y 坐标。 |
| z | double | z 坐标。 |

### Vector4(double x, double y, double z, double w) {#Vector4-double-double-double-double-}
```
public Vector4(double x, double y, double z, double w)
```


初始化 [Vector4](../../com.aspose.threed/vector4) 结构的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| x | double | x 坐标。 |
| y | double | y 坐标。 |
| z | double | z 坐标。 |
| w | double | 宽度。 |

### Vector4() {#Vector4--}
```
public Vector4()
```


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

### add(Vector4 lhs, Vector4 rhs) {#add-com.aspose.threed.Vector4-com.aspose.threed.Vector4-}
```
public static Vector4 add(Vector4 lhs, Vector4 rhs)
```


运算符重载 +

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| lhs | [Vector4](../../com.aspose.threed/vector4) | 左向量 |
| rhs | [Vector4](../../com.aspose.threed/vector4) | 右向量 |

**Returns:**
[Vector4](../../com.aspose.threed/vector4) - Result vector
### clone() {#clone--}
```
public Vector4 clone()
```


克隆当前实例

**Returns:**
[Vector4](../../com.aspose.threed/vector4)
### compareTo(Vector4 other) {#compareTo-com.aspose.threed.Vector4-}
```
public int compareTo(Vector4 other)
```


将当前向量与另一个实例进行比较。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| other | [Vector4](../../com.aspose.threed/vector4) |  |

**Returns:**
int
### copyFrom(Vector4 src) {#copyFrom-com.aspose.threed.Vector4-}
```
public void copyFrom(Vector4 src)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| src | [Vector4](../../com.aspose.threed/vector4) |  |

### create(Vector4 v) {#create-com.aspose.threed.Vector4-}
```
public static FVector4 create(Vector4 v)
```


显式转换运算符，将 Vector4 转换为 FVector4

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| v | [Vector4](../../com.aspose.threed/vector4) |  |

**Returns:**
[FVector4](../../com.aspose.threed/fvector4)
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


检查两个向量是否相等

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
### hashCode() {#hashCode--}
```
public int hashCode()
```


获取此向量的哈希码。

**Returns:**
int
### mul(Vector4 lhs, Vector4 rhs) {#mul-com.aspose.threed.Vector4-com.aspose.threed.Vector4-}
```
public static Vector4 mul(Vector4 lhs, Vector4 rhs)
```


运算符重载 \*

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| lhs | [Vector4](../../com.aspose.threed/vector4) | 左向量 |
| rhs | [Vector4](../../com.aspose.threed/vector4) | 右向量 |

**Returns:**
[Vector4](../../com.aspose.threed/vector4) - Result vector
### mul(Vector4 lhs, double rhs) {#mul-com.aspose.threed.Vector4-double-}
```
public static Vector4 mul(Vector4 lhs, double rhs)
```


运算符重载 \*

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| lhs | [Vector4](../../com.aspose.threed/vector4) | 左向量 |
| rhs | double | 右侧的 double 值 |

**Returns:**
[Vector4](../../com.aspose.threed/vector4) - Result vector
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### set(double newX, double newY, double newZ) {#set-double-double-double-}
```
public void set(double newX, double newY, double newZ)
```


一次性设置向量的 xyz 分量，w 将被设为 1。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| newX | double | 新的 X 分量。 |
| newY | double | 新的 Y 分量。 |
| newZ | double | 新的 Z 分量。 |

### set(double newX, double newY, double newZ, double newW) {#set-double-double-double-double-}
```
public void set(double newX, double newY, double newZ, double newW)
```


一次性设置向量的所有分量。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| newX | double | 新的 X 分量。 |
| newY | double | 新的 Y 分量。 |
| newZ | double | 新的 Z 分量。 |
| newW | double | 新的 W 组件。 |

### sub(Vector4 lhs, Vector4 rhs) {#sub-com.aspose.threed.Vector4-com.aspose.threed.Vector4-}
```
public static Vector4 sub(Vector4 lhs, Vector4 rhs)
```


针对 -（减号）的运算符重载

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| lhs | [Vector4](../../com.aspose.threed/vector4) | 左向量 |
| rhs | [Vector4](../../com.aspose.threed/vector4) | 右向量 |

**Returns:**
[Vector4](../../com.aspose.threed/vector4) - Result vector
### toString() {#toString--}
```
public String toString()
```


返回一个 java.lang.String，表示当前的 [Vector4](../../com.aspose.threed/vector4)。

**Returns:**
java.lang.String - 一个表示当前 [Vector4](../../com.aspose.threed/vector4) 的 java.lang.String。
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


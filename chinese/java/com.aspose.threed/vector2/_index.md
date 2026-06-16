---
title: "Vector2"
second_title: "Aspose.3D for Java API 参考"
description: "一个具有两个分量的向量。"
type: docs
weight: 201
url: /zh/java/com.aspose.threed/vector2/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.lang.Comparable, com.aspose.threed.Struct, java.io.Serializable
```
public final class Vector2 implements Comparable<Vector2>, Struct<Vector2>, Serializable
```

一个具有两个分量的向量。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [Vector2(double s)](#Vector2-double-) | 初始化 [Vector2](../../com.aspose.threed/vector2) 结构的新实例。 |
| [Vector2(Vector3 s)](#Vector2-com.aspose.threed.Vector3-) | 初始化 [Vector2](../../com.aspose.threed/vector2) 结构的新实例。 |
| [Vector2(FVector2 vec)](#Vector2-com.aspose.threed.FVector2-) | 初始化 [Vector2](../../com.aspose.threed/vector2) 结构的新实例。 |
| [Vector2(double x, double y)](#Vector2-double-double-) | 初始化 [Vector2](../../com.aspose.threed/vector2) 结构的新实例。 |
| [Vector2()](#Vector2--) |  |
## 字段

| 字段 | 描述 |
| --- | --- |
| [x](#x) | x 分量。 |
| [y](#y) | y 分量。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [add(Vector2 lhs, Vector2 rhs)](#add-com.aspose.threed.Vector2-com.aspose.threed.Vector2-) | Vector2 的加法运算符 |
| [clone()](#clone--) |  |
| [compareTo(Vector2 other)](#compareTo-com.aspose.threed.Vector2-) | 将当前向量与另一个实例进行比较。 |
| [copyFrom(Vector2 src)](#copyFrom-com.aspose.threed.Vector2-) |  |
| [create(Vector2 v)](#create-com.aspose.threed.Vector2-) | 显式转换运算符，将 Vector2 转换为 FVector2 |
| [cross(Vector2 v)](#cross-com.aspose.threed.Vector2-) | 两个向量的叉积 |
| [div(Vector2 lhs, double rhs)](#div-com.aspose.threed.Vector2-double-) | Vector2 的除法运算符 |
| [dot(Vector2 rhs)](#dot-com.aspose.threed.Vector2-) | 获取两个向量的点积 |
| [equals(Vector2 rhs)](#equals-com.aspose.threed.Vector2-) | 检查两个 vector2 是否相等 |
| [equals(Object obj)](#equals-java.lang.Object-) | 检查两个 vector2 是否相等 |
| [getClass()](#getClass--) |  |
| [getLength()](#getLength--) | 获取长度。 |
| [getU()](#getU--) | 如果将 [Vector2](../../com.aspose.threed/vector2) 用作映射坐标，则获取 U 分量。 |
| [getV()](#getV--) | 如果将 [Vector2](../../com.aspose.threed/vector2) 用作映射坐标，则获取 V 分量。 |
| [hashCode()](#hashCode--) | 获取 Vector2 的哈希码 |
| [mul(Vector2 lhs, double rhs)](#mul-com.aspose.threed.Vector2-double-) | Vector2 的乘法运算符 |
| [mul(double lhs, Vector2 rhs)](#mul-double-com.aspose.threed.Vector2-) | Vector2 的乘法运算符 |
| [normalize()](#normalize--) | 归一化此实例。 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [op_eq(Vector2 lhs, Vector2 rhs)](#op-eq-com.aspose.threed.Vector2-com.aspose.threed.Vector2-) | Vector2 的等于运算符 |
| [op_ne(Vector2 lhs, Vector2 rhs)](#op-ne-com.aspose.threed.Vector2-com.aspose.threed.Vector2-) | Vector2 的不等于运算符 |
| [setU(double value)](#setU-double-) | 如果将 [Vector2](../../com.aspose.threed/vector2) 用作映射坐标，则设置 U 分量。 |
| [setV(double value)](#setV-double-) | 如果将 [Vector2](../../com.aspose.threed/vector2) 用作映射坐标，则设置 V 分量。 |
| [sub(Vector2 lhs, Vector2 rhs)](#sub-com.aspose.threed.Vector2-com.aspose.threed.Vector2-) | Vector2 的减法运算符 |
| [toString()](#toString--) | 返回一个 java.lang.String，表示当前的 [Vector2](../../com.aspose.threed/vector2)。 |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Vector2(double s) {#Vector2-double-}
```
public Vector2(double s)
```


初始化 [Vector2](../../com.aspose.threed/vector2) 结构的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| s | double | S. |

### Vector2(Vector3 s) {#Vector2-com.aspose.threed.Vector3-}
```
public Vector2(Vector3 s)
```


初始化 [Vector2](../../com.aspose.threed/vector2) 结构的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| s | [Vector3](../../com.aspose.threed/vector3) | S. |

### Vector2(FVector2 vec) {#Vector2-com.aspose.threed.FVector2-}
```
public Vector2(FVector2 vec)
```


初始化 [Vector2](../../com.aspose.threed/vector2) 结构的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| vec | [FVector2](../../com.aspose.threed/fvector2) | float 类型的向量。 |

### Vector2(double x, double y) {#Vector2-double-double-}
```
public Vector2(double x, double y)
```


初始化 [Vector2](../../com.aspose.threed/vector2) 结构的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| x | double | x 坐标。 |
| y | double | y 坐标。 |

### Vector2() {#Vector2--}
```
public Vector2()
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

### add(Vector2 lhs, Vector2 rhs) {#add-com.aspose.threed.Vector2-com.aspose.threed.Vector2-}
```
public static Vector2 add(Vector2 lhs, Vector2 rhs)
```


Vector2 的加法运算符

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| lhs | [Vector2](../../com.aspose.threed/vector2) | 左侧值。 |
| rhs | [Vector2](../../com.aspose.threed/vector2) | 右侧值。 |

**Returns:**
[Vector2](../../com.aspose.threed/vector2) - The result of addition.
### clone() {#clone--}
```
public Vector2 clone()
```


克隆当前实例

**Returns:**
[Vector2](../../com.aspose.threed/vector2)
### compareTo(Vector2 other) {#compareTo-com.aspose.threed.Vector2-}
```
public int compareTo(Vector2 other)
```


将当前向量与另一个实例进行比较。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| other | [Vector2](../../com.aspose.threed/vector2) |  |

**Returns:**
int
### copyFrom(Vector2 src) {#copyFrom-com.aspose.threed.Vector2-}
```
public void copyFrom(Vector2 src)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| src | [Vector2](../../com.aspose.threed/vector2) |  |

### create(Vector2 v) {#create-com.aspose.threed.Vector2-}
```
public static FVector2 create(Vector2 v)
```


显式转换运算符，将 Vector2 转换为 FVector2

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| v | [Vector2](../../com.aspose.threed/vector2) |  |

**Returns:**
[FVector2](../../com.aspose.threed/fvector2)
### cross(Vector2 v) {#cross-com.aspose.threed.Vector2-}
```
public double cross(Vector2 v)
```


两个向量的叉积

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| v | [Vector2](../../com.aspose.threed/vector2) |  |

**Returns:**
double
### div(Vector2 lhs, double rhs) {#div-com.aspose.threed.Vector2-double-}
```
public static Vector2 div(Vector2 lhs, double rhs)
```


Vector2 的除法运算符

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| lhs | [Vector2](../../com.aspose.threed/vector2) | 左侧值。 |
| rhs | double | 右侧值。 |

**Returns:**
[Vector2](../../com.aspose.threed/vector2) - The result of division.
### dot(Vector2 rhs) {#dot-com.aspose.threed.Vector2-}
```
public double dot(Vector2 rhs)
```


获取两个向量的点积

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| rhs | [Vector2](../../com.aspose.threed/vector2) | 右侧值。 |

**Returns:**
double - 两个向量的点积。
### equals(Vector2 rhs) {#equals-com.aspose.threed.Vector2-}
```
public boolean equals(Vector2 rhs)
```


检查两个 vector2 是否相等

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| rhs | [Vector2](../../com.aspose.threed/vector2) | 右侧的值。 |

**Returns:**
boolean - 如果所有组件完全相等则为 true。
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


检查两个 vector2 是否相等

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| obj | java.lang.Object | 用于比较的对象。 |

**Returns:**
boolean - 如果所有组件完全相等则为 true。
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


获取长度。

**Returns:**
double - 长度。
### getU() {#getU--}
```
public double getU()
```


如果将 [Vector2](../../com.aspose.threed/vector2) 用作映射坐标，则获取 U 分量。它是 x 分量的别名。

**Returns:**
double - 当 [Vector2](../../com.aspose.threed/vector2) 用作映射坐标时的 U 分量。它是 x 分量的别名。
### getV() {#getV--}
```
public double getV()
```


如果将 [Vector2](../../com.aspose.threed/vector2) 用作映射坐标，则获取 V 分量。它是 y 分量的别名。

**Returns:**
double - 当 [Vector2](../../com.aspose.threed/vector2) 用作映射坐标时的 V 分量。它是 y 分量的别名。
### hashCode() {#hashCode--}
```
public int hashCode()
```


获取 Vector2 的哈希码

**Returns:**
int - [Vector2](../../com.aspose.threed/vector2) 的哈希码
### mul(Vector2 lhs, double rhs) {#mul-com.aspose.threed.Vector2-double-}
```
public static Vector2 mul(Vector2 lhs, double rhs)
```


Vector2 的乘法运算符

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| lhs | [Vector2](../../com.aspose.threed/vector2) | 左侧值。 |
| rhs | double | 右侧值。 |

**Returns:**
[Vector2](../../com.aspose.threed/vector2) - The result of multiply.
### mul(double lhs, Vector2 rhs) {#mul-double-com.aspose.threed.Vector2-}
```
public static Vector2 mul(double lhs, Vector2 rhs)
```


Vector2 的乘法运算符

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| lhs | double | 左侧值。 |
| rhs | [Vector2](../../com.aspose.threed/vector2) | 右侧值。 |

**Returns:**
[Vector2](../../com.aspose.threed/vector2) - The result of multiply.
### normalize() {#normalize--}
```
public Vector2 normalize()
```


归一化此实例。

**Returns:**
[Vector2](../../com.aspose.threed/vector2) - Normalized vector.
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### op_eq(Vector2 lhs, Vector2 rhs) {#op-eq-com.aspose.threed.Vector2-com.aspose.threed.Vector2-}
```
public static boolean op_eq(Vector2 lhs, Vector2 rhs)
```


Vector2 的等于运算符

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| lhs | [Vector2](../../com.aspose.threed/vector2) | 左侧值。 |
| rhs | [Vector2](../../com.aspose.threed/vector2) | 右侧值。 |

**Returns:**
boolean - 如果所有组件完全相等则为 true。
### op_ne(Vector2 lhs, Vector2 rhs) {#op-ne-com.aspose.threed.Vector2-com.aspose.threed.Vector2-}
```
public static boolean op_ne(Vector2 lhs, Vector2 rhs)
```


Vector2 的不等于运算符

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| lhs | [Vector2](../../com.aspose.threed/vector2) | 左侧值。 |
| rhs | [Vector2](../../com.aspose.threed/vector2) | 右侧值。 |

**Returns:**
boolean - 如果两个向量不相等则为 true。
### setU(double value) {#setU-double-}
```
public void setU(double value)
```


如果将 [Vector2](../../com.aspose.threed/vector2) 用作映射坐标，则设置 U 分量。它是 x 分量的别名。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | double | 新值 |

### setV(double value) {#setV-double-}
```
public void setV(double value)
```


如果将 [Vector2](../../com.aspose.threed/vector2) 用作映射坐标，则设置 V 分量。它是 y 分量的别名。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | double | 新值 |

### sub(Vector2 lhs, Vector2 rhs) {#sub-com.aspose.threed.Vector2-com.aspose.threed.Vector2-}
```
public static Vector2 sub(Vector2 lhs, Vector2 rhs)
```


Vector2 的减法运算符

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| lhs | [Vector2](../../com.aspose.threed/vector2) | 左侧值。 |
| rhs | [Vector2](../../com.aspose.threed/vector2) | 右侧值。 |

**Returns:**
[Vector2](../../com.aspose.threed/vector2) - The result of substraction.
### toString() {#toString--}
```
public String toString()
```


返回一个 java.lang.String，表示当前的 [Vector2](../../com.aspose.threed/vector2)。

**Returns:**
java.lang.String - 表示当前 [Vector2](../../com.aspose.threed/vector2) 的 java.lang.String。
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


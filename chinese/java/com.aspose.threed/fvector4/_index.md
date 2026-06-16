---
title: "FVector4"
second_title: "Aspose.3D for Java API 参考"
description: "具有四个分量的 float 向量。"
type: docs
weight: 61
url: /zh/java/com.aspose.threed/fvector4/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.threed.Struct, java.io.Serializable
```
public final class FVector4 implements Struct<FVector4>, Serializable
```

具有四个分量的 float 向量。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [FVector4(float x, float y, float z, float w)](#FVector4-float-float-float-float-) | 初始化 [FVector4](../../com.aspose.threed/fvector4) 的新实例。 |
| [FVector4(float x, float y, float z)](#FVector4-float-float-float-) | 初始化 [FVector4](../../com.aspose.threed/fvector4) 的新实例。 |
| [FVector4(Color color)](#FVector4-java.awt.Color-) | 初始化 [FVector4](../../com.aspose.threed/fvector4) 的新实例。 |
| [FVector4(Vector4 vec)](#FVector4-com.aspose.threed.Vector4-) | 初始化 [FVector4](../../com.aspose.threed/fvector4) 的新实例。 |
| [FVector4(Vector3 vec)](#FVector4-com.aspose.threed.Vector3-) | 初始化 [FVector4](../../com.aspose.threed/fvector4) 的新实例。 |
| [FVector4(Vector3 vec, float w)](#FVector4-com.aspose.threed.Vector3-float-) | 初始化 [FVector4](../../com.aspose.threed/fvector4) 的新实例。 |
| [FVector4()](#FVector4--) |  |
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
| [add(FVector4 lhs, FVector4 rhs)](#add-com.aspose.threed.FVector4-com.aspose.threed.FVector4-) | 运算符重载 + |
| [clone()](#clone--) |  |
| [copyFrom(FVector4 src)](#copyFrom-com.aspose.threed.FVector4-) |  |
| [create(FVector4 v)](#create-com.aspose.threed.FVector4-) | 显式转换运算符，将 Vector4 转换为 FVector4 |
| [equals(Object obj)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) |  |
| [mul(FVector4 lhs, FVector4 rhs)](#mul-com.aspose.threed.FVector4-com.aspose.threed.FVector4-) | 运算符重载 \* |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [sub(FVector4 lhs, FVector4 rhs)](#sub-com.aspose.threed.FVector4-com.aspose.threed.FVector4-) | 针对 -（减号）的运算符重载 |
| [toString()](#toString--) | 返回表示 [FVector4](../../com.aspose.threed/fvector4) 的字符串 |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### FVector4(float x, float y, float z, float w) {#FVector4-float-float-float-float-}
```
public FVector4(float x, float y, float z, float w)
```


初始化 [FVector4](../../com.aspose.threed/fvector4) 的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| x | float | X 分量 |
| y | float | Y 分量 |
| z | float | Z 分量 |
| w | float | W 分量 |

### FVector4(float x, float y, float z) {#FVector4-float-float-float-}
```
public FVector4(float x, float y, float z)
```


初始化 [FVector4](../../com.aspose.threed/fvector4) 的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| x | float | X 分量 |
| y | float | Y 分量 |
| z | float | Z 分量 |

### FVector4(Color color) {#FVector4-java.awt.Color-}
```
public FVector4(Color color)
```


初始化 [FVector4](../../com.aspose.threed/fvector4) 的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 颜色 | java.awt.Color |  |

### FVector4(Vector4 vec) {#FVector4-com.aspose.threed.Vector4-}
```
public FVector4(Vector4 vec)
```


初始化 [FVector4](../../com.aspose.threed/fvector4) 的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| vec | [Vector4](../../com.aspose.threed/vector4) |  |

### FVector4(Vector3 vec) {#FVector4-com.aspose.threed.Vector3-}
```
public FVector4(Vector3 vec)
```


初始化 [FVector4](../../com.aspose.threed/fvector4) 的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| vec | [Vector3](../../com.aspose.threed/vector3) |  |

### FVector4(Vector3 vec, float w) {#FVector4-com.aspose.threed.Vector3-float-}
```
public FVector4(Vector3 vec, float w)
```


初始化 [FVector4](../../com.aspose.threed/fvector4) 的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| vec | [Vector3](../../com.aspose.threed/vector3) |  |
| w | float |  |

### FVector4() {#FVector4--}
```
public FVector4()
```


### w {#w}
```
public float w
```


w 分量。

### x {#x}
```
public float x
```


x 分量。

### y {#y}
```
public float y
```


y 分量。

### z {#z}
```
public float z
```


z 分量。

### add(FVector4 lhs, FVector4 rhs) {#add-com.aspose.threed.FVector4-com.aspose.threed.FVector4-}
```
public static FVector4 add(FVector4 lhs, FVector4 rhs)
```


运算符重载 +

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| lhs | [FVector4](../../com.aspose.threed/fvector4) | 左向量 |
| rhs | [FVector4](../../com.aspose.threed/fvector4) | 右向量 |

**Returns:**
[FVector4](../../com.aspose.threed/fvector4) - Result vector
### clone() {#clone--}
```
public FVector4 clone()
```


克隆当前实例

**Returns:**
[FVector4](../../com.aspose.threed/fvector4)
### copyFrom(FVector4 src) {#copyFrom-com.aspose.threed.FVector4-}
```
public void copyFrom(FVector4 src)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| src | [FVector4](../../com.aspose.threed/fvector4) |  |

### create(FVector4 v) {#create-com.aspose.threed.FVector4-}
```
public static Vector4 create(FVector4 v)
```


显式转换运算符，将 Vector4 转换为 FVector4

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| v | [FVector4](../../com.aspose.threed/fvector4) |  |

**Returns:**
[Vector4](../../com.aspose.threed/vector4)
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
### hashCode() {#hashCode--}
```
public int hashCode()
```




**Returns:**
int
### mul(FVector4 lhs, FVector4 rhs) {#mul-com.aspose.threed.FVector4-com.aspose.threed.FVector4-}
```
public static FVector4 mul(FVector4 lhs, FVector4 rhs)
```


运算符重载 \*

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| lhs | [FVector4](../../com.aspose.threed/fvector4) | 左向量 |
| rhs | [FVector4](../../com.aspose.threed/fvector4) | 右向量 |

**Returns:**
[FVector4](../../com.aspose.threed/fvector4) - Result vector
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### sub(FVector4 lhs, FVector4 rhs) {#sub-com.aspose.threed.FVector4-com.aspose.threed.FVector4-}
```
public static FVector4 sub(FVector4 lhs, FVector4 rhs)
```


针对 -（减号）的运算符重载

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| lhs | [FVector4](../../com.aspose.threed/fvector4) | 左向量 |
| rhs | [FVector4](../../com.aspose.threed/fvector4) | 右向量 |

**Returns:**
[FVector4](../../com.aspose.threed/fvector4) - Result vector
### toString() {#toString--}
```
public String toString()
```


返回表示 [FVector4](../../com.aspose.threed/fvector4) 的字符串

**Returns:**
java.lang.String - 当前向量的字符串表示。
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


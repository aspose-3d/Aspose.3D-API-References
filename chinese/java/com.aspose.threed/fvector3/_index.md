---
title: "FVector3"
second_title: "Aspose.3D for Java API 参考"
description: "具有三个分量的 float 向量。"
type: docs
weight: 60
url: /zh/java/com.aspose.threed/fvector3/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.threed.Struct, java.io.Serializable
```
public final class FVector3 implements Struct<FVector3>, Serializable
```

具有三个分量的 float 向量。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [FVector3(float x, float y, float z)](#FVector3-float-float-float-) | 初始化 [FVector3](../../com.aspose.threed/fvector3) 的新实例。 |
| [FVector3(Vector3 vec)](#FVector3-com.aspose.threed.Vector3-) | 初始化 [FVector3](../../com.aspose.threed/fvector3) 的新实例。 |
| [FVector3(Vector4 vec)](#FVector3-com.aspose.threed.Vector4-) | 初始化 [FVector4](../../com.aspose.threed/fvector4) 的新实例。 |
| [FVector3()](#FVector3--) |  |
## 字段

| 字段 | 描述 |
| --- | --- |
| [x](#x) | x 分量。 |
| [y](#y) | y 分量。 |
| [z](#z) | y 分量。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [add(FVector3 a, FVector3 b)](#add-com.aspose.threed.FVector3-com.aspose.threed.FVector3-) | \+ 运算符重载 |
| [clone()](#clone--) |  |
| [copyFrom(FVector3 src)](#copyFrom-com.aspose.threed.FVector3-) |  |
| [create(FVector3 v)](#create-com.aspose.threed.FVector3-) | 显式转换运算符，将 FVector3 强制转换为 Vector3 |
| [cross(FVector3 rhs)](#cross-com.aspose.threed.FVector3-) | 两个向量的叉积 |
| [equals(Object obj)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getOne()](#getOne--) | 单位缩放向量，所有分量均为 1 |
| [getZero()](#getZero--) | 零向量。 |
| [hashCode()](#hashCode--) |  |
| [mul(FVector3 a, float b)](#mul-com.aspose.threed.FVector3-float-) | \* 运算符重载 |
| [negative(FVector3 a)](#negative-com.aspose.threed.FVector3-) | \- 运算符重载 |
| [normalize()](#normalize--) | 归一化此实例。 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [sub(FVector3 a, FVector3 b)](#sub-com.aspose.threed.FVector3-com.aspose.threed.FVector3-) | \- 运算符重载 |
| [toString()](#toString--) | 返回表示 [FVector3](../../com.aspose.threed/fvector3) 的字符串 |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### FVector3(float x, float y, float z) {#FVector3-float-float-float-}
```
public FVector3(float x, float y, float z)
```


初始化 [FVector3](../../com.aspose.threed/fvector3) 的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| x | float | 向量的 X 分量 |
| y | float | 向量的 Y 分量 |
| z | float | 向量的 Z 分量 |

### FVector3(Vector3 vec) {#FVector3-com.aspose.threed.Vector3-}
```
public FVector3(Vector3 vec)
```


初始化 [FVector3](../../com.aspose.threed/fvector3) 的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| vec | [Vector3](../../com.aspose.threed/vector3) | 双精度类型的 Vector3 |

### FVector3(Vector4 vec) {#FVector3-com.aspose.threed.Vector4-}
```
public FVector3(Vector4 vec)
```


初始化 [FVector4](../../com.aspose.threed/fvector4) 的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| vec | [Vector4](../../com.aspose.threed/vector4) | 双精度类型的 Vector4 |

### FVector3() {#FVector3--}
```
public FVector3()
```


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


y 分量。

### add(FVector3 a, FVector3 b) {#add-com.aspose.threed.FVector3-com.aspose.threed.FVector3-}
```
public static FVector3 add(FVector3 a, FVector3 b)
```


\+ 运算符重载

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| a | [FVector3](../../com.aspose.threed/fvector3) | 第一个向量 |
| b | [FVector3](../../com.aspose.threed/fvector3) | 第二个向量 |

**Returns:**
[FVector3](../../com.aspose.threed/fvector3)
### clone() {#clone--}
```
public FVector3 clone()
```


克隆当前实例

**Returns:**
[FVector3](../../com.aspose.threed/fvector3)
### copyFrom(FVector3 src) {#copyFrom-com.aspose.threed.FVector3-}
```
public void copyFrom(FVector3 src)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| src | [FVector3](../../com.aspose.threed/fvector3) |  |

### create(FVector3 v) {#create-com.aspose.threed.FVector3-}
```
public static Vector3 create(FVector3 v)
```


显式转换运算符，将 FVector3 强制转换为 Vector3

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| v | [FVector3](../../com.aspose.threed/fvector3) | 单精度类型的 Vector3 |

**Returns:**
[Vector3](../../com.aspose.threed/vector3)
### cross(FVector3 rhs) {#cross-com.aspose.threed.FVector3-}
```
public FVector3 cross(FVector3 rhs)
```


两个向量的叉积

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| rhs | [FVector3](../../com.aspose.threed/fvector3) | 右侧值。 |

**Returns:**
[FVector3](../../com.aspose.threed/fvector3) - Cross product of two [FVector3](../../com.aspose.threed/fvector3)s.
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
### getOne() {#getOne--}
```
public static FVector3 getOne()
```


单位缩放向量，所有分量均为 1

**Returns:**
[FVector3](../../com.aspose.threed/fvector3) - The unit scale vector with all components are all 1
### getZero() {#getZero--}
```
public static FVector3 getZero()
```


零向量。

**Returns:**
[FVector3](../../com.aspose.threed/fvector3) - The Zero vector.
### hashCode() {#hashCode--}
```
public int hashCode()
```




**Returns:**
int
### mul(FVector3 a, float b) {#mul-com.aspose.threed.FVector3-float-}
```
public static FVector3 mul(FVector3 a, float b)
```


\* 运算符重载

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| a | [FVector3](../../com.aspose.threed/fvector3) | 第一个向量 |
| b | float | 第二个向量 |

**Returns:**
[FVector3](../../com.aspose.threed/fvector3) - The product of two vectors
### negative(FVector3 a) {#negative-com.aspose.threed.FVector3-}
```
public static FVector3 negative(FVector3 a)
```


\- 运算符重载

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| a | [FVector3](../../com.aspose.threed/fvector3) | 输入向量 |

**Returns:**
[FVector3](../../com.aspose.threed/fvector3) - The negative vector
### normalize() {#normalize--}
```
public FVector3 normalize()
```


归一化此实例。

**Returns:**
[FVector3](../../com.aspose.threed/fvector3) - Normalized vector.
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### sub(FVector3 a, FVector3 b) {#sub-com.aspose.threed.FVector3-com.aspose.threed.FVector3-}
```
public static FVector3 sub(FVector3 a, FVector3 b)
```


\- 运算符重载

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| a | [FVector3](../../com.aspose.threed/fvector3) | 第一个向量 |
| b | [FVector3](../../com.aspose.threed/fvector3) | 第二个向量 |

**Returns:**
[FVector3](../../com.aspose.threed/fvector3) - The difference of two vectors
### toString() {#toString--}
```
public String toString()
```


返回表示 [FVector3](../../com.aspose.threed/fvector3) 的字符串

**Returns:**
java.lang.String - 此向量的字符串表示。
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


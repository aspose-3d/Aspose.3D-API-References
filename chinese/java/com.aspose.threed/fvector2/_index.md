---
title: "FVector2"
second_title: "Aspose.3D for Java API 参考"
description: "具有两个分量的 float 向量。"
type: docs
weight: 59
url: /zh/java/com.aspose.threed/fvector2/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.threed.Struct, java.io.Serializable
```
public final class FVector2 implements Struct<FVector2>, Serializable
```

具有两个分量的 float 向量。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [FVector2(float x, float y)](#FVector2-float-float-) | 初始化 [FVector2](../../com.aspose.threed/fvector2) 的新实例。 |
| [FVector2(Vector2 vec)](#FVector2-com.aspose.threed.Vector2-) | 初始化 [FVector2](../../com.aspose.threed/fvector2) 的新实例。 |
| [FVector2()](#FVector2--) |  |
## 字段

| 字段 | 描述 |
| --- | --- |
| [x](#x) | x 分量。 |
| [y](#y) | y 分量。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [add(FVector2 a, FVector2 b)](#add-com.aspose.threed.FVector2-com.aspose.threed.FVector2-) | \+ 运算符重载 |
| [clone()](#clone--) |  |
| [copyFrom(FVector2 src)](#copyFrom-com.aspose.threed.FVector2-) |  |
| [create(FVector2 v)](#create-com.aspose.threed.FVector2-) | 显式转换运算符，将 FVector2 强制转换为 Vector2 |
| [equals(FVector2 rhs)](#equals-com.aspose.threed.FVector2-) | 检查两个向量是否相等 |
| [equals(Object obj)](#equals-java.lang.Object-) | 检查两个向量是否相等 |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) | 获取此实例的哈希码 |
| [mul(FVector2 a, float b)](#mul-com.aspose.threed.FVector2-float-) | \* 运算符重载 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [op_eq(FVector2 a, FVector2 b)](#op-eq-com.aspose.threed.FVector2-com.aspose.threed.FVector2-) | == 运算符重载 |
| [op_ne(FVector2 a, FVector2 b)](#op-ne-com.aspose.threed.FVector2-com.aspose.threed.FVector2-) | != 运算符重载 |
| [sub(FVector2 a, FVector2 b)](#sub-com.aspose.threed.FVector2-com.aspose.threed.FVector2-) | \- 运算符重载 |
| [toString()](#toString--) | 返回表示 [FVector2](../../com.aspose.threed/fvector2) 的字符串 |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### FVector2(float x, float y) {#FVector2-float-float-}
```
public FVector2(float x, float y)
```


初始化 [FVector2](../../com.aspose.threed/fvector2) 的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| x | float | 向量的 X 分量 |
| y | float | 向量的 Y 分量 |

### FVector2(Vector2 vec) {#FVector2-com.aspose.threed.Vector2-}
```
public FVector2(Vector2 vec)
```


初始化 [FVector2](../../com.aspose.threed/fvector2) 的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| vec | [Vector2](../../com.aspose.threed/vector2) | double 类型的 Vector2 |

### FVector2() {#FVector2--}
```
public FVector2()
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

### add(FVector2 a, FVector2 b) {#add-com.aspose.threed.FVector2-com.aspose.threed.FVector2-}
```
public static FVector2 add(FVector2 a, FVector2 b)
```


\+ 运算符重载

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| a | [FVector2](../../com.aspose.threed/fvector2) | 第一个向量 |
| b | [FVector2](../../com.aspose.threed/fvector2) | 第二个向量 |

**Returns:**
[FVector2](../../com.aspose.threed/fvector2) - The sum of two vectors.
### clone() {#clone--}
```
public FVector2 clone()
```


克隆当前实例

**Returns:**
[FVector2](../../com.aspose.threed/fvector2)
### copyFrom(FVector2 src) {#copyFrom-com.aspose.threed.FVector2-}
```
public void copyFrom(FVector2 src)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| src | [FVector2](../../com.aspose.threed/fvector2) |  |

### create(FVector2 v) {#create-com.aspose.threed.FVector2-}
```
public static Vector2 create(FVector2 v)
```


显式转换运算符，将 FVector2 强制转换为 Vector2

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| v | [FVector2](../../com.aspose.threed/fvector2) | float 类型的 Vector 2。 |

**Returns:**
[Vector2](../../com.aspose.threed/vector2)
### equals(FVector2 rhs) {#equals-com.aspose.threed.FVector2-}
```
public boolean equals(FVector2 rhs)
```


检查两个向量是否相等

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| rhs | [FVector2](../../com.aspose.threed/fvector2) |  |

**Returns:**
boolean - 如果所有分量相等则为 True。
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
boolean - 如果输入是向量且所有分量相等则为 True。
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


获取此实例的哈希码

**Returns:**
int - 向量的哈希码。
### mul(FVector2 a, float b) {#mul-com.aspose.threed.FVector2-float-}
```
public static FVector2 mul(FVector2 a, float b)
```


\* 运算符重载

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| a | [FVector2](../../com.aspose.threed/fvector2) | 第一个向量 |
| b | float | 第二个向量 |

**Returns:**
[FVector2](../../com.aspose.threed/fvector2) - The product of two vectors.
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### op_eq(FVector2 a, FVector2 b) {#op-eq-com.aspose.threed.FVector2-com.aspose.threed.FVector2-}
```
public static boolean op_eq(FVector2 a, FVector2 b)
```


== 运算符重载

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| a | [FVector2](../../com.aspose.threed/fvector2) | 第一个向量 |
| b | [FVector2](../../com.aspose.threed/fvector2) | 第二个向量 |

**Returns:**
boolean - 如果所有分量相等则为 True。
### op_ne(FVector2 a, FVector2 b) {#op-ne-com.aspose.threed.FVector2-com.aspose.threed.FVector2-}
```
public static boolean op_ne(FVector2 a, FVector2 b)
```


!= Operator overloading

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| a | [FVector2](../../com.aspose.threed/fvector2) | 第一个向量 |
| b | [FVector2](../../com.aspose.threed/fvector2) | 第二个向量 |

**Returns:**
boolean - 如果任意分量不同则为 True。
### sub(FVector2 a, FVector2 b) {#sub-com.aspose.threed.FVector2-com.aspose.threed.FVector2-}
```
public static FVector2 sub(FVector2 a, FVector2 b)
```


\- 运算符重载

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| a | [FVector2](../../com.aspose.threed/fvector2) | 第一个向量 |
| b | [FVector2](../../com.aspose.threed/fvector2) | 第二个向量 |

**Returns:**
[FVector2](../../com.aspose.threed/fvector2) - The difference of two vectors.
### toString() {#toString--}
```
public String toString()
```


返回表示 [FVector2](../../com.aspose.threed/fvector2) 的字符串

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


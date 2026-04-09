---
title: FVector2
second_title: Aspose.3D for Java API リファレンス
description: 2 要素の float ベクトルです。
type: docs
weight: 59
url: /ja/java/com.aspose.threed/fvector2/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.threed.Struct, java.io.Serializable
```
public final class FVector2 implements Struct<FVector2>, Serializable
```

2 要素の float ベクトルです。
## Constructors

| Constructor | 説明 |
| --- | --- |
| [FVector2(float x, float y)](#FVector2-float-float-) | [FVector2](../../com.aspose.threed/fvector2) の新しいインスタンスを初期化します。 |
| [FVector2(Vector2 vec)](#FVector2-com.aspose.threed.Vector2-) | [FVector2](../../com.aspose.threed/fvector2) の新しいインスタンスを初期化します。 |
| [FVector2()](#FVector2--) |  |
## フィールド

| フィールド | 説明 |
| --- | --- |
| [x](#x) | The x component. |
| [y](#y) | The y component. |
## Methods

| Method | 説明 |
| --- | --- |
| [add(FVector2 a, FVector2 b)](#add-com.aspose.threed.FVector2-com.aspose.threed.FVector2-) | \+ Operator overloading |
| [clone()](#clone--) |  |
| [copyFrom(FVector2 src)](#copyFrom-com.aspose.threed.FVector2-) |  |
| [create(FVector2 v)](#create-com.aspose.threed.FVector2-) | Explicit conversion operator to cast FVector2 to Vector2 |
| [equals(FVector2 rhs)](#equals-com.aspose.threed.FVector2-) | Check if two vectors are equal |
| [equals(Object obj)](#equals-java.lang.Object-) | Check if two vectors are equal |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) | Gets the hash code of this instance |
| [mul(FVector2 a, float b)](#mul-com.aspose.threed.FVector2-float-) | \* operator overloading |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [op_eq(FVector2 a, FVector2 b)](#op-eq-com.aspose.threed.FVector2-com.aspose.threed.FVector2-) | == Operator overloading |
| [op_ne(FVector2 a, FVector2 b)](#op-ne-com.aspose.threed.FVector2-com.aspose.threed.FVector2-) | != Operator overloading |
| [sub(FVector2 a, FVector2 b)](#sub-com.aspose.threed.FVector2-com.aspose.threed.FVector2-) | \- Operator overloading |
| [toString()](#toString--) | Returns a string that represents the [FVector2](../../com.aspose.threed/fvector2) |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### FVector2(float x, float y) {#FVector2-float-float-}
```
public FVector2(float x, float y)
```


[FVector2](../../com.aspose.threed/fvector2) の新しいインスタンスを初期化します。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| x | float | X component of the vector |
| y | float | Y component of the vector |

### FVector2(Vector2 vec) {#FVector2-com.aspose.threed.Vector2-}
```
public FVector2(Vector2 vec)
```


[FVector2](../../com.aspose.threed/fvector2) の新しいインスタンスを初期化します。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| vec | [Vector2](../../com.aspose.threed/vector2) | Vector2 in double type |

### FVector2() {#FVector2--}
```
public FVector2()
```


### x {#x}
```
public float x
```


The x component.

### y {#y}
```
public float y
```


The y component.

### add(FVector2 a, FVector2 b) {#add-com.aspose.threed.FVector2-com.aspose.threed.FVector2-}
```
public static FVector2 add(FVector2 a, FVector2 b)
```


\+ Operator overloading

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| a | [FVector2](../../com.aspose.threed/fvector2) | First vector |
| b | [FVector2](../../com.aspose.threed/fvector2) | Second vector |

**Returns:**
[FVector2](../../com.aspose.threed/fvector2) - The sum of two vectors.
### clone() {#clone--}
```
public FVector2 clone()
```


現在のインスタンスをクローンする

**Returns:**
[FVector2](../../com.aspose.threed/fvector2)
### copyFrom(FVector2 src) {#copyFrom-com.aspose.threed.FVector2-}
```
public void copyFrom(FVector2 src)
```




**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| src | [FVector2](../../com.aspose.threed/fvector2) |  |

### create(FVector2 v) {#create-com.aspose.threed.FVector2-}
```
public static Vector2 create(FVector2 v)
```


Explicit conversion operator to cast FVector2 to Vector2

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| v | [FVector2](../../com.aspose.threed/fvector2) | Vector 2 in float type. |

**Returns:**
[Vector2](../../com.aspose.threed/vector2)
### equals(FVector2 rhs) {#equals-com.aspose.threed.FVector2-}
```
public boolean equals(FVector2 rhs)
```


Check if two vectors are equal

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| rhs | [FVector2](../../com.aspose.threed/fvector2) |  |

**Returns:**
boolean - True if all components are equal.
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Check if two vectors are equal

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| obj | java.lang.Object |  |

**Returns:**
boolean - True if input is a vector and all components are equal.
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


Gets the hash code of this instance

**Returns:**
int - The hash code of the vector.
### mul(FVector2 a, float b) {#mul-com.aspose.threed.FVector2-float-}
```
public static FVector2 mul(FVector2 a, float b)
```


\* operator overloading

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| a | [FVector2](../../com.aspose.threed/fvector2) | First vector |
| b | float | Second vector |

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


== Operator overloading

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| a | [FVector2](../../com.aspose.threed/fvector2) | First vector |
| b | [FVector2](../../com.aspose.threed/fvector2) | Second vector |

**Returns:**
boolean - True if all components are equal.
### op_ne(FVector2 a, FVector2 b) {#op-ne-com.aspose.threed.FVector2-com.aspose.threed.FVector2-}
```
public static boolean op_ne(FVector2 a, FVector2 b)
```


!= Operator overloading

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| a | [FVector2](../../com.aspose.threed/fvector2) | First vector |
| b | [FVector2](../../com.aspose.threed/fvector2) | Second vector |

**Returns:**
boolean - True if any component is different.
### sub(FVector2 a, FVector2 b) {#sub-com.aspose.threed.FVector2-com.aspose.threed.FVector2-}
```
public static FVector2 sub(FVector2 a, FVector2 b)
```


\- Operator overloading

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| a | [FVector2](../../com.aspose.threed/fvector2) | First vector |
| b | [FVector2](../../com.aspose.threed/fvector2) | Second vector |

**Returns:**
[FVector2](../../com.aspose.threed/fvector2) - The difference of two vectors.
### toString() {#toString--}
```
public String toString()
```


Returns a string that represents the [FVector2](../../com.aspose.threed/fvector2)

**Returns:**
java.lang.String - String representation of current vector.
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final void wait(long arg0)
```




**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |


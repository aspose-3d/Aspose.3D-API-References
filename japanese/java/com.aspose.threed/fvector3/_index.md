---
title: FVector3
second_title: Aspose.3D for Java API リファレンス
description: 3 要素の float ベクトルです。
type: docs
weight: 60
url: /ja/java/com.aspose.threed/fvector3/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.threed.Struct, java.io.Serializable
```
public final class FVector3 implements Struct<FVector3>, Serializable
```

3 要素の float ベクトルです。
## Constructors

| Constructor | 説明 |
| --- | --- |
| [FVector3(float x, float y, float z)](#FVector3-float-float-float-) | 新しい [FVector3](../../com.aspose.threed/fvector3) のインスタンスを初期化します。 |
| [FVector3(Vector3 vec)](#FVector3-com.aspose.threed.Vector3-) | 新しい [FVector3](../../com.aspose.threed/fvector3) のインスタンスを初期化します。 |
| [FVector3(Vector4 vec)](#FVector3-com.aspose.threed.Vector4-) | [FVector4](../../com.aspose.threed/fvector4) の新しいインスタンスを初期化します。 |
| [FVector3()](#FVector3--) |  |
## フィールド

| フィールド | 説明 |
| --- | --- |
| [x](#x) | The x component. |
| [y](#y) | The y component. |
| [z](#z) | The y component. |
## Methods

| Method | 説明 |
| --- | --- |
| [add(FVector3 a, FVector3 b)](#add-com.aspose.threed.FVector3-com.aspose.threed.FVector3-) | \+ Operator overloading |
| [clone()](#clone--) |  |
| [copyFrom(FVector3 src)](#copyFrom-com.aspose.threed.FVector3-) |  |
| [create(FVector3 v)](#create-com.aspose.threed.FVector3-) | FVector3 を Vector3 にキャストする明示的変換演算子 |
| [cross(FVector3 rhs)](#cross-com.aspose.threed.FVector3-) | Cross product of two vectors |
| [equals(Object obj)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getOne()](#getOne--) | すべての成分が 1 の単位スケールベクトル |
| [getZero()](#getZero--) | ゼロベクトルです。 |
| [hashCode()](#hashCode--) |  |
| [mul(FVector3 a, float b)](#mul-com.aspose.threed.FVector3-float-) | \* 演算子オーバーロード |
| [negative(FVector3 a)](#negative-com.aspose.threed.FVector3-) | \- Operator overloading |
| [normalize()](#normalize--) | このインスタンスを正規化します。 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [sub(FVector3 a, FVector3 b)](#sub-com.aspose.threed.FVector3-com.aspose.threed.FVector3-) | \- Operator overloading |
| [toString()](#toString--) | [FVector3](../../com.aspose.threed/fvector3) を表す文字列を返します |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### FVector3(float x, float y, float z) {#FVector3-float-float-float-}
```
public FVector3(float x, float y, float z)
```


新しい [FVector3](../../com.aspose.threed/fvector3) のインスタンスを初期化します。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| x | float | X component of the vector |
| y | float | Y component of the vector |
| z | float | ベクトルの Z 成分 |

### FVector3(Vector3 vec) {#FVector3-com.aspose.threed.Vector3-}
```
public FVector3(Vector3 vec)
```


新しい [FVector3](../../com.aspose.threed/fvector3) のインスタンスを初期化します。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| vec | [Vector3](../../com.aspose.threed/vector3) | double 型の Vector3 |

### FVector3(Vector4 vec) {#FVector3-com.aspose.threed.Vector4-}
```
public FVector3(Vector4 vec)
```


[FVector4](../../com.aspose.threed/fvector4) の新しいインスタンスを初期化します。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| vec | [Vector4](../../com.aspose.threed/vector4) | double 型の Vector4 |

### FVector3() {#FVector3--}
```
public FVector3()
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

### z {#z}
```
public float z
```


The y component.

### add(FVector3 a, FVector3 b) {#add-com.aspose.threed.FVector3-com.aspose.threed.FVector3-}
```
public static FVector3 add(FVector3 a, FVector3 b)
```


\+ Operator overloading

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| a | [FVector3](../../com.aspose.threed/fvector3) | First vector |
| b | [FVector3](../../com.aspose.threed/fvector3) | Second vector |

**Returns:**
[FVector3](../../com.aspose.threed/fvector3)
### clone() {#clone--}
```
public FVector3 clone()
```


現在のインスタンスをクローンする

**Returns:**
[FVector3](../../com.aspose.threed/fvector3)
### copyFrom(FVector3 src) {#copyFrom-com.aspose.threed.FVector3-}
```
public void copyFrom(FVector3 src)
```




**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| src | [FVector3](../../com.aspose.threed/fvector3) |  |

### create(FVector3 v) {#create-com.aspose.threed.FVector3-}
```
public static Vector3 create(FVector3 v)
```


FVector3 を Vector3 にキャストする明示的変換演算子

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| v | [FVector3](../../com.aspose.threed/fvector3) | float 型の Vector3 |

**Returns:**
[Vector3](../../com.aspose.threed/vector3)
### cross(FVector3 rhs) {#cross-com.aspose.threed.FVector3-}
```
public FVector3 cross(FVector3 rhs)
```


Cross product of two vectors

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| rhs | [FVector3](../../com.aspose.threed/fvector3) | Right hand side value. |

**Returns:**
[FVector3](../../com.aspose.threed/fvector3) - Cross product of two [FVector3](../../com.aspose.threed/fvector3)s.
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```




**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| obj | java.lang.Object |  |

**Returns:**
boolean
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


すべての成分が 1 の単位スケールベクトル

**Returns:**
[FVector3](../../com.aspose.threed/fvector3) - The unit scale vector with all components are all 1
### getZero() {#getZero--}
```
public static FVector3 getZero()
```


ゼロベクトルです。

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


\* 演算子オーバーロード

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| a | [FVector3](../../com.aspose.threed/fvector3) | First vector |
| b | float | Second vector |

**Returns:**
[FVector3](../../com.aspose.threed/fvector3) - The product of two vectors
### negative(FVector3 a) {#negative-com.aspose.threed.FVector3-}
```
public static FVector3 negative(FVector3 a)
```


\- Operator overloading

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| a | [FVector3](../../com.aspose.threed/fvector3) | 入力ベクトル |

**Returns:**
[FVector3](../../com.aspose.threed/fvector3) - The negative vector
### normalize() {#normalize--}
```
public FVector3 normalize()
```


このインスタンスを正規化します。

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


\- Operator overloading

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| a | [FVector3](../../com.aspose.threed/fvector3) | First vector |
| b | [FVector3](../../com.aspose.threed/fvector3) | Second vector |

**Returns:**
[FVector3](../../com.aspose.threed/fvector3) - The difference of two vectors
### toString() {#toString--}
```
public String toString()
```


[FVector3](../../com.aspose.threed/fvector3) を表す文字列を返します

**Returns:**
java.lang.String - このベクトルの文字列表現。
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


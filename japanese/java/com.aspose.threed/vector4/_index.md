---
title: Vector4
second_title: Aspose.3D for Java API リファレンス
description: 4 つの成分を持つベクトル。
type: docs
weight: 203
url: /ja/java/com.aspose.threed/vector4/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.lang.Comparable, com.aspose.threed.Struct, java.io.Serializable
```
public final class Vector4 implements Comparable<Vector4>, Struct<Vector4>, Serializable
```

4 つの成分を持つベクトル。
## Constructors

| Constructor | 説明 |
| --- | --- |
| [Vector4(Vector3 vec, double w)](#Vector4-com.aspose.threed.Vector3-double-) | 新しい [Vector4](../../com.aspose.threed/vector4) 構造体のインスタンスを初期化します。 |
| [Vector4(Vector3 vec)](#Vector4-com.aspose.threed.Vector3-) | 新しい [Vector4](../../com.aspose.threed/vector4) 構造体のインスタンスを初期化します。 |
| [Vector4(FVector4 vec)](#Vector4-com.aspose.threed.FVector4-) | 新しい [Vector4](../../com.aspose.threed/vector4) 構造体のインスタンスを初期化します。 |
| [Vector4(double x, double y, double z)](#Vector4-double-double-double-) | 新しい [Vector4](../../com.aspose.threed/vector4) 構造体のインスタンスを初期化します。 |
| [Vector4(double x, double y, double z, double w)](#Vector4-double-double-double-double-) | 新しい [Vector4](../../com.aspose.threed/vector4) 構造体のインスタンスを初期化します。 |
| [Vector4()](#Vector4--) |  |
## フィールド

| フィールド | 説明 |
| --- | --- |
| [w](#w) | w コンポーネント。 |
| [x](#x) | The x component. |
| [y](#y) | The y component. |
| [z](#z) | The z component. |
## Methods

| Method | 説明 |
| --- | --- |
| [add(Vector4 lhs, Vector4 rhs)](#add-com.aspose.threed.Vector4-com.aspose.threed.Vector4-) | Operator overloading for + |
| [clone()](#clone--) |  |
| [compareTo(Vector4 other)](#compareTo-com.aspose.threed.Vector4-) | Compare current vector to another instance. |
| [copyFrom(Vector4 src)](#copyFrom-com.aspose.threed.Vector4-) |  |
| [create(Vector4 v)](#create-com.aspose.threed.Vector4-) | Vector4 を FVector4 にキャストする明示的変換演算子 |
| [equals(Object obj)](#equals-java.lang.Object-) | Check if two vectors are equal |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) | このベクトルのハッシュコードを取得します |
| [mul(Vector4 lhs, Vector4 rhs)](#mul-com.aspose.threed.Vector4-com.aspose.threed.Vector4-) | Operator overloading for \* |
| [mul(Vector4 lhs, double rhs)](#mul-com.aspose.threed.Vector4-double-) | Operator overloading for \* |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [set(double newX, double newY, double newZ)](#set-double-double-double-) | ベクトルの xyz 成分を一度に設定し、w は 1 に設定されます |
| [set(double newX, double newY, double newZ, double newW)](#set-double-double-double-double-) | ベクトルのすべての成分を一度に設定します |
| [sub(Vector4 lhs, Vector4 rhs)](#sub-com.aspose.threed.Vector4-com.aspose.threed.Vector4-) | 「-」(マイナス) の演算子オーバーロード |
| [toString()](#toString--) | 現在の [Vector4](../../com.aspose.threed/vector4) を表す java.lang.String を返します。 |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Vector4(Vector3 vec, double w) {#Vector4-com.aspose.threed.Vector3-double-}
```
public Vector4(Vector3 vec, double w)
```


新しい [Vector4](../../com.aspose.threed/vector4) 構造体のインスタンスを初期化します。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| vec | [Vector3](../../com.aspose.threed/vector3) | Vec. |
| w | double | 幅です。 |

### Vector4(Vector3 vec) {#Vector4-com.aspose.threed.Vector3-}
```
public Vector4(Vector3 vec)
```


新しい [Vector4](../../com.aspose.threed/vector4) 構造体のインスタンスを初期化します。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| vec | [Vector3](../../com.aspose.threed/vector3) | Vec. |

### Vector4(FVector4 vec) {#Vector4-com.aspose.threed.FVector4-}
```
public Vector4(FVector4 vec)
```


新しい [Vector4](../../com.aspose.threed/vector4) 構造体のインスタンスを初期化します。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| vec | [FVector4](../../com.aspose.threed/fvector4) | Vec. |

### Vector4(double x, double y, double z) {#Vector4-double-double-double-}
```
public Vector4(double x, double y, double z)
```


新しい [Vector4](../../com.aspose.threed/vector4) 構造体のインスタンスを初期化します。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| x | double | x 座標。 |
| y | double | y 座標。 |
| z | double | z 座標。 |

### Vector4(double x, double y, double z, double w) {#Vector4-double-double-double-double-}
```
public Vector4(double x, double y, double z, double w)
```


新しい [Vector4](../../com.aspose.threed/vector4) 構造体のインスタンスを初期化します。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| x | double | x 座標。 |
| y | double | y 座標。 |
| z | double | z 座標。 |
| w | double | 幅です。 |

### Vector4() {#Vector4--}
```
public Vector4()
```


### w {#w}
```
public double w
```


w コンポーネント。

### x {#x}
```
public double x
```


The x component.

### y {#y}
```
public double y
```


The y component.

### z {#z}
```
public double z
```


The z component.

### add(Vector4 lhs, Vector4 rhs) {#add-com.aspose.threed.Vector4-com.aspose.threed.Vector4-}
```
public static Vector4 add(Vector4 lhs, Vector4 rhs)
```


Operator overloading for +

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| lhs | [Vector4](../../com.aspose.threed/vector4) | 左ベクトル |
| rhs | [Vector4](../../com.aspose.threed/vector4) | 右ベクトル |

**Returns:**
[Vector4](../../com.aspose.threed/vector4) - Result vector
### clone() {#clone--}
```
public Vector4 clone()
```


現在のインスタンスをクローンする

**Returns:**
[Vector4](../../com.aspose.threed/vector4)
### compareTo(Vector4 other) {#compareTo-com.aspose.threed.Vector4-}
```
public int compareTo(Vector4 other)
```


Compare current vector to another instance.

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| other | [Vector4](../../com.aspose.threed/vector4) |  |

**Returns:**
int
### copyFrom(Vector4 src) {#copyFrom-com.aspose.threed.Vector4-}
```
public void copyFrom(Vector4 src)
```




**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| src | [Vector4](../../com.aspose.threed/vector4) |  |

### create(Vector4 v) {#create-com.aspose.threed.Vector4-}
```
public static FVector4 create(Vector4 v)
```


Vector4 を FVector4 にキャストする明示的変換演算子

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| v | [Vector4](../../com.aspose.threed/vector4) |  |

**Returns:**
[FVector4](../../com.aspose.threed/fvector4)
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
boolean
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


このベクトルのハッシュコードを取得します

**Returns:**
int
### mul(Vector4 lhs, Vector4 rhs) {#mul-com.aspose.threed.Vector4-com.aspose.threed.Vector4-}
```
public static Vector4 mul(Vector4 lhs, Vector4 rhs)
```


Operator overloading for \*

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| lhs | [Vector4](../../com.aspose.threed/vector4) | 左ベクトル |
| rhs | [Vector4](../../com.aspose.threed/vector4) | 右ベクトル |

**Returns:**
[Vector4](../../com.aspose.threed/vector4) - Result vector
### mul(Vector4 lhs, double rhs) {#mul-com.aspose.threed.Vector4-double-}
```
public static Vector4 mul(Vector4 lhs, double rhs)
```


Operator overloading for \*

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| lhs | [Vector4](../../com.aspose.threed/vector4) | 左ベクトル |
| rhs | double | The right double value |

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


ベクトルの xyz 成分を一度に設定し、w は 1 に設定されます

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| newX | double | 新しい X 成分です。 |
| newY | double | 新しい Y 成分です。 |
| newZ | double | 新しい Z 成分です。 |

### set(double newX, double newY, double newZ, double newW) {#set-double-double-double-double-}
```
public void set(double newX, double newY, double newZ, double newW)
```


ベクトルのすべての成分を一度に設定します

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| newX | double | 新しい X 成分です。 |
| newY | double | 新しい Y 成分です。 |
| newZ | double | 新しい Z 成分です。 |
| newW | double | New W component. |

### sub(Vector4 lhs, Vector4 rhs) {#sub-com.aspose.threed.Vector4-com.aspose.threed.Vector4-}
```
public static Vector4 sub(Vector4 lhs, Vector4 rhs)
```


「-」(マイナス) の演算子オーバーロード

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| lhs | [Vector4](../../com.aspose.threed/vector4) | 左ベクトル |
| rhs | [Vector4](../../com.aspose.threed/vector4) | 右ベクトル |

**Returns:**
[Vector4](../../com.aspose.threed/vector4) - Result vector
### toString() {#toString--}
```
public String toString()
```


現在の [Vector4](../../com.aspose.threed/vector4) を表す java.lang.String を返します。

**Returns:**
java.lang.String - 現在の [Vector4](../../com.aspose.threed/vector4) を表す java.lang.String。
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


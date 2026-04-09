---
title: Vector2
second_title: Aspose.3D for Java API リファレンス
description: 2 つの成分を持つベクトル。
type: docs
weight: 201
url: /ja/java/com.aspose.threed/vector2/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.lang.Comparable, com.aspose.threed.Struct, java.io.Serializable
```
public final class Vector2 implements Comparable<Vector2>, Struct<Vector2>, Serializable
```

2 つの成分を持つベクトル。
## Constructors

| Constructor | 説明 |
| --- | --- |
| [Vector2(double s)](#Vector2-double-) | [Vector2](../../com.aspose.threed/vector2) 構造体の新しいインスタンスを初期化します。 |
| [Vector2(Vector3 s)](#Vector2-com.aspose.threed.Vector3-) | [Vector2](../../com.aspose.threed/vector2) 構造体の新しいインスタンスを初期化します。 |
| [Vector2(FVector2 vec)](#Vector2-com.aspose.threed.FVector2-) | [Vector2](../../com.aspose.threed/vector2) 構造体の新しいインスタンスを初期化します。 |
| [Vector2(double x, double y)](#Vector2-double-double-) | [Vector2](../../com.aspose.threed/vector2) 構造体の新しいインスタンスを初期化します。 |
| [Vector2()](#Vector2--) |  |
## フィールド

| フィールド | 説明 |
| --- | --- |
| [x](#x) | The x component. |
| [y](#y) | The y component. |
## Methods

| Method | 説明 |
| --- | --- |
| [add(Vector2 lhs, Vector2 rhs)](#add-com.aspose.threed.Vector2-com.aspose.threed.Vector2-) | Vector2 の加算演算子 |
| [clone()](#clone--) |  |
| [compareTo(Vector2 other)](#compareTo-com.aspose.threed.Vector2-) | Compare current vector to another instance. |
| [copyFrom(Vector2 src)](#copyFrom-com.aspose.threed.Vector2-) |  |
| [create(Vector2 v)](#create-com.aspose.threed.Vector2-) | Vector2 を FVector2 にキャストする明示的変換演算子 |
| [cross(Vector2 v)](#cross-com.aspose.threed.Vector2-) | Cross product of two vectors |
| [div(Vector2 lhs, double rhs)](#div-com.aspose.threed.Vector2-double-) | Vector2 の除算演算子 |
| [dot(Vector2 rhs)](#dot-com.aspose.threed.Vector2-) | Gets the dot product of two vectors |
| [equals(Vector2 rhs)](#equals-com.aspose.threed.Vector2-) | 二つの vector2 が等しいかチェックします |
| [equals(Object obj)](#equals-java.lang.Object-) | 二つの vector2 が等しいかチェックします |
| [getClass()](#getClass--) |  |
| [getLength()](#getLength--) | 長さを取得します。 |
| [getU()](#getU--) | [Vector2](../../com.aspose.threed/vector2) がマッピング座標として使用される場合の U 成分を取得します。 |
| [getV()](#getV--) | [Vector2](../../com.aspose.threed/vector2) がマッピング座標として使用される場合の V 成分を取得します。 |
| [hashCode()](#hashCode--) | Vector2 のハッシュコードを取得します |
| [mul(Vector2 lhs, double rhs)](#mul-com.aspose.threed.Vector2-double-) | Vector2 の乗算演算子 |
| [mul(double lhs, Vector2 rhs)](#mul-double-com.aspose.threed.Vector2-) | Vector2 の乗算演算子 |
| [normalize()](#normalize--) | このインスタンスを正規化します。 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [op_eq(Vector2 lhs, Vector2 rhs)](#op-eq-com.aspose.threed.Vector2-com.aspose.threed.Vector2-) | Vector2 の等価演算子 |
| [op_ne(Vector2 lhs, Vector2 rhs)](#op-ne-com.aspose.threed.Vector2-com.aspose.threed.Vector2-) | Vector2 の不等価演算子 |
| [setU(double value)](#setU-double-) | [Vector2](../../com.aspose.threed/vector2) がマッピング座標として使用されている場合、U 成分を設定します。 |
| [setV(double value)](#setV-double-) | [Vector2](../../com.aspose.threed/vector2) がマッピング座標として使用されている場合、V 成分を設定します。 |
| [sub(Vector2 lhs, Vector2 rhs)](#sub-com.aspose.threed.Vector2-com.aspose.threed.Vector2-) | Vector2 の減算演算子 |
| [toString()](#toString--) | 現在の [Vector2](../../com.aspose.threed/vector2) を表す java.lang.String を返します。 |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Vector2(double s) {#Vector2-double-}
```
public Vector2(double s)
```


[Vector2](../../com.aspose.threed/vector2) 構造体の新しいインスタンスを初期化します。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| s | double | S。 |

### Vector2(Vector3 s) {#Vector2-com.aspose.threed.Vector3-}
```
public Vector2(Vector3 s)
```


[Vector2](../../com.aspose.threed/vector2) 構造体の新しいインスタンスを初期化します。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| s | [Vector3](../../com.aspose.threed/vector3) | S。 |

### Vector2(FVector2 vec) {#Vector2-com.aspose.threed.FVector2-}
```
public Vector2(FVector2 vec)
```


[Vector2](../../com.aspose.threed/vector2) 構造体の新しいインスタンスを初期化します。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| vec | [FVector2](../../com.aspose.threed/fvector2) | float 型のベクトル。 |

### Vector2(double x, double y) {#Vector2-double-double-}
```
public Vector2(double x, double y)
```


[Vector2](../../com.aspose.threed/vector2) 構造体の新しいインスタンスを初期化します。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| x | double | x 座標。 |
| y | double | y 座標。 |

### Vector2() {#Vector2--}
```
public Vector2()
```


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

### add(Vector2 lhs, Vector2 rhs) {#add-com.aspose.threed.Vector2-com.aspose.threed.Vector2-}
```
public static Vector2 add(Vector2 lhs, Vector2 rhs)
```


Vector2 の加算演算子

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| lhs | [Vector2](../../com.aspose.threed/vector2) | Left hand side value. |
| rhs | [Vector2](../../com.aspose.threed/vector2) | Right hand side value. |

**Returns:**
[Vector2](../../com.aspose.threed/vector2) - The result of addition.
### clone() {#clone--}
```
public Vector2 clone()
```


現在のインスタンスをクローンする

**Returns:**
[Vector2](../../com.aspose.threed/vector2)
### compareTo(Vector2 other) {#compareTo-com.aspose.threed.Vector2-}
```
public int compareTo(Vector2 other)
```


Compare current vector to another instance.

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| other | [Vector2](../../com.aspose.threed/vector2) |  |

**Returns:**
int
### copyFrom(Vector2 src) {#copyFrom-com.aspose.threed.Vector2-}
```
public void copyFrom(Vector2 src)
```




**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| src | [Vector2](../../com.aspose.threed/vector2) |  |

### create(Vector2 v) {#create-com.aspose.threed.Vector2-}
```
public static FVector2 create(Vector2 v)
```


Vector2 を FVector2 にキャストする明示的変換演算子

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| v | [Vector2](../../com.aspose.threed/vector2) |  |

**Returns:**
[FVector2](../../com.aspose.threed/fvector2)
### cross(Vector2 v) {#cross-com.aspose.threed.Vector2-}
```
public double cross(Vector2 v)
```


Cross product of two vectors

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| v | [Vector2](../../com.aspose.threed/vector2) |  |

**Returns:**
double
### div(Vector2 lhs, double rhs) {#div-com.aspose.threed.Vector2-double-}
```
public static Vector2 div(Vector2 lhs, double rhs)
```


Vector2 の除算演算子

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| lhs | [Vector2](../../com.aspose.threed/vector2) | Left hand side value. |
| rhs | double | Right hand side value. |

**Returns:**
[Vector2](../../com.aspose.threed/vector2) - The result of division.
### dot(Vector2 rhs) {#dot-com.aspose.threed.Vector2-}
```
public double dot(Vector2 rhs)
```


Gets the dot product of two vectors

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| rhs | [Vector2](../../com.aspose.threed/vector2) | Right hand side value. |

**Returns:**
double - The dot product of the two vectors.
### equals(Vector2 rhs) {#equals-com.aspose.threed.Vector2-}
```
public boolean equals(Vector2 rhs)
```


二つの vector2 が等しいかチェックします

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| rhs | [Vector2](../../com.aspose.threed/vector2) | 右辺の値。 |

**Returns:**
boolean - True if all components are identically equal.
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


二つの vector2 が等しいかチェックします

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| obj | java.lang.Object | 比較対象のオブジェクト。 |

**Returns:**
boolean - True if all components are identically equal.
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


長さを取得します。

**Returns:**
double - 長さ。
### getU() {#getU--}
```
public double getU()
```


[Vector2](../../com.aspose.threed/vector2) がマッピング座標として使用されている場合、U 成分を取得します。これは x 成分のエイリアスです。

**Returns:**
double - [Vector2](../../com.aspose.threed/vector2) がマッピング座標として使用されている場合の U 成分。これは x 成分のエイリアスです。
### getV() {#getV--}
```
public double getV()
```


[Vector2](../../com.aspose.threed/vector2) がマッピング座標として使用されている場合、V 成分を取得します。これは y 成分のエイリアスです。

**Returns:**
double - [Vector2](../../com.aspose.threed/vector2) がマッピング座標として使用されている場合の V 成分。これは y 成分のエイリアスです。
### hashCode() {#hashCode--}
```
public int hashCode()
```


Vector2 のハッシュコードを取得します

**Returns:**
int - [Vector2](../../com.aspose.threed/vector2) のハッシュコード
### mul(Vector2 lhs, double rhs) {#mul-com.aspose.threed.Vector2-double-}
```
public static Vector2 mul(Vector2 lhs, double rhs)
```


Vector2 の乗算演算子

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| lhs | [Vector2](../../com.aspose.threed/vector2) | Left hand side value. |
| rhs | double | Right hand side value. |

**Returns:**
[Vector2](../../com.aspose.threed/vector2) - The result of multiply.
### mul(double lhs, Vector2 rhs) {#mul-double-com.aspose.threed.Vector2-}
```
public static Vector2 mul(double lhs, Vector2 rhs)
```


Vector2 の乗算演算子

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| lhs | double | Left hand side value. |
| rhs | [Vector2](../../com.aspose.threed/vector2) | Right hand side value. |

**Returns:**
[Vector2](../../com.aspose.threed/vector2) - The result of multiply.
### normalize() {#normalize--}
```
public Vector2 normalize()
```


このインスタンスを正規化します。

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


Vector2 の等価演算子

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| lhs | [Vector2](../../com.aspose.threed/vector2) | Left hand side value. |
| rhs | [Vector2](../../com.aspose.threed/vector2) | Right hand side value. |

**Returns:**
boolean - True if all components are identically equal.
### op_ne(Vector2 lhs, Vector2 rhs) {#op-ne-com.aspose.threed.Vector2-com.aspose.threed.Vector2-}
```
public static boolean op_ne(Vector2 lhs, Vector2 rhs)
```


Vector2 の不等価演算子

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| lhs | [Vector2](../../com.aspose.threed/vector2) | Left hand side value. |
| rhs | [Vector2](../../com.aspose.threed/vector2) | Right hand side value. |

**Returns:**
boolean - True if two vectors are not equal.
### setU(double value) {#setU-double-}
```
public void setU(double value)
```


[Vector2](../../com.aspose.threed/vector2) がマッピング座標として使用されている場合、U 成分を設定します。これは x 成分のエイリアスです。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| 値 | double | 新しい値 |

### setV(double value) {#setV-double-}
```
public void setV(double value)
```


[Vector2](../../com.aspose.threed/vector2) がマッピング座標として使用されている場合、V 成分を設定します。これは y 成分のエイリアスです。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| 値 | double | 新しい値 |

### sub(Vector2 lhs, Vector2 rhs) {#sub-com.aspose.threed.Vector2-com.aspose.threed.Vector2-}
```
public static Vector2 sub(Vector2 lhs, Vector2 rhs)
```


Vector2 の減算演算子

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| lhs | [Vector2](../../com.aspose.threed/vector2) | Left hand side value. |
| rhs | [Vector2](../../com.aspose.threed/vector2) | Right hand side value. |

**Returns:**
[Vector2](../../com.aspose.threed/vector2) - The result of substraction.
### toString() {#toString--}
```
public String toString()
```


現在の [Vector2](../../com.aspose.threed/vector2) を表す java.lang.String を返します。

**Returns:**
java.lang.String - 現在の [Vector2](../../com.aspose.threed/vector2) を表す java.lang.String。
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


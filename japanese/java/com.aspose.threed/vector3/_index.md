---
title: "Vector3"
second_title: "Aspose.3D for Java API リファレンス"
description: "3 つの成分を持つベクトル。"
type: docs
weight: 202
url: /ja/java/com.aspose.threed/vector3/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.lang.Comparable, com.aspose.threed.Struct, java.io.Serializable
```
public final class Vector3 implements Comparable<Vector3>, Struct<Vector3>, Serializable
```

3 つの成分を持つベクトル。
## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [Vector3(double x, double y, double z)](#Vector3-double-double-double-) | 新しいインスタンスを初期化します。[Vector3](../../com.aspose.threed/vector3) 構造体。 |
| [Vector3(FVector3 vec)](#Vector3-com.aspose.threed.FVector3-) | 新しいインスタンスを初期化します。[Vector3](../../com.aspose.threed/vector3) 構造体。 |
| [Vector3(double v)](#Vector3-double-) | 新しいインスタンスを初期化します。[Vector3](../../com.aspose.threed/vector3) 構造体。 |
| [Vector3(Vector4 vec4)](#Vector3-com.aspose.threed.Vector4-) | 新しいインスタンスを初期化します。[Vector3](../../com.aspose.threed/vector3) 構造体。 |
| [Vector3()](#Vector3--) |  |
## フィールド

| フィールド | 説明 |
| --- | --- |
| [x](#x) | x 成分。 |
| [y](#y) | y 成分。 |
| [z](#z) | z 成分。 |
## メソッド

| メソッド | 説明 |
| --- | --- |
| [add(Vector3 lhs, Vector3 rhs)](#add-com.aspose.threed.Vector3-com.aspose.threed.Vector3-) | + の演算子オーバーロード |
| [angleBetween(Vector3 dir)](#angleBetween-com.aspose.threed.Vector3-) | 2つの方向間の内部角度を計算します。2つの方向は正規化されていないベクトルでも構いません。 |
| [angleBetween(Vector3 dir, Vector3 up)](#angleBetween-com.aspose.threed.Vector3-com.aspose.threed.Vector3-) | 2つの方向間の内部角度を計算します。2つの方向は正規化されていないベクトルでも構いません。 |
| [clone()](#clone--) |  |
| [compareTo(Vector3 other)](#compareTo-com.aspose.threed.Vector3-) | 現在のベクトルを別のインスタンスと比較します。 |
| [copyFrom(Vector3 src)](#copyFrom-com.aspose.threed.Vector3-) |  |
| [cos()](#cos--) | 各成分の余弦を計算します。 |
| [create(Vector3 v)](#create-com.aspose.threed.Vector3-) | Vector3 を FVector3 にキャストする明示的変換演算子 |
| [cross(Vector3 rhs)](#cross-com.aspose.threed.Vector3-) | 2つのベクトルの外積 |
| [div(Vector3 lhs, Vector3 rhs)](#div-com.aspose.threed.Vector3-com.aspose.threed.Vector3-) | / の演算子オーバーロード |
| [div(Vector3 lhs, double rhs)](#div-com.aspose.threed.Vector3-double-) | / の演算子オーバーロード |
| [dot(Vector3 rhs)](#dot-com.aspose.threed.Vector3-) | 2つのベクトルのドット積を取得します |
| [equals(Object obj)](#equals-java.lang.Object-) | 2つの vector3 が等しいかチェックします |
| [get(int idx)](#get-int-) | インデックスでベクトルの成分を取得します。 |
| [getClass()](#getClass--) |  |
| [getLength()](#getLength--) | このベクトルの長さを取得します。 |
| [getLength2()](#getLength2--) | 長さの二乗を取得します。 |
| [getOne()](#getOne--) | 単位ベクトル (1, 1, 1) を取得します |
| [getUnitX()](#getUnitX--) | 単位ベクトル (1, 0, 0) を取得します |
| [getUnitY()](#getUnitY--) | 単位ベクトル (0, 1, 0) を取得します |
| [getUnitZ()](#getUnitZ--) | 単位ベクトル (0, 0, 1) を取得します |
| [getZero()](#getZero--) | 単位ベクトル (0, 0, 0) を取得します |
| [hashCode()](#hashCode--) | Vector3 のハッシュコードを取得します |
| [mul(Vector3 lhs, Vector3 rhs)](#mul-com.aspose.threed.Vector3-com.aspose.threed.Vector3-) | \* の演算子オーバーロード |
| [mul(Vector3 lhs, double rhs)](#mul-com.aspose.threed.Vector3-double-) | \* の演算子オーバーロード |
| [mul(double lhs, Vector3 rhs)](#mul-double-com.aspose.threed.Vector3-) | \* の演算子オーバーロード |
| [negative(Vector3 v)](#negative-com.aspose.threed.Vector3-) | 「-」の演算子オーバーロード |
| [normalize()](#normalize--) | このインスタンスを正規化します。 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [op_eq(Vector3 lhs, Vector3 rhs)](#op-eq-com.aspose.threed.Vector3-com.aspose.threed.Vector3-) | Vector3 の等価演算子 |
| [op_ne(Vector3 lhs, Vector3 rhs)](#op-ne-com.aspose.threed.Vector3-com.aspose.threed.Vector3-) | Vector3 の不等価演算子 |
| [set(double newX, double newY, double newZ)](#set-double-double-double-) | x/y/z コンポーネントを一度の呼び出しで設定します。 |
| [set(int idx, double value)](#set-int-double-) | インデックスでベクトルのコンポーネントを設定します。 |
| [sin()](#sin--) | 各コンポーネントの正弦を計算します |
| [sub(Vector3 lhs, Vector3 rhs)](#sub-com.aspose.threed.Vector3-com.aspose.threed.Vector3-) | 「-」(マイナス) の演算子オーバーロード |
| [toString()](#toString--) | 現在の [Vector3](../../com.aspose.threed/vector3) を表す java.lang.String を返します。 |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Vector3(double x, double y, double z) {#Vector3-double-double-double-}
```
public Vector3(double x, double y, double z)
```


新しいインスタンスを初期化します。[Vector3](../../com.aspose.threed/vector3) 構造体。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| x | double | x 座標。 |
| y | double | y 座標。 |
| z | double | z 座標。 |

### Vector3(FVector3 vec) {#Vector3-com.aspose.threed.FVector3-}
```
public Vector3(FVector3 vec)
```


新しいインスタンスを初期化します。[Vector3](../../com.aspose.threed/vector3) 構造体。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| vec | [FVector3](../../com.aspose.threed/fvector3) | x 座標。 |

### Vector3(double v) {#Vector3-double-}
```
public Vector3(double v)
```


新しいインスタンスを初期化します。[Vector3](../../com.aspose.threed/vector3) 構造体。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| v | double | V. |

### Vector3(Vector4 vec4) {#Vector3-com.aspose.threed.Vector4-}
```
public Vector3(Vector4 vec4)
```


新しいインスタンスを初期化します。[Vector3](../../com.aspose.threed/vector3) 構造体。

**Parameters:**
| パラメーター | 型 | 説明 |
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


x 成分。

### y {#y}
```
public double y
```


y 成分。

### z {#z}
```
public double z
```


z 成分。

### add(Vector3 lhs, Vector3 rhs) {#add-com.aspose.threed.Vector3-com.aspose.threed.Vector3-}
```
public static Vector3 add(Vector3 lhs, Vector3 rhs)
```


+ の演算子オーバーロード

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| lhs | [Vector3](../../com.aspose.threed/vector3) | 左ベクトル |
| rhs | [Vector3](../../com.aspose.threed/vector3) | 右ベクトル |

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - Result vector
### angleBetween(Vector3 dir) {#angleBetween-com.aspose.threed.Vector3-}
```
public double angleBetween(Vector3 dir)
```


2つの方向間の内部角度を計算します。2つの方向は正規化されていないベクトルでも構いません。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| dir | [Vector3](../../com.aspose.threed/vector3) | 比較対象の方向ベクトル |

**Returns:**
double - ラジアン単位の内部角度
### angleBetween(Vector3 dir, Vector3 up) {#angleBetween-com.aspose.threed.Vector3-com.aspose.threed.Vector3-}
```
public double angleBetween(Vector3 dir, Vector3 up)
```


2つの方向間の内部角度を計算します。2つの方向は正規化されていないベクトルでも構いません。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| dir | [Vector3](../../com.aspose.threed/vector3) | 比較対象の方向ベクトル |
| up | [Vector3](../../com.aspose.threed/vector3) | 二つの方向が共有する平面の上ベクトル |

**Returns:**
double - ラジアン単位の内部角度
### clone() {#clone--}
```
public Vector3 clone()
```


現在のインスタンスをクローンする

**Returns:**
[Vector3](../../com.aspose.threed/vector3)
### compareTo(Vector3 other) {#compareTo-com.aspose.threed.Vector3-}
```
public int compareTo(Vector3 other)
```


現在のベクトルを別のインスタンスと比較します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| other | [Vector3](../../com.aspose.threed/vector3) |  |

**Returns:**
int
### copyFrom(Vector3 src) {#copyFrom-com.aspose.threed.Vector3-}
```
public void copyFrom(Vector3 src)
```




**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| src | [Vector3](../../com.aspose.threed/vector3) |  |

### cos() {#cos--}
```
public Vector3 cos()
```


各成分の余弦を計算します。

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - Calculated [Vector3](../../com.aspose.threed/vector3).
### create(Vector3 v) {#create-com.aspose.threed.Vector3-}
```
public static FVector3 create(Vector3 v)
```


Vector3 を FVector3 にキャストする明示的変換演算子

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| v | [Vector3](../../com.aspose.threed/vector3) |  |

**Returns:**
[FVector3](../../com.aspose.threed/fvector3)
### cross(Vector3 rhs) {#cross-com.aspose.threed.Vector3-}
```
public Vector3 cross(Vector3 rhs)
```


2つのベクトルの外積

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| rhs | [Vector3](../../com.aspose.threed/vector3) | 右側の値。 |

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - Cross product of two [Vector3](../../com.aspose.threed/vector3)s.
### div(Vector3 lhs, Vector3 rhs) {#div-com.aspose.threed.Vector3-com.aspose.threed.Vector3-}
```
public static Vector3 div(Vector3 lhs, Vector3 rhs)
```


/ の演算子オーバーロード

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| lhs | [Vector3](../../com.aspose.threed/vector3) | 左ベクトル |
| rhs | [Vector3](../../com.aspose.threed/vector3) | 右ベクトル |

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - Result vector
### div(Vector3 lhs, double rhs) {#div-com.aspose.threed.Vector3-double-}
```
public static Vector3 div(Vector3 lhs, double rhs)
```


/ の演算子オーバーロード

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| lhs | [Vector3](../../com.aspose.threed/vector3) | 左ベクトル |
| rhs | double | 右側の double 値 |

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - Result vector
### dot(Vector3 rhs) {#dot-com.aspose.threed.Vector3-}
```
public double dot(Vector3 rhs)
```


2つのベクトルのドット積を取得します

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| rhs | [Vector3](../../com.aspose.threed/vector3) | 右側の値。 |

**Returns:**
double - 二つのベクトルのドット積。
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


2つの vector3 が等しいかチェックします

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| obj | java.lang.Object | 等価性をチェックするオブジェクト。 |

**Returns:**
boolean - すべてのコンポーネントが完全に等しい場合は true。
### get(int idx) {#get-int-}
```
public double get(int idx)
```


インデックスでベクトルの成分を取得します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| idx | int |  |

**Returns:**
double - インデックスによるベクトルの成分。
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


このベクトルの長さを取得します。

**Returns:**
double - このベクトルの長さ。
### getLength2() {#getLength2--}
```
public double getLength2()
```


長さの二乗を取得します。

**Returns:**
double - 長さの二乗。
### getOne() {#getOne--}
```
public static Vector3 getOne()
```


単位ベクトル (1, 1, 1) を取得します

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - unit vector (1, 1, 1)
### getUnitX() {#getUnitX--}
```
public static Vector3 getUnitX()
```


単位ベクトル (1, 0, 0) を取得します

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - unit vector (1, 0, 0)
### getUnitY() {#getUnitY--}
```
public static Vector3 getUnitY()
```


単位ベクトル (0, 1, 0) を取得します

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - unit vector (0, 1, 0)
### getUnitZ() {#getUnitZ--}
```
public static Vector3 getUnitZ()
```


単位ベクトル (0, 0, 1) を取得します

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - unit vector (0, 0, 1)
### getZero() {#getZero--}
```
public static Vector3 getZero()
```


単位ベクトル (0, 0, 0) を取得します

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - unit vector (0, 0, 0)
### hashCode() {#hashCode--}
```
public int hashCode()
```


Vector3 のハッシュコードを取得します

**Returns:**
int - [Vector3](../../com.aspose.threed/vector3) のハッシュコード。
### mul(Vector3 lhs, Vector3 rhs) {#mul-com.aspose.threed.Vector3-com.aspose.threed.Vector3-}
```
public static Vector3 mul(Vector3 lhs, Vector3 rhs)
```


\* の演算子オーバーロード

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| lhs | [Vector3](../../com.aspose.threed/vector3) | 左ベクトル |
| rhs | [Vector3](../../com.aspose.threed/vector3) | 右ベクトル |

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - Result vector
### mul(Vector3 lhs, double rhs) {#mul-com.aspose.threed.Vector3-double-}
```
public static Vector3 mul(Vector3 lhs, double rhs)
```


\* の演算子オーバーロード

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| lhs | [Vector3](../../com.aspose.threed/vector3) | 左ベクトル |
| rhs | double | 右側の double 値 |

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - Result vector
### mul(double lhs, Vector3 rhs) {#mul-double-com.aspose.threed.Vector3-}
```
public static Vector3 mul(double lhs, Vector3 rhs)
```


\* の演算子オーバーロード

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| lhs | double | 左側のスカラー |
| rhs | [Vector3](../../com.aspose.threed/vector3) | 右ベクトル |

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - Result vector
### negative(Vector3 v) {#negative-com.aspose.threed.Vector3-}
```
public static Vector3 negative(Vector3 v)
```


「-」の演算子オーバーロード

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| v | [Vector3](../../com.aspose.threed/vector3) | 原点ベクトル |

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - Result vector
### normalize() {#normalize--}
```
public Vector3 normalize()
```


このインスタンスを正規化します。

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


Vector3 の等価演算子

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| lhs | [Vector3](../../com.aspose.threed/vector3) | 左側の値。 |
| rhs | [Vector3](../../com.aspose.threed/vector3) | 右側の値。 |

**Returns:**
boolean - すべてのコンポーネントが完全に等しい場合は true。
### op_ne(Vector3 lhs, Vector3 rhs) {#op-ne-com.aspose.threed.Vector3-com.aspose.threed.Vector3-}
```
public static boolean op_ne(Vector3 lhs, Vector3 rhs)
```


Vector3 の不等価演算子

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| lhs | [Vector3](../../com.aspose.threed/vector3) | 左側の値。 |
| rhs | [Vector3](../../com.aspose.threed/vector3) | 右側の値。 |

**Returns:**
boolean - 2 つのベクトルが等しくない場合は true。
### set(double newX, double newY, double newZ) {#set-double-double-double-}
```
public void set(double newX, double newY, double newZ)
```


x/y/z コンポーネントを一度の呼び出しで設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| newX | double | x 成分。 |
| newY | double | y 成分。 |
| newZ | double | z 成分。 |

### set(int idx, double value) {#set-int-double-}
```
public void set(int idx, double value)
```


インデックスでベクトルのコンポーネントを設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| idx | int |  |
| 値 | double | 新しい値 |

### sin() {#sin--}
```
public Vector3 sin()
```


各コンポーネントの正弦を計算します

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - Calculated [Vector3](../../com.aspose.threed/vector3).
### sub(Vector3 lhs, Vector3 rhs) {#sub-com.aspose.threed.Vector3-com.aspose.threed.Vector3-}
```
public static Vector3 sub(Vector3 lhs, Vector3 rhs)
```


「-」(マイナス) の演算子オーバーロード

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| lhs | [Vector3](../../com.aspose.threed/vector3) | 左ベクトル |
| rhs | [Vector3](../../com.aspose.threed/vector3) | 右ベクトル |

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - Result vector
### toString() {#toString--}
```
public String toString()
```


現在の [Vector3](../../com.aspose.threed/vector3) を表す java.lang.String を返します。

**Returns:**
java.lang.String - 現在の [Vector3](../../com.aspose.threed/vector3) を表す java.lang.String。
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final void wait(long arg0)
```




**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |


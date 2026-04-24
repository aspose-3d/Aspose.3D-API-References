---
title: クォータニオン
second_title: Aspose.3D for Java API リファレンス
description: クォータニオンは通常、コンピュータグラフィックスで回転を実行するために使用されます。
type: docs
weight: 143
url: /ja/java/com.aspose.threed/quaternion/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.threed.Struct, java.io.Serializable
```
public final class Quaternion implements Struct<Quaternion>, Serializable
```

クォータニオンは通常、コンピュータグラフィックスで回転を実行するために使用されます。
## Constructors

| Constructor | 説明 |
| --- | --- |
| [Quaternion(double w, double x, double y, double z)](#Quaternion-double-double-double-double-) | 新しい [Quaternion](../../com.aspose.threed/quaternion) クラスのインスタンスを初期化します。 |
| [Quaternion()](#Quaternion--) |  |
## フィールド

| フィールド | 説明 |
| --- | --- |
| [IDENTITY](#IDENTITY) | 単位クォータニオンです。 |
| [w](#w) | w コンポーネント。 |
| [x](#x) | The x component. |
| [y](#y) | The y component. |
| [z](#z) | The z component. |
## Methods

| Method | 説明 |
| --- | --- |
| [add(Quaternion lhs, Quaternion rhs)](#add-com.aspose.threed.Quaternion-com.aspose.threed.Quaternion-) | Operator overloading for + |
| [clone()](#clone--) |  |
| [concat(Quaternion rhs)](#concat-com.aspose.threed.Quaternion-) | 2つのクォータニオンを連結する |
| [conjugate()](#conjugate--) | 現在のクォータニオンの共役クォータニオンを返します |
| [copyFrom(Quaternion src)](#copyFrom-com.aspose.threed.Quaternion-) |  |
| [div(Quaternion lhs, double rhs)](#div-com.aspose.threed.Quaternion-double-) | Operator overloading for / |
| [dot(Quaternion q)](#dot-com.aspose.threed.Quaternion-) | ドット積 |
| [equals(Object obj)](#equals-java.lang.Object-) | 2つのクォータニオンが等しいか確認する |
| [eulerAngles()](#eulerAngles--) | クォータニオンをオイラー角で表される回転に変換します。すべての成分はラジアンです。 |
| [fromAngleAxis(double a, Vector3 axis)](#fromAngleAxis-double-com.aspose.threed.Vector3-) | 指定された軸の周りにクォータニオンを作成し、時計回りに回転させます |
| [fromEulerAngle(Vector3 eulerAngle)](#fromEulerAngle-com.aspose.threed.Vector3-) | 指定されたオイラー角からクォータニオンを作成します |
| [fromEulerAngle(double pitch, double yaw, double roll)](#fromEulerAngle-double-double-double-) | 指定されたオイラー角からクォータニオンを作成します |
| [fromRotation(Vector3 orig, Vector3 dest)](#fromRotation-com.aspose.threed.Vector3-com.aspose.threed.Vector3-) | 元の方向から目的方向へ回転するクォータニオンを作成します |
| [getClass()](#getClass--) |  |
| [getLength()](#getLength--) | クォータニオンの長さを取得します |
| [hashCode()](#hashCode--) | クォータニオンのハッシュコードを取得します |
| [interpolate(float t, Quaternion from, Quaternion to)](#interpolate-float-com.aspose.threed.Quaternion-com.aspose.threed.Quaternion-) | このクォータニオンを、from と to の間の t に対して、与えられたクォータニオン引数間の補間値で設定します。 |
| [inverse()](#inverse--) | 現在のクォータニオンの逆クォータニオンを返します |
| [mul(Quaternion lhs, Quaternion rhs)](#mul-com.aspose.threed.Quaternion-com.aspose.threed.Quaternion-) | Operator overloading for \* |
| [mul(Quaternion q, Vector3 v)](#mul-com.aspose.threed.Quaternion-com.aspose.threed.Vector3-) | Operator overloading for \* |
| [mul(Quaternion q, Vector4 v)](#mul-com.aspose.threed.Quaternion-com.aspose.threed.Vector4-) | Operator overloading for \* |
| [mul(Quaternion lhs, double rhs)](#mul-com.aspose.threed.Quaternion-double-) | Operator overloading for \* |
| [mul(Vector3 v, Quaternion q)](#mul-com.aspose.threed.Vector3-com.aspose.threed.Quaternion-) | Operator overloading for \* |
| [normalize()](#normalize--) | クォータニオンを正規化します |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [op_eq(Quaternion lhs, Quaternion rhs)](#op-eq-com.aspose.threed.Quaternion-com.aspose.threed.Quaternion-) | クォータニオンの等価演算子 |
| [op_ne(Quaternion lhs, Quaternion rhs)](#op-ne-com.aspose.threed.Quaternion-com.aspose.threed.Quaternion-) | クォータニオンの非等価演算子 |
| [slerp(double t, Quaternion v1, Quaternion v2)](#slerp-double-com.aspose.threed.Quaternion-com.aspose.threed.Quaternion-) | 2つの値間で球面線形補間を実行します |
| [toAngleAxis(double[] angle, Vector3 axis)](#toAngleAxis-double---com.aspose.threed.Vector3-) | クォータニオンを角度と軸に分解します |
| [toMatrix()](#toMatrix--) | クォータニオンで表される回転を変換行列に変換します。 |
| [toMatrix(Vector3 translation)](#toMatrix-com.aspose.threed.Vector3-) | クォータニオンで表される回転を変換行列に変換します。 |
| [toString()](#toString--) | クォータニオンの文字列表現を取得します |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Quaternion(double w, double x, double y, double z) {#Quaternion-double-double-double-double-}
```
public Quaternion(double w, double x, double y, double z)
```


新しい [Quaternion](../../com.aspose.threed/quaternion) クラスのインスタンスを初期化します。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| w | double | クォータニオンの w 成分 |
| x | double | クォータニオンの x 成分 |
| y | double | クォータニオンの y 成分 |
| z | double | クォータニオンの z 成分 |

### Quaternion() {#Quaternion--}
```
public Quaternion()
```


### IDENTITY {#IDENTITY}
```
public static final Quaternion IDENTITY
```


単位クォータニオンです。

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

### add(Quaternion lhs, Quaternion rhs) {#add-com.aspose.threed.Quaternion-com.aspose.threed.Quaternion-}
```
public static Quaternion add(Quaternion lhs, Quaternion rhs)
```


Operator overloading for +

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| lhs | [Quaternion](../../com.aspose.threed/quaternion) | 左クォータニオン |
| rhs | [Quaternion](../../com.aspose.threed/quaternion) | 右クォータニオン |

**Returns:**
[Quaternion](../../com.aspose.threed/quaternion) - Result quaternion
### clone() {#clone--}
```
public Quaternion clone()
```


現在のインスタンスをクローンする

**Returns:**
[Quaternion](../../com.aspose.threed/quaternion)
### concat(Quaternion rhs) {#concat-com.aspose.threed.Quaternion-}
```
public Quaternion concat(Quaternion rhs)
```


2つのクォータニオンを連結する

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| rhs | [Quaternion](../../com.aspose.threed/quaternion) |  |

**Returns:**
[Quaternion](../../com.aspose.threed/quaternion)
### conjugate() {#conjugate--}
```
public Quaternion conjugate()
```


現在のクォータニオンの共役クォータニオンを返します

**Returns:**
[Quaternion](../../com.aspose.threed/quaternion) - The conjugate quaternion.
### copyFrom(Quaternion src) {#copyFrom-com.aspose.threed.Quaternion-}
```
public void copyFrom(Quaternion src)
```




**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| src | [Quaternion](../../com.aspose.threed/quaternion) |  |

### div(Quaternion lhs, double rhs) {#div-com.aspose.threed.Quaternion-double-}
```
public static Quaternion div(Quaternion lhs, double rhs)
```


Operator overloading for /

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| lhs | [Quaternion](../../com.aspose.threed/quaternion) | 左クォータニオン |
| rhs | double | 右クォータニオン |

**Returns:**
[Quaternion](../../com.aspose.threed/quaternion) - Result quaternion
### dot(Quaternion q) {#dot-com.aspose.threed.Quaternion-}
```
public double dot(Quaternion q)
```


ドット積

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| q | [Quaternion](../../com.aspose.threed/quaternion) | クォータニオン |

**Returns:**
double - ドット値
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


2つのクォータニオンが等しいか確認する

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| obj | java.lang.Object | The object to check equality. |

**Returns:**
boolean - True if all components are identically equal.
### eulerAngles() {#eulerAngles--}
```
public Vector3 eulerAngles()
```


クォータニオンをオイラー角で表される回転に変換します。すべての成分はラジアンです。

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - Result vector
### fromAngleAxis(double a, Vector3 axis) {#fromAngleAxis-double-com.aspose.threed.Vector3-}
```
public static Quaternion fromAngleAxis(double a, Vector3 axis)
```


指定された軸の周りにクォータニオンを作成し、時計回りに回転させます

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| a | double | ラジアン単位の時計回り回転 |
| axis | [Vector3](../../com.aspose.threed/vector3) | 軸 |

**Returns:**
[Quaternion](../../com.aspose.threed/quaternion) - Created quaternion
### fromEulerAngle(Vector3 eulerAngle) {#fromEulerAngle-com.aspose.threed.Vector3-}
```
public static Quaternion fromEulerAngle(Vector3 eulerAngle)
```


指定されたオイラー角からクォータニオンを作成します

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| eulerAngle | [Vector3](../../com.aspose.threed/vector3) | ラジアン単位のオイラー角 |

**Returns:**
[Quaternion](../../com.aspose.threed/quaternion) - Created quaternion
### fromEulerAngle(double pitch, double yaw, double roll) {#fromEulerAngle-double-double-double-}
```
public static Quaternion fromEulerAngle(double pitch, double yaw, double roll)
```


指定されたオイラー角からクォータニオンを作成します

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| ピッチ | double | ラジアン単位のピッチ |
| ヨー | double | ラジアン単位のヨー |
| ロール | double | ラジアン単位のロール |

**Returns:**
[Quaternion](../../com.aspose.threed/quaternion) - Created quaternion
### fromRotation(Vector3 orig, Vector3 dest) {#fromRotation-com.aspose.threed.Vector3-com.aspose.threed.Vector3-}
```
public static Quaternion fromRotation(Vector3 orig, Vector3 dest)
```


元の方向から目的方向へ回転するクォータニオンを作成します

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| orig | [Vector3](../../com.aspose.threed/vector3) | 元の方向 |
| dest | [Vector3](../../com.aspose.threed/vector3) | 目的地の方向 |

**Returns:**
[Quaternion](../../com.aspose.threed/quaternion) - Created quaternion
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


クォータニオンの長さを取得します

**Returns:**
double - クォータニオンの長さ
### hashCode() {#hashCode--}
```
public int hashCode()
```


クォータニオンのハッシュコードを取得します

**Returns:**
int - [Quaternion](../../com.aspose.threed/quaternion) のハッシュコード
### interpolate(float t, Quaternion from, Quaternion to) {#interpolate-float-com.aspose.threed.Quaternion-com.aspose.threed.Quaternion-}
```
public static Quaternion interpolate(float t, Quaternion from, Quaternion to)
```


このクォータニオンを、from と to の間の t に対して、与えられたクォータニオン引数間の補間値で設定します。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| t | float | 補間係数。 |
| from | [Quaternion](../../com.aspose.threed/quaternion) | ソースクォータニオン。 |
| to | [Quaternion](../../com.aspose.threed/quaternion) | ターゲットクォータニオン。 |

**Returns:**
[Quaternion](../../com.aspose.threed/quaternion) - The interpolated quaternion.
### inverse() {#inverse--}
```
public Quaternion inverse()
```


現在のクォータニオンの逆クォータニオンを返します

**Returns:**
[Quaternion](../../com.aspose.threed/quaternion) - Inverse quaternion.
### mul(Quaternion lhs, Quaternion rhs) {#mul-com.aspose.threed.Quaternion-com.aspose.threed.Quaternion-}
```
public static Quaternion mul(Quaternion lhs, Quaternion rhs)
```


Operator overloading for \*

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| lhs | [Quaternion](../../com.aspose.threed/quaternion) | 左クォータニオン |
| rhs | [Quaternion](../../com.aspose.threed/quaternion) | 右クォータニオン |

**Returns:**
[Quaternion](../../com.aspose.threed/quaternion) - Result quaternion
### mul(Quaternion q, Vector3 v) {#mul-com.aspose.threed.Quaternion-com.aspose.threed.Vector3-}
```
public static Vector3 mul(Quaternion q, Vector3 v)
```


Operator overloading for \*

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| q | [Quaternion](../../com.aspose.threed/quaternion) | 回転クォータニオン |
| v | [Vector3](../../com.aspose.threed/vector3) | 回転させるベクトル |

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - Rotated vector
### mul(Quaternion q, Vector4 v) {#mul-com.aspose.threed.Quaternion-com.aspose.threed.Vector4-}
```
public static Vector4 mul(Quaternion q, Vector4 v)
```


Operator overloading for \*

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| q | [Quaternion](../../com.aspose.threed/quaternion) | 回転クォータニオン |
| v | [Vector4](../../com.aspose.threed/vector4) | 回転させるベクトル |

**Returns:**
[Vector4](../../com.aspose.threed/vector4) - Rotated vector
### mul(Quaternion lhs, double rhs) {#mul-com.aspose.threed.Quaternion-double-}
```
public static Quaternion mul(Quaternion lhs, double rhs)
```


Operator overloading for \*

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| lhs | [Quaternion](../../com.aspose.threed/quaternion) | 左クォータニオン |
| rhs | double | 右クォータニオン |

**Returns:**
[Quaternion](../../com.aspose.threed/quaternion) - Result quaternion
### mul(Vector3 v, Quaternion q) {#mul-com.aspose.threed.Vector3-com.aspose.threed.Quaternion-}
```
public static Vector3 mul(Vector3 v, Quaternion q)
```


Operator overloading for \*

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| v | [Vector3](../../com.aspose.threed/vector3) | 回転クォータニオン |
| q | [Quaternion](../../com.aspose.threed/quaternion) | 回転させるベクトル |

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - Rotated vector
### normalize() {#normalize--}
```
public Quaternion normalize()
```


クォータニオンを正規化します

**Returns:**
[Quaternion](../../com.aspose.threed/quaternion) - Normalized quaternion.
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### op_eq(Quaternion lhs, Quaternion rhs) {#op-eq-com.aspose.threed.Quaternion-com.aspose.threed.Quaternion-}
```
public static boolean op_eq(Quaternion lhs, Quaternion rhs)
```


クォータニオンの等価演算子

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| lhs | [Quaternion](../../com.aspose.threed/quaternion) | Left hand side value. |
| rhs | [Quaternion](../../com.aspose.threed/quaternion) | Right hand side value. |

**Returns:**
boolean - True if all components are identically equal.
### op_ne(Quaternion lhs, Quaternion rhs) {#op-ne-com.aspose.threed.Quaternion-com.aspose.threed.Quaternion-}
```
public static boolean op_ne(Quaternion lhs, Quaternion rhs)
```


クォータニオンの非等価演算子

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| lhs | [Quaternion](../../com.aspose.threed/quaternion) | Left hand side value. |
| rhs | [Quaternion](../../com.aspose.threed/quaternion) | Right hand side value. |

**Returns:**
boolean - 2つのクォータニオンが等しくない場合は True。
### slerp(double t, Quaternion v1, Quaternion v2) {#slerp-double-com.aspose.threed.Quaternion-com.aspose.threed.Quaternion-}
```
public static Quaternion slerp(double t, Quaternion v1, Quaternion v2)
```


2つの値間で球面線形補間を実行します

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| t | double | t は 0 から 1 の間です |
| v1 | [Quaternion](../../com.aspose.threed/quaternion) | 最初の値 |
| v2 | [Quaternion](../../com.aspose.threed/quaternion) | 2番目の値 |

**Returns:**
[Quaternion](../../com.aspose.threed/quaternion)
### toAngleAxis(double[] angle, Vector3 axis) {#toAngleAxis-double---com.aspose.threed.Vector3-}
```
public void toAngleAxis(double[] angle, Vector3 axis)
```


クォータニオンを角度と軸に分解します

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| angle | double[] | 回転角度（ラジアン単位）。 |
| axis | [Vector3](../../com.aspose.threed/vector3) | 回転軸。 |

### toMatrix() {#toMatrix--}
```
public Matrix4 toMatrix()
```


クォータニオンで表される回転を変換行列に変換します。

**Returns:**
[Matrix4](../../com.aspose.threed/matrix4) - The matrix representation of current quaternion.
### toMatrix(Vector3 translation) {#toMatrix-com.aspose.threed.Vector3-}
```
public Matrix4 toMatrix(Vector3 translation)
```


クォータニオンで表される回転を変換行列に変換します。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| translation | [Vector3](../../com.aspose.threed/vector3) | 行列の平行移動部分。 |

**Returns:**
[Matrix4](../../com.aspose.threed/matrix4) - The matrix representation of current quaternion.
### toString() {#toString--}
```
public String toString()
```


クォータニオンの文字列表現を取得します

**Returns:**
java.lang.String - オブジェクト文字列
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


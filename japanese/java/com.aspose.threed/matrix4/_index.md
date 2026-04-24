---
title: Matrix4
second_title: Aspose.3D for Java API リファレンス
description: 4x4 行列の実装です。
type: docs
weight: 100
url: /ja/java/com.aspose.threed/matrix4/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.threed.Struct, java.io.Serializable
```
public final class Matrix4 implements Struct<Matrix4>, Serializable
```

4x4 行列の実装。 **Example:**

```
Matrix4 mat = Matrix4.rotateFromEuler(90, 0, 0);
      Matrix4 mat2 = Matrix4.translate(0, 10, -50);
      Matrix4 transform = Matrix4.mul(mat2, mat);
      Vector4 pos = new Vector4(10, 9, 0, 1);
      Vector4 transformed = Matrix4.mul(transform, pos);
```
## Constructors

| Constructor | 説明 |
| --- | --- |
| [Matrix4(Vector4 r0, Vector4 r1, Vector4 r2, Vector4 r3)](#Matrix4-com.aspose.threed.Vector4-com.aspose.threed.Vector4-com.aspose.threed.Vector4-com.aspose.threed.Vector4-) | 4 行から行列を構築します。 |
| [Matrix4(double m00, double m01, double m02, double m03, double m10, double m11, double m12, double m13, double m20, double m21, double m22, double m23, double m30, double m31, double m32, double m33)](#Matrix4-double-double-double-double-double-double-double-double-double-double-double-double-double-double-double-double-) | 新しい [Matrix4](../../com.aspose.threed/matrix4) 構造体のインスタンスを初期化します。 |
| [Matrix4(FMatrix4 m)](#Matrix4-com.aspose.threed.FMatrix4-) | [FMatrix4](../../com.aspose.threed/fmatrix4) インスタンスから [Matrix4](../../com.aspose.threed/matrix4) を構築します |
| [Matrix4(double[] m)](#Matrix4-double---) | 新しい [Matrix4](../../com.aspose.threed/matrix4) 構造体のインスタンスを初期化します。 |
| [Matrix4()](#Matrix4--) |  |
## フィールド

| フィールド | 説明 |
| --- | --- |
| [m00](#m00) | m00。 |
| [m01](#m01) | m01。 |
| [m02](#m02) | m02。 |
| [m03](#m03) | m03。 |
| [m10](#m10) | m10。 |
| [m11](#m11) | m11。 |
| [m12](#m12) | m12。 |
| [m13](#m13) | m13。 |
| [m20](#m20) | m20。 |
| [m21](#m21) | m21。 |
| [m22](#m22) | m22。 |
| [m23](#m23) | m23。 |
| [m30](#m30) | m30。 |
| [m31](#m31) | m31。 |
| [m32](#m32) | m32。 |
| [m33](#m33) | m33。 |
## Methods

| Method | 説明 |
| --- | --- |
| [clone()](#clone--) |  |
| [concatenate(Matrix4 m2)](#concatenate-com.aspose.threed.Matrix4-) | 2 つの行列を連結します |
| [copyFrom(Matrix4 src)](#copyFrom-com.aspose.threed.Matrix4-) |  |
| [decompose(Vector3 translation, Vector3 scaling, Quaternion rotation)](#decompose-com.aspose.threed.Vector3-com.aspose.threed.Vector3-com.aspose.threed.Quaternion-) | 変換行列を分解します。 |
| [equals(Object obj)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getDeterminant()](#getDeterminant--) | 行列の行列式を取得します。 |
| [getIdentity()](#getIdentity--) | 単位行列を取得します。 |
| [hashCode()](#hashCode--) |  |
| [inverse()](#inverse--) | このインスタンスの逆行列を取得します。 |
| [mul(Matrix4 lhs, Matrix4 rhs)](#mul-com.aspose.threed.Matrix4-com.aspose.threed.Matrix4-) | 2つの行列を掛け合わせます |
| [mul(Matrix4 lhs, Vector3 v)](#mul-com.aspose.threed.Matrix4-com.aspose.threed.Vector3-) | 行列と vector3 を掛け合わせます |
| [mul(Matrix4 lhs, Vector4 v)](#mul-com.aspose.threed.Matrix4-com.aspose.threed.Vector4-) | 行列と vector4 を掛け合わせます |
| [mul(Matrix4 lhs, double v)](#mul-com.aspose.threed.Matrix4-double-) | 行列と倍精度値を乗算します |
| [normalize()](#normalize--) | このインスタンスを正規化します。 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [rotate(Quaternion q)](#rotate-com.aspose.threed.Quaternion-) | クォータニオンから回転行列を作成します |
| [rotate(double angle, Vector3 axis)](#rotate-double-com.aspose.threed.Vector3-) | 回転角と軸で回転行列を作成します |
| [rotateFromEuler(Vector3 eul)](#rotateFromEuler-com.aspose.threed.Vector3-) | オイラー角から回転行列を作成します |
| [rotateFromEuler(double rx, double ry, double rz)](#rotateFromEuler-double-double-double-) | オイラー角から回転行列を作成します |
| [scale(Vector3 s)](#scale-com.aspose.threed.Vector3-) | x 軸、y 軸、z 軸に沿ってスケーリングする行列を作成します。 |
| [scale(double s)](#scale-double-) | x 軸、y 軸、z 軸に沿ってスケーリングする行列を作成します。 |
| [scale(double sx, double sy, double sz)](#scale-double-double-double-) | x 軸、y 軸、z 軸に沿ってスケーリングする行列を作成します。 |
| [setTRS(Vector3 translation, Vector3 rotation, Vector3 scale)](#setTRS-com.aspose.threed.Vector3-com.aspose.threed.Vector3-com.aspose.threed.Vector3-) | 平行移動/回転/スケールで行列を初期化します |
| [toArray()](#toArray--) | 行列を配列に変換します。 |
| [toString()](#toString--) | 現在の [Matrix4](../../com.aspose.threed/matrix4) を表す java.lang.String を返します。 |
| [translate(Vector3 t)](#translate-com.aspose.threed.Vector3-) | x 軸、y 軸、z 軸に沿って平行移動する行列を作成します |
| [translate(double tx, double ty, double tz)](#translate-double-double-double-) | x 軸、y 軸、z 軸に沿って平行移動する行列を作成します |
| [transpose()](#transpose--) | このインスタンスを転置します。 |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Matrix4(Vector4 r0, Vector4 r1, Vector4 r2, Vector4 r3) {#Matrix4-com.aspose.threed.Vector4-com.aspose.threed.Vector4-com.aspose.threed.Vector4-com.aspose.threed.Vector4-}
```
public Matrix4(Vector4 r0, Vector4 r1, Vector4 r2, Vector4 r3)
```


4 行から行列を構築します。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| r0 | [Vector4](../../com.aspose.threed/vector4) | R0. |
| r1 | [Vector4](../../com.aspose.threed/vector4) | R1. |
| r2 | [Vector4](../../com.aspose.threed/vector4) | R2. |
| r3 | [Vector4](../../com.aspose.threed/vector4) | R3. |

### Matrix4(double m00, double m01, double m02, double m03, double m10, double m11, double m12, double m13, double m20, double m21, double m22, double m23, double m30, double m31, double m32, double m33) {#Matrix4-double-double-double-double-double-double-double-double-double-double-double-double-double-double-double-double-}
```
public Matrix4(double m00, double m01, double m02, double m03, double m10, double m11, double m12, double m13, double m20, double m21, double m22, double m23, double m30, double m31, double m32, double m33)
```


新しい [Matrix4](../../com.aspose.threed/matrix4) 構造体のインスタンスを初期化します。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| m00 | double | M00。 |
| m01 | double | M01。 |
| m02 | double | M02。 |
| m03 | double | M03。 |
| m10 | double | M10。 |
| m11 | double | M11. |
| m12 | double | M12. |
| m13 | double | M13. |
| m20 | double | M20. |
| m21 | double | M21. |
| m22 | double | M22. |
| m23 | double | M23. |
| m30 | double | M30. |
| m31 | double | M31. |
| m32 | double | M32. |
|  | m33 | double | M33. **Example:** |

```
var mat = new Matrix4(
         1, 0, 0, 0,
         0, 1, 0, 0,
         0, 0, 1, 0,
         10, 20, 0, 1);
     var pos = new Vector3(10, 0, -1);
     var transformed = Matrix4.mul(mat, pos);
``` |

### Matrix4(FMatrix4 m) {#Matrix4-com.aspose.threed.FMatrix4-}
```
public Matrix4(FMatrix4 m)
```


[FMatrix4](../../com.aspose.threed/fmatrix4) インスタンスから [Matrix4](../../com.aspose.threed/matrix4) を構築します

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| m | [FMatrix4](../../com.aspose.threed/fmatrix4) |  |

### Matrix4(double[] m) {#Matrix4-double---}
```
public Matrix4(double[] m)
```


新しい [Matrix4](../../com.aspose.threed/matrix4) 構造体のインスタンスを初期化します。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| m | double[] | M. |

### Matrix4() {#Matrix4--}
```
public Matrix4()
```


### m00 {#m00}
```
public double m00
```


m00。

### m01 {#m01}
```
public double m01
```


m01。

### m02 {#m02}
```
public double m02
```


m02。

### m03 {#m03}
```
public double m03
```


m03。

### m10 {#m10}
```
public double m10
```


m10。

### m11 {#m11}
```
public double m11
```


m11。

### m12 {#m12}
```
public double m12
```


m12。

### m13 {#m13}
```
public double m13
```


m13。

### m20 {#m20}
```
public double m20
```


m20。

### m21 {#m21}
```
public double m21
```


m21。

### m22 {#m22}
```
public double m22
```


m22。

### m23 {#m23}
```
public double m23
```


m23。

### m30 {#m30}
```
public double m30
```


m30。

### m31 {#m31}
```
public double m31
```


m31。

### m32 {#m32}
```
public double m32
```


m32。

### m33 {#m33}
```
public double m33
```


m33。

### clone() {#clone--}
```
public Matrix4 clone()
```


現在のインスタンスをクローンする

**Returns:**
[Matrix4](../../com.aspose.threed/matrix4)
### concatenate(Matrix4 m2) {#concatenate-com.aspose.threed.Matrix4-}
```
public Matrix4 concatenate(Matrix4 m2)
```


2 つの行列を連結します

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| m2 | [Matrix4](../../com.aspose.threed/matrix4) | M2. |

**Returns:**
[Matrix4](../../com.aspose.threed/matrix4) - New matrix4 **Example:**

```
Matrix4 t = Matrix4.translate(0, 10, 9);
     Matrix4 s = Matrix4.scale(10, 10, 10);
     Matrix4 transform = t.concatenate(s);
     Vector3 pos = new Vector3(10, 0, -1);
     Vector3 transformed = Matrix4.mul(transform, pos);
```
### copyFrom(Matrix4 src) {#copyFrom-com.aspose.threed.Matrix4-}
```
public void copyFrom(Matrix4 src)
```




**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| src | [Matrix4](../../com.aspose.threed/matrix4) |  |

### decompose(Vector3 translation, Vector3 scaling, Quaternion rotation) {#decompose-com.aspose.threed.Vector3-com.aspose.threed.Vector3-com.aspose.threed.Quaternion-}
```
public boolean decompose(Vector3 translation, Vector3 scaling, Quaternion rotation)
```


変換行列を分解します。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| translation | [Vector3](../../com.aspose.threed/vector3) | The translation. |
| scaling | [Vector3](../../com.aspose.threed/vector3) | The scaling. |
| rotation | [Quaternion](../../com.aspose.threed/quaternion) | The rotation. |

**Returns:**
boolean - True if successed.
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
### getDeterminant() {#getDeterminant--}
```
public double getDeterminant()
```


行列の行列式を取得します。

**Returns:**
double - the determinant of the matrix.
### getIdentity() {#getIdentity--}
```
public static Matrix4 getIdentity()
```


単位行列を取得します。

**Returns:**
[Matrix4](../../com.aspose.threed/matrix4) - the identity matrix.
### hashCode() {#hashCode--}
```
public int hashCode()
```




**Returns:**
int
### inverse() {#inverse--}
```
public Matrix4 inverse()
```


このインスタンスの逆行列を取得します。

**Returns:**
[Matrix4](../../com.aspose.threed/matrix4) - Inverse matrix4 **Example:** The following code shows how to inverse a matrix

```
Matrix4 t = Matrix4.translate(0, 10, 9);
     Matrix4 mat = t.inverse();
     System.out.printf("Inversed Matrix: %s", mat);
```
### mul(Matrix4 lhs, Matrix4 rhs) {#mul-com.aspose.threed.Matrix4-com.aspose.threed.Matrix4-}
```
public static Matrix4 mul(Matrix4 lhs, Matrix4 rhs)
```


2つの行列を掛け合わせます

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| lhs | [Matrix4](../../com.aspose.threed/matrix4) | Lhs. |
| rhs | [Matrix4](../../com.aspose.threed/matrix4) | Rhs. |

**Returns:**
[Matrix4](../../com.aspose.threed/matrix4) - Result matrix
### mul(Matrix4 lhs, Vector3 v) {#mul-com.aspose.threed.Matrix4-com.aspose.threed.Vector3-}
```
public static Vector3 mul(Matrix4 lhs, Vector3 v)
```


行列と vector3 を掛け合わせます

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| lhs | [Matrix4](../../com.aspose.threed/matrix4) | Lhs. |
| v | [Vector3](../../com.aspose.threed/vector3) | V. |

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - Result matrix
### mul(Matrix4 lhs, Vector4 v) {#mul-com.aspose.threed.Matrix4-com.aspose.threed.Vector4-}
```
public static Vector4 mul(Matrix4 lhs, Vector4 v)
```


行列と vector4 を掛け合わせます

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| lhs | [Matrix4](../../com.aspose.threed/matrix4) | Lhs. |
| v | [Vector4](../../com.aspose.threed/vector4) | V. |

**Returns:**
[Vector4](../../com.aspose.threed/vector4) - Result matrix
### mul(Matrix4 lhs, double v) {#mul-com.aspose.threed.Matrix4-double-}
```
public static Matrix4 mul(Matrix4 lhs, double v)
```


行列と倍精度値を乗算します

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| lhs | [Matrix4](../../com.aspose.threed/matrix4) | Lhs. |
| v | double | V. |

**Returns:**
[Matrix4](../../com.aspose.threed/matrix4) - Result matrix
### normalize() {#normalize--}
```
public Matrix4 normalize()
```


このインスタンスを正規化します。

**Returns:**
[Matrix4](../../com.aspose.threed/matrix4) - Normalize matrix4
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### rotate(Quaternion q) {#rotate-com.aspose.threed.Quaternion-}
```
public static Matrix4 rotate(Quaternion q)
```


クォータニオンから回転行列を作成します

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
|  | q | [Quaternion](../../com.aspose.threed/quaternion) | Rotation quaternion **Example:** The following code shows how to create a matrix for rotate operation. |

```
var t = Matrix4.rotate(Quaternion.fromAngleAxis(Math.PI, Vector3.getUnitY()));
     var pos = new Vector3(1, 1, 10);
     System.out.printf("Transformed: %s", Matrix4.mul(t, pos));
``` |

**Returns:**
[Matrix4](../../com.aspose.threed/matrix4)
### rotate(double angle, Vector3 axis) {#rotate-double-com.aspose.threed.Vector3-}
```
public static Matrix4 rotate(double angle, Vector3 axis)
```


回転角と軸で回転行列を作成します

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| angle | double | Rotate angle in radian |
|  | axis | [Vector3](../../com.aspose.threed/vector3) | Rotation axis **Example:** The following code shows how to create a matrix for rotate operation. |

```
var t = Matrix4.rotate(Math.PI, new Vector3(0, 1, 0));
     var pos = new Vector3(1, 1, 10);
     System.out.printf("Transformed: %s", Matrix4.mul(t, pos));
``` |

**Returns:**
[Matrix4](../../com.aspose.threed/matrix4)
### rotateFromEuler(Vector3 eul) {#rotateFromEuler-com.aspose.threed.Vector3-}
```
public static Matrix4 rotateFromEuler(Vector3 eul)
```


オイラー角から回転行列を作成します

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
|  | eul | [Vector3](../../com.aspose.threed/vector3) | Rotation in radian **Example:** The following code shows how to create a matrix for rotate operation. |

```
var t = Matrix4.rotateFromEuler(new Vector3(0, Math.PI, 0));
     var pos = new Vector3(1, 1, 10);
     System.out.printf("Transformed: %s", Matrix4.mul(t, pos));
``` |

**Returns:**
[Matrix4](../../com.aspose.threed/matrix4)
### rotateFromEuler(double rx, double ry, double rz) {#rotateFromEuler-double-double-double-}
```
public static Matrix4 rotateFromEuler(double rx, double ry, double rz)
```


オイラー角から回転行列を作成します

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| rx | double | x軸の回転（ラジアン） |
| ry | double | y軸の回転（ラジアン） |
|  | rz | double | z軸の回転（ラジアン） **例:** 次のコードは回転操作の行列を作成する方法を示しています。 |

```
var t = Matrix4.rotateFromEuler(0, Math.PI, 0);
     var pos = new Vector3(1, 1, 10);
     System.out.printf("Transformed: %s", Matrix4.mul(t, pos));
``` |

**Returns:**
[Matrix4](../../com.aspose.threed/matrix4)
### scale(Vector3 s) {#scale-com.aspose.threed.Vector3-}
```
public static Matrix4 scale(Vector3 s)
```


x 軸、y 軸、z 軸に沿ってスケーリングする行列を作成します。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
|  | s | [Vector3](../../com.aspose.threed/vector3) | スケーリングファクトリはx軸、y軸、z軸に適用されます **例:** 次のコードはスケール操作の行列を作成する方法を示しています。 |

```
var t = Matrix4.scale(new Vector3(10, 10, 10));
     var pos = new Vector3(1, 1, 10);
     System.out.printf("Transformed: %s", Matrix4.mul(t, pos));
``` |

**Returns:**
[Matrix4](../../com.aspose.threed/matrix4)
### scale(double s) {#scale-double-}
```
public static Matrix4 scale(double s)
```


x 軸、y 軸、z 軸に沿ってスケーリングする行列を作成します。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
|  | s | double | スケーリングファクトリはすべての軸に適用されます **例:** 次のコードはスケール操作の行列を作成する方法を示しています。 |

```
var t = Matrix4.scale(10);
     var pos = new Vector3(1, 1, 10);
     System.out.printf("Transformed: %s", Matrix4.mul(t, pos));
``` |

**Returns:**
[Matrix4](../../com.aspose.threed/matrix4)
### scale(double sx, double sy, double sz) {#scale-double-double-double-}
```
public static Matrix4 scale(double sx, double sy, double sz)
```


x 軸、y 軸、z 軸に沿ってスケーリングする行列を作成します。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| sx | double | スケーリングファクトリはx軸に適用されます |
| sy | double | スケーリングファクトリはy軸に適用されます |
|  | sz | double | スケーリングファクトリはz軸に適用されます **例:** 次のコードはスケール操作の行列を作成する方法を示しています。 |

```
var t = Matrix4.scale(10, 20, 10);
     var pos = new Vector3(1, 1, 10);
     System.out.printf("Transformed: %s", Matrix4.mul(t, pos));
``` |

**Returns:**
[Matrix4](../../com.aspose.threed/matrix4)
### setTRS(Vector3 translation, Vector3 rotation, Vector3 scale) {#setTRS-com.aspose.threed.Vector3-com.aspose.threed.Vector3-com.aspose.threed.Vector3-}
```
public void setTRS(Vector3 translation, Vector3 rotation, Vector3 scale)
```


平行移動/回転/スケールで行列を初期化します

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| translation | [Vector3](../../com.aspose.threed/vector3) | 平行移動。 |
| rotation | [Vector3](../../com.aspose.threed/vector3) | 回転のオイラー角、フィールドは度単位です。 |
| scale | [Vector3](../../com.aspose.threed/vector3) | スケール。 |

### toArray() {#toArray--}
```
public double[] toArray()
```


行列を配列に変換します。

**Returns:**
double[] - 配列です。
### toString() {#toString--}
```
public String toString()
```


現在の [Matrix4](../../com.aspose.threed/matrix4) を表す java.lang.String を返します。

**Returns:**
java.lang.String - 現在の[Matrix4](../../com.aspose.threed/matrix4)を表すjava.lang.Stringです。
### translate(Vector3 t) {#translate-com.aspose.threed.Vector3-}
```
public static Matrix4 translate(Vector3 t)
```


x 軸、y 軸、z 軸に沿って平行移動する行列を作成します

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
|  | t | [Vector3](../../com.aspose.threed/vector3) | 平行移動オフセット **例:** 次のコードは平行移動操作の行列を作成する方法を示しています。 |

```
Matrix4 t = Matrix4.translate(new Vector3(10, 0, 0));
     Vector3 pos = new Vector3(1, 1, 10);
     System.out.printf("Transformed: %s", Matrix4.mul(t, pos));
``` |

**Returns:**
[Matrix4](../../com.aspose.threed/matrix4)
### translate(double tx, double ty, double tz) {#translate-double-double-double-}
```
public static Matrix4 translate(double tx, double ty, double tz)
```


x 軸、y 軸、z 軸に沿って平行移動する行列を作成します

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| tx | double | X座標オフセット |
| ty | double | Y座標オフセット |
|  | tz | double | Z座標オフセット **Example:** 次のコードは、平行移動操作のための行列を作成する方法を示しています。 |

```
var t = Matrix4.translate(10, 0, 0);
     var pos = new Vector3(1, 1, 10);
     System.out.printf("Transformed: %s", Matrix4.mul(t, pos));
``` |

**Returns:**
[Matrix4](../../com.aspose.threed/matrix4)
### transpose() {#transpose--}
```
public Matrix4 transpose()
```


このインスタンスを転置します。

**Returns:**
[Matrix4](../../com.aspose.threed/matrix4) - The transposed matrix. **Example:** The following code shows how to transpose a matrix

```
Matrix4 t = Matrix4.translate(0, 10, 9);
     Matrix4 mat = t.transpose();
     System.out.printf("Transposed Matrix: %s", mat);
```
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


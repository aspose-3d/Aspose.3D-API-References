---
title: Matrix4
second_title: Aspose.3D for Java API 레퍼런스
description: 4x4 행렬 구현.
type: docs
weight: 100
url: /ko/java/com.aspose.threed/matrix4/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.threed.Struct, java.io.Serializable
```
public final class Matrix4 implements Struct<Matrix4>, Serializable
```

4x4 행렬 구현. **예시:**

```
Matrix4 mat = Matrix4.rotateFromEuler(90, 0, 0);
      Matrix4 mat2 = Matrix4.translate(0, 10, -50);
      Matrix4 transform = Matrix4.mul(mat2, mat);
      Vector4 pos = new Vector4(10, 9, 0, 1);
      Vector4 transformed = Matrix4.mul(transform, pos);
```
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [Matrix4(Vector4 r0, Vector4 r1, Vector4 r2, Vector4 r3)](#Matrix4-com.aspose.threed.Vector4-com.aspose.threed.Vector4-com.aspose.threed.Vector4-com.aspose.threed.Vector4-) | Constructs matrix from 4 rows. |
| [Matrix4(double m00, double m01, double m02, double m03, double m10, double m11, double m12, double m13, double m20, double m21, double m22, double m23, double m30, double m31, double m32, double m33)](#Matrix4-double-double-double-double-double-double-double-double-double-double-double-double-double-double-double-double-) | 새로운 [Matrix4](../../com.aspose.threed/matrix4) 구조체의 인스턴스를 초기화합니다. |
| [Matrix4(FMatrix4 m)](#Matrix4-com.aspose.threed.FMatrix4-) | [FMatrix4](../../com.aspose.threed/fmatrix4) 인스턴스로부터 [Matrix4](../../com.aspose.threed/matrix4)를 구성합니다 |
| [Matrix4(double[] m)](#Matrix4-double---) | 새로운 [Matrix4](../../com.aspose.threed/matrix4) 구조체의 인스턴스를 초기화합니다. |
| [Matrix4()](#Matrix4--) |  |
## 필드

| 필드 | 설명 |
| --- | --- |
| [m00](#m00) | The m00. |
| [m01](#m01) | The m01. |
| [m02](#m02) | The m02. |
| [m03](#m03) | The m03. |
| [m10](#m10) | The m10. |
| [m11](#m11) | The m11. |
| [m12](#m12) | The m12. |
| [m13](#m13) | The m13. |
| [m20](#m20) | The m20. |
| [m21](#m21) | The m21. |
| [m22](#m22) | The m22. |
| [m23](#m23) | The m23. |
| [m30](#m30) | The m30. |
| [m31](#m31) | The m31. |
| [m32](#m32) | The m32. |
| [m33](#m33) | The m33. |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [clone()](#clone--) |  |
| [concatenate(Matrix4 m2)](#concatenate-com.aspose.threed.Matrix4-) | Concatenates the two matrices |
| [copyFrom(Matrix4 src)](#copyFrom-com.aspose.threed.Matrix4-) |  |
| [decompose(Vector3 translation, Vector3 scaling, Quaternion rotation)](#decompose-com.aspose.threed.Vector3-com.aspose.threed.Vector3-com.aspose.threed.Quaternion-) | 변환 행렬을 분해합니다. |
| [equals(Object obj)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getDeterminant()](#getDeterminant--) | 행렬의 행렬식을 가져옵니다. |
| [getIdentity()](#getIdentity--) | 단위 행렬을 가져옵니다. |
| [hashCode()](#hashCode--) |  |
| [inverse()](#inverse--) | 이 인스턴스의 역행렬을 구합니다. |
| [mul(Matrix4 lhs, Matrix4 rhs)](#mul-com.aspose.threed.Matrix4-com.aspose.threed.Matrix4-) | 두 행렬을 곱합니다 |
| [mul(Matrix4 lhs, Vector3 v)](#mul-com.aspose.threed.Matrix4-com.aspose.threed.Vector3-) | 행렬과 vector3을 곱합니다 |
| [mul(Matrix4 lhs, Vector4 v)](#mul-com.aspose.threed.Matrix4-com.aspose.threed.Vector4-) | 행렬과 vector4를 곱합니다 |
| [mul(Matrix4 lhs, double v)](#mul-com.aspose.threed.Matrix4-double-) | Multiply the matrix and double value |
| [normalize()](#normalize--) | 이 인스턴스를 정규화합니다. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [rotate(Quaternion q)](#rotate-com.aspose.threed.Quaternion-) | 쿼터니언으로부터 회전 행렬을 생성합니다 |
| [rotate(double angle, Vector3 axis)](#rotate-double-com.aspose.threed.Vector3-) | 회전 각도와 축을 사용하여 회전 행렬을 생성합니다 |
| [rotateFromEuler(Vector3 eul)](#rotateFromEuler-com.aspose.threed.Vector3-) | 오일러 각으로부터 회전 행렬을 생성합니다 |
| [rotateFromEuler(double rx, double ry, double rz)](#rotateFromEuler-double-double-double-) | 오일러 각으로부터 회전 행렬을 생성합니다 |
| [scale(Vector3 s)](#scale-com.aspose.threed.Vector3-) | x축, y축 및 z축을 따라 스케일링하는 행렬을 생성합니다. |
| [scale(double s)](#scale-double-) | x축, y축 및 z축을 따라 스케일링하는 행렬을 생성합니다. |
| [scale(double sx, double sy, double sz)](#scale-double-double-double-) | x축, y축 및 z축을 따라 스케일링하는 행렬을 생성합니다. |
| [setTRS(Vector3 translation, Vector3 rotation, Vector3 scale)](#setTRS-com.aspose.threed.Vector3-com.aspose.threed.Vector3-com.aspose.threed.Vector3-) | 행렬을 변환/회전/스케일로 초기화합니다 |
| [toArray()](#toArray--) | 행렬을 배열로 변환합니다. |
| [toString()](#toString--) | 현재 [Matrix4](../../com.aspose.threed/matrix4)를 나타내는 java.lang.String을 반환합니다. |
| [translate(Vector3 t)](#translate-com.aspose.threed.Vector3-) | x축, y축 및 z축을 따라 변환하는 행렬을 생성합니다 |
| [translate(double tx, double ty, double tz)](#translate-double-double-double-) | x축, y축 및 z축을 따라 변환하는 행렬을 생성합니다 |
| [transpose()](#transpose--) | Transposes this instance. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Matrix4(Vector4 r0, Vector4 r1, Vector4 r2, Vector4 r3) {#Matrix4-com.aspose.threed.Vector4-com.aspose.threed.Vector4-com.aspose.threed.Vector4-com.aspose.threed.Vector4-}
```
public Matrix4(Vector4 r0, Vector4 r1, Vector4 r2, Vector4 r3)
```


Constructs matrix from 4 rows.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| r0 | [Vector4](../../com.aspose.threed/vector4) | R0. |
| r1 | [Vector4](../../com.aspose.threed/vector4) | R1. |
| r2 | [Vector4](../../com.aspose.threed/vector4) | R2. |
| r3 | [Vector4](../../com.aspose.threed/vector4) | R3. |

### Matrix4(double m00, double m01, double m02, double m03, double m10, double m11, double m12, double m13, double m20, double m21, double m22, double m23, double m30, double m31, double m32, double m33) {#Matrix4-double-double-double-double-double-double-double-double-double-double-double-double-double-double-double-double-}
```
public Matrix4(double m00, double m01, double m02, double m03, double m10, double m11, double m12, double m13, double m20, double m21, double m22, double m23, double m30, double m31, double m32, double m33)
```


새로운 [Matrix4](../../com.aspose.threed/matrix4) 구조체의 인스턴스를 초기화합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| m00 | double | M00. |
| m01 | double | M01. |
| m02 | double | M02. |
| m03 | double | M03. |
| m10 | double | M10. |
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


[FMatrix4](../../com.aspose.threed/fmatrix4) 인스턴스로부터 [Matrix4](../../com.aspose.threed/matrix4)를 구성합니다

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| m | [FMatrix4](../../com.aspose.threed/fmatrix4) |  |

### Matrix4(double[] m) {#Matrix4-double---}
```
public Matrix4(double[] m)
```


새로운 [Matrix4](../../com.aspose.threed/matrix4) 구조체의 인스턴스를 초기화합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
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


The m00.

### m01 {#m01}
```
public double m01
```


The m01.

### m02 {#m02}
```
public double m02
```


The m02.

### m03 {#m03}
```
public double m03
```


The m03.

### m10 {#m10}
```
public double m10
```


The m10.

### m11 {#m11}
```
public double m11
```


The m11.

### m12 {#m12}
```
public double m12
```


The m12.

### m13 {#m13}
```
public double m13
```


The m13.

### m20 {#m20}
```
public double m20
```


The m20.

### m21 {#m21}
```
public double m21
```


The m21.

### m22 {#m22}
```
public double m22
```


The m22.

### m23 {#m23}
```
public double m23
```


The m23.

### m30 {#m30}
```
public double m30
```


The m30.

### m31 {#m31}
```
public double m31
```


The m31.

### m32 {#m32}
```
public double m32
```


The m32.

### m33 {#m33}
```
public double m33
```


The m33.

### clone() {#clone--}
```
public Matrix4 clone()
```


현재 인스턴스를 복제합니다

**Returns:**
[Matrix4](../../com.aspose.threed/matrix4)
### concatenate(Matrix4 m2) {#concatenate-com.aspose.threed.Matrix4-}
```
public Matrix4 concatenate(Matrix4 m2)
```


Concatenates the two matrices

**Parameters:**
| 매개변수 | 형식 | 설명 |
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
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| src | [Matrix4](../../com.aspose.threed/matrix4) |  |

### decompose(Vector3 translation, Vector3 scaling, Quaternion rotation) {#decompose-com.aspose.threed.Vector3-com.aspose.threed.Vector3-com.aspose.threed.Quaternion-}
```
public boolean decompose(Vector3 translation, Vector3 scaling, Quaternion rotation)
```


변환 행렬을 분해합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
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
| 매개변수 | 형식 | 설명 |
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


행렬의 행렬식을 가져옵니다.

**Returns:**
double - the determinant of the matrix.
### getIdentity() {#getIdentity--}
```
public static Matrix4 getIdentity()
```


단위 행렬을 가져옵니다.

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


이 인스턴스의 역행렬을 구합니다.

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


두 행렬을 곱합니다

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| lhs | [Matrix4](../../com.aspose.threed/matrix4) | Lhs. |
| rhs | [Matrix4](../../com.aspose.threed/matrix4) | Rhs. |

**Returns:**
[Matrix4](../../com.aspose.threed/matrix4) - Result matrix
### mul(Matrix4 lhs, Vector3 v) {#mul-com.aspose.threed.Matrix4-com.aspose.threed.Vector3-}
```
public static Vector3 mul(Matrix4 lhs, Vector3 v)
```


행렬과 vector3을 곱합니다

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| lhs | [Matrix4](../../com.aspose.threed/matrix4) | Lhs. |
| v | [Vector3](../../com.aspose.threed/vector3) | V. |

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - Result matrix
### mul(Matrix4 lhs, Vector4 v) {#mul-com.aspose.threed.Matrix4-com.aspose.threed.Vector4-}
```
public static Vector4 mul(Matrix4 lhs, Vector4 v)
```


행렬과 vector4를 곱합니다

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| lhs | [Matrix4](../../com.aspose.threed/matrix4) | Lhs. |
| v | [Vector4](../../com.aspose.threed/vector4) | V. |

**Returns:**
[Vector4](../../com.aspose.threed/vector4) - Result matrix
### mul(Matrix4 lhs, double v) {#mul-com.aspose.threed.Matrix4-double-}
```
public static Matrix4 mul(Matrix4 lhs, double v)
```


Multiply the matrix and double value

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| lhs | [Matrix4](../../com.aspose.threed/matrix4) | Lhs. |
| v | double | V. |

**Returns:**
[Matrix4](../../com.aspose.threed/matrix4) - Result matrix
### normalize() {#normalize--}
```
public Matrix4 normalize()
```


이 인스턴스를 정규화합니다.

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


쿼터니언으로부터 회전 행렬을 생성합니다

**Parameters:**
| 매개변수 | 형식 | 설명 |
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


회전 각도와 축을 사용하여 회전 행렬을 생성합니다

**Parameters:**
| 매개변수 | 형식 | 설명 |
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


오일러 각으로부터 회전 행렬을 생성합니다

**Parameters:**
| 매개변수 | 형식 | 설명 |
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


오일러 각으로부터 회전 행렬을 생성합니다

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| rx | double | x 축의 회전 (라디안) |
| ry | double | y 축의 회전 (라디안) |
|  | rz | double | z 축의 회전 (라디안) **예시:** 다음 코드는 회전 연산을 위한 행렬을 만드는 방법을 보여줍니다. |

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


x축, y축 및 z축을 따라 스케일링하는 행렬을 생성합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | s | [Vector3](../../com.aspose.threed/vector3) | 스케일링 팩터는 x축, y축 및 z축에 적용됩니다 **예시:** 다음 코드는 스케일 연산을 위한 행렬을 만드는 방법을 보여줍니다. |

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


x축, y축 및 z축을 따라 스케일링하는 행렬을 생성합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | s | double | 스케일링 팩터는 모든 축에 적용됩니다 **예시:** 다음 코드는 스케일 연산을 위한 행렬을 만드는 방법을 보여줍니다. |

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


x축, y축 및 z축을 따라 스케일링하는 행렬을 생성합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| sx | double | 스케일링 팩터는 x축에 적용됩니다. |
| sy | double | 스케일링 팩터는 y축에 적용됩니다. |
|  | sz | double | 스케일링 팩터는 z축에 적용됩니다 **예시:** 다음 코드는 스케일 연산을 위한 행렬을 만드는 방법을 보여줍니다. |

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


행렬을 변환/회전/스케일로 초기화합니다

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| translation | [Vector3](../../com.aspose.threed/vector3) | 변환. |
| rotation | [Vector3](../../com.aspose.threed/vector3) | 회전을 위한 오일러 각, 필드는 도 단위입니다. |
| scale | [Vector3](../../com.aspose.threed/vector3) | 스케일. |

### toArray() {#toArray--}
```
public double[] toArray()
```


행렬을 배열로 변환합니다.

**Returns:**
double[] - 배열.
### toString() {#toString--}
```
public String toString()
```


현재 [Matrix4](../../com.aspose.threed/matrix4)를 나타내는 java.lang.String을 반환합니다.

**Returns:**
java.lang.String - 현재 [Matrix4](../../com.aspose.threed/matrix4)를 나타내는 java.lang.String.
### translate(Vector3 t) {#translate-com.aspose.threed.Vector3-}
```
public static Matrix4 translate(Vector3 t)
```


x축, y축 및 z축을 따라 변환하는 행렬을 생성합니다

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | t | [Vector3](../../com.aspose.threed/vector3) | 오프셋 변환 **예시:** 다음 코드는 변환 연산을 위한 행렬을 만드는 방법을 보여줍니다. |

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


x축, y축 및 z축을 따라 변환하는 행렬을 생성합니다

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| tx | double | X 좌표 오프셋 |
| ty | double | Y 좌표 오프셋 |
|  | tz | double | Z 좌표 오프셋 **Example:** 다음 코드는 변환 연산을 위한 행렬을 만드는 방법을 보여줍니다. |

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


Transposes this instance.

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
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |


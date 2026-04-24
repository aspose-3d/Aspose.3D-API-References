---
title: Matrix4
second_title: Aspose.3D for Java API-referentie
description: 4x4 matriximplementatie.
type: docs
weight: 100
url: /nl/java/com.aspose.threed/matrix4/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.threed.Struct, java.io.Serializable
```
public final class Matrix4 implements Struct<Matrix4>, Serializable
```

4x4 matriximplementatie. **Voorbeeld:**

```
Matrix4 mat = Matrix4.rotateFromEuler(90, 0, 0);
      Matrix4 mat2 = Matrix4.translate(0, 10, -50);
      Matrix4 transform = Matrix4.mul(mat2, mat);
      Vector4 pos = new Vector4(10, 9, 0, 1);
      Vector4 transformed = Matrix4.mul(transform, pos);
```
## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [Matrix4(Vector4 r0, Vector4 r1, Vector4 r2, Vector4 r3)](#Matrix4-com.aspose.threed.Vector4-com.aspose.threed.Vector4-com.aspose.threed.Vector4-com.aspose.threed.Vector4-) | Constructs matrix from 4 rows. |
| [Matrix4(double m00, double m01, double m02, double m03, double m10, double m11, double m12, double m13, double m20, double m21, double m22, double m23, double m30, double m31, double m32, double m33)](#Matrix4-double-double-double-double-double-double-double-double-double-double-double-double-double-double-double-double-) | Initialiseert een nieuw exemplaar van de struct [Matrix4](../../com.aspose.threed/matrix4). |
| [Matrix4(FMatrix4 m)](#Matrix4-com.aspose.threed.FMatrix4-) | Construeer [Matrix4](../../com.aspose.threed/matrix4) vanuit een [FMatrix4](../../com.aspose.threed/fmatrix4) exemplaar |
| [Matrix4(double[] m)](#Matrix4-double---) | Initialiseert een nieuw exemplaar van de struct [Matrix4](../../com.aspose.threed/matrix4). |
| [Matrix4()](#Matrix4--) |  |
## Velden

| Veld | Beschrijving |
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
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [clone()](#clone--) |  |
| [concatenate(Matrix4 m2)](#concatenate-com.aspose.threed.Matrix4-) | Concatenates the two matrices |
| [copyFrom(Matrix4 src)](#copyFrom-com.aspose.threed.Matrix4-) |  |
| [decompose(Vector3 translation, Vector3 scaling, Quaternion rotation)](#decompose-com.aspose.threed.Vector3-com.aspose.threed.Vector3-com.aspose.threed.Quaternion-) | Decomposeer de transformatiesmatrix. |
| [equals(Object obj)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getDeterminant()](#getDeterminant--) | Haalt de determinant van de matrix op. |
| [getIdentity()](#getIdentity--) | Haalt de identiteitsmatrix op. |
| [hashCode()](#hashCode--) |  |
| [inverse()](#inverse--) | Inverseert dit exemplaar. |
| [mul(Matrix4 lhs, Matrix4 rhs)](#mul-com.aspose.threed.Matrix4-com.aspose.threed.Matrix4-) | Vermenigvuldig de twee matrices |
| [mul(Matrix4 lhs, Vector3 v)](#mul-com.aspose.threed.Matrix4-com.aspose.threed.Vector3-) | Vermenigvuldig de matrix en vector3 |
| [mul(Matrix4 lhs, Vector4 v)](#mul-com.aspose.threed.Matrix4-com.aspose.threed.Vector4-) | Vermenigvuldig de matrix en vector4 |
| [mul(Matrix4 lhs, double v)](#mul-com.aspose.threed.Matrix4-double-) | Multiply the matrix and double value |
| [normalize()](#normalize--) | Normaliseert deze instantie. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [rotate(Quaternion q)](#rotate-com.aspose.threed.Quaternion-) | Maak een rotatiematrix van een quaternion |
| [rotate(double angle, Vector3 axis)](#rotate-double-com.aspose.threed.Vector3-) | Maak een rotatiematrix op basis van rotatiehoek en as |
| [rotateFromEuler(Vector3 eul)](#rotateFromEuler-com.aspose.threed.Vector3-) | Maak een rotatiematrix van een Euler-hoek |
| [rotateFromEuler(double rx, double ry, double rz)](#rotateFromEuler-double-double-double-) | Maak een rotatiematrix van een Euler-hoek |
| [scale(Vector3 s)](#scale-com.aspose.threed.Vector3-) | Creëert een matrix die schaalt langs de x-as, de y-as en de z-as. |
| [scale(double s)](#scale-double-) | Creëert een matrix die schaalt langs de x-as, de y-as en de z-as. |
| [scale(double sx, double sy, double sz)](#scale-double-double-double-) | Creëert een matrix die schaalt langs de x-as, de y-as en de z-as. |
| [setTRS(Vector3 translation, Vector3 rotation, Vector3 scale)](#setTRS-com.aspose.threed.Vector3-com.aspose.threed.Vector3-com.aspose.threed.Vector3-) | Initialiseert de matrix met translatie/rotatie/schaal |
| [toArray()](#toArray--) | Converteert de matrix naar een array. |
| [toString()](#toString--) | Retourneert een java.lang.String die de huidige [Matrix4](../../com.aspose.threed/matrix4) vertegenwoordigt. |
| [translate(Vector3 t)](#translate-com.aspose.threed.Vector3-) | Creëert een matrix die translateert langs de x-as, de y-as en de z-as |
| [translate(double tx, double ty, double tz)](#translate-double-double-double-) | Creëert een matrix die translateert langs de x-as, de y-as en de z-as |
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
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| r0 | [Vector4](../../com.aspose.threed/vector4) | R0. |
| r1 | [Vector4](../../com.aspose.threed/vector4) | R1. |
| r2 | [Vector4](../../com.aspose.threed/vector4) | R2. |
| r3 | [Vector4](../../com.aspose.threed/vector4) | R3. |

### Matrix4(double m00, double m01, double m02, double m03, double m10, double m11, double m12, double m13, double m20, double m21, double m22, double m23, double m30, double m31, double m32, double m33) {#Matrix4-double-double-double-double-double-double-double-double-double-double-double-double-double-double-double-double-}
```
public Matrix4(double m00, double m01, double m02, double m03, double m10, double m11, double m12, double m13, double m20, double m21, double m22, double m23, double m30, double m31, double m32, double m33)
```


Initialiseert een nieuw exemplaar van de struct [Matrix4](../../com.aspose.threed/matrix4).

**Parameters:**
| Parameter | Type | Beschrijving |
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


Construeer [Matrix4](../../com.aspose.threed/matrix4) vanuit een [FMatrix4](../../com.aspose.threed/fmatrix4) exemplaar

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| m | [FMatrix4](../../com.aspose.threed/fmatrix4) |  |

### Matrix4(double[] m) {#Matrix4-double---}
```
public Matrix4(double[] m)
```


Initialiseert een nieuw exemplaar van de struct [Matrix4](../../com.aspose.threed/matrix4).

**Parameters:**
| Parameter | Type | Beschrijving |
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


Kloon huidige instantie

**Returns:**
[Matrix4](../../com.aspose.threed/matrix4)
### concatenate(Matrix4 m2) {#concatenate-com.aspose.threed.Matrix4-}
```
public Matrix4 concatenate(Matrix4 m2)
```


Concatenates the two matrices

**Parameters:**
| Parameter | Type | Beschrijving |
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
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| src | [Matrix4](../../com.aspose.threed/matrix4) |  |

### decompose(Vector3 translation, Vector3 scaling, Quaternion rotation) {#decompose-com.aspose.threed.Vector3-com.aspose.threed.Vector3-com.aspose.threed.Quaternion-}
```
public boolean decompose(Vector3 translation, Vector3 scaling, Quaternion rotation)
```


Decomposeer de transformatiesmatrix.

**Parameters:**
| Parameter | Type | Beschrijving |
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
| Parameter | Type | Beschrijving |
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


Haalt de determinant van de matrix op.

**Returns:**
double - the determinant of the matrix.
### getIdentity() {#getIdentity--}
```
public static Matrix4 getIdentity()
```


Haalt de identiteitsmatrix op.

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


Inverseert dit exemplaar.

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


Vermenigvuldig de twee matrices

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| lhs | [Matrix4](../../com.aspose.threed/matrix4) | Lhs. |
| rhs | [Matrix4](../../com.aspose.threed/matrix4) | Rhs. |

**Returns:**
[Matrix4](../../com.aspose.threed/matrix4) - Result matrix
### mul(Matrix4 lhs, Vector3 v) {#mul-com.aspose.threed.Matrix4-com.aspose.threed.Vector3-}
```
public static Vector3 mul(Matrix4 lhs, Vector3 v)
```


Vermenigvuldig de matrix en vector3

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| lhs | [Matrix4](../../com.aspose.threed/matrix4) | Lhs. |
| v | [Vector3](../../com.aspose.threed/vector3) | V. |

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - Result matrix
### mul(Matrix4 lhs, Vector4 v) {#mul-com.aspose.threed.Matrix4-com.aspose.threed.Vector4-}
```
public static Vector4 mul(Matrix4 lhs, Vector4 v)
```


Vermenigvuldig de matrix en vector4

**Parameters:**
| Parameter | Type | Beschrijving |
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
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| lhs | [Matrix4](../../com.aspose.threed/matrix4) | Lhs. |
| v | double | V. |

**Returns:**
[Matrix4](../../com.aspose.threed/matrix4) - Result matrix
### normalize() {#normalize--}
```
public Matrix4 normalize()
```


Normaliseert deze instantie.

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


Maak een rotatiematrix van een quaternion

**Parameters:**
| Parameter | Type | Beschrijving |
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


Maak een rotatiematrix op basis van rotatiehoek en as

**Parameters:**
| Parameter | Type | Beschrijving |
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


Maak een rotatiematrix van een Euler-hoek

**Parameters:**
| Parameter | Type | Beschrijving |
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


Maak een rotatiematrix van een Euler-hoek

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| rx | double | Rotatie in de x-as in radialen |
| ry | double | Rotatie in de y-as in radialen |
|  | rz | double | Rotatie in de z-as in radialen **Example:** De volgende code laat zien hoe je een matrix maakt voor rotatiebewerking. |

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


Creëert een matrix die schaalt langs de x-as, de y-as en de z-as.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | s | [Vector3](../../com.aspose.threed/vector3) | Schaalfactoren gelden voor de x-as, de y-as en de z-as **Example:** De volgende code laat zien hoe je een matrix maakt voor schaalbewerking. |

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


Creëert een matrix die schaalt langs de x-as, de y-as en de z-as.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | s | double | Schaalfactoren gelden voor alle assen **Example:** De volgende code laat zien hoe je een matrix maakt voor schaalbewerking. |

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


Creëert een matrix die schaalt langs de x-as, de y-as en de z-as.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| sx | double | Schaalfactoren gelden voor de x-as |
| sy | double | Schaalfactoren gelden voor de y-as |
|  | sz | double | Schaalfactoren gelden voor de z-as **Example:** De volgende code laat zien hoe je een matrix maakt voor schaalbewerking. |

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


Initialiseert de matrix met translatie/rotatie/schaal

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| translation | [Vector3](../../com.aspose.threed/vector3) | Vertaling. |
| rotation | [Vector3](../../com.aspose.threed/vector3) | Eulerhoeken voor rotatie, velden zijn in graden. |
| scale | [Vector3](../../com.aspose.threed/vector3) | Schaal. |

### toArray() {#toArray--}
```
public double[] toArray()
```


Converteert de matrix naar een array.

**Returns:**
double[] - De array.
### toString() {#toString--}
```
public String toString()
```


Retourneert een java.lang.String die de huidige [Matrix4](../../com.aspose.threed/matrix4) vertegenwoordigt.

**Returns:**
java.lang.String - Een java.lang.String die de huidige [Matrix4](../../com.aspose.threed/matrix4) vertegenwoordigt.
### translate(Vector3 t) {#translate-com.aspose.threed.Vector3-}
```
public static Matrix4 translate(Vector3 t)
```


Creëert een matrix die translateert langs de x-as, de y-as en de z-as

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | t | [Vector3](../../com.aspose.threed/vector3) | Translatieverschuiving **Example:** De volgende code laat zien hoe je een matrix maakt voor translatiebewerking. |

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


Creëert een matrix die translateert langs de x-as, de y-as en de z-as

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| tx | double | X-coördinaatverschuiving |
| ty | double | Y-coördinaatverschuiving |
|  | tz | double | Z-coördinaat offset **Example:** De volgende code toont hoe je een matrix voor een vertaaloperatie maakt. |

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
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |


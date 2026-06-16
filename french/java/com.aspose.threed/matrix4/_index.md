---
title: "Matrix4"
second_title: "Référence d'API Aspose.3D pour Java"
description: "Implémentation de matrice 4x4."
type: docs
weight: 100
url: /fr/java/com.aspose.threed/matrix4/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.threed.Struct, java.io.Serializable
```
public final class Matrix4 implements Struct<Matrix4>, Serializable
```

Implémentation d'une matrice 4x4. **Exemple:**

```
Matrix4 mat = Matrix4.rotateFromEuler(90, 0, 0);
      Matrix4 mat2 = Matrix4.translate(0, 10, -50);
      Matrix4 transform = Matrix4.mul(mat2, mat);
      Vector4 pos = new Vector4(10, 9, 0, 1);
      Vector4 transformed = Matrix4.mul(transform, pos);
```
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [Matrix4(Vector4 r0, Vector4 r1, Vector4 r2, Vector4 r3)](#Matrix4-com.aspose.threed.Vector4-com.aspose.threed.Vector4-com.aspose.threed.Vector4-com.aspose.threed.Vector4-) | Construit la matrice à partir de 4 lignes. |
| [Matrix4(double m00, double m01, double m02, double m03, double m10, double m11, double m12, double m13, double m20, double m21, double m22, double m23, double m30, double m31, double m32, double m33)](#Matrix4-double-double-double-double-double-double-double-double-double-double-double-double-double-double-double-double-) | Initialise une nouvelle instance de la structure [Matrix4](../../com.aspose.threed/matrix4). |
| [Matrix4(FMatrix4 m)](#Matrix4-com.aspose.threed.FMatrix4-) | Construit [Matrix4](../../com.aspose.threed/matrix4) à partir d'une instance [FMatrix4](../../com.aspose.threed/fmatrix4). |
| [Matrix4(double[] m)](#Matrix4-double---) | Initialise une nouvelle instance de la structure [Matrix4](../../com.aspose.threed/matrix4). |
| [Matrix4()](#Matrix4--) |  |
## Champs

| Champ | Description |
| --- | --- |
| [m00](#m00) | Le m00. |
| [m01](#m01) | Le m01. |
| [m02](#m02) | Le m02. |
| [m03](#m03) | Le m03. |
| [m10](#m10) | Le m10. |
| [m11](#m11) | Le m11. |
| [m12](#m12) | Le m12. |
| [m13](#m13) | Le m13. |
| [m20](#m20) | Le m20. |
| [m21](#m21) | Le m21. |
| [m22](#m22) | Le m22. |
| [m23](#m23) | Le m23. |
| [m30](#m30) | Le m30. |
| [m31](#m31) | Le m31. |
| [m32](#m32) | Le m32. |
| [m33](#m33) | Le m33. |
## Méthodes

| Méthode | Description |
| --- | --- |
| [clone()](#clone--) |  |
| [concatenate(Matrix4 m2)](#concatenate-com.aspose.threed.Matrix4-) | Concatène les deux matrices |
| [copyFrom(Matrix4 src)](#copyFrom-com.aspose.threed.Matrix4-) |  |
| [decompose(Vector3 translation, Vector3 scaling, Quaternion rotation)](#decompose-com.aspose.threed.Vector3-com.aspose.threed.Vector3-com.aspose.threed.Quaternion-) | Décompose la matrice de transformation. |
| [equals(Object obj)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getDeterminant()](#getDeterminant--) | Obtient le déterminant de la matrice. |
| [getIdentity()](#getIdentity--) | Obtient la matrice identité. |
| [hashCode()](#hashCode--) |  |
| [inverse()](#inverse--) | Inverse cette instance. |
| [mul(Matrix4 lhs, Matrix4 rhs)](#mul-com.aspose.threed.Matrix4-com.aspose.threed.Matrix4-) | Multiplie les deux matrices |
| [mul(Matrix4 lhs, Vector3 v)](#mul-com.aspose.threed.Matrix4-com.aspose.threed.Vector3-) | Multiplie la matrice et le vecteur3 |
| [mul(Matrix4 lhs, Vector4 v)](#mul-com.aspose.threed.Matrix4-com.aspose.threed.Vector4-) | Multiplie la matrice et le vecteur4 |
| [mul(Matrix4 lhs, double v)](#mul-com.aspose.threed.Matrix4-double-) | Multiplie la matrice par une valeur double |
| [normalize()](#normalize--) | Normalise cette instance. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [rotate(Quaternion q)](#rotate-com.aspose.threed.Quaternion-) | Crée une matrice de rotation à partir d'un quaternion |
| [rotate(double angle, Vector3 axis)](#rotate-double-com.aspose.threed.Vector3-) | Crée une matrice de rotation à partir d'un angle de rotation et d'un axe |
| [rotateFromEuler(Vector3 eul)](#rotateFromEuler-com.aspose.threed.Vector3-) | Crée une matrice de rotation à partir d'un angle d'Euler |
| [rotateFromEuler(double rx, double ry, double rz)](#rotateFromEuler-double-double-double-) | Crée une matrice de rotation à partir d'un angle d'Euler |
| [scale(Vector3 s)](#scale-com.aspose.threed.Vector3-) | Crée une matrice qui met à l'échelle le long des axes x, y et z. |
| [scale(double s)](#scale-double-) | Crée une matrice qui met à l'échelle le long des axes x, y et z. |
| [scale(double sx, double sy, double sz)](#scale-double-double-double-) | Crée une matrice qui met à l'échelle le long des axes x, y et z. |
| [setTRS(Vector3 translation, Vector3 rotation, Vector3 scale)](#setTRS-com.aspose.threed.Vector3-com.aspose.threed.Vector3-com.aspose.threed.Vector3-) | Initialise la matrice avec translation/rotation/échelle |
| [toArray()](#toArray--) | Convertit la matrice en tableau. |
| [toString()](#toString--) | Renvoie une java.lang.String qui représente le [Matrix4](../../com.aspose.threed/matrix4) actuel. |
| [translate(Vector3 t)](#translate-com.aspose.threed.Vector3-) | Crée une matrice qui translate le long des axes x, y et z |
| [translate(double tx, double ty, double tz)](#translate-double-double-double-) | Crée une matrice qui translate le long des axes x, y et z |
| [transpose()](#transpose--) | Transpose cette instance. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Matrix4(Vector4 r0, Vector4 r1, Vector4 r2, Vector4 r3) {#Matrix4-com.aspose.threed.Vector4-com.aspose.threed.Vector4-com.aspose.threed.Vector4-com.aspose.threed.Vector4-}
```
public Matrix4(Vector4 r0, Vector4 r1, Vector4 r2, Vector4 r3)
```


Construit la matrice à partir de 4 lignes.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| r0 | [Vector4](../../com.aspose.threed/vector4) | R0. |
| r1 | [Vector4](../../com.aspose.threed/vector4) | R1. |
| r2 | [Vector4](../../com.aspose.threed/vector4) | R2. |
| r3 | [Vector4](../../com.aspose.threed/vector4) | R3. |

### Matrix4(double m00, double m01, double m02, double m03, double m10, double m11, double m12, double m13, double m20, double m21, double m22, double m23, double m30, double m31, double m32, double m33) {#Matrix4-double-double-double-double-double-double-double-double-double-double-double-double-double-double-double-double-}
```
public Matrix4(double m00, double m01, double m02, double m03, double m10, double m11, double m12, double m13, double m20, double m21, double m22, double m23, double m30, double m31, double m32, double m33)
```


Initialise une nouvelle instance de la structure [Matrix4](../../com.aspose.threed/matrix4).

**Parameters:**
| Paramètre | Type | Description |
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
|  | m33 | double | M33. **Exemple:** |

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


Construit [Matrix4](../../com.aspose.threed/matrix4) à partir d'une instance [FMatrix4](../../com.aspose.threed/fmatrix4).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| m | [FMatrix4](../../com.aspose.threed/fmatrix4) |  |

### Matrix4(double[] m) {#Matrix4-double---}
```
public Matrix4(double[] m)
```


Initialise une nouvelle instance de la structure [Matrix4](../../com.aspose.threed/matrix4).

**Parameters:**
| Paramètre | Type | Description |
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


Le m00.

### m01 {#m01}
```
public double m01
```


Le m01.

### m02 {#m02}
```
public double m02
```


Le m02.

### m03 {#m03}
```
public double m03
```


Le m03.

### m10 {#m10}
```
public double m10
```


Le m10.

### m11 {#m11}
```
public double m11
```


Le m11.

### m12 {#m12}
```
public double m12
```


Le m12.

### m13 {#m13}
```
public double m13
```


Le m13.

### m20 {#m20}
```
public double m20
```


Le m20.

### m21 {#m21}
```
public double m21
```


Le m21.

### m22 {#m22}
```
public double m22
```


Le m22.

### m23 {#m23}
```
public double m23
```


Le m23.

### m30 {#m30}
```
public double m30
```


Le m30.

### m31 {#m31}
```
public double m31
```


Le m31.

### m32 {#m32}
```
public double m32
```


Le m32.

### m33 {#m33}
```
public double m33
```


Le m33.

### clone() {#clone--}
```
public Matrix4 clone()
```


Cloner l'instance actuelle

**Returns:**
[Matrix4](../../com.aspose.threed/matrix4)
### concatenate(Matrix4 m2) {#concatenate-com.aspose.threed.Matrix4-}
```
public Matrix4 concatenate(Matrix4 m2)
```


Concatène les deux matrices

**Parameters:**
| Paramètre | Type | Description |
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
| Paramètre | Type | Description |
| --- | --- | --- |
| src | [Matrix4](../../com.aspose.threed/matrix4) |  |

### decompose(Vector3 translation, Vector3 scaling, Quaternion rotation) {#decompose-com.aspose.threed.Vector3-com.aspose.threed.Vector3-com.aspose.threed.Quaternion-}
```
public boolean decompose(Vector3 translation, Vector3 scaling, Quaternion rotation)
```


Décompose la matrice de transformation.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| translation | [Vector3](../../com.aspose.threed/vector3) | La translation. |
| scaling | [Vector3](../../com.aspose.threed/vector3) | Le redimensionnement. |
| rotation | [Quaternion](../../com.aspose.threed/quaternion) | La rotation. |

**Returns:**
booléen - Vrai si réussi.
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```




**Parameters:**
| Paramètre | Type | Description |
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


Obtient le déterminant de la matrice.

**Returns:**
double - le déterminant de la matrice.
### getIdentity() {#getIdentity--}
```
public static Matrix4 getIdentity()
```


Obtient la matrice identité.

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


Inverse cette instance.

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


Multiplie les deux matrices

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| lhs | [Matrix4](../../com.aspose.threed/matrix4) | Lhs. |
| rhs | [Matrix4](../../com.aspose.threed/matrix4) | Rhs. |

**Returns:**
[Matrix4](../../com.aspose.threed/matrix4) - Result matrix
### mul(Matrix4 lhs, Vector3 v) {#mul-com.aspose.threed.Matrix4-com.aspose.threed.Vector3-}
```
public static Vector3 mul(Matrix4 lhs, Vector3 v)
```


Multiplie la matrice et le vecteur3

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| lhs | [Matrix4](../../com.aspose.threed/matrix4) | Lhs. |
| v | [Vector3](../../com.aspose.threed/vector3) | V. |

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - Result matrix
### mul(Matrix4 lhs, Vector4 v) {#mul-com.aspose.threed.Matrix4-com.aspose.threed.Vector4-}
```
public static Vector4 mul(Matrix4 lhs, Vector4 v)
```


Multiplie la matrice et le vecteur4

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| lhs | [Matrix4](../../com.aspose.threed/matrix4) | Lhs. |
| v | [Vector4](../../com.aspose.threed/vector4) | V. |

**Returns:**
[Vector4](../../com.aspose.threed/vector4) - Result matrix
### mul(Matrix4 lhs, double v) {#mul-com.aspose.threed.Matrix4-double-}
```
public static Matrix4 mul(Matrix4 lhs, double v)
```


Multiplie la matrice par une valeur double

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| lhs | [Matrix4](../../com.aspose.threed/matrix4) | Lhs. |
| v | double | V. |

**Returns:**
[Matrix4](../../com.aspose.threed/matrix4) - Result matrix
### normalize() {#normalize--}
```
public Matrix4 normalize()
```


Normalise cette instance.

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


Crée une matrice de rotation à partir d'un quaternion

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | q | [Quaternion](../../com.aspose.threed/quaternion) | Quaternion de rotation **Exemple:** Le code suivant montre comment créer une matrice pour l'opération de rotation. |

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


Crée une matrice de rotation à partir d'un angle de rotation et d'un axe

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| angle | double | Angle de rotation en radians |
|  | axis | [Vector3](../../com.aspose.threed/vector3) | Axe de rotation **Exemple:** Le code suivant montre comment créer une matrice pour l'opération de rotation. |

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


Crée une matrice de rotation à partir d'un angle d'Euler

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | eul | [Vector3](../../com.aspose.threed/vector3) | Rotation en radians **Exemple:** Le code suivant montre comment créer une matrice pour l'opération de rotation. |

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


Crée une matrice de rotation à partir d'un angle d'Euler

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| rx | double | Rotation autour de l'axe x en radian |
| ry | double | Rotation autour de l'axe y en radian |
|  | rz | double | Rotation autour de l'axe z en radian **Exemple:** Le code suivant montre comment créer une matrice pour l'opération de rotation. |

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


Crée une matrice qui met à l'échelle le long des axes x, y et z.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | s | [Vector3](../../com.aspose.threed/vector3) | Les facteurs d'échelle s'appliquent aux axes x, y et z **Exemple:** Le code suivant montre comment créer une matrice pour l'opération de mise à l'échelle. |

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


Crée une matrice qui met à l'échelle le long des axes x, y et z.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | s | double | Les facteurs d'échelle s'appliquent à tous les axes **Exemple:** Le code suivant montre comment créer une matrice pour l'opération de mise à l'échelle. |

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


Crée une matrice qui met à l'échelle le long des axes x, y et z.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| sx | double | Les facteurs d'échelle s'appliquent à l'axe x |
| sy | double | Les facteurs d'échelle s'appliquent à l'axe y |
|  | sz | double | Les facteurs d'échelle s'appliquent à l'axe z **Exemple:** Le code suivant montre comment créer une matrice pour l'opération de mise à l'échelle. |

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


Initialise la matrice avec translation/rotation/échelle

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| translation | [Vector3](../../com.aspose.threed/vector3) | Traduction. |
| rotation | [Vector3](../../com.aspose.threed/vector3) | Angles d'Euler pour la rotation, les champs sont en degrés. |
| scale | [Vector3](../../com.aspose.threed/vector3) | Échelle. |

### toArray() {#toArray--}
```
public double[] toArray()
```


Convertit la matrice en tableau.

**Returns:**
double[] - Le tableau.
### toString() {#toString--}
```
public String toString()
```


Renvoie une java.lang.String qui représente le [Matrix4](../../com.aspose.threed/matrix4) actuel.

**Returns:**
java.lang.String - Un java.lang.String qui représente le [Matrix4](../../com.aspose.threed/matrix4) actuel.
### translate(Vector3 t) {#translate-com.aspose.threed.Vector3-}
```
public static Matrix4 translate(Vector3 t)
```


Crée une matrice qui translate le long des axes x, y et z

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | t | [Vector3](../../com.aspose.threed/vector3) | Décalage de translation **Exemple:** Le code suivant montre comment créer une matrice pour l'opération de translation. |

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


Crée une matrice qui translate le long des axes x, y et z

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| tx | double | Décalage de la coordonnée X |
| ty | double | Décalage de la coordonnée Y |
|  | tz | double | Décalage de la coordonnée Z **Example:** Le code suivant montre comment créer une matrice pour l'opération de translation. |

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


Transpose cette instance.

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
| Paramètre | Type | Description |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |


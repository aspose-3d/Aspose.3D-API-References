---
title: Quaternion
second_title: Referensi API Aspose.3D untuk Java
description: Quaternion biasanya digunakan untuk melakukan rotasi dalam grafika komputer.
type: docs
weight: 143
url: /id/java/com.aspose.threed/quaternion/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.threed.Struct, java.io.Serializable
```
public final class Quaternion implements Struct<Quaternion>, Serializable
```

Quaternion biasanya digunakan untuk melakukan rotasi dalam grafika komputer.
## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [Quaternion(double w, double x, double y, double z)](#Quaternion-double-double-double-double-) | Menginisialisasi instance baru dari kelas [Quaternion](../../com.aspose.threed/quaternion). |
| [Quaternion()](#Quaternion--) |  |
## Bidang

| Bidang | Deskripsi |
| --- | --- |
| [IDENTITY](#IDENTITY) | Quaternion Identitas. |
| [w](#w) | Komponen w. |
| [x](#x) | Komponen x. |
| [y](#y) | Komponen y. |
| [z](#z) | Komponen z. |
## Metode

| Metode | Deskripsi |
| --- | --- |
| [add(Quaternion lhs, Quaternion rhs)](#add-com.aspose.threed.Quaternion-com.aspose.threed.Quaternion-) | Overloading operator untuk +. |
| [clone()](#clone--) |  |
| [concat(Quaternion rhs)](#concat-com.aspose.threed.Quaternion-) | Menggabungkan dua quaternion |
| [conjugate()](#conjugate--) | Mengembalikan quaternion konjugat dari quaternion saat ini |
| [copyFrom(Quaternion src)](#copyFrom-com.aspose.threed.Quaternion-) |  |
| [div(Quaternion lhs, double rhs)](#div-com.aspose.threed.Quaternion-double-) | Overloading operator untuk /. |
| [dot(Quaternion q)](#dot-com.aspose.threed.Quaternion-) | Produk titik |
| [equals(Object obj)](#equals-java.lang.Object-) | Periksa apakah dua quaternion sama |
| [eulerAngles()](#eulerAngles--) | Mengonversi quaternion menjadi rotasi yang direpresentasikan oleh sudut Euler. Semua komponen dalam radian. |
| [fromAngleAxis(double a, Vector3 axis)](#fromAngleAxis-double-com.aspose.threed.Vector3-) | Membuat quaternion di sekitar sumbu yang diberikan dan memutar searah jarum jam |
| [fromEulerAngle(Vector3 eulerAngle)](#fromEulerAngle-com.aspose.threed.Vector3-) | Membuat quaternion dari sudut Euler yang diberikan |
| [fromEulerAngle(double pitch, double yaw, double roll)](#fromEulerAngle-double-double-double-) | Membuat quaternion dari sudut Euler yang diberikan |
| [fromRotation(Vector3 orig, Vector3 dest)](#fromRotation-com.aspose.threed.Vector3-com.aspose.threed.Vector3-) | Membuat quaternion yang memutar dari arah asli ke arah tujuan |
| [getClass()](#getClass--) |  |
| [getLength()](#getLength--) | Mendapatkan panjang quaternion |
| [hashCode()](#hashCode--) | Mendapatkan kode hash dari Quaternion |
| [interpolate(float t, Quaternion from, Quaternion to)](#interpolate-float-com.aspose.threed.Quaternion-com.aspose.threed.Quaternion-) | Mengisi quaternion ini dengan nilai interpolasi antara argumen quaternion yang diberikan untuk t antara dari dan ke. |
| [inverse()](#inverse--) | Mengembalikan quaternion invers dari quaternion saat ini |
| [mul(Quaternion lhs, Quaternion rhs)](#mul-com.aspose.threed.Quaternion-com.aspose.threed.Quaternion-) | Overloading operator untuk \*. |
| [mul(Quaternion q, Vector3 v)](#mul-com.aspose.threed.Quaternion-com.aspose.threed.Vector3-) | Overloading operator untuk \*. |
| [mul(Quaternion q, Vector4 v)](#mul-com.aspose.threed.Quaternion-com.aspose.threed.Vector4-) | Overloading operator untuk \*. |
| [mul(Quaternion lhs, double rhs)](#mul-com.aspose.threed.Quaternion-double-) | Overloading operator untuk \*. |
| [mul(Vector3 v, Quaternion q)](#mul-com.aspose.threed.Vector3-com.aspose.threed.Quaternion-) | Overloading operator untuk \*. |
| [normalize()](#normalize--) | Normalisasi quaternion |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [op_eq(Quaternion lhs, Quaternion rhs)](#op-eq-com.aspose.threed.Quaternion-com.aspose.threed.Quaternion-) | Operator sama untuk quaternion |
| [op_ne(Quaternion lhs, Quaternion rhs)](#op-ne-com.aspose.threed.Quaternion-com.aspose.threed.Quaternion-) | Operator tidak sama untuk quaternion |
| [slerp(double t, Quaternion v1, Quaternion v2)](#slerp-double-com.aspose.threed.Quaternion-com.aspose.threed.Quaternion-) | Melakukan interpolasi linier sferis antara dua nilai |
| [toAngleAxis(double[] angle, Vector3 axis)](#toAngleAxis-double---com.aspose.threed.Vector3-) | Mendecompose quaternion menjadi sudut dan sumbu |
| [toMatrix()](#toMatrix--) | Mengonversi rotasi yang dipresentasikan oleh quaternion menjadi matriks transformasi. |
| [toMatrix(Vector3 translation)](#toMatrix-com.aspose.threed.Vector3-) | Mengonversi rotasi yang dipresentasikan oleh quaternion menjadi matriks transformasi. |
| [toString()](#toString--) | Mendapatkan representasi quaternion dalam string |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Quaternion(double w, double x, double y, double z) {#Quaternion-double-double-double-double-}
```
public Quaternion(double w, double x, double y, double z)
```


Menginisialisasi instance baru dari kelas [Quaternion](../../com.aspose.threed/quaternion).

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| w | double | komponen w dari quaternion |
| x | double | komponen x dari quaternion |
| y | double | komponen y dari quaternion |
| z | double | komponen z dari quaternion |

### Quaternion() {#Quaternion--}
```
public Quaternion()
```


### IDENTITY {#IDENTITY}
```
public static final Quaternion IDENTITY
```


Quaternion Identitas.

### w {#w}
```
public double w
```


Komponen w.

### x {#x}
```
public double x
```


Komponen x.

### y {#y}
```
public double y
```


Komponen y.

### z {#z}
```
public double z
```


Komponen z.

### add(Quaternion lhs, Quaternion rhs) {#add-com.aspose.threed.Quaternion-com.aspose.threed.Quaternion-}
```
public static Quaternion add(Quaternion lhs, Quaternion rhs)
```


Overloading operator untuk +.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| lhs | [Quaternion](../../com.aspose.threed/quaternion) | Quaternion kiri |
| rhs | [Quaternion](../../com.aspose.threed/quaternion) | Quaternion kanan |

**Returns:**
[Quaternion](../../com.aspose.threed/quaternion) - Result quaternion
### clone() {#clone--}
```
public Quaternion clone()
```


Clone current instance

**Returns:**
[Quaternion](../../com.aspose.threed/quaternion)
### concat(Quaternion rhs) {#concat-com.aspose.threed.Quaternion-}
```
public Quaternion concat(Quaternion rhs)
```


Menggabungkan dua quaternion

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| rhs | [Quaternion](../../com.aspose.threed/quaternion) |  |

**Returns:**
[Quaternion](../../com.aspose.threed/quaternion)
### conjugate() {#conjugate--}
```
public Quaternion conjugate()
```


Mengembalikan quaternion konjugat dari quaternion saat ini

**Returns:**
[Quaternion](../../com.aspose.threed/quaternion) - The conjugate quaternion.
### copyFrom(Quaternion src) {#copyFrom-com.aspose.threed.Quaternion-}
```
public void copyFrom(Quaternion src)
```




**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| src | [Quaternion](../../com.aspose.threed/quaternion) |  |

### div(Quaternion lhs, double rhs) {#div-com.aspose.threed.Quaternion-double-}
```
public static Quaternion div(Quaternion lhs, double rhs)
```


Overloading operator untuk /.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| lhs | [Quaternion](../../com.aspose.threed/quaternion) | Quaternion kiri |
| rhs | double | Quaternion kanan |

**Returns:**
[Quaternion](../../com.aspose.threed/quaternion) - Result quaternion
### dot(Quaternion q) {#dot-com.aspose.threed.Quaternion-}
```
public double dot(Quaternion q)
```


Produk titik

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| q | [Quaternion](../../com.aspose.threed/quaternion) | Quaternion |

**Returns:**
double - Nilai dot
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Periksa apakah dua quaternion sama

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| obj | java.lang.Object | The object to check equality. |

**Returns:**
boolean - True if all components are identically equal.
### eulerAngles() {#eulerAngles--}
```
public Vector3 eulerAngles()
```


Mengonversi quaternion menjadi rotasi yang direpresentasikan oleh sudut Euler. Semua komponen dalam radian.

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - Result vector
### fromAngleAxis(double a, Vector3 axis) {#fromAngleAxis-double-com.aspose.threed.Vector3-}
```
public static Quaternion fromAngleAxis(double a, Vector3 axis)
```


Membuat quaternion di sekitar sumbu yang diberikan dan memutar searah jarum jam

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| a | double | Rotasi searah jarum jam dalam radian |
| axis | [Vector3](../../com.aspose.threed/vector3) | Sumbu |

**Returns:**
[Quaternion](../../com.aspose.threed/quaternion) - Created quaternion
### fromEulerAngle(Vector3 eulerAngle) {#fromEulerAngle-com.aspose.threed.Vector3-}
```
public static Quaternion fromEulerAngle(Vector3 eulerAngle)
```


Membuat quaternion dari sudut Euler yang diberikan

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| eulerAngle | [Vector3](../../com.aspose.threed/vector3) | Sudut Euler dalam radian |

**Returns:**
[Quaternion](../../com.aspose.threed/quaternion) - Created quaternion
### fromEulerAngle(double pitch, double yaw, double roll) {#fromEulerAngle-double-double-double-}
```
public static Quaternion fromEulerAngle(double pitch, double yaw, double roll)
```


Membuat quaternion dari sudut Euler yang diberikan

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| pitch | double | Pitch dalam radian |
| yaw | double | Yaw dalam radian |
| roll | double | Roll dalam radian |

**Returns:**
[Quaternion](../../com.aspose.threed/quaternion) - Created quaternion
### fromRotation(Vector3 orig, Vector3 dest) {#fromRotation-com.aspose.threed.Vector3-com.aspose.threed.Vector3-}
```
public static Quaternion fromRotation(Vector3 orig, Vector3 dest)
```


Membuat quaternion yang memutar dari arah asli ke arah tujuan

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| orig | [Vector3](../../com.aspose.threed/vector3) | Arah asli |
| dest | [Vector3](../../com.aspose.threed/vector3) | Arah tujuan |

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


Mendapatkan panjang quaternion

**Returns:**
double - panjang quaternion
### hashCode() {#hashCode--}
```
public int hashCode()
```


Mendapatkan kode hash dari Quaternion

**Returns:**
int - Kode hash dari [Quaternion](../../com.aspose.threed/quaternion)
### interpolate(float t, Quaternion from, Quaternion to) {#interpolate-float-com.aspose.threed.Quaternion-com.aspose.threed.Quaternion-}
```
public static Quaternion interpolate(float t, Quaternion from, Quaternion to)
```


Mengisi quaternion ini dengan nilai interpolasi antara argumen quaternion yang diberikan untuk t antara dari dan ke.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| t | float | Koefisien untuk interpolasi. |
| from | [Quaternion](../../com.aspose.threed/quaternion) | Quaternion sumber. |
| to | [Quaternion](../../com.aspose.threed/quaternion) | Quaternion target. |

**Returns:**
[Quaternion](../../com.aspose.threed/quaternion) - The interpolated quaternion.
### inverse() {#inverse--}
```
public Quaternion inverse()
```


Mengembalikan quaternion invers dari quaternion saat ini

**Returns:**
[Quaternion](../../com.aspose.threed/quaternion) - Inverse quaternion.
### mul(Quaternion lhs, Quaternion rhs) {#mul-com.aspose.threed.Quaternion-com.aspose.threed.Quaternion-}
```
public static Quaternion mul(Quaternion lhs, Quaternion rhs)
```


Overloading operator untuk \*.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| lhs | [Quaternion](../../com.aspose.threed/quaternion) | Quaternion kiri |
| rhs | [Quaternion](../../com.aspose.threed/quaternion) | Quaternion kanan |

**Returns:**
[Quaternion](../../com.aspose.threed/quaternion) - Result quaternion
### mul(Quaternion q, Vector3 v) {#mul-com.aspose.threed.Quaternion-com.aspose.threed.Vector3-}
```
public static Vector3 mul(Quaternion q, Vector3 v)
```


Overloading operator untuk \*.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| q | [Quaternion](../../com.aspose.threed/quaternion) | Quaternion rotasi |
| v | [Vector3](../../com.aspose.threed/vector3) | Vektor untuk diputar |

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - Rotated vector
### mul(Quaternion q, Vector4 v) {#mul-com.aspose.threed.Quaternion-com.aspose.threed.Vector4-}
```
public static Vector4 mul(Quaternion q, Vector4 v)
```


Overloading operator untuk \*.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| q | [Quaternion](../../com.aspose.threed/quaternion) | Quaternion rotasi |
| v | [Vector4](../../com.aspose.threed/vector4) | Vektor untuk diputar |

**Returns:**
[Vector4](../../com.aspose.threed/vector4) - Rotated vector
### mul(Quaternion lhs, double rhs) {#mul-com.aspose.threed.Quaternion-double-}
```
public static Quaternion mul(Quaternion lhs, double rhs)
```


Overloading operator untuk \*.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| lhs | [Quaternion](../../com.aspose.threed/quaternion) | Quaternion kiri |
| rhs | double | Quaternion kanan |

**Returns:**
[Quaternion](../../com.aspose.threed/quaternion) - Result quaternion
### mul(Vector3 v, Quaternion q) {#mul-com.aspose.threed.Vector3-com.aspose.threed.Quaternion-}
```
public static Vector3 mul(Vector3 v, Quaternion q)
```


Overloading operator untuk \*.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| v | [Vector3](../../com.aspose.threed/vector3) | Quaternion rotasi |
| q | [Quaternion](../../com.aspose.threed/quaternion) | Vektor untuk diputar |

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - Rotated vector
### normalize() {#normalize--}
```
public Quaternion normalize()
```


Normalisasi quaternion

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


Operator sama untuk quaternion

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| lhs | [Quaternion](../../com.aspose.threed/quaternion) | Left hand side value. |
| rhs | [Quaternion](../../com.aspose.threed/quaternion) | Right hand side value. |

**Returns:**
boolean - True if all components are identically equal.
### op_ne(Quaternion lhs, Quaternion rhs) {#op-ne-com.aspose.threed.Quaternion-com.aspose.threed.Quaternion-}
```
public static boolean op_ne(Quaternion lhs, Quaternion rhs)
```


Operator tidak sama untuk quaternion

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| lhs | [Quaternion](../../com.aspose.threed/quaternion) | Left hand side value. |
| rhs | [Quaternion](../../com.aspose.threed/quaternion) | Right hand side value. |

**Returns:**
boolean - True jika dua quaternion tidak sama.
### slerp(double t, Quaternion v1, Quaternion v2) {#slerp-double-com.aspose.threed.Quaternion-com.aspose.threed.Quaternion-}
```
public static Quaternion slerp(double t, Quaternion v1, Quaternion v2)
```


Melakukan interpolasi linier sferis antara dua nilai

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| t | double | t berada di antara 0 hingga 1 |
| v1 | [Quaternion](../../com.aspose.threed/quaternion) | Nilai pertama |
| v2 | [Quaternion](../../com.aspose.threed/quaternion) | Nilai kedua |

**Returns:**
[Quaternion](../../com.aspose.threed/quaternion)
### toAngleAxis(double[] angle, Vector3 axis) {#toAngleAxis-double---com.aspose.threed.Vector3-}
```
public void toAngleAxis(double[] angle, Vector3 axis)
```


Mendecompose quaternion menjadi sudut dan sumbu

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| angle | double[] | Sudut untuk diputar, dalam radian. |
| axis | [Vector3](../../com.aspose.threed/vector3) | Sumbu yang diputar di sekitarnya. |

### toMatrix() {#toMatrix--}
```
public Matrix4 toMatrix()
```


Mengonversi rotasi yang dipresentasikan oleh quaternion menjadi matriks transformasi.

**Returns:**
[Matrix4](../../com.aspose.threed/matrix4) - The matrix representation of current quaternion.
### toMatrix(Vector3 translation) {#toMatrix-com.aspose.threed.Vector3-}
```
public Matrix4 toMatrix(Vector3 translation)
```


Mengonversi rotasi yang dipresentasikan oleh quaternion menjadi matriks transformasi.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| translation | [Vector3](../../com.aspose.threed/vector3) | Bagian translasi dari matriks. |

**Returns:**
[Matrix4](../../com.aspose.threed/matrix4) - The matrix representation of current quaternion.
### toString() {#toString--}
```
public String toString()
```


Mendapatkan representasi quaternion dalam string

**Returns:**
java.lang.String - String objek
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final void wait(long arg0)
```




**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |


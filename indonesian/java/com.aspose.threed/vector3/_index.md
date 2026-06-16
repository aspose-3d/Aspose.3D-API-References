---
title: "Vector3"
second_title: "Referensi API Aspose.3D untuk Java"
description: "Vektor dengan tiga komponen."
type: docs
weight: 202
url: /id/java/com.aspose.threed/vector3/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.lang.Comparable, com.aspose.threed.Struct, java.io.Serializable
```
public final class Vector3 implements Comparable<Vector3>, Struct<Vector3>, Serializable
```

Vektor dengan tiga komponen.
## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [Vector3(double x, double y, double z)](#Vector3-double-double-double-) | Menginisialisasi sebuah instance baru dari struct [Vector3](../../com.aspose.threed/vector3). |
| [Vector3(FVector3 vec)](#Vector3-com.aspose.threed.FVector3-) | Menginisialisasi sebuah instance baru dari struct [Vector3](../../com.aspose.threed/vector3). |
| [Vector3(double v)](#Vector3-double-) | Menginisialisasi sebuah instance baru dari struct [Vector3](../../com.aspose.threed/vector3). |
| [Vector3(Vector4 vec4)](#Vector3-com.aspose.threed.Vector4-) | Menginisialisasi sebuah instance baru dari struct [Vector3](../../com.aspose.threed/vector3). |
| [Vector3()](#Vector3--) |  |
## Bidang

| Bidang | Deskripsi |
| --- | --- |
| [x](#x) | Komponen x. |
| [y](#y) | Komponen y. |
| [z](#z) | Komponen z. |
## Metode

| Metode | Deskripsi |
| --- | --- |
| [add(Vector3 lhs, Vector3 rhs)](#add-com.aspose.threed.Vector3-com.aspose.threed.Vector3-) | Overloading operator untuk +. |
| [angleBetween(Vector3 dir)](#angleBetween-com.aspose.threed.Vector3-) | Hitung sudut dalam antara dua arah. Dua arah dapat berupa vektor yang tidak ternormalisasi. |
| [angleBetween(Vector3 dir, Vector3 up)](#angleBetween-com.aspose.threed.Vector3-com.aspose.threed.Vector3-) | Hitung sudut dalam antara dua arah. Dua arah dapat berupa vektor yang tidak ternormalisasi. |
| [clone()](#clone--) |  |
| [compareTo(Vector3 other)](#compareTo-com.aspose.threed.Vector3-) | Bandingkan vektor saat ini dengan instance lain. |
| [copyFrom(Vector3 src)](#copyFrom-com.aspose.threed.Vector3-) |  |
| [cos()](#cos--) | Menghitung kosinus pada setiap komponen. |
| [create(Vector3 v)](#create-com.aspose.threed.Vector3-) | Operator konversi eksplisit untuk mengubah Vector3 menjadi FVector3. |
| [cross(Vector3 rhs)](#cross-com.aspose.threed.Vector3-) | Produk silang dari dua vektor. |
| [div(Vector3 lhs, Vector3 rhs)](#div-com.aspose.threed.Vector3-com.aspose.threed.Vector3-) | Overloading operator untuk /. |
| [div(Vector3 lhs, double rhs)](#div-com.aspose.threed.Vector3-double-) | Overloading operator untuk /. |
| [dot(Vector3 rhs)](#dot-com.aspose.threed.Vector3-) | Mendapatkan produk dot dari dua vektor. |
| [equals(Object obj)](#equals-java.lang.Object-) | Periksa apakah dua vector3 sama. |
| [get(int idx)](#get-int-) | Mendapatkan komponen vektor berdasarkan indeks. |
| [getClass()](#getClass--) |  |
| [getLength()](#getLength--) | Mendapatkan panjang vektor ini. |
| [getLength2()](#getLength2--) | Mendapatkan kuadrat dari panjang. |
| [getOne()](#getOne--) | Mendapatkan vektor satuan (1, 1, 1). |
| [getUnitX()](#getUnitX--) | Mendapatkan vektor satuan (1, 0, 0). |
| [getUnitY()](#getUnitY--) | Mendapatkan vektor satuan (0, 1, 0). |
| [getUnitZ()](#getUnitZ--) | Mendapatkan vektor satuan (0, 0, 1). |
| [getZero()](#getZero--) | Mendapatkan vektor satuan (0, 0, 0). |
| [hashCode()](#hashCode--) | Mendapatkan kode hash dari Vector3. |
| [mul(Vector3 lhs, Vector3 rhs)](#mul-com.aspose.threed.Vector3-com.aspose.threed.Vector3-) | Overloading operator untuk \*. |
| [mul(Vector3 lhs, double rhs)](#mul-com.aspose.threed.Vector3-double-) | Overloading operator untuk \*. |
| [mul(double lhs, Vector3 rhs)](#mul-double-com.aspose.threed.Vector3-) | Overloading operator untuk \*. |
| [negative(Vector3 v)](#negative-com.aspose.threed.Vector3-) | Operator overloading untuk - |
| [normalize()](#normalize--) | Menormalkan instance ini. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [op_eq(Vector3 lhs, Vector3 rhs)](#op-eq-com.aspose.threed.Vector3-com.aspose.threed.Vector3-) | Operator sama dengan untuk Vector3 |
| [op_ne(Vector3 lhs, Vector3 rhs)](#op-ne-com.aspose.threed.Vector3-com.aspose.threed.Vector3-) | Operator tidak sama untuk Vector3 |
| [set(double newX, double newY, double newZ)](#set-double-double-double-) | Mengatur komponen x/y/z dalam satu panggilan. |
| [set(int idx, double value)](#set-int-double-) | Mengatur komponen vektor berdasarkan indeks. |
| [sin()](#sin--) | Menghitung sinus pada setiap komponen. |
| [sub(Vector3 lhs, Vector3 rhs)](#sub-com.aspose.threed.Vector3-com.aspose.threed.Vector3-) | Operator overloading untuk - (minus) |
| [toString()](#toString--) | Mengembalikan java.lang.String yang mewakili [Vector3](../../com.aspose.threed/vector3) saat ini. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Vector3(double x, double y, double z) {#Vector3-double-double-double-}
```
public Vector3(double x, double y, double z)
```


Menginisialisasi sebuah instance baru dari struct [Vector3](../../com.aspose.threed/vector3).

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| x | double | Koordinat x. |
| y | double | Koordinat y. |
| z | double | Koordinat z. |

### Vector3(FVector3 vec) {#Vector3-com.aspose.threed.FVector3-}
```
public Vector3(FVector3 vec)
```


Menginisialisasi sebuah instance baru dari struct [Vector3](../../com.aspose.threed/vector3).

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| vec | [FVector3](../../com.aspose.threed/fvector3) | Koordinat x. |

### Vector3(double v) {#Vector3-double-}
```
public Vector3(double v)
```


Menginisialisasi sebuah instance baru dari struct [Vector3](../../com.aspose.threed/vector3).

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| v | double | V. |

### Vector3(Vector4 vec4) {#Vector3-com.aspose.threed.Vector4-}
```
public Vector3(Vector4 vec4)
```


Menginisialisasi sebuah instance baru dari struct [Vector3](../../com.aspose.threed/vector3).

**Parameters:**
| Parameter | Tipe | Deskripsi |
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

### add(Vector3 lhs, Vector3 rhs) {#add-com.aspose.threed.Vector3-com.aspose.threed.Vector3-}
```
public static Vector3 add(Vector3 lhs, Vector3 rhs)
```


Overloading operator untuk +.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| lhs | [Vector3](../../com.aspose.threed/vector3) | Vektor kiri |
| rhs | [Vector3](../../com.aspose.threed/vector3) | Vektor kanan |

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - Result vector
### angleBetween(Vector3 dir) {#angleBetween-com.aspose.threed.Vector3-}
```
public double angleBetween(Vector3 dir)
```


Hitung sudut dalam antara dua arah. Dua arah dapat berupa vektor yang tidak ternormalisasi.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| dir | [Vector3](../../com.aspose.threed/vector3) | Vektor arah untuk dibandingkan |

**Returns:**
double - sudut dalam radian
### angleBetween(Vector3 dir, Vector3 up) {#angleBetween-com.aspose.threed.Vector3-com.aspose.threed.Vector3-}
```
public double angleBetween(Vector3 dir, Vector3 up)
```


Hitung sudut dalam antara dua arah. Dua arah dapat berupa vektor yang tidak ternormalisasi.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| dir | [Vector3](../../com.aspose.threed/vector3) | Vektor arah untuk dibandingkan |
| up | [Vector3](../../com.aspose.threed/vector3) | Vektor atas dari bidang bersama dua arah |

**Returns:**
double - sudut dalam radian
### clone() {#clone--}
```
public Vector3 clone()
```


Kloning instance saat ini

**Returns:**
[Vector3](../../com.aspose.threed/vector3)
### compareTo(Vector3 other) {#compareTo-com.aspose.threed.Vector3-}
```
public int compareTo(Vector3 other)
```


Bandingkan vektor saat ini dengan instance lain.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| other | [Vector3](../../com.aspose.threed/vector3) |  |

**Returns:**
int
### copyFrom(Vector3 src) {#copyFrom-com.aspose.threed.Vector3-}
```
public void copyFrom(Vector3 src)
```




**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| src | [Vector3](../../com.aspose.threed/vector3) |  |

### cos() {#cos--}
```
public Vector3 cos()
```


Menghitung kosinus pada setiap komponen.

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - Calculated [Vector3](../../com.aspose.threed/vector3).
### create(Vector3 v) {#create-com.aspose.threed.Vector3-}
```
public static FVector3 create(Vector3 v)
```


Operator konversi eksplisit untuk mengubah Vector3 menjadi FVector3.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| v | [Vector3](../../com.aspose.threed/vector3) |  |

**Returns:**
[FVector3](../../com.aspose.threed/fvector3)
### cross(Vector3 rhs) {#cross-com.aspose.threed.Vector3-}
```
public Vector3 cross(Vector3 rhs)
```


Produk silang dari dua vektor.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| rhs | [Vector3](../../com.aspose.threed/vector3) | Nilai sisi kanan. |

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - Cross product of two [Vector3](../../com.aspose.threed/vector3)s.
### div(Vector3 lhs, Vector3 rhs) {#div-com.aspose.threed.Vector3-com.aspose.threed.Vector3-}
```
public static Vector3 div(Vector3 lhs, Vector3 rhs)
```


Overloading operator untuk /.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| lhs | [Vector3](../../com.aspose.threed/vector3) | Vektor kiri |
| rhs | [Vector3](../../com.aspose.threed/vector3) | Vektor kanan |

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - Result vector
### div(Vector3 lhs, double rhs) {#div-com.aspose.threed.Vector3-double-}
```
public static Vector3 div(Vector3 lhs, double rhs)
```


Overloading operator untuk /.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| lhs | [Vector3](../../com.aspose.threed/vector3) | Vektor kiri |
| rhs | double | Nilai double kanan |

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - Result vector
### dot(Vector3 rhs) {#dot-com.aspose.threed.Vector3-}
```
public double dot(Vector3 rhs)
```


Mendapatkan produk dot dari dua vektor.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| rhs | [Vector3](../../com.aspose.threed/vector3) | Nilai sisi kanan. |

**Returns:**
double - Produk titik dari dua vektor.
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Periksa apakah dua vector3 sama.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| obj | java.lang.Object | Objek untuk memeriksa kesetaraan. |

**Returns:**
boolean - True jika semua komponen identik sama.
### get(int idx) {#get-int-}
```
public double get(int idx)
```


Mendapatkan komponen vektor berdasarkan indeks.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| idx | int |  |

**Returns:**
double - komponen vektor berdasarkan indeks.
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


Mendapatkan panjang vektor ini.

**Returns:**
double - panjang vektor ini.
### getLength2() {#getLength2--}
```
public double getLength2()
```


Mendapatkan kuadrat dari panjang.

**Returns:**
double - kuadrat panjang.
### getOne() {#getOne--}
```
public static Vector3 getOne()
```


Mendapatkan vektor satuan (1, 1, 1).

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - unit vector (1, 1, 1)
### getUnitX() {#getUnitX--}
```
public static Vector3 getUnitX()
```


Mendapatkan vektor satuan (1, 0, 0).

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - unit vector (1, 0, 0)
### getUnitY() {#getUnitY--}
```
public static Vector3 getUnitY()
```


Mendapatkan vektor satuan (0, 1, 0).

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - unit vector (0, 1, 0)
### getUnitZ() {#getUnitZ--}
```
public static Vector3 getUnitZ()
```


Mendapatkan vektor satuan (0, 0, 1).

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - unit vector (0, 0, 1)
### getZero() {#getZero--}
```
public static Vector3 getZero()
```


Mendapatkan vektor satuan (0, 0, 0).

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - unit vector (0, 0, 0)
### hashCode() {#hashCode--}
```
public int hashCode()
```


Mendapatkan kode hash dari Vector3.

**Returns:**
int - Kode hash dari [Vector3](../../com.aspose.threed/vector3)
### mul(Vector3 lhs, Vector3 rhs) {#mul-com.aspose.threed.Vector3-com.aspose.threed.Vector3-}
```
public static Vector3 mul(Vector3 lhs, Vector3 rhs)
```


Overloading operator untuk \*.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| lhs | [Vector3](../../com.aspose.threed/vector3) | Vektor kiri |
| rhs | [Vector3](../../com.aspose.threed/vector3) | Vektor kanan |

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - Result vector
### mul(Vector3 lhs, double rhs) {#mul-com.aspose.threed.Vector3-double-}
```
public static Vector3 mul(Vector3 lhs, double rhs)
```


Overloading operator untuk \*.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| lhs | [Vector3](../../com.aspose.threed/vector3) | Vektor kiri |
| rhs | double | Nilai double kanan |

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - Result vector
### mul(double lhs, Vector3 rhs) {#mul-double-com.aspose.threed.Vector3-}
```
public static Vector3 mul(double lhs, Vector3 rhs)
```


Overloading operator untuk \*.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| lhs | double | Skalar kiri |
| rhs | [Vector3](../../com.aspose.threed/vector3) | Vektor kanan |

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - Result vector
### negative(Vector3 v) {#negative-com.aspose.threed.Vector3-}
```
public static Vector3 negative(Vector3 v)
```


Operator overloading untuk -

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| v | [Vector3](../../com.aspose.threed/vector3) | Vektor asal |

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - Result vector
### normalize() {#normalize--}
```
public Vector3 normalize()
```


Menormalkan instance ini.

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


Operator sama dengan untuk Vector3

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| lhs | [Vector3](../../com.aspose.threed/vector3) | Nilai sisi kiri. |
| rhs | [Vector3](../../com.aspose.threed/vector3) | Nilai sisi kanan. |

**Returns:**
boolean - True jika semua komponen identik sama.
### op_ne(Vector3 lhs, Vector3 rhs) {#op-ne-com.aspose.threed.Vector3-com.aspose.threed.Vector3-}
```
public static boolean op_ne(Vector3 lhs, Vector3 rhs)
```


Operator tidak sama untuk Vector3

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| lhs | [Vector3](../../com.aspose.threed/vector3) | Nilai sisi kiri. |
| rhs | [Vector3](../../com.aspose.threed/vector3) | Nilai sisi kanan. |

**Returns:**
boolean - True jika dua vektor tidak sama.
### set(double newX, double newY, double newZ) {#set-double-double-double-}
```
public void set(double newX, double newY, double newZ)
```


Mengatur komponen x/y/z dalam satu panggilan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| newX | double | Komponen x. |
| newY | double | Komponen y. |
| newZ | double | Komponen z. |

### set(int idx, double value) {#set-int-double-}
```
public void set(int idx, double value)
```


Mengatur komponen vektor berdasarkan indeks.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| idx | int |  |
| nilai | double | Nilai baru |

### sin() {#sin--}
```
public Vector3 sin()
```


Menghitung sinus pada setiap komponen.

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - Calculated [Vector3](../../com.aspose.threed/vector3).
### sub(Vector3 lhs, Vector3 rhs) {#sub-com.aspose.threed.Vector3-com.aspose.threed.Vector3-}
```
public static Vector3 sub(Vector3 lhs, Vector3 rhs)
```


Operator overloading untuk - (minus)

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| lhs | [Vector3](../../com.aspose.threed/vector3) | Vektor kiri |
| rhs | [Vector3](../../com.aspose.threed/vector3) | Vektor kanan |

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - Result vector
### toString() {#toString--}
```
public String toString()
```


Mengembalikan java.lang.String yang mewakili [Vector3](../../com.aspose.threed/vector3) saat ini.

**Returns:**
java.lang.String - java.lang.String yang merepresentasikan [Vector3](../../com.aspose.threed/vector3) saat ini.
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


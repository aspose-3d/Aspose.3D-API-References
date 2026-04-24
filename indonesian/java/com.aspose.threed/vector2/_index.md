---
title: Vector2
second_title: Referensi API Aspose.3D untuk Java
description: Vektor dengan dua komponen.
type: docs
weight: 201
url: /id/java/com.aspose.threed/vector2/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.lang.Comparable, com.aspose.threed.Struct, java.io.Serializable
```
public final class Vector2 implements Comparable<Vector2>, Struct<Vector2>, Serializable
```

Vektor dengan dua komponen.
## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [Vector2(double s)](#Vector2-double-) | Menginisialisasi instance baru dari struct [Vector2](../../com.aspose.threed/vector2). |
| [Vector2(Vector3 s)](#Vector2-com.aspose.threed.Vector3-) | Menginisialisasi instance baru dari struct [Vector2](../../com.aspose.threed/vector2). |
| [Vector2(FVector2 vec)](#Vector2-com.aspose.threed.FVector2-) | Menginisialisasi instance baru dari struct [Vector2](../../com.aspose.threed/vector2). |
| [Vector2(double x, double y)](#Vector2-double-double-) | Menginisialisasi instance baru dari struct [Vector2](../../com.aspose.threed/vector2). |
| [Vector2()](#Vector2--) |  |
## Bidang

| Bidang | Deskripsi |
| --- | --- |
| [x](#x) | Komponen x. |
| [y](#y) | Komponen y. |
## Metode

| Metode | Deskripsi |
| --- | --- |
| [add(Vector2 lhs, Vector2 rhs)](#add-com.aspose.threed.Vector2-com.aspose.threed.Vector2-) | Operator penjumlahan untuk Vector2 |
| [clone()](#clone--) |  |
| [compareTo(Vector2 other)](#compareTo-com.aspose.threed.Vector2-) | Bandingkan vektor saat ini dengan instance lain. |
| [copyFrom(Vector2 src)](#copyFrom-com.aspose.threed.Vector2-) |  |
| [create(Vector2 v)](#create-com.aspose.threed.Vector2-) | Operator konversi eksplisit untuk mengubah Vector2 menjadi FVector2 |
| [cross(Vector2 v)](#cross-com.aspose.threed.Vector2-) | Produk silang dari dua vektor. |
| [div(Vector2 lhs, double rhs)](#div-com.aspose.threed.Vector2-double-) | Operator pembagian untuk Vector2 |
| [dot(Vector2 rhs)](#dot-com.aspose.threed.Vector2-) | Mendapatkan produk dot dari dua vektor. |
| [equals(Vector2 rhs)](#equals-com.aspose.threed.Vector2-) | Periksa apakah dua vector2 sama |
| [equals(Object obj)](#equals-java.lang.Object-) | Periksa apakah dua vector2 sama |
| [getClass()](#getClass--) |  |
| [getLength()](#getLength--) | Mendapatkan panjang. |
| [getU()](#getU--) | Mendapatkan komponen U jika [Vector2](../../com.aspose.threed/vector2) digunakan sebagai koordinat pemetaan. |
| [getV()](#getV--) | Mendapatkan komponen V jika [Vector2](../../com.aspose.threed/vector2) digunakan sebagai koordinat pemetaan. |
| [hashCode()](#hashCode--) | Mendapatkan kode hash dari Vector2 |
| [mul(Vector2 lhs, double rhs)](#mul-com.aspose.threed.Vector2-double-) | Operator perkalian untuk Vector2 |
| [mul(double lhs, Vector2 rhs)](#mul-double-com.aspose.threed.Vector2-) | Operator perkalian untuk Vector2 |
| [normalize()](#normalize--) | Normalizes this instance. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [op_eq(Vector2 lhs, Vector2 rhs)](#op-eq-com.aspose.threed.Vector2-com.aspose.threed.Vector2-) | Operator sama dengan untuk Vector2 |
| [op_ne(Vector2 lhs, Vector2 rhs)](#op-ne-com.aspose.threed.Vector2-com.aspose.threed.Vector2-) | Operator tidak sama dengan untuk Vector2 |
| [setU(double value)](#setU-double-) | Mengatur komponen U jika [Vector2](../../com.aspose.threed/vector2) digunakan sebagai koordinat pemetaan. |
| [setV(double value)](#setV-double-) | Mengatur komponen V jika [Vector2](../../com.aspose.threed/vector2) digunakan sebagai koordinat pemetaan. |
| [sub(Vector2 lhs, Vector2 rhs)](#sub-com.aspose.threed.Vector2-com.aspose.threed.Vector2-) | Operator pengurangan untuk Vector2 |
| [toString()](#toString--) | Mengembalikan java.lang.String yang mewakili [Vector2](../../com.aspose.threed/vector2) saat ini. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Vector2(double s) {#Vector2-double-}
```
public Vector2(double s)
```


Menginisialisasi instance baru dari struct [Vector2](../../com.aspose.threed/vector2).

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| s | double | S. |

### Vector2(Vector3 s) {#Vector2-com.aspose.threed.Vector3-}
```
public Vector2(Vector3 s)
```


Menginisialisasi instance baru dari struct [Vector2](../../com.aspose.threed/vector2).

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| s | [Vector3](../../com.aspose.threed/vector3) | S. |

### Vector2(FVector2 vec) {#Vector2-com.aspose.threed.FVector2-}
```
public Vector2(FVector2 vec)
```


Menginisialisasi instance baru dari struct [Vector2](../../com.aspose.threed/vector2).

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| vec | [FVector2](../../com.aspose.threed/fvector2) | Vektor dalam float. |

### Vector2(double x, double y) {#Vector2-double-double-}
```
public Vector2(double x, double y)
```


Menginisialisasi instance baru dari struct [Vector2](../../com.aspose.threed/vector2).

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| x | double | The x coordinate. |
| y | double | The y coordinate. |

### Vector2() {#Vector2--}
```
public Vector2()
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

### add(Vector2 lhs, Vector2 rhs) {#add-com.aspose.threed.Vector2-com.aspose.threed.Vector2-}
```
public static Vector2 add(Vector2 lhs, Vector2 rhs)
```


Operator penjumlahan untuk Vector2

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| lhs | [Vector2](../../com.aspose.threed/vector2) | Left hand side value. |
| rhs | [Vector2](../../com.aspose.threed/vector2) | Right hand side value. |

**Returns:**
[Vector2](../../com.aspose.threed/vector2) - The result of addition.
### clone() {#clone--}
```
public Vector2 clone()
```


Clone current instance

**Returns:**
[Vector2](../../com.aspose.threed/vector2)
### compareTo(Vector2 other) {#compareTo-com.aspose.threed.Vector2-}
```
public int compareTo(Vector2 other)
```


Bandingkan vektor saat ini dengan instance lain.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| other | [Vector2](../../com.aspose.threed/vector2) |  |

**Returns:**
int
### copyFrom(Vector2 src) {#copyFrom-com.aspose.threed.Vector2-}
```
public void copyFrom(Vector2 src)
```




**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| src | [Vector2](../../com.aspose.threed/vector2) |  |

### create(Vector2 v) {#create-com.aspose.threed.Vector2-}
```
public static FVector2 create(Vector2 v)
```


Operator konversi eksplisit untuk mengubah Vector2 menjadi FVector2

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| v | [Vector2](../../com.aspose.threed/vector2) |  |

**Returns:**
[FVector2](../../com.aspose.threed/fvector2)
### cross(Vector2 v) {#cross-com.aspose.threed.Vector2-}
```
public double cross(Vector2 v)
```


Produk silang dari dua vektor.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| v | [Vector2](../../com.aspose.threed/vector2) |  |

**Returns:**
double
### div(Vector2 lhs, double rhs) {#div-com.aspose.threed.Vector2-double-}
```
public static Vector2 div(Vector2 lhs, double rhs)
```


Operator pembagian untuk Vector2

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| lhs | [Vector2](../../com.aspose.threed/vector2) | Left hand side value. |
| rhs | double | Right hand side value. |

**Returns:**
[Vector2](../../com.aspose.threed/vector2) - The result of division.
### dot(Vector2 rhs) {#dot-com.aspose.threed.Vector2-}
```
public double dot(Vector2 rhs)
```


Mendapatkan produk dot dari dua vektor.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| rhs | [Vector2](../../com.aspose.threed/vector2) | Right hand side value. |

**Returns:**
double - The dot product of the two vectors.
### equals(Vector2 rhs) {#equals-com.aspose.threed.Vector2-}
```
public boolean equals(Vector2 rhs)
```


Periksa apakah dua vector2 sama

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| rhs | [Vector2](../../com.aspose.threed/vector2) | Nilai sisi kanan. |

**Returns:**
boolean - True if all components are identically equal.
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Periksa apakah dua vector2 sama

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| obj | java.lang.Object | Objek yang akan dibandingkan. |

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


Mendapatkan panjang.

**Returns:**
double - panjang.
### getU() {#getU--}
```
public double getU()
```


Mendapatkan komponen U jika [Vector2](../../com.aspose.threed/vector2) digunakan sebagai koordinat pemetaan. Ini adalah alias dari komponen x.

**Returns:**
double - komponen U jika [Vector2](../../com.aspose.threed/vector2) digunakan sebagai koordinat pemetaan. Ini adalah alias dari komponen x.
### getV() {#getV--}
```
public double getV()
```


Mendapatkan komponen V jika [Vector2](../../com.aspose.threed/vector2) digunakan sebagai koordinat pemetaan. Ini adalah alias dari komponen y.

**Returns:**
double - komponen V jika [Vector2](../../com.aspose.threed/vector2) digunakan sebagai koordinat pemetaan. Ini adalah alias dari komponen y.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Mendapatkan kode hash dari Vector2

**Returns:**
int - Kode hash dari [Vector2](../../com.aspose.threed/vector2)
### mul(Vector2 lhs, double rhs) {#mul-com.aspose.threed.Vector2-double-}
```
public static Vector2 mul(Vector2 lhs, double rhs)
```


Operator perkalian untuk Vector2

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| lhs | [Vector2](../../com.aspose.threed/vector2) | Left hand side value. |
| rhs | double | Right hand side value. |

**Returns:**
[Vector2](../../com.aspose.threed/vector2) - The result of multiply.
### mul(double lhs, Vector2 rhs) {#mul-double-com.aspose.threed.Vector2-}
```
public static Vector2 mul(double lhs, Vector2 rhs)
```


Operator perkalian untuk Vector2

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| lhs | double | Left hand side value. |
| rhs | [Vector2](../../com.aspose.threed/vector2) | Right hand side value. |

**Returns:**
[Vector2](../../com.aspose.threed/vector2) - The result of multiply.
### normalize() {#normalize--}
```
public Vector2 normalize()
```


Normalizes this instance.

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


Operator sama dengan untuk Vector2

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| lhs | [Vector2](../../com.aspose.threed/vector2) | Left hand side value. |
| rhs | [Vector2](../../com.aspose.threed/vector2) | Right hand side value. |

**Returns:**
boolean - True if all components are identically equal.
### op_ne(Vector2 lhs, Vector2 rhs) {#op-ne-com.aspose.threed.Vector2-com.aspose.threed.Vector2-}
```
public static boolean op_ne(Vector2 lhs, Vector2 rhs)
```


Operator tidak sama dengan untuk Vector2

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| lhs | [Vector2](../../com.aspose.threed/vector2) | Left hand side value. |
| rhs | [Vector2](../../com.aspose.threed/vector2) | Right hand side value. |

**Returns:**
boolean - True if two vectors are not equal.
### setU(double value) {#setU-double-}
```
public void setU(double value)
```


Mengatur komponen U jika [Vector2](../../com.aspose.threed/vector2) digunakan sebagai koordinat pemetaan. Ini adalah alias dari komponen x.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | double | Nilai baru |

### setV(double value) {#setV-double-}
```
public void setV(double value)
```


Mengatur komponen V jika [Vector2](../../com.aspose.threed/vector2) digunakan sebagai koordinat pemetaan. Ini adalah alias dari komponen y.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | double | Nilai baru |

### sub(Vector2 lhs, Vector2 rhs) {#sub-com.aspose.threed.Vector2-com.aspose.threed.Vector2-}
```
public static Vector2 sub(Vector2 lhs, Vector2 rhs)
```


Operator pengurangan untuk Vector2

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| lhs | [Vector2](../../com.aspose.threed/vector2) | Left hand side value. |
| rhs | [Vector2](../../com.aspose.threed/vector2) | Right hand side value. |

**Returns:**
[Vector2](../../com.aspose.threed/vector2) - The result of substraction.
### toString() {#toString--}
```
public String toString()
```


Mengembalikan java.lang.String yang mewakili [Vector2](../../com.aspose.threed/vector2) saat ini.

**Returns:**
java.lang.String - java.lang.String yang mewakili [Vector2](../../com.aspose.threed/vector2) saat ini.
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


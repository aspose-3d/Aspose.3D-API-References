---
title: Vector4
second_title: Referensi API Aspose.3D untuk Java
description: Vektor dengan empat komponen.
type: docs
weight: 203
url: /id/java/com.aspose.threed/vector4/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.lang.Comparable, com.aspose.threed.Struct, java.io.Serializable
```
public final class Vector4 implements Comparable<Vector4>, Struct<Vector4>, Serializable
```

Vektor dengan empat komponen.
## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [Vector4(Vector3 vec, double w)](#Vector4-com.aspose.threed.Vector3-double-) | Menginisialisasi instance baru dari struct [Vector4](../../com.aspose.threed/vector4). |
| [Vector4(Vector3 vec)](#Vector4-com.aspose.threed.Vector3-) | Menginisialisasi instance baru dari struct [Vector4](../../com.aspose.threed/vector4). |
| [Vector4(FVector4 vec)](#Vector4-com.aspose.threed.FVector4-) | Menginisialisasi instance baru dari struct [Vector4](../../com.aspose.threed/vector4). |
| [Vector4(double x, double y, double z)](#Vector4-double-double-double-) | Menginisialisasi instance baru dari struct [Vector4](../../com.aspose.threed/vector4). |
| [Vector4(double x, double y, double z, double w)](#Vector4-double-double-double-double-) | Menginisialisasi instance baru dari struct [Vector4](../../com.aspose.threed/vector4). |
| [Vector4()](#Vector4--) |  |
## Bidang

| Bidang | Deskripsi |
| --- | --- |
| [w](#w) | Komponen w. |
| [x](#x) | Komponen x. |
| [y](#y) | Komponen y. |
| [z](#z) | Komponen z. |
## Metode

| Metode | Deskripsi |
| --- | --- |
| [add(Vector4 lhs, Vector4 rhs)](#add-com.aspose.threed.Vector4-com.aspose.threed.Vector4-) | Overloading operator untuk +. |
| [clone()](#clone--) |  |
| [compareTo(Vector4 other)](#compareTo-com.aspose.threed.Vector4-) | Bandingkan vektor saat ini dengan instance lain. |
| [copyFrom(Vector4 src)](#copyFrom-com.aspose.threed.Vector4-) |  |
| [create(Vector4 v)](#create-com.aspose.threed.Vector4-) | Operator konversi eksplisit untuk mengubah Vector4 menjadi FVector4 |
| [equals(Object obj)](#equals-java.lang.Object-) | Periksa apakah dua vektor sama |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) | Mendapatkan kode hash vektor ini |
| [mul(Vector4 lhs, Vector4 rhs)](#mul-com.aspose.threed.Vector4-com.aspose.threed.Vector4-) | Overloading operator untuk \*. |
| [mul(Vector4 lhs, double rhs)](#mul-com.aspose.threed.Vector4-double-) | Overloading operator untuk \*. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [set(double newX, double newY, double newZ)](#set-double-double-double-) | Mengatur komponen xyz vektor sekaligus, w akan diatur menjadi 1 |
| [set(double newX, double newY, double newZ, double newW)](#set-double-double-double-double-) | Mengatur semua komponen vektor sekaligus |
| [sub(Vector4 lhs, Vector4 rhs)](#sub-com.aspose.threed.Vector4-com.aspose.threed.Vector4-) | Operator overloading for - (minus) |
| [toString()](#toString--) | Mengembalikan java.lang.String yang merepresentasikan [Vector4](../../com.aspose.threed/vector4) saat ini. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Vector4(Vector3 vec, double w) {#Vector4-com.aspose.threed.Vector3-double-}
```
public Vector4(Vector3 vec, double w)
```


Menginisialisasi instance baru dari struct [Vector4](../../com.aspose.threed/vector4).

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| vec | [Vector3](../../com.aspose.threed/vector3) | Vec. |
| w | double | Lebar. |

### Vector4(Vector3 vec) {#Vector4-com.aspose.threed.Vector3-}
```
public Vector4(Vector3 vec)
```


Menginisialisasi instance baru dari struct [Vector4](../../com.aspose.threed/vector4).

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| vec | [Vector3](../../com.aspose.threed/vector3) | Vec. |

### Vector4(FVector4 vec) {#Vector4-com.aspose.threed.FVector4-}
```
public Vector4(FVector4 vec)
```


Menginisialisasi instance baru dari struct [Vector4](../../com.aspose.threed/vector4).

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| vec | [FVector4](../../com.aspose.threed/fvector4) | Vec. |

### Vector4(double x, double y, double z) {#Vector4-double-double-double-}
```
public Vector4(double x, double y, double z)
```


Menginisialisasi instance baru dari struct [Vector4](../../com.aspose.threed/vector4).

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| x | double | The x coordinate. |
| y | double | The y coordinate. |
| z | double | The z coordinate. |

### Vector4(double x, double y, double z, double w) {#Vector4-double-double-double-double-}
```
public Vector4(double x, double y, double z, double w)
```


Menginisialisasi instance baru dari struct [Vector4](../../com.aspose.threed/vector4).

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| x | double | The x coordinate. |
| y | double | The y coordinate. |
| z | double | The z coordinate. |
| w | double | Lebar. |

### Vector4() {#Vector4--}
```
public Vector4()
```


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

### add(Vector4 lhs, Vector4 rhs) {#add-com.aspose.threed.Vector4-com.aspose.threed.Vector4-}
```
public static Vector4 add(Vector4 lhs, Vector4 rhs)
```


Overloading operator untuk +.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| lhs | [Vector4](../../com.aspose.threed/vector4) | The left vector |
| rhs | [Vector4](../../com.aspose.threed/vector4) | The right vector |

**Returns:**
[Vector4](../../com.aspose.threed/vector4) - Result vector
### clone() {#clone--}
```
public Vector4 clone()
```


Clone current instance

**Returns:**
[Vector4](../../com.aspose.threed/vector4)
### compareTo(Vector4 other) {#compareTo-com.aspose.threed.Vector4-}
```
public int compareTo(Vector4 other)
```


Bandingkan vektor saat ini dengan instance lain.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| other | [Vector4](../../com.aspose.threed/vector4) |  |

**Returns:**
int
### copyFrom(Vector4 src) {#copyFrom-com.aspose.threed.Vector4-}
```
public void copyFrom(Vector4 src)
```




**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| src | [Vector4](../../com.aspose.threed/vector4) |  |

### create(Vector4 v) {#create-com.aspose.threed.Vector4-}
```
public static FVector4 create(Vector4 v)
```


Operator konversi eksplisit untuk mengubah Vector4 menjadi FVector4

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| v | [Vector4](../../com.aspose.threed/vector4) |  |

**Returns:**
[FVector4](../../com.aspose.threed/fvector4)
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Periksa apakah dua vektor sama

**Parameters:**
| Parameter | Tipe | Deskripsi |
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
### hashCode() {#hashCode--}
```
public int hashCode()
```


Mendapatkan kode hash vektor ini

**Returns:**
int
### mul(Vector4 lhs, Vector4 rhs) {#mul-com.aspose.threed.Vector4-com.aspose.threed.Vector4-}
```
public static Vector4 mul(Vector4 lhs, Vector4 rhs)
```


Overloading operator untuk \*.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| lhs | [Vector4](../../com.aspose.threed/vector4) | The left vector |
| rhs | [Vector4](../../com.aspose.threed/vector4) | The right vector |

**Returns:**
[Vector4](../../com.aspose.threed/vector4) - Result vector
### mul(Vector4 lhs, double rhs) {#mul-com.aspose.threed.Vector4-double-}
```
public static Vector4 mul(Vector4 lhs, double rhs)
```


Overloading operator untuk \*.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| lhs | [Vector4](../../com.aspose.threed/vector4) | The left vector |
| rhs | double | The right double value |

**Returns:**
[Vector4](../../com.aspose.threed/vector4) - Result vector
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### set(double newX, double newY, double newZ) {#set-double-double-double-}
```
public void set(double newX, double newY, double newZ)
```


Mengatur komponen xyz vektor sekaligus, w akan diatur menjadi 1

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| newX | double | Komponen X baru. |
| newY | double | Komponen Y baru. |
| newZ | double | Komponen Z baru. |

### set(double newX, double newY, double newZ, double newW) {#set-double-double-double-double-}
```
public void set(double newX, double newY, double newZ, double newW)
```


Mengatur semua komponen vektor sekaligus

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| newX | double | Komponen X baru. |
| newY | double | Komponen Y baru. |
| newZ | double | Komponen Z baru. |
| newW | double | Komponen W baru. |

### sub(Vector4 lhs, Vector4 rhs) {#sub-com.aspose.threed.Vector4-com.aspose.threed.Vector4-}
```
public static Vector4 sub(Vector4 lhs, Vector4 rhs)
```


Operator overloading for - (minus)

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| lhs | [Vector4](../../com.aspose.threed/vector4) | The left vector |
| rhs | [Vector4](../../com.aspose.threed/vector4) | The right vector |

**Returns:**
[Vector4](../../com.aspose.threed/vector4) - Result vector
### toString() {#toString--}
```
public String toString()
```


Mengembalikan java.lang.String yang merepresentasikan [Vector4](../../com.aspose.threed/vector4) saat ini.

**Returns:**
java.lang.String - Sebuah java.lang.String yang mewakili [Vector4](../../com.aspose.threed/vector4).
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


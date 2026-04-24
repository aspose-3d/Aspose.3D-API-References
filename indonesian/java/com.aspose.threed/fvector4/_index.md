---
title: FVector4
second_title: Referensi API Aspose.3D untuk Java
description: Vektor float dengan empat komponen.
type: docs
weight: 61
url: /id/java/com.aspose.threed/fvector4/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.threed.Struct, java.io.Serializable
```
public final class FVector4 implements Struct<FVector4>, Serializable
```

Vektor float dengan empat komponen.
## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [FVector4(float x, float y, float z, float w)](#FVector4-float-float-float-float-) | Menginisialisasi instance baru dari [FVector4](../../com.aspose.threed/fvector4). |
| [FVector4(float x, float y, float z)](#FVector4-float-float-float-) | Menginisialisasi instance baru dari [FVector4](../../com.aspose.threed/fvector4). |
| [FVector4(Color color)](#FVector4-java.awt.Color-) | Menginisialisasi instance baru dari [FVector4](../../com.aspose.threed/fvector4). |
| [FVector4(Vector4 vec)](#FVector4-com.aspose.threed.Vector4-) | Menginisialisasi instance baru dari [FVector4](../../com.aspose.threed/fvector4). |
| [FVector4(Vector3 vec)](#FVector4-com.aspose.threed.Vector3-) | Menginisialisasi instance baru dari [FVector4](../../com.aspose.threed/fvector4). |
| [FVector4(Vector3 vec, float w)](#FVector4-com.aspose.threed.Vector3-float-) | Menginisialisasi instance baru dari [FVector4](../../com.aspose.threed/fvector4). |
| [FVector4()](#FVector4--) |  |
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
| [add(FVector4 lhs, FVector4 rhs)](#add-com.aspose.threed.FVector4-com.aspose.threed.FVector4-) | Overloading operator untuk +. |
| [clone()](#clone--) |  |
| [copyFrom(FVector4 src)](#copyFrom-com.aspose.threed.FVector4-) |  |
| [create(FVector4 v)](#create-com.aspose.threed.FVector4-) | Operator konversi eksplisit untuk mengubah Vector4 menjadi FVector4 |
| [equals(Object obj)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) |  |
| [mul(FVector4 lhs, FVector4 rhs)](#mul-com.aspose.threed.FVector4-com.aspose.threed.FVector4-) | Overloading operator untuk \*. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [sub(FVector4 lhs, FVector4 rhs)](#sub-com.aspose.threed.FVector4-com.aspose.threed.FVector4-) | Operator overloading for - (minus) |
| [toString()](#toString--) | Mengembalikan string yang merepresentasikan [FVector4](../../com.aspose.threed/fvector4) |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### FVector4(float x, float y, float z, float w) {#FVector4-float-float-float-float-}
```
public FVector4(float x, float y, float z, float w)
```


Menginisialisasi instance baru dari [FVector4](../../com.aspose.threed/fvector4).

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| x | float | Komponen X |
| y | float | Komponen Y |
| z | float | Komponen Z |
| w | float | Komponen W |

### FVector4(float x, float y, float z) {#FVector4-float-float-float-}
```
public FVector4(float x, float y, float z)
```


Menginisialisasi instance baru dari [FVector4](../../com.aspose.threed/fvector4).

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| x | float | Komponen X |
| y | float | Komponen Y |
| z | float | Komponen Z |

### FVector4(Color color) {#FVector4-java.awt.Color-}
```
public FVector4(Color color)
```


Menginisialisasi instance baru dari [FVector4](../../com.aspose.threed/fvector4).

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| warna | java.awt.Color |  |

### FVector4(Vector4 vec) {#FVector4-com.aspose.threed.Vector4-}
```
public FVector4(Vector4 vec)
```


Menginisialisasi instance baru dari [FVector4](../../com.aspose.threed/fvector4).

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| vec | [Vector4](../../com.aspose.threed/vector4) |  |

### FVector4(Vector3 vec) {#FVector4-com.aspose.threed.Vector3-}
```
public FVector4(Vector3 vec)
```


Menginisialisasi instance baru dari [FVector4](../../com.aspose.threed/fvector4).

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| vec | [Vector3](../../com.aspose.threed/vector3) |  |

### FVector4(Vector3 vec, float w) {#FVector4-com.aspose.threed.Vector3-float-}
```
public FVector4(Vector3 vec, float w)
```


Menginisialisasi instance baru dari [FVector4](../../com.aspose.threed/fvector4).

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| vec | [Vector3](../../com.aspose.threed/vector3) |  |
| w | float |  |

### FVector4() {#FVector4--}
```
public FVector4()
```


### w {#w}
```
public float w
```


Komponen w.

### x {#x}
```
public float x
```


Komponen x.

### y {#y}
```
public float y
```


Komponen y.

### z {#z}
```
public float z
```


Komponen z.

### add(FVector4 lhs, FVector4 rhs) {#add-com.aspose.threed.FVector4-com.aspose.threed.FVector4-}
```
public static FVector4 add(FVector4 lhs, FVector4 rhs)
```


Overloading operator untuk +.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| lhs | [FVector4](../../com.aspose.threed/fvector4) | The left vector |
| rhs | [FVector4](../../com.aspose.threed/fvector4) | The right vector |

**Returns:**
[FVector4](../../com.aspose.threed/fvector4) - Result vector
### clone() {#clone--}
```
public FVector4 clone()
```


Clone current instance

**Returns:**
[FVector4](../../com.aspose.threed/fvector4)
### copyFrom(FVector4 src) {#copyFrom-com.aspose.threed.FVector4-}
```
public void copyFrom(FVector4 src)
```




**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| src | [FVector4](../../com.aspose.threed/fvector4) |  |

### create(FVector4 v) {#create-com.aspose.threed.FVector4-}
```
public static Vector4 create(FVector4 v)
```


Operator konversi eksplisit untuk mengubah Vector4 menjadi FVector4

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| v | [FVector4](../../com.aspose.threed/fvector4) |  |

**Returns:**
[Vector4](../../com.aspose.threed/vector4)
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```




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




**Returns:**
int
### mul(FVector4 lhs, FVector4 rhs) {#mul-com.aspose.threed.FVector4-com.aspose.threed.FVector4-}
```
public static FVector4 mul(FVector4 lhs, FVector4 rhs)
```


Overloading operator untuk \*.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| lhs | [FVector4](../../com.aspose.threed/fvector4) | The left vector |
| rhs | [FVector4](../../com.aspose.threed/fvector4) | The right vector |

**Returns:**
[FVector4](../../com.aspose.threed/fvector4) - Result vector
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### sub(FVector4 lhs, FVector4 rhs) {#sub-com.aspose.threed.FVector4-com.aspose.threed.FVector4-}
```
public static FVector4 sub(FVector4 lhs, FVector4 rhs)
```


Operator overloading for - (minus)

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| lhs | [FVector4](../../com.aspose.threed/fvector4) | The left vector |
| rhs | [FVector4](../../com.aspose.threed/fvector4) | The right vector |

**Returns:**
[FVector4](../../com.aspose.threed/fvector4) - Result vector
### toString() {#toString--}
```
public String toString()
```


Mengembalikan string yang merepresentasikan [FVector4](../../com.aspose.threed/fvector4)

**Returns:**
java.lang.String - Representasi string dari vektor saat ini.
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


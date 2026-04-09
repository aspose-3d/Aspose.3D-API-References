---
title: FVector3
second_title: Referensi API Aspose.3D untuk Java
description: Vektor float dengan tiga komponen.
type: docs
weight: 60
url: /id/java/com.aspose.threed/fvector3/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.threed.Struct, java.io.Serializable
```
public final class FVector3 implements Struct<FVector3>, Serializable
```

Vektor float dengan tiga komponen.
## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [FVector3(float x, float y, float z)](#FVector3-float-float-float-) | Menginisialisasi instance baru dari [FVector3](../../com.aspose.threed/fvector3). |
| [FVector3(Vector3 vec)](#FVector3-com.aspose.threed.Vector3-) | Menginisialisasi instance baru dari [FVector3](../../com.aspose.threed/fvector3). |
| [FVector3(Vector4 vec)](#FVector3-com.aspose.threed.Vector4-) | Menginisialisasi instance baru dari [FVector4](../../com.aspose.threed/fvector4). |
| [FVector3()](#FVector3--) |  |
## Bidang

| Bidang | Deskripsi |
| --- | --- |
| [x](#x) | Komponen x. |
| [y](#y) | Komponen y. |
| [z](#z) | Komponen y. |
## Metode

| Metode | Deskripsi |
| --- | --- |
| [add(FVector3 a, FVector3 b)](#add-com.aspose.threed.FVector3-com.aspose.threed.FVector3-) | + Operator overload |
| [clone()](#clone--) |  |
| [copyFrom(FVector3 src)](#copyFrom-com.aspose.threed.FVector3-) |  |
| [create(FVector3 v)](#create-com.aspose.threed.FVector3-) | Operator konversi eksplisit untuk mengubah FVector3 menjadi Vector3 |
| [cross(FVector3 rhs)](#cross-com.aspose.threed.FVector3-) | Produk silang dari dua vektor. |
| [equals(Object obj)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getOne()](#getOne--) | Vektor skala unit dengan semua komponen bernilai 1 |
| [getZero()](#getZero--) | Vektor Nol. |
| [hashCode()](#hashCode--) |  |
| [mul(FVector3 a, float b)](#mul-com.aspose.threed.FVector3-float-) | \* Operator overloading |
| [negative(FVector3 a)](#negative-com.aspose.threed.FVector3-) | - Operator overload |
| [normalize()](#normalize--) | Normalizes this instance. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [sub(FVector3 a, FVector3 b)](#sub-com.aspose.threed.FVector3-com.aspose.threed.FVector3-) | - Operator overload |
| [toString()](#toString--) | Mengembalikan string yang merepresentasikan [FVector3](../../com.aspose.threed/fvector3) |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### FVector3(float x, float y, float z) {#FVector3-float-float-float-}
```
public FVector3(float x, float y, float z)
```


Menginisialisasi instance baru dari [FVector3](../../com.aspose.threed/fvector3).

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| x | float | Komponen X dari vektor |
| y | float | Komponen Y dari vektor |
| z | float | Komponen Z dari vektor |

### FVector3(Vector3 vec) {#FVector3-com.aspose.threed.Vector3-}
```
public FVector3(Vector3 vec)
```


Menginisialisasi instance baru dari [FVector3](../../com.aspose.threed/fvector3).

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| vec | [Vector3](../../com.aspose.threed/vector3) | Vector3 dalam tipe double |

### FVector3(Vector4 vec) {#FVector3-com.aspose.threed.Vector4-}
```
public FVector3(Vector4 vec)
```


Menginisialisasi instance baru dari [FVector4](../../com.aspose.threed/fvector4).

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| vec | [Vector4](../../com.aspose.threed/vector4) | Vector4 dalam tipe double |

### FVector3() {#FVector3--}
```
public FVector3()
```


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


Komponen y.

### add(FVector3 a, FVector3 b) {#add-com.aspose.threed.FVector3-com.aspose.threed.FVector3-}
```
public static FVector3 add(FVector3 a, FVector3 b)
```


+ Operator overload

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| a | [FVector3](../../com.aspose.threed/fvector3) | Vektor pertama |
| b | [FVector3](../../com.aspose.threed/fvector3) | Vektor kedua |

**Returns:**
[FVector3](../../com.aspose.threed/fvector3)
### clone() {#clone--}
```
public FVector3 clone()
```


Clone current instance

**Returns:**
[FVector3](../../com.aspose.threed/fvector3)
### copyFrom(FVector3 src) {#copyFrom-com.aspose.threed.FVector3-}
```
public void copyFrom(FVector3 src)
```




**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| src | [FVector3](../../com.aspose.threed/fvector3) |  |

### create(FVector3 v) {#create-com.aspose.threed.FVector3-}
```
public static Vector3 create(FVector3 v)
```


Operator konversi eksplisit untuk mengubah FVector3 menjadi Vector3

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| v | [FVector3](../../com.aspose.threed/fvector3) | Vector3 dalam tipe float |

**Returns:**
[Vector3](../../com.aspose.threed/vector3)
### cross(FVector3 rhs) {#cross-com.aspose.threed.FVector3-}
```
public FVector3 cross(FVector3 rhs)
```


Produk silang dari dua vektor.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| rhs | [FVector3](../../com.aspose.threed/fvector3) | Right hand side value. |

**Returns:**
[FVector3](../../com.aspose.threed/fvector3) - Cross product of two [FVector3](../../com.aspose.threed/fvector3)s.
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
### getOne() {#getOne--}
```
public static FVector3 getOne()
```


Vektor skala unit dengan semua komponen bernilai 1

**Returns:**
[FVector3](../../com.aspose.threed/fvector3) - The unit scale vector with all components are all 1
### getZero() {#getZero--}
```
public static FVector3 getZero()
```


Vektor Nol.

**Returns:**
[FVector3](../../com.aspose.threed/fvector3) - The Zero vector.
### hashCode() {#hashCode--}
```
public int hashCode()
```




**Returns:**
int
### mul(FVector3 a, float b) {#mul-com.aspose.threed.FVector3-float-}
```
public static FVector3 mul(FVector3 a, float b)
```


\* Operator overloading

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| a | [FVector3](../../com.aspose.threed/fvector3) | Vektor pertama |
| b | float | Vektor kedua |

**Returns:**
[FVector3](../../com.aspose.threed/fvector3) - The product of two vectors
### negative(FVector3 a) {#negative-com.aspose.threed.FVector3-}
```
public static FVector3 negative(FVector3 a)
```


- Operator overload

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| a | [FVector3](../../com.aspose.threed/fvector3) | Vektor masukan |

**Returns:**
[FVector3](../../com.aspose.threed/fvector3) - The negative vector
### normalize() {#normalize--}
```
public FVector3 normalize()
```


Normalizes this instance.

**Returns:**
[FVector3](../../com.aspose.threed/fvector3) - Normalized vector.
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### sub(FVector3 a, FVector3 b) {#sub-com.aspose.threed.FVector3-com.aspose.threed.FVector3-}
```
public static FVector3 sub(FVector3 a, FVector3 b)
```


- Operator overload

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| a | [FVector3](../../com.aspose.threed/fvector3) | Vektor pertama |
| b | [FVector3](../../com.aspose.threed/fvector3) | Vektor kedua |

**Returns:**
[FVector3](../../com.aspose.threed/fvector3) - The difference of two vectors
### toString() {#toString--}
```
public String toString()
```


Mengembalikan string yang merepresentasikan [FVector3](../../com.aspose.threed/fvector3)

**Returns:**
java.lang.String - Representasi string dari vektor ini.
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


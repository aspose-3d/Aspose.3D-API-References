---
title: FVector2
second_title: Referensi API Aspose.3D untuk Java
description: Vektor float dengan dua komponen.
type: docs
weight: 59
url: /id/java/com.aspose.threed/fvector2/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.threed.Struct, java.io.Serializable
```
public final class FVector2 implements Struct<FVector2>, Serializable
```

Vektor float dengan dua komponen.
## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [FVector2(float x, float y)](#FVector2-float-float-) | Menginisialisasi instance baru dari [FVector2](../../com.aspose.threed/fvector2). |
| [FVector2(Vector2 vec)](#FVector2-com.aspose.threed.Vector2-) | Menginisialisasi instance baru dari [FVector2](../../com.aspose.threed/fvector2). |
| [FVector2()](#FVector2--) |  |
## Bidang

| Bidang | Deskripsi |
| --- | --- |
| [x](#x) | Komponen x. |
| [y](#y) | Komponen y. |
## Metode

| Metode | Deskripsi |
| --- | --- |
| [add(FVector2 a, FVector2 b)](#add-com.aspose.threed.FVector2-com.aspose.threed.FVector2-) | + Operator overload |
| [clone()](#clone--) |  |
| [copyFrom(FVector2 src)](#copyFrom-com.aspose.threed.FVector2-) |  |
| [create(FVector2 v)](#create-com.aspose.threed.FVector2-) | Operator konversi eksplisit untuk mengubah FVector2 menjadi Vector2 |
| [equals(FVector2 rhs)](#equals-com.aspose.threed.FVector2-) | Periksa apakah dua vektor sama |
| [equals(Object obj)](#equals-java.lang.Object-) | Periksa apakah dua vektor sama |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) | Mendapatkan kode hash dari instance ini |
| [mul(FVector2 a, float b)](#mul-com.aspose.threed.FVector2-float-) | * Operator overload |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [op_eq(FVector2 a, FVector2 b)](#op-eq-com.aspose.threed.FVector2-com.aspose.threed.FVector2-) | == Operator overload |
| [op_ne(FVector2 a, FVector2 b)](#op-ne-com.aspose.threed.FVector2-com.aspose.threed.FVector2-) | != Operator overload |
| [sub(FVector2 a, FVector2 b)](#sub-com.aspose.threed.FVector2-com.aspose.threed.FVector2-) | - Operator overload |
| [toString()](#toString--) | Mengembalikan string yang merepresentasikan [FVector2](../../com.aspose.threed/fvector2) |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### FVector2(float x, float y) {#FVector2-float-float-}
```
public FVector2(float x, float y)
```


Menginisialisasi instance baru dari [FVector2](../../com.aspose.threed/fvector2).

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| x | float | Komponen X dari vektor |
| y | float | Komponen Y dari vektor |

### FVector2(Vector2 vec) {#FVector2-com.aspose.threed.Vector2-}
```
public FVector2(Vector2 vec)
```


Menginisialisasi instance baru dari [FVector2](../../com.aspose.threed/fvector2).

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| vec | [Vector2](../../com.aspose.threed/vector2) | Vector2 dalam tipe double |

### FVector2() {#FVector2--}
```
public FVector2()
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

### add(FVector2 a, FVector2 b) {#add-com.aspose.threed.FVector2-com.aspose.threed.FVector2-}
```
public static FVector2 add(FVector2 a, FVector2 b)
```


+ Operator overload

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| a | [FVector2](../../com.aspose.threed/fvector2) | Vektor pertama |
| b | [FVector2](../../com.aspose.threed/fvector2) | Vektor kedua |

**Returns:**
[FVector2](../../com.aspose.threed/fvector2) - The sum of two vectors.
### clone() {#clone--}
```
public FVector2 clone()
```


Clone current instance

**Returns:**
[FVector2](../../com.aspose.threed/fvector2)
### copyFrom(FVector2 src) {#copyFrom-com.aspose.threed.FVector2-}
```
public void copyFrom(FVector2 src)
```




**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| src | [FVector2](../../com.aspose.threed/fvector2) |  |

### create(FVector2 v) {#create-com.aspose.threed.FVector2-}
```
public static Vector2 create(FVector2 v)
```


Operator konversi eksplisit untuk mengubah FVector2 menjadi Vector2

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| v | [FVector2](../../com.aspose.threed/fvector2) | Vector 2 dalam tipe float. |

**Returns:**
[Vector2](../../com.aspose.threed/vector2)
### equals(FVector2 rhs) {#equals-com.aspose.threed.FVector2-}
```
public boolean equals(FVector2 rhs)
```


Periksa apakah dua vektor sama

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| rhs | [FVector2](../../com.aspose.threed/fvector2) |  |

**Returns:**
boolean - True jika semua komponen sama.
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
boolean - True jika input adalah vektor dan semua komponen sama.
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


Mendapatkan kode hash dari instance ini

**Returns:**
int - Kode hash dari vektor.
### mul(FVector2 a, float b) {#mul-com.aspose.threed.FVector2-float-}
```
public static FVector2 mul(FVector2 a, float b)
```


* Operator overload

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| a | [FVector2](../../com.aspose.threed/fvector2) | Vektor pertama |
| b | float | Vektor kedua |

**Returns:**
[FVector2](../../com.aspose.threed/fvector2) - The product of two vectors.
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### op_eq(FVector2 a, FVector2 b) {#op-eq-com.aspose.threed.FVector2-com.aspose.threed.FVector2-}
```
public static boolean op_eq(FVector2 a, FVector2 b)
```


== Operator overload

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| a | [FVector2](../../com.aspose.threed/fvector2) | Vektor pertama |
| b | [FVector2](../../com.aspose.threed/fvector2) | Vektor kedua |

**Returns:**
boolean - True jika semua komponen sama.
### op_ne(FVector2 a, FVector2 b) {#op-ne-com.aspose.threed.FVector2-com.aspose.threed.FVector2-}
```
public static boolean op_ne(FVector2 a, FVector2 b)
```


!= Operator overloading

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| a | [FVector2](../../com.aspose.threed/fvector2) | Vektor pertama |
| b | [FVector2](../../com.aspose.threed/fvector2) | Vektor kedua |

**Returns:**
boolean - True jika ada komponen yang berbeda.
### sub(FVector2 a, FVector2 b) {#sub-com.aspose.threed.FVector2-com.aspose.threed.FVector2-}
```
public static FVector2 sub(FVector2 a, FVector2 b)
```


- Operator overload

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| a | [FVector2](../../com.aspose.threed/fvector2) | Vektor pertama |
| b | [FVector2](../../com.aspose.threed/fvector2) | Vektor kedua |

**Returns:**
[FVector2](../../com.aspose.threed/fvector2) - The difference of two vectors.
### toString() {#toString--}
```
public String toString()
```


Mengembalikan string yang merepresentasikan [FVector2](../../com.aspose.threed/fvector2)

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


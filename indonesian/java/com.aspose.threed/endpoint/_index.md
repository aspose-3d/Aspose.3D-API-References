---
title: EndPoint
second_title: Referensi API Aspose.3D untuk Java
description: Titik akhir untuk memotong kurva dapat berupa nilai parameter atau titik Kartesian.
type: docs
weight: 51
url: /id/java/com.aspose.threed/endpoint/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.threed.Struct, java.io.Serializable
```
public final class EndPoint implements Struct<EndPoint>, Serializable
```

Titik akhir untuk memotong kurva, dapat berupa nilai parameter atau titik Kartesian.
## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [EndPoint(Vector3 point)](#EndPoint-com.aspose.threed.Vector3-) | Bangun sebuah [EndPoint](../../com.aspose.threed/endpoint) dari titik Kartesian. |
| [EndPoint(double v)](#EndPoint-double-) | Bangun sebuah [EndPoint](../../com.aspose.threed/endpoint) dari parameter real. |
| [EndPoint()](#EndPoint--) |  |
## Metode

| Metode | Deskripsi |
| --- | --- |
| [clone()](#clone--) |  |
| [copyFrom(EndPoint src)](#copyFrom-com.aspose.threed.EndPoint-) |  |
| [equals(Object obj)](#equals-java.lang.Object-) |  |
| [fromDegree(double degree)](#fromDegree-double-) | Buat titik akhir yang diukur dalam derajat. |
| [fromRadian(double degree)](#fromRadian-double-) | Buat titik akhir yang diukur dalam radian. |
| [getAsPoint()](#getAsPoint--) | Mendapatkan titik akhir sebagai titik Kartesian, atau melemparkan pengecualian. |
| [getAsValue()](#getAsValue--) | Mendapatkan titik akhir sebagai parameter real, atau melempar pengecualian. |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) |  |
| [isCartesianPoint()](#isCartesianPoint--) | Apakah titik akhir merupakan titik Kartesian? |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) | Mengembalikan representasi string dari titik akhir saat ini. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### EndPoint(Vector3 point) {#EndPoint-com.aspose.threed.Vector3-}
```
public EndPoint(Vector3 point)
```


Bangun sebuah [EndPoint](../../com.aspose.threed/endpoint) dari titik Kartesian.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| point | [Vector3](../../com.aspose.threed/vector3) | Titik untuk dibangun |

### EndPoint(double v) {#EndPoint-double-}
```
public EndPoint(double v)
```


Bangun sebuah [EndPoint](../../com.aspose.threed/endpoint) dari parameter real.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| v | double | Parameter bilangan real untuk membangun titik akhir |

### EndPoint() {#EndPoint--}
```
public EndPoint()
```


### clone() {#clone--}
```
public EndPoint clone()
```


Clone current instance

**Returns:**
[EndPoint](../../com.aspose.threed/endpoint)
### copyFrom(EndPoint src) {#copyFrom-com.aspose.threed.EndPoint-}
```
public void copyFrom(EndPoint src)
```




**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| src | [EndPoint](../../com.aspose.threed/endpoint) |  |

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
### fromDegree(double degree) {#fromDegree-double-}
```
public static EndPoint fromDegree(double degree)
```


Buat titik akhir yang diukur dalam derajat.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| derajat | double | Nilai dalam derajat |

**Returns:**
[EndPoint](../../com.aspose.threed/endpoint) - An end point constructed from degree
### fromRadian(double degree) {#fromRadian-double-}
```
public static EndPoint fromRadian(double degree)
```


Buat titik akhir yang diukur dalam radian.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| derajat | double | Nilai dalam radian |

**Returns:**
[EndPoint](../../com.aspose.threed/endpoint) - An end point constructed from radian
### getAsPoint() {#getAsPoint--}
```
public Vector3 getAsPoint()
```


Mendapatkan titik akhir sebagai titik Kartesian, atau melemparkan pengecualian.

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - the end point as Cartesian point, or thrown an exception.
### getAsValue() {#getAsValue--}
```
public double getAsValue()
```


Mendapatkan titik akhir sebagai parameter real, atau melempar pengecualian.

**Returns:**
double - titik akhir sebagai parameter real, atau melempar pengecualian.
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
### isCartesianPoint() {#isCartesianPoint--}
```
public boolean isCartesianPoint()
```


Apakah titik akhir merupakan titik Kartesian?

**Returns:**
boolean - Apakah titik akhir merupakan titik Kartesian?
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### toString() {#toString--}
```
public String toString()
```


Mengembalikan representasi string dari titik akhir saat ini.

**Returns:**
java.lang.String
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


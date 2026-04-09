---
title: NurbsDirection
second_title: Referensi API Aspose.3D untuk Java
description: Sebuah 3D  memiliki dua arah,  dan ,  mendefinisikan data untuk setiap arah.
type: docs
weight: 113
url: /id/java/com.aspose.threed/nurbsdirection/
---

**Inheritance:**
java.lang.Object
```
public class NurbsDirection
```

Sebuah 3D [NurbsSurface](../../com.aspose.threed/nurbssurface) memiliki dua arah, yaitu [NurbsSurface.getU](../../com.aspose.threed/nurbssurface\#getU) dan [NurbsSurface.getV](../../com.aspose.threed/nurbssurface\#getV), [NurbsDirection](../../com.aspose.threed/nurbsdirection) mendefinisikan data untuk setiap arah. Sebuah arah sebenarnya adalah kurva NURBS, yang berarti juga didefinisikan oleh [getOrder](../../com.aspose.threed/nurbsdirection\#getOrder), sebuah [getKnotVectors](../../com.aspose.threed/nurbsdirection\#getKnotVectors), dan sekumpulan titik kontrol berbobot (didefinisikan dalam [NurbsSurface](../../com.aspose.threed/nurbssurface)).
## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [NurbsDirection()](#NurbsDirection--) | Membuat instance baru dari [NurbsDirection](../../com.aspose.threed/nurbsdirection) |
## Metode

| Metode | Deskripsi |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getCount()](#getCount--) | Mendapatkan jumlah titik kontrol dalam arah saat ini. |
| [getDegree()](#getDegree--) | Mendapatkan derajat kurva NURBS, derajat didefinisikan sebagai Order - 1 |
| [getDivisions()](#getDivisions--) | Mendapatkan jumlah pembagian antara titik kontrol berdekatan dalam arah saat ini. |
| [getKnotVectors()](#getKnotVectors--) | Mendapatkan vektor knot, yaitu urutan nilai parameter yang menentukan di mana dan bagaimana titik kontrol memengaruhi kurva NURBS. |
| [getMultiplicity()](#getMultiplicity--) | Mendapatkan multiplikitas. |
| [getOrder()](#getOrder--) | Mendapatkan order kurva NURBS, yang menentukan jumlah titik kontrol terdekat yang memengaruhi setiap titik pada kurva. |
| [getType()](#getType--) | Mendapatkan tipe arah saat ini. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setCount(int value)](#setCount-int-) | Mengatur jumlah titik kontrol dalam arah saat ini. |
| [setDegree(int value)](#setDegree-int-) | Mengatur derajat kurva NURBS, derajat didefinisikan sebagai Order - 1 |
| [setDivisions(int value)](#setDivisions-int-) | Mengatur jumlah pembagian antara titik kontrol berdekatan dalam arah saat ini. |
| [setOrder(int value)](#setOrder-int-) | Mengatur order kurva NURBS, yang menentukan jumlah titik kontrol terdekat yang memengaruhi setiap titik pada kurva. |
| [setType(NurbsType value)](#setType-com.aspose.threed.NurbsType-) | Mengatur tipe arah saat ini. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### NurbsDirection() {#NurbsDirection--}
```
public NurbsDirection()
```


Membuat instance baru dari [NurbsDirection](../../com.aspose.threed/nurbsdirection)

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getCount() {#getCount--}
```
public int getCount()
```


Mendapatkan jumlah titik kontrol dalam arah saat ini.

**Returns:**
int - jumlah titik kontrol dalam arah saat ini.
### getDegree() {#getDegree--}
```
public int getDegree()
```


Mendapatkan derajat kurva NURBS, derajat didefinisikan sebagai Order - 1

**Returns:**
int - derajat kurva NURBS, derajat didefinisikan sebagai Order - 1
### getDivisions() {#getDivisions--}
```
public int getDivisions()
```


Mendapatkan jumlah pembagian antara titik kontrol berdekatan dalam arah saat ini.

**Returns:**
int - jumlah pembagian antara titik kontrol berdekatan dalam arah saat ini.
### getKnotVectors() {#getKnotVectors--}
```
public List<Double> getKnotVectors()
```


Mendapatkan vektor knot, yaitu urutan nilai parameter yang menentukan di mana dan bagaimana titik kontrol memengaruhi kurva NURBS.

**Returns:**
java.util.List<java.lang.Double> - vektor knot, yaitu urutan nilai parameter yang menentukan di mana dan bagaimana titik kontrol memengaruhi kurva NURBS.
### getMultiplicity() {#getMultiplicity--}
```
public List<Integer> getMultiplicity()
```


Mendapatkan multiplikitas.

**Returns:**
java.util.List<java.lang.Integer> - multiplikasi.
### getOrder() {#getOrder--}
```
public int getOrder()
```


Mendapatkan order kurva NURBS, yang menentukan jumlah titik kontrol terdekat yang memengaruhi setiap titik pada kurva.

**Returns:**
int - urutan kurva NURBS, yang menentukan jumlah titik kontrol terdekat yang memengaruhi setiap titik pada kurva.
### getType() {#getType--}
```
public NurbsType getType()
```


Mendapatkan tipe arah saat ini.

**Returns:**
[NurbsType](../../com.aspose.threed/nurbstype) - the type of the current direction.
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setCount(int value) {#setCount-int-}
```
public void setCount(int value)
```


Mengatur jumlah titik kontrol dalam arah saat ini.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int | Nilai baru |

### setDegree(int value) {#setDegree-int-}
```
public void setDegree(int value)
```


Mengatur derajat kurva NURBS, derajat didefinisikan sebagai Order - 1

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int | Nilai baru |

### setDivisions(int value) {#setDivisions-int-}
```
public void setDivisions(int value)
```


Mengatur jumlah pembagian antara titik kontrol berdekatan dalam arah saat ini.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int | Nilai baru |

### setOrder(int value) {#setOrder-int-}
```
public void setOrder(int value)
```


Mengatur order kurva NURBS, yang menentukan jumlah titik kontrol terdekat yang memengaruhi setiap titik pada kurva.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int | Nilai baru |

### setType(NurbsType value) {#setType-com.aspose.threed.NurbsType-}
```
public void setType(NurbsType value)
```


Mengatur tipe arah saat ini.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [NurbsType](../../com.aspose.threed/nurbstype) | Nilai baru |

### toString() {#toString--}
```
public String toString()
```




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


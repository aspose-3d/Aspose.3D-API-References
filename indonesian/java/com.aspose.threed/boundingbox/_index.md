---
title: BoundingBox
second_title: Referensi API Aspose.3D untuk Java
description: Bounding box yang sejajar sumbu Contoh  Kode berikut menunjukkan cara mendapatkan bounding box dari instance Entity.
type: docs
weight: 24
url: /id/java/com.aspose.threed/boundingbox/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.threed.Struct, java.io.Serializable
```
public final class BoundingBox implements Struct<BoundingBox>, Serializable
```

Kotak pembatas yang sejajar sumbu **Contoh:** Kode berikut menunjukkan cara mendapatkan kotak pembatas dari sebuah instance Entity.

```
var sphere = new Sphere();
      var boundingBox = sphere.getBoundingBox();
      System.out.println("Bounding box = " + boundingBox);
```
## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [BoundingBox(Vector3 minimum, Vector3 maximum)](#BoundingBox-com.aspose.threed.Vector3-com.aspose.threed.Vector3-) | Inisialisasi kotak pembatas berhingga dengan sudut minimum dan maksimum yang diberikan |
| [BoundingBox(double minX, double minY, double minZ, double maxX, double maxY, double maxZ)](#BoundingBox-double-double-double-double-double-double-) | Inisialisasi kotak pembatas berhingga dengan sudut minimum dan maksimum yang diberikan |
| [BoundingBox()](#BoundingBox--) |  |
## Metode

| Metode | Deskripsi |
| --- | --- |
| [clone()](#clone--) |  |
| [contains(BoundingBox bbox)](#contains-com.aspose.threed.BoundingBox-) | Bounding box untuk memeriksa apakah berada di dalam bounding box saat ini. |
| [contains(Vector3 p)](#contains-com.aspose.threed.Vector3-) | Periksa apakah titik p berada di dalam bounding box |
| [copyFrom(BoundingBox src)](#copyFrom-com.aspose.threed.BoundingBox-) |  |
| [equals(Object obj)](#equals-java.lang.Object-) | Menentukan apakah dua objek sama |
| [fromGeometry(Geometry geometry)](#fromGeometry-com.aspose.threed.Geometry-) | Membuat bounding box dari geometri yang diberikan |
| [getCenter()](#getCenter--) | Pusat bounding box. |
| [getClass()](#getClass--) |  |
| [getExtent()](#getExtent--) | Mendapatkan rentang kotak pembatas. |
| [getInfinite()](#getInfinite--) | Kotak pembatas tak terbatas |
| [getMaximum()](#getMaximum--) | Sudut maksimum kotak pembatas |
| [getMinimum()](#getMinimum--) | Sudut minimum kotak pembatas |
| [getNull()](#getNull--) | Kotak pembatas null |
| [getSize()](#getSize--) | Ukuran bounding box |
| [hashCode()](#hashCode--) | Mengembalikan kode hash untuk instance ini |
| [merge(BoundingBox bb)](#merge-com.aspose.threed.BoundingBox-) | Menggabungkan kotak baru ke dalam kotak pembatas saat ini. |
| [merge(Vector3 pt)](#merge-com.aspose.threed.Vector3-) | Gabungkan bounding box saat ini dengan titik yang diberikan |
| [merge(Vector4 pt)](#merge-com.aspose.threed.Vector4-) | Gabungkan bounding box saat ini dengan titik yang diberikan |
| [merge(double x, double y, double z)](#merge-double-double-double-) | Gabungkan bounding box saat ini dengan titik yang diberikan |
| [mul(BoundingBox bbox, Matrix4 mat)](#mul-com.aspose.threed.BoundingBox-com.aspose.threed.Matrix4-) | Overloading operator untuk perkalian, sudut minimum dan maksimum bounding box baru akan ditransformasi oleh matriks. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [overlapsWith(BoundingBox box)](#overlapsWith-com.aspose.threed.BoundingBox-) | Periksa apakah bounding box saat ini tumpang tindih dengan bounding box yang ditentukan. |
| [scale()](#scale--) | Menghitung nilai koordinat terbesar secara absolut dari setiap titik yang terkandung. |
| [toString()](#toString--) | Mendapatkan representasi string dari kotak pembatas. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### BoundingBox(Vector3 minimum, Vector3 maximum) {#BoundingBox-com.aspose.threed.Vector3-com.aspose.threed.Vector3-}
```
public BoundingBox(Vector3 minimum, Vector3 maximum)
```


Inisialisasi kotak pembatas berhingga dengan sudut minimum dan maksimum yang diberikan

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| minimum | [Vector3](../../com.aspose.threed/vector3) | Sudut minimum |
|  | maximum | [Vector3](../../com.aspose.threed/vector3) | Sudut maksimum **Example:** Kode berikut menunjukkan cara membuat bounding box dari sudut minimum dan maksimum. |

```
var minimum = new Vector3(0, 0, 0);
  var maximum = new Vector3(10, 10, 10);
  var boundingBox = new BoundingBox(minimum, maximum);
  System.out.println("Bounding box = " + boundingBox);
``` |

### BoundingBox(double minX, double minY, double minZ, double maxX, double maxY, double maxZ) {#BoundingBox-double-double-double-double-double-double-}
```
public BoundingBox(double minX, double minY, double minZ, double maxX, double maxY, double maxZ)
```


Inisialisasi kotak pembatas berhingga dengan sudut minimum dan maksimum yang diberikan

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| minX | double | X sudut minimum |
| minY | double | Sudut minimum Y |
| minZ | double | Sudut minimum Z |
| maxX | double | Sudut maksimum X |
| maxY | double | Sudut maksimum Y |
|  | maxZ | double | Sudut maksimum Z **Contoh:** Kode berikut menunjukkan cara membuat kotak pembatas dari sudut minimum dan maksimum. |

```
var boundingBox = new BoundingBox(0, 0, 0, 10, 10, 10);
  System.out.println("Bounding box = " + boundingBox);
``` |

### BoundingBox() {#BoundingBox--}
```
public BoundingBox()
```


### clone() {#clone--}
```
public BoundingBox clone()
```


Clone current instance

**Returns:**
[BoundingBox](../../com.aspose.threed/boundingbox)
### contains(BoundingBox bbox) {#contains-com.aspose.threed.BoundingBox-}
```
public boolean contains(BoundingBox bbox)
```


Bounding box untuk memeriksa apakah berada di dalam bounding box saat ini.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| bbox | [BoundingBox](../../com.aspose.threed/boundingbox) |  |

**Returns:**
boolean
### contains(Vector3 p) {#contains-com.aspose.threed.Vector3-}
```
public boolean contains(Vector3 p)
```


Periksa apakah titik p berada di dalam bounding box

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| p | [Vector3](../../com.aspose.threed/vector3) | Titik untuk diuji |

**Returns:**
boolean - Benar jika titik berada di dalam kotak pembatas **Contoh:** Kode berikut menunjukkan cara memeriksa apakah titik berada di dalam kotak pembatas.

```
var boundingBox = new BoundingBox(0, 0, 0, 10, 10, 10);
  var pt = new Vector3(4, 4, 4);
  System.out.println("Bounding box overlaps = " + boundingBox.contains(pt));
```
### copyFrom(BoundingBox src) {#copyFrom-com.aspose.threed.BoundingBox-}
```
public void copyFrom(BoundingBox src)
```




**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| src | [BoundingBox](../../com.aspose.threed/boundingbox) |  |

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Menentukan apakah dua objek sama

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| obj | java.lang.Object | Objek untuk dibandingkan |

**Returns:**
boolean - true jika dua objek sama
### fromGeometry(Geometry geometry) {#fromGeometry-com.aspose.threed.Geometry-}
```
public static BoundingBox fromGeometry(Geometry geometry)
```


Membuat bounding box dari geometri yang diberikan

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| geometry | [Geometry](../../com.aspose.threed/geometry) | Geometri untuk menghitung kotak pembatas |

**Returns:**
[BoundingBox](../../com.aspose.threed/boundingbox) - The bounding box of given geometry **Example:** The following code shows how to construct a bounding box from a geometry instance.

```
var sphere = (new Sphere()).toMesh();
  var boundingBox = BoundingBox.fromGeometry(sphere);
  System.out.println("Bounding box = " + boundingBox);
```
### getCenter() {#getCenter--}
```
public Vector3 getCenter()
```


Pusat bounding box.

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - The center of the bounding box.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getExtent() {#getExtent--}
```
public BoundingBoxExtent getExtent()
```


Mendapatkan rentang kotak pembatas.

**Returns:**
[BoundingBoxExtent](../../com.aspose.threed/boundingboxextent) - the extent of the bounding box.
### getInfinite() {#getInfinite--}
```
public static BoundingBox getInfinite()
```


Kotak pembatas tak terbatas

**Returns:**
[BoundingBox](../../com.aspose.threed/boundingbox) - The infinite bounding box
### getMaximum() {#getMaximum--}
```
public Vector3 getMaximum()
```


Sudut maksimum kotak pembatas

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - The maximum corner of the bounding box
### getMinimum() {#getMinimum--}
```
public Vector3 getMinimum()
```


Sudut minimum kotak pembatas

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - The minimum corner of the bounding box
### getNull() {#getNull--}
```
public static BoundingBox getNull()
```


Kotak pembatas null

**Returns:**
[BoundingBox](../../com.aspose.threed/boundingbox) - The null bounding box
### getSize() {#getSize--}
```
public Vector3 getSize()
```


Ukuran bounding box

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - The size of the bounding box
### hashCode() {#hashCode--}
```
public int hashCode()
```


Mengembalikan kode hash untuk instance ini

**Returns:**
int - Kode hash dari kotak pembatas
### merge(BoundingBox bb) {#merge-com.aspose.threed.BoundingBox-}
```
public void merge(BoundingBox bb)
```


Menggabungkan kotak baru ke dalam kotak pembatas saat ini.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| bb | [BoundingBox](../../com.aspose.threed/boundingbox) | Kotak pembatas untuk digabungkan |

### merge(Vector3 pt) {#merge-com.aspose.threed.Vector3-}
```
public void merge(Vector3 pt)
```


Gabungkan bounding box saat ini dengan titik yang diberikan

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | pt | [Vector3](../../com.aspose.threed/vector3) | Titik yang akan digabungkan ke dalam kotak pembatas **Contoh:** Kode berikut menunjukkan cara menggabungkan titik ke kotak pembatas. |

```
var boundingBox = BoundingBox.getNull();
  boundingBox.Merge(new Vector3(1, 10, -1));
  System.out.println("Bounding box = " + boundingBox);
``` |

### merge(Vector4 pt) {#merge-com.aspose.threed.Vector4-}
```
public void merge(Vector4 pt)
```


Gabungkan bounding box saat ini dengan titik yang diberikan

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | pt | [Vector4](../../com.aspose.threed/vector4) | Titik yang akan digabungkan ke dalam kotak pembatas **Contoh:** Kode berikut menunjukkan cara menggabungkan titik ke kotak pembatas. |

```
var boundingBox = BoundingBox.getNull();
  boundingBox.Merge(new Vector4(1, 10, -1));
  System.out.println("Bounding box = " + boundingBox);
``` |

### merge(double x, double y, double z) {#merge-double-double-double-}
```
public void merge(double x, double y, double z)
```


Gabungkan bounding box saat ini dengan titik yang diberikan

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| x | double | Titik yang akan digabungkan ke dalam kotak pembatas |
| y | double | Titik yang akan digabungkan ke dalam kotak pembatas |
|  | z | double | Titik yang akan digabungkan ke dalam kotak pembatas **Contoh:** Kode berikut menunjukkan cara menggabungkan titik ke kotak pembatas. |

```
var boundingBox = BoundingBox.getNull();
  boundingBox.Merge(1, 10, -1);
  System.out.println("Bounding box = " + boundingBox);
``` |

### mul(BoundingBox bbox, Matrix4 mat) {#mul-com.aspose.threed.BoundingBox-com.aspose.threed.Matrix4-}
```
public static BoundingBox mul(BoundingBox bbox, Matrix4 mat)
```


Overloading operator untuk perkalian, sudut minimum dan maksimum bounding box baru akan ditransformasi oleh matriks.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| bbox | [BoundingBox](../../com.aspose.threed/boundingbox) | Kotak pembatas input. |
| mat | [Matrix4](../../com.aspose.threed/matrix4) | Matriks yang digunakan untuk mentransformasi sudut-sudut kotak pembatas |

**Returns:**
[BoundingBox](../../com.aspose.threed/boundingbox) - The product of bounding box and transform matrix.
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### overlapsWith(BoundingBox box) {#overlapsWith-com.aspose.threed.BoundingBox-}
```
public boolean overlapsWith(BoundingBox box)
```


Periksa apakah bounding box saat ini tumpang tindih dengan bounding box yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| box | [BoundingBox](../../com.aspose.threed/boundingbox) | Kotak pembatas lain untuk diuji |

**Returns:**
boolean - Benar jika kotak pembatas saat ini tumpang tindih dengan yang diberikan. **Contoh:** Kode berikut menunjukkan cara memeriksa apakah dua kotak pembatas tumpang tindih satu sama lain.

```
var boundingBox = new BoundingBox(0, 0, 0, 10, 10, 10);
  var bbox2 = new BoundingBox(1, 1, 1, 11, 11, 11);
  System.out.println("Bounding box overlaps = " + boundingBox.overlapsWith(bbox2));
```
### scale() {#scale--}
```
public double scale()
```


Menghitung nilai koordinat terbesar secara absolut dari setiap titik yang terkandung.

**Returns:**
double - nilai koordinat absolut terbesar yang dihitung dari setiap titik yang terkandung.
### toString() {#toString--}
```
public String toString()
```


Mendapatkan representasi string dari kotak pembatas.

**Returns:**
java.lang.String - Representasi string dari kotak pembatas.
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


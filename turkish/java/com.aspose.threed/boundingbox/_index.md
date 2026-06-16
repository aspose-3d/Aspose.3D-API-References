---
title: "BoundingBox"
second_title: "Aspose.3D for Java API Referansı"
description: "Eksen hizalı sınırlama kutusu Örnek  Aşağıdaki kod, bir Entity örneğinden sınırlama kutusu almanın nasıl yapılacağını gösterir."
type: docs
weight: 24
url: /tr/java/com.aspose.threed/boundingbox/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.threed.Struct, java.io.Serializable
```
public final class BoundingBox implements Struct<BoundingBox>, Serializable
```

Eksen hizalı sınırlayıcı kutu **Örnek:** Aşağıdaki kod, bir Entity örneğinden sınırlayıcı kutu nasıl alınacağını gösterir.

```
var sphere = new Sphere();
      var boundingBox = sphere.getBoundingBox();
      System.out.println("Bounding box = " + boundingBox);
```
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [BoundingBox(Vector3 minimum, Vector3 maximum)](#BoundingBox-com.aspose.threed.Vector3-com.aspose.threed.Vector3-) | Verilen minimum ve maksimum köşe ile sonlu bir sınırlayıcı kutu başlatın |
| [BoundingBox(double minX, double minY, double minZ, double maxX, double maxY, double maxZ)](#BoundingBox-double-double-double-double-double-double-) | Verilen minimum ve maksimum köşe ile sonlu bir sınırlayıcı kutu başlatın |
| [BoundingBox()](#BoundingBox--) |  |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [clone()](#clone--) |  |
| [contains(BoundingBox bbox)](#contains-com.aspose.threed.BoundingBox-) | Mevcut sınırlama kutusunun içinde olup olmadığını kontrol etmek için sınırlama kutusu. |
| [contains(Vector3 p)](#contains-com.aspose.threed.Vector3-) | p noktasının sınırlama kutusunun içinde olup olmadığını kontrol et |
| [copyFrom(BoundingBox src)](#copyFrom-com.aspose.threed.BoundingBox-) |  |
| [equals(Object obj)](#equals-java.lang.Object-) | İki nesnenin eşit olup olmadığını belirler |
| [fromGeometry(Geometry geometry)](#fromGeometry-com.aspose.threed.Geometry-) | Verilen geometriden bir sınırlama kutusu oluştur |
| [getCenter()](#getCenter--) | Sınırlama kutusunun merkezi. |
| [getClass()](#getClass--) |  |
| [getExtent()](#getExtent--) | Sınırlayıcı kutunun kapsamını alır. |
| [getInfinite()](#getInfinite--) | Sonsuz sınırlayıcı kutu |
| [getMaximum()](#getMaximum--) | Sınırlayıcı kutunun maksimum köşesi |
| [getMinimum()](#getMinimum--) | Sınırlayıcı kutunun minimum köşesi |
| [getNull()](#getNull--) | Boş sınırlayıcı kutu |
| [getSize()](#getSize--) | Sınırlama kutusunun boyutu |
| [hashCode()](#hashCode--) | Bu örnek için hash kodunu döndürür |
| [merge(BoundingBox bb)](#merge-com.aspose.threed.BoundingBox-) | Yeni kutuyu mevcut sınırlayıcı kutuya birleştirir. |
| [merge(Vector3 pt)](#merge-com.aspose.threed.Vector3-) | Mevcut sınırlama kutusunu verilen nokta ile birleştir |
| [merge(Vector4 pt)](#merge-com.aspose.threed.Vector4-) | Mevcut sınırlama kutusunu verilen nokta ile birleştir |
| [merge(double x, double y, double z)](#merge-double-double-double-) | Mevcut sınırlama kutusunu verilen nokta ile birleştir |
| [mul(BoundingBox bbox, Matrix4 mat)](#mul-com.aspose.threed.BoundingBox-com.aspose.threed.Matrix4-) | Çarpma için operatör aşırı yüklemesi, yeni sınırlama kutusunun minimum ve maksimum köşeleri matris tarafından dönüştürülecek. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [overlapsWith(BoundingBox box)](#overlapsWith-com.aspose.threed.BoundingBox-) | Mevcut sınırlama kutusunun belirtilen sınırlama kutusuyla çakışıp çakışmadığını kontrol et. |
| [scale()](#scale--) | İçerilen herhangi bir noktanın mutlak en büyük koordinat değerini hesaplar. |
| [toString()](#toString--) | Sınırlayıcı kutunun dize temsilini alır. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### BoundingBox(Vector3 minimum, Vector3 maximum) {#BoundingBox-com.aspose.threed.Vector3-com.aspose.threed.Vector3-}
```
public BoundingBox(Vector3 minimum, Vector3 maximum)
```


Verilen minimum ve maksimum köşe ile sonlu bir sınırlayıcı kutu başlatın

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| minimum | [Vector3](../../com.aspose.threed/vector3) | Minimum köşe |
|  | maximum | [Vector3](../../com.aspose.threed/vector3) | Maksimum köşe **Example:** Aşağıdaki kod, minimum ve maksimum köşelerden bir sınırlama kutusu oluşturmanın nasıl yapılacağını gösterir. |

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


Verilen minimum ve maksimum köşe ile sonlu bir sınırlayıcı kutu başlatın

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| minX | double | Minimum köşenin X'i |
| minY | double | Minimum köşenin Y |
| minZ | double | Minimum köşenin Z |
| maxX | double | Maksimum köşenin X |
| maxY | double | Maksimum köşenin Y |
|  | maxZ | double | Maksimum köşenin Z **Example:** Aşağıdaki kod, minimum ve maksimum köşelerden bir sınırlama kutusu nasıl oluşturulacağını gösterir. |

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


Mevcut örneği kopyala

**Returns:**
[BoundingBox](../../com.aspose.threed/boundingbox)
### contains(BoundingBox bbox) {#contains-com.aspose.threed.BoundingBox-}
```
public boolean contains(BoundingBox bbox)
```


Mevcut sınırlama kutusunun içinde olup olmadığını kontrol etmek için sınırlama kutusu.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| bbox | [BoundingBox](../../com.aspose.threed/boundingbox) |  |

**Returns:**
boolean
### contains(Vector3 p) {#contains-com.aspose.threed.Vector3-}
```
public boolean contains(Vector3 p)
```


p noktasının sınırlama kutusunun içinde olup olmadığını kontrol et

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| p | [Vector3](../../com.aspose.threed/vector3) | Test edilecek nokta |

**Returns:**
boolean - Nokta sınırlama kutusunun içinde ise True **Example:** Aşağıdaki kod, bir noktanın sınırlama kutusunun içinde olup olmadığını nasıl kontrol edeceğini gösterir.

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
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| src | [BoundingBox](../../com.aspose.threed/boundingbox) |  |

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


İki nesnenin eşit olup olmadığını belirler

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| obj | java.lang.Object | Karşılaştırılacak nesne |

**Returns:**
boolean - iki nesne eşitse true
### fromGeometry(Geometry geometry) {#fromGeometry-com.aspose.threed.Geometry-}
```
public static BoundingBox fromGeometry(Geometry geometry)
```


Verilen geometriden bir sınırlama kutusu oluştur

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| geometry | [Geometry](../../com.aspose.threed/geometry) | Sınırlama kutusunu hesaplamak için geometri |

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


Sınırlama kutusunun merkezi.

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


Sınırlayıcı kutunun kapsamını alır.

**Returns:**
[BoundingBoxExtent](../../com.aspose.threed/boundingboxextent) - the extent of the bounding box.
### getInfinite() {#getInfinite--}
```
public static BoundingBox getInfinite()
```


Sonsuz sınırlayıcı kutu

**Returns:**
[BoundingBox](../../com.aspose.threed/boundingbox) - The infinite bounding box
### getMaximum() {#getMaximum--}
```
public Vector3 getMaximum()
```


Sınırlayıcı kutunun maksimum köşesi

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - The maximum corner of the bounding box
### getMinimum() {#getMinimum--}
```
public Vector3 getMinimum()
```


Sınırlayıcı kutunun minimum köşesi

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - The minimum corner of the bounding box
### getNull() {#getNull--}
```
public static BoundingBox getNull()
```


Boş sınırlayıcı kutu

**Returns:**
[BoundingBox](../../com.aspose.threed/boundingbox) - The null bounding box
### getSize() {#getSize--}
```
public Vector3 getSize()
```


Sınırlama kutusunun boyutu

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - The size of the bounding box
### hashCode() {#hashCode--}
```
public int hashCode()
```


Bu örnek için hash kodunu döndürür

**Returns:**
int - Sınırlama kutusunun hash kodu
### merge(BoundingBox bb) {#merge-com.aspose.threed.BoundingBox-}
```
public void merge(BoundingBox bb)
```


Yeni kutuyu mevcut sınırlayıcı kutuya birleştirir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| bb | [BoundingBox](../../com.aspose.threed/boundingbox) | Birleştirilecek sınırlayıcı kutu |

### merge(Vector3 pt) {#merge-com.aspose.threed.Vector3-}
```
public void merge(Vector3 pt)
```


Mevcut sınırlama kutusunu verilen nokta ile birleştir

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | pt | [Vector3](../../com.aspose.threed/vector3) | Sınırlama kutusuna birleştirilecek nokta **Example:** Aşağıdaki kod, bir noktanın sınırlama kutusuna nasıl birleştirileceğini gösterir. |

```
var boundingBox = BoundingBox.getNull();
  boundingBox.Merge(new Vector3(1, 10, -1));
  System.out.println("Bounding box = " + boundingBox);
``` |

### merge(Vector4 pt) {#merge-com.aspose.threed.Vector4-}
```
public void merge(Vector4 pt)
```


Mevcut sınırlama kutusunu verilen nokta ile birleştir

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | pt | [Vector4](../../com.aspose.threed/vector4) | Sınırlama kutusuna birleştirilecek nokta **Example:** Aşağıdaki kod, bir noktanın sınırlama kutusuna nasıl birleştirileceğini gösterir. |

```
var boundingBox = BoundingBox.getNull();
  boundingBox.Merge(new Vector4(1, 10, -1));
  System.out.println("Bounding box = " + boundingBox);
``` |

### merge(double x, double y, double z) {#merge-double-double-double-}
```
public void merge(double x, double y, double z)
```


Mevcut sınırlama kutusunu verilen nokta ile birleştir

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| x | double | Sınırlama kutusuna birleştirilecek nokta |
| y | double | Sınırlama kutusuna birleştirilecek nokta |
|  | z | double | Sınırlama kutusuna birleştirilecek nokta **Example:** Aşağıdaki kod, bir noktanın sınırlama kutusuna nasıl birleştirileceğini gösterir. |

```
var boundingBox = BoundingBox.getNull();
  boundingBox.Merge(1, 10, -1);
  System.out.println("Bounding box = " + boundingBox);
``` |

### mul(BoundingBox bbox, Matrix4 mat) {#mul-com.aspose.threed.BoundingBox-com.aspose.threed.Matrix4-}
```
public static BoundingBox mul(BoundingBox bbox, Matrix4 mat)
```


Çarpma için operatör aşırı yüklemesi, yeni sınırlama kutusunun minimum ve maksimum köşeleri matris tarafından dönüştürülecek.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| bbox | [BoundingBox](../../com.aspose.threed/boundingbox) | Girdi sınırlama kutusu. |
| mat | [Matrix4](../../com.aspose.threed/matrix4) | Sınırlama kutusunun köşelerini dönüştürmek için kullanılan matris |

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


Mevcut sınırlama kutusunun belirtilen sınırlama kutusuyla çakışıp çakışmadığını kontrol et.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| box | [BoundingBox](../../com.aspose.threed/boundingbox) | Test edilecek diğer sınırlama kutusu |

**Returns:**
boolean - Geçerli sınırlama kutusu verilenle çakışıyorsa True. **Example:** Aşağıdaki kod, iki sınırlama kutusunun birbirleriyle nasıl çakıştığını kontrol edeceğini gösterir.

```
var boundingBox = new BoundingBox(0, 0, 0, 10, 10, 10);
  var bbox2 = new BoundingBox(1, 1, 1, 11, 11, 11);
  System.out.println("Bounding box overlaps = " + boundingBox.overlapsWith(bbox2));
```
### scale() {#scale--}
```
public double scale()
```


İçerilen herhangi bir noktanın mutlak en büyük koordinat değerini hesaplar.

**Returns:**
double - içerilen herhangi bir noktanın hesaplanan mutlak en büyük koordinat değeri.
### toString() {#toString--}
```
public String toString()
```


Sınırlayıcı kutunun dize temsilini alır.

**Returns:**
java.lang.String - Sınırlama kutusunun dize temsili.
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final void wait(long arg0)
```




**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |


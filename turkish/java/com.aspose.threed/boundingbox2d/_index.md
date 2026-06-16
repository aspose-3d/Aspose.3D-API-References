---
title: "BoundingBox2D"
second_title: "Aspose.3D for Java API Referansı"
description: "Şunun için eksen hizalı sınırlayıcı kutu"
type: docs
weight: 25
url: /tr/java/com.aspose.threed/boundingbox2d/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.threed.Struct, java.io.Serializable
```
public final class BoundingBox2D implements Struct<BoundingBox2D>, Serializable
```

Eksen hizalı sınırlayıcı kutu [Vector2](../../com.aspose.threed/vector2) için
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [BoundingBox2D(Vector2 minimum, Vector2 maximum)](#BoundingBox2D-com.aspose.threed.Vector2-com.aspose.threed.Vector2-) | Verilen minimum ve maksimum köşe ile sonlu bir sınırlayıcı kutu başlatın |
| [BoundingBox2D()](#BoundingBox2D--) |  |
## Alanlar

| Alan | Açıklama |
| --- | --- |
| [INFINITE](#INFINITE) | Sonsuz sınırlayıcı kutu |
| [NULL](#NULL) | Boş sınırlayıcı kutu |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [clone()](#clone--) |  |
| [copyFrom(BoundingBox2D src)](#copyFrom-com.aspose.threed.BoundingBox2D-) |  |
| [equals(Object obj)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getExtent()](#getExtent--) | Sınırlayıcı kutunun kapsamını alır. |
| [getMaximum()](#getMaximum--) | Sınırlayıcı kutunun maksimum köşesi |
| [getMinimum()](#getMinimum--) | Sınırlayıcı kutunun minimum köşesi |
| [hashCode()](#hashCode--) |  |
| [merge(BoundingBox2D bb)](#merge-com.aspose.threed.BoundingBox2D-) | Yeni kutuyu mevcut sınırlayıcı kutuya birleştirir. |
| [merge(Vector2 pt)](#merge-com.aspose.threed.Vector2-) | Yeni kutuyu mevcut sınırlayıcı kutuya birleştirir. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) | Sınırlayıcı kutunun dize temsilini alır. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### BoundingBox2D(Vector2 minimum, Vector2 maximum) {#BoundingBox2D-com.aspose.threed.Vector2-com.aspose.threed.Vector2-}
```
public BoundingBox2D(Vector2 minimum, Vector2 maximum)
```


Verilen minimum ve maksimum köşe ile sonlu bir sınırlayıcı kutu başlatın

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| minimum | [Vector2](../../com.aspose.threed/vector2) | Minimum köşe |
| maximum | [Vector2](../../com.aspose.threed/vector2) | Maksimum köşe |

### BoundingBox2D() {#BoundingBox2D--}
```
public BoundingBox2D()
```


### INFINITE {#INFINITE}
```
public static final BoundingBox2D INFINITE
```


Sonsuz sınırlayıcı kutu

### NULL {#NULL}
```
public static final BoundingBox2D NULL
```


Boş sınırlayıcı kutu

### clone() {#clone--}
```
public BoundingBox2D clone()
```


Mevcut örneği kopyala

**Returns:**
[BoundingBox2D](../../com.aspose.threed/boundingbox2d)
### copyFrom(BoundingBox2D src) {#copyFrom-com.aspose.threed.BoundingBox2D-}
```
public void copyFrom(BoundingBox2D src)
```




**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| src | [BoundingBox2D](../../com.aspose.threed/boundingbox2d) |  |

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```




**Parameters:**
| Parametre | Tür | Açıklama |
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
### getExtent() {#getExtent--}
```
public BoundingBoxExtent getExtent()
```


Sınırlayıcı kutunun kapsamını alır.

**Returns:**
[BoundingBoxExtent](../../com.aspose.threed/boundingboxextent) - the extent of the bounding box.
### getMaximum() {#getMaximum--}
```
public Vector2 getMaximum()
```


Sınırlayıcı kutunun maksimum köşesi

**Returns:**
[Vector2](../../com.aspose.threed/vector2) - The maximum corner of the bounding box
### getMinimum() {#getMinimum--}
```
public Vector2 getMinimum()
```


Sınırlayıcı kutunun minimum köşesi

**Returns:**
[Vector2](../../com.aspose.threed/vector2) - The minimum corner of the bounding box
### hashCode() {#hashCode--}
```
public int hashCode()
```




**Returns:**
int
### merge(BoundingBox2D bb) {#merge-com.aspose.threed.BoundingBox2D-}
```
public void merge(BoundingBox2D bb)
```


Yeni kutuyu mevcut sınırlayıcı kutuya birleştirir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| bb | [BoundingBox2D](../../com.aspose.threed/boundingbox2d) | Birleştirilecek sınırlayıcı kutu |

### merge(Vector2 pt) {#merge-com.aspose.threed.Vector2-}
```
public void merge(Vector2 pt)
```


Yeni kutuyu mevcut sınırlayıcı kutuya birleştirir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| pt | [Vector2](../../com.aspose.threed/vector2) | Birleştirilecek nokta |

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


Sınırlayıcı kutunun dize temsilini alır.

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


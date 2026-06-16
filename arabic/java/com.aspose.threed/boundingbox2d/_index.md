---
title: "BoundingBox2D"
second_title: "مرجع API لـ Aspose.3D for Java"
description: "مربع الحد المحاذى للمحور لـ"
type: docs
weight: 25
url: /ar/java/com.aspose.threed/boundingbox2d/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.threed.Struct, java.io.Serializable
```
public final class BoundingBox2D implements Struct<BoundingBox2D>, Serializable
```

صندوق الحدود المحاذي للمحور لـ [Vector2](../../com.aspose.threed/vector2)
## المنشئات

| منشئ | الوصف |
| --- | --- |
| [BoundingBox2D(Vector2 minimum, Vector2 maximum)](#BoundingBox2D-com.aspose.threed.Vector2-com.aspose.threed.Vector2-) | تهيئة صندوق حدود نهائي مع الزاوية الدنيا والزاوية القصوى المحددة |
| [BoundingBox2D()](#BoundingBox2D--) |  |
## الحقول

| حقل | الوصف |
| --- | --- |
| [INFINITE](#INFINITE) | صندوق الحدود اللانهائي |
| [NULL](#NULL) | صندوق الحدود الفارغ |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [clone()](#clone--) |  |
| [copyFrom(BoundingBox2D src)](#copyFrom-com.aspose.threed.BoundingBox2D-) |  |
| [equals(Object obj)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getExtent()](#getExtent--) | يسترجع مدى صندوق الحدود. |
| [getMaximum()](#getMaximum--) | الزاوية القصوى لصندوق الحدود |
| [getMinimum()](#getMinimum--) | الزاوية الدنيا لصندوق الحدود |
| [hashCode()](#hashCode--) |  |
| [merge(BoundingBox2D bb)](#merge-com.aspose.threed.BoundingBox2D-) | يدمج الصندوق الجديد في صندوق الحدود الحالي. |
| [merge(Vector2 pt)](#merge-com.aspose.threed.Vector2-) | يدمج الصندوق الجديد في صندوق الحدود الحالي. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) | يسترجع التمثيل النصي لصندوق الحدود. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### BoundingBox2D(Vector2 minimum, Vector2 maximum) {#BoundingBox2D-com.aspose.threed.Vector2-com.aspose.threed.Vector2-}
```
public BoundingBox2D(Vector2 minimum, Vector2 maximum)
```


تهيئة صندوق حدود نهائي مع الزاوية الدنيا والزاوية القصوى المحددة

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| minimum | [Vector2](../../com.aspose.threed/vector2) | الزاوية الدنيا |
| maximum | [Vector2](../../com.aspose.threed/vector2) | الزاوية القصوى |

### BoundingBox2D() {#BoundingBox2D--}
```
public BoundingBox2D()
```


### INFINITE {#INFINITE}
```
public static final BoundingBox2D INFINITE
```


صندوق الحدود اللانهائي

### NULL {#NULL}
```
public static final BoundingBox2D NULL
```


صندوق الحدود الفارغ

### clone() {#clone--}
```
public BoundingBox2D clone()
```


استنساخ النسخة الحالية

**Returns:**
[BoundingBox2D](../../com.aspose.threed/boundingbox2d)
### copyFrom(BoundingBox2D src) {#copyFrom-com.aspose.threed.BoundingBox2D-}
```
public void copyFrom(BoundingBox2D src)
```




**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| src | [BoundingBox2D](../../com.aspose.threed/boundingbox2d) |  |

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```




**Parameters:**
| معامل | نوع | الوصف |
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


يسترجع مدى صندوق الحدود.

**Returns:**
[BoundingBoxExtent](../../com.aspose.threed/boundingboxextent) - the extent of the bounding box.
### getMaximum() {#getMaximum--}
```
public Vector2 getMaximum()
```


الزاوية القصوى لصندوق الحدود

**Returns:**
[Vector2](../../com.aspose.threed/vector2) - The maximum corner of the bounding box
### getMinimum() {#getMinimum--}
```
public Vector2 getMinimum()
```


الزاوية الدنيا لصندوق الحدود

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


يدمج الصندوق الجديد في صندوق الحدود الحالي.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| bb | [BoundingBox2D](../../com.aspose.threed/boundingbox2d) | صندوق الحدود للدمج |

### merge(Vector2 pt) {#merge-com.aspose.threed.Vector2-}
```
public void merge(Vector2 pt)
```


يدمج الصندوق الجديد في صندوق الحدود الحالي.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| pt | [Vector2](../../com.aspose.threed/vector2) | النقطة للدمج |

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


يسترجع التمثيل النصي لصندوق الحدود.

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
| معامل | نوع | الوصف |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |


---
title: "BoundingBox"
second_title: "مرجع API لـ Aspose.3D for Java"
description: "مربع الحد المحاذى للمحاور مثال  الشيفرة التالية توضح كيفية الحصول على مربع حد من كائن Entity."
type: docs
weight: 24
url: /ar/java/com.aspose.threed/boundingbox/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.threed.Struct, java.io.Serializable
```
public final class BoundingBox implements Struct<BoundingBox>, Serializable
```

مربع الحد المحاذى للمحاور **Example:** يوضح الشيفرة التالية كيفية الحصول على مربع حد من مثيل كيان.

```
var sphere = new Sphere();
      var boundingBox = sphere.getBoundingBox();
      System.out.println("Bounding box = " + boundingBox);
```
## المنشئات

| منشئ | الوصف |
| --- | --- |
| [BoundingBox(Vector3 minimum, Vector3 maximum)](#BoundingBox-com.aspose.threed.Vector3-com.aspose.threed.Vector3-) | تهيئة صندوق حدود نهائي مع الزاوية الدنيا والزاوية القصوى المحددة |
| [BoundingBox(double minX, double minY, double minZ, double maxX, double maxY, double maxZ)](#BoundingBox-double-double-double-double-double-double-) | تهيئة صندوق حدود نهائي مع الزاوية الدنيا والزاوية القصوى المحددة |
| [BoundingBox()](#BoundingBox--) |  |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [clone()](#clone--) |  |
| [contains(BoundingBox bbox)](#contains-com.aspose.threed.BoundingBox-) | مربع الحد للتحقق مما إذا كان داخل مربع الحد الحالي. |
| [contains(Vector3 p)](#contains-com.aspose.threed.Vector3-) | تحقق مما إذا كانت النقطة p داخل مربع الحد |
| [copyFrom(BoundingBox src)](#copyFrom-com.aspose.threed.BoundingBox-) |  |
| [equals(Object obj)](#equals-java.lang.Object-) | يحدد ما إذا كان كائنان متساويان |
| [fromGeometry(Geometry geometry)](#fromGeometry-com.aspose.threed.Geometry-) | إنشاء مربع حد من الهندسة المعطاة |
| [getCenter()](#getCenter--) | مركز مربع الحد. |
| [getClass()](#getClass--) |  |
| [getExtent()](#getExtent--) | يسترجع مدى صندوق الحدود. |
| [getInfinite()](#getInfinite--) | صندوق الحدود اللانهائي |
| [getMaximum()](#getMaximum--) | الزاوية القصوى لصندوق الحدود |
| [getMinimum()](#getMinimum--) | الزاوية الدنيا لصندوق الحدود |
| [getNull()](#getNull--) | صندوق الحدود الفارغ |
| [getSize()](#getSize--) | حجم مربع الحد |
| [hashCode()](#hashCode--) | يرجع رمز التجزئة لهذه الحالة |
| [merge(BoundingBox bb)](#merge-com.aspose.threed.BoundingBox-) | يدمج الصندوق الجديد في صندوق الحدود الحالي. |
| [merge(Vector3 pt)](#merge-com.aspose.threed.Vector3-) | دمج مربع الحد الحالي مع النقطة المعطاة |
| [merge(Vector4 pt)](#merge-com.aspose.threed.Vector4-) | دمج مربع الحد الحالي مع النقطة المعطاة |
| [merge(double x, double y, double z)](#merge-double-double-double-) | دمج مربع الحد الحالي مع النقطة المعطاة |
| [mul(BoundingBox bbox, Matrix4 mat)](#mul-com.aspose.threed.BoundingBox-com.aspose.threed.Matrix4-) | تحميل المشغل للضرب، سيتم تحويل الزاوية الدنيا والعليا لمربع الحد الجديد بواسطة المصفوفة. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [overlapsWith(BoundingBox box)](#overlapsWith-com.aspose.threed.BoundingBox-) | تحقق مما إذا كان مربع الحد الحالي يتقاطع مع مربع الحد المحدد. |
| [scale()](#scale--) | يحسب القيمة المطلقة لأكبر إحداثي لأي نقطة محتواة. |
| [toString()](#toString--) | يسترجع التمثيل النصي لصندوق الحدود. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### BoundingBox(Vector3 minimum, Vector3 maximum) {#BoundingBox-com.aspose.threed.Vector3-com.aspose.threed.Vector3-}
```
public BoundingBox(Vector3 minimum, Vector3 maximum)
```


تهيئة صندوق حدود نهائي مع الزاوية الدنيا والزاوية القصوى المحددة

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| minimum | [Vector3](../../com.aspose.threed/vector3) | الزاوية الدنيا |
|  | maximum | [Vector3](../../com.aspose.threed/vector3) | الزاوية القصوى **Example:** يوضح الشيفرة التالية كيفية إنشاء مربع حد من الزوايا الدنيا والقصوى. |

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


تهيئة صندوق حدود نهائي مع الزاوية الدنيا والزاوية القصوى المحددة

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| minX | double | X للزاوية الدنيا |
| minY | double | الزاوية الدنيا للمحور Y |
| minZ | double | الزاوية الدنيا للمحور Z |
| maxX | double | الزاوية القصوى للمحور X |
| maxY | double | الزاوية القصوى للمحور Y |
|  | maxZ | double | الزاوية القصوى للمحور Z **مثال:** يوضح الكود التالي كيفية إنشاء صندوق احتواء من الزوايا الدنيا والقصوى. |

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


استنساخ النسخة الحالية

**Returns:**
[BoundingBox](../../com.aspose.threed/boundingbox)
### contains(BoundingBox bbox) {#contains-com.aspose.threed.BoundingBox-}
```
public boolean contains(BoundingBox bbox)
```


مربع الحد للتحقق مما إذا كان داخل مربع الحد الحالي.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| bbox | [BoundingBox](../../com.aspose.threed/boundingbox) |  |

**Returns:**
boolean
### contains(Vector3 p) {#contains-com.aspose.threed.Vector3-}
```
public boolean contains(Vector3 p)
```


تحقق مما إذا كانت النقطة p داخل مربع الحد

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| p | [Vector3](../../com.aspose.threed/vector3) | النقطة للاختبار |

**Returns:**
منطقي - صحيح إذا كانت النقطة داخل صندوق الاحتواء **مثال:** يوضح الكود التالي كيفية التحقق مما إذا كانت النقطة داخل صندوق الاحتواء.

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
| معامل | نوع | الوصف |
| --- | --- | --- |
| src | [BoundingBox](../../com.aspose.threed/boundingbox) |  |

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


يحدد ما إذا كان كائنان متساويان

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| obj | java.lang.Object | الكائن للمقارنة |

**Returns:**
منطقي - صحيح إذا كان الكائنان متساويين
### fromGeometry(Geometry geometry) {#fromGeometry-com.aspose.threed.Geometry-}
```
public static BoundingBox fromGeometry(Geometry geometry)
```


إنشاء مربع حد من الهندسة المعطاة

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| geometry | [Geometry](../../com.aspose.threed/geometry) | الهندسة لحساب صندوق الاحتواء |

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


مركز مربع الحد.

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


يسترجع مدى صندوق الحدود.

**Returns:**
[BoundingBoxExtent](../../com.aspose.threed/boundingboxextent) - the extent of the bounding box.
### getInfinite() {#getInfinite--}
```
public static BoundingBox getInfinite()
```


صندوق الحدود اللانهائي

**Returns:**
[BoundingBox](../../com.aspose.threed/boundingbox) - The infinite bounding box
### getMaximum() {#getMaximum--}
```
public Vector3 getMaximum()
```


الزاوية القصوى لصندوق الحدود

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - The maximum corner of the bounding box
### getMinimum() {#getMinimum--}
```
public Vector3 getMinimum()
```


الزاوية الدنيا لصندوق الحدود

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - The minimum corner of the bounding box
### getNull() {#getNull--}
```
public static BoundingBox getNull()
```


صندوق الحدود الفارغ

**Returns:**
[BoundingBox](../../com.aspose.threed/boundingbox) - The null bounding box
### getSize() {#getSize--}
```
public Vector3 getSize()
```


حجم مربع الحد

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - The size of the bounding box
### hashCode() {#hashCode--}
```
public int hashCode()
```


يرجع رمز التجزئة لهذه الحالة

**Returns:**
int - قيمة التجزئة لصندوق الاحتواء
### merge(BoundingBox bb) {#merge-com.aspose.threed.BoundingBox-}
```
public void merge(BoundingBox bb)
```


يدمج الصندوق الجديد في صندوق الحدود الحالي.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| bb | [BoundingBox](../../com.aspose.threed/boundingbox) | صندوق الحدود للدمج |

### merge(Vector3 pt) {#merge-com.aspose.threed.Vector3-}
```
public void merge(Vector3 pt)
```


دمج مربع الحد الحالي مع النقطة المعطاة

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | pt | [Vector3](../../com.aspose.threed/vector3) | النقطة التي سيتم دمجها في صندوق الاحتواء **مثال:** يوضح الكود التالي كيفية دمج نقطة في صندوق الاحتواء. |

```
var boundingBox = BoundingBox.getNull();
  boundingBox.Merge(new Vector3(1, 10, -1));
  System.out.println("Bounding box = " + boundingBox);
``` |

### merge(Vector4 pt) {#merge-com.aspose.threed.Vector4-}
```
public void merge(Vector4 pt)
```


دمج مربع الحد الحالي مع النقطة المعطاة

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | pt | [Vector4](../../com.aspose.threed/vector4) | النقطة التي سيتم دمجها في صندوق الاحتواء **مثال:** يوضح الكود التالي كيفية دمج نقطة في صندوق الاحتواء. |

```
var boundingBox = BoundingBox.getNull();
  boundingBox.Merge(new Vector4(1, 10, -1));
  System.out.println("Bounding box = " + boundingBox);
``` |

### merge(double x, double y, double z) {#merge-double-double-double-}
```
public void merge(double x, double y, double z)
```


دمج مربع الحد الحالي مع النقطة المعطاة

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| x | double | النقطة التي سيتم دمجها في صندوق الاحتواء |
| y | double | النقطة التي سيتم دمجها في صندوق الاحتواء |
|  | z | double | النقطة التي سيتم دمجها في صندوق الاحتواء **مثال:** يوضح الكود التالي كيفية دمج نقطة في صندوق الاحتواء. |

```
var boundingBox = BoundingBox.getNull();
  boundingBox.Merge(1, 10, -1);
  System.out.println("Bounding box = " + boundingBox);
``` |

### mul(BoundingBox bbox, Matrix4 mat) {#mul-com.aspose.threed.BoundingBox-com.aspose.threed.Matrix4-}
```
public static BoundingBox mul(BoundingBox bbox, Matrix4 mat)
```


تحميل المشغل للضرب، سيتم تحويل الزاوية الدنيا والعليا لمربع الحد الجديد بواسطة المصفوفة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| bbox | [BoundingBox](../../com.aspose.threed/boundingbox) | صندوق الاحتواء المُدخل. |
| mat | [Matrix4](../../com.aspose.threed/matrix4) | المصفوفة المستخدمة لتحويل زوايا صندوق الاحتواء |

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


تحقق مما إذا كان مربع الحد الحالي يتقاطع مع مربع الحد المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| box | [BoundingBox](../../com.aspose.threed/boundingbox) | صندوق الاحتواء الآخر للاختبار |

**Returns:**
منطقي - صحيح إذا كان صندوق الاحتواء الحالي يتقاطع مع الصندوق المعطى **مثال:** يوضح الكود التالي كيفية التحقق مما إذا كان صندوقا احتواء يتقاطعان مع بعضهما.

```
var boundingBox = new BoundingBox(0, 0, 0, 10, 10, 10);
  var bbox2 = new BoundingBox(1, 1, 1, 11, 11, 11);
  System.out.println("Bounding box overlaps = " + boundingBox.overlapsWith(bbox2));
```
### scale() {#scale--}
```
public double scale()
```


يحسب القيمة المطلقة لأكبر إحداثي لأي نقطة محتواة.

**Returns:**
double - القيمة المطلقة الأكبر للإحداثيات التي تم حسابها لأي نقطة محتواة.
### toString() {#toString--}
```
public String toString()
```


يسترجع التمثيل النصي لصندوق الحدود.

**Returns:**
java.lang.String - تمثيل النص لصندوق الاحتواء.
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


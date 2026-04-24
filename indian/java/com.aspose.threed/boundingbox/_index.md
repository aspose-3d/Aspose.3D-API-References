---
title: BoundingBox
second_title: Aspose.3D for Java API Reference
description: अक्ष-संरेखित बाउंडिंग बॉक्स उदाहरण  निम्नलिखित कोड दिखाता है कि एक Entity इंस्टेंस से बाउंडिंग बॉक्स कैसे प्राप्त किया जाए।
type: docs
weight: 24
url: /hi/java/com.aspose.threed/boundingbox/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.threed.Struct, java.io.Serializable
```
public final class BoundingBox implements Struct<BoundingBox>, Serializable
```

The axis-aligned bounding box **Example:** निम्नलिखित कोड दिखाता है कि कैसे एक Entity इंस्टेंस से बाउंडिंग बॉक्स प्राप्त किया जाए।

```
var sphere = new Sphere();
      var boundingBox = sphere.getBoundingBox();
      System.out.println("Bounding box = " + boundingBox);
```
## Constructors

| Constructor | विवरण |
| --- | --- |
| [BoundingBox(Vector3 minimum, Vector3 maximum)](#BoundingBox-com.aspose.threed.Vector3-com.aspose.threed.Vector3-) | दिए गए न्यूनतम और अधिकतम कोने के साथ एक सीमित बाउंडिंग बॉक्स को आरंभ करें |
| [BoundingBox(double minX, double minY, double minZ, double maxX, double maxY, double maxZ)](#BoundingBox-double-double-double-double-double-double-) | दिए गए न्यूनतम और अधिकतम कोने के साथ एक सीमित बाउंडिंग बॉक्स को आरंभ करें |
| [BoundingBox()](#BoundingBox--) |  |
## Methods

| Method | विवरण |
| --- | --- |
| [clone()](#clone--) |  |
| [contains(BoundingBox bbox)](#contains-com.aspose.threed.BoundingBox-) | वर्तमान बाउंडिंग बॉक्स के अंदर है या नहीं जाँचने के लिए बाउंडिंग बॉक्स। |
| [contains(Vector3 p)](#contains-com.aspose.threed.Vector3-) | जाँचें कि बिंदु p बाउंडिंग बॉक्स के अंदर है या नहीं |
| [copyFrom(BoundingBox src)](#copyFrom-com.aspose.threed.BoundingBox-) |  |
| [equals(Object obj)](#equals-java.lang.Object-) | निर्धारित करता है कि दो वस्तुएँ समान हैं या नहीं |
| [fromGeometry(Geometry geometry)](#fromGeometry-com.aspose.threed.Geometry-) | दिए गए ज्यामिति से बाउंडिंग बॉक्स बनाएं |
| [getCenter()](#getCenter--) | बाउंडिंग बॉक्स का केंद्र। |
| [getClass()](#getClass--) |  |
| [getExtent()](#getExtent--) | बाउंडिंग बॉक्स का विस्तार प्राप्त करता है। |
| [getInfinite()](#getInfinite--) | अनंत बाउंडिंग बॉक्स |
| [getMaximum()](#getMaximum--) | बाउंडिंग बॉक्स का अधिकतम कोना |
| [getMinimum()](#getMinimum--) | बाउंडिंग बॉक्स का न्यूनतम कोना |
| [getNull()](#getNull--) | शून्य बाउंडिंग बॉक्स |
| [getSize()](#getSize--) | बाउंडिंग बॉक्स का आकार |
| [hashCode()](#hashCode--) | इस इंस्टेंस के लिए हैश कोड लौटाता है |
| [merge(BoundingBox bb)](#merge-com.aspose.threed.BoundingBox-) | नए बॉक्स को वर्तमान बाउंडिंग बॉक्स में मिलाता है। |
| [merge(Vector3 pt)](#merge-com.aspose.threed.Vector3-) | दिए गए बिंदु के साथ वर्तमान बाउंडिंग बॉक्स को मिलाएँ |
| [merge(Vector4 pt)](#merge-com.aspose.threed.Vector4-) | दिए गए बिंदु के साथ वर्तमान बाउंडिंग बॉक्स को मिलाएँ |
| [merge(double x, double y, double z)](#merge-double-double-double-) | दिए गए बिंदु के साथ वर्तमान बाउंडिंग बॉक्स को मिलाएँ |
| [mul(BoundingBox bbox, Matrix4 mat)](#mul-com.aspose.threed.BoundingBox-com.aspose.threed.Matrix4-) | गुणा के लिए ऑपरेटर ओवरलोडिंग, नई बाउंडिंग बॉक्स के न्यूनतम और अधिकतम कोने को मैट्रिक्स द्वारा परिवर्तित किया जाएगा। |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [overlapsWith(BoundingBox box)](#overlapsWith-com.aspose.threed.BoundingBox-) | जाँचें कि वर्तमान बाउंडिंग बॉक्स निर्दिष्ट बाउंडिंग बॉक्स के साथ ओवरलैप करता है या नहीं। |
| [scale()](#scale--) | किसी भी सम्मिलित बिंदु के अधिकतम निरपेक्ष निर्देशांक मान की गणना करता है। |
| [toString()](#toString--) | बाउंडिंग बॉक्स का स्ट्रिंग प्रतिनिधित्व प्राप्त करता है। |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### BoundingBox(Vector3 minimum, Vector3 maximum) {#BoundingBox-com.aspose.threed.Vector3-com.aspose.threed.Vector3-}
```
public BoundingBox(Vector3 minimum, Vector3 maximum)
```


दिए गए न्यूनतम और अधिकतम कोने के साथ एक सीमित बाउंडिंग बॉक्स को आरंभ करें

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| minimum | [Vector3](../../com.aspose.threed/vector3) | न्यूनतम कोना |
|  | maximum | [Vector3](../../com.aspose.threed/vector3) | अधिकतम कोना **Example:** निम्नलिखित कोड दिखाता है कि न्यूनतम और अधिकतम कोनों से बाउंडिंग बॉक्स कैसे बनाया जाए। |

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


दिए गए न्यूनतम और अधिकतम कोने के साथ एक सीमित बाउंडिंग बॉक्स को आरंभ करें

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| minX | double | न्यूनतम कोने का X |
| minY | double | न्यूनतम कोने का Y |
| minZ | double | न्यूनतम कोने का Z |
| maxX | double | अधिकतम कोने का X |
| maxY | double | अधिकतम कोने का Y |
|  | maxZ | double | अधिकतम कोने का Z **Example:** निम्नलिखित कोड दिखाता है कि न्यूनतम और अधिकतम कोनों से बाउंडिंग बॉक्स कैसे बनाएं। |

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


वर्तमान उदाहरण को क्लोन करें

**Returns:**
[BoundingBox](../../com.aspose.threed/boundingbox)
### contains(BoundingBox bbox) {#contains-com.aspose.threed.BoundingBox-}
```
public boolean contains(BoundingBox bbox)
```


वर्तमान बाउंडिंग बॉक्स के अंदर है या नहीं जाँचने के लिए बाउंडिंग बॉक्स।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| bbox | [BoundingBox](../../com.aspose.threed/boundingbox) |  |

**Returns:**
boolean
### contains(Vector3 p) {#contains-com.aspose.threed.Vector3-}
```
public boolean contains(Vector3 p)
```


जाँचें कि बिंदु p बाउंडिंग बॉक्स के अंदर है या नहीं

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| p | [Vector3](../../com.aspose.threed/vector3) | परीक्षण के लिए बिंदु |

**Returns:**
boolean - बिंदु बाउंडिंग बॉक्स के भीतर होने पर True **Example:** निम्नलिखित कोड दिखाता है कि बिंदु बाउंडिंग बॉक्स के भीतर है या नहीं जांचें।

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
| Parameter | Type | विवरण |
| --- | --- | --- |
| src | [BoundingBox](../../com.aspose.threed/boundingbox) |  |

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


निर्धारित करता है कि दो वस्तुएँ समान हैं या नहीं

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| obj | java.lang.Object | तुलना करने के लिए वस्तु |

**Returns:**
boolean - दो वस्तुएँ समान हों तो true
### fromGeometry(Geometry geometry) {#fromGeometry-com.aspose.threed.Geometry-}
```
public static BoundingBox fromGeometry(Geometry geometry)
```


दिए गए ज्यामिति से बाउंडिंग बॉक्स बनाएं

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| geometry | [Geometry](../../com.aspose.threed/geometry) | बाउंडिंग बॉक्स की गणना के लिए ज्यामिति |

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


बाउंडिंग बॉक्स का केंद्र।

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


बाउंडिंग बॉक्स का विस्तार प्राप्त करता है।

**Returns:**
[BoundingBoxExtent](../../com.aspose.threed/boundingboxextent) - the extent of the bounding box.
### getInfinite() {#getInfinite--}
```
public static BoundingBox getInfinite()
```


अनंत बाउंडिंग बॉक्स

**Returns:**
[BoundingBox](../../com.aspose.threed/boundingbox) - The infinite bounding box
### getMaximum() {#getMaximum--}
```
public Vector3 getMaximum()
```


बाउंडिंग बॉक्स का अधिकतम कोना

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - The maximum corner of the bounding box
### getMinimum() {#getMinimum--}
```
public Vector3 getMinimum()
```


बाउंडिंग बॉक्स का न्यूनतम कोना

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - The minimum corner of the bounding box
### getNull() {#getNull--}
```
public static BoundingBox getNull()
```


शून्य बाउंडिंग बॉक्स

**Returns:**
[BoundingBox](../../com.aspose.threed/boundingbox) - The null bounding box
### getSize() {#getSize--}
```
public Vector3 getSize()
```


बाउंडिंग बॉक्स का आकार

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - The size of the bounding box
### hashCode() {#hashCode--}
```
public int hashCode()
```


इस इंस्टेंस के लिए हैश कोड लौटाता है

**Returns:**
int - बाउंडिंग बॉक्स का हैश कोड
### merge(BoundingBox bb) {#merge-com.aspose.threed.BoundingBox-}
```
public void merge(BoundingBox bb)
```


नए बॉक्स को वर्तमान बाउंडिंग बॉक्स में मिलाता है।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| bb | [BoundingBox](../../com.aspose.threed/boundingbox) | मर्ज करने के लिए बाउंडिंग बॉक्स |

### merge(Vector3 pt) {#merge-com.aspose.threed.Vector3-}
```
public void merge(Vector3 pt)
```


दिए गए बिंदु के साथ वर्तमान बाउंडिंग बॉक्स को मिलाएँ

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
|  | pt | [Vector3](../../com.aspose.threed/vector3) | बाउंडिंग बॉक्स में मिलाने के लिए बिंदु **Example:** निम्नलिखित कोड दिखाता है कि बिंदु को बाउंडिंग बॉक्स में कैसे मिलाया जाए। |

```
var boundingBox = BoundingBox.getNull();
  boundingBox.Merge(new Vector3(1, 10, -1));
  System.out.println("Bounding box = " + boundingBox);
``` |

### merge(Vector4 pt) {#merge-com.aspose.threed.Vector4-}
```
public void merge(Vector4 pt)
```


दिए गए बिंदु के साथ वर्तमान बाउंडिंग बॉक्स को मिलाएँ

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
|  | pt | [Vector4](../../com.aspose.threed/vector4) | बाउंडिंग बॉक्स में मिलाने के लिए बिंदु **Example:** निम्नलिखित कोड दिखाता है कि बिंदु को बाउंडिंग बॉक्स में कैसे मिलाया जाए। |

```
var boundingBox = BoundingBox.getNull();
  boundingBox.Merge(new Vector4(1, 10, -1));
  System.out.println("Bounding box = " + boundingBox);
``` |

### merge(double x, double y, double z) {#merge-double-double-double-}
```
public void merge(double x, double y, double z)
```


दिए गए बिंदु के साथ वर्तमान बाउंडिंग बॉक्स को मिलाएँ

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| x | double | बाउंडिंग बॉक्स में मिलाने के लिए बिंदु |
| y | double | बाउंडिंग बॉक्स में मिलाने के लिए बिंदु |
|  | z | double | बाउंडिंग बॉक्स में मिलाने के लिए बिंदु **Example:** निम्नलिखित कोड दिखाता है कि बिंदु को बाउंडिंग बॉक्स में कैसे मिलाया जाए। |

```
var boundingBox = BoundingBox.getNull();
  boundingBox.Merge(1, 10, -1);
  System.out.println("Bounding box = " + boundingBox);
``` |

### mul(BoundingBox bbox, Matrix4 mat) {#mul-com.aspose.threed.BoundingBox-com.aspose.threed.Matrix4-}
```
public static BoundingBox mul(BoundingBox bbox, Matrix4 mat)
```


गुणा के लिए ऑपरेटर ओवरलोडिंग, नई बाउंडिंग बॉक्स के न्यूनतम और अधिकतम कोने को मैट्रिक्स द्वारा परिवर्तित किया जाएगा।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| bbox | [BoundingBox](../../com.aspose.threed/boundingbox) | इनपुट बाउंडिंग बॉक्स। |
| mat | [Matrix4](../../com.aspose.threed/matrix4) | बाउंडिंग बॉक्स के कोनों को बदलने के लिए प्रयुक्त मैट्रिक्स |

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


जाँचें कि वर्तमान बाउंडिंग बॉक्स निर्दिष्ट बाउंडिंग बॉक्स के साथ ओवरलैप करता है या नहीं।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| box | [BoundingBox](../../com.aspose.threed/boundingbox) | परीक्षण के लिए अन्य बाउंडिंग बॉक्स |

**Returns:**
boolean - वर्तमान बाउंडिंग बॉक्स दिए गए बॉक्स के साथ ओवरलैप करता है तो True. **Example:** निम्नलिखित कोड दिखाता है कि दो बाउंडिंग बॉक्स एक-दूसरे के साथ ओवरलैप होते हैं या नहीं जांचें।

```
var boundingBox = new BoundingBox(0, 0, 0, 10, 10, 10);
  var bbox2 = new BoundingBox(1, 1, 1, 11, 11, 11);
  System.out.println("Bounding box overlaps = " + boundingBox.overlapsWith(bbox2));
```
### scale() {#scale--}
```
public double scale()
```


किसी भी सम्मिलित बिंदु के अधिकतम निरपेक्ष निर्देशांक मान की गणना करता है।

**Returns:**
double - किसी भी सम्मिलित बिंदु का गणना किया गया पूर्णतम सबसे बड़ा निर्देशांक मान।
### toString() {#toString--}
```
public String toString()
```


बाउंडिंग बॉक्स का स्ट्रिंग प्रतिनिधित्व प्राप्त करता है।

**Returns:**
java.lang.String - बाउंडिंग बॉक्स का स्ट्रिंग प्रतिनिधित्व।
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final void wait(long arg0)
```




**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |


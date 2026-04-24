---
title: BoundingBox2D
second_title: Aspose.3D for Java API Reference
description: के लिए अक्ष-संरेखित बाउंडिंग बॉक्स
type: docs
weight: 25
url: /hi/java/com.aspose.threed/boundingbox2d/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.threed.Struct, java.io.Serializable
```
public final class BoundingBox2D implements Struct<BoundingBox2D>, Serializable
```

अक्ष-संरेखित बाउंडिंग बॉक्स [Vector2](../../com.aspose.threed/vector2) के लिए
## Constructors

| Constructor | विवरण |
| --- | --- |
| [BoundingBox2D(Vector2 minimum, Vector2 maximum)](#BoundingBox2D-com.aspose.threed.Vector2-com.aspose.threed.Vector2-) | दिए गए न्यूनतम और अधिकतम कोने के साथ एक सीमित बाउंडिंग बॉक्स को आरंभ करें |
| [BoundingBox2D()](#BoundingBox2D--) |  |
## फ़ील्ड्स

| फ़ील्ड | विवरण |
| --- | --- |
| [INFINITE](#INFINITE) | अनंत बाउंडिंग बॉक्स |
| [NULL](#NULL) | शून्य बाउंडिंग बॉक्स |
## Methods

| Method | विवरण |
| --- | --- |
| [clone()](#clone--) |  |
| [copyFrom(BoundingBox2D src)](#copyFrom-com.aspose.threed.BoundingBox2D-) |  |
| [equals(Object obj)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getExtent()](#getExtent--) | बाउंडिंग बॉक्स का विस्तार प्राप्त करता है। |
| [getMaximum()](#getMaximum--) | बाउंडिंग बॉक्स का अधिकतम कोना |
| [getMinimum()](#getMinimum--) | बाउंडिंग बॉक्स का न्यूनतम कोना |
| [hashCode()](#hashCode--) |  |
| [merge(BoundingBox2D bb)](#merge-com.aspose.threed.BoundingBox2D-) | नए बॉक्स को वर्तमान बाउंडिंग बॉक्स में मिलाता है। |
| [merge(Vector2 pt)](#merge-com.aspose.threed.Vector2-) | नए बॉक्स को वर्तमान बाउंडिंग बॉक्स में मिलाता है। |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) | बाउंडिंग बॉक्स का स्ट्रिंग प्रतिनिधित्व प्राप्त करता है। |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### BoundingBox2D(Vector2 minimum, Vector2 maximum) {#BoundingBox2D-com.aspose.threed.Vector2-com.aspose.threed.Vector2-}
```
public BoundingBox2D(Vector2 minimum, Vector2 maximum)
```


दिए गए न्यूनतम और अधिकतम कोने के साथ एक सीमित बाउंडिंग बॉक्स को आरंभ करें

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| minimum | [Vector2](../../com.aspose.threed/vector2) | न्यूनतम कोना |
| maximum | [Vector2](../../com.aspose.threed/vector2) | अधिकतम कोना |

### BoundingBox2D() {#BoundingBox2D--}
```
public BoundingBox2D()
```


### INFINITE {#INFINITE}
```
public static final BoundingBox2D INFINITE
```


अनंत बाउंडिंग बॉक्स

### NULL {#NULL}
```
public static final BoundingBox2D NULL
```


शून्य बाउंडिंग बॉक्स

### clone() {#clone--}
```
public BoundingBox2D clone()
```


वर्तमान उदाहरण को क्लोन करें

**Returns:**
[BoundingBox2D](../../com.aspose.threed/boundingbox2d)
### copyFrom(BoundingBox2D src) {#copyFrom-com.aspose.threed.BoundingBox2D-}
```
public void copyFrom(BoundingBox2D src)
```




**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| src | [BoundingBox2D](../../com.aspose.threed/boundingbox2d) |  |

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```




**Parameters:**
| Parameter | Type | विवरण |
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


बाउंडिंग बॉक्स का विस्तार प्राप्त करता है।

**Returns:**
[BoundingBoxExtent](../../com.aspose.threed/boundingboxextent) - the extent of the bounding box.
### getMaximum() {#getMaximum--}
```
public Vector2 getMaximum()
```


बाउंडिंग बॉक्स का अधिकतम कोना

**Returns:**
[Vector2](../../com.aspose.threed/vector2) - The maximum corner of the bounding box
### getMinimum() {#getMinimum--}
```
public Vector2 getMinimum()
```


बाउंडिंग बॉक्स का न्यूनतम कोना

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


नए बॉक्स को वर्तमान बाउंडिंग बॉक्स में मिलाता है।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| bb | [BoundingBox2D](../../com.aspose.threed/boundingbox2d) | मर्ज करने के लिए बाउंडिंग बॉक्स |

### merge(Vector2 pt) {#merge-com.aspose.threed.Vector2-}
```
public void merge(Vector2 pt)
```


नए बॉक्स को वर्तमान बाउंडिंग बॉक्स में मिलाता है।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| pt | [Vector2](../../com.aspose.threed/vector2) | मर्ज करने के लिए बिंदु |

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


बाउंडिंग बॉक्स का स्ट्रिंग प्रतिनिधित्व प्राप्त करता है।

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


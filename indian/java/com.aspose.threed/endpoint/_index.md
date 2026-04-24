---
title: EndPoint
second_title: Aspose.3D for Java API Reference
description: वक्र को ट्रिम करने के लिए अंत बिंदु पैरामीटर मान या कार्टेशियन बिंदु हो सकता है।
type: docs
weight: 51
url: /hi/java/com.aspose.threed/endpoint/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.threed.Struct, java.io.Serializable
```
public final class EndPoint implements Struct<EndPoint>, Serializable
```

वक्र को ट्रिम करने के लिए अंत बिंदु, यह पैरामीटर मान या कार्टेशियन बिंदु हो सकता है।
## Constructors

| Constructor | विवरण |
| --- | --- |
| [EndPoint(Vector3 point)](#EndPoint-com.aspose.threed.Vector3-) | एक कार्टेशियन बिंदु से एक [EndPoint](../../com.aspose.threed/endpoint) बनाएं। |
| [EndPoint(double v)](#EndPoint-double-) | एक वास्तविक पैरामीटर से एक [EndPoint](../../com.aspose.threed/endpoint) बनाएं। |
| [EndPoint()](#EndPoint--) |  |
## Methods

| Method | विवरण |
| --- | --- |
| [clone()](#clone--) |  |
| [copyFrom(EndPoint src)](#copyFrom-com.aspose.threed.EndPoint-) |  |
| [equals(Object obj)](#equals-java.lang.Object-) |  |
| [fromDegree(double degree)](#fromDegree-double-) | डिग्री में मापा गया अंत बिंदु बनाएं। |
| [fromRadian(double degree)](#fromRadian-double-) | रेडियन में मापा गया अंत बिंदु बनाएं। |
| [getAsPoint()](#getAsPoint--) | अंत बिंदु को कार्टेशियन बिंदु के रूप में प्राप्त करता है, या अपवाद फेंकता है। |
| [getAsValue()](#getAsValue--) | अंत बिंदु को वास्तविक पैरामीटर के रूप में प्राप्त करता है, या अपवाद फेंकता है। |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) |  |
| [isCartesianPoint()](#isCartesianPoint--) | क्या अंत बिंदु एक कार्टेशियन बिंदु है? |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) | वर्तमान अंत बिंदु का स्ट्रिंग प्रतिनिधित्व लौटाता है। |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### EndPoint(Vector3 point) {#EndPoint-com.aspose.threed.Vector3-}
```
public EndPoint(Vector3 point)
```


एक कार्टेशियन बिंदु से एक [EndPoint](../../com.aspose.threed/endpoint) बनाएं।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| point | [Vector3](../../com.aspose.threed/vector3) | निर्माण के लिए बिंदु |

### EndPoint(double v) {#EndPoint-double-}
```
public EndPoint(double v)
```


एक वास्तविक पैरामीटर से एक [EndPoint](../../com.aspose.threed/endpoint) बनाएं।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| v | double | अंत बिंदु बनाने के लिए वास्तविक संख्या पैरामीटर |

### EndPoint() {#EndPoint--}
```
public EndPoint()
```


### clone() {#clone--}
```
public EndPoint clone()
```


वर्तमान उदाहरण को क्लोन करें

**Returns:**
[EndPoint](../../com.aspose.threed/endpoint)
### copyFrom(EndPoint src) {#copyFrom-com.aspose.threed.EndPoint-}
```
public void copyFrom(EndPoint src)
```




**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| src | [EndPoint](../../com.aspose.threed/endpoint) |  |

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
### fromDegree(double degree) {#fromDegree-double-}
```
public static EndPoint fromDegree(double degree)
```


डिग्री में मापा गया अंत बिंदु बनाएं।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| डिग्री | double | डिग्री में मान |

**Returns:**
[EndPoint](../../com.aspose.threed/endpoint) - An end point constructed from degree
### fromRadian(double degree) {#fromRadian-double-}
```
public static EndPoint fromRadian(double degree)
```


रेडियन में मापा गया अंत बिंदु बनाएं।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| डिग्री | double | रेडियन में मान |

**Returns:**
[EndPoint](../../com.aspose.threed/endpoint) - An end point constructed from radian
### getAsPoint() {#getAsPoint--}
```
public Vector3 getAsPoint()
```


अंत बिंदु को कार्टेशियन बिंदु के रूप में प्राप्त करता है, या अपवाद फेंकता है।

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - the end point as Cartesian point, or thrown an exception.
### getAsValue() {#getAsValue--}
```
public double getAsValue()
```


अंत बिंदु को वास्तविक पैरामीटर के रूप में प्राप्त करता है, या अपवाद फेंकता है।

**Returns:**
double - अंत बिंदु को वास्तविक पैरामीटर के रूप में, या अपवाद फेंके।
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


क्या अंत बिंदु एक कार्टेशियन बिंदु है?

**Returns:**
boolean - क्या अंत बिंदु एक कार्टेशियन बिंदु है?
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


वर्तमान अंत बिंदु का स्ट्रिंग प्रतिनिधित्व लौटाता है।

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


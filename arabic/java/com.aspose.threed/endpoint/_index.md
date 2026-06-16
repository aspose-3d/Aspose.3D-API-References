---
title: "EndPoint"
second_title: "مرجع API لـ Aspose.3D for Java"
description: "نقطة النهاية لتقليم المنحنى يمكن أن تكون قيمة معامل أو نقطة ديكارتية."
type: docs
weight: 51
url: /ar/java/com.aspose.threed/endpoint/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.threed.Struct, java.io.Serializable
```
public final class EndPoint implements Struct<EndPoint>, Serializable
```

نقطة النهاية لتقليم المنحنى، يمكن أن تكون قيمة معلمة أو نقطة إحداثية.
## المنشئات

| منشئ | الوصف |
| --- | --- |
| [EndPoint(Vector3 point)](#EndPoint-com.aspose.threed.Vector3-) | إنشاء [EndPoint](../../com.aspose.threed/endpoint) من نقطة ديكارتية. |
| [EndPoint(double v)](#EndPoint-double-) | إنشاء [EndPoint](../../com.aspose.threed/endpoint) من معامل حقيقي. |
| [EndPoint()](#EndPoint--) |  |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [clone()](#clone--) |  |
| [copyFrom(EndPoint src)](#copyFrom-com.aspose.threed.EndPoint-) |  |
| [equals(Object obj)](#equals-java.lang.Object-) |  |
| [fromDegree(double degree)](#fromDegree-double-) | إنشاء نقطة نهاية مقاسة بالدرجة. |
| [fromRadian(double degree)](#fromRadian-double-) | إنشاء نقطة نهاية مقاسة بالراديان. |
| [getAsPoint()](#getAsPoint--) | يحصل على نقطة النهاية كنقطة ديكارتية، أو يرمي استثناءً. |
| [getAsValue()](#getAsValue--) | يحصل على نقطة النهاية كمعامل حقيقي، أو يرمي استثناءً. |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) |  |
| [isCartesianPoint()](#isCartesianPoint--) | هل نقطة النهاية هي نقطة ديكارتية؟ |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) | يرجع تمثيلًا نصيًا لنقطة النهاية الحالية. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### EndPoint(Vector3 point) {#EndPoint-com.aspose.threed.Vector3-}
```
public EndPoint(Vector3 point)
```


إنشاء [EndPoint](../../com.aspose.threed/endpoint) من نقطة ديكارتية.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| point | [Vector3](../../com.aspose.threed/vector3) | النقطة للإنشاء |

### EndPoint(double v) {#EndPoint-double-}
```
public EndPoint(double v)
```


إنشاء [EndPoint](../../com.aspose.threed/endpoint) من معامل حقيقي.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| v | double | معامل العدد الحقيقي لإنشاء نقطة النهاية |

### EndPoint() {#EndPoint--}
```
public EndPoint()
```


### clone() {#clone--}
```
public EndPoint clone()
```


استنساخ النسخة الحالية

**Returns:**
[EndPoint](../../com.aspose.threed/endpoint)
### copyFrom(EndPoint src) {#copyFrom-com.aspose.threed.EndPoint-}
```
public void copyFrom(EndPoint src)
```




**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| src | [EndPoint](../../com.aspose.threed/endpoint) |  |

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
### fromDegree(double degree) {#fromDegree-double-}
```
public static EndPoint fromDegree(double degree)
```


إنشاء نقطة نهاية مقاسة بالدرجة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| درجة | double | القيمة بالدرجة |

**Returns:**
[EndPoint](../../com.aspose.threed/endpoint) - An end point constructed from degree
### fromRadian(double degree) {#fromRadian-double-}
```
public static EndPoint fromRadian(double degree)
```


إنشاء نقطة نهاية مقاسة بالراديان.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| درجة | double | القيمة بالراديان |

**Returns:**
[EndPoint](../../com.aspose.threed/endpoint) - An end point constructed from radian
### getAsPoint() {#getAsPoint--}
```
public Vector3 getAsPoint()
```


يحصل على نقطة النهاية كنقطة ديكارتية، أو يرمي استثناءً.

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - the end point as Cartesian point, or thrown an exception.
### getAsValue() {#getAsValue--}
```
public double getAsValue()
```


يحصل على نقطة النهاية كمعامل حقيقي، أو يرمي استثناءً.

**Returns:**
double - نقطة النهاية كمعامل حقيقي، أو يرمي استثناءً.
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


هل نقطة النهاية هي نقطة ديكارتية؟

**Returns:**
boolean - هل نقطة النهاية هي نقطة ديكارتية؟
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


يرجع تمثيلًا نصيًا لنقطة النهاية الحالية.

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


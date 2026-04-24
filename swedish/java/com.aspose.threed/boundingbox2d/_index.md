---
title: BoundingBox2D
second_title: Aspose.3D for Java API-referens
description: Den axeljusterade omgivningsboxen för
type: docs
weight: 25
url: /sv/java/com.aspose.threed/boundingbox2d/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.threed.Struct, java.io.Serializable
```
public final class BoundingBox2D implements Struct<BoundingBox2D>, Serializable
```

Den axeljusterade avgränsningsboxen för [Vector2](../../com.aspose.threed/vector2)
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [BoundingBox2D(Vector2 minimum, Vector2 maximum)](#BoundingBox2D-com.aspose.threed.Vector2-com.aspose.threed.Vector2-) | Initiera en ändlig avgränsningsbox med angivet minsta och största hörn |
| [BoundingBox2D()](#BoundingBox2D--) |  |
## Fält

| Fält | Beskrivning |
| --- | --- |
| [INFINITE](#INFINITE) | Den oändliga avgränsningsboxen |
| [NULL](#NULL) | Den nullavgränsningsboxen |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [clone()](#clone--) |  |
| [copyFrom(BoundingBox2D src)](#copyFrom-com.aspose.threed.BoundingBox2D-) |  |
| [equals(Object obj)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getExtent()](#getExtent--) | Hämtar omfattningen av avgränsningsboxen. |
| [getMaximum()](#getMaximum--) | Det maximala hörnet av avgränsningsboxen |
| [getMinimum()](#getMinimum--) | Det minsta hörnet av avgränsningsboxen |
| [hashCode()](#hashCode--) |  |
| [merge(BoundingBox2D bb)](#merge-com.aspose.threed.BoundingBox2D-) | Slår ihop den nya boxen med den aktuella avgränsningsboxen. |
| [merge(Vector2 pt)](#merge-com.aspose.threed.Vector2-) | Slår ihop den nya boxen med den aktuella avgränsningsboxen. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) | Hämtar strängrepresentationen av avgränsningsboxen. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### BoundingBox2D(Vector2 minimum, Vector2 maximum) {#BoundingBox2D-com.aspose.threed.Vector2-com.aspose.threed.Vector2-}
```
public BoundingBox2D(Vector2 minimum, Vector2 maximum)
```


Initiera en ändlig avgränsningsbox med angivet minsta och största hörn

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| minimum | [Vector2](../../com.aspose.threed/vector2) | Det minsta hörnet |
| maximum | [Vector2](../../com.aspose.threed/vector2) | Det största hörnet |

### BoundingBox2D() {#BoundingBox2D--}
```
public BoundingBox2D()
```


### INFINITE {#INFINITE}
```
public static final BoundingBox2D INFINITE
```


Den oändliga avgränsningsboxen

### NULL {#NULL}
```
public static final BoundingBox2D NULL
```


Den nullavgränsningsboxen

### clone() {#clone--}
```
public BoundingBox2D clone()
```


Clone current instance

**Returns:**
[BoundingBox2D](../../com.aspose.threed/boundingbox2d)
### copyFrom(BoundingBox2D src) {#copyFrom-com.aspose.threed.BoundingBox2D-}
```
public void copyFrom(BoundingBox2D src)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| src | [BoundingBox2D](../../com.aspose.threed/boundingbox2d) |  |

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
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


Hämtar omfattningen av avgränsningsboxen.

**Returns:**
[BoundingBoxExtent](../../com.aspose.threed/boundingboxextent) - the extent of the bounding box.
### getMaximum() {#getMaximum--}
```
public Vector2 getMaximum()
```


Det maximala hörnet av avgränsningsboxen

**Returns:**
[Vector2](../../com.aspose.threed/vector2) - The maximum corner of the bounding box
### getMinimum() {#getMinimum--}
```
public Vector2 getMinimum()
```


Det minsta hörnet av avgränsningsboxen

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


Slår ihop den nya boxen med den aktuella avgränsningsboxen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| bb | [BoundingBox2D](../../com.aspose.threed/boundingbox2d) | Avgränsningsboxen att slå ihop |

### merge(Vector2 pt) {#merge-com.aspose.threed.Vector2-}
```
public void merge(Vector2 pt)
```


Slår ihop den nya boxen med den aktuella avgränsningsboxen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| pt | [Vector2](../../com.aspose.threed/vector2) | Punkten att slå ihop |

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


Hämtar strängrepresentationen av avgränsningsboxen.

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
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |


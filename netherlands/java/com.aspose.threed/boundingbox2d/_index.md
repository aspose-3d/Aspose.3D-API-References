---
title: "BoundingBox2D"
second_title: "Aspose.3D voor Java API-referentie"
description: "De as-uitgelijnde begrenzingskader voor"
type: docs
weight: 25
url: /nl/java/com.aspose.threed/boundingbox2d/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.threed.Struct, java.io.Serializable
```
public final class BoundingBox2D implements Struct<BoundingBox2D>, Serializable
```

De as-uitgelijnde begrenzingsvak voor [Vector2](../../com.aspose.threed/vector2)
## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [BoundingBox2D(Vector2 minimum, Vector2 maximum)](#BoundingBox2D-com.aspose.threed.Vector2-com.aspose.threed.Vector2-) | Initialiseer een eindige begrenzingsvak met de opgegeven minimale en maximale hoek |
| [BoundingBox2D()](#BoundingBox2D--) |  |
## Velden

| Veld | Beschrijving |
| --- | --- |
| [INFINITE](#INFINITE) | De oneindige begrenzingsvak |
| [NULL](#NULL) | De nulbegrenzingsvak |
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [clone()](#clone--) |  |
| [copyFrom(BoundingBox2D src)](#copyFrom-com.aspose.threed.BoundingBox2D-) |  |
| [equals(Object obj)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getExtent()](#getExtent--) | Haalt de omvang van de begrenzingsvak op. |
| [getMaximum()](#getMaximum--) | De maximale hoek van de begrenzingsvak |
| [getMinimum()](#getMinimum--) | De minimale hoek van de begrenzingsvak |
| [hashCode()](#hashCode--) |  |
| [merge(BoundingBox2D bb)](#merge-com.aspose.threed.BoundingBox2D-) | Voegt de nieuwe doos toe aan de huidige begrenzingsvak. |
| [merge(Vector2 pt)](#merge-com.aspose.threed.Vector2-) | Voegt de nieuwe doos toe aan de huidige begrenzingsvak. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) | Haalt de tekenreeksrepresentatie van de begrenzingsvak op. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### BoundingBox2D(Vector2 minimum, Vector2 maximum) {#BoundingBox2D-com.aspose.threed.Vector2-com.aspose.threed.Vector2-}
```
public BoundingBox2D(Vector2 minimum, Vector2 maximum)
```


Initialiseer een eindige begrenzingsvak met de opgegeven minimale en maximale hoek

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| minimum | [Vector2](../../com.aspose.threed/vector2) | De minimale hoek |
| maximum | [Vector2](../../com.aspose.threed/vector2) | De maximale hoek |

### BoundingBox2D() {#BoundingBox2D--}
```
public BoundingBox2D()
```


### INFINITE {#INFINITE}
```
public static final BoundingBox2D INFINITE
```


De oneindige begrenzingsvak

### NULL {#NULL}
```
public static final BoundingBox2D NULL
```


De nulbegrenzingsvak

### clone() {#clone--}
```
public BoundingBox2D clone()
```


Kloon huidige instantie

**Returns:**
[BoundingBox2D](../../com.aspose.threed/boundingbox2d)
### copyFrom(BoundingBox2D src) {#copyFrom-com.aspose.threed.BoundingBox2D-}
```
public void copyFrom(BoundingBox2D src)
```




**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| src | [BoundingBox2D](../../com.aspose.threed/boundingbox2d) |  |

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```




**Parameters:**
| Parameter | Type | Beschrijving |
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


Haalt de omvang van de begrenzingsvak op.

**Returns:**
[BoundingBoxExtent](../../com.aspose.threed/boundingboxextent) - the extent of the bounding box.
### getMaximum() {#getMaximum--}
```
public Vector2 getMaximum()
```


De maximale hoek van de begrenzingsvak

**Returns:**
[Vector2](../../com.aspose.threed/vector2) - The maximum corner of the bounding box
### getMinimum() {#getMinimum--}
```
public Vector2 getMinimum()
```


De minimale hoek van de begrenzingsvak

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


Voegt de nieuwe doos toe aan de huidige begrenzingsvak.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| bb | [BoundingBox2D](../../com.aspose.threed/boundingbox2d) | De te combineren begrenzingsvak |

### merge(Vector2 pt) {#merge-com.aspose.threed.Vector2-}
```
public void merge(Vector2 pt)
```


Voegt de nieuwe doos toe aan de huidige begrenzingsvak.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| pt | [Vector2](../../com.aspose.threed/vector2) | Het te combineren punt |

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


Haalt de tekenreeksrepresentatie van de begrenzingsvak op.

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
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |


---
title: "BoundingBox2D"
second_title: "Référence d'API Aspose.3D pour Java"
description: "La boîte englobante alignée sur les axes pour"
type: docs
weight: 25
url: /fr/java/com.aspose.threed/boundingbox2d/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.threed.Struct, java.io.Serializable
```
public final class BoundingBox2D implements Struct<BoundingBox2D>, Serializable
```

La boîte englobante alignée sur les axes pour [Vector2](../../com.aspose.threed/vector2)
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [BoundingBox2D(Vector2 minimum, Vector2 maximum)](#BoundingBox2D-com.aspose.threed.Vector2-com.aspose.threed.Vector2-) | Initialiser une boîte englobante finie avec les coins minimum et maximum donnés |
| [BoundingBox2D()](#BoundingBox2D--) |  |
## Champs

| Champ | Description |
| --- | --- |
| [INFINITE](#INFINITE) | La boîte englobante infinie |
| [NULL](#NULL) | La boîte englobante nulle |
## Méthodes

| Méthode | Description |
| --- | --- |
| [clone()](#clone--) |  |
| [copyFrom(BoundingBox2D src)](#copyFrom-com.aspose.threed.BoundingBox2D-) |  |
| [equals(Object obj)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getExtent()](#getExtent--) | Obtient l'étendue de la boîte englobante. |
| [getMaximum()](#getMaximum--) | Le coin maximum de la boîte englobante |
| [getMinimum()](#getMinimum--) | Le coin minimum de la boîte englobante |
| [hashCode()](#hashCode--) |  |
| [merge(BoundingBox2D bb)](#merge-com.aspose.threed.BoundingBox2D-) | Fusionne la nouvelle boîte dans la boîte englobante actuelle. |
| [merge(Vector2 pt)](#merge-com.aspose.threed.Vector2-) | Fusionne la nouvelle boîte dans la boîte englobante actuelle. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) | Obtient la représentation sous forme de chaîne de la boîte englobante. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### BoundingBox2D(Vector2 minimum, Vector2 maximum) {#BoundingBox2D-com.aspose.threed.Vector2-com.aspose.threed.Vector2-}
```
public BoundingBox2D(Vector2 minimum, Vector2 maximum)
```


Initialiser une boîte englobante finie avec les coins minimum et maximum donnés

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| minimum | [Vector2](../../com.aspose.threed/vector2) | Le coin minimum |
| maximum | [Vector2](../../com.aspose.threed/vector2) | Le coin maximum |

### BoundingBox2D() {#BoundingBox2D--}
```
public BoundingBox2D()
```


### INFINITE {#INFINITE}
```
public static final BoundingBox2D INFINITE
```


La boîte englobante infinie

### NULL {#NULL}
```
public static final BoundingBox2D NULL
```


La boîte englobante nulle

### clone() {#clone--}
```
public BoundingBox2D clone()
```


Cloner l'instance actuelle

**Returns:**
[BoundingBox2D](../../com.aspose.threed/boundingbox2d)
### copyFrom(BoundingBox2D src) {#copyFrom-com.aspose.threed.BoundingBox2D-}
```
public void copyFrom(BoundingBox2D src)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| src | [BoundingBox2D](../../com.aspose.threed/boundingbox2d) |  |

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```




**Parameters:**
| Paramètre | Type | Description |
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


Obtient l'étendue de la boîte englobante.

**Returns:**
[BoundingBoxExtent](../../com.aspose.threed/boundingboxextent) - the extent of the bounding box.
### getMaximum() {#getMaximum--}
```
public Vector2 getMaximum()
```


Le coin maximum de la boîte englobante

**Returns:**
[Vector2](../../com.aspose.threed/vector2) - The maximum corner of the bounding box
### getMinimum() {#getMinimum--}
```
public Vector2 getMinimum()
```


Le coin minimum de la boîte englobante

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


Fusionne la nouvelle boîte dans la boîte englobante actuelle.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| bb | [BoundingBox2D](../../com.aspose.threed/boundingbox2d) | La boîte englobante à fusionner |

### merge(Vector2 pt) {#merge-com.aspose.threed.Vector2-}
```
public void merge(Vector2 pt)
```


Fusionne la nouvelle boîte dans la boîte englobante actuelle.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| pt | [Vector2](../../com.aspose.threed/vector2) | Le point à fusionner |

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


Obtient la représentation sous forme de chaîne de la boîte englobante.

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
| Paramètre | Type | Description |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |


---
title: BoundingBox2D
second_title: Aspose.3D for Java API Reference
description: Il bounding box allineato agli assi per
type: docs
weight: 25
url: /it/java/com.aspose.threed/boundingbox2d/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.threed.Struct, java.io.Serializable
```
public final class BoundingBox2D implements Struct<BoundingBox2D>, Serializable
```

Il riquadro di delimitazione allineato agli assi per [Vector2](../../com.aspose.threed/vector2)
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [BoundingBox2D(Vector2 minimum, Vector2 maximum)](#BoundingBox2D-com.aspose.threed.Vector2-com.aspose.threed.Vector2-) | Inizializza un box di delimitazione finito con gli angoli minimo e massimo specificati |
| [BoundingBox2D()](#BoundingBox2D--) |  |
## Campi

| Campo | Descrizione |
| --- | --- |
| [INFINITE](#INFINITE) | Il box di delimitazione infinito |
| [NULL](#NULL) | Il box di delimitazione nullo |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [clone()](#clone--) |  |
| [copyFrom(BoundingBox2D src)](#copyFrom-com.aspose.threed.BoundingBox2D-) |  |
| [equals(Object obj)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getExtent()](#getExtent--) | Restituisce l'estensione del box di delimitazione. |
| [getMaximum()](#getMaximum--) | L'angolo massimo del box di delimitazione |
| [getMinimum()](#getMinimum--) | L'angolo minimo del box di delimitazione |
| [hashCode()](#hashCode--) |  |
| [merge(BoundingBox2D bb)](#merge-com.aspose.threed.BoundingBox2D-) | Unisce il nuovo box al box di delimitazione corrente. |
| [merge(Vector2 pt)](#merge-com.aspose.threed.Vector2-) | Unisce il nuovo box al box di delimitazione corrente. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) | Restituisce la rappresentazione stringa del box di delimitazione. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### BoundingBox2D(Vector2 minimum, Vector2 maximum) {#BoundingBox2D-com.aspose.threed.Vector2-com.aspose.threed.Vector2-}
```
public BoundingBox2D(Vector2 minimum, Vector2 maximum)
```


Inizializza un box di delimitazione finito con gli angoli minimo e massimo specificati

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| minimum | [Vector2](../../com.aspose.threed/vector2) | L'angolo minimo |
| maximum | [Vector2](../../com.aspose.threed/vector2) | L'angolo massimo |

### BoundingBox2D() {#BoundingBox2D--}
```
public BoundingBox2D()
```


### INFINITE {#INFINITE}
```
public static final BoundingBox2D INFINITE
```


Il box di delimitazione infinito

### NULL {#NULL}
```
public static final BoundingBox2D NULL
```


Il box di delimitazione nullo

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
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| src | [BoundingBox2D](../../com.aspose.threed/boundingbox2d) |  |

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
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


Restituisce l'estensione del box di delimitazione.

**Returns:**
[BoundingBoxExtent](../../com.aspose.threed/boundingboxextent) - the extent of the bounding box.
### getMaximum() {#getMaximum--}
```
public Vector2 getMaximum()
```


L'angolo massimo del box di delimitazione

**Returns:**
[Vector2](../../com.aspose.threed/vector2) - The maximum corner of the bounding box
### getMinimum() {#getMinimum--}
```
public Vector2 getMinimum()
```


L'angolo minimo del box di delimitazione

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


Unisce il nuovo box al box di delimitazione corrente.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| bb | [BoundingBox2D](../../com.aspose.threed/boundingbox2d) | Il box di delimitazione da unire |

### merge(Vector2 pt) {#merge-com.aspose.threed.Vector2-}
```
public void merge(Vector2 pt)
```


Unisce il nuovo box al box di delimitazione corrente.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| pt | [Vector2](../../com.aspose.threed/vector2) | Il punto da unire |

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


Restituisce la rappresentazione stringa del box di delimitazione.

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
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |


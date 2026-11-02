---
title: "BoundingBox2D"
second_title: "Referencia de API de Aspose.3D for Java"
description: "El cuadro delimitador alineado a los ejes para"
type: docs
weight: 25
url: /es/java/com.aspose.threed/boundingbox2d/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.threed.Struct, java.io.Serializable
```
public final class BoundingBox2D implements Struct<BoundingBox2D>, Serializable
```

La caja delimitadora alineada a los ejes para [Vector2](../../com.aspose.threed/vector2)
## Constructores

| Constructor | Descripción |
| --- | --- |
| [BoundingBox2D(Vector2 minimum, Vector2 maximum)](#BoundingBox2D-com.aspose.threed.Vector2-com.aspose.threed.Vector2-) | Inicializa una caja delimitadora finita con la esquina mínima y máxima dadas |
| [BoundingBox2D()](#BoundingBox2D--) |  |
## Campos

| Campo | Descripción |
| --- | --- |
| [INFINITE](#INFINITE) | La caja delimitadora infinita |
| [NULL](#NULL) | La caja delimitadora nula |
## Métodos

| Método | Descripción |
| --- | --- |
| [clone()](#clone--) |  |
| [copyFrom(BoundingBox2D src)](#copyFrom-com.aspose.threed.BoundingBox2D-) |  |
| [equals(Object obj)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getExtent()](#getExtent--) | Obtiene la extensión de la caja delimitadora. |
| [getMaximum()](#getMaximum--) | La esquina máxima de la caja delimitadora |
| [getMinimum()](#getMinimum--) | La esquina mínima de la caja delimitadora |
| [hashCode()](#hashCode--) |  |
| [merge(BoundingBox2D bb)](#merge-com.aspose.threed.BoundingBox2D-) | Fusiona la nueva caja con la caja delimitadora actual. |
| [merge(Vector2 pt)](#merge-com.aspose.threed.Vector2-) | Fusiona la nueva caja con la caja delimitadora actual. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) | Obtiene la representación en cadena de la caja delimitadora. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### BoundingBox2D(Vector2 minimum, Vector2 maximum) {#BoundingBox2D-com.aspose.threed.Vector2-com.aspose.threed.Vector2-}
```
public BoundingBox2D(Vector2 minimum, Vector2 maximum)
```


Inicializa una caja delimitadora finita con la esquina mínima y máxima dadas

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| minimum | [Vector2](../../com.aspose.threed/vector2) | La esquina mínima |
| maximum | [Vector2](../../com.aspose.threed/vector2) | La esquina máxima |

### BoundingBox2D() {#BoundingBox2D--}
```
public BoundingBox2D()
```


### INFINITE {#INFINITE}
```
public static final BoundingBox2D INFINITE
```


La caja delimitadora infinita

### NULL {#NULL}
```
public static final BoundingBox2D NULL
```


La caja delimitadora nula

### clone() {#clone--}
```
public BoundingBox2D clone()
```


Clonar la instancia actual

**Returns:**
[BoundingBox2D](../../com.aspose.threed/boundingbox2d)
### copyFrom(BoundingBox2D src) {#copyFrom-com.aspose.threed.BoundingBox2D-}
```
public void copyFrom(BoundingBox2D src)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| src | [BoundingBox2D](../../com.aspose.threed/boundingbox2d) |  |

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
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


Obtiene la extensión de la caja delimitadora.

**Returns:**
[BoundingBoxExtent](../../com.aspose.threed/boundingboxextent) - the extent of the bounding box.
### getMaximum() {#getMaximum--}
```
public Vector2 getMaximum()
```


La esquina máxima de la caja delimitadora

**Returns:**
[Vector2](../../com.aspose.threed/vector2) - The maximum corner of the bounding box
### getMinimum() {#getMinimum--}
```
public Vector2 getMinimum()
```


La esquina mínima de la caja delimitadora

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


Fusiona la nueva caja con la caja delimitadora actual.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| bb | [BoundingBox2D](../../com.aspose.threed/boundingbox2d) | La caja delimitadora a fusionar |

### merge(Vector2 pt) {#merge-com.aspose.threed.Vector2-}
```
public void merge(Vector2 pt)
```


Fusiona la nueva caja con la caja delimitadora actual.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| pt | [Vector2](../../com.aspose.threed/vector2) | El punto a fusionar |

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


Obtiene la representación en cadena de la caja delimitadora.

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
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |


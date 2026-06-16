---
title: EndPoint
second_title: Referencia de API de Aspose.3D para Java
description: El punto final para recortar la curva puede ser un valor de parámetro o un punto cartesiano.
type: docs
weight: 51
url: /es/java/com.aspose.threed/endpoint/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.threed.Struct, java.io.Serializable
```
public final class EndPoint implements Struct<EndPoint>, Serializable
```

El punto final para recortar la curva, puede ser un valor de parámetro o un punto cartesiano.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [EndPoint(Vector3 point)](#EndPoint-com.aspose.threed.Vector3-) | Construya un [EndPoint](../../com.aspose.threed/endpoint) a partir de un punto cartesiano. |
| [EndPoint(double v)](#EndPoint-double-) | Construya un [EndPoint](../../com.aspose.threed/endpoint) a partir de un parámetro real. |
| [EndPoint()](#EndPoint--) |  |
## Métodos

| Método | Descripción |
| --- | --- |
| [clone()](#clone--) |  |
| [copyFrom(EndPoint src)](#copyFrom-com.aspose.threed.EndPoint-) |  |
| [equals(Object obj)](#equals-java.lang.Object-) |  |
| [fromDegree(double degree)](#fromDegree-double-) | Cree un punto final medido en grados. |
| [fromRadian(double degree)](#fromRadian-double-) | Cree un punto final medido en radianes. |
| [getAsPoint()](#getAsPoint--) | Obtiene el punto final como punto cartesiano, o lanza una excepción. |
| [getAsValue()](#getAsValue--) | Obtiene el punto final como un parámetro real, o lanza una excepción. |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) |  |
| [isCartesianPoint()](#isCartesianPoint--) | ¿Es el punto final un punto cartesiano? |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) | Devuelve una representación en cadena del punto final actual. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### EndPoint(Vector3 point) {#EndPoint-com.aspose.threed.Vector3-}
```
public EndPoint(Vector3 point)
```


Construya un [EndPoint](../../com.aspose.threed/endpoint) a partir de un punto cartesiano.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| point | [Vector3](../../com.aspose.threed/vector3) | Punto a construir |

### EndPoint(double v) {#EndPoint-double-}
```
public EndPoint(double v)
```


Construya un [EndPoint](../../com.aspose.threed/endpoint) a partir de un parámetro real.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| v | double | El parámetro numérico real para construir un punto final |

### EndPoint() {#EndPoint--}
```
public EndPoint()
```


### clone() {#clone--}
```
public EndPoint clone()
```


Clonar la instancia actual

**Returns:**
[EndPoint](../../com.aspose.threed/endpoint)
### copyFrom(EndPoint src) {#copyFrom-com.aspose.threed.EndPoint-}
```
public void copyFrom(EndPoint src)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| src | [EndPoint](../../com.aspose.threed/endpoint) |  |

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
### fromDegree(double degree) {#fromDegree-double-}
```
public static EndPoint fromDegree(double degree)
```


Cree un punto final medido en grados.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| degree | double | El valor en grados |

**Returns:**
[EndPoint](../../com.aspose.threed/endpoint) - An end point constructed from degree
### fromRadian(double degree) {#fromRadian-double-}
```
public static EndPoint fromRadian(double degree)
```


Cree un punto final medido en radianes.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| degree | double | El valor en radianes |

**Returns:**
[EndPoint](../../com.aspose.threed/endpoint) - An end point constructed from radian
### getAsPoint() {#getAsPoint--}
```
public Vector3 getAsPoint()
```


Obtiene el punto final como punto cartesiano, o lanza una excepción.

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - the end point as Cartesian point, or thrown an exception.
### getAsValue() {#getAsValue--}
```
public double getAsValue()
```


Obtiene el punto final como un parámetro real, o lanza una excepción.

**Returns:**
double - el punto final como un parámetro real, o lanza una excepción.
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


¿Es el punto final un punto cartesiano?

**Returns:**
boolean - ¿Es el punto final un punto cartesiano?
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


Devuelve una representación en cadena del punto final actual.

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


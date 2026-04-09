---
title: EndPoint
second_title: Aspose.3D for Java API Reference
description: Il punto finale per tagliare la curva può essere un valore di parametro o un punto cartesiano.
type: docs
weight: 51
url: /it/java/com.aspose.threed/endpoint/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.threed.Struct, java.io.Serializable
```
public final class EndPoint implements Struct<EndPoint>, Serializable
```

Il punto finale per tagliare la curva, può essere un valore di parametro o un punto cartesiano.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [EndPoint(Vector3 point)](#EndPoint-com.aspose.threed.Vector3-) | Costruisci un [EndPoint](../../com.aspose.threed/endpoint) da un punto cartesiano. |
| [EndPoint(double v)](#EndPoint-double-) | Costruisci un [EndPoint](../../com.aspose.threed/endpoint) da un parametro reale. |
| [EndPoint()](#EndPoint--) |  |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [clone()](#clone--) |  |
| [copyFrom(EndPoint src)](#copyFrom-com.aspose.threed.EndPoint-) |  |
| [equals(Object obj)](#equals-java.lang.Object-) |  |
| [fromDegree(double degree)](#fromDegree-double-) | Crea un punto finale misurato in gradi. |
| [fromRadian(double degree)](#fromRadian-double-) | Crea un punto finale misurato in radianti. |
| [getAsPoint()](#getAsPoint--) | Ottiene il punto finale come punto cartesiano, o lancia un'eccezione. |
| [getAsValue()](#getAsValue--) | Ottiene il punto finale come parametro reale, o lancia un'eccezione. |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) |  |
| [isCartesianPoint()](#isCartesianPoint--) | Il punto finale è un punto cartesiano? |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) | Restituisce una rappresentazione stringa del punto finale corrente. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### EndPoint(Vector3 point) {#EndPoint-com.aspose.threed.Vector3-}
```
public EndPoint(Vector3 point)
```


Costruisci un [EndPoint](../../com.aspose.threed/endpoint) da un punto cartesiano.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| point | [Vector3](../../com.aspose.threed/vector3) | Punto da costruire |

### EndPoint(double v) {#EndPoint-double-}
```
public EndPoint(double v)
```


Costruisci un [EndPoint](../../com.aspose.threed/endpoint) da un parametro reale.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| v | double | Il parametro numero reale per costruire un punto finale |

### EndPoint() {#EndPoint--}
```
public EndPoint()
```


### clone() {#clone--}
```
public EndPoint clone()
```


Clone current instance

**Returns:**
[EndPoint](../../com.aspose.threed/endpoint)
### copyFrom(EndPoint src) {#copyFrom-com.aspose.threed.EndPoint-}
```
public void copyFrom(EndPoint src)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| src | [EndPoint](../../com.aspose.threed/endpoint) |  |

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
### fromDegree(double degree) {#fromDegree-double-}
```
public static EndPoint fromDegree(double degree)
```


Crea un punto finale misurato in gradi.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| degree | double | Il valore in gradi |

**Returns:**
[EndPoint](../../com.aspose.threed/endpoint) - An end point constructed from degree
### fromRadian(double degree) {#fromRadian-double-}
```
public static EndPoint fromRadian(double degree)
```


Crea un punto finale misurato in radianti.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| degree | double | Il valore in radianti |

**Returns:**
[EndPoint](../../com.aspose.threed/endpoint) - An end point constructed from radian
### getAsPoint() {#getAsPoint--}
```
public Vector3 getAsPoint()
```


Ottiene il punto finale come punto cartesiano, o lancia un'eccezione.

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - the end point as Cartesian point, or thrown an exception.
### getAsValue() {#getAsValue--}
```
public double getAsValue()
```


Ottiene il punto finale come parametro reale, o lancia un'eccezione.

**Returns:**
double - il punto finale come parametro reale, o lancia un'eccezione.
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


Il punto finale è un punto cartesiano?

**Returns:**
boolean - Il punto finale è un punto cartesiano?
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


Restituisce una rappresentazione stringa del punto finale corrente.

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


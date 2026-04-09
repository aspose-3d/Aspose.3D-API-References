---
title: EndPoint
second_title: Aspose.3D for Java API-referens
description: Slutpunkten för att trimma kurvan kan vara ett parametervärde eller en kartesisk punkt.
type: docs
weight: 51
url: /sv/java/com.aspose.threed/endpoint/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.threed.Struct, java.io.Serializable
```
public final class EndPoint implements Struct<EndPoint>, Serializable
```

Slutpunkten för att trimma kurvan, kan vara ett parametervärde eller en kartesisk punkt.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [EndPoint(Vector3 point)](#EndPoint-com.aspose.threed.Vector3-) | Skapa en [EndPoint](../../com.aspose.threed/endpoint) från en kartesisk punkt. |
| [EndPoint(double v)](#EndPoint-double-) | Skapa en [EndPoint](../../com.aspose.threed/endpoint) från en reell parameter. |
| [EndPoint()](#EndPoint--) |  |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [clone()](#clone--) |  |
| [copyFrom(EndPoint src)](#copyFrom-com.aspose.threed.EndPoint-) |  |
| [equals(Object obj)](#equals-java.lang.Object-) |  |
| [fromDegree(double degree)](#fromDegree-double-) | Skapa en slutpunkt mätt i grader. |
| [fromRadian(double degree)](#fromRadian-double-) | Skapa en slutpunkt mätt i radianer. |
| [getAsPoint()](#getAsPoint--) | Hämtar slutpunkten som en kartesisk punkt, eller kastar ett undantag. |
| [getAsValue()](#getAsValue--) | Hämtar slutpunkten som en reell parameter, eller kastar ett undantag. |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) |  |
| [isCartesianPoint()](#isCartesianPoint--) | Är slutpunkten en kartesisk punkt? |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) | Returnerar en strängrepresentation av den aktuella slutpunkten. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### EndPoint(Vector3 point) {#EndPoint-com.aspose.threed.Vector3-}
```
public EndPoint(Vector3 point)
```


Skapa en [EndPoint](../../com.aspose.threed/endpoint) från en kartesisk punkt.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| point | [Vector3](../../com.aspose.threed/vector3) | Punkt att konstruera |

### EndPoint(double v) {#EndPoint-double-}
```
public EndPoint(double v)
```


Skapa en [EndPoint](../../com.aspose.threed/endpoint) från en reell parameter.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| v | double | Den reella talparametern för att konstruera en slutpunkt |

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
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| src | [EndPoint](../../com.aspose.threed/endpoint) |  |

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
### fromDegree(double degree) {#fromDegree-double-}
```
public static EndPoint fromDegree(double degree)
```


Skapa en slutpunkt mätt i grader.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| degree | double | Värdet i grader |

**Returns:**
[EndPoint](../../com.aspose.threed/endpoint) - An end point constructed from degree
### fromRadian(double degree) {#fromRadian-double-}
```
public static EndPoint fromRadian(double degree)
```


Skapa en slutpunkt mätt i radianer.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| degree | double | Värdet i radianer |

**Returns:**
[EndPoint](../../com.aspose.threed/endpoint) - An end point constructed from radian
### getAsPoint() {#getAsPoint--}
```
public Vector3 getAsPoint()
```


Hämtar slutpunkten som en kartesisk punkt, eller kastar ett undantag.

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - the end point as Cartesian point, or thrown an exception.
### getAsValue() {#getAsValue--}
```
public double getAsValue()
```


Hämtar slutpunkten som en reell parameter, eller kastar ett undantag.

**Returns:**
double - slutpunkten som en reell parameter, eller kastar ett undantag.
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


Är slutpunkten en kartesisk punkt?

**Returns:**
boolean - är slutpunkten en kartesisk punkt?
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


Returnerar en strängrepresentation av den aktuella slutpunkten.

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


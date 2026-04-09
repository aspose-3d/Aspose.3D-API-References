---
title: EndPoint
second_title: Aspose.3D for Java API-referentie
description: Het eindpunt om de curve bij te snijden kan een parameterwaarde of een cartesisch punt zijn.
type: docs
weight: 51
url: /nl/java/com.aspose.threed/endpoint/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.threed.Struct, java.io.Serializable
```
public final class EndPoint implements Struct<EndPoint>, Serializable
```

Het eindpunt om de curve bij te snijden, kan een parameterwaarde of een Cartesiaans punt zijn.
## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [EndPoint(Vector3 point)](#EndPoint-com.aspose.threed.Vector3-) | Construeer een [EndPoint](../../com.aspose.threed/endpoint) vanuit een cartesisch punt. |
| [EndPoint(double v)](#EndPoint-double-) | Construeer een [EndPoint](../../com.aspose.threed/endpoint) vanuit een reële parameter. |
| [EndPoint()](#EndPoint--) |  |
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [clone()](#clone--) |  |
| [copyFrom(EndPoint src)](#copyFrom-com.aspose.threed.EndPoint-) |  |
| [equals(Object obj)](#equals-java.lang.Object-) |  |
| [fromDegree(double degree)](#fromDegree-double-) | Maak een eindpunt gemeten in graden. |
| [fromRadian(double degree)](#fromRadian-double-) | Maak een eindpunt gemeten in radialen. |
| [getAsPoint()](#getAsPoint--) | Haal het eindpunt op als cartesisch punt, of gooi een uitzondering. |
| [getAsValue()](#getAsValue--) | Haal het eindpunt op als een reële parameter, of gooi een uitzondering. |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) |  |
| [isCartesianPoint()](#isCartesianPoint--) | Is het eindpunt een cartesisch punt? |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) | Retourneert een tekenreeksrepresentatie van het huidige eindpunt. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### EndPoint(Vector3 point) {#EndPoint-com.aspose.threed.Vector3-}
```
public EndPoint(Vector3 point)
```


Construeer een [EndPoint](../../com.aspose.threed/endpoint) vanuit een cartesisch punt.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| point | [Vector3](../../com.aspose.threed/vector3) | Punt om te construeren |

### EndPoint(double v) {#EndPoint-double-}
```
public EndPoint(double v)
```


Construeer een [EndPoint](../../com.aspose.threed/endpoint) vanuit een reële parameter.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| v | double | De reële getalparameter voor het construeren van een eindpunt |

### EndPoint() {#EndPoint--}
```
public EndPoint()
```


### clone() {#clone--}
```
public EndPoint clone()
```


Kloon huidige instantie

**Returns:**
[EndPoint](../../com.aspose.threed/endpoint)
### copyFrom(EndPoint src) {#copyFrom-com.aspose.threed.EndPoint-}
```
public void copyFrom(EndPoint src)
```




**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| src | [EndPoint](../../com.aspose.threed/endpoint) |  |

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
### fromDegree(double degree) {#fromDegree-double-}
```
public static EndPoint fromDegree(double degree)
```


Maak een eindpunt gemeten in graden.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| graad | double | De waarde in graden |

**Returns:**
[EndPoint](../../com.aspose.threed/endpoint) - An end point constructed from degree
### fromRadian(double degree) {#fromRadian-double-}
```
public static EndPoint fromRadian(double degree)
```


Maak een eindpunt gemeten in radialen.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| graad | double | De waarde in radialen |

**Returns:**
[EndPoint](../../com.aspose.threed/endpoint) - An end point constructed from radian
### getAsPoint() {#getAsPoint--}
```
public Vector3 getAsPoint()
```


Haal het eindpunt op als cartesisch punt, of gooi een uitzondering.

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - the end point as Cartesian point, or thrown an exception.
### getAsValue() {#getAsValue--}
```
public double getAsValue()
```


Haal het eindpunt op als een reële parameter, of gooi een uitzondering.

**Returns:**
double - het eindpunt als een reële parameter, of gooi een uitzondering.
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


Is het eindpunt een cartesisch punt?

**Returns:**
boolean - Is het eindpunt een cartesisch punt?
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


Retourneert een tekenreeksrepresentatie van het huidige eindpunt.

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


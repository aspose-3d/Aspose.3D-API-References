---
title: "EndPoint"
second_title: "Référence d'API Aspose.3D pour Java"
description: "Le point final pour tronquer la courbe peut être une valeur de paramètre ou un point cartésien."
type: docs
weight: 51
url: /fr/java/com.aspose.threed/endpoint/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.threed.Struct, java.io.Serializable
```
public final class EndPoint implements Struct<EndPoint>, Serializable
```

Le point final pour tronquer la courbe, peut être une valeur de paramètre ou un point cartésien.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [EndPoint(Vector3 point)](#EndPoint-com.aspose.threed.Vector3-) | Construisez un [EndPoint](../../com.aspose.threed/endpoint) à partir d'un point cartésien. |
| [EndPoint(double v)](#EndPoint-double-) | Construisez un [EndPoint](../../com.aspose.threed/endpoint) à partir d'un paramètre réel. |
| [EndPoint()](#EndPoint--) |  |
## Méthodes

| Méthode | Description |
| --- | --- |
| [clone()](#clone--) |  |
| [copyFrom(EndPoint src)](#copyFrom-com.aspose.threed.EndPoint-) |  |
| [equals(Object obj)](#equals-java.lang.Object-) |  |
| [fromDegree(double degree)](#fromDegree-double-) | Créez un point final mesuré en degrés. |
| [fromRadian(double degree)](#fromRadian-double-) | Créez un point final mesuré en radians. |
| [getAsPoint()](#getAsPoint--) | Obtient le point final en tant que point cartésien, ou lance une exception. |
| [getAsValue()](#getAsValue--) | Obtient le point final en tant que paramètre réel, ou lance une exception. |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) |  |
| [isCartesianPoint()](#isCartesianPoint--) | Le point final est-il un point cartésien ? |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) | Renvoie une représentation sous forme de chaîne du point final actuel. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### EndPoint(Vector3 point) {#EndPoint-com.aspose.threed.Vector3-}
```
public EndPoint(Vector3 point)
```


Construisez un [EndPoint](../../com.aspose.threed/endpoint) à partir d'un point cartésien.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| point | [Vector3](../../com.aspose.threed/vector3) | Point à construire |

### EndPoint(double v) {#EndPoint-double-}
```
public EndPoint(double v)
```


Construisez un [EndPoint](../../com.aspose.threed/endpoint) à partir d'un paramètre réel.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| v | double | Le paramètre nombre réel pour construire un point final |

### EndPoint() {#EndPoint--}
```
public EndPoint()
```


### clone() {#clone--}
```
public EndPoint clone()
```


Cloner l'instance actuelle

**Returns:**
[EndPoint](../../com.aspose.threed/endpoint)
### copyFrom(EndPoint src) {#copyFrom-com.aspose.threed.EndPoint-}
```
public void copyFrom(EndPoint src)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| src | [EndPoint](../../com.aspose.threed/endpoint) |  |

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
### fromDegree(double degree) {#fromDegree-double-}
```
public static EndPoint fromDegree(double degree)
```


Créez un point final mesuré en degrés.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| degré | double | La valeur en degrés |

**Returns:**
[EndPoint](../../com.aspose.threed/endpoint) - An end point constructed from degree
### fromRadian(double degree) {#fromRadian-double-}
```
public static EndPoint fromRadian(double degree)
```


Créez un point final mesuré en radians.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| degré | double | La valeur en radians |

**Returns:**
[EndPoint](../../com.aspose.threed/endpoint) - An end point constructed from radian
### getAsPoint() {#getAsPoint--}
```
public Vector3 getAsPoint()
```


Obtient le point final en tant que point cartésien, ou lance une exception.

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - the end point as Cartesian point, or thrown an exception.
### getAsValue() {#getAsValue--}
```
public double getAsValue()
```


Obtient le point final en tant que paramètre réel, ou lance une exception.

**Returns:**
double - le point final en tant que paramètre réel, ou lance une exception.
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


Le point final est-il un point cartésien ?

**Returns:**
boolean - Le point final est-il un point cartésien ?
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


Renvoie une représentation sous forme de chaîne du point final actuel.

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


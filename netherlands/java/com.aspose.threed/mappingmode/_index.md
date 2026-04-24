---
title: MappingMode
second_title: Aspose.3D for Java API-referentie
description: Bepaalt hoe het element wordt gemapt op een oppervlak.
type: docs
weight: 285
url: /nl/java/com.aspose.threed/mappingmode/
---

**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum MappingMode extends Enum<MappingMode>
```

Determines how the element is mapped to a surface. The [MappingMode](../../com.aspose.threed/mappingmode) defined how [VertexElement](../../com.aspose.threed/vertexelement) is mapped to the surface of geometry.
## Velden

| Veld | Beschrijving |
| --- | --- |
| [ALL_SAME](#ALL-SAME) | Één data toegewezen aan het hele oppervlak. |
| [CONTROL_POINT](#CONTROL-POINT) | Elke data wordt toegewezen aan het controlepunt van de geometrie. |
| [EDGE](#EDGE) | De data wordt toegewezen aan de rand. |
| [POLYGON](#POLYGON) | De data wordt toegewezen aan het polygon. |
| [POLYGON_VERTEX](#POLYGON-VERTEX) | De data wordt toegewezen aan de vertex van het polygon. Wanneer een controlepunt wordt gedeeld door meerdere polygonen, en de data wordt toegewezen als [POLYGON\_VERTEX](../../com.aspose.threed/mappingmode\#POLYGON-VERTEX), zal het controlepunt als verschillende polygon-vertex zijn eigen data hebben. |
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [<T>valueOf(Class<T> arg0, String arg1)](#-T-valueOf-java.lang.Class-T--java.lang.String-) |  |
| [compareTo(E arg0)](#compareTo-E-) |  |
| [describeConstable()](#describeConstable--) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getDeclaringClass()](#getDeclaringClass--) |  |
| [hashCode()](#hashCode--) |  |
| [name()](#name--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [ordinal()](#ordinal--) |  |
| [toString()](#toString--) |  |
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
| [values()](#values--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### ALL_SAME {#ALL-SAME}
```
public static final MappingMode ALL_SAME
```


Één data toegewezen aan het hele oppervlak. Welke data ook wordt geïnterpreteerd als controlepunt/polygon-vertex/rand-eindpunten, de data is altijd hetzelfde als gedefinieerd door [ALL\_SAME](../../com.aspose.threed/mappingmode\#ALL-SAME).

### CONTROL_POINT {#CONTROL-POINT}
```
public static final MappingMode CONTROL_POINT
```


Elke data wordt toegewezen aan het controlepunt van de geometrie.

### EDGE {#EDGE}
```
public static final MappingMode EDGE
```


De data wordt toegewezen aan de rand. Elk rand-eindpunt deelt dezelfde data wanneer de toewijzing [EDGE](../../com.aspose.threed/mappingmode\#EDGE) is.

### POLYGON {#POLYGON}
```
public static final MappingMode POLYGON
```


De data wordt toegewezen aan het polygon. Elke polygon-vertex deelt dezelfde data wanneer de toewijzingsmodus [POLYGON](../../com.aspose.threed/mappingmode\#POLYGON) is.

### POLYGON_VERTEX {#POLYGON-VERTEX}
```
public static final MappingMode POLYGON_VERTEX
```


De data wordt toegewezen aan de vertex van het polygon. Wanneer een controlepunt wordt gedeeld door meerdere polygonen, en de data wordt toegewezen als [POLYGON\_VERTEX](../../com.aspose.threed/mappingmode\#POLYGON-VERTEX), zal het controlepunt als verschillende polygon-vertex zijn eigen data hebben.

### <T>valueOf(Class<T> arg0, String arg1) {#-T-valueOf-java.lang.Class-T--java.lang.String-}
```
public static T <T>valueOf(Class<T> arg0, String arg1)
```




**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| arg0 | java.lang.Class<T> |  |
| arg1 | java.lang.String |  |

**Returns:**
T
### compareTo(E arg0) {#compareTo-E-}
```
public final int compareTo(E arg0)
```




**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| arg0 | E |  |

**Returns:**
int
### describeConstable() {#describeConstable--}
```
public final Optional<Enum.EnumDesc<E>> describeConstable()
```




**Returns:**
java.util.Optional<java.lang.Enum.EnumDesc<E>>
### equals(Object arg0) {#equals-java.lang.Object-}
```
public final boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getDeclaringClass() {#getDeclaringClass--}
```
public final Class<E> getDeclaringClass()
```




**Returns:**
java.lang.Class<E>
### hashCode() {#hashCode--}
```
public final int hashCode()
```




**Returns:**
int
### name() {#name--}
```
public final String name()
```




**Returns:**
java.lang.String
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### ordinal() {#ordinal--}
```
public final int ordinal()
```




**Returns:**
int
### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### valueOf(String name) {#valueOf-java.lang.String-}
```
public static MappingMode valueOf(String name)
```




**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| naam | java.lang.String |  |

**Returns:**
[MappingMode](../../com.aspose.threed/mappingmode)
### values() {#values--}
```
public static MappingMode[] values()
```




**Returns:**
com.aspose.threed.MappingMode[]
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


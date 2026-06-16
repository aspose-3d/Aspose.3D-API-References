---
title: "MappingMode"
second_title: "Référence d'API Aspose.3D pour Java"
description: "Détermine comment l'élément est mappé sur une surface."
type: docs
weight: 285
url: /fr/java/com.aspose.threed/mappingmode/
---

**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum MappingMode extends Enum<MappingMode>
```

Détermine comment l'élément est mappé sur une surface. Le [MappingMode](../../com.aspose.threed/mappingmode) définit comment [VertexElement](../../com.aspose.threed/vertexelement) est mappé sur la surface de la géométrie.
## Champs

| Champ | Description |
| --- | --- |
| [ALL_SAME](#ALL-SAME) | Une donnée mappée sur toute la surface. |
| [CONTROL_POINT](#CONTROL-POINT) | Chaque donnée est mappée au point de contrôle de la géométrie. |
| [EDGE](#EDGE) | La donnée est mappée à l'arête. |
| [POLYGON](#POLYGON) | La donnée est mappée au polygone. |
| [POLYGON_VERTEX](#POLYGON-VERTEX) | La donnée est mappée au sommet du polygone. Lorsqu'un point de contrôle est partagé par plusieurs polygones, et que la donnée est mappée comme [POLYGON\_VERTEX](../../com.aspose.threed/mappingmode\#POLYGON-VERTEX), le point de contrôle en tant que sommet de polygone différent aura ses propres données |
## Méthodes

| Méthode | Description |
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


Une donnée mappée sur toute la surface. Quelle que soit la façon dont la donnée est interprétée comme point de contrôle/sommet de polygone/extremités d'arête, la donnée est toujours la même que celle définie par [ALL\_SAME](../../com.aspose.threed/mappingmode\#ALL-SAME).

### CONTROL_POINT {#CONTROL-POINT}
```
public static final MappingMode CONTROL_POINT
```


Chaque donnée est mappée au point de contrôle de la géométrie.

### EDGE {#EDGE}
```
public static final MappingMode EDGE
```


La donnée est mappée à l'arête. Chaque extrémité d'arête partage la même donnée lorsque le mappage est [EDGE](../../com.aspose.threed/mappingmode\#EDGE).

### POLYGON {#POLYGON}
```
public static final MappingMode POLYGON
```


La donnée est mappée au polygone. Chaque sommet de polygone partage la même donnée lorsque le mode de mappage est [POLYGON](../../com.aspose.threed/mappingmode\#POLYGON).

### POLYGON_VERTEX {#POLYGON-VERTEX}
```
public static final MappingMode POLYGON_VERTEX
```


La donnée est mappée au sommet du polygone. Lorsqu'un point de contrôle est partagé par plusieurs polygones, et que la donnée est mappée comme [POLYGON\_VERTEX](../../com.aspose.threed/mappingmode\#POLYGON-VERTEX), le point de contrôle en tant que sommet de polygone différent aura ses propres données

### <T>valueOf(Class<T> arg0, String arg1) {#-T-valueOf-java.lang.Class-T--java.lang.String-}
```
public static T <T>valueOf(Class<T> arg0, String arg1)
```




**Parameters:**
| Paramètre | Type | Description |
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
| Paramètre | Type | Description |
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
| Paramètre | Type | Description |
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
| Paramètre | Type | Description |
| --- | --- | --- |
| nom | java.lang.String |  |

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


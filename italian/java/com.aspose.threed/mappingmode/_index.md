---
title: MappingMode
second_title: Aspose.3D for Java API Reference
description: Determina come l'elemento è mappato su una superficie.
type: docs
weight: 285
url: /it/java/com.aspose.threed/mappingmode/
---

**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum MappingMode extends Enum<MappingMode>
```

Determina come l'elemento è mappato su una superficie. Il [MappingMode](../../com.aspose.threed/mappingmode) definisce come il [VertexElement](../../com.aspose.threed/vertexelement) è mappato sulla superficie della geometria.
## Campi

| Campo | Descrizione |
| --- | --- |
| [ALL_SAME](#ALL-SAME) | Un dato mappato sull'intera superficie. |
| [CONTROL_POINT](#CONTROL-POINT) | Ogni dato è mappato al punto di controllo della geometria. |
| [EDGE](#EDGE) | Il dato è mappato al bordo. |
| [POLYGON](#POLYGON) | Il dato è mappato al poligono. |
| [POLYGON_VERTEX](#POLYGON-VERTEX) | Il dato è mappato al vertice del poligono. Quando un punto di controllo è condiviso da più poligoni e il dato è mappato come [POLYGON\_VERTEX](../../com.aspose.threed/mappingmode\#POLYGON-VERTEX), il punto di controllo come vertice di poligono diverso avrà i propri dati. |
## Metodi

| Metodo | Descrizione |
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


Un dato mappato sull'intera superficie. Qualunque dato sia interpretato come punto di controllo/vertice del poligono/punti finali del bordo, il dato è sempre lo stesso come definito da [ALL\_SAME](../../com.aspose.threed/mappingmode\#ALL-SAME).

### CONTROL_POINT {#CONTROL-POINT}
```
public static final MappingMode CONTROL_POINT
```


Ogni dato è mappato al punto di controllo della geometria.

### EDGE {#EDGE}
```
public static final MappingMode EDGE
```


Il dato è mappato al bordo. Ogni punto finale del bordo condivide lo stesso dato quando la mappatura è [EDGE](../../com.aspose.threed/mappingmode\#EDGE).

### POLYGON {#POLYGON}
```
public static final MappingMode POLYGON
```


Il dato è mappato al poligono. Ogni vertice del poligono condivide lo stesso dato quando la modalità di mappatura è [POLYGON](../../com.aspose.threed/mappingmode\#POLYGON).

### POLYGON_VERTEX {#POLYGON-VERTEX}
```
public static final MappingMode POLYGON_VERTEX
```


Il dato è mappato al vertice del poligono. Quando un punto di controllo è condiviso da più poligoni e il dato è mappato come [POLYGON\_VERTEX](../../com.aspose.threed/mappingmode\#POLYGON-VERTEX), il punto di controllo come vertice di poligono diverso avrà i propri dati.

### <T>valueOf(Class<T> arg0, String arg1) {#-T-valueOf-java.lang.Class-T--java.lang.String-}
```
public static T <T>valueOf(Class<T> arg0, String arg1)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
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
| Parametro | Tipo | Descrizione |
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
| Parametro | Tipo | Descrizione |
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
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| nome | java.lang.String |  |

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


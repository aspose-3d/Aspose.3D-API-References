---
title: PdfRenderMode
second_title: Aspose.3D for Java API-referens
description: Renderläge specificerar stilen som 3D-konstverket renderas i.
type: docs
weight: 289
url: /sv/java/com.aspose.threed/pdfrendermode/
---

**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum PdfRenderMode extends Enum<PdfRenderMode>
```

Renderläge specificerar stilen som 3D-konstverket renderas i.
## Fält

| Fält | Beskrivning |
| --- | --- |
| [BOUNDING_BOX](#BOUNDING-BOX) | Visar kanterna på varje nods begränsningsbox, justerade med axlarna i den lokala koordinatrymden för den noden. |
| [HIDDEN_WIREFRAME](#HIDDEN-WIREFRAME) | Visar kanter i en enda färg, men tar bort bakvända och dolda kanter. |
| [ILLUSTRATION](#ILLUSTRATION) | Visar silhuettkanter med ytor, tar bort dolda linjer. |
| [SHADED_ILLUSTRATION](#SHADED-ILLUSTRATION) | Visar silhuettkanter med belysta och texturerade ytor samt ett extra emissivt element för att ta bort svagt belysta områden i verket. |
| [SHADED_VERTICES](#SHADED-VERTICES) | Visar endast vertexar, men använder deras vertexfärg och tillämpar ljussättning. |
| [SHADED_WIREFRAME](#SHADED-WIREFRAME) | Visar endast kanter, men interpolerar deras färg mellan deras två vertexar och tillämpar ljussättning. |
| [SOLID](#SOLID) | Visar texturerade och belysta geometriska former. |
| [SOLID_OUTLINE](#SOLID-OUTLINE) | Visar silhuettkanter med belysta och texturerade ytor, tar bort dolda linjer. |
| [SOLID_WIREFRAME](#SOLID-WIREFRAME) | Visar texturerade och belysta geometriska former (trianglar) med enkelfärgade kanter ovanpå dem. |
| [TRANSPARENT](#TRANSPARENT) | Visar texturerade och belysta geometriska former (trianglar) med en extra nivå av transparens. |
| [TRANSPARENT_BOUNDING_BOX](#TRANSPARENT-BOUNDING-BOX) | Visar ytorna på varje nods begränsningsbox, justerade med axlarna i den lokala koordinatrymden för den noden, med en extra nivå av transparens. |
| [TRANSPARENT_BOUNDING_BOX_OUTLINE](#TRANSPARENT-BOUNDING-BOX-OUTLINE) | Visar kanter och ytor på varje nods begränsningsbox, justerade med axlarna i den lokala koordinatrymden för den noden, med en extra nivå av transparens. |
| [TRANSPARENT_WIREFRAME](#TRANSPARENT-WIREFRAME) | Visar texturerade och belysta geometriska former (trianglar) med en extra nivå av transparens, med enkelfärgade ogenomskinliga kanter ovanpå. |
| [VERTICES](#VERTICES) | Visar endast vertexar i en enda färg. |
| [WIREFRAME](#WIREFRAME) | Visar endast kanter i en enda färg. |
## Metoder

| Metod | Beskrivning |
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
### BOUNDING_BOX {#BOUNDING-BOX}
```
public static final PdfRenderMode BOUNDING_BOX
```


Visar kanterna på varje nods begränsningsbox, justerade med axlarna i den lokala koordinatrymden för den noden.

### HIDDEN_WIREFRAME {#HIDDEN-WIREFRAME}
```
public static final PdfRenderMode HIDDEN_WIREFRAME
```


Visar kanter i en enda färg, men tar bort bakvända och dolda kanter.

### ILLUSTRATION {#ILLUSTRATION}
```
public static final PdfRenderMode ILLUSTRATION
```


Visar silhuettkanter med ytor, tar bort dolda linjer.

### SHADED_ILLUSTRATION {#SHADED-ILLUSTRATION}
```
public static final PdfRenderMode SHADED_ILLUSTRATION
```


Visar silhuettkanter med belysta och texturerade ytor samt ett extra emissivt element för att ta bort svagt belysta områden i verket.

### SHADED_VERTICES {#SHADED-VERTICES}
```
public static final PdfRenderMode SHADED_VERTICES
```


Visar endast vertexar, men använder deras vertexfärg och tillämpar ljussättning.

### SHADED_WIREFRAME {#SHADED-WIREFRAME}
```
public static final PdfRenderMode SHADED_WIREFRAME
```


Visar endast kanter, men interpolerar deras färg mellan deras två vertexar och tillämpar ljussättning.

### SOLID {#SOLID}
```
public static final PdfRenderMode SOLID
```


Visar texturerade och belysta geometriska former.

### SOLID_OUTLINE {#SOLID-OUTLINE}
```
public static final PdfRenderMode SOLID_OUTLINE
```


Visar silhuettkanter med belysta och texturerade ytor, tar bort dolda linjer.

### SOLID_WIREFRAME {#SOLID-WIREFRAME}
```
public static final PdfRenderMode SOLID_WIREFRAME
```


Visar texturerade och belysta geometriska former (trianglar) med enkelfärgade kanter ovanpå dem.

### TRANSPARENT {#TRANSPARENT}
```
public static final PdfRenderMode TRANSPARENT
```


Visar texturerade och belysta geometriska former (trianglar) med en extra nivå av transparens.

### TRANSPARENT_BOUNDING_BOX {#TRANSPARENT-BOUNDING-BOX}
```
public static final PdfRenderMode TRANSPARENT_BOUNDING_BOX
```


Visar ytorna på varje nods begränsningsbox, justerade med axlarna i den lokala koordinatrymden för den noden, med en extra nivå av transparens.

### TRANSPARENT_BOUNDING_BOX_OUTLINE {#TRANSPARENT-BOUNDING-BOX-OUTLINE}
```
public static final PdfRenderMode TRANSPARENT_BOUNDING_BOX_OUTLINE
```


Visar kanter och ytor på varje nods begränsningsbox, justerade med axlarna i den lokala koordinatrymden för den noden, med en extra nivå av transparens.

### TRANSPARENT_WIREFRAME {#TRANSPARENT-WIREFRAME}
```
public static final PdfRenderMode TRANSPARENT_WIREFRAME
```


Visar texturerade och belysta geometriska former (trianglar) med en extra nivå av transparens, med enkelfärgade ogenomskinliga kanter ovanpå.

### VERTICES {#VERTICES}
```
public static final PdfRenderMode VERTICES
```


Visar endast vertexar i en enda färg.

### WIREFRAME {#WIREFRAME}
```
public static final PdfRenderMode WIREFRAME
```


Visar endast kanter i en enda färg.

### <T>valueOf(Class<T> arg0, String arg1) {#-T-valueOf-java.lang.Class-T--java.lang.String-}
```
public static T <T>valueOf(Class<T> arg0, String arg1)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
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
| Parameter | Typ | Beskrivning |
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
| Parameter | Typ | Beskrivning |
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
public static PdfRenderMode valueOf(String name)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| namn | java.lang.String |  |

**Returns:**
[PdfRenderMode](../../com.aspose.threed/pdfrendermode)
### values() {#values--}
```
public static PdfRenderMode[] values()
```




**Returns:**
com.aspose.threed.PdfRenderMode[]
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


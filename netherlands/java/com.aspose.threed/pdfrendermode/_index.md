---
title: PdfRenderMode
second_title: Aspose.3D for Java API-referentie
description: Rendermodus specificeert de stijl waarin het 3D-kunstwerk wordt gerenderd.
type: docs
weight: 289
url: /nl/java/com.aspose.threed/pdfrendermode/
---

**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum PdfRenderMode extends Enum<PdfRenderMode>
```

Rendermodus specificeert de stijl waarin het 3D-kunstwerk wordt gerenderd.
## Velden

| Veld | Beschrijving |
| --- | --- |
| [BOUNDING_BOX](#BOUNDING-BOX) | Toont de randen van de begrenzingsdoos van elk knooppunt, uitgelijnd met de assen van de lokale coördinatenruimte voor dat knooppunt. |
| [HIDDEN_WIREFRAME](#HIDDEN-WIREFRAME) | Toont randen in één kleur, maar verwijdert naar achteren gerichte en verduisterde randen. |
| [ILLUSTRATION](#ILLUSTRATION) | Toont silhouetranden met oppervlakken, verwijdert verduisterde lijnen. |
| [SHADED_ILLUSTRATION](#SHADED-ILLUSTRATION) | Toont silhouetranden met verlichte en getextureerde oppervlakken en een extra emissieve term om slecht verlichte gebieden van het kunstwerk te verwijderen. |
| [SHADED_VERTICES](#SHADED-VERTICES) | Toont alleen vertices, maar gebruikt hun vertexkleur en past verlichting toe. |
| [SHADED_WIREFRAME](#SHADED-WIREFRAME) | Toont alleen randen, maar interpoleert hun kleur tussen hun twee vertices en past verlichting toe. |
| [SOLID](#SOLID) | Toont getextureerde en verlichte geometrische vormen. |
| [SOLID_OUTLINE](#SOLID-OUTLINE) | Toont silhouetranden met verlichte en getextureerde oppervlakken, verwijdert verduisterde lijnen. |
| [SOLID_WIREFRAME](#SOLID-WIREFRAME) | Toont getextureerde en verlichte geometrische vormen (driehoeken) met randen in één kleur erboven. |
| [TRANSPARENT](#TRANSPARENT) | Toont getextureerde en verlichte geometrische vormen (driehoeken) met een extra mate van transparantie. |
| [TRANSPARENT_BOUNDING_BOX](#TRANSPARENT-BOUNDING-BOX) | Toont de vlakken van de begrenzingsdozen van elk knooppunt, uitgelijnd met de assen van de lokale coördinatenruimte voor dat knooppunt, met een extra mate van transparantie. |
| [TRANSPARENT_BOUNDING_BOX_OUTLINE](#TRANSPARENT-BOUNDING-BOX-OUTLINE) | Toont de randen en vlakken van de begrenzingsdozen van elk knooppunt, uitgelijnd met de assen van de lokale coördinatenruimte voor dat knooppunt, met een extra mate van transparantie. |
| [TRANSPARENT_WIREFRAME](#TRANSPARENT-WIREFRAME) | Toont getextureerde en verlichte geometrische vormen (driehoeken) met een extra mate van transparantie, met randen in één kleur en ondoorzichtig erboven. |
| [VERTICES](#VERTICES) | Toont alleen vertices in één kleur. |
| [WIREFRAME](#WIREFRAME) | Toont alleen randen in één kleur. |
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
### BOUNDING_BOX {#BOUNDING-BOX}
```
public static final PdfRenderMode BOUNDING_BOX
```


Toont de randen van de begrenzingsdoos van elk knooppunt, uitgelijnd met de assen van de lokale coördinatenruimte voor dat knooppunt.

### HIDDEN_WIREFRAME {#HIDDEN-WIREFRAME}
```
public static final PdfRenderMode HIDDEN_WIREFRAME
```


Toont randen in één kleur, maar verwijdert naar achteren gerichte en verduisterde randen.

### ILLUSTRATION {#ILLUSTRATION}
```
public static final PdfRenderMode ILLUSTRATION
```


Toont silhouetranden met oppervlakken, verwijdert verduisterde lijnen.

### SHADED_ILLUSTRATION {#SHADED-ILLUSTRATION}
```
public static final PdfRenderMode SHADED_ILLUSTRATION
```


Toont silhouetranden met verlichte en getextureerde oppervlakken en een extra emissieve term om slecht verlichte gebieden van het kunstwerk te verwijderen.

### SHADED_VERTICES {#SHADED-VERTICES}
```
public static final PdfRenderMode SHADED_VERTICES
```


Toont alleen vertices, maar gebruikt hun vertexkleur en past verlichting toe.

### SHADED_WIREFRAME {#SHADED-WIREFRAME}
```
public static final PdfRenderMode SHADED_WIREFRAME
```


Toont alleen randen, maar interpoleert hun kleur tussen hun twee vertices en past verlichting toe.

### SOLID {#SOLID}
```
public static final PdfRenderMode SOLID
```


Toont getextureerde en verlichte geometrische vormen.

### SOLID_OUTLINE {#SOLID-OUTLINE}
```
public static final PdfRenderMode SOLID_OUTLINE
```


Toont silhouetranden met verlichte en getextureerde oppervlakken, verwijdert verduisterde lijnen.

### SOLID_WIREFRAME {#SOLID-WIREFRAME}
```
public static final PdfRenderMode SOLID_WIREFRAME
```


Toont getextureerde en verlichte geometrische vormen (driehoeken) met randen in één kleur erboven.

### TRANSPARENT {#TRANSPARENT}
```
public static final PdfRenderMode TRANSPARENT
```


Toont getextureerde en verlichte geometrische vormen (driehoeken) met een extra mate van transparantie.

### TRANSPARENT_BOUNDING_BOX {#TRANSPARENT-BOUNDING-BOX}
```
public static final PdfRenderMode TRANSPARENT_BOUNDING_BOX
```


Toont de vlakken van de begrenzingsdozen van elk knooppunt, uitgelijnd met de assen van de lokale coördinatenruimte voor dat knooppunt, met een extra mate van transparantie.

### TRANSPARENT_BOUNDING_BOX_OUTLINE {#TRANSPARENT-BOUNDING-BOX-OUTLINE}
```
public static final PdfRenderMode TRANSPARENT_BOUNDING_BOX_OUTLINE
```


Toont de randen en vlakken van de begrenzingsdozen van elk knooppunt, uitgelijnd met de assen van de lokale coördinatenruimte voor dat knooppunt, met een extra mate van transparantie.

### TRANSPARENT_WIREFRAME {#TRANSPARENT-WIREFRAME}
```
public static final PdfRenderMode TRANSPARENT_WIREFRAME
```


Toont getextureerde en verlichte geometrische vormen (driehoeken) met een extra mate van transparantie, met randen in één kleur en ondoorzichtig erboven.

### VERTICES {#VERTICES}
```
public static final PdfRenderMode VERTICES
```


Toont alleen vertices in één kleur.

### WIREFRAME {#WIREFRAME}
```
public static final PdfRenderMode WIREFRAME
```


Toont alleen randen in één kleur.

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
public static PdfRenderMode valueOf(String name)
```




**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| naam | java.lang.String |  |

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


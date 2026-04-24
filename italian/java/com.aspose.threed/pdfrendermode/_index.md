---
title: PdfRenderMode
second_title: Aspose.3D for Java API Reference
description: La modalità di rendering specifica lo stile con cui l'opera 3D viene renderizzata.
type: docs
weight: 289
url: /it/java/com.aspose.threed/pdfrendermode/
---

**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum PdfRenderMode extends Enum<PdfRenderMode>
```

La modalità di rendering specifica lo stile con cui l'opera 3D viene renderizzata.
## Campi

| Campo | Descrizione |
| --- | --- |
| [BOUNDING_BOX](#BOUNDING-BOX) | Visualizza i bordi del bounding box di ciascun nodo, allineati con gli assi dello spazio di coordinate locale per quel nodo. |
| [HIDDEN_WIREFRAME](#HIDDEN-WIREFRAME) | Visualizza i bordi in un unico colore, ma rimuove i bordi rivolti verso l'esterno e quelli oscurati. |
| [ILLUSTRATION](#ILLUSTRATION) | Visualizza i bordi silhouette con le superfici, rimuove le linee oscurate. |
| [SHADED_ILLUSTRATION](#SHADED-ILLUSTRATION) | Visualizza i bordi silhouette con superfici illuminate e texturizzate e un termine emissivo aggiuntivo per rimuovere le aree poco illuminate dell'opera. |
| [SHADED_VERTICES](#SHADED-VERTICES) | Visualizza solo i vertici, ma utilizza il loro colore dei vertici e applica l'illuminazione. |
| [SHADED_WIREFRAME](#SHADED-WIREFRAME) | Visualizza solo i bordi, ma interpola il loro colore tra i due vertici e applica l'illuminazione. |
| [SOLID](#SOLID) | Visualizza forme geometriche texturizzate e illuminate. |
| [SOLID_OUTLINE](#SOLID-OUTLINE) | Visualizza i bordi silhouette con superfici illuminate e texturizzate, rimuove le linee oscurate. |
| [SOLID_WIREFRAME](#SOLID-WIREFRAME) | Visualizza forme geometriche texturizzate e illuminate (triangoli) con bordi di colore unico sopra di esse. |
| [TRANSPARENT](#TRANSPARENT) | Visualizza forme geometriche texturizzate e illuminate (triangoli) con un livello aggiunto di trasparenza. |
| [TRANSPARENT_BOUNDING_BOX](#TRANSPARENT-BOUNDING-BOX) | Visualizza le facce dei bounding box di ciascun nodo, allineate con gli assi dello spazio di coordinate locale per quel nodo, con un livello aggiunto di trasparenza. |
| [TRANSPARENT_BOUNDING_BOX_OUTLINE](#TRANSPARENT-BOUNDING-BOX-OUTLINE) | Visualizza i bordi e le facce dei bounding box di ciascun nodo, allineati con gli assi dello spazio di coordinate locale per quel nodo, con un livello aggiunto di trasparenza. |
| [TRANSPARENT_WIREFRAME](#TRANSPARENT-WIREFRAME) | Visualizza forme geometriche texturizzate e illuminate (triangoli) con un livello aggiunto di trasparenza, con bordi opachi di colore unico sopra di esse. |
| [VERTICES](#VERTICES) | Visualizza solo i vertici in un unico colore. |
| [WIREFRAME](#WIREFRAME) | Visualizza solo i bordi in un unico colore. |
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
### BOUNDING_BOX {#BOUNDING-BOX}
```
public static final PdfRenderMode BOUNDING_BOX
```


Visualizza i bordi del bounding box di ciascun nodo, allineati con gli assi dello spazio di coordinate locale per quel nodo.

### HIDDEN_WIREFRAME {#HIDDEN-WIREFRAME}
```
public static final PdfRenderMode HIDDEN_WIREFRAME
```


Visualizza i bordi in un unico colore, ma rimuove i bordi rivolti verso l'esterno e quelli oscurati.

### ILLUSTRATION {#ILLUSTRATION}
```
public static final PdfRenderMode ILLUSTRATION
```


Visualizza i bordi silhouette con le superfici, rimuove le linee oscurate.

### SHADED_ILLUSTRATION {#SHADED-ILLUSTRATION}
```
public static final PdfRenderMode SHADED_ILLUSTRATION
```


Visualizza i bordi silhouette con superfici illuminate e texturizzate e un termine emissivo aggiuntivo per rimuovere le aree poco illuminate dell'opera.

### SHADED_VERTICES {#SHADED-VERTICES}
```
public static final PdfRenderMode SHADED_VERTICES
```


Visualizza solo i vertici, ma utilizza il loro colore dei vertici e applica l'illuminazione.

### SHADED_WIREFRAME {#SHADED-WIREFRAME}
```
public static final PdfRenderMode SHADED_WIREFRAME
```


Visualizza solo i bordi, ma interpola il loro colore tra i due vertici e applica l'illuminazione.

### SOLID {#SOLID}
```
public static final PdfRenderMode SOLID
```


Visualizza forme geometriche texturizzate e illuminate.

### SOLID_OUTLINE {#SOLID-OUTLINE}
```
public static final PdfRenderMode SOLID_OUTLINE
```


Visualizza i bordi silhouette con superfici illuminate e texturizzate, rimuove le linee oscurate.

### SOLID_WIREFRAME {#SOLID-WIREFRAME}
```
public static final PdfRenderMode SOLID_WIREFRAME
```


Visualizza forme geometriche texturizzate e illuminate (triangoli) con bordi di colore unico sopra di esse.

### TRANSPARENT {#TRANSPARENT}
```
public static final PdfRenderMode TRANSPARENT
```


Visualizza forme geometriche texturizzate e illuminate (triangoli) con un livello aggiunto di trasparenza.

### TRANSPARENT_BOUNDING_BOX {#TRANSPARENT-BOUNDING-BOX}
```
public static final PdfRenderMode TRANSPARENT_BOUNDING_BOX
```


Visualizza le facce dei bounding box di ciascun nodo, allineate con gli assi dello spazio di coordinate locale per quel nodo, con un livello aggiunto di trasparenza.

### TRANSPARENT_BOUNDING_BOX_OUTLINE {#TRANSPARENT-BOUNDING-BOX-OUTLINE}
```
public static final PdfRenderMode TRANSPARENT_BOUNDING_BOX_OUTLINE
```


Visualizza i bordi e le facce dei bounding box di ciascun nodo, allineati con gli assi dello spazio di coordinate locale per quel nodo, con un livello aggiunto di trasparenza.

### TRANSPARENT_WIREFRAME {#TRANSPARENT-WIREFRAME}
```
public static final PdfRenderMode TRANSPARENT_WIREFRAME
```


Visualizza forme geometriche texturizzate e illuminate (triangoli) con un livello aggiunto di trasparenza, con bordi opachi di colore unico sopra di esse.

### VERTICES {#VERTICES}
```
public static final PdfRenderMode VERTICES
```


Visualizza solo i vertici in un unico colore.

### WIREFRAME {#WIREFRAME}
```
public static final PdfRenderMode WIREFRAME
```


Visualizza solo i bordi in un unico colore.

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
public static PdfRenderMode valueOf(String name)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| nome | java.lang.String |  |

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


---
title: PdfRenderMode
second_title: Referencia de API de Aspose.3D para Java
description: El modo de renderizado especifica el estilo en el que se renderiza el arte 3D.
type: docs
weight: 289
url: /es/java/com.aspose.threed/pdfrendermode/
---

**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum PdfRenderMode extends Enum<PdfRenderMode>
```

El modo de renderizado especifica el estilo en el que se renderiza el arte 3D.
## Campos

| Campo | Descripción |
| --- | --- |
| [BOUNDING_BOX](#BOUNDING-BOX) | Muestra los bordes de la caja delimitadora de cada nodo, alineados con los ejes del espacio de coordenadas local de ese nodo. |
| [HIDDEN_WIREFRAME](#HIDDEN-WIREFRAME) | Muestra los bordes en un solo color, aunque elimina los bordes que miran hacia atrás y los bordes ocultos. |
| [ILLUSTRATION](#ILLUSTRATION) | Muestra los bordes de silueta con superficies, elimina las líneas ocultas. |
| [SHADED_ILLUSTRATION](#SHADED-ILLUSTRATION) | Muestra los bordes de silueta con superficies iluminadas y texturizadas y un término emisivo adicional para eliminar áreas poco iluminadas de la obra. |
| [SHADED_VERTICES](#SHADED-VERTICES) | Muestra solo los vértices, aunque utiliza su color de vértice y aplica iluminación. |
| [SHADED_WIREFRAME](#SHADED-WIREFRAME) | Muestra solo los bordes, aunque interpola su color entre sus dos vértices y aplica iluminación. |
| [SOLID](#SOLID) | Muestra formas geométricas texturizadas e iluminadas. |
| [SOLID_OUTLINE](#SOLID-OUTLINE) | Muestra los bordes de silueta con superficies iluminadas y texturizadas, elimina las líneas ocultas. |
| [SOLID_WIREFRAME](#SOLID-WIREFRAME) | Muestra formas geométricas texturizadas e iluminadas (triángulos) con bordes de un solo color sobre ellas. |
| [TRANSPARENT](#TRANSPARENT) | Muestra formas geométricas texturizadas e iluminadas (triángulos) con un nivel adicional de transparencia. |
| [TRANSPARENT_BOUNDING_BOX](#TRANSPARENT-BOUNDING-BOX) | Muestra las caras de las cajas delimitadoras de cada nodo, alineadas con los ejes del espacio de coordenadas local de ese nodo, con un nivel adicional de transparencia. |
| [TRANSPARENT_BOUNDING_BOX_OUTLINE](#TRANSPARENT-BOUNDING-BOX-OUTLINE) | Muestra los bordes y caras de las cajas delimitadoras de cada nodo, alineados con los ejes del espacio de coordenadas local de ese nodo, con un nivel adicional de transparencia. |
| [TRANSPARENT_WIREFRAME](#TRANSPARENT-WIREFRAME) | Muestra formas geométricas texturizadas e iluminadas (triángulos) con un nivel adicional de transparencia, con bordes opacos de un solo color sobre ellas. |
| [VERTICES](#VERTICES) | Muestra solo los vértices en un solo color. |
| [WIREFRAME](#WIREFRAME) | Muestra solo los bordes en un solo color. |
## Métodos

| Método | Descripción |
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


Muestra los bordes de la caja delimitadora de cada nodo, alineados con los ejes del espacio de coordenadas local de ese nodo.

### HIDDEN_WIREFRAME {#HIDDEN-WIREFRAME}
```
public static final PdfRenderMode HIDDEN_WIREFRAME
```


Muestra los bordes en un solo color, aunque elimina los bordes que miran hacia atrás y los bordes ocultos.

### ILLUSTRATION {#ILLUSTRATION}
```
public static final PdfRenderMode ILLUSTRATION
```


Muestra los bordes de silueta con superficies, elimina las líneas ocultas.

### SHADED_ILLUSTRATION {#SHADED-ILLUSTRATION}
```
public static final PdfRenderMode SHADED_ILLUSTRATION
```


Muestra los bordes de silueta con superficies iluminadas y texturizadas y un término emisivo adicional para eliminar áreas poco iluminadas de la obra.

### SHADED_VERTICES {#SHADED-VERTICES}
```
public static final PdfRenderMode SHADED_VERTICES
```


Muestra solo los vértices, aunque utiliza su color de vértice y aplica iluminación.

### SHADED_WIREFRAME {#SHADED-WIREFRAME}
```
public static final PdfRenderMode SHADED_WIREFRAME
```


Muestra solo los bordes, aunque interpola su color entre sus dos vértices y aplica iluminación.

### SOLID {#SOLID}
```
public static final PdfRenderMode SOLID
```


Muestra formas geométricas texturizadas e iluminadas.

### SOLID_OUTLINE {#SOLID-OUTLINE}
```
public static final PdfRenderMode SOLID_OUTLINE
```


Muestra los bordes de silueta con superficies iluminadas y texturizadas, elimina las líneas ocultas.

### SOLID_WIREFRAME {#SOLID-WIREFRAME}
```
public static final PdfRenderMode SOLID_WIREFRAME
```


Muestra formas geométricas texturizadas e iluminadas (triángulos) con bordes de un solo color sobre ellas.

### TRANSPARENT {#TRANSPARENT}
```
public static final PdfRenderMode TRANSPARENT
```


Muestra formas geométricas texturizadas e iluminadas (triángulos) con un nivel adicional de transparencia.

### TRANSPARENT_BOUNDING_BOX {#TRANSPARENT-BOUNDING-BOX}
```
public static final PdfRenderMode TRANSPARENT_BOUNDING_BOX
```


Muestra las caras de las cajas delimitadoras de cada nodo, alineadas con los ejes del espacio de coordenadas local de ese nodo, con un nivel adicional de transparencia.

### TRANSPARENT_BOUNDING_BOX_OUTLINE {#TRANSPARENT-BOUNDING-BOX-OUTLINE}
```
public static final PdfRenderMode TRANSPARENT_BOUNDING_BOX_OUTLINE
```


Muestra los bordes y caras de las cajas delimitadoras de cada nodo, alineados con los ejes del espacio de coordenadas local de ese nodo, con un nivel adicional de transparencia.

### TRANSPARENT_WIREFRAME {#TRANSPARENT-WIREFRAME}
```
public static final PdfRenderMode TRANSPARENT_WIREFRAME
```


Muestra formas geométricas texturizadas e iluminadas (triángulos) con un nivel adicional de transparencia, con bordes opacos de un solo color sobre ellas.

### VERTICES {#VERTICES}
```
public static final PdfRenderMode VERTICES
```


Muestra solo los vértices en un solo color.

### WIREFRAME {#WIREFRAME}
```
public static final PdfRenderMode WIREFRAME
```


Muestra solo los bordes en un solo color.

### <T>valueOf(Class<T> arg0, String arg1) {#-T-valueOf-java.lang.Class-T--java.lang.String-}
```
public static T <T>valueOf(Class<T> arg0, String arg1)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
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
| Parámetro | Tipo | Descripción |
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
| Parámetro | Tipo | Descripción |
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
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| nombre | java.lang.String |  |

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
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |


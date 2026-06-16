---
title: VertexElement
second_title: Referencia de API de Aspose.3D para Java
description: Clase base de los elementos de vértice.
type: docs
weight: 207
url: /es/java/com.aspose.threed/vertexelement/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.threed.IIndexedVertexElement](../../com.aspose.threed/iindexedvertexelement)
```
public abstract class VertexElement implements IIndexedVertexElement
```

Clase base de los elementos de vértice. Un tipo de elemento de vértice se identifica mediante VertexElementType. Un VertexElement describe cómo el elemento de vértice se asigna a una superficie geométrica y cómo la información de asignación se organiza en memoria. Un VertexElement contiene normales, UVs u otro tipo de información.
## Métodos

| Método | Descripción |
| --- | --- |
| [clear()](#clear--) | Borra todos los datos de este elemento de vértice. |
| [clone(boolean withData)](#clone-boolean-) | Clona en profundidad el elemento de vértice. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getIndices()](#getIndices--) | Obtiene los datos de los índices. |
| [getMappingMode()](#getMappingMode--) | Obtiene cómo se mapea el elemento. |
| [getName()](#getName--) | Obtiene el nombre. |
| [getReferenceMode()](#getReferenceMode--) | Obtiene cómo se referencia el elemento. |
| [getVertexElementType()](#getVertexElementType--) | Obtiene el tipo del [VertexElement](../../com.aspose.threed/vertexelement) |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setIndices(int[] data)](#setIndices-int---) | Cargar índices |
| [setMappingMode(MappingMode value)](#setMappingMode-com.aspose.threed.MappingMode-) | Establece cómo se mapea el elemento. |
| [setName(String value)](#setName-java.lang.String-) | Establece el nombre. |
| [setReferenceMode(ReferenceMode value)](#setReferenceMode-com.aspose.threed.ReferenceMode-) | Establece cómo se referencia el elemento. |
| [toString()](#toString--) | Representación en cadena del elemento de vértice. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### clear() {#clear--}
```
public abstract void clear()
```


Borra todos los datos de este elemento de vértice.

### clone(boolean withData) {#clone-boolean-}
```
public VertexElement clone(boolean withData)
```


Clona en profundidad el elemento de vértice.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| withData | boolean | Clona el vértice con los arreglos directos e índices |

**Returns:**
[VertexElement](../../com.aspose.threed/vertexelement)
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
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
### getIndices() {#getIndices--}
```
public List<Integer> getIndices()
```


Obtiene los datos de los índices.

**Returns:**
java.util.List<java.lang.Integer> - los datos de los índices
### getMappingMode() {#getMappingMode--}
```
public MappingMode getMappingMode()
```


Obtiene cómo se mapea el elemento.

**Returns:**
[MappingMode](../../com.aspose.threed/mappingmode) - how the element is mapped.
### getName() {#getName--}
```
public String getName()
```


Obtiene el nombre.

**Returns:**
java.lang.String - el nombre.
### getReferenceMode() {#getReferenceMode--}
```
public ReferenceMode getReferenceMode()
```


Obtiene cómo se referencia el elemento.

**Returns:**
[ReferenceMode](../../com.aspose.threed/referencemode) - how the element is referenced.
### getVertexElementType() {#getVertexElementType--}
```
public VertexElementType getVertexElementType()
```


Obtiene el tipo del [VertexElement](../../com.aspose.threed/vertexelement)

**Returns:**
[VertexElementType](../../com.aspose.threed/vertexelementtype) - the type of the [VertexElement](../../com.aspose.threed/vertexelement)
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setIndices(int[] data) {#setIndices-int---}
```
public void setIndices(int[] data)
```


Cargar índices

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| datos | int[] |  |

### setMappingMode(MappingMode value) {#setMappingMode-com.aspose.threed.MappingMode-}
```
public void setMappingMode(MappingMode value)
```


Establece cómo se mapea el elemento.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [MappingMode](../../com.aspose.threed/mappingmode) | Nuevo valor |

### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```


Establece el nombre.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.String | Nuevo valor |

### setReferenceMode(ReferenceMode value) {#setReferenceMode-com.aspose.threed.ReferenceMode-}
```
public void setReferenceMode(ReferenceMode value)
```


Establece cómo se referencia el elemento.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [ReferenceMode](../../com.aspose.threed/referencemode) | Nuevo valor |

### toString() {#toString--}
```
public String toString()
```


Representación en cadena del elemento de vértice.

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


---
title: VertexElementMaterial
second_title: Referencia de API de Aspose.3D para Java
description: Define el índice de material para los componentes especificados.
type: docs
weight: 213
url: /es/java/com.aspose.threed/vertexelementmaterial/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.VertexElement](../../com.aspose.threed/vertexelement)
```
public class VertexElementMaterial extends VertexElement
```

Define el índice de material para los componentes especificados. Un nodo puede tener varios materiales, el [VertexElementMaterial](../../com.aspose.threed/vertexelementmaterial) se utiliza para renderizar diferentes partes de la geometría con diferentes materiales. **Ejemplo:** El siguiente código muestra cómo asignar diferentes materiales a diferentes caras de una caja.

```
// Create a mesh of box(A box is composed by 6 planes)
             Mesh box = (new Box()).ToMesh();
             // Create a material element on this mesh
             VertexElementMaterial mat = (VertexElementMaterial)box.CreateElement(VertexElementType.Material, MappingMode.Polygon, ReferenceMode.Index);
             // And specify different material index for each plane
             mat.Indices.AddRange(new int[] { 0, 1, 2, 3, 4, 5 });
```
## Constructores

| Constructor | Descripción |
| --- | --- |
| [VertexElementMaterial()](#VertexElementMaterial--) | Inicializa una nueva instancia de la clase [VertexElementMaterial](../../com.aspose.threed/vertexelementmaterial). |
## Métodos

| Método | Descripción |
| --- | --- |
| [clear()](#clear--) | Elimina todos los elementos de los arreglos directos y de índices. |
| [clone(boolean withData)](#clone-boolean-) | Clona en profundidad el elemento de vértice. |
| [clone(boolean withDirect, boolean withIndice)](#clone-boolean-boolean-) |  |
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
### VertexElementMaterial() {#VertexElementMaterial--}
```
public VertexElementMaterial()
```


Inicializa una nueva instancia de la clase [VertexElementMaterial](../../com.aspose.threed/vertexelementmaterial).

### clear() {#clear--}
```
public void clear()
```


Elimina todos los elementos de los arreglos directos y de índices.

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
### clone(boolean withDirect, boolean withIndice) {#clone-boolean-boolean-}
```
public VertexElement clone(boolean withDirect, boolean withIndice)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| withDirect | boolean |  |
| withIndice | boolean |  |

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


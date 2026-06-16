---
title: VertexDeclaration
second_title: Referencia de API de Aspose.3D para Java
description: La declaración de una estructura de vértices definida de forma personalizada
type: docs
weight: 206
url: /es/java/com.aspose.threed/vertexdeclaration/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.lang.Iterable, java.lang.Comparable
```
public final class VertexDeclaration implements Iterable<VertexField>, Comparable<VertexDeclaration>
```

La declaración de la estructura de un vértice definido de forma personalizada
## Constructores

| Constructor | Descripción |
| --- | --- |
| [VertexDeclaration()](#VertexDeclaration--) |  |
## Métodos

| Método | Descripción |
| --- | --- |
| [addField(int dataType, VertexFieldSemantic semantic)](#addField-int-com.aspose.threed.VertexFieldSemantic-) | Agregar un nuevo campo de vértice |
| [addField(int dataType, VertexFieldSemantic semantic, int index)](#addField-int-com.aspose.threed.VertexFieldSemantic-int-) | Agregar un nuevo campo de vértice |
| [addField(int dataType, VertexFieldSemantic semantic, int index, String alias)](#addField-int-com.aspose.threed.VertexFieldSemantic-int-java.lang.String-) | Agregar un nuevo campo de vértice |
| [clear()](#clear--) | Borrar todos los campos. |
| [compareTo(VertexDeclaration other)](#compareTo-com.aspose.threed.VertexDeclaration-) | Compara esta instancia con un objeto especificado y devuelve una indicación de sus valores relativos. |
| [equals(Object obj)](#equals-java.lang.Object-) | Determina si esta instancia y un objeto especificado, que también debe ser un objeto [VertexDeclaration](../../com.aspose.threed/vertexdeclaration), tienen el mismo valor. |
| [fromGeometry(Geometry geometry, boolean useFloat)](#fromGeometry-com.aspose.threed.Geometry-boolean-) | Crea un [VertexDeclaration](../../com.aspose.threed/vertexdeclaration) basado en el diseño de una [Geometry](../../com.aspose.threed/geometry). |
| [get(int index)](#get-int-) | Obtiene el [VertexField](../../com.aspose.threed/vertexfield) por índice |
| [getClass()](#getClass--) |  |
| [getCount()](#getCount--) | Obtiene el recuento de todos los campos definidos en este [VertexDeclaration](../../com.aspose.threed/vertexdeclaration) |
| [getSealed()](#getSealed--) | Un [VertexDeclaration](../../com.aspose.threed/vertexdeclaration) será sellado cuando haya sido usado por [TriMesh](../../com.aspose.threed/trimesh), no se permiten más modificaciones. |
| [getSize()](#getSize--) | El tamaño en bytes de la estructura de vértice. |
| [hashCode()](#hashCode--) | Devuelve el código hash para esta cadena. |
| [iterator()](#iterator--) | Obtiene un enumerador para recorrer todos los campos de vértice en esta instancia. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) | Representación en cadena de [VertexDeclaration](../../com.aspose.threed/vertexdeclaration) |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### VertexDeclaration() {#VertexDeclaration--}
```
public VertexDeclaration()
```


### addField(int dataType, VertexFieldSemantic semantic) {#addField-int-com.aspose.threed.VertexFieldSemantic-}
```
public VertexField addField(int dataType, VertexFieldSemantic semantic)
```


Agregar un nuevo campo de vértice

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| dataType | int | El tipo de datos del campo de vértice |
| semantic | [VertexFieldSemantic](../../com.aspose.threed/vertexfieldsemantic) | ¿Para qué se usará este campo? |

**Returns:**
[VertexField](../../com.aspose.threed/vertexfield)
### addField(int dataType, VertexFieldSemantic semantic, int index) {#addField-int-com.aspose.threed.VertexFieldSemantic-int-}
```
public VertexField addField(int dataType, VertexFieldSemantic semantic, int index)
```


Agregar un nuevo campo de vértice

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| dataType | int | El tipo de datos del campo de vértice |
| semantic | [VertexFieldSemantic](../../com.aspose.threed/vertexfieldsemantic) | ¿Para qué se usará este campo? |
| índice | int | El índice para la misma semántica de campo, -1 para generación automática |

**Returns:**
[VertexField](../../com.aspose.threed/vertexfield)
### addField(int dataType, VertexFieldSemantic semantic, int index, String alias) {#addField-int-com.aspose.threed.VertexFieldSemantic-int-java.lang.String-}
```
public VertexField addField(int dataType, VertexFieldSemantic semantic, int index, String alias)
```


Agregar un nuevo campo de vértice

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| dataType | int | El tipo de datos del campo de vértice |
| semantic | [VertexFieldSemantic](../../com.aspose.threed/vertexfieldsemantic) | ¿Para qué se usará este campo? |
| índice | int | El índice para la misma semántica de campo, -1 para generación automática |
| alias | java.lang.String | El nombre alias del campo |

**Returns:**
[VertexField](../../com.aspose.threed/vertexfield)
### clear() {#clear--}
```
public void clear()
```


Borrar todos los campos.

### compareTo(VertexDeclaration other) {#compareTo-com.aspose.threed.VertexDeclaration-}
```
public int compareTo(VertexDeclaration other)
```


Compara esta instancia con un objeto especificado y devuelve una indicación de sus valores relativos.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| other | [VertexDeclaration](../../com.aspose.threed/vertexdeclaration) |  |

**Returns:**
int
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Determina si esta instancia y un objeto especificado, que también debe ser un objeto [VertexDeclaration](../../com.aspose.threed/vertexdeclaration), tienen el mismo valor.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| obj | java.lang.Object |  |

**Returns:**
boolean
### fromGeometry(Geometry geometry, boolean useFloat) {#fromGeometry-com.aspose.threed.Geometry-boolean-}
```
public static VertexDeclaration fromGeometry(Geometry geometry, boolean useFloat)
```


Crea un [VertexDeclaration](../../com.aspose.threed/vertexdeclaration) basado en el diseño de una [Geometry](../../com.aspose.threed/geometry).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| geometry | [Geometry](../../com.aspose.threed/geometry) |  |
| useFloat | boolean | Usar float en lugar del tipo double |

**Returns:**
[VertexDeclaration](../../com.aspose.threed/vertexdeclaration)
### get(int index) {#get-int-}
```
public VertexField get(int index)
```


Obtiene el [VertexField](../../com.aspose.threed/vertexfield) por índice

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| índice | int |  |

**Returns:**
[VertexField](../../com.aspose.threed/vertexfield) - the [VertexField](../../com.aspose.threed/vertexfield) by index
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getCount() {#getCount--}
```
public int getCount()
```


Obtiene el recuento de todos los campos definidos en este [VertexDeclaration](../../com.aspose.threed/vertexdeclaration)

**Returns:**
int - el recuento de todos los campos definidos en este [VertexDeclaration](../../com.aspose.threed/vertexdeclaration)
### getSealed() {#getSealed--}
```
public boolean getSealed()
```


Un [VertexDeclaration](../../com.aspose.threed/vertexdeclaration) será sellado cuando haya sido usado por [TriMesh](../../com.aspose.threed/trimesh), no se permiten más modificaciones.

**Returns:**
boolean - Un [VertexDeclaration](../../com.aspose.threed/vertexdeclaration) será sellado cuando haya sido usado por [TriMesh](../../com.aspose.threed/trimesh), no se permiten más modificaciones.
### getSize() {#getSize--}
```
public int getSize()
```


El tamaño en bytes de la estructura de vértice.

**Returns:**
int - El tamaño en bytes de la estructura del vértice.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Devuelve el código hash para esta cadena.

**Returns:**
int - Un código hash entero de 32 bits con signo.
### iterator() {#iterator--}
```
public Iterator<VertexField> iterator()
```


Obtiene un enumerador para recorrer todos los campos de vértice en esta instancia.

**Returns:**
java.util.Iterator<com.aspose.threed.VertexField> - Enumerador
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


Representación en cadena de [VertexDeclaration](../../com.aspose.threed/vertexdeclaration)

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


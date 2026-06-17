---
title: "VertexDeclaration"
second_title: "Referencia de API de Aspose.3D para Node.js vía Java"
description: 
type: docs

url: /es/nodejs-java/aspose.threed/vertexdeclaration/
---
## VertexDeclaration class

La declaración de la estructura de un vértice definido de forma personalizada


## Métodos

### constructor{#constructor}

| Nombre | Descripción |
| --- | --- |
| constructor() |  |

 **Result:**



---


### getSealed{#getSealed}

| Nombre | Descripción |
| --- | --- |
| getSealed() | Una VertexDeclaration se sellará cuando haya sido usada por com.aspose.threed.TriMesh`1 o TriMesh, no se permiten más modificaciones. |

 **Result:**



---


### getCount{#getCount}

| Nombre | Descripción |
| --- | --- |
| getCount() | Obtiene el recuento de todos los campos definidos en esta VertexDeclaration. |

 **Result:**



---


### getSize{#getSize}

| Nombre | Descripción |
| --- | --- |
| getSize() | El tamaño en bytes de la estructura del vértice. |

 **Result:**



---


### get{#get}

| Nombre | Descripción |
| --- | --- |
| get(index) |  |

 **Result:**



---


### clear{#clear}

| Nombre | Descripción |
| --- | --- |
| clear() | Borrar todos los campos. |

 **Result:**



---


### addField{#addField}

| Nombre | Descripción |
| --- | --- |
| addField(dataType, semantic, index, alias) | Agregar un nuevo campo de vértice |

 **Parameters:**

| Nombre | Tipo | Descripción |
| --- | --- | --- |
| dataType | Número | VertexFieldDataType |
| semantic | VertexFieldSemantic | VertexFieldSemantic |
| index | Número | El índice para el mismo semántico de campo, -1 para generación automática |
| alias | Cadena | El nombre alias del campo |

 **Result:**



---


### fromGeometry{#fromGeometry}

| Nombre | Descripción |
| --- | --- |
| fromGeometry(geometry, useFloat) | Crear una VertexDeclaration basada en la disposición de una Geometry. |

 **Parameters:**

| Nombre | Tipo | Descripción |
| --- | --- | --- |
| geometría | Geometría | null |
| useFloat | boolean | Usar float en lugar del tipo double |

 **Result:**
VertexDeclaration


---


### compareTo{#compareTo}

| Nombre | Descripción |
| --- | --- |
| compareTo(other) | Compara esta instancia con un objeto especificado y devuelve una indicación de sus valores relativos. |

 **Result:**
VertexDeclaration


---


### toString{#toString}

| Nombre | Descripción |
| --- | --- |
| toString() |  |

 **Result:**
Cadena


---


### hashCode{#hashCode}

| Nombre | Descripción |
| --- | --- |
| hashCode() |  |

 **Result:**
Número


---


### equals{#equals}

| Nombre | Descripción |
| --- | --- |
| equals(obj) | Determina si esta instancia y un objeto especificado, que también debe ser un objeto VertexDeclaration, tienen el mismo valor. |

 **Result:**
Número


---


### iterator{#iterator}

| Nombre | Descripción |
| --- | --- |
| iterator() | Reservado para uso interno. |

 **Result:**
Número


---




---
title: "TriMesh"
second_title: "Referencia de API de Aspose.3D para Node.js vía Java"
description: 
type: docs

url: /es/nodejs-java/aspose.threed/trimesh/
---
## TriMesh class

Un TriMesh contiene datos sin procesar que pueden ser usados directamente por la GPU.  Esta clase es una utilidad para ayudar a construir una malla que solo contiene datos por vértice.


## Métodos

### constructor{#constructor}

| Nombre | Descripción |
| --- | --- |
| constructor(name, declaration) | Inicializar una instancia de TriMesh |

 **Parameters:**

| Nombre | Tipo | Descripción |
| --- | --- | --- |
| name | Cadena | El nombre de este TriMesh |
| declaración | VertexDeclaration | La declaración del vértice |

 **Result:**



---


### getVertexDeclaration{#getVertexDeclaration}

| Nombre | Descripción |
| --- | --- |
| getVertexDeclaration() | La disposición de vértices del TriMesh. |

 **Result:**



---


### getVerticesCount{#getVerticesCount}

| Nombre | Descripción |
| --- | --- |
| getVerticesCount() | El número de vértices en este TriMesh |

 **Result:**



---


### getIndicesCount{#getIndicesCount}

| Nombre | Descripción |
| --- | --- |
| getIndicesCount() | El número de índices en este TriMesh |

 **Result:**



---


### getUnmergedVerticesCount{#getUnmergedVerticesCount}

| Nombre | Descripción |
| --- | --- |
| getUnmergedVerticesCount() | El número de vértices no fusionados que se pasaron mediante beginVertex() y endVertex(). |

 **Result:**



---


### getCapacity{#getCapacity}

| Nombre | Descripción |
| --- | --- |
| getCapacity() | La capacidad de los vértices preasignados. |

 **Result:**



---


### getVerticesSizeInBytes{#getVerticesSizeInBytes}

| Nombre | Descripción |
| --- | --- |
| getVerticesSizeInBytes() | El tamaño total de todos los vértices en bytes |

 **Result:**



---


### getParentNodes{#getParentNodes}

| Nombre | Descripción |
| --- | --- |
| getParentNodes() | Obtiene todos los nodos padre; una entidad puede estar adjunta a varios nodos padre para la instanciación de geometría. Los nodos. |

 **Result:**



---


### getExcluded{#getExcluded}

| Nombre | Descripción |
| --- | --- |
| getExcluded() | Obtiene o establece si excluir esta entidad durante la exportación. |

 **Result:**



---


### setExcluded{#setExcluded}

| Nombre | Descripción |
| --- | --- |
| setExcluded(value) | Obtiene o establece si excluir esta entidad durante la exportación. |

 **Result:**



---


### getParentNode{#getParentNode}

| Nombre | Descripción |
| --- | --- |
| getParentNode() | Obtiene o establece el primer nodo padre; si se establece el primer nodo padre, esta entidad se separará de los demás nodos padres. El nodo padre. |

 **Result:**



---


### setParentNode{#setParentNode}

| Nombre | Descripción |
| --- | --- |
| setParentNode(value) | Obtiene o establece el primer nodo padre; si se establece el primer nodo padre, esta entidad se separará de los demás nodos padres. El nodo padre. |

 **Result:**



---


### getScene{#getScene}

| Nombre | Descripción |
| --- | --- |
| getScene() | Obtiene la escena a la que pertenece este objeto |

 **Result:**



---


### getName{#getName}

| Nombre | Descripción |
| --- | --- |
| getName() | Obtiene o establece el nombre. El nombre. |

 **Result:**



---


### setName{#setName}

| Nombre | Descripción |
| --- | --- |
| setName(value) | Obtiene o establece el nombre. El nombre. |

 **Result:**



---


### getProperties{#getProperties}

| Nombre | Descripción |
| --- | --- |
| getProperties() | Obtiene la colección de todas las propiedades. |

 **Result:**



---


### fromMesh{#fromMesh}

| Nombre | Descripción |
| --- | --- |
| fromMesh(declaration, mesh) | Crea un TriMesh a partir del objeto mesh dado con la disposición de vértices especificada. |

 **Parameters:**

| Nombre | Tipo | Descripción |
| --- | --- | --- |
| declaración | VertexDeclaration | null |
| malla | Malla | null |

 **Result:**
TriMesh


---


### copyFrom{#copyFrom}

| Nombre | Descripción |
| --- | --- |
| copyFrom(input, vd) | Copia el TriMesh de la entrada con una nueva disposición de vértices |

 **Parameters:**

| Nombre | Tipo | Descripción |
| --- | --- | --- |
| input | TriMesh | El TriMesh de entrada para copiar |
| vd | VertexDeclaration | La nueva declaración de vértices del TriMesh de salida |

 **Result:**
TriMesh


---


### fromMesh{#fromMesh}

| Nombre | Descripción |
| --- | --- |
| fromMesh(mesh, useFloat) | Crea un TriMesh a partir del objeto mesh dado, la declaración de vértices se basa en la estructura del mesh de entrada. |

 **Parameters:**

| Nombre | Tipo | Descripción |
| --- | --- | --- |
| malla | Malla | null |
| useFloat | boolean | Utiliza el tipo float en lugar del tipo double para cada componente del elemento de vértice. |

 **Result:**
TriMesh


---


### beginVertex{#beginVertex}

| Nombre | Descripción |
| --- | --- |
| beginVertex() | Comienza a agregar vértice |

 **Result:**
Vértice


---


### endVertex{#endVertex}

| Nombre | Descripción |
| --- | --- |
| endVertex() | Finalizar la adición del vértice |

 **Result:**
Vértice


---


### verticesToArray{#verticesToArray}

| Nombre | Descripción |
| --- | --- |
| verticesToArray() | Convertir los datos de los vértices a un arreglo de bytes |

 **Result:**
byte[]


---


### toString{#toString}

| Nombre | Descripción |
| --- | --- |
| toString() |  |

 **Result:**
Cadena


---


### fromRawData{#fromRawData}

| Nombre | Descripción |
| --- | --- |
| fromRawData(vd, vertices, indices, generateVertexMapping) | Crear TriMesh a partir de datos sin procesar. El TriMesh devuelto no copiará el arreglo de bytes de entrada por rendimiento; los cambios externos en el arreglo se reflejarán en esta instancia. |

 **Parameters:**

| Nombre | Tipo | Descripción |
| --- | --- | --- |
| vd | VertexDeclaration | Declaración de vértice, debe contener al menos un campo. |
| vertices | byte[] | Los datos de vértice de entrada, la longitud mínima de los vértices debe ser mayor o igual al tamaño de la declaración de vértice. |
| indices | Number[] | Los índices de triángulo |
| generateVertexMapping | boolean | Generar |

 **Result:**
TriMesh


---


### loadVerticesFromBytes{#loadVerticesFromBytes}

| Nombre | Descripción |
| --- | --- |
| loadVerticesFromBytes(verticesInBytes) | Cargar vértices desde bytes, la longitud de los bytes debe ser un múltiplo entero del tamaño del vértice. |

 **Parameters:**

| Nombre | Tipo | Descripción |
| --- | --- | --- |
| verticesInByte | byte[] | null |

 **Result:**
TriMesh


---


### readVector4{#readVector4}

| Nombre | Descripción |
| --- | --- |
| readVector4(idx, field) | Leer el campo vector4 |

 **Parameters:**

| Nombre | Tipo | Descripción |
| --- | --- | --- |
| idx | Número | El índice del vértice a leer |
| field | VertexField | El campo con un tipo de datos Vector4/FVector4 |

 **Result:**
Vector4


---


### readFVector4{#readFVector4}

| Nombre | Descripción |
| --- | --- |
| readFVector4(idx, field) | Leer el campo vector4 |

 **Parameters:**

| Nombre | Tipo | Descripción |
| --- | --- | --- |
| idx | Número | El índice del vértice a leer |
| field | VertexField | El campo con un tipo de datos Vector4/FVector4 |

 **Result:**
FVector4


---


### readVector3{#readVector3}

| Nombre | Descripción |
| --- | --- |
| readVector3(idx, field) | Leer el campo vector3 |

 **Parameters:**

| Nombre | Tipo | Descripción |
| --- | --- | --- |
| idx | Número | El índice del vértice a leer |
| field | VertexField | El campo con un tipo de datos Vector3/FVector3 |

 **Result:**
Vector3


---


### readFVector3{#readFVector3}

| Nombre | Descripción |
| --- | --- |
| readFVector3(idx, field) | Leer el campo vector3 |

 **Parameters:**

| Nombre | Tipo | Descripción |
| --- | --- | --- |
| idx | Número | El índice del vértice a leer |
| field | VertexField | El campo con un tipo de datos Vector3/FVector3 |

 **Result:**
FVector3


---


### readVector2{#readVector2}

| Nombre | Descripción |
| --- | --- |
| readVector2(idx, field) | Leer el campo vector2 |

 **Parameters:**

| Nombre | Tipo | Descripción |
| --- | --- | --- |
| idx | Número | El índice del vértice a leer |
| field | VertexField | El campo con un tipo de datos Vector2/FVector2 |

 **Result:**
Vector2


---


### readFVector2{#readFVector2}

| Nombre | Descripción |
| --- | --- |
| readFVector2(idx, field) | Leer el campo vector2 |

 **Parameters:**

| Nombre | Tipo | Descripción |
| --- | --- | --- |
| idx | Número | El índice del vértice a leer |
| field | VertexField | El campo con un tipo de datos Vector2/FVector2 |

 **Result:**
FVector2


---


### readDouble{#readDouble}

| Nombre | Descripción |
| --- | --- |
| readDouble(idx, field) | Leer el campo double |

 **Parameters:**

| Nombre | Tipo | Descripción |
| --- | --- | --- |
| idx | Número | El índice del vértice a leer |
| field | VertexField | El campo con un tipo de datos compatible con float/double |

 **Result:**
Número


---


### readFloat{#readFloat}

| Nombre | Descripción |
| --- | --- |
| readFloat(idx, field) | Leer el campo float |

 **Parameters:**

| Nombre | Tipo | Descripción |
| --- | --- | --- |
| idx | Número | El índice del vértice a leer |
| field | VertexField | El campo con un tipo de datos compatible con float/double |

 **Result:**
Número


---


### getBoundingBox{#getBoundingBox}

| Nombre | Descripción |
| --- | --- |
| getBoundingBox() | Obtiene el cuadro delimitador de la entidad actual en su sistema de coordenadas de espacio de objeto. |

 **Result:**
Número


---


### getEntityRendererKey{#getEntityRendererKey}

| Nombre | Descripción |
| --- | --- |
| getEntityRendererKey() | Obtiene la clave del renderizador de entidad registrado en el renderizador |

 **Result:**
EntityRendererKey


---


### removeProperty{#removeProperty}

| Nombre | Descripción |
| --- | --- |
| removeProperty(property) | Elimina una propiedad dinámica. |

 **Parameters:**

| Nombre | Tipo | Descripción |
| --- | --- | --- |
| property | Property | Qué propiedad eliminar |

 **Result:**
boolean


---


### removeProperty{#removeProperty}

| Nombre | Descripción |
| --- | --- |
| removeProperty(property) | Eliminar la propiedad especificada identificada por nombre |

 **Parameters:**

| Nombre | Tipo | Descripción |
| --- | --- | --- |
| propert | Cadena | null |

 **Result:**
boolean


---


### getProperty{#getProperty}

| Nombre | Descripción |
| --- | --- |
| getProperty(property) | Obtener el valor de la propiedad especificada |

 **Parameters:**

| Nombre | Tipo | Descripción |
| --- | --- | --- |
| property | Cadena | Nombre de la propiedad |

 **Result:**
Objeto


---


### setProperty{#setProperty}

| Nombre | Descripción |
| --- | --- |
| setProperty(property, value) | Establece el valor de la propiedad especificada |

 **Parameters:**

| Nombre | Tipo | Descripción |
| --- | --- | --- |
| property | Cadena | Nombre de la propiedad |
| valor | Objeto | El valor de la propiedad |

 **Result:**
Objeto


---


### findProperty{#findProperty}

| Nombre | Descripción |
| --- | --- |
| findProperty(propertyName) | Busca la propiedad. Puede ser una propiedad dinámica (Creada por CreateDynamicProperty/SetProperty) o una propiedad nativa (Identificada por su nombre) |

 **Parameters:**

| Nombre | Tipo | Descripción |
| --- | --- | --- |
| propertyName | Cadena | Nombre de la propiedad. |

 **Result:**
Property


---


### iterator{#iterator}

| Nombre | Descripción |
| --- | --- |
| iterator() | Reservado para uso interno. |

 **Result:**
Property


---




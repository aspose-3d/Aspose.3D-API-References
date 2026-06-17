---
title: "Forma"
second_title: "Referencia de API de Aspose.3D para Node.js vía Java"
description: 
type: docs

url: /es/nodejs-java/aspose.threed/shape/
---
## Shape class

La forma describe la deformación en un conjunto de puntos de control, lo cual es similar al deformador de clúster en Maya.  Por ejemplo, podemos añadir una forma a una geometría creada.  Y la forma y la geometría tienen la misma información topológica pero diferentes posiciones de los puntos de control.  Con diferentes niveles de influencia, la geometría produce un efecto de deformación.


## Métodos

### constructor{#constructor}

| Nombre | Descripción |
| --- | --- |
| constructor() | Inicializa una nueva instancia de la clase Shape. |

 **Result:**



---


### constructor_overload{#constructor_overload}

| Nombre | Descripción |
| --- | --- |
| constructor_overload(name) | Inicializa una nueva instancia de la clase Shape. |

 **Parameters:**

| Nombre | Tipo | Descripción |
| --- | --- | --- |
| name | Cadena | Nombre |

 **Result:**



---


### getIndices{#getIndices}

| Nombre | Descripción |
| --- | --- |
| getIndices() | Obtiene los índices. Los índices. |

 **Result:**



---


### getVisible{#getVisible}

| Nombre | Descripción |
| --- | --- |
| getVisible() | Obtiene o establece si la geometría es visible |

 **Result:**



---


### setVisible{#setVisible}

| Nombre | Descripción |
| --- | --- |
| setVisible(value) | Obtiene o establece si la geometría es visible |

 **Result:**



---


### getDeformers{#getDeformers}

| Nombre | Descripción |
| --- | --- |
| getDeformers() | Obtiene todos los deformadores asociados con esta geometría. Los deformadores. |

 **Result:**



---


### getControlPoints{#getControlPoints}

| Nombre | Descripción |
| --- | --- |
| getControlPoints() | Obtiene todos los puntos de control |

 **Result:**



---


### getCastShadows{#getCastShadows}

| Nombre | Descripción |
| --- | --- |
| getCastShadows() | Obtiene o establece si esta geometría puede proyectar sombra |

 **Result:**



---


### setCastShadows{#setCastShadows}

| Nombre | Descripción |
| --- | --- |
| setCastShadows(value) | Obtiene o establece si esta geometría puede proyectar sombra |

 **Result:**



---


### getReceiveShadows{#getReceiveShadows}

| Nombre | Descripción |
| --- | --- |
| getReceiveShadows() | Obtiene o establece si esta geometría puede recibir sombra. |

 **Result:**



---


### setReceiveShadows{#setReceiveShadows}

| Nombre | Descripción |
| --- | --- |
| setReceiveShadows(value) | Obtiene o establece si esta geometría puede recibir sombra. |

 **Result:**



---


### getVertexElements{#getVertexElements}

| Nombre | Descripción |
| --- | --- |
| getVertexElements() | Obtiene todos los elementos de vértice |

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


### fromControlPoints{#fromControlPoints}

| Nombre | Descripción |
| --- | --- |
| fromControlPoints(controlPoints) | Crea una forma con puntos de control especificados con índices predeterminados. |

 **Parameters:**

| Nombre | Tipo | Descripción |
| --- | --- | --- |
| controlPoint | Vector3[] | null |

 **Result:**
Forma


---


### getElement{#getElement}

| Nombre | Descripción |
| --- | --- |
| getElement(type) | Obtiene un elemento de vértice con el tipo especificado |

 **Parameters:**

| Nombre | Tipo | Descripción |
| --- | --- | --- |
| type | VertexElementType | VertexElementType |

 **Result:**
VertexElement


---


### getVertexElementOfUV{#getVertexElementOfUV}

| Nombre | Descripción |
| --- | --- |
| getVertexElementOfUV(textureMapping) | Obtiene una instancia de VertexElementUV con el tipo de TextureMapping dado |

 **Parameters:**

| Nombre | Tipo | Descripción |
| --- | --- | --- |
| textureMapping | TextureMapping | TextureMapping |

 **Result:**
VertexElementUV


---


### createElement{#createElement}

| Nombre | Descripción |
| --- | --- |
| createElement(type) | Crea un elemento de vértice con el tipo especificado y lo agrega a la geometría. Si el tipo es VertexElementType.UV, se creará un VertexElementUV con el tipo de mapeo de textura a TextureMapping.DIFFUSE. |

 **Parameters:**

| Nombre | Tipo | Descripción |
| --- | --- | --- |
| type | VertexElementType | VertexElementType |

 **Result:**
VertexElement


---


### addElement{#addElement}

| Nombre | Descripción |
| --- | --- |
| addElement(element) | Agrega un elemento de vértice existente a la geometría actual |

 **Parameters:**

| Nombre | Tipo | Descripción |
| --- | --- | --- |
| element | VertexElement | El elemento de vértice a agregar |

 **Result:**
VertexElement


---


### createElement{#createElement}

| Nombre | Descripción |
| --- | --- |
| createElement(type, mappingMode, referenceMode) | Crea un elemento de vértice con el tipo especificado y lo agrega a la geometría. Si el tipo es VertexElementType.UV, se creará un VertexElementUV con el tipo de mapeo de textura a TextureMapping.DIFFUSE. |

 **Parameters:**

| Nombre | Tipo | Descripción |
| --- | --- | --- |
| type | VertexElementType | VertexElementType |
| mappingMode | MappingMode | MappingMode |
| referenceMode | ReferenceMode | ReferenceMode |

 **Result:**
VertexElement


---


### createElementUV{#createElementUV}

| Nombre | Descripción |
| --- | --- |
| createElementUV(uvMapping) | Crea un VertexElementUV con el tipo de mapeo de textura dado. |

 **Parameters:**

| Nombre | Tipo | Descripción |
| --- | --- | --- |
| uvMapping | TextureMapping | TextureMapping |

 **Result:**
VertexElementUV


---


### createElementUV{#createElementUV}

| Nombre | Descripción |
| --- | --- |
| createElementUV(uvMapping, mappingMode, referenceMode) | Crea un VertexElementUV con el tipo de mapeo de textura dado. |

 **Parameters:**

| Nombre | Tipo | Descripción |
| --- | --- | --- |
| uvMapping | TextureMapping | TextureMapping |
| mappingMode | MappingMode | MappingMode |
| referenceMode | ReferenceMode | ReferenceMode |

 **Result:**
VertexElementUV


---


### getBoundingBox{#getBoundingBox}

| Nombre | Descripción |
| --- | --- |
| getBoundingBox() | Obtiene el cuadro delimitador de la entidad actual en su sistema de coordenadas de espacio de objeto. |

 **Result:**
VertexElementUV


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




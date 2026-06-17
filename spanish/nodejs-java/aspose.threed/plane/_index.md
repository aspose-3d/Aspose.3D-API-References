---
title: "Plane"
second_title: "Referencia de API de Aspose.3D para Node.js vía Java"
description: 
type: docs

url: /es/nodejs-java/aspose.threed/plane/
---
## Plane class

Plano parametrizado.


## Métodos

### constructor{#constructor}

| Nombre | Descripción |
| --- | --- |
| constructor() | Inicializa una nueva instancia de Plane con tamaño predeterminado de 1x1. |

 **Result:**



---


### constructor_overload{#constructor_overload}

| Nombre | Descripción |
| --- | --- |
| constructor_overload(length, width) | Inicializa una nueva instancia del Plano. |

 **Parameters:**

| Nombre | Tipo | Descripción |
| --- | --- | --- |
| length | Número | Longitud del plano. |
| ancho | Número | Ancho del plano. |

 **Result:**



---


### constructor_overload2{#constructor_overload2}

| Nombre | Descripción |
| --- | --- |
| constructor_overload2(name, length, width, lengthSegments, widthSegments) | Inicializa una nueva instancia del Plano. |

 **Parameters:**

| Nombre | Tipo | Descripción |
| --- | --- | --- |
| name | Cadena | Nombre. |
| length | Número | Longitud del plano. |
| ancho | Número | Ancho del plano. |
| lengthSegments | Número | Segmentos de longitud. |
| widthSegments | Número | Segmentos de ancho. |

 **Result:**



---


### getUp{#getUp}

| Nombre | Descripción |
| --- | --- |
| getUp() | Obtiene o establece el vector ascendente del plano, el valor predeterminado es (0, 1, 0), esto afecta la generación del plano |

 **Result:**



---


### setUp{#setUp}

| Nombre | Descripción |
| --- | --- |
| setUp(value) | Obtiene o establece el vector ascendente del plano, el valor predeterminado es (0, 1, 0), esto afecta la generación del plano |

 **Result:**



---


### getLength{#getLength}

| Nombre | Descripción |
| --- | --- |
| getLength() | Obtiene o establece la longitud del plano. La longitud. |

 **Result:**



---


### setLength{#setLength}

| Nombre | Descripción |
| --- | --- |
| setLength(value) | Obtiene o establece la longitud del plano. La longitud. |

 **Result:**



---


### getWidth{#getWidth}

| Nombre | Descripción |
| --- | --- |
| getWidth() | Obtiene o establece el ancho del plano. El ancho. |

 **Result:**



---


### setWidth{#setWidth}

| Nombre | Descripción |
| --- | --- |
| setWidth(value) | Obtiene o establece el ancho del plano. El ancho. |

 **Result:**



---


### getLengthSegments{#getLengthSegments}

| Nombre | Descripción |
| --- | --- |
| getLengthSegments() | Obtiene o establece los segmentos de longitud. Los segmentos de longitud. |

 **Result:**



---


### setLengthSegments{#setLengthSegments}

| Nombre | Descripción |
| --- | --- |
| setLengthSegments(value) | Obtiene o establece los segmentos de longitud. Los segmentos de longitud. |

 **Result:**



---


### getWidthSegments{#getWidthSegments}

| Nombre | Descripción |
| --- | --- |
| getWidthSegments() | Obtiene o establece los segmentos de ancho. Los segmentos de ancho. |

 **Result:**



---


### setWidthSegments{#setWidthSegments}

| Nombre | Descripción |
| --- | --- |
| setWidthSegments(value) | Obtiene o establece los segmentos de ancho. Los segmentos de ancho. |

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


### toMesh{#toMesh}

| Nombre | Descripción |
| --- | --- |
| toMesh() | Convertir el objeto actual a malla |

 **Result:**
Malla


---


### getBoundingBox{#getBoundingBox}

| Nombre | Descripción |
| --- | --- |
| getBoundingBox() | Obtiene el cuadro delimitador de la entidad actual en su sistema de coordenadas de espacio de objeto. |

 **Result:**
Malla


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




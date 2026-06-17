---
title: "TShape"
second_title: "Referencia de API de Aspose.3D para Node.js vía Java"
description: 
type: docs

url: /es/nodejs-java/aspose.threed/tshape/
---
## TShape class

Forma en T compatible con IFC definida por parámetros.


## Métodos

### constructor{#constructor}

| Nombre | Descripción |
| --- | --- |
| constructor() | Constructor de TShape |

 **Result:**



---


### getDepth{#getDepth}

| Nombre | Descripción |
| --- | --- |
| getDepth() | Obtiene o establece la longitud del web. |

 **Result:**



---


### setDepth{#setDepth}

| Nombre | Descripción |
| --- | --- |
| setDepth(value) | Obtiene o establece la longitud del web. |

 **Result:**



---


### getFlangeWidth{#getFlangeWidth}

| Nombre | Descripción |
| --- | --- |
| getFlangeWidth() | Obtiene o establece la longitud del flange. |

 **Result:**



---


### setFlangeWidth{#setFlangeWidth}

| Nombre | Descripción |
| --- | --- |
| setFlangeWidth(value) | Obtiene o establece la longitud del flange. |

 **Result:**



---


### getWebThickness{#getWebThickness}

| Nombre | Descripción |
| --- | --- |
| getWebThickness() | Obtiene o establece el espesor de la pared del web. |

 **Result:**



---


### setWebThickness{#setWebThickness}

| Nombre | Descripción |
| --- | --- |
| setWebThickness(value) | Obtiene o establece el espesor de la pared del web. |

 **Result:**



---


### getFlangeThickness{#getFlangeThickness}

| Nombre | Descripción |
| --- | --- |
| getFlangeThickness() | Obtiene o establece el espesor de la pared del flange. |

 **Result:**



---


### setFlangeThickness{#setFlangeThickness}

| Nombre | Descripción |
| --- | --- |
| setFlangeThickness(value) | Obtiene o establece el espesor de la pared del flange. |

 **Result:**



---


### getFilletRadius{#getFilletRadius}

| Nombre | Descripción |
| --- | --- |
| getFilletRadius() | Obtiene o establece el radio del filete entre el alma y el flanco. |

 **Result:**



---


### setFilletRadius{#setFilletRadius}

| Nombre | Descripción |
| --- | --- |
| setFilletRadius(value) | Obtiene o establece el radio del filete entre el alma y el flanco. |

 **Result:**



---


### getFlangeEdgeRadius{#getFlangeEdgeRadius}

| Nombre | Descripción |
| --- | --- |
| getFlangeEdgeRadius() | Obtiene o establece el radio del borde del flanco. |

 **Result:**



---


### setFlangeEdgeRadius{#setFlangeEdgeRadius}

| Nombre | Descripción |
| --- | --- |
| setFlangeEdgeRadius(value) | Obtiene o establece el radio del borde del flanco. |

 **Result:**



---


### getWebEdgeRadius{#getWebEdgeRadius}

| Nombre | Descripción |
| --- | --- |
| getWebEdgeRadius() | Obtiene o establece el radio del borde del alma. |

 **Result:**



---


### setWebEdgeRadius{#setWebEdgeRadius}

| Nombre | Descripción |
| --- | --- |
| setWebEdgeRadius(value) | Obtiene o establece el radio del borde del alma. |

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


### getExtent{#getExtent}

| Nombre | Descripción |
| --- | --- |
| getExtent() | Obtiene la extensión en las dimensiones x e y. |

 **Result:**
Vector2


---


### getEntityRendererKey{#getEntityRendererKey}

| Nombre | Descripción |
| --- | --- |
| getEntityRendererKey() | Obtiene la clave del renderizador de entidad registrado en el renderizador |

 **Result:**
EntityRendererKey


---


### getBoundingBox{#getBoundingBox}

| Nombre | Descripción |
| --- | --- |
| getBoundingBox() | Obtiene el cuadro delimitador de la entidad actual en su sistema de coordenadas de espacio de objeto. |

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




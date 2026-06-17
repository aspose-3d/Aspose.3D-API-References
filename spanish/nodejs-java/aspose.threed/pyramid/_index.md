---
title: "Pyramid"
second_title: "Referencia de API de Aspose.3D para Node.js vía Java"
description: 
type: docs

url: /es/nodejs-java/aspose.threed/pyramid/
---
## Pyramid class

Pirámide parametrizada.


## Métodos

### constructor{#constructor}

| Nombre | Descripción |
| --- | --- |
| constructor() | Construye una nueva instancia de pyramid con el área inferior predeterminada (10, 10) y la altura predeterminada (5). |

 **Result:**



---


### constructor_overload{#constructor_overload}

| Nombre | Descripción |
| --- | --- |
| constructor_overload(xbottom, ybottom, height) | Construye una nueva instancia de pyramid con el área inferior especificada |

 **Parameters:**

| Nombre | Tipo | Descripción |
| --- | --- | --- |
| xbottom | Número | La longitud en la dirección x de la parte inferior |
| ybottom | Número | La longitud en la dirección y de la parte inferior |
| height | Número | La altura de la pyramid |

 **Result:**



---


### constructor_overload2{#constructor_overload2}

| Nombre | Descripción |
| --- | --- |
| constructor_overload2(xbottom, ybottom, xtop, ytop, height) | Construye una nueva instancia de pyramid con el área inferior y el área superior especificadas y la altura. |

 **Parameters:**

| Nombre | Tipo | Descripción |
| --- | --- | --- |
| xbottom | Número | La longitud en la dirección x del área inferior |
| ybottom | Número | La longitud en la dirección y del área inferior |
| xtop | Número | La longitud en la dirección x del área superior |
| ytop | Número | La longitud en la dirección y del área superior |
| height | Número | La altura de la pyramid |

 **Result:**



---


### constructor_overload3{#constructor_overload3}

| Nombre | Descripción |
| --- | --- |
| constructor_overload3(name, xbottom, ybottom, xtop, ytop, height) | Construye una nueva instancia de pyramid con el área inferior y el área superior especificadas y la altura. |

 **Parameters:**

| Nombre | Tipo | Descripción |
| --- | --- | --- |
| name | Cadena | El nombre de la pirámide |
| xbottom | Número | La longitud en la dirección x del área inferior |
| ybottom | Número | La longitud en la dirección y del área inferior |
| xtop | Número | La longitud en la dirección x del área superior |
| ytop | Número | La longitud en la dirección y del área superior |
| height | Número | La altura de la pyramid |

 **Result:**



---


### getBottomArea{#getBottomArea}

| Nombre | Descripción |
| --- | --- |
| getBottomArea() | Área de la tapa inferior |

 **Result:**



---


### setBottomArea{#setBottomArea}

| Nombre | Descripción |
| --- | --- |
| setBottomArea(value) | Área de la tapa inferior |

 **Result:**



---


### getTopArea{#getTopArea}

| Nombre | Descripción |
| --- | --- |
| getTopArea() | Área de la tapa superior |

 **Result:**



---


### setTopArea{#setTopArea}

| Nombre | Descripción |
| --- | --- |
| setTopArea(value) | Área de la tapa superior |

 **Result:**



---


### getBottomOffset{#getBottomOffset}

| Nombre | Descripción |
| --- | --- |
| getBottomOffset() | Desplazamiento para los vértices inferiores |

 **Result:**



---


### setBottomOffset{#setBottomOffset}

| Nombre | Descripción |
| --- | --- |
| setBottomOffset(value) | Desplazamiento para los vértices inferiores |

 **Result:**



---


### getHeight{#getHeight}

| Nombre | Descripción |
| --- | --- |
| getHeight() | Altura de la pirámide |

 **Result:**



---


### setHeight{#setHeight}

| Nombre | Descripción |
| --- | --- |
| setHeight(value) | Altura de la pirámide |

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




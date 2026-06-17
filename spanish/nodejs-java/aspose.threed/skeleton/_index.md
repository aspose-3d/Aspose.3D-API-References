---
title: "Esqueleto"
second_title: "Referencia de API de Aspose.3D para Node.js vía Java"
description: 
type: docs

url: /es/nodejs-java/aspose.threed/skeleton/
---
## Skeleton class

El esqueleto se usa principalmente en software CAD para ayudar al diseñador a manipular la transformación de la estructura esquelética; suele ser inútil fuera de los softwares CAD. Para que la jerarquía del esqueleto actúe como un solo objeto en el software CAD, es necesario marcar el nodo superior del Skeleton como la raíz estableciendo Type a SkeletonType.SKELETON, y todos los hijos a SkeletonType.BONE.


## Métodos

### constructor{#constructor}

| Nombre | Descripción |
| --- | --- |
| constructor() | Inicializa una nueva instancia de la clase Skeleton. |

 **Result:**



---


### constructor_overload{#constructor_overload}

| Nombre | Descripción |
| --- | --- |
| constructor_overload(name) | Inicializa una nueva instancia de la clase Skeleton. |

 **Parameters:**

| Nombre | Tipo | Descripción |
| --- | --- | --- |
| name | Cadena | Nombre. |

 **Result:**



---


### getSize{#getSize}

| Nombre | Descripción |
| --- | --- |
| getSize() | Obtiene o establece el tamaño del nodo de extremidad que se usa en el software CAD para representar el tamaño del hueso. |

 **Result:**



---


### setSize{#setSize}

| Nombre | Descripción |
| --- | --- |
| setSize(value) | Obtiene o establece el tamaño del nodo de extremidad que se usa en el software CAD para representar el tamaño del hueso. |

 **Result:**



---


### getType{#getType}

| Nombre | Descripción |
| --- | --- |
| getType() | Obtiene o establece el tipo del esqueleto. El valor de la propiedad es la constante entera SkeletonType. El tipo del esqueleto. |

 **Result:**



---


### setType{#setType}

| Nombre | Descripción |
| --- | --- |
| setType(value) | Obtiene o establece el tipo del esqueleto. El valor de la propiedad es la constante entera SkeletonType. El tipo del esqueleto. |

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


### getBoundingBox{#getBoundingBox}

| Nombre | Descripción |
| --- | --- |
| getBoundingBox() | Obtiene el cuadro delimitador de la entidad actual en su sistema de coordenadas de espacio de objeto. |

 **Result:**



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




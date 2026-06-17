---
title: "RevolvedAreaSolid"
second_title: "Referencia de API de Aspose.3D para Node.js vía Java"
description: 
type: docs

url: /es/nodejs-java/aspose.threed/revolvedareasolid/
---
## RevolvedAreaSolid class

Esta clase representa un modelo sólido al girar una sección transversal proporcionada por un perfil alrededor de un eje.


## Métodos

### constructor{#constructor}

| Nombre | Descripción |
| --- | --- |
| constructor() |  |

 **Result:**



---


### getAngleStart{#getAngleStart}

| Nombre | Descripción |
| --- | --- |
| getAngleStart() | Obtiene o establece el ángulo inicial del procedimiento de revolución, medido en radianes, el valor predeterminado es 0. |

 **Result:**



---


### setAngleStart{#setAngleStart}

| Nombre | Descripción |
| --- | --- |
| setAngleStart(value) | Obtiene o establece el ángulo inicial del procedimiento de revolución, medido en radianes, el valor predeterminado es 0. |

 **Result:**



---


### getAngleEnd{#getAngleEnd}

| Nombre | Descripción |
| --- | --- |
| getAngleEnd() | Obtiene o establece el ángulo final del procedimiento de revolución, medido en radianes, el valor predeterminado es pi. |

 **Result:**



---


### setAngleEnd{#setAngleEnd}

| Nombre | Descripción |
| --- | --- |
| setAngleEnd(value) | Obtiene o establece el ángulo final del procedimiento de revolución, medido en radianes, el valor predeterminado es pi. |

 **Result:**



---


### getAxis{#getAxis}

| Nombre | Descripción |
| --- | --- |
| getAxis() | Obtiene o establece la dirección del eje, el valor predeterminado es (0, 1, 0). |

 **Result:**



---


### setAxis{#setAxis}

| Nombre | Descripción |
| --- | --- |
| setAxis(value) | Obtiene o establece la dirección del eje, el valor predeterminado es (0, 1, 0). |

 **Result:**



---


### getOrigin{#getOrigin}

| Nombre | Descripción |
| --- | --- |
| getOrigin() | Obtiene o establece el punto de origen de la revolución, el valor predeterminado es (0, 0, 0). |

 **Result:**



---


### setOrigin{#setOrigin}

| Nombre | Descripción |
| --- | --- |
| setOrigin(value) | Obtiene o establece el punto de origen de la revolución, el valor predeterminado es (0, 0, 0). |

 **Result:**



---


### getShape{#getShape}

| Nombre | Descripción |
| --- | --- |
| getShape() | Obtiene o establece el perfil base utilizado para la revolución. |

 **Result:**



---


### setShape{#setShape}

| Nombre | Descripción |
| --- | --- |
| setShape(value) | Obtiene o establece el perfil base utilizado para la revolución. |

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
| toMesh() | Convierte el RevolvedAreaSolid en una malla. |

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




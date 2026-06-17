---
title: "LinearExtrusion"
second_title: "Referencia de API de Aspose.3D para Node.js vía Java"
description: 
type: docs

url: /es/nodejs-java/aspose.threed/linearextrusion/
---
## LinearExtrusion class

La extrusión lineal toma una forma 2D como entrada y extiende la forma en la tercera dimensión.


## Métodos

### constructor{#constructor}

| Nombre | Descripción |
| --- | --- |
| constructor() | Constructor de la instancia LinearExtrusion. |

 **Result:**



---


### constructor_overload{#constructor_overload}

| Nombre | Descripción |
| --- | --- |
| constructor_overload(shape, height) | Constructor de la instancia LinearExtrusion. |

 **Result:**



---


### getShape{#getShape}

| Nombre | Descripción |
| --- | --- |
| getShape() | La forma base que se extruirá. |

 **Result:**



---


### setShape{#setShape}

| Nombre | Descripción |
| --- | --- |
| setShape(value) | La forma base que se extruirá. |

 **Result:**



---


### getDirection{#getDirection}

| Nombre | Descripción |
| --- | --- |
| getDirection() | La dirección de la extrusión, el valor predeterminado es (0, 0, 1) |

 **Result:**



---


### setDirection{#setDirection}

| Nombre | Descripción |
| --- | --- |
| setDirection(value) | La dirección de la extrusión, el valor predeterminado es (0, 0, 1) |

 **Result:**



---


### getHeight{#getHeight}

| Nombre | Descripción |
| --- | --- |
| getHeight() | La altura de la geometría extruida, el valor predeterminado es 1.0 |

 **Result:**



---


### setHeight{#setHeight}

| Nombre | Descripción |
| --- | --- |
| setHeight(value) | La altura de la geometría extruida, el valor predeterminado es 1.0 |

 **Result:**



---


### getSlices{#getSlices}

| Nombre | Descripción |
| --- | --- |
| getSlices() | Las capas de la geometría extruida y retorcida, el valor predeterminado es 1. |

 **Result:**



---


### setSlices{#setSlices}

| Nombre | Descripción |
| --- | --- |
| setSlices(value) | Las capas de la geometría extruida y retorcida, el valor predeterminado es 1. |

 **Result:**



---


### getCenter{#getCenter}

| Nombre | Descripción |
| --- | --- |
| getCenter() | Si este valor es false, el rango Z de la extrusión lineal es de 0 a la altura; de lo contrario, el rango es de -altura/2 a altura/2. |

 **Result:**



---


### setCenter{#setCenter}

| Nombre | Descripción |
| --- | --- |
| setCenter(value) | Si este valor es false, el rango Z de la extrusión lineal es de 0 a la altura; de lo contrario, el rango es de -altura/2 a altura/2. |

 **Result:**



---


### getTwistOffset{#getTwistOffset}

| Nombre | Descripción |
| --- | --- |
| getTwistOffset() | El desplazamiento usado en la torsión, el valor predeterminado es (0, 0, 0). |

 **Result:**



---


### setTwistOffset{#setTwistOffset}

| Nombre | Descripción |
| --- | --- |
| setTwistOffset(value) | El desplazamiento usado en la torsión, el valor predeterminado es (0, 0, 0). |

 **Result:**



---


### getTwist{#getTwist}

| Nombre | Descripción |
| --- | --- |
| getTwist() | El número de grados a través de los cuales se extruye la forma. |

 **Result:**



---


### setTwist{#setTwist}

| Nombre | Descripción |
| --- | --- |
| setTwist(value) | El número de grados a través de los cuales se extruye la forma. |

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
| toMesh() | Convertir la extrusión a malla. |

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




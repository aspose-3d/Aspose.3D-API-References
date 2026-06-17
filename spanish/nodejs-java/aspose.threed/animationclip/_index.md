---
title: "AnimationClip"
second_title: "Referencia de API de Aspose.3D para Node.js vía Java"
description: 
type: docs

url: /es/nodejs-java/aspose.threed/animationclip/
---
## AnimationClip class

El clip de Animación es una colección de animaciones.  La escena puede tener uno o más clips de animación.


## Métodos

### constructor{#constructor}

| Nombre | Descripción |
| --- | --- |
| constructor() | Inicializa una nueva instancia de la clase AnimationClip. |

 **Result:**



---


### constructor_overload{#constructor_overload}

| Nombre | Descripción |
| --- | --- |
| constructor_overload(name) | Inicializa una nueva instancia de la clase AnimationClip. |

 **Parameters:**

| Nombre | Tipo | Descripción |
| --- | --- | --- |
| name | Cadena | Nombre |

 **Result:**



---


### getAnimations{#getAnimations}

| Nombre | Descripción |
| --- | --- |
| getAnimations() | Obtiene las animaciones contenidas dentro del clip. Las capas. |

 **Result:**



---


### getDescription{#getDescription}

| Nombre | Descripción |
| --- | --- |
| getDescription() | Obtiene o establece la descripción de este clip de animación |

 **Result:**



---


### setDescription{#setDescription}

| Nombre | Descripción |
| --- | --- |
| setDescription(value) | Obtiene o establece la descripción de este clip de animación |

 **Result:**



---


### getStart{#getStart}

| Nombre | Descripción |
| --- | --- |
| getStart() | Obtiene o establece el tiempo en segundos del inicio del clip. |

 **Result:**



---


### setStart{#setStart}

| Nombre | Descripción |
| --- | --- |
| setStart(value) | Obtiene o establece el tiempo en segundos del inicio del clip. |

 **Result:**



---


### getStop{#getStop}

| Nombre | Descripción |
| --- | --- |
| getStop() | Obtiene o establece el tiempo en segundos del final del clip. |

 **Result:**



---


### setStop{#setStop}

| Nombre | Descripción |
| --- | --- |
| setStop(value) | Obtiene o establece el tiempo en segundos del final del clip. |

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


### createAnimationNode{#createAnimationNode}

| Nombre | Descripción |
| --- | --- |
| createAnimationNode(nodeName) | Una función abreviada para crear y registrar el nodo de animación en el clip actual. |

 **Parameters:**

| Nombre | Tipo | Descripción |
| --- | --- | --- |
| nodeName | Cadena | Nombre del nuevo nodo de animación |

 **Result:**
AnimationNode


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




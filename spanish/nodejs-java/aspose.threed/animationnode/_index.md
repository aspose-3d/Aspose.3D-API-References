---
title: "AnimationNode"
second_title: "Referencia de API de Aspose.3D para Node.js vía Java"
description: 
type: docs

url: /es/nodejs-java/aspose.threed/animationnode/
---
## AnimationNode class

Aspose.3D admite jerarquía de animación, cada animación puede estar compuesta por varias animaciones y la definición de fotogramas clave de la animación.  AnimationNode define la transformación del valor de una propiedad a lo largo del tiempo, por ejemplo, el nodo de animación puede usarse para controlar la transformación de un nodo o otras propiedades numéricas del objeto A3DObject.


## Métodos

### constructor{#constructor}

| Nombre | Descripción |
| --- | --- |
| constructor(name) | Inicializa una nueva instancia de la clase AnimationNode. |

 **Parameters:**

| Nombre | Tipo | Descripción |
| --- | --- | --- |
| name | Cadena | Nombre |

 **Result:**



---


### constructor_overload{#constructor_overload}

| Nombre | Descripción |
| --- | --- |
| constructor_overload() | Inicializa una nueva instancia de la clase AnimationNode. |

 **Result:**



---


### getBindPoints{#getBindPoints}

| Nombre | Descripción |
| --- | --- |
| getBindPoints() | Obtiene los puntos de enlace de propiedad actuales |

 **Result:**



---


### getSubAnimations{#getSubAnimations}

| Nombre | Descripción |
| --- | --- |
| getSubAnimations() | Obtiene los nodos de subanimación bajo las animaciones actuales |

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


### findBindPoint{#findBindPoint}

| Nombre | Descripción |
| --- | --- |
| findBindPoint(name) | Busca el punto de enlace por nombre. |

 **Parameters:**

| Nombre | Tipo | Descripción |
| --- | --- | --- |
| name | Cadena | Nombre del punto de enlace a buscar. |

 **Result:**
BindPoint


---


### getBindPoint{#getBindPoint}

| Nombre | Descripción |
| --- | --- |
| getBindPoint(target, propName, create) | Obtiene el punto de enlace de animación en la propiedad dada. |

 **Parameters:**

| Nombre | Tipo | Descripción |
| --- | --- | --- |
| target | A3DObject | En qué objeto crear el punto de enlace. |
| propName | Cadena | El nombre de la propiedad. |
| crear | boolean | Si se establece en |

 **Result:**
BindPoint


---


### getKeyframeSequence{#getKeyframeSequence}

| Nombre | Descripción |
| --- | --- |
| getKeyframeSequence(target, propName, channelName, create) | Obtiene la secuencia de fotogramas clave en la propiedad y canal dados. |

 **Parameters:**

| Nombre | Tipo | Descripción |
| --- | --- | --- |
| target | A3DObject | En qué instancia crear la secuencia de fotogramas clave. |
| propName | Cadena | El nombre de la propiedad. |
| channelName | Cadena | El nombre del canal. |
| crear | boolean | Si se establece en |

 **Result:**
KeyframeSequence


---


### getKeyframeSequence{#getKeyframeSequence}

| Nombre | Descripción |
| --- | --- |
| getKeyframeSequence(target, propName, create) | Obtiene la secuencia de fotogramas clave en la propiedad dada. |

 **Parameters:**

| Nombre | Tipo | Descripción |
| --- | --- | --- |
| target | A3DObject | En qué instancia crear la secuencia de fotogramas clave. |
| propName | Cadena | El nombre de la propiedad. |
| crear | boolean | Si se establece en |

 **Result:**
KeyframeSequence


---


### createBindPoint{#createBindPoint}

| Nombre | Descripción |
| --- | --- |
| createBindPoint(obj, propName) | Crea un BindPoint basado en el tipo de datos de la propiedad. |

 **Parameters:**

| Nombre | Tipo | Descripción |
| --- | --- | --- |
| obj | A3DObject | Object. |
| propName | Cadena | Nombre de la propiedad. |

 **Result:**
BindPoint


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




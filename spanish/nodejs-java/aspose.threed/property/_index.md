---
title: "Property"
second_title: "Referencia de API de Aspose.3D para Node.js vía Java"
description: 
type: docs

url: /es/nodejs-java/aspose.threed/property/
---
## Property class

Clase para contener propiedades definidas por el usuario.  @hideconstructor


## Métodos

### getValue{#getValue}

| Nombre | Descripción |
| --- | --- |
| getValue() | Obtiene o establece el valor. El valor. |

 **Result:**



---


### setValue{#setValue}

| Nombre | Descripción |
| --- | --- |
| setValue(value) | Obtiene o establece el valor. El valor. |

 **Result:**



---


### setName{#setName}

| Nombre | Descripción |
| --- | --- |
| setName(value) |  |

 **Result:**



---


### getValueType{#getValueType}

| Nombre | Descripción |
| --- | --- |
| getValueType() | Obtiene el tipo del valor de la propiedad. El tipo del valor. |

 **Result:**



---


### getProperties{#getProperties}

| Nombre | Descripción |
| --- | --- |
| getProperties() | Obtiene la colección de todas las propiedades. |

 **Result:**



---


### getBindPoint{#getBindPoint}

| Nombre | Descripción |
| --- | --- |
| getBindPoint(anim, create) | Obtiene el punto de enlace de la propiedad en la instancia de animación especificada. |

 **Parameters:**

| Nombre | Tipo | Descripción |
| --- | --- | --- |
| anim | AnimationNode | En qué animación crear el punto de enlace. |
| crear | boolean | Crear el punto de enlace de la propiedad si no se encuentra. |

 **Result:**
BindPoint


---


### getKeyframeSequence{#getKeyframeSequence}

| Nombre | Descripción |
| --- | --- |
| getKeyframeSequence(anim, create) | Obtiene la secuencia de fotogramas clave en la instancia de animación especificada. |

 **Parameters:**

| Nombre | Tipo | Descripción |
| --- | --- | --- |
| anim | AnimationNode | En qué animación crear la secuencia de fotogramas clave. |
| crear | boolean | Crear la secuencia de fotogramas clave si no se encuentra. |

 **Result:**
KeyframeSequence


---


### toString{#toString}

| Nombre | Descripción |
| --- | --- |
| toString() | Devuelve una cadena que representa la Propiedad actual. |

 **Result:**
Cadena


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




---
title: "KeyframeSequence"
second_title: "Referencia de API de Aspose.3D para Node.js vía Java"
description: 
type: docs

url: /es/nodejs-java/aspose.threed/keyframesequence/
---
## KeyframeSequence class

La secuencia de fotogramas clave, describe la transformación de un valor muestreado a lo largo del tiempo.


## Métodos

### constructor{#constructor}

| Nombre | Descripción |
| --- | --- |
| constructor(name) | Inicializa una nueva instancia de la clase KeyframeSequence. |

 **Parameters:**

| Nombre | Tipo | Descripción |
| --- | --- | --- |
| name | Cadena | Nombre |

 **Result:**



---


### constructor_overload{#constructor_overload}

| Nombre | Descripción |
| --- | --- |
| constructor_overload() | Inicializa una nueva instancia de la clase KeyframeSequence. |

 **Result:**



---


### getBindPoint{#getBindPoint}

| Nombre | Descripción |
| --- | --- |
| getBindPoint() | Obtiene el punto de enlace de la propiedad que posee esta curva. |

 **Result:**



---


### getKeyFrames{#getKeyFrames}

| Nombre | Descripción |
| --- | --- |
| getKeyFrames() | Obtiene los fotogramas clave de esta curva. Las claves. |

 **Result:**



---


### getPostBehavior{#getPostBehavior}

| Nombre | Descripción |
| --- | --- |
| getPostBehavior() | Obtiene el comportamiento post que indica cuál debe ser el valor muestreado después del último fotograma clave. |

 **Result:**



---


### getPreBehavior{#getPreBehavior}

| Nombre | Descripción |
| --- | --- |
| getPreBehavior() | Obtiene el comportamiento pre que indica cuál debe ser el valor muestreado antes del primer fotograma. |

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


### add{#add}

| Nombre | Descripción |
| --- | --- |
| add(time, value) | Crear un nuevo fotograma clave con el valor especificado |

 **Parameters:**

| Nombre | Tipo | Descripción |
| --- | --- | --- |
| tiempo | Número | Posición de tiempo (medida en segundos) |
| valor | Número | El valor en esta posición de tiempo |

 **Result:**



---


### add{#add}

| Nombre | Descripción |
| --- | --- |
| add(time, value, interpolation) | Crear un nuevo fotograma clave con el valor especificado |

 **Parameters:**

| Nombre | Tipo | Descripción |
| --- | --- | --- |
| tiempo | Número | Posición de tiempo (medida en segundos) |
| valor | Número | El valor en esta posición de tiempo |
| interpolación | Interpolación | Interpolación |

 **Result:**



---


### reset{#reset}

| Nombre | Descripción |
| --- | --- |
| reset() | Elimina todos los fotogramas clave y restablece los comportamientos post/pre. |

 **Result:**



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


### iterator{#iterator}

| Nombre | Descripción |
| --- | --- |
| iterator() | Reservado para uso interno. |

 **Result:**
Property


---




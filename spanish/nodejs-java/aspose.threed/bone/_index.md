---
title: "Bone"
second_title: "Referencia de API de Aspose.3D para Node.js vía Java"
description: 
type: docs

url: /es/nodejs-java/aspose.threed/bone/
---
## Bone class

Un hueso define el subconjunto del punto de control de la geometría y el peso de mezcla definido para cada punto de control.  El objeto Bone no puede usarse directamente, se utiliza una instancia de SkinDeformer para deformar la geometría, y SkinDeformer viene con un conjunto de huesos, cada hueso vinculado a un nodo.  NOTA: Un punto de control de una geometría puede estar vinculado a más de un Bone.


## Métodos

### constructor{#constructor}

| Nombre | Descripción |
| --- | --- |
| constructor(name) | Inicializa una nueva instancia de la clase Bone. |

 **Parameters:**

| Nombre | Tipo | Descripción |
| --- | --- | --- |
| name | Cadena | Nombre. |

 **Result:**



---


### constructor_overload{#constructor_overload}

| Nombre | Descripción |
| --- | --- |
| constructor_overload() | Inicializa una nueva instancia de la clase Bone. |

 **Result:**



---


### getWeightCount{#getWeightCount}

| Nombre | Descripción |
| --- | --- |
| getWeightCount() | Obtiene el recuento de pesos, esto se amplía automáticamente mediante setWeight(int, double) |

 **Result:**



---


### getTransform{#getTransform}

| Nombre | Descripción |
| --- | --- |
| getTransform() | Obtiene o establece la matriz de transformación del nodo que contiene el bone. |

 **Result:**



---


### setTransform{#setTransform}

| Nombre | Descripción |
| --- | --- |
| setTransform(value) | Obtiene o establece la matriz de transformación del nodo que contiene el bone. |

 **Result:**



---


### getBoneTransform{#getBoneTransform}

| Nombre | Descripción |
| --- | --- |
| getBoneTransform() | Obtiene o establece la matriz de transformación del bone. |

 **Result:**



---


### setBoneTransform{#setBoneTransform}

| Nombre | Descripción |
| --- | --- |
| setBoneTransform(value) | Obtiene o establece la matriz de transformación del bone. |

 **Result:**



---


### getNode{#getNode}

| Nombre | Descripción |
| --- | --- |
| getNode() | Obtiene o establece el nodo. El nodo bone es el bone al que se adjunta la piel, el SkinDeformer usará el nodo bone para influir en el desplazamiento de los puntos de control. El nodo bone suele tener un Skeleton adjunto, pero no es obligatorio. El Skeleton adjunto suele ser usado por el software DCC para mostrar el esqueleto al usuario. |

 **Result:**



---


### setNode{#setNode}

| Nombre | Descripción |
| --- | --- |
| setNode(value) | Obtiene o establece el nodo. El nodo bone es el bone al que se adjunta la piel, el SkinDeformer usará el nodo bone para influir en el desplazamiento de los puntos de control. El nodo bone suele tener un Skeleton adjunto, pero no es obligatorio. El Skeleton adjunto suele ser usado por el software DCC para mostrar el esqueleto al usuario. |

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


### get{#get}

| Nombre | Descripción |
| --- | --- |
| get(index) |  |

 **Result:**



---


### set{#set}

| Nombre | Descripción |
| --- | --- |
| set(index, value) |  |

 **Result:**



---


### getWeight{#getWeight}

| Nombre | Descripción |
| --- | --- |
| getWeight(index) | Obtiene el peso del punto de control especificado por el índice |

 **Parameters:**

| Nombre | Tipo | Descripción |
| --- | --- | --- |
| index | Número | Índice del punto de control |

 **Result:**
Número


---


### setWeight{#setWeight}

| Nombre | Descripción |
| --- | --- |
| setWeight(index, weight) | Establece el peso para el punto de control especificado por el índice |

 **Parameters:**

| Nombre | Tipo | Descripción |
| --- | --- | --- |
| index | Número | Índice del punto de control |
| peso | Número | Nuevo peso |

 **Result:**
Número


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




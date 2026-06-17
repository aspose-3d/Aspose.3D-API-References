---
title: "MorphTargetChannel"
second_title: "Referencia de API de Aspose.3D para Node.js vía Java"
description: 
type: docs

url: /es/nodejs-java/aspose.threed/morphtargetchannel/
---
## MorphTargetChannel class

Un MorphTargetChannel es utilizado por MorphTargetDeformer para organizar las geometrías objetivo. Algunos formatos de archivo como FBX admiten múltiples canales en paralelo. El peso está entre 0 y 1.0, y el peso predeterminado para el objetivo es 0.0;


## Propiedades

| Nombre | Descripción |
| --- | --- |
| DEFAULT_WEIGHT | Peso predeterminado para el objetivo de morph. |

## Métodos

### constructor{#constructor}

| Nombre | Descripción |
| --- | --- |
| constructor(name) | Inicializa una nueva instancia de la clase MorphTargetChannel. |

 **Parameters:**

| Nombre | Tipo | Descripción |
| --- | --- | --- |
| name | Cadena | Nombre. |

 **Result:**



---


### constructor_overload{#constructor_overload}

| Nombre | Descripción |
| --- | --- |
| constructor_overload() | Inicializa una nueva instancia de la clase MorphTargetChannel. |

 **Result:**



---


### getWeights{#getWeights}

| Nombre | Descripción |
| --- | --- |
| getWeights() | Obtiene los valores completos de peso de las geometrías objetivo. Los pesos completos. |

 **Result:**



---


### getChannelWeight{#getChannelWeight}

| Nombre | Descripción |
| --- | --- |
| getChannelWeight() | Obtiene o establece el peso del deformador de este canal. El peso está entre 0.0 y 1.0 |

 **Result:**



---


### setChannelWeight{#setChannelWeight}

| Nombre | Descripción |
| --- | --- |
| setChannelWeight(value) | Obtiene o establece el peso del deformador de este canal. El peso está entre 0.0 y 1.0 |

 **Result:**



---


### getTargets{#getTargets}

| Nombre | Descripción |
| --- | --- |
| getTargets() | Obtiene todos los objetivos asociados con el canal. |

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
| get(target) |  |

 **Result:**



---


### set{#set}

| Nombre | Descripción |
| --- | --- |
| set(target, value) |  |

 **Result:**



---


### getWeight{#getWeight}

| Nombre | Descripción |
| --- | --- |
| getWeight(target) | Obtiene el peso del objetivo especificado; si el objetivo no pertenece a este canal, se devuelve el valor predeterminado 0. |

 **Parameters:**

| Nombre | Tipo | Descripción |
| --- | --- | --- |
| objetivo | Forma | null |

 **Result:**
Número


---


### setWeight{#setWeight}

| Nombre | Descripción |
| --- | --- |
| setWeight(target, weight) | Establece el peso para el objetivo especificado, el valor predeterminado es 1, el rango debe estar entre 0 y 1. |

 **Parameters:**

| Nombre | Tipo | Descripción |
| --- | --- | --- |
| objetivo | Forma | null |
| pesar | Número | null |

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




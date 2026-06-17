---
title: "Pose"
second_title: "Referencia de API de Aspose.3D para Node.js vía Java"
description: 
type: docs

url: /es/nodejs-java/aspose.threed/pose/
---
## Pose class

La pose se usa para almacenar la matriz de transformación cuando la geometría está con skinning. La pose es un conjunto de BonePose, cada BonePose guarda la información concreta de transformación del nodo óseo.


## Métodos

### constructor{#constructor}

| Nombre | Descripción |
| --- | --- |
| constructor(name) | Inicializa una nueva instancia de la clase Pose. |

 **Parameters:**

| Nombre | Tipo | Descripción |
| --- | --- | --- |
| name | Cadena | Nombre |

 **Result:**



---


### constructor_overload{#constructor_overload}

| Nombre | Descripción |
| --- | --- |
| constructor_overload() | Inicializa una nueva instancia de la clase Pose. |

 **Result:**



---


### getPoseType{#getPoseType}

| Nombre | Descripción |
| --- | --- |
| getPoseType() | Obtiene o establece el tipo de la pose. El valor de la propiedad es la constante entera PoseType. El tipo de la pose. |

 **Result:**



---


### setPoseType{#setPoseType}

| Nombre | Descripción |
| --- | --- |
| setPoseType(value) | Obtiene o establece el tipo de la pose. El valor de la propiedad es la constante entera PoseType. El tipo de la pose. |

 **Result:**



---


### getBonePoses{#getBonePoses}

| Nombre | Descripción |
| --- | --- |
| getBonePoses() | Obtiene todos los BonePose. Los nodos. |

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


### addBonePose{#addBonePose}

| Nombre | Descripción |
| --- | --- |
| addBonePose(node, matrix, localMatrix) | Guarda la matriz de transformación de la pose para el nodo óseo dado. |

 **Parameters:**

| Nombre | Tipo | Descripción |
| --- | --- | --- |
| nodo | Nodo | Nodo óseo. |
| matrix | Matrix4 | Matriz de transformación. |
| localMatrix | boolean | Si se establece en |

 **Result:**



---


### addBonePose{#addBonePose}

| Nombre | Descripción |
| --- | --- |
| addBonePose(node, matrix) | Guarda la matriz de transformación de pose para el nodo óseo dado. Se implica la matriz de transformación global. |

 **Parameters:**

| Nombre | Tipo | Descripción |
| --- | --- | --- |
| nodo | Nodo | Nodo óseo. |
| matrix | Matrix4 | Matriz de transformación. |

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




---
title: "SkinDeformer"
second_title: "Referencia de API de Aspose.3D para Node.js vía Java"
description: 
type: docs

url: /es/nodejs-java/aspose.threed/skindeformer/
---
## SkinDeformer class

Un deformador de piel contiene múltiples huesos para trabajar, cada hueso mezcla una parte de la geometría mediante los pesos de los puntos de control.


## Métodos

### constructor{#constructor}

| Nombre | Descripción |
| --- | --- |
| constructor(name) | Inicializa una nueva instancia de la clase SkinDeformer. |

 **Parameters:**

| Nombre | Tipo | Descripción |
| --- | --- | --- |
| name | Cadena | Nombre. |

 **Result:**



---


### constructor_overload{#constructor_overload}

| Nombre | Descripción |
| --- | --- |
| constructor_overload() | Inicializa una nueva instancia de la clase SkinDeformer. |

 **Result:**



---


### getBones{#getBones}

| Nombre | Descripción |
| --- | --- |
| getBones() | Obtiene todos los huesos que contiene el deformer de piel |

 **Result:**



---


### getOwner{#getOwner}

| Nombre | Descripción |
| --- | --- |
| getOwner() | Obtiene la geometría que posee este deformer |

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




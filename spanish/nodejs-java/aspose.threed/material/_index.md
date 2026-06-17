---
title: "Material"
second_title: "Referencia de API de Aspose.3D para Node.js vía Java"
description: 
type: docs

url: /es/nodejs-java/aspose.threed/material/
---
## Material class

Material define los parámetros necesarios para la apariencia visual de la geometría.  Aspose.3D proporciona modelos de sombreado para LambertMaterial, PhongMaterial y ShaderMaterial  @hideconstructor


## Propiedades

| Nombre | Descripción |
| --- | --- |
| MAP_SPECULAR | Usado en setTexture(java.lang.String, com.aspose.threed.TextureBase) para asignar un mapeo de textura especular. |
| MAP_DIFFUSE | Usado en setTexture(java.lang.String, com.aspose.threed.TextureBase) para asignar un mapeo de textura difusa. |
| MAP_EMISSIVE | Usado en setTexture(java.lang.String, com.aspose.threed.TextureBase) para asignar un mapeo de textura emisiva. |
| MAP_AMBIENT | Usado en setTexture(java.lang.String, com.aspose.threed.TextureBase) para asignar un mapeo de textura ambiental. |
| MAP_NORMAL | Usado en setTexture(java.lang.String, com.aspose.threed.TextureBase) para asignar un mapeo de textura normal. |

## Métodos

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


### getTexture{#getTexture}

| Nombre | Descripción |
| --- | --- |
| getTexture(slotName) | Obtiene la textura del slot especificado, puede ser el nombre de una propiedad del material o el nombre de un parámetro del shader |

 **Parameters:**

| Nombre | Tipo | Descripción |
| --- | --- | --- |
| slotName | Cadena | Nombre del slot. |

 **Result:**
TextureBase


---


### setTexture{#setTexture}

| Nombre | Descripción |
| --- | --- |
| setTexture(slotName, texture) | Establece la textura al slot especificado |

 **Parameters:**

| Nombre | Tipo | Descripción |
| --- | --- | --- |
| slotName | Cadena | Nombre del slot. |
| texture | TextureBase | Textura. |

 **Result:**
TextureBase


---


### toString{#toString}

| Nombre | Descripción |
| --- | --- |
| toString() | Formatea el objeto a cadena |

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


### iterator{#iterator}

| Nombre | Descripción |
| --- | --- |
| iterator() | Reservado para uso interno. |

 **Result:**
Property


---




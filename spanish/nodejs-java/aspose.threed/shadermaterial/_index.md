---
title: "ShaderMaterial"
second_title: "Referencia de API de Aspose.3D para Node.js vía Java"
description: 
type: docs

url: /es/nodejs-java/aspose.threed/shadermaterial/
---
## ShaderMaterial class

Un material de shader permite describir el material mediante un motor de renderizado externo o un lenguaje de shader.  ShaderMaterial usa ShaderTechnique para describir los detalles concretos de renderizado, y se utilizará el más adecuado según la plataforma de renderizado final.  Por ejemplo, su instancia de ShaderMaterial puede tener dos técnicas, una definida por HLSL y otra definida por GLSL.  En plataformas sin ventana, se debe usar GLSL en lugar de HLSL.


## Métodos

### constructor{#constructor}

| Nombre | Descripción |
| --- | --- |
| constructor() | Inicializa una nueva instancia de la clase ShaderMaterial. |

 **Result:**



---


### constructor_overload{#constructor_overload}

| Nombre | Descripción |
| --- | --- |
| constructor_overload(name) | Inicializa una nueva instancia de la clase ShaderMaterial. |

 **Parameters:**

| Nombre | Tipo | Descripción |
| --- | --- | --- |
| name | Cadena | Nombre |

 **Result:**



---


### getTechniques{#getTechniques}

| Nombre | Descripción |
| --- | --- |
| getTechniques() | Obtiene todas las técnicas disponibles definidas en este material. |

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




---
title: "PbrSpecularMaterial"
second_title: "Referencia de API de Aspose.3D para Node.js vía Java"
description: 
type: docs

url: /es/nodejs-java/aspose.threed/pbrspecularmaterial/
---
## PbrSpecularMaterial class

Material para renderizado físicamente basado en color difuso/specular/glossiness


## Propiedades

| Nombre | Descripción |
| --- | --- |
| MAP_SPECULAR_GLOSSINESS | El mapa de textura para el brillo especular |

## Métodos

### constructor{#constructor}

| Nombre | Descripción |
| --- | --- |
| constructor() | Constructor de PbrSpecularMaterial |

 **Result:**



---


### getTransparency{#getTransparency}

| Nombre | Descripción |
| --- | --- |
| getTransparency() | Obtiene o establece el factor de transparencia. El factor debe estar en el rango entre 0 (0%, totalmente opaco) y 1 (100%, totalmente transparente). Cualquier valor de factor no válido será limitado. El factor de transparencia. |

 **Result:**



---


### setTransparency{#setTransparency}

| Nombre | Descripción |
| --- | --- |
| setTransparency(value) | Obtiene o establece el factor de transparencia. El factor debe estar en el rango entre 0 (0%, totalmente opaco) y 1 (100%, totalmente transparente). Cualquier valor de factor no válido será limitado. El factor de transparencia. |

 **Result:**



---


### getNormalTexture{#getNormalTexture}

| Nombre | Descripción |
| --- | --- |
| getNormalTexture() | Obtiene o establece la textura del mapeo normal |

 **Result:**



---


### setNormalTexture{#setNormalTexture}

| Nombre | Descripción |
| --- | --- |
| setNormalTexture(value) | Obtiene o establece la textura del mapeo normal |

 **Result:**



---


### getSpecularGlossinessTexture{#getSpecularGlossinessTexture}

| Nombre | Descripción |
| --- | --- |
| getSpecularGlossinessTexture() | Obtiene o establece la textura para el color especular, el canal RGB almacena el color especular y el canal A almacena el brillo. |

 **Result:**



---


### setSpecularGlossinessTexture{#setSpecularGlossinessTexture}

| Nombre | Descripción |
| --- | --- |
| setSpecularGlossinessTexture(value) | Obtiene o establece la textura para el color especular, el canal RGB almacena el color especular y el canal A almacena el brillo. |

 **Result:**



---


### getGlossinessFactor{#getGlossinessFactor}

| Nombre | Descripción |
| --- | --- |
| getGlossinessFactor() | Obtiene o establece el brillo (suavidad) del material, 1 significa perfectamente liso y 0 significa perfectamente rugoso, el valor predeterminado es 1, el rango es [0, 1] |

 **Result:**



---


### setGlossinessFactor{#setGlossinessFactor}

| Nombre | Descripción |
| --- | --- |
| setGlossinessFactor(value) | Obtiene o establece el brillo (suavidad) del material, 1 significa perfectamente liso y 0 significa perfectamente rugoso, el valor predeterminado es 1, el rango es [0, 1] |

 **Result:**



---


### getSpecular{#getSpecular}

| Nombre | Descripción |
| --- | --- |
| getSpecular() | Obtiene o establece el color especular del material, el valor predeterminado es (1, 1, 1). |

 **Result:**



---


### setSpecular{#setSpecular}

| Nombre | Descripción |
| --- | --- |
| setSpecular(value) | Obtiene o establece el color especular del material, el valor predeterminado es (1, 1, 1). |

 **Result:**



---


### getDiffuseTexture{#getDiffuseTexture}

| Nombre | Descripción |
| --- | --- |
| getDiffuseTexture() | Obtiene o establece la textura para difuso |

 **Result:**



---


### setDiffuseTexture{#setDiffuseTexture}

| Nombre | Descripción |
| --- | --- |
| setDiffuseTexture(value) | Obtiene o establece la textura para difuso |

 **Result:**



---


### getDiffuse{#getDiffuse}

| Nombre | Descripción |
| --- | --- |
| getDiffuse() | Obtiene o establece el color difuso del material, el valor predeterminado es (1, 1, 1) |

 **Result:**



---


### setDiffuse{#setDiffuse}

| Nombre | Descripción |
| --- | --- |
| setDiffuse(value) | Obtiene o establece el color difuso del material, el valor predeterminado es (1, 1, 1) |

 **Result:**



---


### getEmissiveTexture{#getEmissiveTexture}

| Nombre | Descripción |
| --- | --- |
| getEmissiveTexture() | Obtiene o establece la textura para emisivo |

 **Result:**



---


### setEmissiveTexture{#setEmissiveTexture}

| Nombre | Descripción |
| --- | --- |
| setEmissiveTexture(value) | Obtiene o establece la textura para emisivo |

 **Result:**



---


### getEmissiveColor{#getEmissiveColor}

| Nombre | Descripción |
| --- | --- |
| getEmissiveColor() | Obtiene o establece el color emisivo, el valor predeterminado es (0, 0, 0) |

 **Result:**



---


### setEmissiveColor{#setEmissiveColor}

| Nombre | Descripción |
| --- | --- |
| setEmissiveColor(value) | Obtiene o establece el color emisivo, el valor predeterminado es (0, 0, 0) |

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




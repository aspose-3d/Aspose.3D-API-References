---
title: "LambertMaterial"
second_title: "Referencia de API de Aspose.3D para Node.js vía Java"
description: 
type: docs

url: /es/nodejs-java/aspose.threed/lambertmaterial/
---
## LambertMaterial class

Material para el modelo de sombreado Lambert


## Métodos

### constructor{#constructor}

| Nombre | Descripción |
| --- | --- |
| constructor() | Inicializa una nueva instancia de la clase LambertMaterial. |

 **Result:**



---


### constructor_overload{#constructor_overload}

| Nombre | Descripción |
| --- | --- |
| constructor_overload(name) | Inicializa una nueva instancia de la clase LambertMaterial. |

 **Parameters:**

| Nombre | Tipo | Descripción |
| --- | --- | --- |
| name | Cadena | Nombre |

 **Result:**



---


### getEmissiveColor{#getEmissiveColor}

| Nombre | Descripción |
| --- | --- |
| getEmissiveColor() | Obtiene o establece el color emisivo |

 **Result:**



---


### setEmissiveColor{#setEmissiveColor}

| Nombre | Descripción |
| --- | --- |
| setEmissiveColor(value) | Obtiene o establece el color emisivo |

 **Result:**



---


### getAmbientColor{#getAmbientColor}

| Nombre | Descripción |
| --- | --- |
| getAmbientColor() | Obtiene o establece el color ambiental. El ejemplo: var mat = new LambertMaterial(); mat.AmbientColor = new Vector3(1, 1, 1); ambient. |

 **Result:**



---


### setAmbientColor{#setAmbientColor}

| Nombre | Descripción |
| --- | --- |
| setAmbientColor(value) | Obtiene o establece el color ambiental. El ejemplo: var mat = new LambertMaterial(); mat.AmbientColor = new Vector3(1, 1, 1); ambient. |

 **Result:**



---


### getDiffuseColor{#getDiffuseColor}

| Nombre | Descripción |
| --- | --- |
| getDiffuseColor() | Obtiene o establece el color difuso. El ejemplo: var mat = new LambertMaterial(); mat.DiffuseColor = new Vector3(1, 0, 0); difuso. |

 **Result:**



---


### setDiffuseColor{#setDiffuseColor}

| Nombre | Descripción |
| --- | --- |
| setDiffuseColor(value) | Obtiene o establece el color difuso. El ejemplo: var mat = new LambertMaterial(); mat.DiffuseColor = new Vector3(1, 0, 0); difuso. |

 **Result:**



---


### getTransparentColor{#getTransparentColor}

| Nombre | Descripción |
| --- | --- |
| getTransparentColor() | Obtiene o establece el color transparente. El ejemplo: var mat = new LambertMaterial(); mat.TransparentColor = new Vector3(0.3, 0.5, 0.2); color del transparente. |

 **Result:**



---


### setTransparentColor{#setTransparentColor}

| Nombre | Descripción |
| --- | --- |
| setTransparentColor(value) | Obtiene o establece el color transparente. El ejemplo: var mat = new LambertMaterial(); mat.TransparentColor = new Vector3(0.3, 0.5, 0.2); color del transparente. |

 **Result:**



---


### getTransparency{#getTransparency}

| Nombre | Descripción |
| --- | --- |
| getTransparency() | Obtiene o establece el factor de transparencia. El factor debe estar en el rango entre 0 (0 %, totalmente opaco) y 1 (100 %, totalmente transparente). Cualquier valor de factor no válido será limitado. El ejemplo: var mat = new LambertMaterial(); mat.Transparency = 0.3; factor de transparencia. |

 **Result:**



---


### setTransparency{#setTransparency}

| Nombre | Descripción |
| --- | --- |
| setTransparency(value) | Obtiene o establece el factor de transparencia. El factor debe estar en el rango entre 0 (0 %, totalmente opaco) y 1 (100 %, totalmente transparente). Cualquier valor de factor no válido será limitado. El ejemplo: var mat = new LambertMaterial(); mat.Transparency = 0.3; factor de transparencia. |

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




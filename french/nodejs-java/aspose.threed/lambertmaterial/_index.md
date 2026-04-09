---
title: LambertMaterial
second_title: Référence d'API Aspose.3D pour Node.js via Java
description: 
type: docs

url: /fr/nodejs-java/aspose.threed/lambertmaterial/
---
## LambertMaterial class

Matériau pour le modèle d'éclairage Lambert


## Méthodes

### constructor{#constructor}

| Nom | Description |
| --- | --- |
| constructor() | Initialise une nouvelle instance de la classe LambertMaterial. |

 **Result:**



---


### constructor_overload{#constructor_overload}

| Nom | Description |
| --- | --- |
| constructor_overload(name) | Initialise une nouvelle instance de la classe LambertMaterial. |

 **Parameters:**

| Nom | Type | Description |
| --- | --- | --- |
| nom | String | Nom |

 **Result:**



---


### getEmissiveColor{#getEmissiveColor}

| Nom | Description |
| --- | --- |
| getEmissiveColor() | Obtient ou définit la couleur émissive |

 **Result:**



---


### setEmissiveColor{#setEmissiveColor}

| Nom | Description |
| --- | --- |
| setEmissiveColor(value) | Obtient ou définit la couleur émissive |

 **Result:**



---


### getAmbientColor{#getAmbientColor}

| Nom | Description |
| --- | --- |
| getAmbientColor() | Obtient ou définit la couleur ambiante L'exemple : var mat = new LambertMaterial(); mat.AmbientColor = new Vector3(1, 1, 1); ambiante. |

 **Result:**



---


### setAmbientColor{#setAmbientColor}

| Nom | Description |
| --- | --- |
| setAmbientColor(value) | Obtient ou définit la couleur ambiante L'exemple : var mat = new LambertMaterial(); mat.AmbientColor = new Vector3(1, 1, 1); ambiante. |

 **Result:**



---


### getDiffuseColor{#getDiffuseColor}

| Nom | Description |
| --- | --- |
| getDiffuseColor() | Obtient ou définit la couleur diffuse L'exemple : var mat = new LambertMaterial(); mat.DiffuseColor = new Vector3(1, 0, 0); diffuse. |

 **Result:**



---


### setDiffuseColor{#setDiffuseColor}

| Nom | Description |
| --- | --- |
| setDiffuseColor(value) | Obtient ou définit la couleur diffuse L'exemple : var mat = new LambertMaterial(); mat.DiffuseColor = new Vector3(1, 0, 0); diffuse. |

 **Result:**



---


### getTransparentColor{#getTransparentColor}

| Nom | Description |
| --- | --- |
| getTransparentColor() | Obtient ou définit la couleur transparente. L'exemple : var mat = new LambertMaterial(); mat.TransparentColor = new Vector3(0.3, 0.5, 0.2); couleur du transparent. |

 **Result:**



---


### setTransparentColor{#setTransparentColor}

| Nom | Description |
| --- | --- |
| setTransparentColor(value) | Obtient ou définit la couleur transparente. L'exemple : var mat = new LambertMaterial(); mat.TransparentColor = new Vector3(0.3, 0.5, 0.2); couleur du transparent. |

 **Result:**



---


### getTransparency{#getTransparency}

| Nom | Description |
| --- | --- |
| getTransparency() | Obtient ou définit le facteur de transparence. Le facteur doit être compris entre 0 (0 %, totalement opaque) et 1 (100 %, totalement transparent). Toute valeur de facteur invalide sera tronquée. Exemple : var mat = new LambertMaterial(); mat.Transparency = 0.3; facteur de transparence. |

 **Result:**



---


### setTransparency{#setTransparency}

| Nom | Description |
| --- | --- |
| setTransparency(value) | Obtient ou définit le facteur de transparence. Le facteur doit être compris entre 0 (0 %, totalement opaque) et 1 (100 %, totalement transparent). Toute valeur de facteur invalide sera tronquée. Exemple : var mat = new LambertMaterial(); mat.Transparency = 0.3; facteur de transparence. |

 **Result:**



---


### getName{#getName}

| Nom | Description |
| --- | --- |
| getName() | Obtient ou définit le nom. Le nom. |

 **Result:**



---


### setName{#setName}

| Nom | Description |
| --- | --- |
| setName(value) | Obtient ou définit le nom. Le nom. |

 **Result:**



---


### getProperties{#getProperties}

| Nom | Description |
| --- | --- |
| getProperties() | Obtient la collection de toutes les propriétés. |

 **Result:**



---


### getTexture{#getTexture}

| Nom | Description |
| --- | --- |
| getTexture(slotName) | Obtient la texture du slot spécifié, cela peut être le nom de la propriété du matériau ou le nom du paramètre du shader |

 **Parameters:**

| Nom | Type | Description |
| --- | --- | --- |
| slotName | String | Nom du slot. |

 **Result:**
TextureBase


---


### setTexture{#setTexture}

| Nom | Description |
| --- | --- |
| setTexture(slotName, texture) | Définit la texture au slot spécifié |

 **Parameters:**

| Nom | Type | Description |
| --- | --- | --- |
| slotName | String | Nom du slot. |
| texture | TextureBase | Texture. |

 **Result:**
TextureBase


---


### toString{#toString}

| Nom | Description |
| --- | --- |
| toString() | Formate l'objet en chaîne |

 **Result:**
String


---


### removeProperty{#removeProperty}

| Nom | Description |
| --- | --- |
| removeProperty(property) | Supprime une propriété dynamique. |

 **Parameters:**

| Nom | Type | Description |
| --- | --- | --- |
| propriété | Property | Quelle propriété supprimer |

 **Result:**
boolean


---


### removeProperty{#removeProperty}

| Nom | Description |
| --- | --- |
| removeProperty(property) | Supprime la propriété spécifiée identifiée par son nom |

 **Parameters:**

| Nom | Type | Description |
| --- | --- | --- |
| propert | String | null |

 **Result:**
boolean


---


### getProperty{#getProperty}

| Nom | Description |
| --- | --- |
| getProperty(property) | Obtenir la valeur de la propriété spécifiée |

 **Parameters:**

| Nom | Type | Description |
| --- | --- | --- |
| propriété | String | Nom de la propriété |

 **Result:**
Object


---


### setProperty{#setProperty}

| Nom | Description |
| --- | --- |
| setProperty(property, value) | Définit la valeur de la propriété spécifiée |

 **Parameters:**

| Nom | Type | Description |
| --- | --- | --- |
| propriété | String | Nom de la propriété |
| valeur | Object | La valeur de la propriété |

 **Result:**
Object


---


### findProperty{#findProperty}

| Nom | Description |
| --- | --- |
| findProperty(propertyName) | Trouve la propriété. Elle peut être une propriété dynamique (Créée par CreateDynamicProperty/SetProperty) ou une propriété native (Identifiée par son nom) |

 **Parameters:**

| Nom | Type | Description |
| --- | --- | --- |
| propertyName | String | Nom de la propriété. |

 **Result:**
Property


---


### iterator{#iterator}

| Nom | Description |
| --- | --- |
| iterator() | Réservé à un usage interne. |

 **Result:**
Property


---




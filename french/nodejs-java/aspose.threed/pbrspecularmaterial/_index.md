---
title: PbrSpecularMaterial
second_title: Référence d'API Aspose.3D pour Node.js via Java
description: 
type: docs

url: /fr/nodejs-java/aspose.threed/pbrspecularmaterial/
---
## PbrSpecularMaterial class

Matériau pour le rendu physiquement basé sur la couleur diffuse/speculaire/brillance


## Properties

| Nom | Description |
| --- | --- |
| MAP_SPECULAR_GLOSSINESS | La carte de texture pour la brillance spéculaire |

## Méthodes

### constructor{#constructor}

| Nom | Description |
| --- | --- |
| constructor() | Constructeur de PbrSpecularMaterial |

 **Result:**



---


### getTransparency{#getTransparency}

| Nom | Description |
| --- | --- |
| getTransparency() | Obtient ou définit le facteur de transparence. Le facteur doit être compris entre 0 (0 %, totalement opaque) et 1 (100 %, totalement transparent). Toute valeur de facteur invalide sera limitée. Le facteur de transparence. |

 **Result:**



---


### setTransparency{#setTransparency}

| Nom | Description |
| --- | --- |
| setTransparency(value) | Obtient ou définit le facteur de transparence. Le facteur doit être compris entre 0 (0 %, totalement opaque) et 1 (100 %, totalement transparent). Toute valeur de facteur invalide sera limitée. Le facteur de transparence. |

 **Result:**



---


### getNormalTexture{#getNormalTexture}

| Nom | Description |
| --- | --- |
| getNormalTexture() | Obtient ou définit la texture du mappage normal |

 **Result:**



---


### setNormalTexture{#setNormalTexture}

| Nom | Description |
| --- | --- |
| setNormalTexture(value) | Obtient ou définit la texture du mappage normal |

 **Result:**



---


### getSpecularGlossinessTexture{#getSpecularGlossinessTexture}

| Nom | Description |
| --- | --- |
| getSpecularGlossinessTexture() | Obtient ou définit la texture pour la couleur spéculaire, le canal RGB stocke la couleur spéculaire et le canal A stocke la brillance. |

 **Result:**



---


### setSpecularGlossinessTexture{#setSpecularGlossinessTexture}

| Nom | Description |
| --- | --- |
| setSpecularGlossinessTexture(value) | Obtient ou définit la texture pour la couleur spéculaire, le canal RGB stocke la couleur spéculaire et le canal A stocke la brillance. |

 **Result:**



---


### getGlossinessFactor{#getGlossinessFactor}

| Nom | Description |
| --- | --- |
| getGlossinessFactor() | Obtient ou définit la brillance (lissage) du matériau, 1 signifie parfaitement lisse et 0 signifie parfaitement rugueux, la valeur par défaut est 1, la plage est [0, 1]. |

 **Result:**



---


### setGlossinessFactor{#setGlossinessFactor}

| Nom | Description |
| --- | --- |
| setGlossinessFactor(value) | Obtient ou définit la brillance (lissage) du matériau, 1 signifie parfaitement lisse et 0 signifie parfaitement rugueux, la valeur par défaut est 1, la plage est [0, 1]. |

 **Result:**



---


### getSpecular{#getSpecular}

| Nom | Description |
| --- | --- |
| getSpecular() | Obtient ou définit la couleur spéculaire du matériau, la valeur par défaut est (1, 1, 1). |

 **Result:**



---


### setSpecular{#setSpecular}

| Nom | Description |
| --- | --- |
| setSpecular(value) | Obtient ou définit la couleur spéculaire du matériau, la valeur par défaut est (1, 1, 1). |

 **Result:**



---


### getDiffuseTexture{#getDiffuseTexture}

| Nom | Description |
| --- | --- |
| getDiffuseTexture() | Obtient ou définit la texture diffuse |

 **Result:**



---


### setDiffuseTexture{#setDiffuseTexture}

| Nom | Description |
| --- | --- |
| setDiffuseTexture(value) | Obtient ou définit la texture diffuse |

 **Result:**



---


### getDiffuse{#getDiffuse}

| Nom | Description |
| --- | --- |
| getDiffuse() | Obtient ou définit la couleur diffuse du matériau, la valeur par défaut est (1, 1, 1). |

 **Result:**



---


### setDiffuse{#setDiffuse}

| Nom | Description |
| --- | --- |
| setDiffuse(value) | Obtient ou définit la couleur diffuse du matériau, la valeur par défaut est (1, 1, 1). |

 **Result:**



---


### getEmissiveTexture{#getEmissiveTexture}

| Nom | Description |
| --- | --- |
| getEmissiveTexture() | Obtient ou définit la texture émissive |

 **Result:**



---


### setEmissiveTexture{#setEmissiveTexture}

| Nom | Description |
| --- | --- |
| setEmissiveTexture(value) | Obtient ou définit la texture émissive |

 **Result:**



---


### getEmissiveColor{#getEmissiveColor}

| Nom | Description |
| --- | --- |
| getEmissiveColor() | Obtient ou définit la couleur émissive, la valeur par défaut est (0, 0, 0). |

 **Result:**



---


### setEmissiveColor{#setEmissiveColor}

| Nom | Description |
| --- | --- |
| setEmissiveColor(value) | Obtient ou définit la couleur émissive, la valeur par défaut est (0, 0, 0). |

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




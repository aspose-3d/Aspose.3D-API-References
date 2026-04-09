---
title: Material
second_title: Référence d'API Aspose.3D pour Node.js via Java
description: 
type: docs

url: /fr/nodejs-java/aspose.threed/material/
---
## Material class

Material définit les paramètres nécessaires à l'apparence visuelle de la géométrie. Aspose.3D fournit des modèles d'ombrage pour LambertMaterial, PhongMaterial et ShaderMaterial  @hideconstructor


## Properties

| Nom | Description |
| --- | --- |
| MAP_SPECULAR | Utilisé dans setTexture(java.lang.String, com.aspose.threed.TextureBase) pour assigner un mappage de texture spéculaire. |
| MAP_DIFFUSE | Utilisé dans setTexture(java.lang.String, com.aspose.threed.TextureBase) pour assigner un mappage de texture diffuse. |
| MAP_EMISSIVE | Utilisé dans setTexture(java.lang.String, com.aspose.threed.TextureBase) pour assigner un mappage de texture émissive. |
| MAP_AMBIENT | Utilisé dans setTexture(java.lang.String, com.aspose.threed.TextureBase) pour assigner un mappage de texture ambiante. |
| MAP_NORMAL | Utilisé dans setTexture(java.lang.String, com.aspose.threed.TextureBase) pour assigner un mappage de texture normale. |

## Méthodes

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




---
title: "ShaderMaterial"
second_title: "Référence d'API Aspose.3D pour Node.js via Java"
description: 
type: docs

url: /fr/nodejs-java/aspose.threed/shadermaterial/
---
## ShaderMaterial class

Un matériau de shader permet de décrire le matériau via un moteur de rendu externe ou un langage de shader.  ShaderMaterial utilise ShaderTechnique pour décrire les détails concrets du rendu,  et le plus approprié sera utilisé en fonction de la plateforme de rendu finale.  Par exemple, votre instance de ShaderMaterial peut avoir deux techniques, l'une définie par HLSL et l'autre par GLSL.  Sur les plateformes non Windows, le GLSL doit être utilisé à la place du HLSL


## Méthodes

### constructor{#constructor}

| Nom | Description |
| --- | --- |
| constructor() | Initialise une nouvelle instance de la classe ShaderMaterial. |

 **Result:**



---


### constructor_overload{#constructor_overload}

| Nom | Description |
| --- | --- |
| constructor_overload(name) | Initialise une nouvelle instance de la classe ShaderMaterial. |

 **Parameters:**

| Nom | Type | Description |
| --- | --- | --- |
| name | String | Nom |

 **Result:**



---


### getTechniques{#getTechniques}

| Nom | Description |
| --- | --- |
| getTechniques() | Récupère toutes les techniques disponibles définies dans ce matériau. |

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
| getTexture(slotName) | Obtient la texture depuis l'emplacement spécifié, cela peut être le nom d'une propriété du matériau ou le nom d'un paramètre du shader |

 **Parameters:**

| Nom | Type | Description |
| --- | --- | --- |
| slotName | String | Nom de l'emplacement. |

 **Result:**
TextureBase


---


### setTexture{#setTexture}

| Nom | Description |
| --- | --- |
| setTexture(slotName, texture) | Définit la texture sur l'emplacement spécifié |

 **Parameters:**

| Nom | Type | Description |
| --- | --- | --- |
| slotName | String | Nom de l'emplacement. |
| texture | TextureBase | Texture. |

 **Result:**
TextureBase


---


### toString{#toString}

| Nom | Description |
| --- | --- |
| toString() | Formate l'objet en chaîne. |

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
| property | Property | Quelle propriété supprimer |

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
| property | String | Nom de la propriété |

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
| property | String | Nom de la propriété |
| value | Object | La valeur de la propriété |

 **Result:**
Object


---


### findProperty{#findProperty}

| Nom | Description |
| --- | --- |
| findProperty(propertyName) | Recherche la propriété. Elle peut être une propriété dynamique (Créée par CreateDynamicProperty/SetProperty) ou une propriété native (Identifiée par son nom) |

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




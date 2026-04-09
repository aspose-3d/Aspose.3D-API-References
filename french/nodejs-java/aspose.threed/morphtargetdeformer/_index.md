---
title: MorphTargetDeformer
second_title: Référence d'API Aspose.3D pour Node.js via Java
description: 
type: docs

url: /fr/nodejs-java/aspose.threed/morphtargetdeformer/
---
## MorphTargetDeformer class

MorphTargetDeformer fournit une animation par sommet. MorphTargetDeformer organise toutes les cibles via MorphTargetChannel, chaque canal pouvant organiser plusieurs cibles. Une utilisation courante du déformeur de cibles morphologiques est d'appliquer des expressions faciales à un personnage. Plus de détails sont disponibles sur https://en.wikipedia.org/wiki/Morph_target_animation


## Méthodes

### constructor{#constructor}

| Nom | Description |
| --- | --- |
| constructor(name) | Initialise une nouvelle instance de la classe MorphTargetDeformer. |

 **Parameters:**

| Nom | Type | Description |
| --- | --- | --- |
| nom | String | Name. |

 **Result:**



---


### constructor_overload{#constructor_overload}

| Nom | Description |
| --- | --- |
| constructor_overload() | Initialise une nouvelle instance de la classe MorphTargetDeformer. |

 **Result:**



---


### getChannels{#getChannels}

| Nom | Description |
| --- | --- |
| getChannels() | Obtient tous les canaux contenus dans ce déformeur |

 **Result:**



---


### getOwner{#getOwner}

| Nom | Description |
| --- | --- |
| getOwner() | Obtient la géométrie qui possède ce deformer |

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


### get{#get}

| Nom | Description |
| --- | --- |
| get(target) |  |

 **Result:**



---


### set{#set}

| Nom | Description |
| --- | --- |
| set(target, value) |  |

 **Result:**



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




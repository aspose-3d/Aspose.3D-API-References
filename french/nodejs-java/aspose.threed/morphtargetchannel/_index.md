---
title: MorphTargetChannel
second_title: Référence d'API Aspose.3D pour Node.js via Java
description: 
type: docs

url: /fr/nodejs-java/aspose.threed/morphtargetchannel/
---
## MorphTargetChannel class

Un MorphTargetChannel est utilisé par MorphTargetDeformer pour organiser les géométries cibles. Certains formats de fichier comme FBX prennent en charge plusieurs canaux en parallèle. Le poids est compris entre 0 et 1,0, et le poids par défaut pour la cible est 0,0 ;


## Properties

| Nom | Description |
| --- | --- |
| DEFAULT_WEIGHT | Poids par défaut pour la cible de morph. |

## Méthodes

### constructor{#constructor}

| Nom | Description |
| --- | --- |
| constructor(name) | Initialise une nouvelle instance de la classe MorphTargetChannel. |

 **Parameters:**

| Nom | Type | Description |
| --- | --- | --- |
| nom | String | Name. |

 **Result:**



---


### constructor_overload{#constructor_overload}

| Nom | Description |
| --- | --- |
| constructor_overload() | Initialise une nouvelle instance de la classe MorphTargetChannel. |

 **Result:**



---


### getWeights{#getWeights}

| Nom | Description |
| --- | --- |
| getWeights() | Obtient les valeurs complètes des poids des géométries cibles. Les poids complets. |

 **Result:**



---


### getChannelWeight{#getChannelWeight}

| Nom | Description |
| --- | --- |
| getChannelWeight() | Obtient ou définit le poids du déformateur de ce canal. Le poids est compris entre 0,0 et 1,0. |

 **Result:**



---


### setChannelWeight{#setChannelWeight}

| Nom | Description |
| --- | --- |
| setChannelWeight(value) | Obtient ou définit le poids du déformateur de ce canal. Le poids est compris entre 0,0 et 1,0. |

 **Result:**



---


### getTargets{#getTargets}

| Nom | Description |
| --- | --- |
| getTargets() | Obtient toutes les cibles associées au canal. |

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


### getWeight{#getWeight}

| Nom | Description |
| --- | --- |
| getWeight(target) | Obtient le poids pour la cible spécifiée, si la cible n'appartient pas à ce canal, la valeur par défaut 0 est renvoyée. |

 **Parameters:**

| Nom | Type | Description |
| --- | --- | --- |
| cible | Shape | null |

 **Result:**
Number


---


### setWeight{#setWeight}

| Nom | Description |
| --- | --- |
| setWeight(target, weight) | Définit le poids pour la cible spécifiée, la valeur par défaut est 1, la plage doit être entre 0~1 |

 **Parameters:**

| Nom | Type | Description |
| --- | --- | --- |
| cible | Shape | null |
| peser | Number | null |

 **Result:**
Number


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




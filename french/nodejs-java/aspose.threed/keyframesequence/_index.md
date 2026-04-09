---
title: KeyframeSequence
second_title: Référence d'API Aspose.3D pour Node.js via Java
description: 
type: docs

url: /fr/nodejs-java/aspose.threed/keyframesequence/
---
## KeyframeSequence class

La séquence d'images clés décrit la transformation d'une valeur échantillonnée au fil du temps.


## Méthodes

### constructor{#constructor}

| Nom | Description |
| --- | --- |
| constructor(name) | Initialise une nouvelle instance de la classe KeyframeSequence. |

 **Parameters:**

| Nom | Type | Description |
| --- | --- | --- |
| nom | String | Nom |

 **Result:**



---


### constructor_overload{#constructor_overload}

| Nom | Description |
| --- | --- |
| constructor_overload() | Initialise une nouvelle instance de la classe KeyframeSequence. |

 **Result:**



---


### getBindPoint{#getBindPoint}

| Nom | Description |
| --- | --- |
| getBindPoint() | Obtient le point de liaison de la propriété qui possède cette courbe |

 **Result:**



---


### getKeyFrames{#getKeyFrames}

| Nom | Description |
| --- | --- |
| getKeyFrames() | Obtient les images clés de cette courbe. Les clés. |

 **Result:**



---


### getPostBehavior{#getPostBehavior}

| Nom | Description |
| --- | --- |
| getPostBehavior() | Obtient le comportement postérieur indiquant quelle doit être la valeur échantillonnée après la dernière image clé. |

 **Result:**



---


### getPreBehavior{#getPreBehavior}

| Nom | Description |
| --- | --- |
| getPreBehavior() | Obtient le comportement antérieur indiquant quelle doit être la valeur échantillonnée avant la première image clé. |

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


### add{#add}

| Nom | Description |
| --- | --- |
| add(time, value) | Crée une nouvelle image clé avec la valeur spécifiée |

 **Parameters:**

| Nom | Type | Description |
| --- | --- | --- |
| temps | Number | Position temporelle (mesurée en secondes) |
| valeur | Number | La valeur à cette position temporelle |

 **Result:**



---


### add{#add}

| Nom | Description |
| --- | --- |
| add(time, value, interpolation) | Crée une nouvelle image clé avec la valeur spécifiée |

 **Parameters:**

| Nom | Type | Description |
| --- | --- | --- |
| temps | Number | Position temporelle (mesurée en secondes) |
| valeur | Number | La valeur à cette position temporelle |
| interpolation | Interpolation | Interpolation |

 **Result:**



---


### reset{#reset}

| Nom | Description |
| --- | --- |
| reset() | Supprime toutes les images clés et réinitialise les comportements post/ pré. |

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


### iterator{#iterator}

| Nom | Description |
| --- | --- |
| iterator() | Réservé à un usage interne. |

 **Result:**
Property


---




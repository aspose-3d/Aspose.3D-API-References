---
title: AnimationClip
second_title: Référence d'API Aspose.3D pour Node.js via Java
description: 
type: docs

url: /fr/nodejs-java/aspose.threed/animationclip/
---
## AnimationClip class

Le clip d'animation est une collection d'animations.  La scène peut contenir un ou plusieurs clips d'animation.


## Méthodes

### constructor{#constructor}

| Nom | Description |
| --- | --- |
| constructor() | Initialise une nouvelle instance de la classe AnimationClip. |

 **Result:**



---


### constructor_overload{#constructor_overload}

| Nom | Description |
| --- | --- |
| constructor_overload(name) | Initialise une nouvelle instance de la classe AnimationClip. |

 **Parameters:**

| Nom | Type | Description |
| --- | --- | --- |
| nom | String | Nom |

 **Result:**



---


### getAnimations{#getAnimations}

| Nom | Description |
| --- | --- |
| getAnimations() | Obtient les animations contenues dans le clip. Les calques. |

 **Result:**



---


### getDescription{#getDescription}

| Nom | Description |
| --- | --- |
| getDescription() | Obtient ou définit la description de ce clip d'animation |

 **Result:**



---


### setDescription{#setDescription}

| Nom | Description |
| --- | --- |
| setDescription(value) | Obtient ou définit la description de ce clip d'animation |

 **Result:**



---


### getStart{#getStart}

| Nom | Description |
| --- | --- |
| getStart() | Obtient ou définit le temps en secondes du début du clip. |

 **Result:**



---


### setStart{#setStart}

| Nom | Description |
| --- | --- |
| setStart(value) | Obtient ou définit le temps en secondes du début du clip. |

 **Result:**



---


### getStop{#getStop}

| Nom | Description |
| --- | --- |
| getStop() | Obtient ou définit le temps en secondes de la fin du clip. |

 **Result:**



---


### setStop{#setStop}

| Nom | Description |
| --- | --- |
| setStop(value) | Obtient ou définit le temps en secondes de la fin du clip. |

 **Result:**



---


### getScene{#getScene}

| Nom | Description |
| --- | --- |
| getScene() | Obtient la scène à laquelle cet objet appartient |

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


### createAnimationNode{#createAnimationNode}

| Nom | Description |
| --- | --- |
| createAnimationNode(nodeName) | Une fonction raccourcie pour créer et enregistrer le nœud d'animation sur le clip actuel. |

 **Parameters:**

| Nom | Type | Description |
| --- | --- | --- |
| nodeName | String | Nom du nouveau nœud d'animation |

 **Result:**
AnimationNode


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




---
title: AnimationNode
second_title: Référence d'API Aspose.3D pour Node.js via Java
description: 
type: docs

url: /fr/nodejs-java/aspose.threed/animationnode/
---
## AnimationNode class

Aspose.3D prend en charge la hiérarchie d'animation, chaque animation pouvant être composée de plusieurs animations et de la définition des images clés d'animation.  AnimationNode définit la transformation d'une valeur de propriété au fil du temps, par exemple, le nœud d'animation peut être utilisé pour contrôler la transformation d'un nœud ou d'autres propriétés numériques d'un objet A3DObject.


## Méthodes

### constructor{#constructor}

| Nom | Description |
| --- | --- |
| constructor(name) | Initialise une nouvelle instance de la classe AnimationNode. |

 **Parameters:**

| Nom | Type | Description |
| --- | --- | --- |
| nom | String | Nom |

 **Result:**



---


### constructor_overload{#constructor_overload}

| Nom | Description |
| --- | --- |
| constructor_overload() | Initialise une nouvelle instance de la classe AnimationNode. |

 **Result:**



---


### getBindPoints{#getBindPoints}

| Nom | Description |
| --- | --- |
| getBindPoints() | Obtient les points de liaison de propriété actuels |

 **Result:**



---


### getSubAnimations{#getSubAnimations}

| Nom | Description |
| --- | --- |
| getSubAnimations() | Obtient les nœuds de sous-animation sous les animations actuelles |

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


### findBindPoint{#findBindPoint}

| Nom | Description |
| --- | --- |
| findBindPoint(name) | Trouve le point de liaison par son nom. |

 **Parameters:**

| Nom | Type | Description |
| --- | --- | --- |
| nom | String | Nom du point de liaison à rechercher. |

 **Result:**
BindPoint


---


### getBindPoint{#getBindPoint}

| Nom | Description |
| --- | --- |
| getBindPoint(target, propName, create) | Obtient le point de liaison d'animation sur la propriété donnée. |

 **Parameters:**

| Nom | Type | Description |
| --- | --- | --- |
| target | A3DObject | Sur quel objet créer le point de liaison. |
| propName | String | Le nom de la propriété. |
| créer | boolean | Si défini sur |

 **Result:**
BindPoint


---


### getKeyframeSequence{#getKeyframeSequence}

| Nom | Description |
| --- | --- |
| getKeyframeSequence(target, propName, channelName, create) | Obtient la séquence d'images clés sur la propriété et le canal donnés. |

 **Parameters:**

| Nom | Type | Description |
| --- | --- | --- |
| target | A3DObject | Sur quelle instance créer la séquence d'images clés. |
| propName | String | Le nom de la propriété. |
| channelName | String | Le nom du canal. |
| créer | boolean | Si défini sur |

 **Result:**
KeyframeSequence


---


### getKeyframeSequence{#getKeyframeSequence}

| Nom | Description |
| --- | --- |
| getKeyframeSequence(target, propName, create) | Obtient la séquence d'images clés sur la propriété donnée. |

 **Parameters:**

| Nom | Type | Description |
| --- | --- | --- |
| target | A3DObject | Sur quelle instance créer la séquence d'images clés. |
| propName | String | Le nom de la propriété. |
| créer | boolean | Si défini sur |

 **Result:**
KeyframeSequence


---


### createBindPoint{#createBindPoint}

| Nom | Description |
| --- | --- |
| createBindPoint(obj, propName) | Crée un BindPoint basé sur le type de données de la propriété. |

 **Parameters:**

| Nom | Type | Description |
| --- | --- | --- |
| obj | A3DObject | Objet. |
| propName | String | Nom de la propriété. |

 **Result:**
BindPoint


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




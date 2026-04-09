---
title: Property
second_title: Référence d'API Aspose.3D pour Node.js via Java
description: 
type: docs

url: /fr/nodejs-java/aspose.threed/property/
---
## Property class

Classe pour contenir des propriétés définies par l'utilisateur.  @hideconstructor


## Méthodes

### getValue{#getValue}

| Nom | Description |
| --- | --- |
| getValue() | Obtient ou définit la valeur. La valeur. |

 **Result:**



---


### setValue{#setValue}

| Nom | Description |
| --- | --- |
| setValue(value) | Obtient ou définit la valeur. La valeur. |

 **Result:**



---


### setName{#setName}

| Nom | Description |
| --- | --- |
| setName(value) |  |

 **Result:**



---


### getValueType{#getValueType}

| Nom | Description |
| --- | --- |
| getValueType() | Obtient le type de la valeur de la propriété. Le type de la valeur. |

 **Result:**



---


### getProperties{#getProperties}

| Nom | Description |
| --- | --- |
| getProperties() | Obtient la collection de toutes les propriétés. |

 **Result:**



---


### getBindPoint{#getBindPoint}

| Nom | Description |
| --- | --- |
| getBindPoint(anim, create) | Obtient le point de liaison de la propriété sur l'instance d'animation spécifiée. |

 **Parameters:**

| Nom | Type | Description |
| --- | --- | --- |
| anim | AnimationNode | Sur quelle animation créer le point de liaison. |
| créer | boolean | Crée le point de liaison de la propriété s'il n'est pas trouvé. |

 **Result:**
BindPoint


---


### getKeyframeSequence{#getKeyframeSequence}

| Nom | Description |
| --- | --- |
| getKeyframeSequence(anim, create) | Obtient la séquence d'images clés sur l'instance d'animation spécifiée. |

 **Parameters:**

| Nom | Type | Description |
| --- | --- | --- |
| anim | AnimationNode | Sur quelle animation créer la séquence d'images clés. |
| créer | boolean | Crée la séquence d'images clés si elle n'est pas trouvée. |

 **Result:**
KeyframeSequence


---


### toString{#toString}

| Nom | Description |
| --- | --- |
| toString() | Renvoie une chaîne qui représente la propriété actuelle. |

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




---
title: "BindPoint"
second_title: "Référence d'API Aspose.3D pour Node.js via Java"
description: 
type: docs

url: /fr/nodejs-java/aspose.threed/bindpoint/
---
## BindPoint class

Un BindPoint est généralement créé sur la propriété d'un objet, certains types de propriétés contiennent plusieurs champs de composant (comme un champ Vector3),  BindPoint générera un canal pour chaque champ de composant et connectera le champ à une ou plusieurs instances de séquence d'images clés via les canaux.


## Méthodes

### constructor{#constructor}

| Nom | Description |
| --- | --- |
| constructor(scene, prop) | Initialise une nouvelle instance de la classe BindPoint. |

 **Parameters:**

| Nom | Type | Description |
| --- | --- | --- |
| scène | Scene | La scène qui contient l'animation. |
| prop | Property | Propriété. |

 **Result:**



---


### getProperty{#getProperty}

| Nom | Description |
| --- | --- |
| getProperty() | Obtient la propriété associée à CurveMapping |

 **Result:**



---


### setProperty{#setProperty}

| Nom | Description |
| --- | --- |
| setProperty(value) | Obtient la propriété associée à CurveMapping |

 **Result:**



---


### getChannelsCount{#getChannelsCount}

| Nom | Description |
| --- | --- |
| getChannelsCount() | Obtient le nombre total de canaux de propriété définis dans ce mappage de courbe d'animation. |

 **Result:**
Nombre


---


### getName{#getName}

| Nom | Description |
| --- | --- |
| getName() | Obtient ou définit le nom. Le nom. |

 **Result:**
Nombre


---


### setName{#setName}

| Nom | Description |
| --- | --- |
| setName(value) | Obtient ou définit le nom. Le nom. |

 **Result:**
Nombre


---


### getProperties{#getProperties}

| Nom | Description |
| --- | --- |
| getProperties() | Obtient la collection de toutes les propriétés. |

 **Result:**
Nombre


---


### get{#get}

| Nom | Description |
| --- | --- |
| get(channelName) |  |

 **Result:**
Nombre


---


### getKeyframeSequence{#getKeyframeSequence}

| Nom | Description |
| --- | --- |
| getKeyframeSequence(channelName) | Récupère la première séquence de keyframes dans le canal spécifié |

 **Parameters:**

| Nom | Type | Description |
| --- | --- | --- |
| channelName | String | Le nom du canal à rechercher |

 **Result:**
KeyframeSequence


---


### getKeyframeSequences{#getKeyframeSequences}

| Nom | Description |
| --- | --- |
| getKeyframeSequences(channelName) | Récupère toutes les séquences de keyframes dans le canal spécifié |

 **Parameters:**

| Nom | Type | Description |
| --- | --- | --- |
| channelName | String | Le nom du canal à rechercher |

 **Result:**
0, Culture=neutral, PublicKeyToken=f071c641d0b4582b]]


---


### createKeyframeSequence{#createKeyframeSequence}

| Nom | Description |
| --- | --- |
| createKeyframeSequence(name) | Crée une nouvelle courbe et la connecte au premier canal du mappage de courbes |

 **Parameters:**

| Nom | Type | Description |
| --- | --- | --- |
| name | String | Le nom de la nouvelle séquence. |

 **Result:**
KeyframeSequence


---


### bindKeyframeSequence{#bindKeyframeSequence}

| Nom | Description |
| --- | --- |
| bindKeyframeSequence(channelName, sequence) | Lie la séquence de keyframes au canal spécifié |

 **Parameters:**

| Nom | Type | Description |
| --- | --- | --- |
| channelName | String | Quel canal la séquence de keyframes sera liée à |
| sequence | KeyframeSequence | La séquence de keyframes à lier |

 **Result:**
KeyframeSequence


---


### getChannel{#getChannel}

| Nom | Description |
| --- | --- |
| getChannel(channelName) | Récupère le canal par le nom fourni |

 **Parameters:**

| Nom | Type | Description |
| --- | --- | --- |
| channelName | String | Le nom du canal à rechercher |

 **Result:**
AnimationChannel


---


### addChannel{#addChannel}

| Nom | Description |
| --- | --- |
| addChannel(name, value) | Ajoute la propriété de canal spécifiée. |

 **Parameters:**

| Nom | Type | Description |
| --- | --- | --- |
| name | String | Nom. |
| value | Object | Valeur. |

 **Result:**
boolean


---


### addChannel{#addChannel}

| Nom | Description |
| --- | --- |
| addChannel(name, type, value) | Ajoute la propriété de canal spécifiée. |

 **Parameters:**

| Nom | Type | Description |
| --- | --- | --- |
| name | String | Nom. |
| type | Classe | Type. |
| value | Object | Valeur. |

 **Result:**
boolean


---


### resetChannels{#resetChannels}

| Nom | Description |
| --- | --- |
| resetChannels() | Vide les canaux de propriétés de ce mappage de courbes d'animation. |

 **Result:**
boolean


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




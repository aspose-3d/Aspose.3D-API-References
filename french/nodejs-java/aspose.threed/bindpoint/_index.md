---
title: BindPoint
second_title: Référence d'API Aspose.3D pour Node.js via Java
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
| scene | Scène | La scène qui contient l'animation. |
| prop | Property | Propriété. |

 **Result:**



---


### getProperty{#getProperty}

| Nom | Description |
| --- | --- |
| getProperty() | Obtient la propriété associée au CurveMapping |

 **Result:**



---


### setProperty{#setProperty}

| Nom | Description |
| --- | --- |
| setProperty(value) | Obtient la propriété associée au CurveMapping |

 **Result:**



---


### getChannelsCount{#getChannelsCount}

| Nom | Description |
| --- | --- |
| getChannelsCount() | Obtient le nombre total de canaux de propriétés définis dans ce mappage de courbe d'animation. |

 **Result:**
Number


---


### getName{#getName}

| Nom | Description |
| --- | --- |
| getName() | Obtient ou définit le nom. Le nom. |

 **Result:**
Number


---


### setName{#setName}

| Nom | Description |
| --- | --- |
| setName(value) | Obtient ou définit le nom. Le nom. |

 **Result:**
Number


---


### getProperties{#getProperties}

| Nom | Description |
| --- | --- |
| getProperties() | Obtient la collection de toutes les propriétés. |

 **Result:**
Number


---


### get{#get}

| Nom | Description |
| --- | --- |
| get(channelName) |  |

 **Result:**
Number


---


### getKeyframeSequence{#getKeyframeSequence}

| Nom | Description |
| --- | --- |
| getKeyframeSequence(channelName) | Obtient la première séquence d'images clés dans le canal spécifié |

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
| getKeyframeSequences(channelName) | Récupère toutes les séquences d'images clés dans le canal spécifié |

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
| createKeyframeSequence(name) | Crée une nouvelle courbe et la connecte au premier canal du mappage de courbe |

 **Parameters:**

| Nom | Type | Description |
| --- | --- | --- |
| nom | String | Le nom de la nouvelle séquence. |

 **Result:**
KeyframeSequence


---


### bindKeyframeSequence{#bindKeyframeSequence}

| Nom | Description |
| --- | --- |
| bindKeyframeSequence(channelName, sequence) | Lier la séquence d'images clés au canal spécifié |

 **Parameters:**

| Nom | Type | Description |
| --- | --- | --- |
| channelName | String | Quel canal la séquence d'images clés sera liée à |
| séquence | KeyframeSequence | La séquence d'images clés à lier |

 **Result:**
KeyframeSequence


---


### getChannel{#getChannel}

| Nom | Description |
| --- | --- |
| getChannel(channelName) | Obtient le canal par le nom donné |

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
| nom | String | Name. |
| valeur | Object | Valeur. |

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
| nom | String | Name. |
| type | Classe | Type. |
| valeur | Object | Valeur. |

 **Result:**
boolean


---


### resetChannels{#resetChannels}

| Nom | Description |
| --- | --- |
| resetChannels() | Vide les canaux de propriétés de ce mappage de courbe d'animation. |

 **Result:**
boolean


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




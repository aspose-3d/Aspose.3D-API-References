---
title: AnimationChannel
second_title: Référence d'API Aspose.3D pour Node.js via Java
description: 
type: docs

url: /fr/nodejs-java/aspose.threed/animationchannel/
---
## AnimationChannel class

Un canal mappe le champ de composant d'une propriété à un ensemble de séquences d'images clés  @hideconstructor


## Méthodes

### getComponentType{#getComponentType}

| Nom | Description |
| --- | --- |
| getComponentType() | Obtient le type du champ de composant |

 **Result:**



---


### getName{#getName}

| Nom | Description |
| --- | --- |
| getName() | Obtient le nom du canal |

 **Result:**



---


### getDefaultValue{#getDefaultValue}

| Nom | Description |
| --- | --- |
| getDefaultValue() | Obtient ou définit la valeur Default du canal. Si un canal n’a aucune séquence d’images clés connectée, la valeur par défaut sera utilisée lors de l’évaluation de l’animation. Un scénario réel : l’animation ne modifie que la coordonnée x d’un nœud, les y et z ne sont pas changés, alors la valeur par défaut sera utilisée lors de l’évaluation complète de la translation. |

 **Result:**



---


### setDefaultValue{#setDefaultValue}

| Nom | Description |
| --- | --- |
| setDefaultValue(value) | Obtient ou définit la valeur Default du canal. Si un canal n’a aucune séquence d’images clés connectée, la valeur par défaut sera utilisée lors de l’évaluation de l’animation. Un scénario réel : l’animation ne modifie que la coordonnée x d’un nœud, les y et z ne sont pas changés, alors la valeur par défaut sera utilisée lors de l’évaluation complète de la translation. |

 **Result:**



---


### getKeyframeSequences{#getKeyframeSequences}

| Nom | Description |
| --- | --- |
| getKeyframeSequences() | Obtient toutes les séquences d’images clés à l’intérieur de ce canal |

 **Result:**



---


### addKeyframeSequence{#addKeyframeSequence}

| Nom | Description |
| --- | --- |
| addKeyframeSequence(sequence) | Ajoute une séquence d’images clés à ce canal |

 **Parameters:**

| Nom | Type | Description |
| --- | --- | --- |
| séquence | KeyframeSequence | La séquence d’images clés à ajouter. |

 **Result:**



---


### iterator{#iterator}

| Nom | Description |
| --- | --- |
| iterator() | Réservé à un usage interne. |

 **Result:**



---




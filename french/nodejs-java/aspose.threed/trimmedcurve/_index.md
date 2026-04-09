---
title: TrimmedCurve
second_title: Référence d'API Aspose.3D pour Node.js via Java
description: 
type: docs

url: /fr/nodejs-java/aspose.threed/trimmedcurve/
---
## TrimmedCurve class

Une courbe bornée qui coupe la courbe de base aux deux extrémités.


## Méthodes

### constructor{#constructor}

| Nom | Description |
| --- | --- |
| constructor() | Constructeur de TrimmedCurve |

 **Result:**



---


### getBasisCurve{#getBasisCurve}

| Nom | Description |
| --- | --- |
| getBasisCurve() | La courbe de base à découper. |

 **Result:**



---


### setBasisCurve{#setBasisCurve}

| Nom | Description |
| --- | --- |
| setBasisCurve(value) | La courbe de base à découper. |

 **Result:**



---


### getFirst{#getFirst}

| Nom | Description |
| --- | --- |
| getFirst() | Le premier point d'extrémité à tronquer, peut être un point cartésien ou un paramètre réel. |

 **Result:**



---


### setFirst{#setFirst}

| Nom | Description |
| --- | --- |
| setFirst(value) | Le premier point d'extrémité à tronquer, peut être un point cartésien ou un paramètre réel. |

 **Result:**



---


### getSecond{#getSecond}

| Nom | Description |
| --- | --- |
| getSecond() | Le deuxième point d'extrémité à tronquer, peut être un point cartésien ou un paramètre réel. |

 **Result:**



---


### setSecond{#setSecond}

| Nom | Description |
| --- | --- |
| setSecond(value) | Le deuxième point d'extrémité à tronquer, peut être un point cartésien ou un paramètre réel. |

 **Result:**



---


### getSameDirection{#getSameDirection}

| Nom | Description |
| --- | --- |
| getSameDirection() | Obtient ou définit si le résultat tronqué utilise la même direction de la courbe de base. |

 **Result:**



---


### setSameDirection{#setSameDirection}

| Nom | Description |
| --- | --- |
| setSameDirection(value) | Obtient ou définit si le résultat tronqué utilise la même direction de la courbe de base. |

 **Result:**



---


### getColor{#getColor}

| Nom | Description |
| --- | --- |
| getColor() | Obtient ou définit la couleur de la ligne, la valeur par défaut est blanc(1, 1, 1) |

 **Result:**



---


### setColor{#setColor}

| Nom | Description |
| --- | --- |
| setColor(value) | Obtient ou définit la couleur de la ligne, la valeur par défaut est blanc(1, 1, 1) |

 **Result:**



---


### getParentNodes{#getParentNodes}

| Nom | Description |
| --- | --- |
| getParentNodes() | Obtient tous les nœuds parents, une entité peut être attachée à plusieurs nœuds parents pour l'instanciation de géométrie. Les nœuds. |

 **Result:**



---


### getExcluded{#getExcluded}

| Nom | Description |
| --- | --- |
| getExcluded() | Obtient ou définit si cette entité doit être exclue lors de l'exportation. |

 **Result:**



---


### setExcluded{#setExcluded}

| Nom | Description |
| --- | --- |
| setExcluded(value) | Obtient ou définit si cette entité doit être exclue lors de l'exportation. |

 **Result:**



---


### getParentNode{#getParentNode}

| Nom | Description |
| --- | --- |
| getParentNode() | Obtient ou définit le premier nœud parent, si le premier nœud parent est défini, cette entité sera détachée des autres nœuds parents. Le nœud parent. |

 **Result:**



---


### setParentNode{#setParentNode}

| Nom | Description |
| --- | --- |
| setParentNode(value) | Obtient ou définit le premier nœud parent, si le premier nœud parent est défini, cette entité sera détachée des autres nœuds parents. Le nœud parent. |

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


### getEntityRendererKey{#getEntityRendererKey}

| Nom | Description |
| --- | --- |
| getEntityRendererKey() | Obtient la clé du rendu d'entité enregistré dans le moteur de rendu |

 **Result:**
EntityRendererKey


---


### getBoundingBox{#getBoundingBox}

| Nom | Description |
| --- | --- |
| getBoundingBox() | Obtient la boîte englobante de l'entité actuelle dans son système de coordonnées d'espace objet. |

 **Result:**
EntityRendererKey


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




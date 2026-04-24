---
title: UShape
second_title: Référence d'API Aspose.3D pour Node.js via Java
description: 
type: docs

url: /fr/nodejs-java/aspose.threed/ushape/
---
## UShape class

Forme en U compatible IFC définie par des paramètres.


## Méthodes

### constructor{#constructor}

| Nom | Description |
| --- | --- |
| constructor() | Constructeur de UShape |

 **Result:**



---


### getDepth{#getDepth}

| Nom | Description |
| --- | --- |
| getDepth() | Obtient ou définit la longueur du web. |

 **Result:**



---


### setDepth{#setDepth}

| Nom | Description |
| --- | --- |
| setDepth(value) | Obtient ou définit la longueur du web. |

 **Result:**



---


### getFlangeWidth{#getFlangeWidth}

| Nom | Description |
| --- | --- |
| getFlangeWidth() | Obtient ou définit la longueur de la flange. |

 **Result:**



---


### setFlangeWidth{#setFlangeWidth}

| Nom | Description |
| --- | --- |
| setFlangeWidth(value) | Obtient ou définit la longueur de la flange. |

 **Result:**



---


### getWebThickness{#getWebThickness}

| Nom | Description |
| --- | --- |
| getWebThickness() | Obtient ou définit l'épaisseur du filet. |

 **Result:**



---


### setWebThickness{#setWebThickness}

| Nom | Description |
| --- | --- |
| setWebThickness(value) | Obtient ou définit l'épaisseur du filet. |

 **Result:**



---


### getFlangeThickness{#getFlangeThickness}

| Nom | Description |
| --- | --- |
| getFlangeThickness() | Obtient ou définit l'épaisseur de la flange. |

 **Result:**



---


### setFlangeThickness{#setFlangeThickness}

| Nom | Description |
| --- | --- |
| setFlangeThickness(value) | Obtient ou définit l'épaisseur de la flange. |

 **Result:**



---


### getFilletRadius{#getFilletRadius}

| Nom | Description |
| --- | --- |
| getFilletRadius() | Obtient ou définit le rayon du congé entre la flange et le web. |

 **Result:**



---


### setFilletRadius{#setFilletRadius}

| Nom | Description |
| --- | --- |
| setFilletRadius(value) | Obtient ou définit le rayon du congé entre la flange et le web. |

 **Result:**



---


### getEdgeRadius{#getEdgeRadius}

| Nom | Description |
| --- | --- |
| getEdgeRadius() | Obtient ou définit le rayon du bord dans le bord de la bride. |

 **Result:**



---


### setEdgeRadius{#setEdgeRadius}

| Nom | Description |
| --- | --- |
| setEdgeRadius(value) | Obtient ou définit le rayon du bord dans le bord de la bride. |

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


### getExtent{#getExtent}

| Nom | Description |
| --- | --- |
| getExtent() | Obtient l'étendue dans les dimensions x et y. |

 **Result:**
Vector2


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




---
title: HollowRectangleShape
second_title: Référence d'API Aspose.3D pour Node.js via Java
description: 
type: docs

url: /fr/nodejs-java/aspose.threed/hollowrectangleshape/
---
## HollowRectangleShape class

Forme rectangulaire creuse compatible IFC avec des coins arrondis intérieurs/extérieurs.


## Méthodes

### constructor{#constructor}

| Nom | Description |
| --- | --- |
| constructor() |  |

 **Result:**



---


### getWallThickness{#getWallThickness}

| Nom | Description |
| --- | --- |
| getWallThickness() | L'épaisseur entre la bordure du rectangle et le trou intérieur |

 **Result:**



---


### setWallThickness{#setWallThickness}

| Nom | Description |
| --- | --- |
| setWallThickness(value) | L'épaisseur entre la bordure du rectangle et le trou intérieur |

 **Result:**



---


### getInnerFilletRadius{#getInnerFilletRadius}

| Nom | Description |
| --- | --- |
| getInnerFilletRadius() | Le rayon du congé intérieur du rectangle interne. |

 **Result:**



---


### setInnerFilletRadius{#setInnerFilletRadius}

| Nom | Description |
| --- | --- |
| setInnerFilletRadius(value) | Le rayon du congé intérieur du rectangle interne. |

 **Result:**



---


### getRoundingRadius{#getRoundingRadius}

| Nom | Description |
| --- | --- |
| getRoundingRadius() | Obtient ou définit le rayon des arcs circulaires des quatre coins, mesuré en degrés. Valeur par défaut : 0.0 |

 **Result:**



---


### setRoundingRadius{#setRoundingRadius}

| Nom | Description |
| --- | --- |
| setRoundingRadius(value) | Obtient ou définit le rayon des arcs circulaires des quatre coins, mesuré en degrés. Valeur par défaut : 0.0 |

 **Result:**



---


### getXDim{#getXDim}

| Nom | Description |
| --- | --- |
| getXDim() | Obtient ou définit l'étendue du rectangle dans la direction de l'axe x. Valeur par défaut : 2.0 |

 **Result:**



---


### setXDim{#setXDim}

| Nom | Description |
| --- | --- |
| setXDim(value) | Obtient ou définit l'étendue du rectangle dans la direction de l'axe x. Valeur par défaut : 2.0 |

 **Result:**



---


### getYDim{#getYDim}

| Nom | Description |
| --- | --- |
| getYDim() | Obtient ou définit l'étendue du rectangle dans la direction de l'axe y. Valeur par défaut : 2.0 |

 **Result:**



---


### setYDim{#setYDim}

| Nom | Description |
| --- | --- |
| setYDim(value) | Obtient ou définit l'étendue du rectangle dans la direction de l'axe y. Valeur par défaut : 2.0 |

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




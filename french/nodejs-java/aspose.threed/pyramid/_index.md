---
title: Pyramide
second_title: Référence d'API Aspose.3D pour Node.js via Java
description: 
type: docs

url: /fr/nodejs-java/aspose.threed/pyramid/
---
## Pyramid class

Pyramide paramétrée.


## Méthodes

### constructor{#constructor}

| Nom | Description |
| --- | --- |
| constructor() | Construire une nouvelle instance de pyramide avec la zone inférieure par défaut (10, 10) et la hauteur par défaut (5) |

 **Result:**



---


### constructor_overload{#constructor_overload}

| Nom | Description |
| --- | --- |
| constructor_overload(xbottom, ybottom, height) | Construire une nouvelle instance de pyramide avec la zone inférieure spécifiée |

 **Parameters:**

| Nom | Type | Description |
| --- | --- | --- |
| xbottom | Number | La longueur dans la direction x du bas |
| ybottom | Number | La longueur dans la direction y du bas |
| hauteur | Number | La hauteur de la pyramide |

 **Result:**



---


### constructor_overload2{#constructor_overload2}

| Nom | Description |
| --- | --- |
| constructor_overload2(xbottom, ybottom, xtop, ytop, height) | Construire une nouvelle instance de pyramide avec la zone inférieure et la zone supérieure spécifiées ainsi que la hauteur. |

 **Parameters:**

| Nom | Type | Description |
| --- | --- | --- |
| xbottom | Number | La longueur dans la direction x de la zone inférieure |
| ybottom | Number | La longueur dans la direction y de la zone inférieure |
| xtop | Number | La longueur dans la direction x de la zone supérieure |
| ytop | Number | La longueur dans la direction y de la zone supérieure |
| hauteur | Number | La hauteur de la pyramide |

 **Result:**



---


### constructor_overload3{#constructor_overload3}

| Nom | Description |
| --- | --- |
| constructor_overload3(name, xbottom, ybottom, xtop, ytop, height) | Construire une nouvelle instance de pyramide avec la zone inférieure et la zone supérieure spécifiées ainsi que la hauteur. |

 **Parameters:**

| Nom | Type | Description |
| --- | --- | --- |
| nom | String | Le nom de la pyramide |
| xbottom | Number | La longueur dans la direction x de la zone inférieure |
| ybottom | Number | La longueur dans la direction y de la zone inférieure |
| xtop | Number | La longueur dans la direction x de la zone supérieure |
| ytop | Number | La longueur dans la direction y de la zone supérieure |
| hauteur | Number | La hauteur de la pyramide |

 **Result:**



---


### getBottomArea{#getBottomArea}

| Nom | Description |
| --- | --- |
| getBottomArea() | Surface du cap inférieur |

 **Result:**



---


### setBottomArea{#setBottomArea}

| Nom | Description |
| --- | --- |
| setBottomArea(value) | Surface du cap inférieur |

 **Result:**



---


### getTopArea{#getTopArea}

| Nom | Description |
| --- | --- |
| getTopArea() | Surface du cap supérieur |

 **Result:**



---


### setTopArea{#setTopArea}

| Nom | Description |
| --- | --- |
| setTopArea(value) | Surface du cap supérieur |

 **Result:**



---


### getBottomOffset{#getBottomOffset}

| Nom | Description |
| --- | --- |
| getBottomOffset() | Décalage pour les sommets inférieurs |

 **Result:**



---


### setBottomOffset{#setBottomOffset}

| Nom | Description |
| --- | --- |
| setBottomOffset(value) | Décalage pour les sommets inférieurs |

 **Result:**



---


### getHeight{#getHeight}

| Nom | Description |
| --- | --- |
| getHeight() | Hauteur de la pyramide |

 **Result:**



---


### setHeight{#setHeight}

| Nom | Description |
| --- | --- |
| setHeight(value) | Hauteur de la pyramide |

 **Result:**



---


### getCastShadows{#getCastShadows}

| Nom | Description |
| --- | --- |
| getCastShadows() | Obtient ou définit si cette géométrie peut projeter une ombre |

 **Result:**



---


### setCastShadows{#setCastShadows}

| Nom | Description |
| --- | --- |
| setCastShadows(value) | Obtient ou définit si cette géométrie peut projeter une ombre |

 **Result:**



---


### getReceiveShadows{#getReceiveShadows}

| Nom | Description |
| --- | --- |
| getReceiveShadows() | Obtient ou définit si cette géométrie peut recevoir une ombre. |

 **Result:**



---


### setReceiveShadows{#setReceiveShadows}

| Nom | Description |
| --- | --- |
| setReceiveShadows(value) | Obtient ou définit si cette géométrie peut recevoir une ombre. |

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


### toMesh{#toMesh}

| Nom | Description |
| --- | --- |
| toMesh() | Convertir l'objet actuel en maillage |

 **Result:**
Mesh


---


### getBoundingBox{#getBoundingBox}

| Nom | Description |
| --- | --- |
| getBoundingBox() | Obtient la boîte englobante de l'entité actuelle dans son système de coordonnées d'espace objet. |

 **Result:**
Mesh


---


### getEntityRendererKey{#getEntityRendererKey}

| Nom | Description |
| --- | --- |
| getEntityRendererKey() | Obtient la clé du rendu d'entité enregistré dans le moteur de rendu |

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




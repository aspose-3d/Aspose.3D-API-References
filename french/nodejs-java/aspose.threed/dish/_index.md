---
title: Dish
second_title: Référence d'API Aspose.3D pour Node.js via Java
description: 
type: docs

url: /fr/nodejs-java/aspose.threed/dish/
---
## Dish class

Plat paramétré.


## Méthodes

### constructor{#constructor}

| Nom | Description |
| --- | --- |
| constructor() | Créer une nouvelle instance de dish avec un rayon par défaut (10) et une hauteur par défaut (5) |

 **Result:**



---


### constructor_overload{#constructor_overload}

| Nom | Description |
| --- | --- |
| constructor_overload(radius, height) | Créer une nouvelle instance de dish avec le rayon et la hauteur spécifiés |

 **Parameters:**

| Nom | Type | Description |
| --- | --- | --- |
| radius | Number | Le rayon du plat |
| hauteur | Number | La hauteur du plat |

 **Result:**



---


### constructor_overload2{#constructor_overload2}

| Nom | Description |
| --- | --- |
| constructor_overload2(name, radius, height, widthSegments, heightSegments) | Créer une nouvelle instance de dish avec le rayon et la hauteur spécifiés |

 **Parameters:**

| Nom | Type | Description |
| --- | --- | --- |
| nom | String | Le nom du plat |
| radius | Number | Le rayon du plat |
| hauteur | Number | La hauteur du plat |
| widthSegments | Number | Le segment de largeur du plat |
| heightSegments | Number | Le segment de hauteur du plat |

 **Result:**



---


### getHeight{#getHeight}

| Nom | Description |
| --- | --- |
| getHeight() | Hauteur du dish |

 **Result:**



---


### setHeight{#setHeight}

| Nom | Description |
| --- | --- |
| setHeight(value) | Hauteur du dish |

 **Result:**



---


### getRadius{#getRadius}

| Nom | Description |
| --- | --- |
| getRadius() | Rayon du plat |

 **Result:**



---


### setRadius{#setRadius}

| Nom | Description |
| --- | --- |
| setRadius(value) | Rayon du plat |

 **Result:**



---


### getWidthSegments{#getWidthSegments}

| Nom | Description |
| --- | --- |
| getWidthSegments() | Obtient ou définit les segments de largeur |

 **Result:**



---


### setWidthSegments{#setWidthSegments}

| Nom | Description |
| --- | --- |
| setWidthSegments(value) | Obtient ou définit les segments de largeur |

 **Result:**



---


### getHeightSegments{#getHeightSegments}

| Nom | Description |
| --- | --- |
| getHeightSegments() | Obtient ou définit les segments de hauteur |

 **Result:**



---


### setHeightSegments{#setHeightSegments}

| Nom | Description |
| --- | --- |
| setHeightSegments(value) | Obtient ou définit les segments de hauteur |

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




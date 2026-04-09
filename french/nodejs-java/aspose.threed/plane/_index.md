---
title: Plane
second_title: Référence d'API Aspose.3D pour Node.js via Java
description: 
type: docs

url: /fr/nodejs-java/aspose.threed/plane/
---
## Plane class

Plan paramétré.


## Méthodes

### constructor{#constructor}

| Nom | Description |
| --- | --- |
| constructor() | Initialise une nouvelle instance de Plane avec une taille par défaut de 1x1. |

 **Result:**



---


### constructor_overload{#constructor_overload}

| Nom | Description |
| --- | --- |
| constructor_overload(length, width) | Initialise une nouvelle instance de Plane. |

 **Parameters:**

| Nom | Type | Description |
| --- | --- | --- |
| longueur | Number | Longueur du plan. |
| largeur | Number | Largeur du plan. |

 **Result:**



---


### constructor_overload2{#constructor_overload2}

| Nom | Description |
| --- | --- |
| constructor_overload2(name, length, width, lengthSegments, widthSegments) | Initialise une nouvelle instance de Plane. |

 **Parameters:**

| Nom | Type | Description |
| --- | --- | --- |
| nom | String | Name. |
| longueur | Number | Longueur du plan. |
| largeur | Number | Largeur du plan. |
| lengthSegments | Number | Segments de longueur. |
| widthSegments | Number | Segments de largeur. |

 **Result:**



---


### getUp{#getUp}

| Nom | Description |
| --- | --- |
| getUp() | Obtient ou définit le vecteur up du plan, la valeur par défaut est (0, 1, 0), cela affecte la génération du plan |

 **Result:**



---


### setUp{#setUp}

| Nom | Description |
| --- | --- |
| setUp(value) | Obtient ou définit le vecteur up du plan, la valeur par défaut est (0, 1, 0), cela affecte la génération du plan |

 **Result:**



---


### getLength{#getLength}

| Nom | Description |
| --- | --- |
| getLength() | Obtient ou définit la longueur du plan. La longueur. |

 **Result:**



---


### setLength{#setLength}

| Nom | Description |
| --- | --- |
| setLength(value) | Obtient ou définit la longueur du plan. La longueur. |

 **Result:**



---


### getWidth{#getWidth}

| Nom | Description |
| --- | --- |
| getWidth() | Obtient ou définit la largeur du plan. La largeur. |

 **Result:**



---


### setWidth{#setWidth}

| Nom | Description |
| --- | --- |
| setWidth(value) | Obtient ou définit la largeur du plan. La largeur. |

 **Result:**



---


### getLengthSegments{#getLengthSegments}

| Nom | Description |
| --- | --- |
| getLengthSegments() | Obtient ou définit les segments de longueur. Les segments de longueur. |

 **Result:**



---


### setLengthSegments{#setLengthSegments}

| Nom | Description |
| --- | --- |
| setLengthSegments(value) | Obtient ou définit les segments de longueur. Les segments de longueur. |

 **Result:**



---


### getWidthSegments{#getWidthSegments}

| Nom | Description |
| --- | --- |
| getWidthSegments() | Obtient ou définit les segments de largeur. Les segments de largeur. |

 **Result:**



---


### setWidthSegments{#setWidthSegments}

| Nom | Description |
| --- | --- |
| setWidthSegments(value) | Obtient ou définit les segments de largeur. Les segments de largeur. |

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




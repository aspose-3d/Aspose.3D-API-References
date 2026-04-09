---
title: RevolvedAreaSolid
second_title: Référence d'API Aspose.3D pour Node.js via Java
description: 
type: docs

url: /fr/nodejs-java/aspose.threed/revolvedareasolid/
---
## RevolvedAreaSolid class

Cette classe représente un modèle solide en faisant tourner une section transversale fournie par un profil autour d'un axe.


## Méthodes

### constructor{#constructor}

| Nom | Description |
| --- | --- |
| constructor() |  |

 **Result:**



---


### getAngleStart{#getAngleStart}

| Nom | Description |
| --- | --- |
| getAngleStart() | Obtient ou définit l'angle de départ de la procédure de révolution, mesuré en radians, la valeur par défaut est 0. |

 **Result:**



---


### setAngleStart{#setAngleStart}

| Nom | Description |
| --- | --- |
| setAngleStart(value) | Obtient ou définit l'angle de départ de la procédure de révolution, mesuré en radians, la valeur par défaut est 0. |

 **Result:**



---


### getAngleEnd{#getAngleEnd}

| Nom | Description |
| --- | --- |
| getAngleEnd() | Obtient ou définit l'angle final de la procédure de révolution, mesuré en radians, la valeur par défaut est π. |

 **Result:**



---


### setAngleEnd{#setAngleEnd}

| Nom | Description |
| --- | --- |
| setAngleEnd(value) | Obtient ou définit l'angle final de la procédure de révolution, mesuré en radians, la valeur par défaut est π. |

 **Result:**



---


### getAxis{#getAxis}

| Nom | Description |
| --- | --- |
| getAxis() | Obtient ou définit la direction de l'axe, la valeur par défaut est (0, 1, 0). |

 **Result:**



---


### setAxis{#setAxis}

| Nom | Description |
| --- | --- |
| setAxis(value) | Obtient ou définit la direction de l'axe, la valeur par défaut est (0, 1, 0). |

 **Result:**



---


### getOrigin{#getOrigin}

| Nom | Description |
| --- | --- |
| getOrigin() | Obtient ou définit le point d'origine de la révolution, la valeur par défaut est (0, 0, 0). |

 **Result:**



---


### setOrigin{#setOrigin}

| Nom | Description |
| --- | --- |
| setOrigin(value) | Obtient ou définit le point d'origine de la révolution, la valeur par défaut est (0, 0, 0). |

 **Result:**



---


### getShape{#getShape}

| Nom | Description |
| --- | --- |
| getShape() | Obtient ou définit le profil de base utilisé pour la révolution. |

 **Result:**



---


### setShape{#setShape}

| Nom | Description |
| --- | --- |
| setShape(value) | Obtient ou définit le profil de base utilisé pour la révolution. |

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
| toMesh() | Convertit le RevolvedAreaSolid en maillage. |

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




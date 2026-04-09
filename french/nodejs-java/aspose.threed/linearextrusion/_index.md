---
title: LinearExtrusion
second_title: Référence d'API Aspose.3D pour Node.js via Java
description: 
type: docs

url: /fr/nodejs-java/aspose.threed/linearextrusion/
---
## LinearExtrusion class

L'extrusion linéaire prend une forme 2D en entrée et étend la forme dans la troisième dimension.


## Méthodes

### constructor{#constructor}

| Nom | Description |
| --- | --- |
| constructor() | Constructeur de l'instance LinearExtrusion. |

 **Result:**



---


### constructor_overload{#constructor_overload}

| Nom | Description |
| --- | --- |
| constructor_overload(shape, height) | Constructeur de l'instance LinearExtrusion. |

 **Result:**



---


### getShape{#getShape}

| Nom | Description |
| --- | --- |
| getShape() | La forme de base à extruder. |

 **Result:**



---


### setShape{#setShape}

| Nom | Description |
| --- | --- |
| setShape(value) | La forme de base à extruder. |

 **Result:**



---


### getDirection{#getDirection}

| Nom | Description |
| --- | --- |
| getDirection() | La direction de l'extrusion, la valeur par défaut est (0, 0, 1) |

 **Result:**



---


### setDirection{#setDirection}

| Nom | Description |
| --- | --- |
| setDirection(value) | La direction de l'extrusion, la valeur par défaut est (0, 0, 1) |

 **Result:**



---


### getHeight{#getHeight}

| Nom | Description |
| --- | --- |
| getHeight() | La hauteur de la géométrie extrudée, la valeur par défaut est 1.0 |

 **Result:**



---


### setHeight{#setHeight}

| Nom | Description |
| --- | --- |
| setHeight(value) | La hauteur de la géométrie extrudée, la valeur par défaut est 1.0 |

 **Result:**



---


### getSlices{#getSlices}

| Nom | Description |
| --- | --- |
| getSlices() | Les tranches de la géométrie extrudée tordue, la valeur par défaut est 1. |

 **Result:**



---


### setSlices{#setSlices}

| Nom | Description |
| --- | --- |
| setSlices(value) | Les tranches de la géométrie extrudée tordue, la valeur par défaut est 1. |

 **Result:**



---


### getCenter{#getCenter}

| Nom | Description |
| --- | --- |
| getCenter() | Si cette valeur est fausse, la plage Z de l'extrusion linéaire va de 0 à la hauteur, sinon la plage va de -hauteur/2 à hauteur/2. |

 **Result:**



---


### setCenter{#setCenter}

| Nom | Description |
| --- | --- |
| setCenter(value) | Si cette valeur est fausse, la plage Z de l'extrusion linéaire va de 0 à la hauteur, sinon la plage va de -hauteur/2 à hauteur/2. |

 **Result:**



---


### getTwistOffset{#getTwistOffset}

| Nom | Description |
| --- | --- |
| getTwistOffset() | Le décalage utilisé dans la torsion, la valeur par défaut est (0, 0, 0). |

 **Result:**



---


### setTwistOffset{#setTwistOffset}

| Nom | Description |
| --- | --- |
| setTwistOffset(value) | Le décalage utilisé dans la torsion, la valeur par défaut est (0, 0, 0). |

 **Result:**



---


### getTwist{#getTwist}

| Nom | Description |
| --- | --- |
| getTwist() | Le nombre de degrés selon lesquels la forme est extrudée. |

 **Result:**



---


### setTwist{#setTwist}

| Nom | Description |
| --- | --- |
| setTwist(value) | Le nombre de degrés selon lesquels la forme est extrudée. |

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
| toMesh() | Convertir l'extrusion en maillage. |

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




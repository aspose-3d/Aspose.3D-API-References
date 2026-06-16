---
title: "PointCloud"
second_title: "Référence d'API Aspose.3D pour Node.js via Java"
description: 
type: docs

url: /fr/nodejs-java/aspose.threed/pointcloud/
---
## PointCloud class

Le nuage de points ne contient aucune information de topologie mais uniquement les points de contrôle et les éléments de sommet.


## Méthodes

### constructor{#constructor}

| Nom | Description |
| --- | --- |
| constructor(name) | Constructeur de PointCloud |

 **Parameters:**

| Nom | Type | Description |
| --- | --- | --- |
| name | String | Le nom de cette entité |

 **Result:**



---


### constructor_overload{#constructor_overload}

| Nom | Description |
| --- | --- |
| constructor_overload() | Constructeur de PointCloud |

 **Result:**



---


### getVisible{#getVisible}

| Nom | Description |
| --- | --- |
| getVisible() | Récupère ou définit si la géométrie est visible |

 **Result:**



---


### setVisible{#setVisible}

| Nom | Description |
| --- | --- |
| setVisible(value) | Récupère ou définit si la géométrie est visible |

 **Result:**



---


### getDeformers{#getDeformers}

| Nom | Description |
| --- | --- |
| getDeformers() | Récupère tous les déformateurs associés à cette géométrie. Les déformateurs. |

 **Result:**



---


### getControlPoints{#getControlPoints}

| Nom | Description |
| --- | --- |
| getControlPoints() | Récupère tous les points de contrôle |

 **Result:**



---


### getCastShadows{#getCastShadows}

| Nom | Description |
| --- | --- |
| getCastShadows() | Récupère ou définit si cette géométrie peut projeter une ombre |

 **Result:**



---


### setCastShadows{#setCastShadows}

| Nom | Description |
| --- | --- |
| setCastShadows(value) | Récupère ou définit si cette géométrie peut projeter une ombre |

 **Result:**



---


### getReceiveShadows{#getReceiveShadows}

| Nom | Description |
| --- | --- |
| getReceiveShadows() | Récupère ou définit si cette géométrie peut recevoir une ombre. |

 **Result:**



---


### setReceiveShadows{#setReceiveShadows}

| Nom | Description |
| --- | --- |
| setReceiveShadows(value) | Récupère ou définit si cette géométrie peut recevoir une ombre. |

 **Result:**



---


### getVertexElements{#getVertexElements}

| Nom | Description |
| --- | --- |
| getVertexElements() | Récupère tous les éléments de sommet |

 **Result:**



---


### getParentNodes{#getParentNodes}

| Nom | Description |
| --- | --- |
| getParentNodes() | Obtient tous les nœuds parents, une entité peut être attachée à plusieurs nœuds parents pour l'instanciation géométrique. Les nœuds. |

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
| getParentNode() | Obtient ou définit le premier nœud parent ; si le premier nœud parent est défini, cette entité sera détachée des autres nœuds parents. Le nœud parent. |

 **Result:**



---


### setParentNode{#setParentNode}

| Nom | Description |
| --- | --- |
| setParentNode(value) | Obtient ou définit le premier nœud parent ; si le premier nœud parent est défini, cette entité sera détachée des autres nœuds parents. Le nœud parent. |

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


### fromGeometry{#fromGeometry}

| Nom | Description |
| --- | --- |
| fromGeometry(g) | Créez une nouvelle instance de PointCloud à partir d'un objet de géométrie |

 **Parameters:**

| Nom | Type | Description |
| --- | --- | --- |
|  | Geometry | null |

 **Result:**
PointCloud


---


### fromGeometry{#fromGeometry}

| Nom | Description |
| --- | --- |
| fromGeometry(g, density) | Créez une nouvelle instance de point cloud à partir d'un objet de géométrie. La densité est le nombre de points par triangle unité (les triangles unité sont les triangles avec la surface maximale du maillage) |

 **Parameters:**

| Nom | Type | Description |
| --- | --- | --- |
| g | Geometry | Mesh ou autre instance de géométrie |
| density | Nombre | Nombre de points par triangle unité |

 **Result:**
PointCloud


---


### getElement{#getElement}

| Nom | Description |
| --- | --- |
| getElement(type) | Obtient un élément de sommet avec le type spécifié |

 **Parameters:**

| Nom | Type | Description |
| --- | --- | --- |
| type | VertexElementType | VertexElementType |

 **Result:**
VertexElement


---


### getVertexElementOfUV{#getVertexElementOfUV}

| Nom | Description |
| --- | --- |
| getVertexElementOfUV(textureMapping) | Obtient une instance VertexElementUV avec le type de texture mapping donné |

 **Parameters:**

| Nom | Type | Description |
| --- | --- | --- |
| textureMapping | TextureMapping | TextureMapping |

 **Result:**
VertexElementUV


---


### createElement{#createElement}

| Nom | Description |
| --- | --- |
| createElement(type) | Crée un élément de sommet avec le type spécifié et l'ajoute à la géométrie. Si le type est VertexElementType.UV, un VertexElementUV avec le type de texture mapping à TextureMapping.DIFFUSE sera créé. |

 **Parameters:**

| Nom | Type | Description |
| --- | --- | --- |
| type | VertexElementType | VertexElementType |

 **Result:**
VertexElement


---


### addElement{#addElement}

| Nom | Description |
| --- | --- |
| addElement(element) | Ajoute un élément de sommet existant à la géométrie actuelle |

 **Parameters:**

| Nom | Type | Description |
| --- | --- | --- |
| element | VertexElement | L'élément de sommet à ajouter |

 **Result:**
VertexElement


---


### createElement{#createElement}

| Nom | Description |
| --- | --- |
| createElement(type, mappingMode, referenceMode) | Crée un élément de sommet avec le type spécifié et l'ajoute à la géométrie. Si le type est VertexElementType.UV, un VertexElementUV avec le type de texture mapping à TextureMapping.DIFFUSE sera créé. |

 **Parameters:**

| Nom | Type | Description |
| --- | --- | --- |
| type | VertexElementType | VertexElementType |
| mappingMode | MappingMode | MappingMode |
| referenceMode | ReferenceMode | ReferenceMode |

 **Result:**
VertexElement


---


### createElementUV{#createElementUV}

| Nom | Description |
| --- | --- |
| createElementUV(uvMapping) | Crée un VertexElementUV avec le type de mappage de texture donné. |

 **Parameters:**

| Nom | Type | Description |
| --- | --- | --- |
| uvMapping | TextureMapping | TextureMapping |

 **Result:**
VertexElementUV


---


### createElementUV{#createElementUV}

| Nom | Description |
| --- | --- |
| createElementUV(uvMapping, mappingMode, referenceMode) | Crée un VertexElementUV avec le type de mappage de texture donné. |

 **Parameters:**

| Nom | Type | Description |
| --- | --- | --- |
| uvMapping | TextureMapping | TextureMapping |
| mappingMode | MappingMode | MappingMode |
| referenceMode | ReferenceMode | ReferenceMode |

 **Result:**
VertexElementUV


---


### getBoundingBox{#getBoundingBox}

| Nom | Description |
| --- | --- |
| getBoundingBox() | Obtient la boîte englobante de l'entité actuelle dans son système de coordonnées d'espace objet. |

 **Result:**
VertexElementUV


---


### removeProperty{#removeProperty}

| Nom | Description |
| --- | --- |
| removeProperty(property) | Supprime une propriété dynamique. |

 **Parameters:**

| Nom | Type | Description |
| --- | --- | --- |
| property | Property | Quelle propriété supprimer |

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
| property | String | Nom de la propriété |

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
| property | String | Nom de la propriété |
| value | Object | La valeur de la propriété |

 **Result:**
Object


---


### findProperty{#findProperty}

| Nom | Description |
| --- | --- |
| findProperty(propertyName) | Recherche la propriété. Elle peut être une propriété dynamique (Créée par CreateDynamicProperty/SetProperty) ou une propriété native (Identifiée par son nom) |

 **Parameters:**

| Nom | Type | Description |
| --- | --- | --- |
| propertyName | String | Nom de la propriété. |

 **Result:**
Property


---




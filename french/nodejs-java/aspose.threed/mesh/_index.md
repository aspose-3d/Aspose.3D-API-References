---
title: Mesh
second_title: Référence d'API Aspose.3D pour Node.js via Java
description: 
type: docs

url: /fr/nodejs-java/aspose.threed/mesh/
---
## Mesh class

Un maillage est composé de nombreux polygones à n côtés.


## Méthodes

### constructor{#constructor}

| Nom | Description |
| --- | --- |
| constructor() | Initializes a new instance of the Mesh class. |

 **Result:**



---


### constructor_overload{#constructor_overload}

| Nom | Description |
| --- | --- |
| constructor_overload(name) | Initializes a new instance of the Mesh class. |

 **Parameters:**

| Nom | Type | Description |
| --- | --- | --- |
| nom | String | Name. |

 **Result:**



---


### getEdges{#getEdges}

| Nom | Description |
| --- | --- |
| getEdges() | Obtient les arêtes du maillage. L'arête est facultative dans le maillage, elle peut donc être vide. |

 **Result:**



---


### getPolygonCount{#getPolygonCount}

| Nom | Description |
| --- | --- |
| getPolygonCount() | Gets the count of polygons The polygon count. |

 **Result:**



---


### getPolygons{#getPolygons}

| Nom | Description |
| --- | --- |
| getPolygons() | Obtient la définition des polygones du maillage |

 **Result:**



---


### getVisible{#getVisible}

| Nom | Description |
| --- | --- |
| getVisible() | Gets or sets if the geometry is visible |

 **Result:**



---


### setVisible{#setVisible}

| Nom | Description |
| --- | --- |
| setVisible(value) | Gets or sets if the geometry is visible |

 **Result:**



---


### getDeformers{#getDeformers}

| Nom | Description |
| --- | --- |
| getDeformers() | Gets all deformers associated with this geometry. The deformers. |

 **Result:**



---


### getControlPoints{#getControlPoints}

| Nom | Description |
| --- | --- |
| getControlPoints() | Obtient tous les points de contrôle |

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


### getVertexElements{#getVertexElements}

| Nom | Description |
| --- | --- |
| getVertexElements() | Obtient tous les éléments de sommet |

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


### getPolygonSize{#getPolygonSize}

| Nom | Description |
| --- | --- |
| getPolygonSize(index) | Obtient le nombre de sommets du polygone spécifié. |

 **Parameters:**

| Nom | Type | Description |
| --- | --- | --- |
| indice | Number | Indice. |

 **Result:**
Number


---


### createPolygon{#createPolygon}

| Nom | Description |
| --- | --- |
| createPolygon(indices, offset, length) | Crée un nouveau polygone avec tous les sommets définis dans indices. Pour créer le polygone sommet par sommet, veuillez utiliser PolygonBuilder. |

 **Parameters:**

| Nom | Type | Description |
| --- | --- | --- |
| indices | Number[] | Tableau des indices du polygone, chaque indice pointe vers un point de contrôle qui forme le polygone. |
| décalage | Number | Le décalage du premier indice du polygone |
| longueur | Number | La longueur des indices |

 **Result:**
Number


---


### createPolygon{#createPolygon}

| Nom | Description |
| --- | --- |
| createPolygon(indices) | Crée un nouveau polygone avec tous les sommets définis dans indices. Pour créer le polygone sommet par sommet, veuillez utiliser PolygonBuilder. |

 **Parameters:**

| Nom | Type | Description |
| --- | --- | --- |
| indices | Number[] | Tableau des indices du polygone, chaque indice pointe vers un point de contrôle qui forme le polygone. |

 **Result:**
Number


---


### createPolygon{#createPolygon}

| Nom | Description |
| --- | --- |
| createPolygon(v1, v2, v3, v4) | Créer un polygone avec 4 sommets(quad) |

 **Parameters:**

| Nom | Type | Description |
| --- | --- | --- |
| v1 | Number | Indice du premier sommet |
| v2 | Number | Indice du deuxième sommet |
| v3 | Number | Indice du troisième sommet |
| v4 | Number | Indice du quatrième sommet |

 **Result:**
Number


---


### createPolygon{#createPolygon}

| Nom | Description |
| --- | --- |
| createPolygon(v1, v2, v3) | Créer un polygone avec 3 sommets(triangle) |

 **Parameters:**

| Nom | Type | Description |
| --- | --- | --- |
| v1 | Number | Indice du premier sommet |
| v2 | Number | Indice du deuxième sommet |
| v3 | Number | Indice du troisième sommet |

 **Result:**
Number


---


### toMesh{#toMesh}

| Nom | Description |
| --- | --- |
| toMesh() | Obtient l'instance Mesh de l'entité actuelle. |

 **Result:**
Mesh


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
| getVertexElementOfUV(textureMapping) | Obtient une instance VertexElementUV avec le type de mappage de texture donné |

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
| createElement(type) | Crée un élément de sommet avec le type spécifié et l'ajoute à la géométrie. Si le type est VertexElementType.UV, un VertexElementUV avec le type de mappage de texture TextureMapping.DIFFUSE sera créé. |

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
| createElement(type, mappingMode, referenceMode) | Crée un élément de sommet avec le type spécifié et l'ajoute à la géométrie. Si le type est VertexElementType.UV, un VertexElementUV avec le type de mappage de texture TextureMapping.DIFFUSE sera créé. |

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


### iterator{#iterator}

| Nom | Description |
| --- | --- |
| iterator() | Réservé à un usage interne. |

 **Result:**
Property


---




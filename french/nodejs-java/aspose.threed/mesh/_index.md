---
title: "Mesh"
second_title: "Référence d'API Aspose.3D pour Node.js via Java"
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
| constructor() | Initialise une nouvelle instance de la classe Mesh. |

 **Result:**



---


### constructor_overload{#constructor_overload}

| Nom | Description |
| --- | --- |
| constructor_overload(name) | Initialise une nouvelle instance de la classe Mesh. |

 **Parameters:**

| Nom | Type | Description |
| --- | --- | --- |
| name | String | Nom. |

 **Result:**



---


### getEdges{#getEdges}

| Nom | Description |
| --- | --- |
| getEdges() | Récupère les arêtes du Mesh. L'arête est facultative dans le mesh, elle peut donc être vide. |

 **Result:**



---


### getPolygonCount{#getPolygonCount}

| Nom | Description |
| --- | --- |
| getPolygonCount() | Récupère le nombre de polygones. Le nombre de polygones. |

 **Result:**



---


### getPolygons{#getPolygons}

| Nom | Description |
| --- | --- |
| getPolygons() | Récupère la définition des polygones du mesh |

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


### getPolygonSize{#getPolygonSize}

| Nom | Description |
| --- | --- |
| getPolygonSize(index) | Obtient le nombre de sommets du polygone spécifié. |

 **Parameters:**

| Nom | Type | Description |
| --- | --- | --- |
| index | Nombre | Indice. |

 **Result:**
Nombre


---


### createPolygon{#createPolygon}

| Nom | Description |
| --- | --- |
| createPolygon(indices, offset, length) | Crée un nouveau polygone avec tous les sommets définis dans indices. Pour créer le polygone sommet par sommet, veuillez utiliser PolygonBuilder. |

 **Parameters:**

| Nom | Type | Description |
| --- | --- | --- |
| indices | Number[] | Tableau des indices du polygone, chaque indice pointe vers un point de contrôle qui forme le polygone. |
| offset | Nombre | Le décalage du premier indice du polygone |
| length | Nombre | La longueur des indices |

 **Result:**
Nombre


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
Nombre


---


### createPolygon{#createPolygon}

| Nom | Description |
| --- | --- |
| createPolygon(v1, v2, v3, v4) | Créer un polygone avec 4 sommets (quad) |

 **Parameters:**

| Nom | Type | Description |
| --- | --- | --- |
| v1 | Nombre | Indice du premier sommet |
| v2 | Nombre | Indice du deuxième sommet |
| v3 | Nombre | Indice du troisième sommet |
| v4 | Nombre | Indice du quatrième sommet |

 **Result:**
Nombre


---


### createPolygon{#createPolygon}

| Nom | Description |
| --- | --- |
| createPolygon(v1, v2, v3) | Créer un polygone avec 3 sommets(triangle) |

 **Parameters:**

| Nom | Type | Description |
| --- | --- | --- |
| v1 | Nombre | Indice du premier sommet |
| v2 | Nombre | Indice du deuxième sommet |
| v3 | Nombre | Indice du troisième sommet |

 **Result:**
Nombre


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


### iterator{#iterator}

| Nom | Description |
| --- | --- |
| iterator() | Réservé à un usage interne. |

 **Result:**
Property


---




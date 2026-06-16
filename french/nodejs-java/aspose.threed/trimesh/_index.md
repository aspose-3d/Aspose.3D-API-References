---
title: "TriMesh"
second_title: "Référence d'API Aspose.3D pour Node.js via Java"
description: 
type: docs

url: /fr/nodejs-java/aspose.threed/trimesh/
---
## TriMesh class

Un TriMesh contient des données brutes pouvant être utilisées directement par le GPU.  Cette classe est un utilitaire pour aider à construire un maillage ne contenant que des données par sommet.


## Méthodes

### constructor{#constructor}

| Nom | Description |
| --- | --- |
| constructor(name, declaration) | Initialiser une instance de TriMesh |

 **Parameters:**

| Nom | Type | Description |
| --- | --- | --- |
| name | String | Le nom de ce TriMesh |
| déclaration | VertexDeclaration | Déclaration du vertex |

 **Result:**



---


### getVertexDeclaration{#getVertexDeclaration}

| Nom | Description |
| --- | --- |
| getVertexDeclaration() | Disposition des vertex du TriMesh. |

 **Result:**



---


### getVerticesCount{#getVerticesCount}

| Nom | Description |
| --- | --- |
| getVerticesCount() | Le nombre de vertex dans ce TriMesh |

 **Result:**



---


### getIndicesCount{#getIndicesCount}

| Nom | Description |
| --- | --- |
| getIndicesCount() | Le nombre d'indices dans ce TriMesh |

 **Result:**



---


### getUnmergedVerticesCount{#getUnmergedVerticesCount}

| Nom | Description |
| --- | --- |
| getUnmergedVerticesCount() | Le nombre de sommets non fusionnés qui ont été passés par beginVertex() et endVertex(). |

 **Result:**



---


### getCapacity{#getCapacity}

| Nom | Description |
| --- | --- |
| getCapacity() | La capacité des sommets pré-alloués. |

 **Result:**



---


### getVerticesSizeInBytes{#getVerticesSizeInBytes}

| Nom | Description |
| --- | --- |
| getVerticesSizeInBytes() | La taille totale de tous les sommets en octets |

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


### fromMesh{#fromMesh}

| Nom | Description |
| --- | --- |
| fromMesh(declaration, mesh) | Créez un TriMesh à partir de l'objet mesh donné avec la disposition de sommets spécifiée. |

 **Parameters:**

| Nom | Type | Description |
| --- | --- | --- |
| déclaration | VertexDeclaration | null |
| maillage | Mesh | null |

 **Result:**
TriMesh


---


### copyFrom{#copyFrom}

| Nom | Description |
| --- | --- |
| copyFrom(input, vd) | Copiez le TriMesh depuis input avec une nouvelle disposition de sommets |

 **Parameters:**

| Nom | Type | Description |
| --- | --- | --- |
| input | TriMesh | Le TriMesh d'entrée pour la copie |
| vd | VertexDeclaration | La nouvelle déclaration de sommet du TriMesh de sortie |

 **Result:**
TriMesh


---


### fromMesh{#fromMesh}

| Nom | Description |
| --- | --- |
| fromMesh(mesh, useFloat) | Créez un TriMesh à partir de l'objet mesh donné, la déclaration de sommet étant basée sur la structure du mesh d'entrée. |

 **Parameters:**

| Nom | Type | Description |
| --- | --- | --- |
| maillage | Mesh | null |
| useFloat | boolean | Utilisez le type float au lieu du type double pour chaque composant d'élément de sommet. |

 **Result:**
TriMesh


---


### beginVertex{#beginVertex}

| Nom | Description |
| --- | --- |
| beginVertex() | Commencez à ajouter un sommet |

 **Result:**
Sommet


---


### endVertex{#endVertex}

| Nom | Description |
| --- | --- |
| endVertex() | Fin de l'ajout de sommet |

 **Result:**
Sommet


---


### verticesToArray{#verticesToArray}

| Nom | Description |
| --- | --- |
| verticesToArray() | Convertir les données des sommets en tableau d'octets |

 **Result:**
byte[]


---


### toString{#toString}

| Nom | Description |
| --- | --- |
| toString() |  |

 **Result:**
String


---


### fromRawData{#fromRawData}

| Nom | Description |
| --- | --- |
| fromRawData(vd, vertices, indices, generateVertexMapping) | Créer un TriMesh à partir de données brutes Le TriMesh retourné ne copiera pas le tableau d'octets d'entrée pour des raisons de performance, les modifications externes du tableau seront reflétées dans cette instance. |

 **Parameters:**

| Nom | Type | Description |
| --- | --- | --- |
| vd | VertexDeclaration | Déclaration de sommet, doit contenir au moins un champ. |
| vertices | byte[] | Les données de sommet d'entrée, la longueur minimale des sommets doit être supérieure ou égale à la taille de la déclaration de sommet |
| indices | Number[] | Les indices de triangle |
| generateVertexMapping | boolean | Générer |

 **Result:**
TriMesh


---


### loadVerticesFromBytes{#loadVerticesFromBytes}

| Nom | Description |
| --- | --- |
| loadVerticesFromBytes(verticesInBytes) | Charger les sommets à partir d'octets, la longueur des octets doit être un multiple entier de la taille du sommet. |

 **Parameters:**

| Nom | Type | Description |
| --- | --- | --- |
| verticesInByte | byte[] | null |

 **Result:**
TriMesh


---


### readVector4{#readVector4}

| Nom | Description |
| --- | --- |
| readVector4(idx, field) | Lire le champ vector4 |

 **Parameters:**

| Nom | Type | Description |
| --- | --- | --- |
| idx | Nombre | L'index du sommet à lire |
| field | VertexField | Le champ avec un type de données Vector4/FVector4 |

 **Result:**
Vector4


---


### readFVector4{#readFVector4}

| Nom | Description |
| --- | --- |
| readFVector4(idx, field) | Lire le champ vector4 |

 **Parameters:**

| Nom | Type | Description |
| --- | --- | --- |
| idx | Nombre | L'index du sommet à lire |
| field | VertexField | Le champ avec un type de données Vector4/FVector4 |

 **Result:**
FVector4


---


### readVector3{#readVector3}

| Nom | Description |
| --- | --- |
| readVector3(idx, field) | Lire le champ vector3 |

 **Parameters:**

| Nom | Type | Description |
| --- | --- | --- |
| idx | Nombre | L'index du sommet à lire |
| field | VertexField | Le champ avec un type de données Vector3/FVector3 |

 **Result:**
Vector3


---


### readFVector3{#readFVector3}

| Nom | Description |
| --- | --- |
| readFVector3(idx, field) | Lire le champ vector3 |

 **Parameters:**

| Nom | Type | Description |
| --- | --- | --- |
| idx | Nombre | L'index du sommet à lire |
| field | VertexField | Le champ avec un type de données Vector3/FVector3 |

 **Result:**
FVector3


---


### readVector2{#readVector2}

| Nom | Description |
| --- | --- |
| readVector2(idx, field) | Lire le champ vector2 |

 **Parameters:**

| Nom | Type | Description |
| --- | --- | --- |
| idx | Nombre | L'index du sommet à lire |
| field | VertexField | Le champ avec un type de données Vector2/FVector2 |

 **Result:**
Vector2


---


### readFVector2{#readFVector2}

| Nom | Description |
| --- | --- |
| readFVector2(idx, field) | Lire le champ vector2 |

 **Parameters:**

| Nom | Type | Description |
| --- | --- | --- |
| idx | Nombre | L'index du sommet à lire |
| field | VertexField | Le champ avec un type de données Vector2/FVector2 |

 **Result:**
FVector2


---


### readDouble{#readDouble}

| Nom | Description |
| --- | --- |
| readDouble(idx, field) | Lire le champ double |

 **Parameters:**

| Nom | Type | Description |
| --- | --- | --- |
| idx | Nombre | L'index du sommet à lire |
| field | VertexField | Le champ avec un type de données compatible float/double |

 **Result:**
Nombre


---


### readFloat{#readFloat}

| Nom | Description |
| --- | --- |
| readFloat(idx, field) | Lire le champ float |

 **Parameters:**

| Nom | Type | Description |
| --- | --- | --- |
| idx | Nombre | L'index du sommet à lire |
| field | VertexField | Le champ avec un type de données compatible float/double |

 **Result:**
Nombre


---


### getBoundingBox{#getBoundingBox}

| Nom | Description |
| --- | --- |
| getBoundingBox() | Obtient la boîte englobante de l'entité actuelle dans son système de coordonnées d'espace objet. |

 **Result:**
Nombre


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




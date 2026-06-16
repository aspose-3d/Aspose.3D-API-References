---
title: "PolygonModifier"
second_title: "Référence d'API Aspose.3D pour Node.js via Java"
description: 
type: docs

url: /fr/nodejs-java/aspose.threed/polygonmodifier/
---
## PolygonModifier class

Utilitaires pour modifier les polygones  @hideconstructor


## Méthodes

### triangulate{#triangulate}

| Nom | Description |
| --- | --- |
| triangulate(scene) | Convertit tous les maillages basés sur des polygones en un maillage complet de triangles |

 **Parameters:**

| Nom | Type | Description |
| --- | --- | --- |
| scène | Scene | La scène à traiter |

 **Result:**



---


### triangulate{#triangulate}

| Nom | Description |
| --- | --- |
| triangulate(mesh) | Convertit un maillage basé sur des polygones en un maillage complet de triangles |

 **Parameters:**

| Nom | Type | Description |
| --- | --- | --- |
| mesh | Mesh | Le maillage d'origine non triangulaire |

 **Result:**
Mesh


---


### mergeMesh{#mergeMesh}

| Nom | Description |
| --- | --- |
| mergeMesh(scene) | Convertit une scène entière en un seul maillage transformé. Les éléments de type Vertex comme les normales/coordonnées de texture ne sont pas encore pris en charge. |

 **Parameters:**

| Nom | Type | Description |
| --- | --- | --- |
| scène | Scene | La scène à fusionner |

 **Result:**
Mesh


---


### mergeMesh{#mergeMesh}

| Nom | Description |
| --- | --- |
| mergeMesh(node) | Convertit un nœud entier en un seul maillage transformé. Les éléments de type Vertex comme les normales/coordonnées de texture ne sont pas encore pris en charge. |

 **Parameters:**

| Nom | Type | Description |
| --- | --- | --- |
| node | Node | Le nœud à fusionner |

 **Result:**
Mesh


---


### scale{#scale}

| Nom | Description |
| --- | --- |
| scale(scene, scale) | Mise à l'échelle de toutes les géométries (Mise à l'échelle des points de contrôle, pas de la matrice de transformation) dans cette scène |

 **Parameters:**

| Nom | Type | Description |
| --- | --- | --- |
| scène | Scene | La scène à mettre à l'échelle |
| scale | Vector3 | Le facteur d'échelle |

 **Result:**
Mesh


---


### scale{#scale}

| Nom | Description |
| --- | --- |
| scale(node, scale) | Mise à l'échelle de toutes les géométries (Mise à l'échelle des points de contrôle, pas de la matrice de transformation) dans ce nœud |

 **Parameters:**

| Nom | Type | Description |
| --- | --- | --- |
| node | Node | Le nœud à mettre à l'échelle |
| scale | Vector3 | Le facteur d'échelle |

 **Result:**
Mesh


---


### generateNormal{#generateNormal}

| Nom | Description |
| --- | --- |
| generateNormal(mesh) | Générer les données normales à partir de la définition du Mesh |

 **Result:**
VertexElementNormal


---


### generateUV{#generateUV}

| Nom | Description |
| --- | --- |
| generateUV(mesh, normals) | Générer les données UV à partir du mesh d'entrée fourni et des données normales spécifiées. |

 **Parameters:**

| Nom | Type | Description |
| --- | --- | --- |
| mesh | Mesh | Le mesh d'entrée |
| normales | VertexElementNormal | Les données normales |

 **Result:**
VertexElementUV


---


### generateUV{#generateUV}

| Nom | Description |
| --- | --- |
| generateUV(mesh) | Générer les données UV à partir du mesh d'entrée fourni |

 **Parameters:**

| Nom | Type | Description |
| --- | --- | --- |
| mesh | Mesh | Le mesh d'entrée |

 **Result:**
VertexElementUV


---


### splitMesh{#splitMesh}

| Nom | Description |
| --- | --- |
| splitMesh(node, policy, createChildNodes, removeOldMesh) | Diviser le mesh en sous-meshes selon VertexElementMaterial. Chaque sous-mesh utilisera un seul matériau. Effectuer la division du mesh sur un nœud. |

 **Parameters:**

| Nom | Type | Description |
| --- | --- | --- |
| nod | Node | null |
| policy | SplitMeshPolicy | SplitMeshPolicy |
| createChildNodes | boolean | Créer des nœuds enfants pour chaque sous-mesh. |
| removeOldMesh | boolean | Supprimer le mesh ancien après la division, si ce paramètre est faux, les meshes anciens et nouveaux coexisteront. |

 **Result:**
VertexElementUV


---


### splitMesh{#splitMesh}

| Nom | Description |
| --- | --- |
| splitMesh(scene, policy, removeOldMesh) | Diviser le mesh en sous-meshes selon VertexElementMaterial. Chaque sous-mesh utilisera un seul matériau. Effectuer la division du mesh sur tous les nœuds de la scène. |

 **Parameters:**

| Nom | Type | Description |
| --- | --- | --- |
| scen | Scene | null |
| policy | SplitMeshPolicy | SplitMeshPolicy |
| removeOldMes | boolean | null |

 **Result:**
VertexElementUV


---


### splitMesh{#splitMesh}

| Nom | Description |
| --- | --- |
| splitMesh(mesh, policy) | Diviser le mesh en sous-meshes selon VertexElementMaterial. Chaque sous-mesh utilisera un seul matériau. Le mesh original ne sera pas modifié. |

 **Result:**
Mesh[]


---


### buildTangentBinormal{#buildTangentBinormal}

| Nom | Description |
| --- | --- |
| buildTangentBinormal(scene) | Cela créera les tangentes et binormales sur tous les meshes de la scène. La normale est requise, si la normale n'existe pas sur le mesh, elle créera également les données normales à partir de la position. L'UV est également requis, le mesh sera ignoré s'aucun UV n'est défini. |

 **Result:**
Mesh[]


---


### buildTangentBinormal{#buildTangentBinormal}

| Nom | Description |
| --- | --- |
| buildTangentBinormal(mesh) | Cela créera les tangentes et binormales sur le maillage. La normale est requise, si la normale n'existe pas sur le maillage, elle créera également les données de normale à partir de la position. Les UV sont également requis, une exception sera levée si aucune UV n'est trouvée. |

 **Result:**
Mesh[]


---




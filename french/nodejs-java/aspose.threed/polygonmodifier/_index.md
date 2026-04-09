---
title: PolygonModifier
second_title: Référence d'API Aspose.3D pour Node.js via Java
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
| triangulate(scene) | Convertir tous les maillages basés sur des polygones en un maillage complet de triangles |

 **Parameters:**

| Nom | Type | Description |
| --- | --- | --- |
| scene | Scène | La scène à traiter |

 **Result:**



---


### triangulate{#triangulate}

| Nom | Description |
| --- | --- |
| triangulate(mesh) | Convertir un maillage basé sur des polygones en un maillage complet de triangles |

 **Parameters:**

| Nom | Type | Description |
| --- | --- | --- |
| mesh | Mesh | Le maillage original non triangulaire |

 **Result:**
Mesh


---


### mergeMesh{#mergeMesh}

| Nom | Description |
| --- | --- |
| mergeMesh(scene) | Convertir une scène entière en un seul maillage transformé. Les éléments de sommet tels que les normales/coordonnées de texture ne sont pas encore pris en charge. |

 **Parameters:**

| Nom | Type | Description |
| --- | --- | --- |
| scene | Scène | La scène à fusionner |

 **Result:**
Mesh


---


### mergeMesh{#mergeMesh}

| Nom | Description |
| --- | --- |
| mergeMesh(node) | Convertir un nœud complet en un seul maillage transformé. Les éléments de sommet tels que les normales/coordonnées de texture ne sont pas encore pris en charge. |

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
| scale(scene, scale) | Mettre à l'échelle toutes les géométries (mettre à l'échelle les points de contrôle, pas la matrice de transformation) dans cette scène |

 **Parameters:**

| Nom | Type | Description |
| --- | --- | --- |
| scene | Scène | La scène à mettre à l'échelle |
| scale | Vector3 | Le facteur d'échelle |

 **Result:**
Mesh


---


### scale{#scale}

| Nom | Description |
| --- | --- |
| scale(node, scale) | Mettre à l'échelle toutes les géométries (mettre à l'échelle les points de contrôle, pas la matrice de transformation) dans ce nœud |

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
| generateNormal(mesh) | Générer les données de normales à partir de la définition du maillage |

 **Result:**
VertexElementNormal


---


### generateUV{#generateUV}

| Nom | Description |
| --- | --- |
| generateUV(mesh, normals) | Générer les données UV à partir du maillage d'entrée fourni et des données de normales spécifiées. |

 **Parameters:**

| Nom | Type | Description |
| --- | --- | --- |
| mesh | Mesh | Le maillage d'entrée |
| normales | VertexElementNormal | Les données de normale |

 **Result:**
VertexElementUV


---


### generateUV{#generateUV}

| Nom | Description |
| --- | --- |
| generateUV(mesh) | Générer les données UV à partir du maillage d'entrée fourni |

 **Parameters:**

| Nom | Type | Description |
| --- | --- | --- |
| mesh | Mesh | Le maillage d'entrée |

 **Result:**
VertexElementUV


---


### splitMesh{#splitMesh}

| Nom | Description |
| --- | --- |
| splitMesh(node, policy, createChildNodes, removeOldMesh) | Diviser le maillage en sous-maillages par VertexElementMaterial. Chaque sous-maillage n'utilisera qu'un seul matériau. Effectuer la division du maillage sur un nœud. |

 **Parameters:**

| Nom | Type | Description |
| --- | --- | --- |
| nod | Node | null |
| politique | SplitMeshPolicy | SplitMeshPolicy |
| createChildNodes | boolean | Créez des nœuds enfants pour chaque sous‑maillage. |
| removeOldMesh | boolean | Supprimer l'ancien maillage après la division, si ce paramètre est faux, les anciens et nouveaux maillages coexisteront. |

 **Result:**
VertexElementUV


---


### splitMesh{#splitMesh}

| Nom | Description |
| --- | --- |
| splitMesh(scene, policy, removeOldMesh) | Diviser le maillage en sous-maillages par VertexElementMaterial. Chaque sous-maillage n'utilisera qu'un seul matériau. Effectuer la division du maillage sur tous les nœuds de la scène. |

 **Parameters:**

| Nom | Type | Description |
| --- | --- | --- |
| scène | Scène | null |
| politique | SplitMeshPolicy | SplitMeshPolicy |
| removeOldMes | boolean | null |

 **Result:**
VertexElementUV


---


### splitMesh{#splitMesh}

| Nom | Description |
| --- | --- |
| splitMesh(mesh, policy) | Diviser le maillage en sous-maillages par VertexElementMaterial. Chaque sous-maillage n'utilisera qu'un seul matériau. Le maillage original ne sera pas modifié. |

 **Result:**
Mesh[]


---


### buildTangentBinormal{#buildTangentBinormal}

| Nom | Description |
| --- | --- |
| buildTangentBinormal(scene) | Cette opération créera les tangentes et binormales sur tous les maillages de la scène. La normale est requise ; si aucune normale n'existe sur le maillage, les données de normale seront également créées à partir de la position. Les UV sont également requis, le maillage sera ignoré s'aucun UV n'est défini. |

 **Result:**
Mesh[]


---


### buildTangentBinormal{#buildTangentBinormal}

| Nom | Description |
| --- | --- |
| buildTangentBinormal(mesh) | Cette opération créera les tangentes et binormales sur le maillage. La normale est requise ; si aucune normale n'existe sur le maillage, les données de normale seront également créées à partir de la position. Les UV sont également requis, une exception sera levée si aucun UV n'est trouvé. |

 **Result:**
Mesh[]


---




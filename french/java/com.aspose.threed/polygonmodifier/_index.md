---
title: "PolygonModifier"
second_title: "Référence d'API Aspose.3D pour Java"
description: "Utilitaires pour modifier les polygones"
type: docs
weight: 134
url: /fr/java/com.aspose.threed/polygonmodifier/
---

**Inheritance:**
java.lang.Object
```
public class PolygonModifier
```

Utilitaires pour modifier les polygones
## Méthodes

| Méthode | Description |
| --- | --- |
| [applyTransform(Node node, Matrix4 transform)](#applyTransform-com.aspose.threed.Node-com.aspose.threed.Matrix4-) | Appliquer la matrice de transformation sur les points de contrôle de toutes les géométries |
| [buildTangentBinormal(Mesh mesh)](#buildTangentBinormal-com.aspose.threed.Mesh-) | Cela créera les tangentes et binormales sur le maillage. La normale est requise, si aucune normale n'existe sur le maillage, elle créera également les données de normale à partir de la position. |
| [buildTangentBinormal(Scene scene)](#buildTangentBinormal-com.aspose.threed.Scene-) | Cela créera les tangentes et binormales sur tous les maillages de la scène. La normale est requise, si aucune normale n'existe sur le maillage, elle créera également les données de normale à partir de la position. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [generateNormal(Mesh mesh)](#generateNormal-com.aspose.threed.Mesh-) | Générer les données de normales à partir de la définition du maillage |
| [generateUV(Mesh mesh)](#generateUV-com.aspose.threed.Mesh-) | Générer les données UV à partir du maillage d'entrée fourni |
| [generateUV(Mesh mesh, VertexElementNormal normals)](#generateUV-com.aspose.threed.Mesh-com.aspose.threed.VertexElementNormal-) | Générer les données UV à partir du maillage d'entrée fourni et des données de normales spécifiées. |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) |  |
| [mergeMesh(Node node)](#mergeMesh-com.aspose.threed.Node-) | Convertir un nœud complet en un seul maillage transformé. Les éléments de sommet tels que les normales/coordonnées de texture ne sont pas encore pris en charge. |
| [mergeMesh(Scene scene)](#mergeMesh-com.aspose.threed.Scene-) | Convertir une scène entière en un seul maillage transformé. Les éléments de sommet tels que les normales/coordonnées de texture ne sont pas encore pris en charge. |
| [mergeMesh(List<Node> nodes)](#mergeMesh-java.util.List-com.aspose.threed.Node--) | Convertir un nœud complet en un seul maillage transformé. Les éléments de sommet tels que les normales/coordonnées de texture ne sont pas encore pris en charge. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [scale(Node node, Vector3 scale)](#scale-com.aspose.threed.Node-com.aspose.threed.Vector3-) | Mettre à l'échelle toutes les géométries (mettre à l'échelle les points de contrôle, pas la matrice de transformation) dans ce nœud |
| [scale(Scene scene, Vector3 scale)](#scale-com.aspose.threed.Scene-com.aspose.threed.Vector3-) | Mettre à l'échelle toutes les géométries (mettre à l'échelle les points de contrôle, pas la matrice de transformation) dans cette scène |
| [splitMesh(Mesh mesh, SplitMeshPolicy policy)](#splitMesh-com.aspose.threed.Mesh-com.aspose.threed.SplitMeshPolicy-) | Diviser le maillage en sous-maillages par [VertexElementMaterial](../../com.aspose.threed/vertexelementmaterial). |
| [splitMesh(Node node, SplitMeshPolicy policy)](#splitMesh-com.aspose.threed.Node-com.aspose.threed.SplitMeshPolicy-) | Diviser le maillage en sous-maillages par [VertexElementMaterial](../../com.aspose.threed/vertexelementmaterial). |
| [splitMesh(Node node, SplitMeshPolicy policy, boolean createChildNodes)](#splitMesh-com.aspose.threed.Node-com.aspose.threed.SplitMeshPolicy-boolean-) | Diviser le maillage en sous-maillages par [VertexElementMaterial](../../com.aspose.threed/vertexelementmaterial). |
| [splitMesh(Node node, SplitMeshPolicy policy, boolean createChildNodes, boolean removeOldMesh)](#splitMesh-com.aspose.threed.Node-com.aspose.threed.SplitMeshPolicy-boolean-boolean-) | Diviser le maillage en sous-maillages par [VertexElementMaterial](../../com.aspose.threed/vertexelementmaterial). |
| [splitMesh(Scene scene, SplitMeshPolicy policy)](#splitMesh-com.aspose.threed.Scene-com.aspose.threed.SplitMeshPolicy-) | Diviser le maillage en sous-maillages par [VertexElementMaterial](../../com.aspose.threed/vertexelementmaterial). |
| [splitMesh(Scene scene, SplitMeshPolicy policy, boolean removeOldMesh)](#splitMesh-com.aspose.threed.Scene-com.aspose.threed.SplitMeshPolicy-boolean-) | Diviser le maillage en sous-maillages par [VertexElementMaterial](../../com.aspose.threed/vertexelementmaterial). |
| [toString()](#toString--) |  |
| [triangulate(Mesh mesh)](#triangulate-com.aspose.threed.Mesh-) | Convertir un maillage basé sur des polygones en un maillage complet de triangles |
| [triangulate(Scene scene)](#triangulate-com.aspose.threed.Scene-) | Convertir tous les maillages basés sur des polygones en un maillage complet de triangles |
| [triangulate(List<Vector4> controlPoints)](#triangulate-java.util.List-com.aspose.threed.Vector4--) | Convertir un polygone en triangles, l'ordre du polygone est défini par les `controlPoints` |
| [triangulate(List<Vector4> controlPoints, int[] polygon)](#triangulate-java.util.List-com.aspose.threed.Vector4--int---) | Convertir un polygone en triangles |
| [triangulate(List<Vector4> controlPoints, List<int[]> polygons)](#triangulate-java.util.List-com.aspose.threed.Vector4--java.util.List-int----) | Convertir un maillage basé sur des polygones en triangles |
| [triangulate(List<Vector4> controlPoints, List<int[]> polygons, boolean generateNormals, Vector3[][] nor_out)](#triangulate-java.util.List-com.aspose.threed.Vector4--java.util.List-int----boolean-com.aspose.threed.Vector3-----) | Convertir un maillage basé sur des polygones en un maillage complet de triangles |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### applyTransform(Node node, Matrix4 transform) {#applyTransform-com.aspose.threed.Node-com.aspose.threed.Matrix4-}
```
public static void applyTransform(Node node, Matrix4 transform)
```


Appliquer la matrice de transformation sur les points de contrôle de toutes les géométries

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| node | [Node](../../com.aspose.threed/node) | Quelles géométries du nœud seront appliquées avec la transformation donnée |
| transform | [Matrix4](../../com.aspose.threed/matrix4) | La matrice de transformation qui sera appliquée aux points de contrôle. |

### buildTangentBinormal(Mesh mesh) {#buildTangentBinormal-com.aspose.threed.Mesh-}
```
public static void buildTangentBinormal(Mesh mesh)
```


Cette opération créera les tangentes et binormales sur le maillage. La normale est requise ; si aucune normale n'existe sur le maillage, les données de normale seront également créées à partir de la position. Les UV sont également requis, une exception sera levée si aucun UV n'est trouvé.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| mesh | [Mesh](../../com.aspose.threed/mesh) |  |

### buildTangentBinormal(Scene scene) {#buildTangentBinormal-com.aspose.threed.Scene-}
```
public static void buildTangentBinormal(Scene scene)
```


Cette opération créera les tangentes et binormales sur tous les maillages de la scène. La normale est requise ; si aucune normale n'existe sur le maillage, les données de normale seront également créées à partir de la position. Les UV sont également requis, le maillage sera ignoré s'aucun UV n'est défini.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| scene | [Scene](../../com.aspose.threed/scene) |  |

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### generateNormal(Mesh mesh) {#generateNormal-com.aspose.threed.Mesh-}
```
public static VertexElementNormal generateNormal(Mesh mesh)
```


Générer les données de normales à partir de la définition du maillage

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| mesh | [Mesh](../../com.aspose.threed/mesh) |  |

**Returns:**
[VertexElementNormal](../../com.aspose.threed/vertexelementnormal) - [VertexElementNormal](../../com.aspose.threed/vertexelementnormal) instance with normal data.
### generateUV(Mesh mesh) {#generateUV-com.aspose.threed.Mesh-}
```
public static VertexElementUV generateUV(Mesh mesh)
```


Générer les données UV à partir du maillage d'entrée fourni

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| mesh | [Mesh](../../com.aspose.threed/mesh) | Le maillage d'entrée |

**Returns:**
[VertexElementUV](../../com.aspose.threed/vertexelementuv) - Generated UV data
### generateUV(Mesh mesh, VertexElementNormal normals) {#generateUV-com.aspose.threed.Mesh-com.aspose.threed.VertexElementNormal-}
```
public static VertexElementUV generateUV(Mesh mesh, VertexElementNormal normals)
```


Générer les données UV à partir du maillage d'entrée fourni et des données de normales spécifiées.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| mesh | [Mesh](../../com.aspose.threed/mesh) | Le maillage d'entrée |
| normals | [VertexElementNormal](../../com.aspose.threed/vertexelementnormal) | Les données de normale |

**Returns:**
[VertexElementUV](../../com.aspose.threed/vertexelementuv) - Generated UV data
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### mergeMesh(Node node) {#mergeMesh-com.aspose.threed.Node-}
```
public static Mesh mergeMesh(Node node)
```


Convertir un nœud complet en un seul maillage transformé. Les éléments de sommet tels que les normales/coordonnées de texture ne sont pas encore pris en charge.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| node | [Node](../../com.aspose.threed/node) | Le nœud à fusionner |

**Returns:**
[Mesh](../../com.aspose.threed/mesh) - Merged mesh **Example:** The following code shows how to merge all objects from nodes into a single mesh.

```
//Input file may contains multiple objects
          var scene = Scene.fromFile("input.fbx");
          //now merge them into a single mesh
          Mesh merged = PolygonModifier.mergeMesh(scene.getRootNode());
          //then we save it to a file with only one mesh
          var newScene = new Scene(merged);
          newScene.save("test.obj");
```
### mergeMesh(Scene scene) {#mergeMesh-com.aspose.threed.Scene-}
```
public static Mesh mergeMesh(Scene scene)
```


Convertir une scène entière en un seul maillage transformé. Les éléments de sommet tels que les normales/coordonnées de texture ne sont pas encore pris en charge.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| scene | [Scene](../../com.aspose.threed/scene) | La scène à fusionner |

**Returns:**
[Mesh](../../com.aspose.threed/mesh) - The merged mesh **Example:** The following code shows how to merge all objects from a scene into a single mesh.

```
//Input file may contains multiple objects
         var scene = Scene.fromFile("input.fbx");
         //now merge them into a single mesh
         Mesh merged = PolygonModifier.mergeMesh(scene);
         //then we save it to a file with only one mesh
         var newScene = new Scene(merged);
         newScene.save("test.obj");
```
### mergeMesh(List<Node> nodes) {#mergeMesh-java.util.List-com.aspose.threed.Node--}
```
public static Mesh mergeMesh(List<Node> nodes)
```


Convertir un nœud complet en un seul maillage transformé. Les éléments de sommet tels que les normales/coordonnées de texture ne sont pas encore pris en charge.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| nœuds | java.util.List<com.aspose.threed.Node> | Les nœuds à fusionner |

**Returns:**
[Mesh](../../com.aspose.threed/mesh) - Merged mesh **Example:** The following code shows how to merge all objects from nodes into a single mesh.

```
//Input file may contains multiple objects
         var scene = Scene.fromFile("input.fbx");
         //now merge them into a single mesh
         Mesh merged = PolygonModifier.mergeMesh(scene.getRootNode().getChildNodes());
         //then we save it to a file with only one mesh
         var newScene = new Scene(merged);
         newScene.save("test.obj");
```
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### scale(Node node, Vector3 scale) {#scale-com.aspose.threed.Node-com.aspose.threed.Vector3-}
```
public static void scale(Node node, Vector3 scale)
```


Mettre à l'échelle toutes les géométries (mettre à l'échelle les points de contrôle, pas la matrice de transformation) dans ce nœud

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| node | [Node](../../com.aspose.threed/node) | Le nœud à mettre à l'échelle |
|  | scale | [Vector3](../../com.aspose.threed/vector3) | Le facteur d'échelle **Example:** Le code suivant montre comment mettre à l'échelle toutes les géométries de la scène par 10 fois. |

```
//Load a test file for scaling
 		 var scene = Scene.fromFile("input.fbx");
 		 //scale all geometries 10 times.
 		 PolygonModifier.scale(scene.getRootNode(), new Vector3(10, 10, 10));
 		 scene.save("test.obj");
``` |

### scale(Scene scene, Vector3 scale) {#scale-com.aspose.threed.Scene-com.aspose.threed.Vector3-}
```
public static Scene scale(Scene scene, Vector3 scale)
```


Mettre à l'échelle toutes les géométries (mettre à l'échelle les points de contrôle, pas la matrice de transformation) dans cette scène

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| scene | [Scene](../../com.aspose.threed/scene) | La scène à mettre à l'échelle |
|  | scale | [Vector3](../../com.aspose.threed/vector3) | Le facteur d'échelle **Example:** Le code suivant montre comment mettre à l'échelle toutes les géométries de la scène par 10 fois. |

```
//Load a test file for scaling
 		var scene = Scene.fromFile("input.fbx");
 		//scale all geometries 10 times.
 		PolygonModifier.scale(scene, new Vector3(10, 10, 10));
 		scene.save("test.obj");
``` |

**Returns:**
[Scene](../../com.aspose.threed/scene)
### splitMesh(Mesh mesh, SplitMeshPolicy policy) {#splitMesh-com.aspose.threed.Mesh-com.aspose.threed.SplitMeshPolicy-}
```
public static Mesh[] splitMesh(Mesh mesh, SplitMeshPolicy policy)
```


Diviser le maillage en sous-maillages par [VertexElementMaterial](../../com.aspose.threed/vertexelementmaterial). Chaque sous-maillage n'utilisera qu'un seul matériau. Le maillage original ne sera pas modifié.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| mesh | [Mesh](../../com.aspose.threed/mesh) |  |
| policy | [SplitMeshPolicy](../../com.aspose.threed/splitmeshpolicy) |  |

**Returns:**
com.aspose.threed.Mesh[] - Nouveaux maillages découpés **Exemple:** Le code suivant montre comment diviser une boîte en sous‑maillages en utilisant les indices de matériau.

```
// Create a mesh of box(A box is composed by 6 planes)
 			Mesh box = (new Box()).toMesh();
 			// Create a material element on this mesh
 			VertexElementMaterial mat = (VertexElementMaterial)box.createElement(VertexElementType.MATERIAL, MappingMode.POLYGON, ReferenceMode.INDEX);
 			// And specify different material index for each plane
 			mat.setIndices(new int[] { 0, 1, 2, 3, 4, 5 });
 			// Now split it into 6 sub meshes, we specified 6 different materials on each plane, each plane will become a sub mesh.
 			// We used the CloneData policy, each plane will has the same control point information or control point-based vertex element information.
 			Mesh[] planes = PolygonModifier.splitMesh(box, SplitMeshPolicy.CLONE_DATA);
 
 			// Now split it into 2 sub meshes, first mesh will contains 0/1/2 planes, and second mesh will contains the 3/4/5th planes.
 			mat.setIndices(new int[] { 0, 0, 0, 1, 1, 1 });
 			// We used the CompactData policy, each plane will has its own control point information or control point-based vertex element information.
 			planes = PolygonModifier.splitMesh(box, SplitMeshPolicy.COMPACT_DATA);
```
### splitMesh(Node node, SplitMeshPolicy policy) {#splitMesh-com.aspose.threed.Node-com.aspose.threed.SplitMeshPolicy-}
```
public static void splitMesh(Node node, SplitMeshPolicy policy)
```


Divisez le maillage en sous‑maillages par [VertexElementMaterial](../../com.aspose.threed/vertexelementmaterial). Chaque sous‑maillage n’utilisera qu’un seul matériau. Effectuez le découpage du maillage sur un nœud **Exemple:** Le code suivant montre comment diviser une boîte en sous‑maillages en utilisant les indices de matériau.

```
// Create a mesh of box(A box is composed by 6 planes)
 			Mesh box = (new Box()).toMesh();
 			// Create a material element on this mesh
 			VertexElementMaterial mat = (VertexElementMaterial)box.createElement(VertexElementType.MATERIAL, MappingMode.POLYGON, ReferenceMode.INDEX);
 			// And specify different material index for each plane
 			mat.setIndices(new int[] { 0, 1, 2, 3, 4, 5 });
 			// Now split it into 6 sub meshes, we specified 6 different materials on each plane, each plane will become a sub mesh.
 			// We used the CloneData policy, each plane will has the same control point information or control point-based vertex element information.
 			Mesh[] planes = PolygonModifier.splitMesh(box, SplitMeshPolicy.CLONE_DATA);
 
 			// Now split it into 2 sub meshes, first mesh will contains 0/1/2 planes, and second mesh will contains the 3/4/5th planes.
 			mat.setIndices(new int[] { 0, 0, 0, 1, 1, 1 });
 			// We used the CompactData policy, each plane will has its own control point information or control point-based vertex element information.
 			planes = PolygonModifier.splitMesh(box, SplitMeshPolicy.COMPACT_DATA);
```

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| node | [Node](../../com.aspose.threed/node) |  |
| policy | [SplitMeshPolicy](../../com.aspose.threed/splitmeshpolicy) |  |

### splitMesh(Node node, SplitMeshPolicy policy, boolean createChildNodes) {#splitMesh-com.aspose.threed.Node-com.aspose.threed.SplitMeshPolicy-boolean-}
```
public static void splitMesh(Node node, SplitMeshPolicy policy, boolean createChildNodes)
```


Divisez le maillage en sous‑maillages par [VertexElementMaterial](../../com.aspose.threed/vertexelementmaterial). Chaque sous‑maillage n’utilisera qu’un seul matériau. Effectuez le découpage du maillage sur un nœud

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| node | [Node](../../com.aspose.threed/node) |  |
| policy | [SplitMeshPolicy](../../com.aspose.threed/splitmeshpolicy) |  |
|  | createChildNodes | boolean | Créez des nœuds enfants pour chaque sous‑maillage. **Exemple:** Le code suivant montre comment diviser une boîte en sous‑maillages en utilisant les indices de matériau. |

```
// Create a mesh of box(A box is composed by 6 planes)
 			Mesh box = (new Box()).toMesh();
 			// Create a material element on this mesh
 			VertexElementMaterial mat = (VertexElementMaterial)box.createElement(VertexElementType.MATERIAL, MappingMode.POLYGON, ReferenceMode.INDEX);
 			// And specify different material index for each plane
 			mat.setIndices(new int[] { 0, 1, 2, 3, 4, 5 });
 			// Now split it into 6 sub meshes, we specified 6 different materials on each plane, each plane will become a sub mesh.
 			// We used the CloneData policy, each plane will has the same control point information or control point-based vertex element information.
 			Mesh[] planes = PolygonModifier.splitMesh(box, SplitMeshPolicy.CLONE_DATA);
 
 			// Now split it into 2 sub meshes, first mesh will contains 0/1/2 planes, and second mesh will contains the 3/4/5th planes.
 			mat.setIndices(new int[] { 0, 0, 0, 1, 1, 1 });
 			// We used the CompactData policy, each plane will has its own control point information or control point-based vertex element information.
 			planes = PolygonModifier.splitMesh(box, SplitMeshPolicy.COMPACT_DATA);
``` |

### splitMesh(Node node, SplitMeshPolicy policy, boolean createChildNodes, boolean removeOldMesh) {#splitMesh-com.aspose.threed.Node-com.aspose.threed.SplitMeshPolicy-boolean-boolean-}
```
public static void splitMesh(Node node, SplitMeshPolicy policy, boolean createChildNodes, boolean removeOldMesh)
```


Divisez le maillage en sous‑maillages par [VertexElementMaterial](../../com.aspose.threed/vertexelementmaterial). Chaque sous‑maillage n’utilisera qu’un seul matériau. Effectuez le découpage du maillage sur un nœud

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| node | [Node](../../com.aspose.threed/node) |  |
| policy | [SplitMeshPolicy](../../com.aspose.threed/splitmeshpolicy) |  |
| createChildNodes | boolean | Créez des nœuds enfants pour chaque sous‑maillage. |
|  | removeOldMesh | boolean | Supprimez l’ancien maillage après le découpage, si ce paramètre est faux, les anciens et nouveaux maillages coexisteront. **Exemple:** Le code suivant montre comment diviser une boîte en sous‑maillages en utilisant les indices de matériau. |

```
// Create a mesh of box(A box is composed by 6 planes)
 			Mesh box = (new Box()).toMesh();
 			// Create a material element on this mesh
 			VertexElementMaterial mat = (VertexElementMaterial)box.createElement(VertexElementType.MATERIAL, MappingMode.POLYGON, ReferenceMode.INDEX);
 			// And specify different material index for each plane
 			mat.setIndices(new int[] { 0, 1, 2, 3, 4, 5 });
 			// Now split it into 6 sub meshes, we specified 6 different materials on each plane, each plane will become a sub mesh.
 			// We used the CloneData policy, each plane will has the same control point information or control point-based vertex element information.
 			Mesh[] planes = PolygonModifier.splitMesh(box, SplitMeshPolicy.CLONE_DATA);
 
 			// Now split it into 2 sub meshes, first mesh will contains 0/1/2 planes, and second mesh will contains the 3/4/5th planes.
 			mat.setIndices(new int[] { 0, 0, 0, 1, 1, 1 });
 			// We used the CompactData policy, each plane will has its own control point information or control point-based vertex element information.
 			planes = PolygonModifier.splitMesh(box, SplitMeshPolicy.COMPACT_DATA);
``` |

### splitMesh(Scene scene, SplitMeshPolicy policy) {#splitMesh-com.aspose.threed.Scene-com.aspose.threed.SplitMeshPolicy-}
```
public static void splitMesh(Scene scene, SplitMeshPolicy policy)
```


Divisez le maillage en sous‑maillages par [VertexElementMaterial](../../com.aspose.threed/vertexelementmaterial). Chaque sous‑maillage n’utilisera qu’un seul matériau. Effectuez le découpage du maillage sur tous les nœuds de la scène. **Exemple:** Le code suivant montre comment diviser une boîte en sous‑maillages en utilisant les indices de matériau.

```
// Create a mesh of box(A box is composed by 6 planes)
 			Mesh box = (new Box()).toMesh();
 			// Create a material element on this mesh
 			VertexElementMaterial mat = (VertexElementMaterial)box.createElement(VertexElementType.MATERIAL, MappingMode.POLYGON, ReferenceMode.INDEX);
 			// And specify different material index for each plane
 			mat.setIndices(new int[] { 0, 1, 2, 3, 4, 5 });
 			// Now split it into 6 sub meshes, we specified 6 different materials on each plane, each plane will become a sub mesh.
 			// We used the CloneData policy, each plane will has the same control point information or control point-based vertex element information.
 			Mesh[] planes = PolygonModifier.splitMesh(box, SplitMeshPolicy.CLONE_DATA);
 
 			// Now split it into 2 sub meshes, first mesh will contains 0/1/2 planes, and second mesh will contains the 3/4/5th planes.
 			mat.setIndices(new int[] { 0, 0, 0, 1, 1, 1 });
 			// We used the CompactData policy, each plane will has its own control point information or control point-based vertex element information.
 			planes = PolygonModifier.splitMesh(box, SplitMeshPolicy.COMPACT_DATA);
```

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| scene | [Scene](../../com.aspose.threed/scene) |  |
| policy | [SplitMeshPolicy](../../com.aspose.threed/splitmeshpolicy) |  |

### splitMesh(Scene scene, SplitMeshPolicy policy, boolean removeOldMesh) {#splitMesh-com.aspose.threed.Scene-com.aspose.threed.SplitMeshPolicy-boolean-}
```
public static void splitMesh(Scene scene, SplitMeshPolicy policy, boolean removeOldMesh)
```


Divisez le maillage en sous‑maillages par [VertexElementMaterial](../../com.aspose.threed/vertexelementmaterial). Chaque sous‑maillage n’utilisera qu’un seul matériau. Effectuez le découpage du maillage sur tous les nœuds de la scène. **Exemple:** Le code suivant montre comment diviser une boîte en sous‑maillages en utilisant les indices de matériau.

```
// Create a mesh of box(A box is composed by 6 planes)
 			Mesh box = (new Box()).toMesh();
 			// Create a material element on this mesh
 			VertexElementMaterial mat = (VertexElementMaterial)box.createElement(VertexElementType.MATERIAL, MappingMode.POLYGON, ReferenceMode.INDEX);
 			// And specify different material index for each plane
 			mat.setIndices(new int[] { 0, 1, 2, 3, 4, 5 });
 			// Now split it into 6 sub meshes, we specified 6 different materials on each plane, each plane will become a sub mesh.
 			// We used the CloneData policy, each plane will has the same control point information or control point-based vertex element information.
 			Mesh[] planes = PolygonModifier.splitMesh(box, SplitMeshPolicy.CLONE_DATA);
 
 			// Now split it into 2 sub meshes, first mesh will contains 0/1/2 planes, and second mesh will contains the 3/4/5th planes.
 			mat.setIndices(new int[] { 0, 0, 0, 1, 1, 1 });
 			// We used the CompactData policy, each plane will has its own control point information or control point-based vertex element information.
 			planes = PolygonModifier.splitMesh(box, SplitMeshPolicy.COMPACT_DATA);
```

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| scene | [Scene](../../com.aspose.threed/scene) |  |
| policy | [SplitMeshPolicy](../../com.aspose.threed/splitmeshpolicy) |  |
| removeOldMesh | boolean |  |

### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### triangulate(Mesh mesh) {#triangulate-com.aspose.threed.Mesh-}
```
public static Mesh triangulate(Mesh mesh)
```


Convertir un maillage basé sur des polygones en un maillage complet de triangles

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| mesh | [Mesh](../../com.aspose.threed/mesh) | Le maillage original non triangulaire |

**Returns:**
[Mesh](../../com.aspose.threed/mesh) - The generated new triangle mesh **Example:** The following code shows how to merge all objects from a scene into a single mesh.

```
var mesh = new Cylinder().toMesh();
 
 		//Triangulate this quadrangle-based mesh to triangle-based
 		mesh = PolygonModifier.triangulate(mesh);
 
 		var scene = new Scene(mesh);
 
         scene.save("test.obj");
```
### triangulate(Scene scene) {#triangulate-com.aspose.threed.Scene-}
```
public static void triangulate(Scene scene)
```


Convertir tous les maillages basés sur des polygones en un maillage complet de triangles

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | scene | [Scene](../../com.aspose.threed/scene) | La scène à traiter **Exemple:** Le code suivant montre comment fusionner tous les objets d’une scène en un seul maillage. |

```
var mesh = new Cylinder().toMesh();
 
 		//Triangulate this quadrangle-based mesh to triangle-based
 		mesh = PolygonModifier.triangulate(mesh);
 
 		var scene = new Scene(mesh);
 
         scene.save("test.obj");
``` |

### triangulate(List<Vector4> controlPoints) {#triangulate-java.util.List-com.aspose.threed.Vector4--}
```
public static int[][] triangulate(List<Vector4> controlPoints)
```


Convertir un polygone en triangles, l'ordre du polygone est défini par les `controlPoints`

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| controlPoints | java.util.List<com.aspose.threed.Vector4> | Points de contrôle du maillage |

**Returns:**
int[][] - Un ensemble de triangles **Exemple:** Le code suivant montre comment fusionner tous les objets d’une scène en un seul maillage.

```
var mesh = new Cylinder().toMesh();
 
 		//Triangulate this quadrangle-based mesh to triangle-based
 		mesh = PolygonModifier.triangulate(mesh);
 
 		var scene = new Scene(mesh);
 
         scene.save("test.obj");
```
### triangulate(List<Vector4> controlPoints, int[] polygon) {#triangulate-java.util.List-com.aspose.threed.Vector4--int---}
```
public static int[][] triangulate(List<Vector4> controlPoints, int[] polygon)
```


Convertir un polygone en triangles

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| controlPoints | java.util.List<com.aspose.threed.Vector4> | Points de contrôle du maillage |
| polygon | int[] | Face du polygone |

**Returns:**
int[][] - Un ensemble de triangles **Exemple:** Le code suivant montre comment fusionner tous les objets d’une scène en un seul maillage.

```
var mesh = new Cylinder().toMesh();
 
 		//Triangulate this quadrangle-based mesh to triangle-based
 		mesh = PolygonModifier.triangulate(mesh);
 
 		var scene = new Scene(mesh);
 
         scene.save("test.obj");
```
### triangulate(List<Vector4> controlPoints, List<int[]> polygons) {#triangulate-java.util.List-com.aspose.threed.Vector4--java.util.List-int----}
```
public static int[][] triangulate(List<Vector4> controlPoints, List<int[]> polygons)
```


Convertir un maillage basé sur des polygones en triangles

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| controlPoints | java.util.List<com.aspose.threed.Vector4> | Points de contrôle du maillage |
| polygons | java.util.List<int[]> | Faces de polygone |

**Returns:**
int[][] - Un ensemble de triangles **Exemple:** Le code suivant montre comment fusionner tous les objets d’une scène en un seul maillage.

```
var mesh = new Cylinder().toMesh();
 
 		//Triangulate this quadrangle-based mesh to triangle-based
 		mesh = PolygonModifier.triangulate(mesh);
 
 		var scene = new Scene(mesh);
 
         scene.save("test.obj");
```
### triangulate(List<Vector4> controlPoints, List<int[]> polygons, boolean generateNormals, Vector3[][] nor_out) {#triangulate-java.util.List-com.aspose.threed.Vector4--java.util.List-int----boolean-com.aspose.threed.Vector3-----}
```
public static int[][] triangulate(List<Vector4> controlPoints, List<int[]> polygons, boolean generateNormals, Vector3[][] nor_out)
```


Convertir un maillage basé sur des polygones en un maillage complet de triangles

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| controlPoints | java.util.List<com.aspose.threed.Vector4> | Points de contrôle du maillage |
| polygons | java.util.List<int[]> | Faces de polygone |
| generateNormals | boolean | Générer les normales |
| nor_out | [Vector3\[\]](../../com.aspose.threed/vector3) | Normale générée par point de contrôle |

**Returns:**
int[][] - Un ensemble de triangles **Exemple:** Le code suivant montre comment fusionner tous les objets d’une scène en un seul maillage.

```
var mesh = new Cylinder().toMesh();
 
 		//Triangulate this quadrangle-based mesh to triangle-based
 		mesh = PolygonModifier.triangulate(mesh);
 
 		var scene = new Scene(mesh);
 
         scene.save("test.obj");
```
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final void wait(long arg0)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |


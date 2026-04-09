---
title: PolygonModifier
second_title: Aspose.3D for Java API-referentie
description: Hulpmiddelen om polygonen te wijzigen
type: docs
weight: 134
url: /nl/java/com.aspose.threed/polygonmodifier/
---

**Inheritance:**
java.lang.Object
```
public class PolygonModifier
```

Hulpmiddelen om polygonen te wijzigen
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [applyTransform(Node node, Matrix4 transform)](#applyTransform-com.aspose.threed.Node-com.aspose.threed.Matrix4-) | Pas transformatie-matrix toe op controlepunten van alle geometrieën |
| [buildTangentBinormal(Mesh mesh)](#buildTangentBinormal-com.aspose.threed.Mesh-) | Dit maakt tangent en binormaal aan op het mesh. Normaal is vereist; als normaal niet bestaat op het mesh, wordt de normale data ook vanuit de positie aangemaakt. |
| [buildTangentBinormal(Scene scene)](#buildTangentBinormal-com.aspose.threed.Scene-) | Dit maakt tangent en binormaal aan op alle meshes van de scène. Normaal is vereist; als normaal niet bestaat op het mesh, wordt de normale data ook vanuit de positie aangemaakt. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [generateNormal(Mesh mesh)](#generateNormal-com.aspose.threed.Mesh-) | Genereer normale data vanuit Mesh-definitie |
| [generateUV(Mesh mesh)](#generateUV-com.aspose.threed.Mesh-) | Genereer UV-data vanuit het opgegeven invoer‑mesh |
| [generateUV(Mesh mesh, VertexElementNormal normals)](#generateUV-com.aspose.threed.Mesh-com.aspose.threed.VertexElementNormal-) | Genereer UV-data vanuit het opgegeven invoer‑mesh en gespecificeerde normale data. |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) |  |
| [mergeMesh(Node node)](#mergeMesh-com.aspose.threed.Node-) | Converteer een heel knooppunt naar een enkele getransformeerde mesh Vertex-elementen zoals normale/textuurcoördinaten worden nog niet ondersteund |
| [mergeMesh(Scene scene)](#mergeMesh-com.aspose.threed.Scene-) | Converteer een hele scène naar een enkele getransformeerde mesh Vertex-elementen zoals normale/textuurcoördinaten worden nog niet ondersteund |
| [mergeMesh(List<Node> nodes)](#mergeMesh-java.util.List-com.aspose.threed.Node--) | Converteer een heel knooppunt naar een enkele getransformeerde mesh Vertex-elementen zoals normale/textuurcoördinaten worden nog niet ondersteund |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [scale(Node node, Vector3 scale)](#scale-com.aspose.threed.Node-com.aspose.threed.Vector3-) | Schaal alle geometrieën (Schaal de controlepunten, niet de transformatie-matrix) in dit knooppunt |
| [scale(Scene scene, Vector3 scale)](#scale-com.aspose.threed.Scene-com.aspose.threed.Vector3-) | Schaal alle geometrieën (Schaal de controlepunten, niet de transformatie-matrix) in deze scène |
| [splitMesh(Mesh mesh, SplitMeshPolicy policy)](#splitMesh-com.aspose.threed.Mesh-com.aspose.threed.SplitMeshPolicy-) | Splits mesh in sub-meshes via [VertexElementMaterial](../../com.aspose.threed/vertexelementmaterial). |
| [splitMesh(Node node, SplitMeshPolicy policy)](#splitMesh-com.aspose.threed.Node-com.aspose.threed.SplitMeshPolicy-) | Splits mesh in sub-meshes via [VertexElementMaterial](../../com.aspose.threed/vertexelementmaterial). |
| [splitMesh(Node node, SplitMeshPolicy policy, boolean createChildNodes)](#splitMesh-com.aspose.threed.Node-com.aspose.threed.SplitMeshPolicy-boolean-) | Splits mesh in sub-meshes via [VertexElementMaterial](../../com.aspose.threed/vertexelementmaterial). |
| [splitMesh(Node node, SplitMeshPolicy policy, boolean createChildNodes, boolean removeOldMesh)](#splitMesh-com.aspose.threed.Node-com.aspose.threed.SplitMeshPolicy-boolean-boolean-) | Splits mesh in sub-meshes via [VertexElementMaterial](../../com.aspose.threed/vertexelementmaterial). |
| [splitMesh(Scene scene, SplitMeshPolicy policy)](#splitMesh-com.aspose.threed.Scene-com.aspose.threed.SplitMeshPolicy-) | Splits mesh in sub-meshes via [VertexElementMaterial](../../com.aspose.threed/vertexelementmaterial). |
| [splitMesh(Scene scene, SplitMeshPolicy policy, boolean removeOldMesh)](#splitMesh-com.aspose.threed.Scene-com.aspose.threed.SplitMeshPolicy-boolean-) | Splits mesh in sub-meshes via [VertexElementMaterial](../../com.aspose.threed/vertexelementmaterial). |
| [toString()](#toString--) |  |
| [triangulate(Mesh mesh)](#triangulate-com.aspose.threed.Mesh-) | Converteer een op polygonen gebaseerd mesh naar een volledig driehoekmesh |
| [triangulate(Scene scene)](#triangulate-com.aspose.threed.Scene-) | Converteer alle op polygonen gebaseerde meshes naar een volledig driehoekmesh |
| [triangulate(List<Vector4> controlPoints)](#triangulate-java.util.List-com.aspose.threed.Vector4--) | Converteer een polygoon naar driehoeken, de volgorde van de polygoon wordt gedefinieerd door de `controlPoints` |
| [triangulate(List<Vector4> controlPoints, int[] polygon)](#triangulate-java.util.List-com.aspose.threed.Vector4--int---) | Converteer een polygoon naar driehoeken |
| [triangulate(List<Vector4> controlPoints, List<int[]> polygons)](#triangulate-java.util.List-com.aspose.threed.Vector4--java.util.List-int----) | Converteer een op polygoon gebaseerd mesh naar driehoeken |
| [triangulate(List<Vector4> controlPoints, List<int[]> polygons, boolean generateNormals, Vector3[][] nor_out)](#triangulate-java.util.List-com.aspose.threed.Vector4--java.util.List-int----boolean-com.aspose.threed.Vector3-----) | Converteer een op polygonen gebaseerd mesh naar een volledig driehoekmesh |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### applyTransform(Node node, Matrix4 transform) {#applyTransform-com.aspose.threed.Node-com.aspose.threed.Matrix4-}
```
public static void applyTransform(Node node, Matrix4 transform)
```


Pas transformatie-matrix toe op controlepunten van alle geometrieën

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| node | [Node](../../com.aspose.threed/node) | Welke geometrieën van het knooppunt worden toegepast met de opgegeven transformatie |
| transform | [Matrix4](../../com.aspose.threed/matrix4) | De transformatie-matrix die wordt toegepast op controlepunten. |

### buildTangentBinormal(Mesh mesh) {#buildTangentBinormal-com.aspose.threed.Mesh-}
```
public static void buildTangentBinormal(Mesh mesh)
```


Dit maakt tangent en binormaal aan op de mesh. Normal is vereist; als normal niet bestaat op de mesh, wordt de normaldata ook aangemaakt vanuit positie. UV is ook vereist; er wordt een uitzondering opgegooid als er geen UV wordt gevonden.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| mesh | [Mesh](../../com.aspose.threed/mesh) |  |

### buildTangentBinormal(Scene scene) {#buildTangentBinormal-com.aspose.threed.Scene-}
```
public static void buildTangentBinormal(Scene scene)
```


Dit maakt tangent en binormaal aan op alle meshes van de scène. Normal is vereist; als normal niet bestaat op de mesh, wordt de normaldata ook aangemaakt vanuit positie. UV is ook vereist; de mesh wordt genegeerd als er geen UV is gedefinieerd.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| scene | [Scene](../../com.aspose.threed/scene) |  |

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### generateNormal(Mesh mesh) {#generateNormal-com.aspose.threed.Mesh-}
```
public static VertexElementNormal generateNormal(Mesh mesh)
```


Genereer normale data vanuit Mesh-definitie

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| mesh | [Mesh](../../com.aspose.threed/mesh) |  |

**Returns:**
[VertexElementNormal](../../com.aspose.threed/vertexelementnormal) - [VertexElementNormal](../../com.aspose.threed/vertexelementnormal) instance with normal data.
### generateUV(Mesh mesh) {#generateUV-com.aspose.threed.Mesh-}
```
public static VertexElementUV generateUV(Mesh mesh)
```


Genereer UV-data vanuit het opgegeven invoer‑mesh

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| mesh | [Mesh](../../com.aspose.threed/mesh) | De invoer‑mesh |

**Returns:**
[VertexElementUV](../../com.aspose.threed/vertexelementuv) - Generated UV data
### generateUV(Mesh mesh, VertexElementNormal normals) {#generateUV-com.aspose.threed.Mesh-com.aspose.threed.VertexElementNormal-}
```
public static VertexElementUV generateUV(Mesh mesh, VertexElementNormal normals)
```


Genereer UV-data vanuit het opgegeven invoer‑mesh en gespecificeerde normale data.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| mesh | [Mesh](../../com.aspose.threed/mesh) | De invoer‑mesh |
| normals | [VertexElementNormal](../../com.aspose.threed/vertexelementnormal) | De normaldata |

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


Converteer een heel knooppunt naar een enkele getransformeerde mesh Vertex-elementen zoals normale/textuurcoördinaten worden nog niet ondersteund

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| node | [Node](../../com.aspose.threed/node) | Het knooppunt om te samenvoegen |

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


Converteer een hele scène naar een enkele getransformeerde mesh Vertex-elementen zoals normale/textuurcoördinaten worden nog niet ondersteund

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| scene | [Scene](../../com.aspose.threed/scene) | De scène om samen te voegen |

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


Converteer een heel knooppunt naar een enkele getransformeerde mesh Vertex-elementen zoals normale/textuurcoördinaten worden nog niet ondersteund

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| knooppunten | java.util.List<com.aspose.threed.Node> | De knooppunten om samen te voegen |

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


Schaal alle geometrieën (Schaal de controlepunten, niet de transformatie-matrix) in dit knooppunt

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| node | [Node](../../com.aspose.threed/node) | Het knooppunt om te schalen |
|  | scale | [Vector3](../../com.aspose.threed/vector3) | De schaalfactor **Example:** De volgende code laat zien hoe alle geometrieën in de scène met 10 keer worden geschaald. |

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


Schaal alle geometrieën (Schaal de controlepunten, niet de transformatie-matrix) in deze scène

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| scene | [Scene](../../com.aspose.threed/scene) | De scène om te schalen |
|  | scale | [Vector3](../../com.aspose.threed/vector3) | De schaalfactor **Example:** De volgende code laat zien hoe alle geometrieën in de scène met 10 keer worden geschaald. |

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


Splits mesh in sub-meshes via [VertexElementMaterial](../../com.aspose.threed/vertexelementmaterial). Elk sub-mesh zal slechts één materiaal gebruiken. De originele mesh wordt niet gewijzigd.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| mesh | [Mesh](../../com.aspose.threed/mesh) |  |
| policy | [SplitMeshPolicy](../../com.aspose.threed/splitmeshpolicy) |  |

**Returns:**
com.aspose.threed.Mesh[] - Nieuwe gesplitste meshes **Voorbeeld:** De volgende code laat zien hoe een doos te splitsen in submeshes met behulp van materiaindexen.

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


Splits mesh in sub-meshes met [VertexElementMaterial](../../com.aspose.threed/vertexelementmaterial). Elke sub-mesh zal slechts één materiaal gebruiken. Voer mesh-splitsing uit op een knooppunt **Voorbeeld:** De volgende code laat zien hoe een doos te splitsen in submeshes met behulp van materiaindexen.

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
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| node | [Node](../../com.aspose.threed/node) |  |
| policy | [SplitMeshPolicy](../../com.aspose.threed/splitmeshpolicy) |  |

### splitMesh(Node node, SplitMeshPolicy policy, boolean createChildNodes) {#splitMesh-com.aspose.threed.Node-com.aspose.threed.SplitMeshPolicy-boolean-}
```
public static void splitMesh(Node node, SplitMeshPolicy policy, boolean createChildNodes)
```


Splits mesh in sub-meshes met [VertexElementMaterial](../../com.aspose.threed/vertexelementmaterial). Elke sub-mesh zal slechts één materiaal gebruiken. Voer mesh-splitsing uit op een knooppunt.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| node | [Node](../../com.aspose.threed/node) |  |
| policy | [SplitMeshPolicy](../../com.aspose.threed/splitmeshpolicy) |  |
|  | createChildNodes | boolean | Maak kindknooppunten aan voor elke sub-mesh. **Voorbeeld:** De volgende code laat zien hoe een doos te splitsen in submeshes met behulp van materiaindexen. |

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


Splits mesh in sub-meshes met [VertexElementMaterial](../../com.aspose.threed/vertexelementmaterial). Elke sub-mesh zal slechts één materiaal gebruiken. Voer mesh-splitsing uit op een knooppunt.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| node | [Node](../../com.aspose.threed/node) |  |
| policy | [SplitMeshPolicy](../../com.aspose.threed/splitmeshpolicy) |  |
| createChildNodes | boolean | Maak kindknooppunten aan voor elke sub-mesh. |
|  | removeOldMesh | boolean | Verwijder de oude mesh na het splitsen; als deze parameter onwaar is, zullen de oude en nieuwe meshes naast elkaar bestaan. **Voorbeeld:** De volgende code laat zien hoe een doos te splitsen in submeshes met behulp van materiaindexen. |

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


Splits mesh in sub-meshes met [VertexElementMaterial](../../com.aspose.threed/vertexelementmaterial). Elke sub-mesh zal slechts één materiaal gebruiken. Voer mesh-splitsing uit op alle knooppunten van de scène **Voorbeeld:** De volgende code laat zien hoe een doos te splitsen in submeshes met behulp van materiaindexen.

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
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| scene | [Scene](../../com.aspose.threed/scene) |  |
| policy | [SplitMeshPolicy](../../com.aspose.threed/splitmeshpolicy) |  |

### splitMesh(Scene scene, SplitMeshPolicy policy, boolean removeOldMesh) {#splitMesh-com.aspose.threed.Scene-com.aspose.threed.SplitMeshPolicy-boolean-}
```
public static void splitMesh(Scene scene, SplitMeshPolicy policy, boolean removeOldMesh)
```


Splits mesh in sub-meshes met [VertexElementMaterial](../../com.aspose.threed/vertexelementmaterial). Elke sub-mesh zal slechts één materiaal gebruiken. Voer mesh-splitsing uit op alle knooppunten van de scène **Voorbeeld:** De volgende code laat zien hoe een doos te splitsen in submeshes met behulp van materiaindexen.

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
| Parameter | Type | Beschrijving |
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


Converteer een op polygonen gebaseerd mesh naar een volledig driehoekmesh

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| mesh | [Mesh](../../com.aspose.threed/mesh) | De originele niet-driehoekige mesh |

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


Converteer alle op polygonen gebaseerde meshes naar een volledig driehoekmesh

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | scene | [Scene](../../com.aspose.threed/scene) | De scène om te verwerken **Voorbeeld:** De volgende code laat zien hoe alle objecten uit een scène te combineren tot één enkele mesh. |

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


Converteer een polygoon naar driehoeken, de volgorde van de polygoon wordt gedefinieerd door de `controlPoints`

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| controlPoints | java.util.List<com.aspose.threed.Vector4> | Controlepunten van de mesh |

**Returns:**
int[][] - Een set van driehoeken **Voorbeeld:** De volgende code laat zien hoe alle objecten uit een scène te combineren tot één enkele mesh.

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


Converteer een polygoon naar driehoeken

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| controlPoints | java.util.List<com.aspose.threed.Vector4> | Controlepunten van de mesh |
| polygoon | int[] | Polygonvlak |

**Returns:**
int[][] - Een set van driehoeken **Voorbeeld:** De volgende code laat zien hoe alle objecten uit een scène te combineren tot één enkele mesh.

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


Converteer een op polygoon gebaseerd mesh naar driehoeken

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| controlPoints | java.util.List<com.aspose.threed.Vector4> | Controlepunten van de mesh |
| polygonen | java.util.List<int[]> | Polygonvlakken |

**Returns:**
int[][] - Een set van driehoeken **Voorbeeld:** De volgende code laat zien hoe alle objecten uit een scène te combineren tot één enkele mesh.

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


Converteer een op polygonen gebaseerd mesh naar een volledig driehoekmesh

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| controlPoints | java.util.List<com.aspose.threed.Vector4> | Controlepunten van de mesh |
| polygonen | java.util.List<int[]> | Polygonvlakken |
| generateNormals | boolean | Genereer normalen |
| nor_out | [Vector3\[\]](../../com.aspose.threed/vector3) | Gegenereerde normaal per controlepunt |

**Returns:**
int[][] - Een set van driehoeken **Voorbeeld:** De volgende code laat zien hoe alle objecten uit een scène te combineren tot één enkele mesh.

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
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |


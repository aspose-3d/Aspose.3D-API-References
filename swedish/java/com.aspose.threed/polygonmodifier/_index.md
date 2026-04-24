---
title: PolygonModifier
second_title: Aspose.3D for Java API-referens
description: Verktyg för att modifiera polygoner
type: docs
weight: 134
url: /sv/java/com.aspose.threed/polygonmodifier/
---

**Inheritance:**
java.lang.Object
```
public class PolygonModifier
```

Verktyg för att modifiera polygoner
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [applyTransform(Node node, Matrix4 transform)](#applyTransform-com.aspose.threed.Node-com.aspose.threed.Matrix4-) | Applicera transformationsmatris på kontrollpunkter för alla geometrier |
| [buildTangentBinormal(Mesh mesh)](#buildTangentBinormal-com.aspose.threed.Mesh-) | Detta kommer att skapa tangent och binormal på meshen Normal krävs, om normal inte finns på meshen kommer den också att skapa normaldata från positionen. |
| [buildTangentBinormal(Scene scene)](#buildTangentBinormal-com.aspose.threed.Scene-) | Detta kommer att skapa tangent och binormal på alla meshar i scenen Normal krävs, om normal inte finns på meshen kommer den också att skapa normaldata från positionen. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [generateNormal(Mesh mesh)](#generateNormal-com.aspose.threed.Mesh-) | Generera normaldata från Mesh-definition |
| [generateUV(Mesh mesh)](#generateUV-com.aspose.threed.Mesh-) | Generera UV-data från den angivna inmatningsmeshen |
| [generateUV(Mesh mesh, VertexElementNormal normals)](#generateUV-com.aspose.threed.Mesh-com.aspose.threed.VertexElementNormal-) | Generera UV-data från den angivna inmatningsmeshen och specificerad normaldata. |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) |  |
| [mergeMesh(Node node)](#mergeMesh-com.aspose.threed.Node-) | Konvertera en hel nod till ett enda transformerat mesh Vertex-element som normal-/texturkoordinater ännu inte stöds |
| [mergeMesh(Scene scene)](#mergeMesh-com.aspose.threed.Scene-) | Konvertera en hel scen till ett enda transformerat mesh Vertex-element som normal-/texturkoordinater ännu inte stöds |
| [mergeMesh(List<Node> nodes)](#mergeMesh-java.util.List-com.aspose.threed.Node--) | Konvertera en hel nod till ett enda transformerat mesh Vertex-element som normal-/texturkoordinater ännu inte stöds |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [scale(Node node, Vector3 scale)](#scale-com.aspose.threed.Node-com.aspose.threed.Vector3-) | Skala alla geometrier(Skala kontrollpunkterna, inte transformationsmatrisen) i denna nod |
| [scale(Scene scene, Vector3 scale)](#scale-com.aspose.threed.Scene-com.aspose.threed.Vector3-) | Skala alla geometrier(Skala kontrollpunkterna, inte transformationsmatrisen) i denna scen |
| [splitMesh(Mesh mesh, SplitMeshPolicy policy)](#splitMesh-com.aspose.threed.Mesh-com.aspose.threed.SplitMeshPolicy-) | Dela upp mesh i del-meshar med [VertexElementMaterial](../../com.aspose.threed/vertexelementmaterial). |
| [splitMesh(Node node, SplitMeshPolicy policy)](#splitMesh-com.aspose.threed.Node-com.aspose.threed.SplitMeshPolicy-) | Dela upp mesh i del-meshar med [VertexElementMaterial](../../com.aspose.threed/vertexelementmaterial). |
| [splitMesh(Node node, SplitMeshPolicy policy, boolean createChildNodes)](#splitMesh-com.aspose.threed.Node-com.aspose.threed.SplitMeshPolicy-boolean-) | Dela upp mesh i del-meshar med [VertexElementMaterial](../../com.aspose.threed/vertexelementmaterial). |
| [splitMesh(Node node, SplitMeshPolicy policy, boolean createChildNodes, boolean removeOldMesh)](#splitMesh-com.aspose.threed.Node-com.aspose.threed.SplitMeshPolicy-boolean-boolean-) | Dela upp mesh i del-meshar med [VertexElementMaterial](../../com.aspose.threed/vertexelementmaterial). |
| [splitMesh(Scene scene, SplitMeshPolicy policy)](#splitMesh-com.aspose.threed.Scene-com.aspose.threed.SplitMeshPolicy-) | Dela upp mesh i del-meshar med [VertexElementMaterial](../../com.aspose.threed/vertexelementmaterial). |
| [splitMesh(Scene scene, SplitMeshPolicy policy, boolean removeOldMesh)](#splitMesh-com.aspose.threed.Scene-com.aspose.threed.SplitMeshPolicy-boolean-) | Dela upp mesh i del-meshar med [VertexElementMaterial](../../com.aspose.threed/vertexelementmaterial). |
| [toString()](#toString--) |  |
| [triangulate(Mesh mesh)](#triangulate-com.aspose.threed.Mesh-) | Konvertera ett polygonbaserat mesh till ett fullständigt triangelmesh |
| [triangulate(Scene scene)](#triangulate-com.aspose.threed.Scene-) | Konvertera alla polygonbaserade mesh till ett fullständigt triangelmesh |
| [triangulate(List<Vector4> controlPoints)](#triangulate-java.util.List-com.aspose.threed.Vector4--) | Konvertera en polygon till trianglar, ordningen på polygonen definieras av `controlPoints` |
| [triangulate(List<Vector4> controlPoints, int[] polygon)](#triangulate-java.util.List-com.aspose.threed.Vector4--int---) | Konvertera en polygon till trianglar |
| [triangulate(List<Vector4> controlPoints, List<int[]> polygons)](#triangulate-java.util.List-com.aspose.threed.Vector4--java.util.List-int----) | Konvertera ett polygonbaserat mesh till trianglar |
| [triangulate(List<Vector4> controlPoints, List<int[]> polygons, boolean generateNormals, Vector3[][] nor_out)](#triangulate-java.util.List-com.aspose.threed.Vector4--java.util.List-int----boolean-com.aspose.threed.Vector3-----) | Konvertera ett polygonbaserat mesh till ett fullständigt triangelmesh |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### applyTransform(Node node, Matrix4 transform) {#applyTransform-com.aspose.threed.Node-com.aspose.threed.Matrix4-}
```
public static void applyTransform(Node node, Matrix4 transform)
```


Applicera transformationsmatris på kontrollpunkter för alla geometrier

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| node | [Node](../../com.aspose.threed/node) | Vilken nods geometrier som kommer att tillämpas med given transformation |
| transform | [Matrix4](../../com.aspose.threed/matrix4) | Transformationsmatrisen som kommer att tillämpas på kontrollpunkterna. |

### buildTangentBinormal(Mesh mesh) {#buildTangentBinormal-com.aspose.threed.Mesh-}
```
public static void buildTangentBinormal(Mesh mesh)
```


Detta kommer att skapa tangent och binormal på mesh. Normal krävs, om normal inte finns på mesh, kommer den också att skapa normaldata från position. UV krävs också, ett undantag kastas om ingen UV hittas.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| mesh | [Mesh](../../com.aspose.threed/mesh) |  |

### buildTangentBinormal(Scene scene) {#buildTangentBinormal-com.aspose.threed.Scene-}
```
public static void buildTangentBinormal(Scene scene)
```


Detta kommer att skapa tangent och binormal på alla meshar i scenen. Normal krävs, om normal inte finns på ett mesh, kommer den också att skapa normaldata från position. UV krävs också, meshen ignoreras om ingen UV är definierad.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| scene | [Scene](../../com.aspose.threed/scene) |  |

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### generateNormal(Mesh mesh) {#generateNormal-com.aspose.threed.Mesh-}
```
public static VertexElementNormal generateNormal(Mesh mesh)
```


Generera normaldata från Mesh-definition

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| mesh | [Mesh](../../com.aspose.threed/mesh) |  |

**Returns:**
[VertexElementNormal](../../com.aspose.threed/vertexelementnormal) - [VertexElementNormal](../../com.aspose.threed/vertexelementnormal) instance with normal data.
### generateUV(Mesh mesh) {#generateUV-com.aspose.threed.Mesh-}
```
public static VertexElementUV generateUV(Mesh mesh)
```


Generera UV-data från den angivna inmatningsmeshen

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| mesh | [Mesh](../../com.aspose.threed/mesh) | Inmatningsmesh |

**Returns:**
[VertexElementUV](../../com.aspose.threed/vertexelementuv) - Generated UV data
### generateUV(Mesh mesh, VertexElementNormal normals) {#generateUV-com.aspose.threed.Mesh-com.aspose.threed.VertexElementNormal-}
```
public static VertexElementUV generateUV(Mesh mesh, VertexElementNormal normals)
```


Generera UV-data från den angivna inmatningsmeshen och specificerad normaldata.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| mesh | [Mesh](../../com.aspose.threed/mesh) | Inmatningsmesh |
| normals | [VertexElementNormal](../../com.aspose.threed/vertexelementnormal) | Normaldata |

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


Konvertera en hel nod till ett enda transformerat mesh Vertex-element som normal-/texturkoordinater ännu inte stöds

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| node | [Node](../../com.aspose.threed/node) | Noden att slå ihop |

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


Konvertera en hel scen till ett enda transformerat mesh Vertex-element som normal-/texturkoordinater ännu inte stöds

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| scene | [Scene](../../com.aspose.threed/scene) | Scenen att slå ihop |

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


Konvertera en hel nod till ett enda transformerat mesh Vertex-element som normal-/texturkoordinater ännu inte stöds

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| noder | java.util.List<com.aspose.threed.Node> | Noderna att slå ihop |

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


Skala alla geometrier(Skala kontrollpunkterna, inte transformationsmatrisen) i denna nod

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| node | [Node](../../com.aspose.threed/node) | Noden att skala |
|  | scale | [Vector3](../../com.aspose.threed/vector3) | Skalfaktorn **Example:** Följande kod visar hur man skalar alla geometrier i scenen med 10 gånger. |

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


Skala alla geometrier(Skala kontrollpunkterna, inte transformationsmatrisen) i denna scen

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| scene | [Scene](../../com.aspose.threed/scene) | Scenen att skala |
|  | scale | [Vector3](../../com.aspose.threed/vector3) | Skalfaktorn **Example:** Följande kod visar hur man skalar alla geometrier i scenen med 10 gånger. |

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


Dela upp mesh i del-meshar med [VertexElementMaterial](../../com.aspose.threed/vertexelementmaterial). Varje del-mesh kommer att använda endast ett material. Det ursprungliga meshet kommer inte att ändras.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| mesh | [Mesh](../../com.aspose.threed/mesh) |  |
| policy | [SplitMeshPolicy](../../com.aspose.threed/splitmeshpolicy) |  |

**Returns:**
com.aspose.threed.Mesh[] - Nya delade meshar **Exempel:** Följande kod visar hur man delar en låda i delmeshar med materialindex.

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


Dela mesh i del-meshar med [VertexElementMaterial](../../com.aspose.threed/vertexelementmaterial). Varje del-mesh kommer att använda endast ett material. Utför meshdelning på en nod **Exempel:** Följande kod visar hur man delar en låda i delmeshar med materialindex.

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
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| node | [Node](../../com.aspose.threed/node) |  |
| policy | [SplitMeshPolicy](../../com.aspose.threed/splitmeshpolicy) |  |

### splitMesh(Node node, SplitMeshPolicy policy, boolean createChildNodes) {#splitMesh-com.aspose.threed.Node-com.aspose.threed.SplitMeshPolicy-boolean-}
```
public static void splitMesh(Node node, SplitMeshPolicy policy, boolean createChildNodes)
```


Dela mesh i del-meshar med [VertexElementMaterial](../../com.aspose.threed/vertexelementmaterial). Varje del-mesh kommer att använda endast ett material. Utför meshdelning på en nod

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| node | [Node](../../com.aspose.threed/node) |  |
| policy | [SplitMeshPolicy](../../com.aspose.threed/splitmeshpolicy) |  |
|  | createChildNodes | boolean | Skapa barnnoder för varje del-mesh. **Exempel:** Följande kod visar hur man delar en låda i delmeshar med materialindex. |

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


Dela mesh i del-meshar med [VertexElementMaterial](../../com.aspose.threed/vertexelementmaterial). Varje del-mesh kommer att använda endast ett material. Utför meshdelning på en nod

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| node | [Node](../../com.aspose.threed/node) |  |
| policy | [SplitMeshPolicy](../../com.aspose.threed/splitmeshpolicy) |  |
| createChildNodes | boolean | Skapa barnnoder för varje del-mesh. |
|  | removeOldMesh | boolean | Ta bort den gamla meshen efter delning, om detta parameter är falskt, kommer den gamla och nya meshen att existera samtidigt. **Exempel:** Följande kod visar hur man delar en låda i delmeshar med materialindex. |

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


Dela mesh i del-meshar med [VertexElementMaterial](../../com.aspose.threed/vertexelementmaterial). Varje del-mesh kommer att använda endast ett material. Utför meshdelning på alla noder i scenen. **Exempel:** Följande kod visar hur man delar en låda i delmeshar med materialindex.

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
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| scene | [Scene](../../com.aspose.threed/scene) |  |
| policy | [SplitMeshPolicy](../../com.aspose.threed/splitmeshpolicy) |  |

### splitMesh(Scene scene, SplitMeshPolicy policy, boolean removeOldMesh) {#splitMesh-com.aspose.threed.Scene-com.aspose.threed.SplitMeshPolicy-boolean-}
```
public static void splitMesh(Scene scene, SplitMeshPolicy policy, boolean removeOldMesh)
```


Dela mesh i del-meshar med [VertexElementMaterial](../../com.aspose.threed/vertexelementmaterial). Varje del-mesh kommer att använda endast ett material. Utför meshdelning på alla noder i scenen. **Exempel:** Följande kod visar hur man delar en låda i delmeshar med materialindex.

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
| Parameter | Typ | Beskrivning |
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


Konvertera ett polygonbaserat mesh till ett fullständigt triangelmesh

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| mesh | [Mesh](../../com.aspose.threed/mesh) | Den ursprungliga icke-triangulära meshen |

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


Konvertera alla polygonbaserade mesh till ett fullständigt triangelmesh

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | scene | [Scene](../../com.aspose.threed/scene) | Scenen att bearbeta **Exempel:** Följande kod visar hur man slår ihop alla objekt från en scen till ett enda mesh. |

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


Konvertera en polygon till trianglar, ordningen på polygonen definieras av `controlPoints`

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| controlPoints | java.util.List<com.aspose.threed.Vector4> | Kontrollpunkter för meshen |

**Returns:**
int[][] - En uppsättning trianglar **Exempel:** Följande kod visar hur man slår ihop alla objekt från en scen till ett enda mesh.

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


Konvertera en polygon till trianglar

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| controlPoints | java.util.List<com.aspose.threed.Vector4> | Kontrollpunkter för meshen |
| polygon | int[] | Polygonyta |

**Returns:**
int[][] - En uppsättning trianglar **Exempel:** Följande kod visar hur man slår ihop alla objekt från en scen till ett enda mesh.

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


Konvertera ett polygonbaserat mesh till trianglar

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| controlPoints | java.util.List<com.aspose.threed.Vector4> | Kontrollpunkter för meshen |
| polygoner | java.util.List<int[]> | Polygonytor |

**Returns:**
int[][] - En uppsättning trianglar **Exempel:** Följande kod visar hur man slår ihop alla objekt från en scen till ett enda mesh.

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


Konvertera ett polygonbaserat mesh till ett fullständigt triangelmesh

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| controlPoints | java.util.List<com.aspose.threed.Vector4> | Kontrollpunkter för meshen |
| polygoner | java.util.List<int[]> | Polygonytor |
| generateNormals | boolean | Generera normaler |
| nor_out | [Vector3\[\]](../../com.aspose.threed/vector3) | Genererad normal per kontrollpunkt |

**Returns:**
int[][] - En uppsättning trianglar **Exempel:** Följande kod visar hur man slår ihop alla objekt från en scen till ett enda mesh.

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
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |


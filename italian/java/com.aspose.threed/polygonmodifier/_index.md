---
title: PolygonModifier
second_title: Aspose.3D for Java API Reference
description: Utility per modificare i poligoni
type: docs
weight: 134
url: /it/java/com.aspose.threed/polygonmodifier/
---

**Inheritance:**
java.lang.Object
```
public class PolygonModifier
```

Utility per modificare i poligoni
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [applyTransform(Node node, Matrix4 transform)](#applyTransform-com.aspose.threed.Node-com.aspose.threed.Matrix4-) | Applica la matrice di trasformazione sui punti di controllo di tutte le geometrie |
| [buildTangentBinormal(Mesh mesh)](#buildTangentBinormal-com.aspose.threed.Mesh-) | Questo creerà tangente e binormale sulla mesh. È necessaria la normale; se la normale non esiste sulla mesh, verrà anche creata la dati della normale dalla posizione. |
| [buildTangentBinormal(Scene scene)](#buildTangentBinormal-com.aspose.threed.Scene-) | Questo creerà tangente e binormale su tutte le mesh della scena. È necessaria la normale; se la normale non esiste sulla mesh, verrà anche creata la dati della normale dalla posizione. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [generateNormal(Mesh mesh)](#generateNormal-com.aspose.threed.Mesh-) | Genera dati normali dalla definizione della Mesh |
| [generateUV(Mesh mesh)](#generateUV-com.aspose.threed.Mesh-) | Genera dati UV dalla mesh di input fornita |
| [generateUV(Mesh mesh, VertexElementNormal normals)](#generateUV-com.aspose.threed.Mesh-com.aspose.threed.VertexElementNormal-) | Genera dati UV dalla mesh di input fornita e dai dati normali specificati |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) |  |
| [mergeMesh(Node node)](#mergeMesh-com.aspose.threed.Node-) | Converti un intero nodo in una singola mesh trasformata Gli elementi Vertex come le coordinate normali/texture non sono ancora supportati |
| [mergeMesh(Scene scene)](#mergeMesh-com.aspose.threed.Scene-) | Converti un'intera scena in una singola mesh trasformata Gli elementi Vertex come le coordinate normali/texture non sono ancora supportati |
| [mergeMesh(List<Node> nodes)](#mergeMesh-java.util.List-com.aspose.threed.Node--) | Converti un intero nodo in una singola mesh trasformata Gli elementi Vertex come le coordinate normali/texture non sono ancora supportati |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [scale(Node node, Vector3 scale)](#scale-com.aspose.threed.Node-com.aspose.threed.Vector3-) | Scala tutte le geometrie (Scala i punti di controllo, non la matrice di trasformazione) in questo nodo |
| [scale(Scene scene, Vector3 scale)](#scale-com.aspose.threed.Scene-com.aspose.threed.Vector3-) | Scala tutte le geometrie (Scala i punti di controllo, non la matrice di trasformazione) in questa scena |
| [splitMesh(Mesh mesh, SplitMeshPolicy policy)](#splitMesh-com.aspose.threed.Mesh-com.aspose.threed.SplitMeshPolicy-) | Dividi la mesh in sotto-mesh tramite [VertexElementMaterial](../../com.aspose.threed/vertexelementmaterial). |
| [splitMesh(Node node, SplitMeshPolicy policy)](#splitMesh-com.aspose.threed.Node-com.aspose.threed.SplitMeshPolicy-) | Dividi la mesh in sotto-mesh tramite [VertexElementMaterial](../../com.aspose.threed/vertexelementmaterial). |
| [splitMesh(Node node, SplitMeshPolicy policy, boolean createChildNodes)](#splitMesh-com.aspose.threed.Node-com.aspose.threed.SplitMeshPolicy-boolean-) | Dividi la mesh in sotto-mesh tramite [VertexElementMaterial](../../com.aspose.threed/vertexelementmaterial). |
| [splitMesh(Node node, SplitMeshPolicy policy, boolean createChildNodes, boolean removeOldMesh)](#splitMesh-com.aspose.threed.Node-com.aspose.threed.SplitMeshPolicy-boolean-boolean-) | Dividi la mesh in sotto-mesh tramite [VertexElementMaterial](../../com.aspose.threed/vertexelementmaterial). |
| [splitMesh(Scene scene, SplitMeshPolicy policy)](#splitMesh-com.aspose.threed.Scene-com.aspose.threed.SplitMeshPolicy-) | Dividi la mesh in sotto-mesh tramite [VertexElementMaterial](../../com.aspose.threed/vertexelementmaterial). |
| [splitMesh(Scene scene, SplitMeshPolicy policy, boolean removeOldMesh)](#splitMesh-com.aspose.threed.Scene-com.aspose.threed.SplitMeshPolicy-boolean-) | Dividi la mesh in sotto-mesh tramite [VertexElementMaterial](../../com.aspose.threed/vertexelementmaterial). |
| [toString()](#toString--) |  |
| [triangulate(Mesh mesh)](#triangulate-com.aspose.threed.Mesh-) | Converti una mesh basata su poligoni in una mesh a triangoli completa |
| [triangulate(Scene scene)](#triangulate-com.aspose.threed.Scene-) | Converti tutte le mesh basate su poligoni in una mesh a triangoli completa |
| [triangulate(List<Vector4> controlPoints)](#triangulate-java.util.List-com.aspose.threed.Vector4--) | Converti un poligono in triangoli, l'ordine del poligono è definito da `controlPoints` |
| [triangulate(List<Vector4> controlPoints, int[] polygon)](#triangulate-java.util.List-com.aspose.threed.Vector4--int---) | Converti un poligono in triangoli |
| [triangulate(List<Vector4> controlPoints, List<int[]> polygons)](#triangulate-java.util.List-com.aspose.threed.Vector4--java.util.List-int----) | Converti una mesh basata su poligoni in triangoli |
| [triangulate(List<Vector4> controlPoints, List<int[]> polygons, boolean generateNormals, Vector3[][] nor_out)](#triangulate-java.util.List-com.aspose.threed.Vector4--java.util.List-int----boolean-com.aspose.threed.Vector3-----) | Converti una mesh basata su poligoni in una mesh a triangoli completa |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### applyTransform(Node node, Matrix4 transform) {#applyTransform-com.aspose.threed.Node-com.aspose.threed.Matrix4-}
```
public static void applyTransform(Node node, Matrix4 transform)
```


Applica la matrice di trasformazione sui punti di controllo di tutte le geometrie

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| node | [Node](../../com.aspose.threed/node) | Quali geometrie del nodo saranno applicate con la trasformazione fornita |
| transform | [Matrix4](../../com.aspose.threed/matrix4) | La matrice di trasformazione che sarà applicata ai punti di controllo. |

### buildTangentBinormal(Mesh mesh) {#buildTangentBinormal-com.aspose.threed.Mesh-}
```
public static void buildTangentBinormal(Mesh mesh)
```


Questo creerà tangente e binormale sulla mesh La normale è necessaria, se la normale non esiste sulla mesh, verrà creata anche la normale dai dati di posizione. È richiesto anche l'UV, verrà sollevata un'eccezione se non viene trovato alcun UV.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| mesh | [Mesh](../../com.aspose.threed/mesh) |  |

### buildTangentBinormal(Scene scene) {#buildTangentBinormal-com.aspose.threed.Scene-}
```
public static void buildTangentBinormal(Scene scene)
```


Questo creerà tangente e binormale su tutte le mesh della scena. La normale è necessaria; se la normale non esiste sulla mesh, verrà creata anche a partire dalla posizione. È richiesto anche l'UV; la mesh verrà ignorata se non è definito alcun UV.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| scene | [Scene](../../com.aspose.threed/scene) |  |

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### generateNormal(Mesh mesh) {#generateNormal-com.aspose.threed.Mesh-}
```
public static VertexElementNormal generateNormal(Mesh mesh)
```


Genera dati normali dalla definizione della Mesh

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| mesh | [Mesh](../../com.aspose.threed/mesh) |  |

**Returns:**
[VertexElementNormal](../../com.aspose.threed/vertexelementnormal) - [VertexElementNormal](../../com.aspose.threed/vertexelementnormal) instance with normal data.
### generateUV(Mesh mesh) {#generateUV-com.aspose.threed.Mesh-}
```
public static VertexElementUV generateUV(Mesh mesh)
```


Genera dati UV dalla mesh di input fornita

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| mesh | [Mesh](../../com.aspose.threed/mesh) | La mesh di input |

**Returns:**
[VertexElementUV](../../com.aspose.threed/vertexelementuv) - Generated UV data
### generateUV(Mesh mesh, VertexElementNormal normals) {#generateUV-com.aspose.threed.Mesh-com.aspose.threed.VertexElementNormal-}
```
public static VertexElementUV generateUV(Mesh mesh, VertexElementNormal normals)
```


Genera dati UV dalla mesh di input fornita e dai dati normali specificati

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| mesh | [Mesh](../../com.aspose.threed/mesh) | La mesh di input |
| normals | [VertexElementNormal](../../com.aspose.threed/vertexelementnormal) | I dati della normale |

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


Converti un intero nodo in una singola mesh trasformata Gli elementi Vertex come le coordinate normali/texture non sono ancora supportati

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| node | [Node](../../com.aspose.threed/node) | Il nodo da unire |

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


Converti un'intera scena in una singola mesh trasformata Gli elementi Vertex come le coordinate normali/texture non sono ancora supportati

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| scene | [Scene](../../com.aspose.threed/scene) | La scena da unire |

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


Converti un intero nodo in una singola mesh trasformata Gli elementi Vertex come le coordinate normali/texture non sono ancora supportati

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| nodi | java.util.List<com.aspose.threed.Node> | I nodi da unire |

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


Scala tutte le geometrie (Scala i punti di controllo, non la matrice di trasformazione) in questo nodo

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| node | [Node](../../com.aspose.threed/node) | Il nodo da scalare |
|  | scale | [Vector3](../../com.aspose.threed/vector3) | Il fattore di scala **Example:** Il codice seguente mostra come scalare tutte le geometrie nella scena di 10 volte. |

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


Scala tutte le geometrie (Scala i punti di controllo, non la matrice di trasformazione) in questa scena

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| scene | [Scene](../../com.aspose.threed/scene) | La scena da scalare |
|  | scale | [Vector3](../../com.aspose.threed/vector3) | Il fattore di scala **Example:** Il codice seguente mostra come scalare tutte le geometrie nella scena di 10 volte. |

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


Dividi la mesh in sotto-mesh tramite [VertexElementMaterial](../../com.aspose.threed/vertexelementmaterial). Ogni sotto-mesh utilizzerà un solo materiale. La mesh originale non verrà modificata.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| mesh | [Mesh](../../com.aspose.threed/mesh) |  |
| policy | [SplitMeshPolicy](../../com.aspose.threed/splitmeshpolicy) |  |

**Returns:**
com.aspose.threed.Mesh[] - Nuove mesh suddivise **Esempio:** Il codice seguente mostra come dividere una scatola in sub mesh usando gli indici dei materiali.

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


Dividi la mesh in sub-mesh usando [VertexElementMaterial](../../com.aspose.threed/vertexelementmaterial). Ogni sub-mesh utilizzerà un solo materiale. Esegui la suddivisione della mesh su un nodo **Esempio:** Il codice seguente mostra come dividere una scatola in sub mesh usando gli indici dei materiali.

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
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| node | [Node](../../com.aspose.threed/node) |  |
| policy | [SplitMeshPolicy](../../com.aspose.threed/splitmeshpolicy) |  |

### splitMesh(Node node, SplitMeshPolicy policy, boolean createChildNodes) {#splitMesh-com.aspose.threed.Node-com.aspose.threed.SplitMeshPolicy-boolean-}
```
public static void splitMesh(Node node, SplitMeshPolicy policy, boolean createChildNodes)
```


Dividi la mesh in sub-mesh usando [VertexElementMaterial](../../com.aspose.threed/vertexelementmaterial). Ogni sub-mesh utilizzerà un solo materiale. Esegui la suddivisione della mesh su un nodo

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| node | [Node](../../com.aspose.threed/node) |  |
| policy | [SplitMeshPolicy](../../com.aspose.threed/splitmeshpolicy) |  |
|  | createChildNodes | boolean | Crea nodi figlio per ogni sub-mesh. **Esempio:** Il codice seguente mostra come dividere una scatola in sub mesh usando gli indici dei materiali. |

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


Dividi la mesh in sub-mesh usando [VertexElementMaterial](../../com.aspose.threed/vertexelementmaterial). Ogni sub-mesh utilizzerà un solo materiale. Esegui la suddivisione della mesh su un nodo

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| node | [Node](../../com.aspose.threed/node) |  |
| policy | [SplitMeshPolicy](../../com.aspose.threed/splitmeshpolicy) |  |
| createChildNodes | boolean | Crea nodi figlio per ogni sub-mesh. |
|  | removeOldMesh | boolean | Rimuovi la mesh vecchia dopo la divisione; se questo parametro è false, le mesh vecchie e nuove coesisteranno. **Esempio:** Il codice seguente mostra come dividere una scatola in sub mesh usando gli indici dei materiali. |

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


Dividi la mesh in sub-mesh usando [VertexElementMaterial](../../com.aspose.threed/vertexelementmaterial). Ogni sub-mesh utilizzerà un solo materiale. Esegui la suddivisione della mesh su tutti i nodi della scena. **Esempio:** Il codice seguente mostra come dividere una scatola in sub mesh usando gli indici dei materiali.

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
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| scene | [Scene](../../com.aspose.threed/scene) |  |
| policy | [SplitMeshPolicy](../../com.aspose.threed/splitmeshpolicy) |  |

### splitMesh(Scene scene, SplitMeshPolicy policy, boolean removeOldMesh) {#splitMesh-com.aspose.threed.Scene-com.aspose.threed.SplitMeshPolicy-boolean-}
```
public static void splitMesh(Scene scene, SplitMeshPolicy policy, boolean removeOldMesh)
```


Dividi la mesh in sub-mesh usando [VertexElementMaterial](../../com.aspose.threed/vertexelementmaterial). Ogni sub-mesh utilizzerà un solo materiale. Esegui la suddivisione della mesh su tutti i nodi della scena. **Esempio:** Il codice seguente mostra come dividere una scatola in sub mesh usando gli indici dei materiali.

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
| Parametro | Tipo | Descrizione |
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


Converti una mesh basata su poligoni in una mesh a triangoli completa

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| mesh | [Mesh](../../com.aspose.threed/mesh) | La mesh originale non triangolare |

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


Converti tutte le mesh basate su poligoni in una mesh a triangoli completa

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | scene | [Scene](../../com.aspose.threed/scene) | La scena da elaborare **Esempio:** Il codice seguente mostra come unire tutti gli oggetti di una scena in una singola mesh. |

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


Converti un poligono in triangoli, l'ordine del poligono è definito da `controlPoints`

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| controlPoints | java.util.List<com.aspose.threed.Vector4> | Punti di controllo della mesh |

**Returns:**
int[][] - Un insieme di triangoli **Esempio:** Il codice seguente mostra come unire tutti gli oggetti di una scena in una singola mesh.

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


Converti un poligono in triangoli

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| controlPoints | java.util.List<com.aspose.threed.Vector4> | Punti di controllo della mesh |
| polygon | int[] | Faccia del poligono |

**Returns:**
int[][] - Un insieme di triangoli **Esempio:** Il codice seguente mostra come unire tutti gli oggetti di una scena in una singola mesh.

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


Converti una mesh basata su poligoni in triangoli

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| controlPoints | java.util.List<com.aspose.threed.Vector4> | Punti di controllo della mesh |
| polygons | java.util.List<int[]> | Facce del poligono |

**Returns:**
int[][] - Un insieme di triangoli **Esempio:** Il codice seguente mostra come unire tutti gli oggetti di una scena in una singola mesh.

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


Converti una mesh basata su poligoni in una mesh a triangoli completa

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| controlPoints | java.util.List<com.aspose.threed.Vector4> | Punti di controllo della mesh |
| polygons | java.util.List<int[]> | Facce del poligono |
| generateNormals | boolean | Genera normali |
| nor_out | [Vector3\[\]](../../com.aspose.threed/vector3) | Normale generata per punto di controllo |

**Returns:**
int[][] - Un insieme di triangoli **Esempio:** Il codice seguente mostra come unire tutti gli oggetti di una scena in una singola mesh.

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
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |


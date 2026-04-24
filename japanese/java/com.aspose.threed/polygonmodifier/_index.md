---
title: PolygonModifier
second_title: Aspose.3D for Java API リファレンス
description: ポリゴンを変更するユーティリティ
type: docs
weight: 134
url: /ja/java/com.aspose.threed/polygonmodifier/
---

**Inheritance:**
java.lang.Object
```
public class PolygonModifier
```

ポリゴンを変更するユーティリティ
## Methods

| Method | 説明 |
| --- | --- |
| [applyTransform(Node node, Matrix4 transform)](#applyTransform-com.aspose.threed.Node-com.aspose.threed.Matrix4-) | すべてのジオメトリの制御点に変換行列を適用します |
| [buildTangentBinormal(Mesh mesh)](#buildTangentBinormal-com.aspose.threed.Mesh-) | これによりメッシュ上に接線とバイノーマルが作成されます。法線が必要で、メッシュに法線が存在しない場合は位置から法線データも作成されます。 |
| [buildTangentBinormal(Scene scene)](#buildTangentBinormal-com.aspose.threed.Scene-) | これによりシーン内のすべてのメッシュに接線とバイノーマルが作成されます。法線が必要で、メッシュに法線が存在しない場合は位置から法線データも作成されます。 |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [generateNormal(Mesh mesh)](#generateNormal-com.aspose.threed.Mesh-) | メッシュ定義から法線データを生成します |
| [generateUV(Mesh mesh)](#generateUV-com.aspose.threed.Mesh-) | 指定された入力メッシュから UV データを生成します |
| [generateUV(Mesh mesh, VertexElementNormal normals)](#generateUV-com.aspose.threed.Mesh-com.aspose.threed.VertexElementNormal-) | 指定された入力メッシュと指定された法線データから UV データを生成します |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) |  |
| [mergeMesh(Node node)](#mergeMesh-com.aspose.threed.Node-) | ノード全体を単一の変換済みメッシュに変換しますが、法線やテクスチャ座標などの頂点要素はまだサポートされていません。 |
| [mergeMesh(Scene scene)](#mergeMesh-com.aspose.threed.Scene-) | シーン全体を単一の変換済みメッシュに変換しますが、法線やテクスチャ座標などの頂点要素はまだサポートされていません。 |
| [mergeMesh(List<Node> nodes)](#mergeMesh-java.util.List-com.aspose.threed.Node--) | ノード全体を単一の変換済みメッシュに変換しますが、法線やテクスチャ座標などの頂点要素はまだサポートされていません。 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [scale(Node node, Vector3 scale)](#scale-com.aspose.threed.Node-com.aspose.threed.Vector3-) | このノード内のすべてのジオメトリをスケールします（変換行列ではなく制御点をスケール）。 |
| [scale(Scene scene, Vector3 scale)](#scale-com.aspose.threed.Scene-com.aspose.threed.Vector3-) | このシーン内のすべてのジオメトリをスケールします（変換行列ではなく制御点をスケール）。 |
| [splitMesh(Mesh mesh, SplitMeshPolicy policy)](#splitMesh-com.aspose.threed.Mesh-com.aspose.threed.SplitMeshPolicy-) | メッシュを [VertexElementMaterial](../../com.aspose.threed/vertexelementmaterial) によってサブメッシュに分割します。 |
| [splitMesh(Node node, SplitMeshPolicy policy)](#splitMesh-com.aspose.threed.Node-com.aspose.threed.SplitMeshPolicy-) | メッシュを [VertexElementMaterial](../../com.aspose.threed/vertexelementmaterial) によってサブメッシュに分割します。 |
| [splitMesh(Node node, SplitMeshPolicy policy, boolean createChildNodes)](#splitMesh-com.aspose.threed.Node-com.aspose.threed.SplitMeshPolicy-boolean-) | メッシュを [VertexElementMaterial](../../com.aspose.threed/vertexelementmaterial) によってサブメッシュに分割します。 |
| [splitMesh(Node node, SplitMeshPolicy policy, boolean createChildNodes, boolean removeOldMesh)](#splitMesh-com.aspose.threed.Node-com.aspose.threed.SplitMeshPolicy-boolean-boolean-) | メッシュを [VertexElementMaterial](../../com.aspose.threed/vertexelementmaterial) によってサブメッシュに分割します。 |
| [splitMesh(Scene scene, SplitMeshPolicy policy)](#splitMesh-com.aspose.threed.Scene-com.aspose.threed.SplitMeshPolicy-) | メッシュを [VertexElementMaterial](../../com.aspose.threed/vertexelementmaterial) によってサブメッシュに分割します。 |
| [splitMesh(Scene scene, SplitMeshPolicy policy, boolean removeOldMesh)](#splitMesh-com.aspose.threed.Scene-com.aspose.threed.SplitMeshPolicy-boolean-) | メッシュを [VertexElementMaterial](../../com.aspose.threed/vertexelementmaterial) によってサブメッシュに分割します。 |
| [toString()](#toString--) |  |
| [triangulate(Mesh mesh)](#triangulate-com.aspose.threed.Mesh-) | ポリゴンベースのメッシュを完全な三角形メッシュに変換します。 |
| [triangulate(Scene scene)](#triangulate-com.aspose.threed.Scene-) | すべてのポリゴンベースのメッシュを完全な三角形メッシュに変換します。 |
| [triangulate(List<Vector4> controlPoints)](#triangulate-java.util.List-com.aspose.threed.Vector4--) | ポリゴンを三角形に変換します。ポリゴンの順序は `controlPoints` によって定義されます。 |
| [triangulate(List<Vector4> controlPoints, int[] polygon)](#triangulate-java.util.List-com.aspose.threed.Vector4--int---) | ポリゴンを三角形に変換します。 |
| [triangulate(List<Vector4> controlPoints, List<int[]> polygons)](#triangulate-java.util.List-com.aspose.threed.Vector4--java.util.List-int----) | ポリゴンベースのメッシュを三角形に変換します。 |
| [triangulate(List<Vector4> controlPoints, List<int[]> polygons, boolean generateNormals, Vector3[][] nor_out)](#triangulate-java.util.List-com.aspose.threed.Vector4--java.util.List-int----boolean-com.aspose.threed.Vector3-----) | ポリゴンベースのメッシュを完全な三角形メッシュに変換します。 |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### applyTransform(Node node, Matrix4 transform) {#applyTransform-com.aspose.threed.Node-com.aspose.threed.Matrix4-}
```
public static void applyTransform(Node node, Matrix4 transform)
```


すべてのジオメトリの制御点に変換行列を適用します

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| node | [Node](../../com.aspose.threed/node) | どのノードのジオメトリが指定された変換で適用されますか。 |
| transform | [Matrix4](../../com.aspose.threed/matrix4) | 制御点に適用される変換行列です。 |

### buildTangentBinormal(Mesh mesh) {#buildTangentBinormal-com.aspose.threed.Mesh-}
```
public static void buildTangentBinormal(Mesh mesh)
```


これによりメッシュ上に接線とバイノーマルが作成されます。法線は必須で、メッシュに法線が存在しない場合は位置情報から法線データも作成されます。UVも必須で、UVが見つからない場合は例外がスローされます。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| mesh | [Mesh](../../com.aspose.threed/mesh) |  |

### buildTangentBinormal(Scene scene) {#buildTangentBinormal-com.aspose.threed.Scene-}
```
public static void buildTangentBinormal(Scene scene)
```


これによりシーン内のすべてのメッシュに接線とバイノーマルが作成されます。法線は必須で、メッシュに法線が存在しない場合は位置情報から法線データも作成されます。UVも必須で、UVが定義されていないメッシュは無視されます。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| scene | [Scene](../../com.aspose.threed/scene) |  |

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### generateNormal(Mesh mesh) {#generateNormal-com.aspose.threed.Mesh-}
```
public static VertexElementNormal generateNormal(Mesh mesh)
```


メッシュ定義から法線データを生成します

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| mesh | [Mesh](../../com.aspose.threed/mesh) |  |

**Returns:**
[VertexElementNormal](../../com.aspose.threed/vertexelementnormal) - [VertexElementNormal](../../com.aspose.threed/vertexelementnormal) instance with normal data.
### generateUV(Mesh mesh) {#generateUV-com.aspose.threed.Mesh-}
```
public static VertexElementUV generateUV(Mesh mesh)
```


指定された入力メッシュから UV データを生成します

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| mesh | [Mesh](../../com.aspose.threed/mesh) | 入力メッシュ |

**Returns:**
[VertexElementUV](../../com.aspose.threed/vertexelementuv) - Generated UV data
### generateUV(Mesh mesh, VertexElementNormal normals) {#generateUV-com.aspose.threed.Mesh-com.aspose.threed.VertexElementNormal-}
```
public static VertexElementUV generateUV(Mesh mesh, VertexElementNormal normals)
```


指定された入力メッシュと指定された法線データから UV データを生成します

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| mesh | [Mesh](../../com.aspose.threed/mesh) | 入力メッシュ |
| normals | [VertexElementNormal](../../com.aspose.threed/vertexelementnormal) | 法線データ |

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


ノード全体を単一の変換済みメッシュに変換しますが、法線やテクスチャ座標などの頂点要素はまだサポートされていません。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| node | [Node](../../com.aspose.threed/node) | 結合するノード |

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


シーン全体を単一の変換済みメッシュに変換しますが、法線やテクスチャ座標などの頂点要素はまだサポートされていません。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| scene | [Scene](../../com.aspose.threed/scene) | 結合するシーン |

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


ノード全体を単一の変換済みメッシュに変換しますが、法線やテクスチャ座標などの頂点要素はまだサポートされていません。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| ノード | java.util.List<com.aspose.threed.Node> | 結合するノード一覧 |

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


このノード内のすべてのジオメトリをスケールします（変換行列ではなく制御点をスケール）。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| node | [Node](../../com.aspose.threed/node) | スケールするノード |
|  | scale | [Vector3](../../com.aspose.threed/vector3) | スケール係数 **Example:** 次のコードはシーン内のすべてのジオメトリを10倍にスケールする方法を示しています。 |

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


このシーン内のすべてのジオメトリをスケールします（変換行列ではなく制御点をスケール）。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| scene | [Scene](../../com.aspose.threed/scene) | スケールするシーン |
|  | scale | [Vector3](../../com.aspose.threed/vector3) | スケール係数 **Example:** 次のコードはシーン内のすべてのジオメトリを10倍にスケールする方法を示しています。 |

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


メッシュを [VertexElementMaterial](../../com.aspose.threed/vertexelementmaterial) によってサブメッシュに分割します。各サブメッシュは1つのマテリアルのみを使用します。元のメッシュは変更されません。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| mesh | [Mesh](../../com.aspose.threed/mesh) |  |
| policy | [SplitMeshPolicy](../../com.aspose.threed/splitmeshpolicy) |  |

**Returns:**
com.aspose.threed.Mesh[] - 新しい分割メッシュ **例:** 次のコードは、マテリアルインデックスを使用してボックスをサブメッシュに分割する方法を示しています。

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


メッシュを [VertexElementMaterial](../../com.aspose.threed/vertexelementmaterial) でサブメッシュに分割します。各サブメッシュは1つのマテリアルのみを使用します。ノード上でメッシュ分割を実行します **例:** 次のコードは、マテリアルインデックスを使用してボックスをサブメッシュに分割する方法を示しています。

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
| Parameter | Type | 説明 |
| --- | --- | --- |
| node | [Node](../../com.aspose.threed/node) |  |
| policy | [SplitMeshPolicy](../../com.aspose.threed/splitmeshpolicy) |  |

### splitMesh(Node node, SplitMeshPolicy policy, boolean createChildNodes) {#splitMesh-com.aspose.threed.Node-com.aspose.threed.SplitMeshPolicy-boolean-}
```
public static void splitMesh(Node node, SplitMeshPolicy policy, boolean createChildNodes)
```


メッシュを [VertexElementMaterial](../../com.aspose.threed/vertexelementmaterial) でサブメッシュに分割します。各サブメッシュは1つのマテリアルのみを使用します。ノード上でメッシュ分割を実行します

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| node | [Node](../../com.aspose.threed/node) |  |
| policy | [SplitMeshPolicy](../../com.aspose.threed/splitmeshpolicy) |  |
|  | createChildNodes | boolean | 各サブメッシュの子ノードを作成します。 **例:** 次のコードは、マテリアルインデックスを使用してボックスをサブメッシュに分割する方法を示しています。 |

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


メッシュを [VertexElementMaterial](../../com.aspose.threed/vertexelementmaterial) でサブメッシュに分割します。各サブメッシュは1つのマテリアルのみを使用します。ノード上でメッシュ分割を実行します

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| node | [Node](../../com.aspose.threed/node) |  |
| policy | [SplitMeshPolicy](../../com.aspose.threed/splitmeshpolicy) |  |
| createChildNodes | boolean | 各サブメッシュの子ノードを作成します。 |
|  | removeOldMesh | boolean | 分割後に古いメッシュを削除します。このパラメータが false の場合、古いメッシュと新しいメッシュは共存します。 **例:** 次のコードは、マテリアルインデックスを使用してボックスをサブメッシュに分割する方法を示しています。 |

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


メッシュを [VertexElementMaterial](../../com.aspose.threed/vertexelementmaterial) でサブメッシュに分割します。各サブメッシュは1つのマテリアルのみを使用します。シーン内のすべてのノードでメッシュ分割を実行します **例:** 次のコードは、マテリアルインデックスを使用してボックスをサブメッシュに分割する方法を示しています。

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
| Parameter | Type | 説明 |
| --- | --- | --- |
| scene | [Scene](../../com.aspose.threed/scene) |  |
| policy | [SplitMeshPolicy](../../com.aspose.threed/splitmeshpolicy) |  |

### splitMesh(Scene scene, SplitMeshPolicy policy, boolean removeOldMesh) {#splitMesh-com.aspose.threed.Scene-com.aspose.threed.SplitMeshPolicy-boolean-}
```
public static void splitMesh(Scene scene, SplitMeshPolicy policy, boolean removeOldMesh)
```


メッシュを [VertexElementMaterial](../../com.aspose.threed/vertexelementmaterial) でサブメッシュに分割します。各サブメッシュは1つのマテリアルのみを使用します。シーン内のすべてのノードでメッシュ分割を実行します **例:** 次のコードは、マテリアルインデックスを使用してボックスをサブメッシュに分割する方法を示しています。

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
| Parameter | Type | 説明 |
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


ポリゴンベースのメッシュを完全な三角形メッシュに変換します。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| mesh | [Mesh](../../com.aspose.threed/mesh) | 元の非三角形メッシュ |

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


すべてのポリゴンベースのメッシュを完全な三角形メッシュに変換します。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
|  | scene | [Scene](../../com.aspose.threed/scene) | 処理対象のシーン **例:** 次のコードは、シーン内のすべてのオブジェクトを単一のメッシュにマージする方法を示しています。 |

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


ポリゴンを三角形に変換します。ポリゴンの順序は `controlPoints` によって定義されます。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| controlPoints | java.util.List<com.aspose.threed.Vector4> | メッシュの制御点 |

**Returns:**
int[][] - 三角形の集合 **例:** 次のコードは、シーン内のすべてのオブジェクトを単一のメッシュにマージする方法を示しています。

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


ポリゴンを三角形に変換します。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| controlPoints | java.util.List<com.aspose.threed.Vector4> | メッシュの制御点 |
| polygon | int[] | ポリゴンの面 |

**Returns:**
int[][] - 三角形の集合 **例:** 次のコードは、シーン内のすべてのオブジェクトを単一のメッシュにマージする方法を示しています。

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


ポリゴンベースのメッシュを三角形に変換します。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| controlPoints | java.util.List<com.aspose.threed.Vector4> | メッシュの制御点 |
| ポリゴン | java.util.List<int[]> | ポリゴンの面 |

**Returns:**
int[][] - 三角形の集合 **例:** 次のコードは、シーン内のすべてのオブジェクトを単一のメッシュにマージする方法を示しています。

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


ポリゴンベースのメッシュを完全な三角形メッシュに変換します。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| controlPoints | java.util.List<com.aspose.threed.Vector4> | メッシュの制御点 |
| ポリゴン | java.util.List<int[]> | ポリゴンの面 |
| generateNormals | boolean | 法線を生成する |
| nor_out | [Vector3\[\]](../../com.aspose.threed/vector3) | 制御点ごとの法線が生成されました |

**Returns:**
int[][] - 三角形の集合 **例:** 次のコードは、シーン内のすべてのオブジェクトを単一のメッシュにマージする方法を示しています。

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
| Parameter | Type | 説明 |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |


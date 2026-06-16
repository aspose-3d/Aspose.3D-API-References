---
title: "PolygonModifier"
second_title: "Aspose.3D for Java API 参考"
description: "用于修改多边形的实用工具"
type: docs
weight: 134
url: /zh/java/com.aspose.threed/polygonmodifier/
---

**Inheritance:**
java.lang.Object
```
public class PolygonModifier
```

用于修改多边形的实用工具
## 方法

| 方法 | 描述 |
| --- | --- |
| [applyTransform(Node node, Matrix4 transform)](#applyTransform-com.aspose.threed.Node-com.aspose.threed.Matrix4-) | 对所有几何体的控制点应用变换矩阵 |
| [buildTangentBinormal(Mesh mesh)](#buildTangentBinormal-com.aspose.threed.Mesh-) | 这将在网格上创建切线和副法线。需要法线，如果网格上不存在法线，它还会根据位置创建法线数据。 |
| [buildTangentBinormal(Scene scene)](#buildTangentBinormal-com.aspose.threed.Scene-) | 这将在场景的所有网格上创建切线和副法线。需要法线，如果网格上不存在法线，它还会根据位置创建法线数据。 |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [generateNormal(Mesh mesh)](#generateNormal-com.aspose.threed.Mesh-) | 从 Mesh 定义生成法线数据 |
| [generateUV(Mesh mesh)](#generateUV-com.aspose.threed.Mesh-) | 从给定的输入网格生成 UV 数据 |
| [generateUV(Mesh mesh, VertexElementNormal normals)](#generateUV-com.aspose.threed.Mesh-com.aspose.threed.VertexElementNormal-) | 从给定的输入网格和指定的法线数据生成 UV 数据。 |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) |  |
| [mergeMesh(Node node)](#mergeMesh-com.aspose.threed.Node-) | 将整个节点转换为单个变换后的网格，尚不支持法线/纹理坐标等顶点元素 |
| [mergeMesh(Scene scene)](#mergeMesh-com.aspose.threed.Scene-) | 将整个场景转换为单个变换后的网格，尚不支持法线/纹理坐标等顶点元素 |
| [mergeMesh(List<Node> nodes)](#mergeMesh-java.util.List-com.aspose.threed.Node--) | 将整个节点转换为单个变换后的网格，尚不支持法线/纹理坐标等顶点元素 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [scale(Node node, Vector3 scale)](#scale-com.aspose.threed.Node-com.aspose.threed.Vector3-) | 在此节点中缩放所有几何体（缩放控制点而非变换矩阵） |
| [scale(Scene scene, Vector3 scale)](#scale-com.aspose.threed.Scene-com.aspose.threed.Vector3-) | 在此场景中缩放所有几何体（缩放控制点而非变换矩阵） |
| [splitMesh(Mesh mesh, SplitMeshPolicy policy)](#splitMesh-com.aspose.threed.Mesh-com.aspose.threed.SplitMeshPolicy-) | 通过 [VertexElementMaterial](../../com.aspose.threed/vertexelementmaterial) 将网格拆分为子网格。 |
| [splitMesh(Node node, SplitMeshPolicy policy)](#splitMesh-com.aspose.threed.Node-com.aspose.threed.SplitMeshPolicy-) | 通过 [VertexElementMaterial](../../com.aspose.threed/vertexelementmaterial) 将网格拆分为子网格。 |
| [splitMesh(Node node, SplitMeshPolicy policy, boolean createChildNodes)](#splitMesh-com.aspose.threed.Node-com.aspose.threed.SplitMeshPolicy-boolean-) | 通过 [VertexElementMaterial](../../com.aspose.threed/vertexelementmaterial) 将网格拆分为子网格。 |
| [splitMesh(Node node, SplitMeshPolicy policy, boolean createChildNodes, boolean removeOldMesh)](#splitMesh-com.aspose.threed.Node-com.aspose.threed.SplitMeshPolicy-boolean-boolean-) | 通过 [VertexElementMaterial](../../com.aspose.threed/vertexelementmaterial) 将网格拆分为子网格。 |
| [splitMesh(Scene scene, SplitMeshPolicy policy)](#splitMesh-com.aspose.threed.Scene-com.aspose.threed.SplitMeshPolicy-) | 通过 [VertexElementMaterial](../../com.aspose.threed/vertexelementmaterial) 将网格拆分为子网格。 |
| [splitMesh(Scene scene, SplitMeshPolicy policy, boolean removeOldMesh)](#splitMesh-com.aspose.threed.Scene-com.aspose.threed.SplitMeshPolicy-boolean-) | 通过 [VertexElementMaterial](../../com.aspose.threed/vertexelementmaterial) 将网格拆分为子网格。 |
| [toString()](#toString--) |  |
| [triangulate(Mesh mesh)](#triangulate-com.aspose.threed.Mesh-) | 将基于多边形的网格转换为完整的三角形网格 |
| [triangulate(Scene scene)](#triangulate-com.aspose.threed.Scene-) | 将所有基于多边形的网格转换为完整的三角形网格 |
| [triangulate(List<Vector4> controlPoints)](#triangulate-java.util.List-com.aspose.threed.Vector4--) | 将多边形转换为三角形，多边形的顺序由 `controlPoints` 定义 |
| [triangulate(List<Vector4> controlPoints, int[] polygon)](#triangulate-java.util.List-com.aspose.threed.Vector4--int---) | 将多边形转换为三角形 |
| [triangulate(List<Vector4> controlPoints, List<int[]> polygons)](#triangulate-java.util.List-com.aspose.threed.Vector4--java.util.List-int----) | 将基于多边形的网格转换为三角形 |
| [triangulate(List<Vector4> controlPoints, List<int[]> polygons, boolean generateNormals, Vector3[][] nor_out)](#triangulate-java.util.List-com.aspose.threed.Vector4--java.util.List-int----boolean-com.aspose.threed.Vector3-----) | 将基于多边形的网格转换为完整的三角形网格 |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### applyTransform(Node node, Matrix4 transform) {#applyTransform-com.aspose.threed.Node-com.aspose.threed.Matrix4-}
```
public static void applyTransform(Node node, Matrix4 transform)
```


对所有几何体的控制点应用变换矩阵

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| node | [Node](../../com.aspose.threed/node) | 将对哪个节点的几何体应用给定的变换 |
| transform | [Matrix4](../../com.aspose.threed/matrix4) | 将应用于控制点的变换矩阵。 |

### buildTangentBinormal(Mesh mesh) {#buildTangentBinormal-com.aspose.threed.Mesh-}
```
public static void buildTangentBinormal(Mesh mesh)
```


这将在网格上创建切线和双切线。需要法线，如果网格上不存在法线，它还会根据位置创建法线数据。还需要 UV，如果未找到 UV，将抛出异常。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| mesh | [Mesh](../../com.aspose.threed/mesh) |  |

### buildTangentBinormal(Scene scene) {#buildTangentBinormal-com.aspose.threed.Scene-}
```
public static void buildTangentBinormal(Scene scene)
```


这将在场景的所有网格上创建切线和双切线。需要法线，如果网格上不存在法线，它还会根据位置创建法线数据。还需要 UV，如果未定义 UV，则该网格将被忽略。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| scene | [Scene](../../com.aspose.threed/scene) |  |

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
布尔
### generateNormal(Mesh mesh) {#generateNormal-com.aspose.threed.Mesh-}
```
public static VertexElementNormal generateNormal(Mesh mesh)
```


从 Mesh 定义生成法线数据

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| mesh | [Mesh](../../com.aspose.threed/mesh) |  |

**Returns:**
[VertexElementNormal](../../com.aspose.threed/vertexelementnormal) - [VertexElementNormal](../../com.aspose.threed/vertexelementnormal) instance with normal data.
### generateUV(Mesh mesh) {#generateUV-com.aspose.threed.Mesh-}
```
public static VertexElementUV generateUV(Mesh mesh)
```


从给定的输入网格生成 UV 数据

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| mesh | [Mesh](../../com.aspose.threed/mesh) | 输入网格 |

**Returns:**
[VertexElementUV](../../com.aspose.threed/vertexelementuv) - Generated UV data
### generateUV(Mesh mesh, VertexElementNormal normals) {#generateUV-com.aspose.threed.Mesh-com.aspose.threed.VertexElementNormal-}
```
public static VertexElementUV generateUV(Mesh mesh, VertexElementNormal normals)
```


从给定的输入网格和指定的法线数据生成 UV 数据。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| mesh | [Mesh](../../com.aspose.threed/mesh) | 输入网格 |
| normals | [VertexElementNormal](../../com.aspose.threed/vertexelementnormal) | 法线数据 |

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


将整个节点转换为单个变换后的网格，尚不支持法线/纹理坐标等顶点元素

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| node | [Node](../../com.aspose.threed/node) | 要合并的节点 |

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


将整个场景转换为单个变换后的网格，尚不支持法线/纹理坐标等顶点元素

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| scene | [Scene](../../com.aspose.threed/scene) | 要合并的场景 |

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


将整个节点转换为单个变换后的网格，尚不支持法线/纹理坐标等顶点元素

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 节点 | java.util.List<com.aspose.threed.Node> | 要合并的节点 |

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


在此节点中缩放所有几何体（缩放控制点而非变换矩阵）

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| node | [Node](../../com.aspose.threed/node) | 要缩放的节点 |
|  | scale | [Vector3](../../com.aspose.threed/vector3) | 缩放因子 **Example:** 以下代码展示了如何将场景中所有几何体缩放 10 倍。 |

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


在此场景中缩放所有几何体（缩放控制点而非变换矩阵）

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| scene | [Scene](../../com.aspose.threed/scene) | 要缩放的场景 |
|  | scale | [Vector3](../../com.aspose.threed/vector3) | 缩放因子 **Example:** 以下代码展示了如何将场景中所有几何体缩放 10 倍。 |

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


通过 [VertexElementMaterial](../../com.aspose.threed/vertexelementmaterial) 将网格拆分为子网格。每个子网格只使用一种材质。原始网格不会被更改。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| mesh | [Mesh](../../com.aspose.threed/mesh) |  |
| policy | [SplitMeshPolicy](../../com.aspose.threed/splitmeshpolicy) |  |

**Returns:**
com.aspose.threed.Mesh[] - 新的拆分网格 **示例：** 以下代码演示如何使用材质索引将盒子拆分为子网格。

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


通过 [VertexElementMaterial](../../com.aspose.threed/vertexelementmaterial) 将网格拆分为子网格。每个子网格只使用一种材质。在节点上执行网格拆分 **示例：** 以下代码演示如何使用材质索引将盒子拆分为子网格。

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
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| node | [Node](../../com.aspose.threed/node) |  |
| policy | [SplitMeshPolicy](../../com.aspose.threed/splitmeshpolicy) |  |

### splitMesh(Node node, SplitMeshPolicy policy, boolean createChildNodes) {#splitMesh-com.aspose.threed.Node-com.aspose.threed.SplitMeshPolicy-boolean-}
```
public static void splitMesh(Node node, SplitMeshPolicy policy, boolean createChildNodes)
```


通过 [VertexElementMaterial](../../com.aspose.threed/vertexelementmaterial) 将网格拆分为子网格。每个子网格只使用一种材质。在节点上执行网格拆分

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| node | [Node](../../com.aspose.threed/node) |  |
| policy | [SplitMeshPolicy](../../com.aspose.threed/splitmeshpolicy) |  |
|  | createChildNodes | 布尔 | 为每个子网格创建子节点。 **示例：** 以下代码演示如何使用材质索引将盒子拆分为子网格。 |

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


通过 [VertexElementMaterial](../../com.aspose.threed/vertexelementmaterial) 将网格拆分为子网格。每个子网格只使用一种材质。在节点上执行网格拆分

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| node | [Node](../../com.aspose.threed/node) |  |
| policy | [SplitMeshPolicy](../../com.aspose.threed/splitmeshpolicy) |  |
| createChildNodes | 布尔 | 为每个子网格创建子节点。 |
|  | removeOldMesh | 布尔 | 拆分后移除旧网格，如果此参数为 false，则旧网格和新网格将共存。 **示例：** 以下代码演示如何使用材质索引将盒子拆分为子网格。 |

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


通过 [VertexElementMaterial](../../com.aspose.threed/vertexelementmaterial) 将网格拆分为子网格。每个子网格只使用一种材质。在场景的所有节点上执行网格拆分 **示例：** 以下代码演示如何使用材质索引将盒子拆分为子网格。

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
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| scene | [Scene](../../com.aspose.threed/scene) |  |
| policy | [SplitMeshPolicy](../../com.aspose.threed/splitmeshpolicy) |  |

### splitMesh(Scene scene, SplitMeshPolicy policy, boolean removeOldMesh) {#splitMesh-com.aspose.threed.Scene-com.aspose.threed.SplitMeshPolicy-boolean-}
```
public static void splitMesh(Scene scene, SplitMeshPolicy policy, boolean removeOldMesh)
```


通过 [VertexElementMaterial](../../com.aspose.threed/vertexelementmaterial) 将网格拆分为子网格。每个子网格只使用一种材质。在场景的所有节点上执行网格拆分 **示例：** 以下代码演示如何使用材质索引将盒子拆分为子网格。

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
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| scene | [Scene](../../com.aspose.threed/scene) |  |
| policy | [SplitMeshPolicy](../../com.aspose.threed/splitmeshpolicy) |  |
| removeOldMesh | 布尔 |  |

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


将基于多边形的网格转换为完整的三角形网格

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| mesh | [Mesh](../../com.aspose.threed/mesh) | 原始非三角形网格 |

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


将所有基于多边形的网格转换为完整的三角形网格

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | scene | [Scene](../../com.aspose.threed/scene) | 要处理的场景 **示例：** 以下代码演示如何将场景中的所有对象合并为单个网格。 |

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


将多边形转换为三角形，多边形的顺序由 `controlPoints` 定义

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| controlPoints | java.util.List<com.aspose.threed.Vector4> | 网格的控制点 |

**Returns:**
int[][] - 一组三角形 **示例：** 以下代码演示如何将场景中的所有对象合并为单个网格。

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


将多边形转换为三角形

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| controlPoints | java.util.List<com.aspose.threed.Vector4> | 网格的控制点 |
| polygon | int[] | 多边形面 |

**Returns:**
int[][] - 一组三角形 **示例：** 以下代码演示如何将场景中的所有对象合并为单个网格。

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


将基于多边形的网格转换为三角形

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| controlPoints | java.util.List<com.aspose.threed.Vector4> | 网格的控制点 |
| polygons | java.util.List<int[]> | 多边形面 |

**Returns:**
int[][] - 一组三角形 **示例：** 以下代码演示如何将场景中的所有对象合并为单个网格。

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


将基于多边形的网格转换为完整的三角形网格

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| controlPoints | java.util.List<com.aspose.threed.Vector4> | 网格的控制点 |
| polygons | java.util.List<int[]> | 多边形面 |
| generateNormals | 布尔 | 生成法线 |
| nor_out | [Vector3\[\]](../../com.aspose.threed/vector3) | 为每个控制点生成的法线 |

**Returns:**
int[][] - 一组三角形 **示例：** 以下代码演示如何将场景中的所有对象合并为单个网格。

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
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |


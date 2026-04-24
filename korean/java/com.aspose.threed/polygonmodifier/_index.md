---
title: PolygonModifier
second_title: Aspose.3D for Java API 레퍼런스
description: 다각형을 수정하기 위한 유틸리티
type: docs
weight: 134
url: /ko/java/com.aspose.threed/polygonmodifier/
---

**Inheritance:**
java.lang.Object
```
public class PolygonModifier
```

다각형을 수정하기 위한 유틸리티
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [applyTransform(Node node, Matrix4 transform)](#applyTransform-com.aspose.threed.Node-com.aspose.threed.Matrix4-) | 모든 기하학의 제어점에 변환 행렬을 적용합니다 |
| [buildTangentBinormal(Mesh mesh)](#buildTangentBinormal-com.aspose.threed.Mesh-) | 이 작업은 메시에 접선과 바이노멀을 생성합니다. 노멀은 필수이며, 메시에 노멀 데이터가 없을 경우 위치에서 노멀 데이터를 생성합니다. |
| [buildTangentBinormal(Scene scene)](#buildTangentBinormal-com.aspose.threed.Scene-) | 이 작업은 씬의 모든 메시에 접선과 바이노멀을 생성합니다. 노멀은 필수이며, 메시에 노멀 데이터가 없을 경우 위치에서 노멀 데이터를 생성합니다. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [generateNormal(Mesh mesh)](#generateNormal-com.aspose.threed.Mesh-) | Mesh 정의에서 노멀 데이터를 생성합니다 |
| [generateUV(Mesh mesh)](#generateUV-com.aspose.threed.Mesh-) | 주어진 입력 메쉬에서 UV 데이터를 생성합니다 |
| [generateUV(Mesh mesh, VertexElementNormal normals)](#generateUV-com.aspose.threed.Mesh-com.aspose.threed.VertexElementNormal-) | 주어진 입력 메쉬와 지정된 노멀 데이터에서 UV 데이터를 생성합니다 |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) |  |
| [mergeMesh(Node node)](#mergeMesh-com.aspose.threed.Node-) | 전체 노드를 단일 변환 메시로 변환합니다. normal/texture 좌표와 같은 Vertex elements는 아직 지원되지 않습니다. |
| [mergeMesh(Scene scene)](#mergeMesh-com.aspose.threed.Scene-) | 전체 씬을 단일 변환 메시로 변환합니다. normal/texture 좌표와 같은 Vertex elements는 아직 지원되지 않습니다. |
| [mergeMesh(List<Node> nodes)](#mergeMesh-java.util.List-com.aspose.threed.Node--) | 전체 노드를 단일 변환 메시로 변환합니다. normal/texture 좌표와 같은 Vertex elements는 아직 지원되지 않습니다. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [scale(Node node, Vector3 scale)](#scale-com.aspose.threed.Node-com.aspose.threed.Vector3-) | 이 노드의 모든 기하학을 스케일합니다(변환 행렬이 아니라 제어점을 스케일). |
| [scale(Scene scene, Vector3 scale)](#scale-com.aspose.threed.Scene-com.aspose.threed.Vector3-) | 이 씬의 모든 기하학을 스케일합니다(변환 행렬이 아니라 제어점을 스케일). |
| [splitMesh(Mesh mesh, SplitMeshPolicy policy)](#splitMesh-com.aspose.threed.Mesh-com.aspose.threed.SplitMeshPolicy-) | [VertexElementMaterial](../../com.aspose.threed/vertexelementmaterial)를 사용하여 메시를 서브 메시로 분할합니다. |
| [splitMesh(Node node, SplitMeshPolicy policy)](#splitMesh-com.aspose.threed.Node-com.aspose.threed.SplitMeshPolicy-) | [VertexElementMaterial](../../com.aspose.threed/vertexelementmaterial)를 사용하여 메시를 서브 메시로 분할합니다. |
| [splitMesh(Node node, SplitMeshPolicy policy, boolean createChildNodes)](#splitMesh-com.aspose.threed.Node-com.aspose.threed.SplitMeshPolicy-boolean-) | [VertexElementMaterial](../../com.aspose.threed/vertexelementmaterial)를 사용하여 메시를 서브 메시로 분할합니다. |
| [splitMesh(Node node, SplitMeshPolicy policy, boolean createChildNodes, boolean removeOldMesh)](#splitMesh-com.aspose.threed.Node-com.aspose.threed.SplitMeshPolicy-boolean-boolean-) | [VertexElementMaterial](../../com.aspose.threed/vertexelementmaterial)를 사용하여 메시를 서브 메시로 분할합니다. |
| [splitMesh(Scene scene, SplitMeshPolicy policy)](#splitMesh-com.aspose.threed.Scene-com.aspose.threed.SplitMeshPolicy-) | [VertexElementMaterial](../../com.aspose.threed/vertexelementmaterial)를 사용하여 메시를 서브 메시로 분할합니다. |
| [splitMesh(Scene scene, SplitMeshPolicy policy, boolean removeOldMesh)](#splitMesh-com.aspose.threed.Scene-com.aspose.threed.SplitMeshPolicy-boolean-) | [VertexElementMaterial](../../com.aspose.threed/vertexelementmaterial)를 사용하여 메시를 서브 메시로 분할합니다. |
| [toString()](#toString--) |  |
| [triangulate(Mesh mesh)](#triangulate-com.aspose.threed.Mesh-) | 폴리곤 기반 메시를 완전한 삼각형 메시로 변환합니다. |
| [triangulate(Scene scene)](#triangulate-com.aspose.threed.Scene-) | 모든 폴리곤 기반 메시를 완전한 삼각형 메시로 변환합니다. |
| [triangulate(List<Vector4> controlPoints)](#triangulate-java.util.List-com.aspose.threed.Vector4--) | `controlPoints`에 의해 정의된 폴리곤 순서를 사용하여 폴리곤을 삼각형으로 변환합니다. |
| [triangulate(List<Vector4> controlPoints, int[] polygon)](#triangulate-java.util.List-com.aspose.threed.Vector4--int---) | 폴리곤을 삼각형으로 변환합니다. |
| [triangulate(List<Vector4> controlPoints, List<int[]> polygons)](#triangulate-java.util.List-com.aspose.threed.Vector4--java.util.List-int----) | 폴리곤 기반 메시를 삼각형으로 변환합니다. |
| [triangulate(List<Vector4> controlPoints, List<int[]> polygons, boolean generateNormals, Vector3[][] nor_out)](#triangulate-java.util.List-com.aspose.threed.Vector4--java.util.List-int----boolean-com.aspose.threed.Vector3-----) | 폴리곤 기반 메시를 완전한 삼각형 메시로 변환합니다. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### applyTransform(Node node, Matrix4 transform) {#applyTransform-com.aspose.threed.Node-com.aspose.threed.Matrix4-}
```
public static void applyTransform(Node node, Matrix4 transform)
```


모든 기하학의 제어점에 변환 행렬을 적용합니다

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| node | [Node](../../com.aspose.threed/node) | 주어진 변환이 적용될 노드의 기하학은 무엇입니까? |
| transform | [Matrix4](../../com.aspose.threed/matrix4) | 제어점에 적용될 변환 행렬입니다. |

### buildTangentBinormal(Mesh mesh) {#buildTangentBinormal-com.aspose.threed.Mesh-}
```
public static void buildTangentBinormal(Mesh mesh)
```


이 작업은 메시에 접선과 바이노멀을 생성합니다. Normal이 필요하며, 메시에 Normal이 없을 경우 위치에서 Normal 데이터를 생성합니다. UV도 필요하며, UV가 없을 경우 예외가 발생합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| mesh | [Mesh](../../com.aspose.threed/mesh) |  |

### buildTangentBinormal(Scene scene) {#buildTangentBinormal-com.aspose.threed.Scene-}
```
public static void buildTangentBinormal(Scene scene)
```


이 작업은 씬의 모든 메시에 접선과 바이노멀을 생성합니다. Normal이 필요하며, 메시에 Normal이 없을 경우 위치에서 Normal 데이터를 생성합니다. UV도 필요하며, UV가 정의되지 않은 메시는 무시됩니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| scene | [Scene](../../com.aspose.threed/scene) |  |

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### generateNormal(Mesh mesh) {#generateNormal-com.aspose.threed.Mesh-}
```
public static VertexElementNormal generateNormal(Mesh mesh)
```


Mesh 정의에서 노멀 데이터를 생성합니다

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| mesh | [Mesh](../../com.aspose.threed/mesh) |  |

**Returns:**
[VertexElementNormal](../../com.aspose.threed/vertexelementnormal) - [VertexElementNormal](../../com.aspose.threed/vertexelementnormal) instance with normal data.
### generateUV(Mesh mesh) {#generateUV-com.aspose.threed.Mesh-}
```
public static VertexElementUV generateUV(Mesh mesh)
```


주어진 입력 메쉬에서 UV 데이터를 생성합니다

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| mesh | [Mesh](../../com.aspose.threed/mesh) | 입력 메시 |

**Returns:**
[VertexElementUV](../../com.aspose.threed/vertexelementuv) - Generated UV data
### generateUV(Mesh mesh, VertexElementNormal normals) {#generateUV-com.aspose.threed.Mesh-com.aspose.threed.VertexElementNormal-}
```
public static VertexElementUV generateUV(Mesh mesh, VertexElementNormal normals)
```


주어진 입력 메쉬와 지정된 노멀 데이터에서 UV 데이터를 생성합니다

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| mesh | [Mesh](../../com.aspose.threed/mesh) | 입력 메시 |
| normals | [VertexElementNormal](../../com.aspose.threed/vertexelementnormal) | Normal 데이터 |

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


전체 노드를 단일 변환 메시로 변환합니다. normal/texture 좌표와 같은 Vertex elements는 아직 지원되지 않습니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| node | [Node](../../com.aspose.threed/node) | 병합할 노드 |

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


전체 씬을 단일 변환 메시로 변환합니다. normal/texture 좌표와 같은 Vertex elements는 아직 지원되지 않습니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| scene | [Scene](../../com.aspose.threed/scene) | 병합할 씬 |

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


전체 노드를 단일 변환 메시로 변환합니다. normal/texture 좌표와 같은 Vertex elements는 아직 지원되지 않습니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 노드들 | java.util.List<com.aspose.threed.Node> | 병합할 노드들 |

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


이 노드의 모든 기하학을 스케일합니다(변환 행렬이 아니라 제어점을 스케일).

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| node | [Node](../../com.aspose.threed/node) | 스케일할 노드 |
|  | scale | [Vector3](../../com.aspose.threed/vector3) | 스케일 팩터 **Example:** 다음 코드는 씬의 모든 기하학을 10배 스케일하는 방법을 보여줍니다. |

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


이 씬의 모든 기하학을 스케일합니다(변환 행렬이 아니라 제어점을 스케일).

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| scene | [Scene](../../com.aspose.threed/scene) | 스케일할 씬 |
|  | scale | [Vector3](../../com.aspose.threed/vector3) | 스케일 팩터 **Example:** 다음 코드는 씬의 모든 기하학을 10배 스케일하는 방법을 보여줍니다. |

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


[VertexElementMaterial](../../com.aspose.threed/vertexelementmaterial)를 사용하여 메시를 서브 메시로 분할합니다. 각 서브 메시는 하나의 재질만 사용합니다. 원본 메시는 변경되지 않습니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| mesh | [Mesh](../../com.aspose.threed/mesh) |  |
| policy | [SplitMeshPolicy](../../com.aspose.threed/splitmeshpolicy) |  |

**Returns:**
com.aspose.threed.Mesh[] - 새로 분할된 메시 **Example:** 다음 코드는 재질 인덱스를 사용하여 박스를 서브 메시에 분할하는 방법을 보여줍니다.

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


메시를 [VertexElementMaterial](../../com.aspose.threed/vertexelementmaterial)으로 서브 메시로 분할합니다. 각 서브 메시는 하나의 재질만 사용합니다. 노드에서 메시 분할을 수행합니다 **Example:** 다음 코드는 재질 인덱스를 사용하여 박스를 서브 메시에 분할하는 방법을 보여줍니다.

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
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| node | [Node](../../com.aspose.threed/node) |  |
| policy | [SplitMeshPolicy](../../com.aspose.threed/splitmeshpolicy) |  |

### splitMesh(Node node, SplitMeshPolicy policy, boolean createChildNodes) {#splitMesh-com.aspose.threed.Node-com.aspose.threed.SplitMeshPolicy-boolean-}
```
public static void splitMesh(Node node, SplitMeshPolicy policy, boolean createChildNodes)
```


메시를 [VertexElementMaterial](../../com.aspose.threed/vertexelementmaterial)으로 서브 메시로 분할합니다. 각 서브 메시는 하나의 재질만 사용합니다. 노드에서 메시 분할을 수행합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| node | [Node](../../com.aspose.threed/node) |  |
| policy | [SplitMeshPolicy](../../com.aspose.threed/splitmeshpolicy) |  |
|  | createChildNodes | boolean | 각 서브 메시마다 자식 노드를 생성합니다. **Example:** 다음 코드는 재질 인덱스를 사용하여 박스를 서브 메시에 분할하는 방법을 보여줍니다. |

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


메시를 [VertexElementMaterial](../../com.aspose.threed/vertexelementmaterial)으로 서브 메시로 분할합니다. 각 서브 메시는 하나의 재질만 사용합니다. 노드에서 메시 분할을 수행합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| node | [Node](../../com.aspose.threed/node) |  |
| policy | [SplitMeshPolicy](../../com.aspose.threed/splitmeshpolicy) |  |
| createChildNodes | boolean | 각 서브 메시마다 자식 노드를 생성합니다. |
|  | removeOldMesh | boolean | 분할 후 기존 메시를 제거합니다. 이 매개변수가 false이면 기존 메시와 새 메시가 동시에 존재합니다. **Example:** 다음 코드는 재질 인덱스를 사용하여 박스를 서브 메시에 분할하는 방법을 보여줍니다. |

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


메시를 [VertexElementMaterial](../../com.aspose.threed/vertexelementmaterial)으로 서브 메시로 분할합니다. 각 서브 메시는 하나의 재질만 사용합니다. 씬의 모든 노드에서 메시 분할을 수행합니다 **Example:** 다음 코드는 재질 인덱스를 사용하여 박스를 서브 메시에 분할하는 방법을 보여줍니다.

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
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| scene | [Scene](../../com.aspose.threed/scene) |  |
| policy | [SplitMeshPolicy](../../com.aspose.threed/splitmeshpolicy) |  |

### splitMesh(Scene scene, SplitMeshPolicy policy, boolean removeOldMesh) {#splitMesh-com.aspose.threed.Scene-com.aspose.threed.SplitMeshPolicy-boolean-}
```
public static void splitMesh(Scene scene, SplitMeshPolicy policy, boolean removeOldMesh)
```


메시를 [VertexElementMaterial](../../com.aspose.threed/vertexelementmaterial)으로 서브 메시로 분할합니다. 각 서브 메시는 하나의 재질만 사용합니다. 씬의 모든 노드에서 메시 분할을 수행합니다 **Example:** 다음 코드는 재질 인덱스를 사용하여 박스를 서브 메시에 분할하는 방법을 보여줍니다.

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
| 매개변수 | 형식 | 설명 |
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


폴리곤 기반 메시를 완전한 삼각형 메시로 변환합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| mesh | [Mesh](../../com.aspose.threed/mesh) | 원본 비삼각형 메시 |

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


모든 폴리곤 기반 메시를 완전한 삼각형 메시로 변환합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | scene | [Scene](../../com.aspose.threed/scene) | 처리할 씬 **Example:** 다음 코드는 씬의 모든 객체를 단일 메시로 병합하는 방법을 보여줍니다. |

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


`controlPoints`에 의해 정의된 폴리곤 순서를 사용하여 폴리곤을 삼각형으로 변환합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| controlPoints | java.util.List<com.aspose.threed.Vector4> | 메시의 제어점 |

**Returns:**
int[][] - 삼각형 집합 **Example:** 다음 코드는 씬의 모든 객체를 단일 메시로 병합하는 방법을 보여줍니다.

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


폴리곤을 삼각형으로 변환합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| controlPoints | java.util.List<com.aspose.threed.Vector4> | 메시의 제어점 |
| polygon | int[] | 다각형 면 |

**Returns:**
int[][] - 삼각형 집합 **Example:** 다음 코드는 씬의 모든 객체를 단일 메시로 병합하는 방법을 보여줍니다.

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


폴리곤 기반 메시를 삼각형으로 변환합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| controlPoints | java.util.List<com.aspose.threed.Vector4> | 메시의 제어점 |
| 다각형 | java.util.List<int[]> | 다각형 면 |

**Returns:**
int[][] - 삼각형 집합 **Example:** 다음 코드는 씬의 모든 객체를 단일 메시로 병합하는 방법을 보여줍니다.

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


폴리곤 기반 메시를 완전한 삼각형 메시로 변환합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| controlPoints | java.util.List<com.aspose.threed.Vector4> | 메시의 제어점 |
| 다각형 | java.util.List<int[]> | 다각형 면 |
| generateNormals | boolean | 노멀 생성 |
| nor_out | [Vector3\[\]](../../com.aspose.threed/vector3) | 제어점당 생성된 노멀 |

**Returns:**
int[][] - 삼각형 집합 **Example:** 다음 코드는 씬의 모든 객체를 단일 메시로 병합하는 방법을 보여줍니다.

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
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |


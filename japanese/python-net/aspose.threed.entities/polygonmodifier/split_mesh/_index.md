---
title: split_mesh method
second_title: Aspose.3D for Python via .NET API References
description: 
type: docs
weight: 80
url: /ja/python-net/aspose.threed.entities/polygonmodifier/split_mesh/
is_root: false
---

## split_mesh(, mesh, policy) {#aspose.threed.entities.Mesh-aspose.threed.entities.SplitMeshPolicy}

Split mesh into sub-meshes by [`VertexElementMaterial`](/3d/python-net/aspose.threed.entities/vertexelementmaterial).
Each sub-mesh will use only one material.
The original mesh will not get changed.


### Returns 


New splitted meshes


```python

@staticmethod
def split_mesh(mesh, policy):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| mesh | aspose.threed.entities.Mesh |  |
| policy | aspose.threed.entities.SplitMeshPolicy |  |

### Example 


The following code shows how to split a box into sub meshes using material indices.
		
```python
from aspose import pycore
from aspose.threed.entities import Box, MappingMode, PolygonModifier, ReferenceMode, SplitMeshPolicy, VertexElementMaterial, VertexElementType

#  箱のメッシュを作成する（箱は 6 つの平面で構成される）
box = Box().to_mesh()
#  このメッシュ上にマテリアル要素を作成する
mat = pycore.cast(VertexElementMaterial, box.create_element(VertexElementType.MATERIAL, MappingMode.POLYGON, ReferenceMode.INDEX))
#  各平面に異なるマテリアルインデックスを指定する
mat.indices.extend([0, 1, 2, 3, 4, 5 ])
#  これを 6 つのサブメッシュに分割し、各平面に 6 種類の異なるマテリアルを指定すると、各平面がサブメッシュになります。
#  CloneData ポリシーを使用したため、各平面は同じ制御点情報または制御点ベースの頂点要素情報を持ちます。
planes = PolygonModifier.split_mesh(box, SplitMeshPolicy.CLONE_DATA)
#  これを 2 つのサブメッシュに分割し、最初のメッシュは 0/1/2 平面を、2 番目のメッシュは 3/4/5 平面を含みます。
mat.indices.clear()
mat.indices.extend([0, 0, 0, 1, 1, 1 ])
#  CompactData ポリシーを使用したため、各平面は独自の制御点情報または制御点ベースの頂点要素情報を持ちます。
planes = PolygonModifier.split_mesh(box, SplitMeshPolicy.COMPACT_DATA)

```


## split_mesh(, scene, policy, remove_old_mesh) {#aspose.threed.Scene-aspose.threed.entities.SplitMeshPolicy-bool}

Split mesh into sub-meshes by [`VertexElementMaterial`](/3d/python-net/aspose.threed.entities/vertexelementmaterial).
Each sub-mesh will use only one material.
Perform mesh splitting on all nodes of the scene.



```python

@staticmethod
def split_mesh(scene, policy, remove_old_mesh):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| scene | aspose.threed.Scene |  |
| policy | aspose.threed.entities.SplitMeshPolicy |  |
| remove_old_mesh | bool |  |

### Example 


The following code shows how to split a box into sub meshes using material indices.
		
```python
from aspose import pycore
from aspose.threed.entities import Box, MappingMode, PolygonModifier, ReferenceMode, SplitMeshPolicy, VertexElementMaterial, VertexElementType

#  箱のメッシュを作成する（箱は 6 つの平面で構成される）
box = Box().to_mesh()
#  このメッシュ上にマテリアル要素を作成する
mat = pycore.cast(VertexElementMaterial, box.create_element(VertexElementType.MATERIAL, MappingMode.POLYGON, ReferenceMode.INDEX))
#  各平面に異なるマテリアルインデックスを指定する
mat.indices.extend([0, 1, 2, 3, 4, 5 ])
#  これを 6 つのサブメッシュに分割し、各平面に 6 種類の異なるマテリアルを指定すると、各平面がサブメッシュになります。
#  CloneData ポリシーを使用したため、各平面は同じ制御点情報または制御点ベースの頂点要素情報を持ちます。
planes = PolygonModifier.split_mesh(box, SplitMeshPolicy.CLONE_DATA)
#  これを 2 つのサブメッシュに分割し、最初のメッシュは 0/1/2 平面を、2 番目のメッシュは 3/4/5 平面を含みます。
mat.indices.clear()
mat.indices.extend([0, 0, 0, 1, 1, 1 ])
#  CompactData ポリシーを使用したため、各平面は独自の制御点情報または制御点ベースの頂点要素情報を持ちます。
planes = PolygonModifier.split_mesh(box, SplitMeshPolicy.COMPACT_DATA)

```


## split_mesh(, node, policy, create_child_nodes, remove_old_mesh) {#aspose.threed.Node-aspose.threed.entities.SplitMeshPolicy-bool-bool}

Split mesh into sub-meshes by [`VertexElementMaterial`](/3d/python-net/aspose.threed.entities/vertexelementmaterial).
Each sub-mesh will use only one material.
Perform mesh splitting on a node



```python

@staticmethod
def split_mesh(node, policy, create_child_nodes, remove_old_mesh):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| node | aspose.threed.Node |  |
| policy | aspose.threed.entities.SplitMeshPolicy |  |
| create_child_nodes | bool | Create child nodes for each sub-mesh. |
| remove_old_mesh | bool | Remove the old mesh after split, if this parameter is false, the old and new meshes will co-exists. |

### Example 


The following code shows how to split a box into sub meshes using material indices.
		
```python
from aspose import pycore
from aspose.threed.entities import Box, MappingMode, PolygonModifier, ReferenceMode, SplitMeshPolicy, VertexElementMaterial, VertexElementType

#  箱のメッシュを作成する（箱は 6 つの平面で構成される）
box = Box().to_mesh()
#  このメッシュ上にマテリアル要素を作成する
mat = pycore.cast(VertexElementMaterial, box.create_element(VertexElementType.MATERIAL, MappingMode.POLYGON, ReferenceMode.INDEX))
#  各平面に異なるマテリアルインデックスを指定する
mat.indices.extend([0, 1, 2, 3, 4, 5 ])
#  これを 6 つのサブメッシュに分割し、各平面に 6 種類の異なるマテリアルを指定すると、各平面がサブメッシュになります。
#  CloneData ポリシーを使用したため、各平面は同じ制御点情報または制御点ベースの頂点要素情報を持ちます。
planes = PolygonModifier.split_mesh(box, SplitMeshPolicy.CLONE_DATA)
#  これを 2 つのサブメッシュに分割し、最初のメッシュは 0/1/2 平面を、2 番目のメッシュは 3/4/5 平面を含みます。
mat.indices.clear()
mat.indices.extend([0, 0, 0, 1, 1, 1 ])
#  CompactData ポリシーを使用したため、各平面は独自の制御点情報または制御点ベースの頂点要素情報を持ちます。
planes = PolygonModifier.split_mesh(box, SplitMeshPolicy.COMPACT_DATA)

```



### See Also
* module [`aspose.threed.entities`](../../)
* class [`PolygonModifier`](/3d/python-net/aspose.threed.entities/polygonmodifier)
* class [`VertexElementMaterial`](/3d/python-net/aspose.threed.entities/vertexelementmaterial)

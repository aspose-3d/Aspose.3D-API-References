---
title: split_mesh method
second_title: Aspose.3D for Python via .NET API References
description: 
type: docs
weight: 80
url: /zh/python-net/aspose.threed.entities/polygonmodifier/split_mesh/
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

#  创建一个盒子网格（盒子由 6 个平面组成）
box = Box().to_mesh()
#  在此网格上创建材质元素
mat = pycore.cast(VertexElementMaterial, box.create_element(VertexElementType.MATERIAL, MappingMode.POLYGON, ReferenceMode.INDEX))
#  并为每个平面指定不同的材质索引
mat.indices.extend([0, 1, 2, 3, 4, 5 ])
#  现在将其拆分为 6 个子网格，我们在每个平面上指定了 6 种不同的材质，每个平面将成为一个子网格。
#  我们使用了 CloneData 策略，每个平面将拥有相同的控制点信息或基于控制点的顶点元素信息。
planes = PolygonModifier.split_mesh(box, SplitMeshPolicy.CLONE_DATA)
#  现在将其拆分为 2 个子网格，第一个网格将包含 0/1/2 平面，第二个网格将包含第 3/4/5 平面。
mat.indices.clear()
mat.indices.extend([0, 0, 0, 1, 1, 1 ])
#  我们使用了 CompactData 策略，每个平面将拥有各自的控制点信息或基于控制点的顶点元素信息。
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

#  创建一个盒子网格（盒子由 6 个平面组成）
box = Box().to_mesh()
#  在此网格上创建材质元素
mat = pycore.cast(VertexElementMaterial, box.create_element(VertexElementType.MATERIAL, MappingMode.POLYGON, ReferenceMode.INDEX))
#  并为每个平面指定不同的材质索引
mat.indices.extend([0, 1, 2, 3, 4, 5 ])
#  现在将其拆分为 6 个子网格，我们在每个平面上指定了 6 种不同的材质，每个平面将成为一个子网格。
#  我们使用了 CloneData 策略，每个平面将拥有相同的控制点信息或基于控制点的顶点元素信息。
planes = PolygonModifier.split_mesh(box, SplitMeshPolicy.CLONE_DATA)
#  现在将其拆分为 2 个子网格，第一个网格将包含 0/1/2 平面，第二个网格将包含第 3/4/5 平面。
mat.indices.clear()
mat.indices.extend([0, 0, 0, 1, 1, 1 ])
#  我们使用了 CompactData 策略，每个平面将拥有各自的控制点信息或基于控制点的顶点元素信息。
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

#  创建一个盒子网格（盒子由 6 个平面组成）
box = Box().to_mesh()
#  在此网格上创建材质元素
mat = pycore.cast(VertexElementMaterial, box.create_element(VertexElementType.MATERIAL, MappingMode.POLYGON, ReferenceMode.INDEX))
#  并为每个平面指定不同的材质索引
mat.indices.extend([0, 1, 2, 3, 4, 5 ])
#  现在将其拆分为 6 个子网格，我们在每个平面上指定了 6 种不同的材质，每个平面将成为一个子网格。
#  我们使用了 CloneData 策略，每个平面将拥有相同的控制点信息或基于控制点的顶点元素信息。
planes = PolygonModifier.split_mesh(box, SplitMeshPolicy.CLONE_DATA)
#  现在将其拆分为 2 个子网格，第一个网格将包含 0/1/2 平面，第二个网格将包含第 3/4/5 平面。
mat.indices.clear()
mat.indices.extend([0, 0, 0, 1, 1, 1 ])
#  我们使用了 CompactData 策略，每个平面将拥有各自的控制点信息或基于控制点的顶点元素信息。
planes = PolygonModifier.split_mesh(box, SplitMeshPolicy.COMPACT_DATA)

```



### See Also
* module [`aspose.threed.entities`](../../)
* class [`PolygonModifier`](/3d/python-net/aspose.threed.entities/polygonmodifier)
* class [`VertexElementMaterial`](/3d/python-net/aspose.threed.entities/vertexelementmaterial)

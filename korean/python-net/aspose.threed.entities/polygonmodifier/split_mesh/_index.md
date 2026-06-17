---
title: split_mesh method
second_title: Aspose.3D for Python via .NET API References
description: 
type: docs
weight: 80
url: /ko/python-net/aspose.threed.entities/polygonmodifier/split_mesh/
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

#  상자 메쉬를 생성합니다(상자는 6개의 평면으로 구성됩니다).
box = Box().to_mesh()
#  이 메시에 재질 요소를 생성합니다.
mat = pycore.cast(VertexElementMaterial, box.create_element(VertexElementType.MATERIAL, MappingMode.POLYGON, ReferenceMode.INDEX))
#  그리고 각 평면에 다른 재질 인덱스를 지정합니다.
mat.indices.extend([0, 1, 2, 3, 4, 5 ])
#  이제 이를 6개의 서브 메쉬로 분할합니다. 각 평면에 6개의 다른 재질을 지정했으며, 각 평면은 서브 메쉬가 됩니다.
#  CloneData 정책을 사용했으며, 각 평면은 동일한 제어점 정보 또는 제어점 기반 정점 요소 정보를 가집니다.
planes = PolygonModifier.split_mesh(box, SplitMeshPolicy.CLONE_DATA)
#  이제 이를 2개의 서브 메쉬로 분할합니다. 첫 번째 메쉬는 0/1/2 평면을 포함하고, 두 번째 메쉬는 3/4/5 평면을 포함합니다.
mat.indices.clear()
mat.indices.extend([0, 0, 0, 1, 1, 1 ])
#  CompactData 정책을 사용했으며, 각 평면은 자체 제어점 정보 또는 제어점 기반 정점 요소 정보를 가집니다.
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

#  상자 메쉬를 생성합니다(상자는 6개의 평면으로 구성됩니다).
box = Box().to_mesh()
#  이 메시에 재질 요소를 생성합니다.
mat = pycore.cast(VertexElementMaterial, box.create_element(VertexElementType.MATERIAL, MappingMode.POLYGON, ReferenceMode.INDEX))
#  그리고 각 평면에 다른 재질 인덱스를 지정합니다.
mat.indices.extend([0, 1, 2, 3, 4, 5 ])
#  이제 이를 6개의 서브 메쉬로 분할합니다. 각 평면에 6개의 다른 재질을 지정했으며, 각 평면은 서브 메쉬가 됩니다.
#  CloneData 정책을 사용했으며, 각 평면은 동일한 제어점 정보 또는 제어점 기반 정점 요소 정보를 가집니다.
planes = PolygonModifier.split_mesh(box, SplitMeshPolicy.CLONE_DATA)
#  이제 이를 2개의 서브 메쉬로 분할합니다. 첫 번째 메쉬는 0/1/2 평면을 포함하고, 두 번째 메쉬는 3/4/5 평면을 포함합니다.
mat.indices.clear()
mat.indices.extend([0, 0, 0, 1, 1, 1 ])
#  CompactData 정책을 사용했으며, 각 평면은 자체 제어점 정보 또는 제어점 기반 정점 요소 정보를 가집니다.
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

#  상자 메쉬를 생성합니다(상자는 6개의 평면으로 구성됩니다).
box = Box().to_mesh()
#  이 메시에 재질 요소를 생성합니다.
mat = pycore.cast(VertexElementMaterial, box.create_element(VertexElementType.MATERIAL, MappingMode.POLYGON, ReferenceMode.INDEX))
#  그리고 각 평면에 다른 재질 인덱스를 지정합니다.
mat.indices.extend([0, 1, 2, 3, 4, 5 ])
#  이제 이를 6개의 서브 메쉬로 분할합니다. 각 평면에 6개의 다른 재질을 지정했으며, 각 평면은 서브 메쉬가 됩니다.
#  CloneData 정책을 사용했으며, 각 평면은 동일한 제어점 정보 또는 제어점 기반 정점 요소 정보를 가집니다.
planes = PolygonModifier.split_mesh(box, SplitMeshPolicy.CLONE_DATA)
#  이제 이를 2개의 서브 메쉬로 분할합니다. 첫 번째 메쉬는 0/1/2 평면을 포함하고, 두 번째 메쉬는 3/4/5 평면을 포함합니다.
mat.indices.clear()
mat.indices.extend([0, 0, 0, 1, 1, 1 ])
#  CompactData 정책을 사용했으며, 각 평면은 자체 제어점 정보 또는 제어점 기반 정점 요소 정보를 가집니다.
planes = PolygonModifier.split_mesh(box, SplitMeshPolicy.COMPACT_DATA)

```



### See Also
* module [`aspose.threed.entities`](../../)
* class [`PolygonModifier`](/3d/python-net/aspose.threed.entities/polygonmodifier)
* class [`VertexElementMaterial`](/3d/python-net/aspose.threed.entities/vertexelementmaterial)

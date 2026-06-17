---
title: split_mesh method
second_title: Aspose.3D for Python via .NET API References
description: 
type: docs
weight: 80
url: /tr/python-net/aspose.threed.entities/polygonmodifier/split_mesh/
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

#  Bir kutu ağı oluştur (Bir kutu 6 düzlemden oluşur)
box = Box().to_mesh()
#  Bu ağ üzerinde bir malzeme öğesi oluştur
mat = pycore.cast(VertexElementMaterial, box.create_element(VertexElementType.MATERIAL, MappingMode.POLYGON, ReferenceMode.INDEX))
#  Ve her düzlem için farklı malzeme indeksini belirt
mat.indices.extend([0, 1, 2, 3, 4, 5 ])
#  Şimdi bunu 6 alt ağa böl, her düzlemde 6 farklı malzeme belirttik, her düzlem bir alt ağ haline gelecek.
#  CloneData politikasını kullandık, her düzlem aynı kontrol noktası bilgisine veya kontrol noktasına dayalı vertex öğe bilgisine sahip olacak.
planes = PolygonModifier.split_mesh(box, SplitMeshPolicy.CLONE_DATA)
#  Şimdi bunu 2 alt ağa böl, ilk ağ 0/1/2 düzlemleri içerecek ve ikinci ağ 3/4/5. düzlemleri içerecek.
mat.indices.clear()
mat.indices.extend([0, 0, 0, 1, 1, 1 ])
#  CompactData politikasını kullandık, her düzlem kendi kontrol noktası bilgisine veya kontrol noktasına dayalı vertex öğe bilgisine sahip olacak.
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

#  Bir kutu ağı oluştur (Bir kutu 6 düzlemden oluşur)
box = Box().to_mesh()
#  Bu ağ üzerinde bir malzeme öğesi oluştur
mat = pycore.cast(VertexElementMaterial, box.create_element(VertexElementType.MATERIAL, MappingMode.POLYGON, ReferenceMode.INDEX))
#  Ve her düzlem için farklı malzeme indeksini belirt
mat.indices.extend([0, 1, 2, 3, 4, 5 ])
#  Şimdi bunu 6 alt ağa böl, her düzlemde 6 farklı malzeme belirttik, her düzlem bir alt ağ haline gelecek.
#  CloneData politikasını kullandık, her düzlem aynı kontrol noktası bilgisine veya kontrol noktasına dayalı vertex öğe bilgisine sahip olacak.
planes = PolygonModifier.split_mesh(box, SplitMeshPolicy.CLONE_DATA)
#  Şimdi bunu 2 alt ağa böl, ilk ağ 0/1/2 düzlemleri içerecek ve ikinci ağ 3/4/5. düzlemleri içerecek.
mat.indices.clear()
mat.indices.extend([0, 0, 0, 1, 1, 1 ])
#  CompactData politikasını kullandık, her düzlem kendi kontrol noktası bilgisine veya kontrol noktasına dayalı vertex öğe bilgisine sahip olacak.
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

#  Bir kutu ağı oluştur (Bir kutu 6 düzlemden oluşur)
box = Box().to_mesh()
#  Bu ağ üzerinde bir malzeme öğesi oluştur
mat = pycore.cast(VertexElementMaterial, box.create_element(VertexElementType.MATERIAL, MappingMode.POLYGON, ReferenceMode.INDEX))
#  Ve her düzlem için farklı malzeme indeksini belirt
mat.indices.extend([0, 1, 2, 3, 4, 5 ])
#  Şimdi bunu 6 alt ağa böl, her düzlemde 6 farklı malzeme belirttik, her düzlem bir alt ağ haline gelecek.
#  CloneData politikasını kullandık, her düzlem aynı kontrol noktası bilgisine veya kontrol noktasına dayalı vertex öğe bilgisine sahip olacak.
planes = PolygonModifier.split_mesh(box, SplitMeshPolicy.CLONE_DATA)
#  Şimdi bunu 2 alt ağa böl, ilk ağ 0/1/2 düzlemleri içerecek ve ikinci ağ 3/4/5. düzlemleri içerecek.
mat.indices.clear()
mat.indices.extend([0, 0, 0, 1, 1, 1 ])
#  CompactData politikasını kullandık, her düzlem kendi kontrol noktası bilgisine veya kontrol noktasına dayalı vertex öğe bilgisine sahip olacak.
planes = PolygonModifier.split_mesh(box, SplitMeshPolicy.COMPACT_DATA)

```



### See Also
* module [`aspose.threed.entities`](../../)
* class [`PolygonModifier`](/3d/python-net/aspose.threed.entities/polygonmodifier)
* class [`VertexElementMaterial`](/3d/python-net/aspose.threed.entities/vertexelementmaterial)

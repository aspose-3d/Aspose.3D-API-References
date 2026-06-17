---
title: split_mesh method
second_title: Aspose.3D for Python via .NET API References
description: 
type: docs
weight: 80
url: /hi/python-net/aspose.threed.entities/polygonmodifier/split_mesh/
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

#  बॉक्स का एक मेष बनाएं (एक बॉक्स 6 विमानों से बना होता है)
box = Box().to_mesh()
#  इस मेष पर एक सामग्री तत्व बनाएं
mat = pycore.cast(VertexElementMaterial, box.create_element(VertexElementType.MATERIAL, MappingMode.POLYGON, ReferenceMode.INDEX))
#  और प्रत्येक विमान के लिए अलग सामग्री सूचकांक निर्दिष्ट करें
mat.indices.extend([0, 1, 2, 3, 4, 5 ])
#  अब इसे 6 उप-मे़श में विभाजित करें, हमने प्रत्येक विमान पर 6 अलग-अलग सामग्री निर्दिष्ट की हैं, प्रत्येक विमान एक उप-मे़श बन जाएगा।
#  हमने CloneData नीति का उपयोग किया, प्रत्येक विमान के पास समान नियंत्रण बिंदु जानकारी या नियंत्रण बिंदु-आधारित वर्टेक्स तत्व जानकारी होगी।
planes = PolygonModifier.split_mesh(box, SplitMeshPolicy.CLONE_DATA)
#  अब इसे 2 उप-मे़श में विभाजित करें, पहला मे़श 0/1/2 विमानों को शामिल करेगा, और दूसरा मे़श 3/4/5वें विमानों को शामिल करेगा।
mat.indices.clear()
mat.indices.extend([0, 0, 0, 1, 1, 1 ])
#  हमने CompactData नीति का उपयोग किया, प्रत्येक विमान के पास अपना स्वयं का नियंत्रण बिंदु जानकारी या नियंत्रण बिंदु-आधारित वर्टेक्स तत्व जानकारी होगी।
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

#  बॉक्स का एक मेष बनाएं (एक बॉक्स 6 विमानों से बना होता है)
box = Box().to_mesh()
#  इस मेष पर एक सामग्री तत्व बनाएं
mat = pycore.cast(VertexElementMaterial, box.create_element(VertexElementType.MATERIAL, MappingMode.POLYGON, ReferenceMode.INDEX))
#  और प्रत्येक विमान के लिए अलग सामग्री सूचकांक निर्दिष्ट करें
mat.indices.extend([0, 1, 2, 3, 4, 5 ])
#  अब इसे 6 उप-मे़श में विभाजित करें, हमने प्रत्येक विमान पर 6 अलग-अलग सामग्री निर्दिष्ट की हैं, प्रत्येक विमान एक उप-मे़श बन जाएगा।
#  हमने CloneData नीति का उपयोग किया, प्रत्येक विमान के पास समान नियंत्रण बिंदु जानकारी या नियंत्रण बिंदु-आधारित वर्टेक्स तत्व जानकारी होगी।
planes = PolygonModifier.split_mesh(box, SplitMeshPolicy.CLONE_DATA)
#  अब इसे 2 उप-मे़श में विभाजित करें, पहला मे़श 0/1/2 विमानों को शामिल करेगा, और दूसरा मे़श 3/4/5वें विमानों को शामिल करेगा।
mat.indices.clear()
mat.indices.extend([0, 0, 0, 1, 1, 1 ])
#  हमने CompactData नीति का उपयोग किया, प्रत्येक विमान के पास अपना स्वयं का नियंत्रण बिंदु जानकारी या नियंत्रण बिंदु-आधारित वर्टेक्स तत्व जानकारी होगी।
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

#  बॉक्स का एक मेष बनाएं (एक बॉक्स 6 विमानों से बना होता है)
box = Box().to_mesh()
#  इस मेष पर एक सामग्री तत्व बनाएं
mat = pycore.cast(VertexElementMaterial, box.create_element(VertexElementType.MATERIAL, MappingMode.POLYGON, ReferenceMode.INDEX))
#  और प्रत्येक विमान के लिए अलग सामग्री सूचकांक निर्दिष्ट करें
mat.indices.extend([0, 1, 2, 3, 4, 5 ])
#  अब इसे 6 उप-मे़श में विभाजित करें, हमने प्रत्येक विमान पर 6 अलग-अलग सामग्री निर्दिष्ट की हैं, प्रत्येक विमान एक उप-मे़श बन जाएगा।
#  हमने CloneData नीति का उपयोग किया, प्रत्येक विमान के पास समान नियंत्रण बिंदु जानकारी या नियंत्रण बिंदु-आधारित वर्टेक्स तत्व जानकारी होगी।
planes = PolygonModifier.split_mesh(box, SplitMeshPolicy.CLONE_DATA)
#  अब इसे 2 उप-मे़श में विभाजित करें, पहला मे़श 0/1/2 विमानों को शामिल करेगा, और दूसरा मे़श 3/4/5वें विमानों को शामिल करेगा।
mat.indices.clear()
mat.indices.extend([0, 0, 0, 1, 1, 1 ])
#  हमने CompactData नीति का उपयोग किया, प्रत्येक विमान के पास अपना स्वयं का नियंत्रण बिंदु जानकारी या नियंत्रण बिंदु-आधारित वर्टेक्स तत्व जानकारी होगी।
planes = PolygonModifier.split_mesh(box, SplitMeshPolicy.COMPACT_DATA)

```



### See Also
* module [`aspose.threed.entities`](../../)
* class [`PolygonModifier`](/3d/python-net/aspose.threed.entities/polygonmodifier)
* class [`VertexElementMaterial`](/3d/python-net/aspose.threed.entities/vertexelementmaterial)

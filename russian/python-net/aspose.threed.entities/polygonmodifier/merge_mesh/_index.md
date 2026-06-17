---
title: merge_mesh method
second_title: Aspose.3D for Python via .NET API References
description: 
type: docs
weight: 60
url: /ru/python-net/aspose.threed.entities/polygonmodifier/merge_mesh/
is_root: false
---

## merge_mesh(, scene) {#aspose.threed.Scene}

Convert a whole scene to a single transformed mesh
Vertex elements like normal/texture coordinates are not supported yet


### Returns 


The merged mesh


```python

@staticmethod
def merge_mesh(scene):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| scene | aspose.threed.Scene | The scene to merge |

### Example 


The following code shows how to merge all objects from a scene into a single mesh.

```python
from aspose.threed import Scene
from aspose.threed.entities import PolygonModifier

# Входной файл может содержать несколько объектов
scene = Scene.from_file("input.fbx")
# теперь объедините их в одну сетку
merged = PolygonModifier.merge_mesh(scene)
# затем сохраняем её в файл, содержащий только одну сетку
newScene = Scene(merged)
newScene.save("test.obj")

```


## merge_mesh(, nodes) {#list}





```python

@staticmethod
def merge_mesh(nodes):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| nodes | list |  |


## merge_mesh(, node) {#aspose.threed.Node}

Convert a whole node to a single transformed mesh
Vertex elements like normal/texture coordinates are not supported yet


### Returns 


Merged mesh


```python

@staticmethod
def merge_mesh(node):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| node | aspose.threed.Node | The node to merge |

### Example 


The following code shows how to merge all objects from nodes into a single mesh.

```python
from aspose.threed import Scene
from aspose.threed.entities import PolygonModifier

# Входной файл может содержать несколько объектов
scene = Scene.from_file("input.fbx")
# теперь объедините их в одну сетку
merged = PolygonModifier.merge_mesh(scene.root_node)
# затем сохраняем её в файл, содержащий только одну сетку
newScene = Scene(merged)
newScene.save("test.obj")

```



### See Also
* module [`aspose.threed.entities`](../../)
* class [`Mesh`](/3d/python-net/aspose.threed.entities/mesh)
* class [`PolygonModifier`](/3d/python-net/aspose.threed.entities/polygonmodifier)

---
title: merge_mesh method
second_title: Aspose.3D for Python via .NET API References
description: 
type: docs
weight: 60
url: /ja/python-net/aspose.threed.entities/polygonmodifier/merge_mesh/
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

# 入力ファイルには複数のオブジェクトが含まれる場合があります
scene = Scene.from_file("input.fbx")
# それらを単一のメッシュに結合する
merged = PolygonModifier.merge_mesh(scene)
# その後、メッシュが 1 つだけのファイルに保存する
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

# 入力ファイルには複数のオブジェクトが含まれる場合があります
scene = Scene.from_file("input.fbx")
# それらを単一のメッシュに結合する
merged = PolygonModifier.merge_mesh(scene.root_node)
# その後、メッシュが 1 つだけのファイルに保存する
newScene = Scene(merged)
newScene.save("test.obj")

```



### See Also
* module [`aspose.threed.entities`](../../)
* class [`Mesh`](/3d/python-net/aspose.threed.entities/mesh)
* class [`PolygonModifier`](/3d/python-net/aspose.threed.entities/polygonmodifier)

---
title: optimize method
second_title: Aspose.3D for Python via .NET API References
description: 
type: docs
weight: 170
url: /hi/python-net/aspose.threed.entities/mesh/optimize/
is_root: false
---

## optimize(self, vertex_elements) {#bool}

Optimize the mesh's memory usage by eliminating duplicated control points


### Returns 


New mesh instance with compact memory usage


```python

def optimize(self, vertex_elements):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| vertex_elements | bool | Optimize duplicated vertex element data |

### Example 


The following code shows how to eliminate duplicated control points from an unoptimized mesh:

```python
from aspose.threed.entities import Sphere

# Sphere.ToMesh 117 नियंत्रण बिंदु उत्पन्न करता है
mesh = Sphere().to_mesh()
# ऑप्टिमाइज़ करने के बाद, केवल 86 नियंत्रण बिंदु बचे हैं, बहुभुज सूचकांक भी पुनः मानचित्रित किए गए हैं।
optimized = mesh.optimize(True)

```


## optimize(self, vertex_elements, tolerance_control_point, tolerance_normal, tolerance_uv) {#bool-float-float-float}

Optimize the mesh's memory usage by eliminating duplicated control points


### Returns 


New mesh instance with compact memory usage


```python

def optimize(self, vertex_elements, tolerance_control_point, tolerance_normal, tolerance_uv):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| vertex_elements | bool | Optimize duplicated vertex element data |
| tolerance_control_point | float | The tolerance for control point, default value is 1e-9 |
| tolerance_normal | float | The tolerance for normal/tangent/binormal default value is 1e-9 |
| tolerance_uv | float | The tolerance for uv, default value is 1e-9 |



### See Also
* module [`aspose.threed.entities`](../../)
* class [`Mesh`](/3d/python-net/aspose.threed.entities/mesh)

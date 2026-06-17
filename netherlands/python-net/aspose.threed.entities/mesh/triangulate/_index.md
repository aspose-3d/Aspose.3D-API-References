---
title: triangulate method
second_title: Aspose.3D for Python via .NET API References
description: 
type: docs
weight: 210
url: /nl/python-net/aspose.threed.entities/mesh/triangulate/
is_root: false
---

## triangulate(self) {#}

Return triangulated mesh


### Returns 


Current mesh if current mesh is already triangulated, otherwise a new triangulated mesh will be calculated and returned


```python

def triangulate(self):
    ...
```



### Example 


The following code shows how to triangulate a mesh:

```python
from aspose.threed.entities import Plane

# De vlak-mesh heeft slechts één polygoon met 4 controlepunten
mesh = Plane().to_mesh()
# Na triangulatie wordt het rechthoek van de nieuwe mesh twee driehoeken.
triangulated = mesh.triangulate()

```



### See Also
* module [`aspose.threed.entities`](../../)
* class [`Mesh`](/3d/python-net/aspose.threed.entities/mesh)

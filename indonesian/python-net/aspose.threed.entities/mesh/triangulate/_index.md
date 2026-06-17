---
title: triangulate method
second_title: Aspose.3D for Python via .NET API References
description: 
type: docs
weight: 210
url: /id/python-net/aspose.threed.entities/mesh/triangulate/
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

# Mesh bidang hanya memiliki satu poligon dengan 4 titik kontrol
mesh = Plane().to_mesh()
# Setelah ditriangulasi, persegi panjang mesh baru akan menjadi 2 segitiga.
triangulated = mesh.triangulate()

```



### See Also
* module [`aspose.threed.entities`](../../)
* class [`Mesh`](/3d/python-net/aspose.threed.entities/mesh)

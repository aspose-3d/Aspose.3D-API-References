---
title: triangulate method
second_title: Aspose.3D for Python via .NET API References
description: 
type: docs
weight: 210
url: /ko/python-net/aspose.threed.entities/mesh/triangulate/
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

# 평면 메시는 4개의 제어점을 가진 하나의 폴리곤만 가지고 있습니다.
mesh = Plane().to_mesh()
# 삼각형화 후, 새로운 메쉬의 사각형은 2개의 삼각형이 됩니다.
triangulated = mesh.triangulate()

```



### See Also
* module [`aspose.threed.entities`](../../)
* class [`Mesh`](/3d/python-net/aspose.threed.entities/mesh)

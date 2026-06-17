---
title: triangulate method
second_title: Aspose.3D for Python via .NET API References
description: 
type: docs
weight: 210
url: /ar/python-net/aspose.threed.entities/mesh/triangulate/
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

# شبكة المستوى لديها مضلع واحد فقط مع 4 نقاط تحكم
mesh = Plane().to_mesh()
# بعد التحويل إلى مثلثات، سيصبح مستطيل الشبكة الجديد مكوّنًا من مثلثين.
triangulated = mesh.triangulate()

```



### See Also
* module [`aspose.threed.entities`](../../)
* class [`Mesh`](/3d/python-net/aspose.threed.entities/mesh)

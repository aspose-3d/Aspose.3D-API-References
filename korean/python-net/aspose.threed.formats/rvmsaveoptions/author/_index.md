---
title: author property
second_title: Aspose.3D for Python via .NET API References
description: 
type: docs
weight: 50
url: /ko/python-net/aspose.threed.formats/rvmsaveoptions/author/
is_root: false
---

## author property


Author information, default value is '3d@aspose'

### Example 


The following code shows how to export attribute in RVM. 
		
```python
from aspose.threed import Scene
from aspose.threed.entities import Box
from aspose.threed.formats import RvmSaveOptions

scene = Scene()
box = Box().to_mesh()
# 노드 이름은 속성을 내보내기 위해 필요합니다.
boxNode = scene.root_node.create_child_node("box", box)
boxNode.set_property("rvm:Price", 12.0)
boxNode.set_property("rvm:Weight", 30.0)
opt = RvmSaveOptions()
# rvm: 접두사가 있는 속성은 내보내집니다.
opt.export_attributes = True
opt.attribute_prefix = "rvm:"
opt.author = "Aspose.3D"
opt.file_note = "Test attribute export"
scene.save("output.rvm", opt)

```
### Definition:
```python
@property
def author(self):
    ...
@author.setter
def author(self, value):
    ...
```

### See Also
* module [`aspose.threed.formats`](../../)
* class [`RvmSaveOptions`](/3d/python-net/aspose.threed.formats/rvmsaveoptions)

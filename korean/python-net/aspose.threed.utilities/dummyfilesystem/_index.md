---
title: DummyFileSystem class
second_title: Aspose.3D for Python via .NET API References
description: 
type: docs
weight: 30
url: /ko/python-net/aspose.threed.utilities/dummyfilesystem/
is_root: false
---

## DummyFileSystem class

Read/write operations are dummy operations.



**Inheritance:** [`DummyFileSystem`](/3d/python-net/aspose.threed.utilities/dummyfilesystem) → 
[`FileSystem`](/3d/python-net/aspose.threed.utilities/filesystem)



The DummyFileSystem type exposes the following members:

### Constructors
| Constructor | Description |
| :- | :- |
| [__init__](/3d/python-net/aspose.threed.utilities/dummyfilesystem/__init__/#) | Constructs a new instance of DummyFileSystem |


### Methods
| Method | Description |
| :- | :- |
| [read_file](/3d/python-net/aspose.threed.utilities/dummyfilesystem/read_file/#str-aspose.threed.formats.IOConfig) | Create a stream for reading dependencies. |
| [write_file](/3d/python-net/aspose.threed.utilities/dummyfilesystem/write_file/#str-aspose.threed.formats.IOConfig) | Create a stream for writing dependencies. |



### Example 


The following code shows how to export file to memory, and ignore all dependent file generation.

```python
from aspose.threed import FileFormat, Scene
from aspose.threed.entities import Box
from aspose.threed.shading import LambertMaterial
from aspose.threed.utilities import DummyFileSystem
from io import BytesIO

# 재질과 함께 씬을 생성합니다
scene = Scene()
scene.root_node.create_child_node(Box()).material = LambertMaterial()
# 저장 옵션을 만들고 파일 시스템을 지정하여 종속 파일이 메모리에 기록되도록 합니다.
opt = FileFormat.WAVEFRONT_OBJ.create_save_options()
dfs = DummyFileSystem()
opt.file_system = dfs
# obj의 재질 파일 이름은 obj 파일 이름과 연결되어 있으므로 명시적인 이름이 필요합니다.
opt.file_name = "test.obj"
with BytesIO() as ms:
    scene.save(ms, opt)

```

### See Also
* module [`aspose.threed.utilities`](..)
* class [`DummyFileSystem`](/3d/python-net/aspose.threed.utilities/dummyfilesystem)
* class [`FileSystem`](/3d/python-net/aspose.threed.utilities/filesystem)

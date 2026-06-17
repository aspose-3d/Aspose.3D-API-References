---
title: MemoryFileSystem class
second_title: Aspose.3D for Python via .NET API References
description: 
type: docs
weight: 130
url: /ja/python-net/aspose.threed.utilities/memoryfilesystem/
is_root: false
---

## MemoryFileSystem class

The [`MemoryFileSystem`](/3d/python-net/aspose.threed.utilities/memoryfilesystem) will maps the read/write operations to memory.



**Inheritance:** [`MemoryFileSystem`](/3d/python-net/aspose.threed.utilities/memoryfilesystem) → 
[`FileSystem`](/3d/python-net/aspose.threed.utilities/filesystem)



The MemoryFileSystem type exposes the following members:

### Constructors
| Constructor | Description |
| :- | :- |
| [__init__](/3d/python-net/aspose.threed.utilities/memoryfilesystem/__init__/#) | Constructs a new instance of MemoryFileSystem |


### Properties
| Property | Description |
| :- | :- |
| [file_names](/3d/python-net/aspose.threed.utilities/memoryfilesystem/file_names) | File names that in this memory file system. |


### Methods
| Method | Description |
| :- | :- |
| [read_file](/3d/python-net/aspose.threed.utilities/memoryfilesystem/read_file/#str-aspose.threed.formats.IOConfig) | Create a stream for reading dependencies. |
| [write_file](/3d/python-net/aspose.threed.utilities/memoryfilesystem/write_file/#str-aspose.threed.formats.IOConfig) | Create a stream for writing dependencies. |
| [get_file_content](/3d/python-net/aspose.threed.utilities/memoryfilesystem/get_file_content/#str) | Returns the raw content of the specified file.
<br/>Throw FileNotFoundException if the specified file is not existing. |



### Example 


The following code shows how to export file to memory, includes the dependent file by using MemoryFileSystem.

```python
from aspose.threed import FileFormat, Scene
from aspose.threed.entities import Box
from aspose.threed.shading import LambertMaterial
from aspose.threed.utilities import MemoryFileSystem
from io import BytesIO

# マテリアルでシーンを作成する
scene = Scene()
scene.root_node.create_child_node(Box()).material = LambertMaterial()
# 保存オプションを作成し、ファイルシステムを指定して、依存ファイルがメモリに書き込まれるようにする
opt = FileFormat.WAVEFRONT_OBJ.create_save_options()
mfs = MemoryFileSystem()
opt.file_system = mfs
# obj のマテリアルファイル名は obj のファイル名に関連付けられているので、明示的な名前が必要です。
opt.file_name = "test.obj"
with BytesIO() as ms:
    scene.save(ms, opt)
# test.obj は変数 ms に書き込まれ、test.mtl ファイルの内容も取得できます。
materialFile = mfs.get_file_content("test.mtl")

```

### See Also
* module [`aspose.threed.utilities`](..)
* class [`FileSystem`](/3d/python-net/aspose.threed.utilities/filesystem)
* class [`MemoryFileSystem`](/3d/python-net/aspose.threed.utilities/memoryfilesystem)

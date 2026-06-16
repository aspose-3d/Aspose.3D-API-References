---
title: "MemoryFileSystem"
second_title: "Aspose.3D for .NET API 参考"
description: 
type: docs
weight: 2680
url: /zh/net/aspose.threed.utilities/memoryfilesystem/
---
## MemoryFileSystem class

[`MemoryFileSystem`](../memoryfilesystem) 将映射读/写操作到内存。

```csharp
public class MemoryFileSystem : FileSystem
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [MemoryFileSystem](memoryfilesystem)() | 默认构造函数。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [FileNames](../../aspose.threed.utilities/memoryfilesystem/filenames) { get; } | 此内存文件系统中的文件名。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| virtual [Dispose](../../aspose.threed.utilities/filesystem/dispose)() | 释放文件系统并释放其资源。 |
| [GetFileContent](../../aspose.threed.utilities/memoryfilesystem/getfilecontent)(string) | 返回指定文件的原始内容。如果指定文件不存在，则抛出 FileNotFoundException。 |
| override [ReadFile](../../aspose.threed.utilities/memoryfilesystem/readfile)(string, IOConfig) | 创建用于读取依赖项的流。 |
| override [WriteFile](../../aspose.threed.utilities/memoryfilesystem/writefile)(string, IOConfig) | 创建用于写入依赖项的流。 |

### 示例

以下代码展示了如何将文件导出到内存，并通过使用 MemoryFileSystem 包含依赖文件。

```csharp
//创建带材质的场景
Scene scene = new Scene();
scene.RootNode.CreateChildNode(new Box()).Material = new LambertMaterial();
//创建保存选项并指定文件系统，以便将依赖文件写入内存
var opt = FileFormat.WavefrontOBJ.CreateSaveOptions();
var mfs = new MemoryFileSystem();
opt.FileSystem = mfs;
//obj 的材质文件名与 obj 的文件名关联，因此我们需要一个显式的名称。
opt.FileName = "test.obj";
using (var ms = new MemoryStream())
{
    scene.Save(ms, opt);
}
//test.obj 已写入变量 ms，我们也可以通过以下方式获取 test.mtl 文件内容
var materialFile = mfs.GetFileContent("test.mtl");
```

### 另请参见

* class [FileSystem](../filesystem)
* namespace [Aspose.ThreeD.Utilities](../../aspose.threed.utilities)
* assembly [Aspose.3D](../../)

<!-- 请勿编辑：由 xmldocmd 为 Aspose.3D.dll 生成 -->

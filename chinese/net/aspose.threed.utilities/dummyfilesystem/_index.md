---
title: "DummyFileSystem"
second_title: "Aspose.3D for .NET API 参考"
description: 
type: docs
weight: 2570
url: /zh/net/aspose.threed.utilities/dummyfilesystem/
---
## DummyFileSystem class

读/写操作是虚拟操作。

```csharp
public class DummyFileSystem : FileSystem
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [DummyFileSystem](dummyfilesystem)() | 默认构造函数。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| virtual [Dispose](../../aspose.threed.utilities/filesystem/dispose)() | 释放文件系统并释放其资源。 |
| override [ReadFile](../../aspose.threed.utilities/dummyfilesystem/readfile)(string, IOConfig) | 创建用于读取依赖项的流。 |
| override [WriteFile](../../aspose.threed.utilities/dummyfilesystem/writefile)(string, IOConfig) | 创建用于写入依赖项的流。 |

### 示例

以下代码展示了如何将文件导出到内存，并忽略所有依赖文件的生成。

```csharp
//创建带材质的场景
Scene scene = new Scene();
scene.RootNode.CreateChildNode(new Box()).Material = new LambertMaterial();
//创建保存选项并指定文件系统，以便将依赖文件写入内存
var opt = FileFormat.WavefrontOBJ.CreateSaveOptions();
var dfs = new DummyFileSystem();
opt.FileSystem = dfs;
//obj 的材质文件名与 obj 的文件名关联，因此我们需要一个显式的名称。
opt.FileName = "test.obj";
using (var ms = new MemoryStream())
{
    scene.Save(ms, opt);
}
```

### 另请参见

* class [FileSystem](../filesystem)
* namespace [Aspose.ThreeD.Utilities](../../aspose.threed.utilities)
* assembly [Aspose.3D](../../)

<!-- 请勿编辑：由 xmldocmd 为 Aspose.3D.dll 生成 -->

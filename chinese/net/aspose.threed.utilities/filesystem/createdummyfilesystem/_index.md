---
title: FileSystem.CreateDummyFileSystem
second_title: Aspose.3D for .NET API 参考手册
description: FileSystem 方法。创建一个虚拟文件系统，读/写操作为虚拟操作。
type: docs
weight: 10
url: /zh/net/aspose.threed.utilities/filesystem/createdummyfilesystem/
---
## FileSystem.CreateDummyFileSystem method

创建一个虚拟文件系统，读取/写入操作为虚拟操作。

```csharp
public static FileSystem CreateDummyFileSystem()
```

### 返回值

虚拟文件系统

## 示例

以下代码展示了如何将文件导出到内存，并忽略所有依赖文件的生成。

```csharp
//创建一个带材质的场景
Scene scene = new Scene();
scene.RootNode.CreateChildNode(new Box()).Material = new LambertMaterial();
//创建保存选项并指定文件系统，以便将依赖文件写入内存
var opt = FileFormat.WavefrontOBJ.CreateSaveOptions();
var dfs = FileSystem.CreateDummyFileSystem();
opt.FileSystem = dfs;
//obj 的材质文件名与 obj 的文件名关联，因此我们需要一个显式的名称。
opt.FileName = "test.obj";
using (var ms = new MemoryStream())
{
    scene.Save(ms, opt);
}
```

### 另请参见

* class [FileSystem](../)
* namespace [Aspose.ThreeD.Utilities](../../filesystem/)
* assembly [Aspose.3D](../../../)



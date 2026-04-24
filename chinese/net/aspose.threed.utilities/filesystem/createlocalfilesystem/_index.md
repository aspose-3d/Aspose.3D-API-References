---
title: FileSystem.CreateLocalFileSystem
second_title: Aspose.3D for .NET API 参考手册
description: FileSystem 方法。初始化一个仅访问本地目录的新 FileSystem。此 FileSystem 实例上的所有文件读/写操作都将映射到指定目录。
type: docs
weight: 20
url: /zh/net/aspose.threed.utilities/filesystem/createlocalfilesystem/
---
## FileSystem.CreateLocalFileSystem method

初始化一个仅访问本地目录的新 [`FileSystem`](../)。此 FileSystem 实例上的所有文件读/写操作都将映射到指定目录。

```csharp
public static FileSystem CreateLocalFileSystem(string directory)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 目录 | 字符串 | 将您物理文件系统中的目录用作虚拟根目录。 |

### 返回值

提供本地文件访问的新文件系统实例

### 异常

| 异常 | 条件 |
| --- | --- |
| FileNotFoundException | 当找不到目录时抛出。 |

## 示例

以下代码展示了如何导入文件，并在给定目录中提供依赖文件。

```csharp
var inputFile = "input.fbx";
var format = FileFormat.Detect(inputFile);
//创建一个加载选项实例并指定本地文件系统
var opt = format.CreateLoadOptions();
opt.FileSystem = FileSystem.CreateLocalFileSystem("textures/");
//加载文件
var scene = Scene.FromFile(inputFile, opt);
```

### 另请参见

* class [FileSystem](../)
* namespace [Aspose.ThreeD.Utilities](../../filesystem/)
* assembly [Aspose.3D](../../../)



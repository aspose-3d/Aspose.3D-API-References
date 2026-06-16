---
title: "LocalFileSystem"
second_title: "Aspose.3D for .NET API 参考"
description: 
type: docs
weight: 2650
url: /zh/net/aspose.threed.utilities/localfilesystem/
---
## LocalFileSystem class

[`LocalFileSystem`](../localfilesystem) 将把读/写操作映射到本地目录。

```csharp
public class LocalFileSystem : FileSystem
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [LocalFileSystem](localfilesystem)(string) | 使用指定的基目录初始化一个新的 [`LocalFileSystem`](../localfilesystem)。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| virtual [Dispose](../../aspose.threed.utilities/filesystem/dispose)() | 释放文件系统并释放其资源。 |
| override [ReadFile](../../aspose.threed.utilities/localfilesystem/readfile)(string, IOConfig) | 创建用于读取依赖项的流。 |
| override [WriteFile](../../aspose.threed.utilities/localfilesystem/writefile)(string, IOConfig) | 创建用于写入依赖项的流。 |

### 示例

以下代码展示了如何导入文件，并在给定目录中提供依赖文件。

```csharp
var inputFile = "input.fbx";
var format = FileFormat.Detect(inputFile);
//创建一个加载选项实例并指定 zip 文件系统
var opt = format.CreateLoadOptions();
opt.FileSystem = new LocalFileSystem("textures/");
//加载文件
var scene = Scene.FromFile(inputFile, opt);
```

### 另请参见

* class [FileSystem](../filesystem)
* namespace [Aspose.ThreeD.Utilities](../../aspose.threed.utilities)
* assembly [Aspose.3D](../../)

<!-- 请勿编辑：由 xmldocmd 为 Aspose.3D.dll 生成 -->

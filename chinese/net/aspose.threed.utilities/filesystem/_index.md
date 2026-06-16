---
title: "类 FileSystem"
second_title: "Aspose.3D for .NET API 参考"
description: "Aspose.ThreeD.Utilities.FileSystem 类。文件系统封装。Aspose.3D 将使用它来读取/写入依赖项"
type: docs
weight: 2750
url: /zh/net/aspose.threed.utilities/filesystem/
---
## FileSystem class

文件系统封装。Aspose.3D 将使用它来读取/写入依赖项。

```csharp
public abstract class FileSystem : IDisposable
```

## 方法

| 名称 | 描述 |
| --- | --- |
| static [CreateDummyFileSystem](../../aspose.threed.utilities/filesystem/createdummyfilesystem/)() | 创建一个虚拟文件系统，读取/写入操作为虚拟操作。 |
| static [CreateLocalFileSystem](../../aspose.threed.utilities/filesystem/createlocalfilesystem/)(string) | 初始化一个仅访问本地目录的新的 `FileSystem`。此 FileSystem 实例上的所有文件读取/写入将映射到指定目录。 |
| static [CreateMemoryFileSystem](../../aspose.threed.utilities/filesystem/creatememoryfilesystem/)(Dictionary&lt;string, MemoryStream&gt;) |  |
| static [CreateZipFileSystem](../../aspose.threed.utilities/filesystem/createzipfilesystem/#createzipfilesystem_1)(string) | 文件系统提供对指定 zip 文件或 zip 流的只读访问。文件系统将在打开/保存操作后被释放。 |
| static [CreateZipFileSystem](../../aspose.threed.utilities/filesystem/createzipfilesystem/#createzipfilesystem)(Stream, string) | 创建一个文件系统，以提供对指定 zip 文件或 zip 流的只读访问。文件系统将在打开/保存操作后被释放。 |
| virtual [Dispose](../../aspose.threed.utilities/filesystem/dispose/)() | 释放文件系统并释放其资源。 |
| abstract [ReadFile](../../aspose.threed.utilities/filesystem/readfile/)(string, IOConfig) | 创建用于读取依赖项的流。 |
| abstract [WriteFile](../../aspose.threed.utilities/filesystem/writefile/)(string, IOConfig) | 创建用于写入依赖项的流。 |

## 示例

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

* namespace [Aspose.ThreeD.Utilities](../../aspose.threed.utilities/)
* assembly [Aspose.3D](../../)



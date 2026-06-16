---
title: "类 ZipArchiveFileSystem"
second_title: "Aspose.3D for .NET API 参考"
description: "Aspose.ThreeD.Utilities.ZipArchiveFileSystem 类。文件系统提供对指定 zip 文件或 zip 流的只读访问。文件系统将在打开/保存操作后被释放。"
type: docs
weight: 2830
url: /zh/net/aspose.threed.utilities/ziparchivefilesystem/
---
## ZipArchiveFileSystem class

文件系统提供对指定 zip 文件或 zip 流的只读访问。文件系统将在打开/保存操作后被释放。

```csharp
public class ZipArchiveFileSystem : FileSystem
```

## 方法

| 名称 | 描述 |
| --- | --- |
| override [Dispose](../../aspose.threed.utilities/ziparchivefilesystem/dispose/)() | 释放 ZipArchiveFileSystem 并释放其内部资源。 |
| override [ReadFile](../../aspose.threed.utilities/ziparchivefilesystem/readfile/)(string, IOConfig) | 打开文件进行读取 |
| override [WriteFile](../../aspose.threed.utilities/ziparchivefilesystem/writefile/)(string, IOConfig) | 打开文件进行写入，此类未实现此功能。 |

### 示例

以下代码展示了如何导入文件，并在 zip 存档文件中提供依赖文件。

```csharp
var inputFile = "input.fbx";
var format = FileFormat.Detect(inputFile);
//创建一个加载选项实例并指定 zip 文件系统
var opt = format.CreateLoadOptions();
opt.FileSystem = new ZipArchiveFileSystem("textures.zip");
//加载文件
var scene = Scene.FromFile(inputFile, opt);
```

### 另请参见

* class [FileSystem](../filesystem/)
* namespace [Aspose.ThreeD.Utilities](../../aspose.threed.utilities/)
* assembly [Aspose.3D](../../)



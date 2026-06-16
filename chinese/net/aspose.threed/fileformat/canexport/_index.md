---
title: "FileFormat.CanExport"
second_title: "Aspose.3D for .NET API 参考"
description: "FileFormat 属性。获取 Aspose.3D 是否支持将场景导出为当前文件格式"
type: docs
weight: 480
url: /zh/net/aspose.threed/fileformat/canexport/
---
## FileFormat.CanExport property

获取 Aspose.3D 是否支持将场景导出为当前文件格式。

```csharp
public bool CanExport { get; }
```

## 示例

以下代码展示了如何检查是否支持导出到指定格式。

```csharp
var outputFormat = ".glb";
var format = FileFormat.GetFormatByExtension(outputFormat);
if (format.CanExport)
    Console.WriteLine($"Can export to {outputFormat}");
```

### 另请参见

* class [FileFormat](../)
* namespace [Aspose.ThreeD](../../fileformat/)
* assembly [Aspose.3D](../../../)



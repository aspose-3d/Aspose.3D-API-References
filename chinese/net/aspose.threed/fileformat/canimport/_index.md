---
title: "FileFormat.CanImport"
second_title: "Aspose.3D for .NET API 参考"
description: "FileFormat 属性。获取 Aspose.3D 是否支持从当前文件格式导入场景"
type: docs
weight: 490
url: /zh/net/aspose.threed/fileformat/canimport/
---
## FileFormat.CanImport property

获取 Aspose.3D 是否支持从当前文件格式导入场景。

```csharp
public bool CanImport { get; }
```

## 示例

以下代码展示了如何检查是否支持从指定格式导入。

```csharp
var outputFormat = ".glb";
var format = FileFormat.GetFormatByExtension(outputFormat);
if (format.CanImport)
    Console.WriteLine($"Can import from {outputFormat}");
```

### 另请参见

* class [FileFormat](../)
* namespace [Aspose.ThreeD](../../fileformat/)
* assembly [Aspose.3D](../../../)



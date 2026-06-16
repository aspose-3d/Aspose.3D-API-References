---
title: "类 XLoadOptions"
second_title: "Aspose.3D for .NET API 参考"
description: "Aspose.ThreeD.Formats.XLoadOptions 类。DirectX X 文件的加载选项"
type: docs
weight: 1550
url: /zh/net/aspose.threed.formats/xloadoptions/
---
## XLoadOptions class

DirectX X 文件的加载选项。

```csharp
public class XLoadOptions : LoadOptions
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [XLoadOptions](xloadoptions/)(FileContentType) | `XLoadOptions` 的构造函数 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [Encoding](../../aspose.threed.formats/ioconfig/encoding/) { get; set; } | 获取或设置基于文本文件的默认编码。默认值为 null，这意味着导入器/导出器将决定使用哪种编码。 |
| [FileFormat](../../aspose.threed.formats/ioconfig/fileformat/) { get; } | 获取当前保存/加载选项中指定的文件格式。 |
| [FileName](../../aspose.threed.formats/ioconfig/filename/) { get; set; } | 导出/导入场景的文件名。这是可选的，但在序列化外部资源（如 OBJ 的材质）时很有用。 |
| [FileSystem](../../aspose.threed.formats/ioconfig/filesystem/) { get; set; } | 允许用户处理在加载/保存期间如何管理外部依赖项。 |
| [FlipCoordinateSystem](../../aspose.threed.formats/xloadoptions/flipcoordinatesystem/) { get; set; } | 翻转坐标系，默认情况下为 true。 |
| [LookupPaths](../../aspose.threed.formats/ioconfig/lookuppaths/) { get; set; } | 某些文件（如 OBJ）依赖外部文件，查找路径将允许 Aspose.3D 查找并加载外部文件。 |

### 另请参见

* class [LoadOptions](../loadoptions/)
* namespace [Aspose.ThreeD.Formats](../../aspose.threed.formats/)
* assembly [Aspose.3D](../../)



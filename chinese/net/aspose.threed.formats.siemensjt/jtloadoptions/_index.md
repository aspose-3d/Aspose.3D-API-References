---
title: 类 JtLoadOptions
second_title: Aspose.3D for .NET API 参考手册
description: Aspose.ThreeD.Formats.SiemensJT.JtLoadOptions 类。Siemens JT 的加载选项
type: docs
weight: 1380
url: /zh/net/aspose.threed.formats.siemensjt/jtloadoptions/
---
## JtLoadOptions class

Siemens JT 的加载选项。

```csharp
public class JtLoadOptions : LoadOptions
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [JtLoadOptions](jtloadoptions/)() | 默认构造函数。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [Encoding](../../aspose.threed.formats/ioconfig/encoding/) { get; set; } | 获取或设置基于文本文件的默认编码。默认值为 null，表示导入器/导出器将决定使用哪种编码。（继承自 [`IOConfig`](../../aspose.threed.formats/ioconfig/)。） |
| [FileFormat](../../aspose.threed.formats/ioconfig/fileformat/) { get; } | 获取当前保存/加载选项中指定的文件格式。（继承自 [`IOConfig`](../../aspose.threed.formats/ioconfig/)。） |
| [FileName](../../aspose.threed.formats/ioconfig/filename/) { get; set; } | 导出/导入场景的文件名。此项可选，但在序列化外部资源（如 OBJ 的材质）时很有用。（继承自 [`IOConfig`](../../aspose.threed.formats/ioconfig/)。） |
| [FileSystem](../../aspose.threed.formats/ioconfig/filesystem/) { get; set; } | 允许用户处理在加载/保存期间如何管理外部依赖项。（继承自 [`IOConfig`](../../aspose.threed.formats/ioconfig/)。） |
| [LoadPMI](../../aspose.threed.formats.siemensjt/jtloadoptions/loadpmi/) { get; set; } | 如果可能，从 JT 文件加载 PMI 信息，数据将保存为 [`AssetInfo`](../../aspose.threed/scene/assetinfo/) 的 "PMI" 属性。默认值为 false。 |
| [LoadProperties](../../aspose.threed.formats.siemensjt/jtloadoptions/loadproperties/) { get; set; } | 将 JT 的属性表中的属性加载为 Aspose.3D 属性。默认值为 false。 |
| [LookupPaths](../../aspose.threed.formats/ioconfig/lookuppaths/) { get; set; } | 某些文件（如 OBJ）依赖外部文件，查找路径将允许 Aspose.3D 查找并加载外部文件。（继承自 [`IOConfig`](../../aspose.threed.formats/ioconfig/)。） |

### 另请参见

* class [LoadOptions](../../aspose.threed.formats/loadoptions/)
* namespace [Aspose.ThreeD.Formats.SiemensJT](../../aspose.threed.formats.siemensjt/)
* assembly [Aspose.3D](../../)



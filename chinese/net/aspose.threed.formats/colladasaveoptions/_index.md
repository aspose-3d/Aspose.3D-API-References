---
title: "ColladaSaveOptions 类"
second_title: "Aspose.3D for .NET API 参考"
description: "Aspose.ThreeD.Formats.ColladaSaveOptions 类。Collada 的保存选项"
type: docs
weight: 1100
url: /zh/net/aspose.threed.formats/colladasaveoptions/
---
## ColladaSaveOptions class

collada 的保存选项

```csharp
public class ColladaSaveOptions : SaveOptions
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [ColladaSaveOptions](colladasaveoptions/)() | `ColladaSaveOptions` 的构造函数 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [Encoding](../../aspose.threed.formats/ioconfig/encoding/) { get; set; } | 获取或设置基于文本文件的默认编码。默认值为 null，这意味着导入器/导出器将决定使用哪种编码。 |
| [ExportTextures](../../aspose.threed.formats/saveoptions/exporttextures/) { get; set; } | 尝试将场景中使用的纹理复制到输出目录。 |
| [FileFormat](../../aspose.threed.formats/ioconfig/fileformat/) { get; } | 获取当前保存/加载选项中指定的文件格式。 |
| [FileName](../../aspose.threed.formats/ioconfig/filename/) { get; set; } | 导出/导入场景的文件名。这是可选的，但在序列化外部资源（如 OBJ 的材质）时很有用。 |
| [FileSystem](../../aspose.threed.formats/ioconfig/filesystem/) { get; set; } | 允许用户处理在加载/保存期间如何管理外部依赖项。 |
| [Indented](../../aspose.threed.formats/colladasaveoptions/indented/) { get; set; } | 获取或设置导出的 XML 文档是否进行缩进。 |
| [LookupPaths](../../aspose.threed.formats/ioconfig/lookuppaths/) { get; set; } | 某些文件（如 OBJ）依赖外部文件，查找路径将允许 Aspose.3D 查找并加载外部文件。 |
| [TransformStyle](../../aspose.threed.formats/colladasaveoptions/transformstyle/) { get; set; } | 获取或设置节点变换的样式 |

### 另请参见

* class [SaveOptions](../saveoptions/)
* namespace [Aspose.ThreeD.Formats](../../aspose.threed.formats/)
* assembly [Aspose.3D](../../)



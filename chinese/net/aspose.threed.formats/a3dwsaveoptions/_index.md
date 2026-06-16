---
title: "A3dwSaveOptions 类"
second_title: "Aspose.3D for .NET API 参考"
description: "Aspose.ThreeD.Formats.A3dwSaveOptions 类。用于 A3DW 格式的保存选项"
type: docs
weight: 1080
url: /zh/net/aspose.threed.formats/a3dwsaveoptions/
---
## A3dwSaveOptions class

A3DW 格式的保存选项。

```csharp
public class A3dwSaveOptions : SaveOptions
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [A3dwSaveOptions](a3dwsaveoptions/)() | `A3dwSaveOptions` 的构造函数 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [Encoding](../../aspose.threed.formats/ioconfig/encoding/) { get; set; } | 获取或设置基于文本文件的默认编码。默认值为 null，这意味着导入器/导出器将决定使用哪种编码。 |
| [ExportMetaData](../../aspose.threed.formats/a3dwsaveoptions/exportmetadata/) { get; set; } | 导出与 Scene/Node 关联的元数据到客户端，默认值为 true |
| [ExportTextures](../../aspose.threed.formats/saveoptions/exporttextures/) { get; set; } | 尝试将场景中使用的纹理复制到输出目录。 |
| [FileFormat](../../aspose.threed.formats/ioconfig/fileformat/) { get; } | 获取当前保存/加载选项中指定的文件格式。 |
| [FileName](../../aspose.threed.formats/ioconfig/filename/) { get; set; } | 导出/导入场景的文件名。这是可选的，但在序列化外部资源（如 OBJ 的材质）时很有用。 |
| [FileSystem](../../aspose.threed.formats/ioconfig/filesystem/) { get; set; } | 允许用户处理在加载/保存期间如何管理外部依赖项。 |
| [LookupPaths](../../aspose.threed.formats/ioconfig/lookuppaths/) { get; set; } | 某些文件（如 OBJ）依赖外部文件，查找路径将允许 Aspose.3D 查找并加载外部文件。 |
| [MetaDataPrefix](../../aspose.threed.formats/a3dwsaveoptions/metadataprefix/) { get; set; } | 如果此属性非空，则仅导出以此前缀开头的 Scene/Node 属性，并且会去除该前缀。 |

### 另请参见

* class [SaveOptions](../saveoptions/)
* namespace [Aspose.ThreeD.Formats](../../aspose.threed.formats/)
* assembly [Aspose.3D](../../)



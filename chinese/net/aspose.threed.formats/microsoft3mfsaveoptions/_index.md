---
title: 类 Microsoft3MFSaveOptions
second_title: Aspose.3D for .NET API 参考手册
description: Aspose.ThreeD.Formats.Microsoft3MFSaveOptions 类。Microsoft 3MF 文件的保存选项
type: docs
weight: 1350
url: /zh/net/aspose.threed.formats/microsoft3mfsaveoptions/
---
## Microsoft3MFSaveOptions class

Microsoft 3MF 文件的保存选项。

```csharp
public class Microsoft3MFSaveOptions : SaveOptions
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [Microsoft3MFSaveOptions](microsoft3mfsaveoptions/)() | 构造一个 `Microsoft3MFSaveOptions` |

## 属性

| 名称 | 描述 |
| --- | --- |
| [BuildAll](../../aspose.threed.formats/microsoft3mfsaveoptions/buildall/) { get; set; } | 将场景中所有几何体标记为可打印。或者您可以通过 [`SetBuildable`](../microsoft3mfformat/setbuildable/) 手动将节点标记为可打印。默认值为 true。 |
| [EnableCompression](../../aspose.threed.formats/microsoft3mfsaveoptions/enablecompression/) { get; set; } | 在输出的 3mf 文件上启用压缩，默认值为 true。 |
| [Encoding](../../aspose.threed.formats/ioconfig/encoding/) { get; set; } | 获取或设置基于文本文件的默认编码。默认值为 null，表示导入器/导出器将决定使用哪种编码。 |
| [ExportTextures](../../aspose.threed.formats/saveoptions/exporttextures/) { get; set; } | 尝试将场景中使用的纹理复制到输出目录。 |
| [FileFormat](../../aspose.threed.formats/ioconfig/fileformat/) { get; } | 获取当前保存/加载选项中指定的文件格式。 |
| [FileName](../../aspose.threed.formats/ioconfig/filename/) { get; set; } | 导出/导入场景的文件名。此项是可选的，但在序列化外部资源（如 OBJ 的材质）时很有用。 |
| [FileSystem](../../aspose.threed.formats/ioconfig/filesystem/) { get; set; } | 允许用户处理在加载/保存期间如何管理外部依赖项。 |
| [LookupPaths](../../aspose.threed.formats/ioconfig/lookuppaths/) { get; set; } | 某些文件（如 OBJ）依赖外部文件，查找路径将允许 Aspose.3D 查找并加载外部文件。 |

### 另请参见

* class [SaveOptions](../saveoptions/)
* namespace [Aspose.ThreeD.Formats](../../aspose.threed.formats/)
* assembly [Aspose.3D](../../)



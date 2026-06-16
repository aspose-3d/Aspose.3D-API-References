---
title: "PdfSaveOptions 类"
second_title: "Aspose.3D for .NET API 参考"
description: "Aspose.ThreeD.Formats.PdfSaveOptions 类。PDF 导出时的保存选项"
type: docs
weight: 1420
url: /zh/net/aspose.threed.formats/pdfsaveoptions/
---
## PdfSaveOptions class

PDF 导出时的保存选项。

```csharp
public class PdfSaveOptions : SaveOptions
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [PdfSaveOptions](pdfsaveoptions/)() | `PdfSaveOptions` 的构造函数 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [AuxiliaryColor](../../aspose.threed.formats/pdfsaveoptions/auxiliarycolor/) { get; set; } | 获取或设置渲染 3D 内容时使用的辅助颜色。此颜色的解释取决于 [`RenderMode`](./rendermode/) |
| [BackgroundColor](../../aspose.threed.formats/pdfsaveoptions/backgroundcolor/) { get; set; } | PDF 文件中 3D 视图的背景颜色。 |
| [EmbedTextures](../../aspose.threed.formats/pdfsaveoptions/embedtextures/) { get; set; } | 将外部纹理嵌入 PDF 文件，默认值为 false。 |
| [Encoding](../../aspose.threed.formats/ioconfig/encoding/) { get; set; } | 获取或设置基于文本文件的默认编码。默认值为 null，这意味着导入器/导出器将决定使用哪种编码。 |
| [ExportTextures](../../aspose.threed.formats/saveoptions/exporttextures/) { get; set; } | 尝试将场景中使用的纹理复制到输出目录。 |
| [FaceColor](../../aspose.threed.formats/pdfsaveoptions/facecolor/) { get; set; } | 获取或设置渲染 3D 内容时使用的面颜色。仅在 [`RenderMode`](./rendermode/) 为 Illustration 时相关。 |
| [FileFormat](../../aspose.threed.formats/ioconfig/fileformat/) { get; } | 获取当前保存/加载选项中指定的文件格式。 |
| [FileName](../../aspose.threed.formats/ioconfig/filename/) { get; set; } | 导出/导入场景的文件名。这是可选的，但在序列化外部资源（如 OBJ 的材质）时很有用。 |
| [FileSystem](../../aspose.threed.formats/ioconfig/filesystem/) { get; set; } | 允许用户处理在加载/保存期间如何管理外部依赖项。 |
| [FlipCoordinateSystem](../../aspose.threed.formats/pdfsaveoptions/flipcoordinatesystem/) { get; set; } | 获取或设置在导出期间翻转场景的坐标系。 |
| [LightingScheme](../../aspose.threed.formats/pdfsaveoptions/lightingscheme/) { get; set; } | LightingScheme 指定要应用于 3D 艺术作品的光照。 |
| [LookupPaths](../../aspose.threed.formats/ioconfig/lookuppaths/) { get; set; } | 某些文件（如 OBJ）依赖外部文件，查找路径将允许 Aspose.3D 查找并加载外部文件。 |
| [RenderMode](../../aspose.threed.formats/pdfsaveoptions/rendermode/) { get; set; } | 渲染模式指定 3D 艺术作品的渲染风格。 |

### 另请参见

* class [SaveOptions](../saveoptions/)
* namespace [Aspose.ThreeD.Formats](../../aspose.threed.formats/)
* assembly [Aspose.3D](../../)



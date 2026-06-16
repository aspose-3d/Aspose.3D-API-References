---
title: "类 U3dSaveOptions"
second_title: "Aspose.3D for .NET API 参考"
description: "Aspose.ThreeD.Formats.U3dSaveOptions 类。通用 3D 的保存选项"
type: docs
weight: 1530
url: /zh/net/aspose.threed.formats/u3dsaveoptions/
---
## U3dSaveOptions class

通用 3d 的保存选项

```csharp
public class U3dSaveOptions : SaveOptions
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [U3dSaveOptions](u3dsaveoptions/)() | `U3dSaveOptions` 的构造函数 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [EmbedTextures](../../aspose.threed.formats/u3dsaveoptions/embedtextures/) { get; set; } | 将外部纹理嵌入 U3D 文件，默认值为 false。 |
| [Encoding](../../aspose.threed.formats/ioconfig/encoding/) { get; set; } | 获取或设置基于文本文件的默认编码。默认值为 null，这意味着导入器/导出器将决定使用哪种编码。 |
| [ExportNormals](../../aspose.threed.formats/u3dsaveoptions/exportnormals/) { get; set; } | 获取或设置是否导出法线数据。 |
| [ExportTextureCoordinates](../../aspose.threed.formats/u3dsaveoptions/exporttexturecoordinates/) { get; set; } | 获取或设置是否导出纹理坐标。 |
| [ExportTextures](../../aspose.threed.formats/saveoptions/exporttextures/) { get; set; } | 尝试将场景中使用的纹理复制到输出目录。 |
| [ExportVertexDiffuse](../../aspose.threed.formats/u3dsaveoptions/exportvertexdiffuse/) { get; set; } | 获取或设置是否导出顶点的漫反射颜色。 |
| [ExportVertexSpecular](../../aspose.threed.formats/u3dsaveoptions/exportvertexspecular/) { get; set; } | 获取或设置是否导出顶点的高光颜色。 |
| [FileFormat](../../aspose.threed.formats/ioconfig/fileformat/) { get; } | 获取当前保存/加载选项中指定的文件格式。 |
| [FileName](../../aspose.threed.formats/ioconfig/filename/) { get; set; } | 导出/导入场景的文件名。这是可选的，但在序列化外部资源（如 OBJ 的材质）时很有用。 |
| [FileSystem](../../aspose.threed.formats/ioconfig/filesystem/) { get; set; } | 允许用户处理在加载/保存期间如何管理外部依赖项。 |
| [FlipCoordinateSystem](../../aspose.threed.formats/u3dsaveoptions/flipcoordinatesystem/) { get; set; } | 获取或设置在导入/导出时是否翻转控制点/法线的坐标系。 |
| [LookupPaths](../../aspose.threed.formats/ioconfig/lookuppaths/) { get; set; } | 某些文件（如 OBJ）依赖外部文件，查找路径将允许 Aspose.3D 查找并加载外部文件。 |
| [MeshCompression](../../aspose.threed.formats/u3dsaveoptions/meshcompression/) { get; set; } | 获取或设置是否启用网格数据压缩。 |

### 另请参见

* class [SaveOptions](../saveoptions/)
* namespace [Aspose.ThreeD.Formats](../../aspose.threed.formats/)
* assembly [Aspose.3D](../../)



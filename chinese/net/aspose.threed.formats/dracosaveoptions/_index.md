---
title: "DracoSaveOptions 类"
second_title: "Aspose.3D for .NET API 参考"
description: "Aspose.ThreeD.Formats.DracoSaveOptions 类。用于 Google Draco 文件的保存选项"
type: docs
weight: 1160
url: /zh/net/aspose.threed.formats/dracosaveoptions/
---
## DracoSaveOptions class

Google Draco 文件的保存选项

```csharp
public class DracoSaveOptions : SaveOptions
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [DracoSaveOptions](dracosaveoptions/)() | 构建用于保存 Draco 文件的默认配置。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [ApplyUnitScale](../../aspose.threed.formats/dracosaveoptions/applyunitscale/) { get; set; } | 将 [`UnitScaleFactor`](../../aspose.threed/assetinfo/unitscalefactor/) 应用于网格。默认值为 false。 |
| [ColorBits](../../aspose.threed.formats/dracosaveoptions/colorbits/) { get; set; } | 顶点颜色的量化位数，默认值为 10 |
| [CompressionLevel](../../aspose.threed.formats/dracosaveoptions/compressionlevel/) { get; set; } | 压缩级别，默认值为 Standard |
| [Encoding](../../aspose.threed.formats/ioconfig/encoding/) { get; set; } | 获取或设置基于文本文件的默认编码。默认值为 null，这意味着导入器/导出器将决定使用哪种编码。 |
| [ExportTextures](../../aspose.threed.formats/saveoptions/exporttextures/) { get; set; } | 尝试将场景中使用的纹理复制到输出目录。 |
| [FileFormat](../../aspose.threed.formats/ioconfig/fileformat/) { get; } | 获取当前保存/加载选项中指定的文件格式。 |
| [FileName](../../aspose.threed.formats/ioconfig/filename/) { get; set; } | 导出/导入场景的文件名。这是可选的，但在序列化外部资源（如 OBJ 的材质）时很有用。 |
| [FileSystem](../../aspose.threed.formats/ioconfig/filesystem/) { get; set; } | 允许用户处理在加载/保存期间如何管理外部依赖项。 |
| [LookupPaths](../../aspose.threed.formats/ioconfig/lookuppaths/) { get; set; } | 某些文件（如 OBJ）依赖外部文件，查找路径将允许 Aspose.3D 查找并加载外部文件。 |
| [NormalBits](../../aspose.threed.formats/dracosaveoptions/normalbits/) { get; set; } | 法线向量的量化位数，默认值为 10 |
| [PointCloud](../../aspose.threed.formats/dracosaveoptions/pointcloud/) { get; set; } | 将场景导出为点云，默认值为 false。 |
| [PositionBits](../../aspose.threed.formats/dracosaveoptions/positionbits/) { get; set; } | 位置的量化位数，默认值为 14 |
| [TextureCoordinateBits](../../aspose.threed.formats/dracosaveoptions/texturecoordinatebits/) { get; set; } | 纹理坐标的量化位数，默认值为 12 |

### 另请参见

* class [SaveOptions](../saveoptions/)
* namespace [Aspose.ThreeD.Formats](../../aspose.threed.formats/)
* assembly [Aspose.3D](../../)



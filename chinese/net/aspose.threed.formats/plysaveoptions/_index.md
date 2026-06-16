---
title: "PlySaveOptions 类"
second_title: "Aspose.3D for .NET API 参考"
description: "Aspose.ThreeD.Formats.PlySaveOptions 类。用于将场景导出为 PLY 文件的保存选项"
type: docs
weight: 1450
url: /zh/net/aspose.threed.formats/plysaveoptions/
---
## PlySaveOptions class

导出场景为 PLY 文件的保存选项。

```csharp
public class PlySaveOptions : SaveOptions
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [PlySaveOptions](plysaveoptions/#constructor)() | `PlySaveOptions` 的构造函数 |
| [PlySaveOptions](plysaveoptions/#constructor_1)(FileContentType) | `PlySaveOptions` 的构造函数 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [AxisSystem](../../aspose.threed.formats/plysaveoptions/axissystem/) { get; set; } | 获取或设置导出 STL 文件中的坐标系。 |
| [ColorComponents](../../aspose.threed.formats/plysaveoptions/colorcomponents/) { get; set; } | 顶点颜色的组件名称，默认值为 (\"red\", \"green\", \"blue\") |
| [Encoding](../../aspose.threed.formats/ioconfig/encoding/) { get; set; } | 获取或设置基于文本文件的默认编码。默认值为 null，这意味着导入器/导出器将决定使用哪种编码。 |
| [ExportTextures](../../aspose.threed.formats/saveoptions/exporttextures/) { get; set; } | 尝试将场景中使用的纹理复制到输出目录。 |
| [FaceElement](../../aspose.threed.formats/plysaveoptions/faceelement/) { get; set; } | 面数据的元素名称，默认值为 \"face\" |
| [FaceProperty](../../aspose.threed.formats/plysaveoptions/faceproperty/) { get; set; } | 面数据的属性名称，默认值为 \"vertex_index\" |
| [FileFormat](../../aspose.threed.formats/ioconfig/fileformat/) { get; } | 获取当前保存/加载选项中指定的文件格式。 |
| [FileName](../../aspose.threed.formats/ioconfig/filename/) { get; set; } | 导出/导入场景的文件名。这是可选的，但在序列化外部资源（如 OBJ 的材质）时很有用。 |
| [FileSystem](../../aspose.threed.formats/ioconfig/filesystem/) { get; set; } | 允许用户处理在加载/保存期间如何管理外部依赖项。 |
| [FlipCoordinate](../../aspose.threed.formats/plysaveoptions/flipcoordinate/) { get; set; } | 保存场景时翻转坐标，默认值为 true |
| [LookupPaths](../../aspose.threed.formats/ioconfig/lookuppaths/) { get; set; } | 某些文件（如 OBJ）依赖外部文件，查找路径将允许 Aspose.3D 查找并加载外部文件。 |
| [NormalComponents](../../aspose.threed.formats/plysaveoptions/normalcomponents/) { get; set; } | 法线数据的组件名称，默认值为 (\"nx\", \"ny\", \"nz\") |
| [PointCloud](../../aspose.threed.formats/plysaveoptions/pointcloud/) { get; set; } | 将场景导出为点云，默认值为 false。 |
| [PositionComponents](../../aspose.threed.formats/plysaveoptions/positioncomponents/) { get; set; } | 位置数据的组件名称，默认值为 (\"x\", \"y\", \"z\") |
| [TextureCoordinateComponents](../../aspose.threed.formats/plysaveoptions/texturecoordinatecomponents/) { get; set; } | 纹理坐标数据的组件名称，默认值为 (\"u\", \"v\") |
| [VertexElement](../../aspose.threed.formats/plysaveoptions/vertexelement/) { get; set; } | 顶点数据的元素名称，默认值为 \"vertex\" |

### 另请参见

* class [SaveOptions](../saveoptions/)
* namespace [Aspose.ThreeD.Formats](../../aspose.threed.formats/)
* assembly [Aspose.3D](../../)



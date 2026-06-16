---
title: "类 ObjSaveOptions"
second_title: "Aspose.3D for .NET API 参考"
description: "Aspose.ThreeD.Formats.ObjSaveOptions 类。Wavefront OBJ 文件的保存选项。"
type: docs
weight: 1370
url: /zh/net/aspose.threed.formats/objsaveoptions/
---
## ObjSaveOptions class

wavefront obj 文件的保存选项

```csharp
public class ObjSaveOptions : SaveOptions
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [ObjSaveOptions](objsaveoptions/)() | `ObjSaveOptions` 的构造函数 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [ApplyUnitScale](../../aspose.threed.formats/objsaveoptions/applyunitscale/) { get; set; } | 将 [`UnitScaleFactor`](../../aspose.threed/assetinfo/unitscalefactor/) 应用于网格。默认值为 false。 |
| [AxisSystem](../../aspose.threed.formats/objsaveoptions/axissystem/) { get; set; } | 获取或设置导出文件中的坐标系。 |
| [EnableMaterials](../../aspose.threed.formats/objsaveoptions/enablematerials/) { get; set; } | 获取或设置是否为每个对象导入/导出材质。 |
| [Encoding](../../aspose.threed.formats/ioconfig/encoding/) { get; set; } | 获取或设置基于文本文件的默认编码。默认值为 null，这意味着导入器/导出器将决定使用哪种编码。 |
| [ExportTextures](../../aspose.threed.formats/saveoptions/exporttextures/) { get; set; } | 尝试将场景中使用的纹理复制到输出目录。 |
| [FileFormat](../../aspose.threed.formats/ioconfig/fileformat/) { get; } | 获取当前保存/加载选项中指定的文件格式。 |
| [FileName](../../aspose.threed.formats/ioconfig/filename/) { get; set; } | 导出/导入场景的文件名。这是可选的，但在序列化外部资源（如 OBJ 的材质）时很有用。 |
| [FileSystem](../../aspose.threed.formats/ioconfig/filesystem/) { get; set; } | 允许用户处理在加载/保存期间如何管理外部依赖项。 |
| [FlipCoordinateSystem](../../aspose.threed.formats/objsaveoptions/flipcoordinatesystem/) { get; set; } | 获取或设置在导入/导出时是否翻转控制点/法线的坐标系。 |
| [LookupPaths](../../aspose.threed.formats/ioconfig/lookuppaths/) { get; set; } | 某些文件（如 OBJ）依赖外部文件，查找路径将允许 Aspose.3D 查找并加载外部文件。 |
| [PointCloud](../../aspose.threed.formats/objsaveoptions/pointcloud/) { get; set; } | 获取或设置导出器是否应将场景导出为点云（无拓扑结构）的标志，默认值为 false。 |
| [SerializeW](../../aspose.threed.formats/objsaveoptions/serializew/) { get; set; } | 获取或设置是否在模型的顶点位置中序列化 W 分量。 |
| [Verbose](../../aspose.threed.formats/objsaveoptions/verbose/) { get; set; } | 获取或设置是否为每个部分生成注释。 |

### 另请参见

* class [SaveOptions](../saveoptions/)
* namespace [Aspose.ThreeD.Formats](../../aspose.threed.formats/)
* assembly [Aspose.3D](../../)



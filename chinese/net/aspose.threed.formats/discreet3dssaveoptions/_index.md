---
title: "Discreet3dsSaveOptions 类"
second_title: "Aspose.3D for .NET API 参考"
description: "Aspose.ThreeD.Formats.Discreet3dsSaveOptions 类。3DS 文件的保存选项"
type: docs
weight: 1130
url: /zh/net/aspose.threed.formats/discreet3dssaveoptions/
---
## Discreet3dsSaveOptions class

3DS 文件的保存选项。

```csharp
public class Discreet3dsSaveOptions : SaveOptions
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [Discreet3dsSaveOptions](discreet3dssaveoptions/)() | `Discreet3dsSaveOptions` 的构造函数 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [DuplicatedNameCounterBase](../../aspose.threed.formats/discreet3dssaveoptions/duplicatednamecounterbase/) { get; set; } | 用于为重复名称生成新名称的计数器，默认值为 2。 |
| [DuplicatedNameCounterFormat](../../aspose.threed.formats/discreet3dssaveoptions/duplicatednamecounterformat/) { get; set; } | 重复计数器的格式，默认值为空字符串。 |
| [DuplicatedNameSeparator](../../aspose.threed.formats/discreet3dssaveoptions/duplicatednameseparator/) { get; set; } | 对象名称与重复计数器之间的分隔符，默认值为 "_"。当场景中包含使用相同名称的对象时，Aspose.3D 3DS 导出器将为该对象生成不同的名称。例如，有两个名为 "Box" 的节点，第一个节点的名称为 "Box"，第二个节点将在默认配置下获得新名称 "Box_2"。 |
| [Encoding](../../aspose.threed.formats/ioconfig/encoding/) { get; set; } | 获取或设置基于文本文件的默认编码。默认值为 null，这意味着导入器/导出器将决定使用哪种编码。 |
| [ExportCamera](../../aspose.threed.formats/discreet3dssaveoptions/exportcamera/) { get; set; } | 获取或设置是否导出场景中的所有相机。 |
| [ExportLight](../../aspose.threed.formats/discreet3dssaveoptions/exportlight/) { get; set; } | 获取或设置是否导出场景中的所有灯光。 |
| [ExportTextures](../../aspose.threed.formats/saveoptions/exporttextures/) { get; set; } | 尝试将场景中使用的纹理复制到输出目录。 |
| [FileFormat](../../aspose.threed.formats/ioconfig/fileformat/) { get; } | 获取当前保存/加载选项中指定的文件格式。 |
| [FileName](../../aspose.threed.formats/ioconfig/filename/) { get; set; } | 导出/导入场景的文件名。这是可选的，但在序列化外部资源（如 OBJ 的材质）时很有用。 |
| [FileSystem](../../aspose.threed.formats/ioconfig/filesystem/) { get; set; } | 允许用户处理在加载/保存期间如何管理外部依赖项。 |
| [FlipCoordinateSystem](../../aspose.threed.formats/discreet3dssaveoptions/flipcoordinatesystem/) { get; set; } | 获取或设置在导入/导出期间翻转控制点/法线的坐标系。 |
| [GammaCorrectedColor](../../aspose.threed.formats/discreet3dssaveoptions/gammacorrectedcolor/) { get; set; } | 3ds 文件可能包含同一属性的原始颜色和伽马校正颜色，将此设置为 true 将在可能的情况下使用伽马校正颜色，否则 Aspose.3D 将尝试使用原始颜色。 |
| [HighPreciseColor](../../aspose.threed.formats/discreet3dssaveoptions/highprecisecolor/) { get; set; } | 如果设置为 true，生成的 3ds 文件将使用高精度颜色，即红/绿/蓝每个通道采用 32 位浮点。否则生成的文件将使用 24 位颜色，每个通道采用 8 位字节。默认值为 false，因为并非所有应用程序都支持高精度颜色。 |
| [LookupPaths](../../aspose.threed.formats/ioconfig/lookuppaths/) { get; set; } | 某些文件（如 OBJ）依赖外部文件，查找路径将允许 Aspose.3D 查找并加载外部文件。 |
| [MasterScale](../../aspose.threed.formats/discreet3dssaveoptions/masterscale/) { get; set; } | 获取或设置导出时使用的主比例。 |

### 另请参见

* class [SaveOptions](../saveoptions/)
* namespace [Aspose.ThreeD.Formats](../../aspose.threed.formats/)
* assembly [Aspose.3D](../../)



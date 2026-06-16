---
title: "类 Discreet3dsLoadOptions"
second_title: "Aspose.3D for .NET API 参考"
description: "Aspose.ThreeD.Formats.Discreet3dsLoadOptions 类。3DS 文件的加载选项。"
type: docs
weight: 1120
url: /zh/net/aspose.threed.formats/discreet3dsloadoptions/
---
## Discreet3dsLoadOptions class

3DS 文件的加载选项。

```csharp
public class Discreet3dsLoadOptions : LoadOptions
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [Discreet3dsLoadOptions](discreet3dsloadoptions/)() | `Discreet3dsLoadOptions` 的构造函数 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [ApplyAnimationTransform](../../aspose.threed.formats/discreet3dsloadoptions/applyanimationtransform/) { get; set; } | 获取或设置是否使用动画轨道第一帧中定义的变换。 |
| [Encoding](../../aspose.threed.formats/ioconfig/encoding/) { get; set; } | 获取或设置基于文本文件的默认编码。默认值为 null，这意味着导入器/导出器将决定使用哪种编码。 |
| [FileFormat](../../aspose.threed.formats/ioconfig/fileformat/) { get; } | 获取当前保存/加载选项中指定的文件格式。 |
| [FileName](../../aspose.threed.formats/ioconfig/filename/) { get; set; } | 导出/导入场景的文件名。这是可选的，但在序列化外部资源（如 OBJ 的材质）时很有用。 |
| [FileSystem](../../aspose.threed.formats/ioconfig/filesystem/) { get; set; } | 允许用户处理在加载/保存期间如何管理外部依赖项。 |
| [FlipCoordinateSystem](../../aspose.threed.formats/discreet3dsloadoptions/flipcoordinatesystem/) { get; set; } | 获取或设置在导入/导出期间翻转控制点/法线的坐标系。 |
| [GammaCorrectedColor](../../aspose.threed.formats/discreet3dsloadoptions/gammacorrectedcolor/) { get; set; } | 3ds 文件可能包含同一属性的原始颜色和伽马校正颜色，将此设置为 true 将在可能的情况下使用伽马校正颜色，否则 Aspose.3D 将尝试使用原始颜色。 |
| [LookupPaths](../../aspose.threed.formats/ioconfig/lookuppaths/) { get; set; } | 某些文件（如 OBJ）依赖外部文件，查找路径将允许 Aspose.3D 查找并加载外部文件。 |

### 另请参见

* class [LoadOptions](../loadoptions/)
* namespace [Aspose.ThreeD.Formats](../../aspose.threed.formats/)
* assembly [Aspose.3D](../../)



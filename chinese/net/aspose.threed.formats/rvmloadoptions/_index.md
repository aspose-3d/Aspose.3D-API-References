---
title: "类 RvmLoadOptions"
second_title: "Aspose.3D for .NET API 参考"
description: "Aspose.ThreeD.Formats.RvmLoadOptions 类。用于 AVEVA Plant Design Management Systems RVM 文件的加载选项"
type: docs
weight: 1470
url: /zh/net/aspose.threed.formats/rvmloadoptions/
---
## RvmLoadOptions class

AVEVA Plant Design Management System 的 RVM 文件加载选项。

```csharp
public class RvmLoadOptions : LoadOptions
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [RvmLoadOptions](rvmloadoptions/#constructor)() | 构造一个 `RvmLoadOptions` 实例 |
| [RvmLoadOptions](rvmloadoptions/#constructor_1)(FileContentType) | 构造一个 `RvmLoadOptions` 实例 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [AttributePrefix](../../aspose.threed.formats/rvmloadoptions/attributeprefix/) { get; set; } | 获取或设置在外部属性文件中定义的属性前缀，前缀用于避免名称冲突，默认值为 "rvm:" |
| [CenterScene](../../aspose.threed.formats/rvmloadoptions/centerscene/) { get; set; } | 加载后将场景居中。 |
| [CylinderRadialSegments](../../aspose.threed.formats/rvmloadoptions/cylinderradialsegments/) { get; set; } | 获取或设置圆柱体的径向段数，默认值为 16 |
| [DishLatitudeSegments](../../aspose.threed.formats/rvmloadoptions/dishlatitudesegments/) { get; set; } | 获取或设置碟形体的纬向段数，默认值为 8 |
| [DishLongitudeSegments](../../aspose.threed.formats/rvmloadoptions/dishlongitudesegments/) { get; set; } | 获取或设置碟形体的经向段数，默认值为 12 |
| [Encoding](../../aspose.threed.formats/ioconfig/encoding/) { get; set; } | 获取或设置基于文本文件的默认编码。默认值为 null，这意味着导入器/导出器将决定使用哪种编码。 |
| [FileFormat](../../aspose.threed.formats/ioconfig/fileformat/) { get; } | 获取当前保存/加载选项中指定的文件格式。 |
| [FileName](../../aspose.threed.formats/ioconfig/filename/) { get; set; } | 导出/导入场景的文件名。这是可选的，但在序列化外部资源（如 OBJ 的材质）时很有用。 |
| [FileSystem](../../aspose.threed.formats/ioconfig/filesystem/) { get; set; } | 允许用户处理在加载/保存期间如何管理外部依赖项。 |
| [GenerateMaterials](../../aspose.threed.formats/rvmloadoptions/generatematerials/) { get; set; } | 如果 RVM 文件中未导出颜色表，则为场景中的每个对象生成随机颜色的材质。默认值为 true |
| [LookupAttributes](../../aspose.threed.formats/rvmloadoptions/lookupattributes/) { get; set; } | 获取或设置是否从外部属性列表文件（.att/.attrib/.txt）加载属性，默认值为 true。 |
| [LookupPaths](../../aspose.threed.formats/ioconfig/lookuppaths/) { get; set; } | 某些文件（如 OBJ）依赖外部文件，查找路径将允许 Aspose.3D 查找并加载外部文件。 |
| [RectangularTorusSegments](../../aspose.threed.formats/rvmloadoptions/rectangulartorussegments/) { get; set; } | 获取或设置矩形环面的径向段数，默认值为 20 |
| [TorusTubularSegments](../../aspose.threed.formats/rvmloadoptions/torustubularsegments/) { get; set; } | 获取或设置环面的管线段数，默认值为 20 |

## 示例

以下代码展示了如何使用 RvmLoadOptions 自定义从 RVM 文件导入的原始几何体的细分参数。

```csharp
RvmLoadOptions opt = new RvmLoadOptions();
opt.RectangularTorusSegments = 30;
opt.CylinderRadialSegments = 20;
opt.DishLatitudeSegments = 20;
opt.DishLongitudeSegments = 20;
opt.CenterScene = true;
var scene = Scene.FromFile("input.rvm", opt);
scene.Save("output.obj");
```

### 另请参见

* class [LoadOptions](../loadoptions/)
* namespace [Aspose.ThreeD.Formats](../../aspose.threed.formats/)
* assembly [Aspose.3D](../../)



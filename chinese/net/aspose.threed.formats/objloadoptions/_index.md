---
title: "类 ObjLoadOptions"
second_title: "Aspose.3D for .NET API 参考"
description: "Aspose.ThreeD.Formats.ObjLoadOptions 类。wavefront obj 的加载选项。"
type: docs
weight: 1360
url: /zh/net/aspose.threed.formats/objloadoptions/
---
## ObjLoadOptions class

wavefront obj 的加载选项

```csharp
public class ObjLoadOptions : LoadOptions
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [ObjLoadOptions](objloadoptions/)() | `ObjLoadOptions` 的构造函数 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [EnableMaterials](../../aspose.threed.formats/objloadoptions/enablematerials/) { get; set; } | 获取或设置是否为每个对象导入材质 |
| [Encoding](../../aspose.threed.formats/ioconfig/encoding/) { get; set; } | 获取或设置基于文本文件的默认编码。默认值为 null，这意味着导入器/导出器将决定使用哪种编码。 |
| [FileFormat](../../aspose.threed.formats/ioconfig/fileformat/) { get; } | 获取当前保存/加载选项中指定的文件格式。 |
| [FileName](../../aspose.threed.formats/ioconfig/filename/) { get; set; } | 导出/导入场景的文件名。这是可选的，但在序列化外部资源（如 OBJ 的材质）时很有用。 |
| [FileSystem](../../aspose.threed.formats/ioconfig/filesystem/) { get; set; } | 允许用户处理在加载/保存期间如何管理外部依赖项。 |
| [FlipCoordinateSystem](../../aspose.threed.formats/objloadoptions/flipcoordinatesystem/) { get; set; } | 获取或设置在导入期间是否翻转控制点/法线的坐标系 |
| [LookupPaths](../../aspose.threed.formats/ioconfig/lookuppaths/) { get; set; } | 某些文件（如 OBJ）依赖外部文件，查找路径将允许 Aspose.3D 查找并加载外部文件。 |
| [NormalizeNormal](../../aspose.threed.formats/objloadoptions/normalizenormal/) { get; set; } | 获取或设置在加载期间是否归一化法向量。默认值为 true。 |
| [Scale](../../aspose.threed.formats/objloadoptions/scale/) { get; set; } | 在 x/y/z 轴上的缩放比例，默认值为 1.0 |

### 另请参见

* class [LoadOptions](../loadoptions/)
* namespace [Aspose.ThreeD.Formats](../../aspose.threed.formats/)
* assembly [Aspose.3D](../../)



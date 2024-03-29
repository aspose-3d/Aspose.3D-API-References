---
title: PlyLoadOptions
second_title: Aspose.3D for .NET API 参考
description: PLY 文件的加载选项
type: docs
weight: 1290
url: /zh/net/aspose.threed.formats/plyloadoptions/
---
## PlyLoadOptions class

PLY 文件的加载选项

```csharp
public class PlyLoadOptions : LoadOptions
```

## 构造函数

| 姓名 | 描述 |
| --- | --- |
| [PlyLoadOptions](plyloadoptions)() | 的构造函数[`PlyLoadOptions`](../plyloadoptions) |

## 特性

| 姓名 | 描述 |
| --- | --- |
| [Encoding](../../aspose.threed.formats/ioconfig/encoding) { get; set; } | 获取或设置基于文本的文件的默认编码。 默认值为 null，这意味着导入器/导出器将决定使用哪种编码。 |
| [FileFormat](../../aspose.threed.formats/ioconfig/fileformat) { get; } | 获取当前保存/加载选项中指定的文件格式。 |
| [FileName](../../aspose.threed.formats/ioconfig/filename) { get; set; } | 导出/导入场景的文件名。 这是可选的，但在序列化外部资产（如 OBJ 的材质）时很有用。 |
| [FileSystem](../../aspose.threed.formats/ioconfig/filesystem) { get; set; } | 允许用户在加载/保存期间处理如何管理外部依赖项。 |
| [FlipCoordinateSystem](../../aspose.threed.formats/plyloadoptions/flipcoordinatesystem) { get; set; } | 在导入/导出过程中获取或设置控制点/法线的翻转坐标系。 |
| [LookupPaths](../../aspose.threed.formats/ioconfig/lookuppaths) { get; set; } | 像 OBJ 这样的一些文件依赖于外部文件，查找路径将允许 Aspose.3D 查找要加载的外部文件。 |

### 也可以看看

* class [LoadOptions](../loadoptions)
* 命名空间 [Aspose.ThreeD.Formats](../../aspose.threed.formats)
* 部件 [Aspose.3D](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.3D.dll -->

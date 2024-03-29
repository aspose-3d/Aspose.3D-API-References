---
title: StlLoadOptions
second_title: Aspose.3D for .NET API 参考
description: STL 的加载选项
type: docs
weight: 1350
url: /zh/net/aspose.threed.formats/stlloadoptions/
---
## StlLoadOptions class

STL 的加载选项

```csharp
public class StlLoadOptions : LoadOptions
```

## 构造函数

| 姓名 | 描述 |
| --- | --- |
| [StlLoadOptions](stlloadoptions#constructor)() | 初始化一个新的[`StlLoadOptions`](../stlloadoptions)实例. |
| [StlLoadOptions](stlloadoptions#constructor_1)(FileContentType) | 初始化一个新的[`StlLoadOptions`](../stlloadoptions)实例. |

## 特性

| 姓名 | 描述 |
| --- | --- |
| [Encoding](../../aspose.threed.formats/ioconfig/encoding) { get; set; } | 获取或设置基于文本的文件的默认编码。 默认值为 null，这意味着导入器/导出器将决定使用哪种编码。 |
| [FileFormat](../../aspose.threed.formats/ioconfig/fileformat) { get; } | 获取当前保存/加载选项中指定的文件格式。 |
| [FileName](../../aspose.threed.formats/ioconfig/filename) { get; set; } | 导出/导入场景的文件名。 这是可选的，但在序列化外部资产（如 OBJ 的材质）时很有用。 |
| [FileSystem](../../aspose.threed.formats/ioconfig/filesystem) { get; set; } | 允许用户在加载/保存期间处理如何管理外部依赖项。 |
| [FlipCoordinateSystem](../../aspose.threed.formats/stlloadoptions/flipcoordinatesystem) { get; set; } | 获取或设置在导入时是否翻转控制点/法线的坐标系。 |
| [LookupPaths](../../aspose.threed.formats/ioconfig/lookuppaths) { get; set; } | 像 OBJ 这样的一些文件依赖于外部文件，查找路径将允许 Aspose.3D 查找要加载的外部文件。 |
| [RecalculateNormal](../../aspose.threed.formats/stlloadoptions/recalculatenormal) { get; set; } | 忽略存储在STL文件中的法线数据，根据顶点位置重新计算法线数据。 默认值为false |

### 也可以看看

* class [LoadOptions](../loadoptions)
* 命名空间 [Aspose.ThreeD.Formats](../../aspose.threed.formats)
* 部件 [Aspose.3D](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.3D.dll -->

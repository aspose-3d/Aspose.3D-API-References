---
title: "类 UsdSaveOptions"
second_title: "Aspose.3D for .NET API 参考"
description: "Aspose.ThreeD.Formats.UsdSaveOptions 类。USD/USDZ 格式的保存选项"
type: docs
weight: 1540
url: /zh/net/aspose.threed.formats/usdsaveoptions/
---
## UsdSaveOptions class

USD/USDZ 格式的保存选项。

```csharp
public class UsdSaveOptions : SaveOptions
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [UsdSaveOptions](usdsaveoptions/#constructor)() | 使用 [`USD`](../../aspose.threed/fileformat/usd/) 格式初始化新的 `UsdSaveOptions` |
| [UsdSaveOptions](usdsaveoptions/#constructor_1)(FileFormat) | 使用指定的 USD/USDZ 格式初始化新的 `UsdSaveOptions`。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [Encoding](../../aspose.threed.formats/ioconfig/encoding/) { get; set; } | 获取或设置基于文本文件的默认编码。默认值为 null，这意味着导入器/导出器将决定使用哪种编码。 |
| [ExportMetaData](../../aspose.threed.formats/usdsaveoptions/exportmetadata/) { get; set; } | 通过 USD 的 customData 字段导出节点属性。 |
| [ExportTextures](../../aspose.threed.formats/saveoptions/exporttextures/) { get; set; } | 尝试将场景中使用的纹理复制到输出目录。 |
| [FileFormat](../../aspose.threed.formats/ioconfig/fileformat/) { get; } | 获取当前保存/加载选项中指定的文件格式。 |
| [FileName](../../aspose.threed.formats/ioconfig/filename/) { get; set; } | 导出/导入场景的文件名。这是可选的，但在序列化外部资源（如 OBJ 的材质）时很有用。 |
| [FileSystem](../../aspose.threed.formats/ioconfig/filesystem/) { get; set; } | 允许用户处理在加载/保存期间如何管理外部依赖项。 |
| [LookupPaths](../../aspose.threed.formats/ioconfig/lookuppaths/) { get; set; } | 某些文件（如 OBJ）依赖外部文件，查找路径将允许 Aspose.3D 查找并加载外部文件。 |
| [MaterialConverter](../../aspose.threed.formats/usdsaveoptions/materialconverter/) { get; set; } | 自定义转换器，将几何体的材质转换为 PBR 材质。如果未分配，USD 导出器将自动将标准材质转换为 PBR 材质。默认值为 null |
| [PrimitiveToMesh](../../aspose.threed.formats/usdsaveoptions/primitivetomesh/) { get; set; } | 在导出期间将原始实体转换为网格。或者直接将原始实体编码到输出文件（将使用 Aspose 的扩展定义来处理非官方原始实体，如 Dish、Torus），默认值为 true。 |

### 另请参见

* class [SaveOptions](../saveoptions/)
* namespace [Aspose.ThreeD.Formats](../../aspose.threed.formats/)
* assembly [Aspose.3D](../../)



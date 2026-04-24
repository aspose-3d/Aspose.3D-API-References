---
title: Microsoft3MFFormat 类
second_title: Aspose.3D for .NET API 参考手册
description: Aspose.ThreeD.Formats.Microsoft3MFFormat 类。Microsoft 3MF 的文件格式实例，包含 3MF 相关工具
type: docs
weight: 1340
url: /zh/net/aspose.threed.formats/microsoft3mfformat/
---
## Microsoft3MFFormat class

Microsoft 3MF 文件格式实例，包含 3MF 相关工具。

```csharp
public class Microsoft3MFFormat : FileFormat
```

## 属性

| 名称 | 描述 |
| --- | --- |
| [CanExport](../../aspose.threed/fileformat/canexport/) { get; } | 获取 Aspose.3D 是否支持将场景导出为当前文件格式。 |
| [CanImport](../../aspose.threed/fileformat/canimport/) { get; } | 获取 Aspose.3D 是否支持从当前文件格式导入场景。 |
| [ContentType](../../aspose.threed/fileformat/contenttype/) { get; } | 获取文件格式的内容类型 |
| [Extension](../../aspose.threed/fileformat/extension/) { get; } | 获取此类型的扩展名。 |
| [Extensions](../../aspose.threed/fileformat/extensions/) { get; } | 获取此类型的扩展名列表。 |
| [FileFormatType](../../aspose.threed/fileformat/fileformattype/) { get; } | 获取文件格式类型 |
| [Version](../../aspose.threed/fileformat/version/) { get; } | 获取文件格式版本 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [CreateLoadOptions](../../aspose.threed/fileformat/createloadoptions/)() | 为此文件格式创建默认加载选项 |
| [CreateSaveOptions](../../aspose.threed/fileformat/createsaveoptions/)() | 为此文件格式创建默认保存选项 |
| [GetObjectType](../../aspose.threed.formats/microsoft3mfformat/getobjecttype/)(Node) | 获取指定节点的模型类型。 |
| [GetTransformForBuild](../../aspose.threed.formats/microsoft3mfformat/gettransformforbuild/)(Node) | 获取在构建中使用的节点的变换矩阵。 |
| [IsBuildable](../../aspose.threed.formats/microsoft3mfformat/isbuildable/)(Node) | 检查此节点是否标记为构建。 |
| [SetBuildable](../../aspose.threed.formats/microsoft3mfformat/setbuildable/)(Node, bool, Matrix4?) |  |
| [SetObjectType](../../aspose.threed.formats/microsoft3mfformat/setobjecttype/)(Node, string) | 设置指定节点的模型类型。可能的值：model surface solidsupport support other |
| override [ToString](../../aspose.threed/fileformat/tostring/)() | 将格式转换为字符串 |

### 另请参见

* class [FileFormat](../../aspose.threed/fileformat/)
* namespace [Aspose.ThreeD.Formats](../../aspose.threed.formats/)
* assembly [Aspose.3D](../../)



---
title: "类 DracoFormat"
second_title: "Aspose.3D for .NET API 参考"
description: "Aspose.ThreeD.Formats.DracoFormat 类。Google Draco 格式"
type: docs
weight: 1150
url: /zh/net/aspose.threed.formats/dracoformat/
---
## DracoFormat class

Google Draco 格式

```csharp
public class DracoFormat : FileFormat
```

## 属性

| 名称 | 描述 |
| --- | --- |
| [CanExport](../../aspose.threed/fileformat/canexport/) { get; } | 获取 Aspose.3D 是否支持将场景导出为当前文件格式。 |
| [CanImport](../../aspose.threed/fileformat/canimport/) { get; } | 获取 Aspose.3D 是否支持从当前文件格式导入场景。 |
| [ContentType](../../aspose.threed/fileformat/contenttype/) { get; } | 获取文件格式的内容类型 |
| [Extension](../../aspose.threed/fileformat/extension/) { get; } | 获取此类型的扩展名 |
| [Extensions](../../aspose.threed/fileformat/extensions/) { get; } | 获取此类型的扩展名列表 |
| [FileFormatType](../../aspose.threed/fileformat/fileformattype/) { get; } | 获取文件格式类型 |
| [Version](../../aspose.threed/fileformat/version/) { get; } | 获取文件格式版本 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [CreateLoadOptions](../../aspose.threed/fileformat/createloadoptions/)() | 为此文件格式创建默认的加载选项 |
| [CreateSaveOptions](../../aspose.threed/fileformat/createsaveoptions/)() | 为此文件格式创建默认的保存选项 |
| [Decode](../../aspose.threed.formats/dracoformat/decode/#decode)(byte[]) | 从内存数据解码点云或网格 |
| [Decode](../../aspose.threed.formats/dracoformat/decode/#decode_1)(string) | 从指定的文件名解码点云或网格 |
| [Encode](../../aspose.threed.formats/dracoformat/encode/#encode)(Entity, DracoSaveOptions) | 将实体编码为 Draco 原始数据 |
| [Encode](../../aspose.threed.formats/dracoformat/encode/#encode_1)(Entity, Stream, DracoSaveOptions) | 将实体编码到指定的流 |
| [Encode](../../aspose.threed.formats/dracoformat/encode/#encode_2)(Entity, string, DracoSaveOptions) | 将实体编码到指定的文件 |
| override [ToString](../../aspose.threed/fileformat/tostring/)() | 将格式转换为字符串 |

## 示例

以下代码展示了如何对 Mesh 进行编码和解码为/从字节数组：

```csharp
Mesh mesh = (new Sphere()).ToMesh();
//将网格编码为 Draco 格式
byte[] draco = FileFormat.Draco.Encode(mesh);
//从 Draco 格式解码网格
Mesh decodedMesh = (Mesh)FileFormat.Draco.Decode(draco);
```

### 另请参见

* class [FileFormat](../../aspose.threed/fileformat/)
* namespace [Aspose.ThreeD.Formats](../../aspose.threed.formats/)
* assembly [Aspose.3D](../../)



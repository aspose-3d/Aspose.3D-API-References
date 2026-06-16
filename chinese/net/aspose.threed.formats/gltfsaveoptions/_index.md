---
title: "类 GltfSaveOptions"
second_title: "Aspose.3D for .NET API 参考"
description: "Aspose.ThreeD.Formats.GltfSaveOptions 类。glTF 格式的保存选项"
type: docs
weight: 1280
url: /zh/net/aspose.threed.formats/gltfsaveoptions/
---
## GltfSaveOptions class

glTF 格式的保存选项。

```csharp
public class GltfSaveOptions : SaveOptions
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [GltfSaveOptions](gltfsaveoptions/#constructor)(FileContentType) | `GltfSaveOptions` 的构造函数 |
| [GltfSaveOptions](gltfsaveoptions/#constructor_1)(FileFormat) | `GltfSaveOptions` 的构造函数 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [ApplyUnitScale](../../aspose.threed.formats/gltfsaveoptions/applyunitscale/) { get; set; } | 将 [`UnitScaleFactor`](../../aspose.threed/assetinfo/unitscalefactor/) 应用于网格。默认值为 false。 |
| [BufferFile](../../aspose.threed.formats/gltfsaveoptions/bufferfile/) { get; set; } | 用于存储二进制数据的外部缓冲文件的文件名。如果未指定此文件，Aspose.3D 将为您生成一个名称。在二进制模式导出 glTF 时此设置将被忽略。 |
| [DracoCompression](../../aspose.threed.formats/gltfsaveoptions/dracocompression/) { get; set; } | 获取或设置是否启用 draco 压缩 |
| [EmbedAssets](../../aspose.threed.formats/gltfsaveoptions/embedassets/) { get; set; } | 以 ASCII 模式将所有外部资源嵌入为 base64 到单个文件中，默认值为 false。 |
| [Encoding](../../aspose.threed.formats/ioconfig/encoding/) { get; set; } | 获取或设置基于文本文件的默认编码。默认值为 null，这意味着导入器/导出器将决定使用哪种编码。 |
| [ExportTextures](../../aspose.threed.formats/saveoptions/exporttextures/) { get; set; } | 尝试将场景中使用的纹理复制到输出目录。 |
| [ExternalDracoEncoder](../../aspose.threed.formats/gltfsaveoptions/externaldracoencoder/) { get; set; } | 使用外部 draco 编码器来加速 draco 压缩速度。 |
| [FallbackNormal](../../aspose.threed.formats/gltfsaveoptions/fallbacknormal/) { get; set; } | 当 GLTF2 导出器检测到无效法线时，将使用此值替代原始值以绕过验证。默认值为 (0, 1, 0)。 |
| [FileFormat](../../aspose.threed.formats/ioconfig/fileformat/) { get; } | 获取当前保存/加载选项中指定的文件格式。 |
| [FileName](../../aspose.threed.formats/ioconfig/filename/) { get; set; } | 导出/导入场景的文件名。这是可选的，但在序列化外部资源（如 OBJ 的材质）时很有用。 |
| [FileSystem](../../aspose.threed.formats/ioconfig/filesystem/) { get; set; } | 允许用户处理在加载/保存期间如何管理外部依赖项。 |
| [FlipTexCoordV](../../aspose.threed.formats/gltfsaveoptions/fliptexcoordv/) { get; set; } | 翻转纹理坐标 v(t) 分量，默认值为 true。 |
| [ImageFormat](../../aspose.threed.formats/gltfsaveoptions/imageformat/) { get; set; } | 标准 glTF 仅支持 PNG/JPG 作为纹理格式，此选项将指导 Aspose.3D 在导出期间如何将非标准图像转换为支持的格式。默认值为 Png。 |
| [LookupPaths](../../aspose.threed.formats/ioconfig/lookuppaths/) { get; set; } | 某些文件（如 OBJ）依赖外部文件，查找路径将允许 Aspose.3D 查找并加载外部文件。 |
| [MaterialConverter](../../aspose.threed.formats/gltfsaveoptions/materialconverter/) { get; set; } | 自定义转换器用于将几何体的材质转换为 PBR 材质。如果未分配此转换器，glTF 2.0 导出器将自动将标准材质转换为 PBR 材质。默认值为 null。此属性在将场景导出为 glTF 2.0 文件时使用。 |
| [PrettyPrint](../../aspose.threed.formats/gltfsaveoptions/prettyprint/) { get; set; } | GLTF 文件的 JSON 内容已缩进以便人工阅读，默认值为 false。 |
| [SaveExtras](../../aspose.threed.formats/gltfsaveoptions/saveextras/) { get; set; } | 将场景对象的动态属性保存到生成的 glTF 文件中的 'extra' 字段中。这对于提供特定应用程序的数据很有用。默认值为 false。 |
| [UseCommonMaterials](../../aspose.threed.formats/gltfsaveoptions/usecommonmaterials/) { get; set; } | 使用 KHR 通用材质扩展序列化材质，默认值为 false。将此设置为 false 将导致 Aspose.3D 在 ExportShaders 时导出一套顶点/片段着色器。 |

### 另请参见

* class [SaveOptions](../saveoptions/)
* namespace [Aspose.ThreeD.Formats](../../aspose.threed.formats/)
* assembly [Aspose.3D](../../)



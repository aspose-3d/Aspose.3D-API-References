---
title: "类 FbxSaveOptions"
second_title: "Aspose.3D for .NET API 参考"
description: "Aspose.ThreeD.Formats.FbxSaveOptions 类。Fbx 文件的保存选项"
type: docs
weight: 1180
url: /zh/net/aspose.threed.formats/fbxsaveoptions/
---
## FbxSaveOptions class

Fbx 文件的保存选项。

```csharp
public class FbxSaveOptions : SaveOptions
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [FbxSaveOptions](fbxsaveoptions/#constructor)(FileContentType) | 使用最新支持的版本初始化 `FbxSaveOptions`。 |
| [FbxSaveOptions](fbxsaveoptions/#constructor_1)(FileFormat) | 初始化 `FbxSaveOptions` |

## 属性

| 名称 | 描述 |
| --- | --- |
| [EmbedTextures](../../aspose.threed.formats/fbxsaveoptions/embedtextures/) { get; set; } | 获取或设置是否将纹理嵌入最终输出文件。FBX 导出器将尝试从 [`FileSystem`](../ioconfig/filesystem/) 中获取纹理的原始数据，并将文件嵌入最终的 FBX 文件。默认值为 false。 |
| [EnableCompression](../../aspose.threed.formats/fbxsaveoptions/enablecompression/) { get; set; } | 压缩 FBX 文件中的大型二进制数据（例如动画数据、控制点、顶点元素数据、索引），默认值为 true。 |
| [Encoding](../../aspose.threed.formats/ioconfig/encoding/) { get; set; } | 获取或设置基于文本文件的默认编码。默认值为 null，这意味着导入器/导出器将决定使用哪种编码。 |
| [ExportLegacyMaterialProperties](../../aspose.threed.formats/fbxsaveoptions/exportlegacymaterialproperties/) { get; set; } | 获取或设置是否导出旧版材质属性，用于向后兼容。此选项默认开启。 |
| [ExportTextures](../../aspose.threed.formats/saveoptions/exporttextures/) { get; set; } | 尝试将场景中使用的纹理复制到输出目录。 |
| [FileFormat](../../aspose.threed.formats/ioconfig/fileformat/) { get; } | 获取当前保存/加载选项中指定的文件格式。 |
| [FileName](../../aspose.threed.formats/ioconfig/filename/) { get; set; } | 导出/导入场景的文件名。这是可选的，但在序列化外部资源（如 OBJ 的材质）时很有用。 |
| [FileSystem](../../aspose.threed.formats/ioconfig/filesystem/) { get; set; } | 允许用户处理在加载/保存期间如何管理外部依赖项。 |
| [FoldRepeatedCurveData](../../aspose.threed.formats/fbxsaveoptions/foldrepeatedcurvedata/) { get; set; } | 获取或设置是否通过增加上一次数据的引用计数来复用重复的曲线数据 |
| [GenerateVertexElementMaterial](../../aspose.threed.formats/fbxsaveoptions/generatevertexelementmaterial/) { get; set; } | 获取或设置是否在附加节点包含材质时始终为几何体生成 [`VertexElementMaterial`](../../aspose.threed.entities/vertexelementmaterial/)。此选项默认关闭。 |
| [LookupPaths](../../aspose.threed.formats/ioconfig/lookuppaths/) { get; set; } | 某些文件（如 OBJ）依赖外部文件，查找路径将允许 Aspose.3D 查找并加载外部文件。 |
| [ReusePrimitiveMesh](../../aspose.threed.formats/fbxsaveoptions/reuseprimitivemesh/) { get; set; } | 对具有相同参数的原语复用网格，这将显著减小由大量原始形状（如从 CAD 文件导入）构建的场景的 FBX 输出大小。默认值为 false |
| [VideoForTexture](../../aspose.threed.formats/fbxsaveoptions/videofortexture/) { get; set; } | 获取或设置在导出为 FBX 时是否为 [`Texture`](../../aspose.threed.shading/texture/) 生成 Video 实例。 |

### 另请参见

* class [SaveOptions](../saveoptions/)
* namespace [Aspose.ThreeD.Formats](../../aspose.threed.formats/)
* assembly [Aspose.3D](../../)



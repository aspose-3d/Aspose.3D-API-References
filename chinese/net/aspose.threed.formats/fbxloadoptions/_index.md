---
title: "类 FbxLoadOptions"
second_title: "Aspose.3D for .NET API 参考"
description: "Aspose.ThreeD.Formats.FbxLoadOptions 类。Fbx 格式的加载选项"
type: docs
weight: 1170
url: /zh/net/aspose.threed.formats/fbxloadoptions/
---
## FbxLoadOptions class

Fbx 格式的加载选项。

```csharp
public class FbxLoadOptions : LoadOptions
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [FbxLoadOptions](fbxloadoptions/#constructor)() | `FbxLoadOptions` 的构造函数 |
| [FbxLoadOptions](fbxloadoptions/#constructor_1)(FileFormat) | `FbxLoadOptions` 的构造函数 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [CompatibleMode](../../aspose.threed.formats/fbxloadoptions/compatiblemode/) { get; set; } | 获取或设置是否启用兼容模式。兼容模式将尝试支持非标准的 FBX 定义，例如 Blender 导出的 PBR 材质。默认值为 false。 |
| [Encoding](../../aspose.threed.formats/ioconfig/encoding/) { get; set; } | 获取或设置基于文本文件的默认编码。默认值为 null，这意味着导入器/导出器将决定使用哪种编码。 |
| [FileFormat](../../aspose.threed.formats/ioconfig/fileformat/) { get; } | 获取当前保存/加载选项中指定的文件格式。 |
| [FileName](../../aspose.threed.formats/ioconfig/filename/) { get; set; } | 导出/导入场景的文件名。这是可选的，但在序列化外部资源（如 OBJ 的材质）时很有用。 |
| [FileSystem](../../aspose.threed.formats/ioconfig/filesystem/) { get; set; } | 允许用户处理在加载/保存期间如何管理外部依赖项。 |
| [KeepBuiltinGlobalSettings](../../aspose.threed.formats/fbxloadoptions/keepbuiltinglobalsettings/) { get; set; } | 获取或设置是否保留在 GlobalSettings 中具有原生属性替代的内置属性，这些属性在 [`AssetInfo`](../../aspose.threed/assetinfo/) 中有替代。若希望在 GlobalSettings 中保留完整属性，请将其设为 true。默认值为 false |
| [LookupPaths](../../aspose.threed.formats/ioconfig/lookuppaths/) { get; set; } | 某些文件（如 OBJ）依赖外部文件，查找路径将允许 Aspose.3D 查找并加载外部文件。 |

### 另请参见

* class [LoadOptions](../loadoptions/)
* namespace [Aspose.ThreeD.Formats](../../aspose.threed.formats/)
* assembly [Aspose.3D](../../)



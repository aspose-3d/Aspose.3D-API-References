---
title: "类 RvmSaveOptions"
second_title: "Aspose.3D for .NET API 参考"
description: "Aspose.ThreeD.Formats.RvmSaveOptions 类。Aveva PDMS RVM 文件的保存选项"
type: docs
weight: 1480
url: /zh/net/aspose.threed.formats/rvmsaveoptions/
---
## RvmSaveOptions class

Aveva PDMS RVM 文件的保存选项。

```csharp
public class RvmSaveOptions : SaveOptions
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [RvmSaveOptions](rvmsaveoptions/#constructor)() | `RvmSaveOptions` 的构造函数 |
| [RvmSaveOptions](rvmsaveoptions/#constructor_1)(FileContentType) | `RvmSaveOptions` 的构造函数 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [AttributeListFile](../../aspose.threed.formats/rvmsaveoptions/attributelistfile/) { get; set; } | 获取或设置属性列表文件的文件名；当此属性未定义时，导出器将根据 .rvm 文件名生成名称，默认值为 null。 |
| [AttributePrefix](../../aspose.threed.formats/rvmsaveoptions/attributeprefix/) { get; set; } | 获取或设置将被导出的属性前缀，导出的属性将不包含前缀，具有不同前缀的自定义属性将不会被导出，默认值为 'rvm:'。例如，如果属性为 rvm:Refno=345，导出的属性将为 Refno = 345，前缀被去除。 |
| [Author](../../aspose.threed.formats/rvmsaveoptions/author/) { get; set; } | 作者信息，默认值为 '3d@aspose' |
| [CreationTime](../../aspose.threed.formats/rvmsaveoptions/creationtime/) { get; set; } | 导出此文件的时间戳，默认值为当前时间 |
| [Encoding](../../aspose.threed.formats/ioconfig/encoding/) { get; set; } | 获取或设置基于文本文件的默认编码。默认值为 null，这意味着导入器/导出器将决定使用哪种编码。 |
| [ExportAttributes](../../aspose.threed.formats/rvmsaveoptions/exportattributes/) { get; set; } | 获取或设置是否将属性列表导出到外部 .att 文件，默认值为 false。 |
| [ExportTextures](../../aspose.threed.formats/saveoptions/exporttextures/) { get; set; } | 尝试将场景中使用的纹理复制到输出目录。 |
| [FileFormat](../../aspose.threed.formats/ioconfig/fileformat/) { get; } | 获取当前保存/加载选项中指定的文件格式。 |
| [FileName](../../aspose.threed.formats/ioconfig/filename/) { get; set; } | 导出/导入场景的文件名。这是可选的，但在序列化外部资源（如 OBJ 的材质）时很有用。 |
| [FileNote](../../aspose.threed.formats/rvmsaveoptions/filenote/) { get; set; } | 文件头中的文件备注。 |
| [FileSystem](../../aspose.threed.formats/ioconfig/filesystem/) { get; set; } | 允许用户处理在加载/保存期间如何管理外部依赖项。 |
| [LookupPaths](../../aspose.threed.formats/ioconfig/lookuppaths/) { get; set; } | 某些文件（如 OBJ）依赖外部文件，查找路径将允许 Aspose.3D 查找并加载外部文件。 |

## 示例

以下代码展示了如何在 RVM 中导出属性。

```csharp
Scene scene = new Scene();
var box = new Box().ToMesh();
//导出属性需要节点名称
var boxNode = scene.RootNode.CreateChildNode("box", box);
boxNode.SetProperty("rvm:Price", 12.0);
boxNode.SetProperty("rvm:Weight", 30.0);
var opt = new RvmSaveOptions();
//带有 rvm: 前缀的属性将被导出。
opt.ExportAttributes = true;
opt.AttributePrefix = "rvm:";
opt.Author = "Aspose.3D";
opt.FileNote = "Test attribute export";
scene.Save("output.rvm", opt);
```

### 另请参见

* class [SaveOptions](../saveoptions/)
* namespace [Aspose.ThreeD.Formats](../../aspose.threed.formats/)
* assembly [Aspose.3D](../../)



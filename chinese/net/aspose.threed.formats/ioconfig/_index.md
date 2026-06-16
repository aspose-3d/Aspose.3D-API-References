---
title: "类 IOConfig"
second_title: "Aspose.3D for .NET API 参考"
description: "Aspose.ThreeD.Formats.IOConfig 类。用于序列化/反序列化的 IO 配置。用户可以在此指定详细配置，例如依赖查找路径或与格式相关的配置。"
type: docs
weight: 1300
url: /zh/net/aspose.threed.formats/ioconfig/
---
## IOConfig class

用于序列化/反序列化的 IO 配置。用户可以在此指定详细的配置，例如依赖查找路径或与格式相关的配置。

```csharp
public class IOConfig
```

## 属性

| 名称 | 描述 |
| --- | --- |
| [Encoding](../../aspose.threed.formats/ioconfig/encoding/) { get; set; } | 获取或设置基于文本文件的默认编码。默认值为 null，这意味着导入器/导出器将决定使用哪种编码。 |
| [FileFormat](../../aspose.threed.formats/ioconfig/fileformat/) { get; } | 获取当前保存/加载选项中指定的文件格式。 |
| [FileName](../../aspose.threed.formats/ioconfig/filename/) { get; set; } | 导出/导入场景的文件名。这是可选的，但在序列化外部资源（如 OBJ 的材质）时很有用。 |
| [FileSystem](../../aspose.threed.formats/ioconfig/filesystem/) { get; set; } | 允许用户处理在加载/保存期间如何管理外部依赖项。 |
| [LookupPaths](../../aspose.threed.formats/ioconfig/lookuppaths/) { get; set; } | 某些文件（如 OBJ）依赖外部文件，查找路径将允许 Aspose.3D 查找并加载外部文件。 |
| static [FileSystemFactory](../../aspose.threed.formats/ioconfig/filesystemfactory/) { get; set; } | 获取或设置 FileSystem 的工厂类。默认工厂将创建 LocalFileSystem，但它不适用于服务器环境。 |

### 另请参见

* namespace [Aspose.ThreeD.Formats](../../aspose.threed.formats/)
* assembly [Aspose.3D](../../)



---
title: "类 Html5SaveOptions"
second_title: "Aspose.3D for .NET API 参考"
description: "Aspose.ThreeD.Formats.Html5SaveOptions 类。HTML5 的保存选项"
type: docs
weight: 1290
url: /zh/net/aspose.threed.formats/html5saveoptions/
---
## Html5SaveOptions class

HTML5 的保存选项

```csharp
public class Html5SaveOptions : SaveOptions
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [Html5SaveOptions](html5saveoptions/)() | `Html5SaveOptions` 的构造函数，使用所有默认设置。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [CameraPosition](../../aspose.threed.formats/html5saveoptions/cameraposition/) { get; set; } | 获取或设置相机的初始位置，默认值为 (10, 10, 10) |
| [Encoding](../../aspose.threed.formats/ioconfig/encoding/) { get; set; } | 获取或设置基于文本文件的默认编码。默认值为 null，这意味着导入器/导出器将决定使用哪种编码。 |
| [ExportTextures](../../aspose.threed.formats/saveoptions/exporttextures/) { get; set; } | 尝试将场景中使用的纹理复制到输出目录。 |
| [FarPlane](../../aspose.threed.formats/html5saveoptions/farplane/) { get; set; } | 获取或设置相机的远裁剪面，默认值为 1000。 |
| [FieldOfView](../../aspose.threed.formats/html5saveoptions/fieldofview/) { get; set; } | 获取或设置视场角，默认值为 45，单位为度。 |
| [FileFormat](../../aspose.threed.formats/ioconfig/fileformat/) { get; } | 获取当前保存/加载选项中指定的文件格式。 |
| [FileName](../../aspose.threed.formats/ioconfig/filename/) { get; set; } | 导出/导入场景的文件名。这是可选的，但在序列化外部资源（如 OBJ 的材质）时很有用。 |
| [FileSystem](../../aspose.threed.formats/ioconfig/filesystem/) { get; set; } | 允许用户处理在加载/保存期间如何管理外部依赖项。 |
| [LookAt](../../aspose.threed.formats/html5saveoptions/lookat/) { get; set; } | 获取或设置默认的观察位置，默认值为 (0, 0, 0) |
| [LookupPaths](../../aspose.threed.formats/ioconfig/lookuppaths/) { get; set; } | 某些文件（如 OBJ）依赖外部文件，查找路径将允许 Aspose.3D 查找并加载外部文件。 |
| [NearPlane](../../aspose.threed.formats/html5saveoptions/nearplane/) { get; set; } | 获取或设置相机的近裁剪面，默认值为 1 |
| [OrientationBox](../../aspose.threed.formats/html5saveoptions/orientationbox/) { get; set; } | 显示方向框。默认值为 true。 |
| [ShowGrid](../../aspose.threed.formats/html5saveoptions/showgrid/) { get; set; } | 在场景中显示网格。默认值为 true。 |
| [ShowRulers](../../aspose.threed.formats/html5saveoptions/showrulers/) { get; set; } | 在场景中显示 x/y/z 轴的标尺以测量模型。默认值为 false。 |
| [ShowUI](../../aspose.threed.formats/html5saveoptions/showui/) { get; set; } | 在场景中显示简易 UI。默认值为 true。 |
| [UpVector](../../aspose.threed.formats/html5saveoptions/upvector/) { get; set; } | 获取或设置上向量，取值可以是 "x"/"y"/"z"，默认值为 "y" |

### 另请参见

* class [SaveOptions](../saveoptions/)
* namespace [Aspose.ThreeD.Formats](../../aspose.threed.formats/)
* assembly [Aspose.3D](../../)



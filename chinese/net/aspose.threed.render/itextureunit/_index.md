---
title: "接口 ITextureUnit"
second_title: "Aspose.3D for .NET API 参考"
description: "Aspose.ThreeD.Render.ITextureUnit 接口。ITextureUnit 表示内存中的纹理，该纹理在 GPU 和 CPU 之间共享，并可被着色器采样，而 Texture 仅表示对外部文件的引用。更多细节可参见 https//en.wikipedia.org/wiki/Texture_mapping_unit"
type: docs
weight: 2170
url: /zh/net/aspose.threed.render/itextureunit/
---
## ITextureUnit interface

`ITextureUnit` 表示内存中的纹理，该纹理在 GPU 和 CPU 之间共享，并可被着色器采样，其中 [`Texture`](../../aspose.threed.shading/texture/) 仅表示对外部文件的引用。更多细节可参见 https://en.wikipedia.org/wiki/Texture_mapping_unit

```csharp
public interface ITextureUnit : IDisposable
```

## 属性

| 名称 | 描述 |
| --- | --- |
| [Depth](../../aspose.threed.render/itextureunit/depth/) { get; } | 获取此纹理的高度，对于非 3D 纹理始终为 1。 |
| [Height](../../aspose.threed.render/itextureunit/height/) { get; } | 获取此纹理的高度。 |
| [Magnification](../../aspose.threed.render/itextureunit/magnification/) { get; set; } | 获取或设置放大过滤模式。 |
| [Minification](../../aspose.threed.render/itextureunit/minification/) { get; set; } | 获取或设置缩小过滤模式。 |
| [Mipmap](../../aspose.threed.render/itextureunit/mipmap/) { get; set; } | 获取或设置 mipmap 过滤模式。 |
| [Scale](../../aspose.threed.render/itextureunit/scale/) { get; set; } | 获取或设置 UV 坐标的缩放比例。 |
| [Scroll](../../aspose.threed.render/itextureunit/scroll/) { get; set; } | 获取或设置 UV 坐标的滚动。 |
| [Type](../../aspose.threed.render/itextureunit/type/) { get; } | 获取此纹理单元的类型。 |
| [UWrap](../../aspose.threed.render/itextureunit/uwrap/) { get; set; } | 获取或设置纹理 U 坐标的环绕模式。 |
| [VWrap](../../aspose.threed.render/itextureunit/vwrap/) { get; set; } | 获取或设置纹理 V 坐标的环绕模式。 |
| [Width](../../aspose.threed.render/itextureunit/width/) { get; } | 获取此纹理的宽度。 |
| [WWrap](../../aspose.threed.render/itextureunit/wwrap/) { get; set; } | 获取或设置纹理 W 坐标的环绕模式。 |

### 另请参见

* namespace [Aspose.ThreeD.Render](../../aspose.threed.render/)
* assembly [Aspose.3D](../../)



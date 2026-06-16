---
title: "接口 IRenderTarget"
second_title: "Aspose.3D for .NET API 参考"
description: "Aspose.ThreeD.Render.IRenderTarget 接口。渲染目标的基础接口"
type: docs
weight: 2080
url: /zh/net/aspose.threed.render/irendertarget/
---
## IRenderTarget interface

渲染目标的基础接口

```csharp
public interface IRenderTarget : IDisposable
```

## 属性

| 名称 | 描述 |
| --- | --- |
| [Size](../../aspose.threed.render/irendertarget/size/) { get; set; } | 获取或设置渲染目标的大小。 |
| [Viewports](../../aspose.threed.render/irendertarget/viewports/) { get; } | 获取与此渲染目标关联的所有视口。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [CreateViewport](../../aspose.threed.render/irendertarget/createviewport/#createviewport)(Camera) | 在指定的相机视角中创建视口。 |
| [CreateViewport](../../aspose.threed.render/irendertarget/createviewport/#createviewport_1)(Camera, RelativeRectangle) | 在指定的相机视角中创建具有位置/大小的视口。 |
| [CreateViewport](../../aspose.threed.render/irendertarget/createviewport/#createviewport_2)(Camera, Vector3, RelativeRectangle) | 在指定的相机视角中创建具有指定背景颜色和位置/大小的视口。 |

### 另请参见

* namespace [Aspose.ThreeD.Render](../../aspose.threed.render/)
* assembly [Aspose.3D](../../)



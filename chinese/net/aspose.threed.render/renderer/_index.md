---
title: "类 Renderer"
second_title: "Aspose.3D for .NET API 参考"
description: "Aspose.ThreeD.Render.Renderer 类。关于渲染器的上下文"
type: docs
weight: 2340
url: /zh/net/aspose.threed.render/renderer/
---
## Renderer class

关于渲染器的上下文。

```csharp
public abstract class Renderer : IDisposable
```

## 属性

| 名称 | 描述 |
| --- | --- |
| [AssetDirectories](../../aspose.threed.render/renderer/assetdirectories/) { get; } | 存储外部资源的目录 |
| [EnableShadows](../../aspose.threed.render/renderer/enableshadows/) { get; set; } | 获取或设置是否启用阴影。 |
| [FallbackEntityRenderer](../../aspose.threed.render/renderer/fallbackentityrenderer/) { get; set; } | 获取或设置当实体没有定义特殊渲染器时的后备实体渲染器。 |
| virtual [Frustum](../../aspose.threed.render/renderer/frustum/) { get; set; } | 获取或设置用于提供视图矩阵的视锥体。 |
| virtual [Material](../../aspose.threed.render/renderer/material/) { get; set; } | 获取或设置用于提供着色器使用的材质信息的材质。 |
| [Node](../../aspose.threed.render/renderer/node/) { get; set; } | 获取或设置用于提供世界变换矩阵的 [`Node`](./node/) 实例。 |
| [PostProcessings](../../aspose.threed.render/renderer/postprocessings/) { get; } | 活动的后处理链 |
| [PresetShaders](../../aspose.threed.render/renderer/presetshaders/) { get; set; } | 获取或设置预设着色器集合 |
| abstract [RenderFactory](../../aspose.threed.render/renderer/renderfactory/) { get; } | 获取用于构建渲染相关对象的工厂。 |
| [RenderStage](../../aspose.threed.render/renderer/renderstage/) { get; } | 获取当前渲染阶段。 |
| [RenderTarget](../../aspose.threed.render/renderer/rendertarget/) { get; } | 指定后续渲染操作将执行的渲染目标。 |
| [Shader](../../aspose.threed.render/renderer/shader/) { get; set; } | 获取或设置用于渲染几何体的着色器实例。 |
| [ShaderSet](../../aspose.threed.render/renderer/shaderset/) { get; set; } | 获取或设置用于渲染场景的着色器集合 |
| [Variables](../../aspose.threed.render/renderer/variables/) { get; } | 访问用于渲染的内部变量 |

## 方法

| 名称 | 描述 |
| --- | --- |
| static [CreateRenderer](../../aspose.threed.render/renderer/createrenderer/)() | 使用默认配置创建一个新的 `Renderer`。 |
| virtual [ClearCache](../../aspose.threed.render/renderer/clearcache/)() | 手动清除缓存。Aspose.3D 会将一些对象（如材质/几何体）缓存到与渲染管线兼容的内部类型中。当场景发生重大更改时应手动调用此方法。 |
| [Dispose](../../aspose.threed.render/renderer/dispose/)() | 释放 `Renderer` 及所有相关资源 |
| abstract [Execute](../../aspose.threed.render/renderer/execute/)(PostProcessing, IRenderTarget) | 在指定的渲染目标上执行后处理 |
| [GetPostProcessing](../../aspose.threed.render/renderer/getpostprocessing/)(string) | 获取渲染器支持的内置后处理器。 |
| virtual [RegisterEntityRenderer](../../aspose.threed.render/renderer/registerentityrenderer/)(EntityRenderer) | 为指定实体注册实体渲染器 |
| virtual [Render](../../aspose.threed.render/renderer/render/)(IRenderTarget) | 渲染指定的目标 |

### 另请参见

* namespace [Aspose.ThreeD.Render](../../aspose.threed.render/)
* assembly [Aspose.3D](../../)



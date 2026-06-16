---
title: "类 RenderState"
second_title: "Aspose.3D for .NET API 参考"
description: "Aspose.ThreeD.Render.RenderState 类。用于构建管线的渲染状态 对渲染状态所做的更改不会影响已创建的管线实例"
type: docs
weight: 2330
url: /zh/net/aspose.threed.render/renderstate/
---
## RenderState class

用于构建管线的渲染状态。对渲染状态所做的更改不会影响已创建的管线实例。

```csharp
public class RenderState : IComparable<RenderState>, IDisposable
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [RenderState](renderstate/)() | `RenderState` 的构造函数 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [Blend](../../aspose.threed.render/renderstate/blend/) { get; set; } | 启用或禁用片段混合。 |
| [BlendColor](../../aspose.threed.render/renderstate/blendcolor/) { get; set; } | 获取或设置在 ConstantColor 中使用的混合颜色 |
| [CullFace](../../aspose.threed.render/renderstate/cullface/) { get; set; } | 启用或禁用剔除面 |
| [CullFaceMode](../../aspose.threed.render/renderstate/cullfacemode/) { get; set; } | 获取或设置将被剔除的面。 |
| [DepthFunction](../../aspose.threed.render/renderstate/depthfunction/) { get; set; } | 获取或设置深度测试中使用的比较函数 |
| [DepthMask](../../aspose.threed.render/renderstate/depthmask/) { get; set; } | 启用或禁用深度写入。 |
| [DepthTest](../../aspose.threed.render/renderstate/depthtest/) { get; set; } | 启用或禁用深度测试。 |
| [DestinationBlendFactor](../../aspose.threed.render/renderstate/destinationblendfactor/) { get; set; } | 获取或设置颜色的混合方式。 |
| [FrontFace](../../aspose.threed.render/renderstate/frontface/) { get; set; } | 获取或设置哪种顺序为正面。 |
| [PolygonMode](../../aspose.threed.render/renderstate/polygonmode/) { get; set; } | 获取或设置多边形的渲染模式。 |
| [ScissorTest](../../aspose.threed.render/renderstate/scissortest/) { get; set; } | 启用或禁用剪裁测试 |
| [SourceBlendFactor](../../aspose.threed.render/renderstate/sourceblendfactor/) { get; set; } | 获取或设置颜色的混合方式。 |
| [StencilBackFace](../../aspose.threed.render/renderstate/stencilbackface/) { get; } | 获取背面模板状态。 |
| [StencilFrontFace](../../aspose.threed.render/renderstate/stencilfrontface/) { get; } | 获取正面模板状态。 |
| [StencilMask](../../aspose.threed.render/renderstate/stencilmask/) { get; set; } | 获取或设置在测试完成时与参考值和存储的模板值进行 AND 运算的掩码。 |
| [StencilReference](../../aspose.threed.render/renderstate/stencilreference/) { get; set; } | 获取或设置模板测试的参考值。 |
| [StencilTest](../../aspose.threed.render/renderstate/stenciltest/) { get; set; } | 启用或禁用模板测试。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [CompareTo](../../aspose.threed.render/renderstate/compareto/)(RenderState) | 将渲染状态与另一个实例进行比较 |
| [Dispose](../../aspose.threed.render/renderstate/dispose/)() | 释放 `RenderState` 并释放所有内部资源。 |
| override [Equals](../../aspose.threed.render/renderstate/equals/)(object) | 返回一个值，指示此实例是否等于指定的对象。 |
| override [GetHashCode](../../aspose.threed.render/renderstate/gethashcode/)() | 返回此实例的哈希码。 |

### 另请参见

* namespace [Aspose.ThreeD.Render](../../aspose.threed.render/)
* assembly [Aspose.3D](../../)



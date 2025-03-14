---
title: Class RenderState
second_title: Aspose.3D for .NET API Reference
description: Aspose.ThreeD.Render.RenderState class. Render state for building the pipeline The changes made on render state will not affect the created pipeline instances
type: docs
weight: 2230
url: /net/aspose.threed.render/renderstate/
---
## RenderState class

Render state for building the pipeline The changes made on render state will not affect the created pipeline instances.

```csharp
public class RenderState : IComparable<RenderState>, IDisposable
```

## Constructors

| Name | Description |
| --- | --- |
| [RenderState](renderstate/)() | Constructor of `RenderState` |

## Properties

| Name | Description |
| --- | --- |
| [Blend](../../aspose.threed.render/renderstate/blend/) { get; set; } | Enable or disable the fragment blending. |
| [BlendColor](../../aspose.threed.render/renderstate/blendcolor/) { get; set; } | Gets or sets the blend color where used in ConstantColor |
| [CullFace](../../aspose.threed.render/renderstate/cullface/) { get; set; } | Enable or disable cull face |
| [CullFaceMode](../../aspose.threed.render/renderstate/cullfacemode/) { get; set; } | Gets or sets which face will be culled. |
| [DepthFunction](../../aspose.threed.render/renderstate/depthfunction/) { get; set; } | Gets or sets the compare function used in depth test |
| [DepthMask](../../aspose.threed.render/renderstate/depthmask/) { get; set; } | Enable or disable the depth writing. |
| [DepthTest](../../aspose.threed.render/renderstate/depthtest/) { get; set; } | Enable or disable the depth test. |
| [DestinationBlendFactor](../../aspose.threed.render/renderstate/destinationblendfactor/) { get; set; } | Gets or sets how the color is blended. |
| [FrontFace](../../aspose.threed.render/renderstate/frontface/) { get; set; } | Gets or sets which order is front face. |
| [PolygonMode](../../aspose.threed.render/renderstate/polygonmode/) { get; set; } | Gets or sets the polygon's render mode. |
| [ScissorTest](../../aspose.threed.render/renderstate/scissortest/) { get; set; } | Enable or disable scissor test |
| [SourceBlendFactor](../../aspose.threed.render/renderstate/sourceblendfactor/) { get; set; } | Gets or sets how the color is blended. |
| [StencilBackFace](../../aspose.threed.render/renderstate/stencilbackface/) { get; } | Gets the stencil state for back face. |
| [StencilFrontFace](../../aspose.threed.render/renderstate/stencilfrontface/) { get; } | Gets the stencil state for front face. |
| [StencilMask](../../aspose.threed.render/renderstate/stencilmask/) { get; set; } | Gets or sets the mask that is ANDed with the both reference and stored stencil value when test is done. |
| [StencilReference](../../aspose.threed.render/renderstate/stencilreference/) { get; set; } | Gets or sets the reference value for the stencil test. |
| [StencilTest](../../aspose.threed.render/renderstate/stenciltest/) { get; set; } | Enable or disable the stencil test. |

## Methods

| Name | Description |
| --- | --- |
| [CompareTo](../../aspose.threed.render/renderstate/compareto/)(RenderState) | Compare the render state with another instance |
| [Dispose](../../aspose.threed.render/renderstate/dispose/)() | Dispose the `RenderState` and release all internal resources. |
| override [Equals](../../aspose.threed.render/renderstate/equals/)(object) | Returns a value indicating whether this instance is equal to a specified object. |
| override [GetHashCode](../../aspose.threed.render/renderstate/gethashcode/)() | Returns the hash code for this instance. |

### See Also

* namespace [Aspose.ThreeD.Render](../../aspose.threed.render/)
* assembly [Aspose.3D](../../)



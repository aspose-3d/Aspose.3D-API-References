---
title: "类 RenderFactory"
second_title: "Aspose.3D for .NET API 参考"
description: "Aspose.ThreeD.Render.RenderFactory 类。RenderFactory 创建渲染管线中表示的所有资源"
type: docs
weight: 2280
url: /zh/net/aspose.threed.render/renderfactory/
---
## RenderFactory class

RenderFactory 创建渲染管线中表示的所有资源。

```csharp
public abstract class RenderFactory
```

## 方法

| 名称 | 描述 |
| --- | --- |
| abstract [CreateCubeRenderTexture](../../aspose.threed.render/renderfactory/createcuberendertexture/)(RenderParameters, int, int) | 创建一个包含 1 个立方体纹理的渲染目标 |
| abstract [CreateDescriptorSet](../../aspose.threed.render/renderfactory/createdescriptorset/)(ShaderProgram) | 为指定的着色器程序创建描述符集。 |
| abstract [CreateIndexBuffer](../../aspose.threed.render/renderfactory/createindexbuffer/)() | 创建一个 [`IIndexBuffer`](../iindexbuffer/) 实例来存储多边形的面信息。 |
| abstract [CreatePipeline](../../aspose.threed.render/renderfactory/createpipeline/)(ShaderProgram, RenderState, VertexDeclaration, DrawOperation) | 创建一个预配置的图形管线，包含预配置的着色器/渲染状态/顶点声明和绘制操作。 |
| abstract [CreateRenderTexture](../../aspose.threed.render/renderfactory/createrendertexture/#createrendertexture)(RenderParameters, int, int) | 创建一个渲染目标，包含 1 个渲染到纹理的目标 |
| abstract [CreateRenderTexture](../../aspose.threed.render/renderfactory/createrendertexture/#createrendertexture_1)(RenderParameters, int, int, int) | 创建一个渲染到纹理的渲染目标 |
| abstract [CreateRenderWindow](../../aspose.threed.render/renderfactory/createrenderwindow/)(RenderParameters, WindowHandle) | 创建一个渲染到本机窗口的渲染目标。 |
| abstract [CreateShaderProgram](../../aspose.threed.render/renderfactory/createshaderprogram/)(ShaderSource) | 创建一个 [`ShaderProgram`](../shaderprogram/) 对象 |
| [CreateTextureUnit](../../aspose.threed.render/renderfactory/createtextureunit/#createtextureunit)() | 创建一个可被着色器访问的 2D 纹理单元。 |
| abstract [CreateTextureUnit](../../aspose.threed.render/renderfactory/createtextureunit/#createtextureunit_1)(TextureType) | 创建一个可被着色器访问的纹理单元。 |
| abstract [CreateUniformBuffer](../../aspose.threed.render/renderfactory/createuniformbuffer/)(int) | 在 GPU 端创建一个具有预分配大小的新统一缓冲区。 |
| abstract [CreateVertexBuffer](../../aspose.threed.render/renderfactory/createvertexbuffer/)(VertexDeclaration) | 创建一个 [`IVertexBuffer`](../ivertexbuffer/) 实例来存储多边形的顶点信息。 |

### 另请参见

* namespace [Aspose.ThreeD.Render](../../aspose.threed.render/)
* assembly [Aspose.3D](../../)



---
title: "Класс RenderFactory"
second_title: "Справочник API Aspose.3D для .NET"
description: "Класс Aspose.ThreeD.Render.RenderFactory. RenderFactory создает все ресурсы, представленные в конвейере рендеринга"
type: docs
weight: 2280
url: /ru/net/aspose.threed.render/renderfactory/
---
## RenderFactory class

RenderFactory создает все ресурсы, представленные в конвейере рендеринга.

```csharp
public abstract class RenderFactory
```

## Методы

| Имя | Описание |
| --- | --- |
| abstract [CreateCubeRenderTexture](../../aspose.threed.render/renderfactory/createcuberendertexture/)(RenderParameters, int, int) | Создайте целевой объект рендеринга, содержащий 1 кубическую текстуру |
| abstract [CreateDescriptorSet](../../aspose.threed.render/renderfactory/createdescriptorset/)(ShaderProgram) | Создайте набор дескрипторов для указанной программы шейдера. |
| abstract [CreateIndexBuffer](../../aspose.threed.render/renderfactory/createindexbuffer/)() | Создайте экземпляр [`IIndexBuffer`](../iindexbuffer/) для хранения информации о гранях полигона. |
| abstract [CreatePipeline](../../aspose.threed.render/renderfactory/createpipeline/)(ShaderProgram, RenderState, VertexDeclaration, DrawOperation) | Создайте предварительно настроенный графический конвейер с предустановленными шейдером/состоянием рендеринга/объявлением вершин и операциями отрисовки. |
| abstract [CreateRenderTexture](../../aspose.threed.render/renderfactory/createrendertexture/#createrendertexture)(RenderParameters, int, int) | Создайте целевой объект рендеринга, содержащий 1 цель, выводящую в текстуру |
| abstract [CreateRenderTexture](../../aspose.threed.render/renderfactory/createrendertexture/#createrendertexture_1)(RenderParameters, int, int, int) | Создайте целевой объект рендеринга, выводящий в текстуру |
| abstract [CreateRenderWindow](../../aspose.threed.render/renderfactory/createrenderwindow/)(RenderParameters, WindowHandle) | Создайте целевой объект рендеринга, выводящий в нативное окно. |
| abstract [CreateShaderProgram](../../aspose.threed.render/renderfactory/createshaderprogram/)(ShaderSource) | Создайте объект [`ShaderProgram`](../shaderprogram/) |
| [CreateTextureUnit](../../aspose.threed.render/renderfactory/createtextureunit/#createtextureunit)() | Создайте 2D‑юнит текстуры, доступный шейдеру. |
| abstract [CreateTextureUnit](../../aspose.threed.render/renderfactory/createtextureunit/#createtextureunit_1)(TextureType) | Создайте юнит текстуры, доступный шейдеру. |
| abstract [CreateUniformBuffer](../../aspose.threed.render/renderfactory/createuniformbuffer/)(int) | Создайте новый униформ‑буфер на стороне GPU с предварительно выделенным размером. |
| abstract [CreateVertexBuffer](../../aspose.threed.render/renderfactory/createvertexbuffer/)(VertexDeclaration) | Создайте экземпляр [`IVertexBuffer`](../ivertexbuffer/) для хранения информации о вершинах полигона. |

### См. также

* namespace [Aspose.ThreeD.Render](../../aspose.threed.render/)
* assembly [Aspose.3D](../../)



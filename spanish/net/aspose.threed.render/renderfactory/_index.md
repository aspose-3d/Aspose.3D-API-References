---
title: "Clase RenderFactory"
second_title: "Referencia de la API de Aspose.3D para .NET"
description: "Clase Aspose.ThreeD.Render.RenderFactory. RenderFactory crea todos los recursos que se representan en la canalización de renderizado"
type: docs
weight: 2280
url: /es/net/aspose.threed.render/renderfactory/
---
## RenderFactory class

RenderFactory crea todos los recursos que se representan en el pipeline de renderizado.

```csharp
public abstract class RenderFactory
```

## Métodos

| Nombre | Descripción |
| --- | --- |
| abstract [CreateCubeRenderTexture](../../aspose.threed.render/renderfactory/createcuberendertexture/)(RenderParameters, int, int) | Cree un objetivo de renderizado que contiene 1 textura cúbica |
| abstract [CreateDescriptorSet](../../aspose.threed.render/renderfactory/createdescriptorset/)(ShaderProgram) | Cree el conjunto de descriptores para el programa de sombreado especificado. |
| abstract [CreateIndexBuffer](../../aspose.threed.render/renderfactory/createindexbuffer/)() | Cree una instancia de [`IIndexBuffer`](../iindexbuffer/) para almacenar la información de caras del polígono. |
| abstract [CreatePipeline](../../aspose.threed.render/renderfactory/createpipeline/)(ShaderProgram, RenderState, VertexDeclaration, DrawOperation) | Cree una canalización gráfica preconfigurada con sombreado/estado de renderizado/declaración de vértices preconfigurados y operaciones de dibujo. |
| abstract [CreateRenderTexture](../../aspose.threed.render/renderfactory/createrendertexture/#createrendertexture)(RenderParameters, int, int) | Cree un objetivo de renderizado que contiene 1 objetivo que renderiza a la textura |
| abstract [CreateRenderTexture](../../aspose.threed.render/renderfactory/createrendertexture/#createrendertexture_1)(RenderParameters, int, int, int) | Cree un objetivo de renderizado que renderiza a la textura |
| abstract [CreateRenderWindow](../../aspose.threed.render/renderfactory/createrenderwindow/)(RenderParameters, WindowHandle) | Cree un objetivo de renderizado que renderiza a la ventana nativa. |
| abstract [CreateShaderProgram](../../aspose.threed.render/renderfactory/createshaderprogram/)(ShaderSource) | Cree un objeto [`ShaderProgram`](../shaderprogram/) |
| [CreateTextureUnit](../../aspose.threed.render/renderfactory/createtextureunit/#createtextureunit)() | Cree una unidad de textura 2D que pueda ser accedida por el sombreado. |
| abstract [CreateTextureUnit](../../aspose.threed.render/renderfactory/createtextureunit/#createtextureunit_1)(TextureType) | Cree una unidad de textura que pueda ser accedida por el sombreado. |
| abstract [CreateUniformBuffer](../../aspose.threed.render/renderfactory/createuniformbuffer/)(int) | Cree un nuevo búfer uniforme en el GPU con tamaño preasignado. |
| abstract [CreateVertexBuffer](../../aspose.threed.render/renderfactory/createvertexbuffer/)(VertexDeclaration) | Cree una instancia de [`IVertexBuffer`](../ivertexbuffer/) para almacenar la información de vértices del polígono. |

### Ver también

* namespace [Aspose.ThreeD.Render](../../aspose.threed.render/)
* assembly [Aspose.3D](../../)



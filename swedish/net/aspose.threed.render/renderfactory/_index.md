---
title: RenderFactory
second_title: Aspose.3D för .NET API-referens
description: RenderFactory skapar alla resurser som representeras i renderingspipeline.
type: docs
weight: 2040
url: /sv/net/aspose.threed.render/renderfactory/
---
## RenderFactory class

RenderFactory skapar alla resurser som representeras i renderingspipeline.

```csharp
public abstract class RenderFactory
```

## Metoder

| namn | Beskrivning |
| --- | --- |
| abstract [CreateCubeRenderTexture](../../aspose.threed.render/renderfactory/createcuberendertexture)(RenderParameters, int, int) | Skapa ett renderingsmål innehåller 1 kub texture |
| abstract [CreateDescriptorSet](../../aspose.threed.render/renderfactory/createdescriptorset)(ShaderProgram) | Skapa beskrivningsuppsättningen för specificerat shader-program. |
| abstract [CreateIndexBuffer](../../aspose.threed.render/renderfactory/createindexbuffer)() | Skapa en[`IIndexBuffer`](../iindexbuffer) instans för att lagra polygons ansiktsinformation. |
| abstract [CreatePipeline](../../aspose.threed.render/renderfactory/createpipeline)(ShaderProgram, RenderState, VertexDeclaration, DrawOperation) | Skapa en förkonfigurerad grafikpipeline med förkonfigurerad shader/render state/vertex-deklaration och ritoperationer. |
| abstract [CreateRenderTexture](../../aspose.threed.render/renderfactory/createrendertexture#createrendertexture)(RenderParameters, int, int) | Skapa ett renderingsmål innehåller 1 mål som renderar till texture |
| abstract [CreateRenderTexture](../../aspose.threed.render/renderfactory/createrendertexture#createrendertexture_1)(RenderParameters, int, int, int) | Skapa ett renderingsmål som renderar till texture |
| abstract [CreateRenderWindow](../../aspose.threed.render/renderfactory/createrenderwindow)(RenderParameters, WindowHandle) | Skapa ett renderingsmål som renderar till det ursprungliga fönstret. |
| abstract [CreateShaderProgram](../../aspose.threed.render/renderfactory/createshaderprogram)(ShaderSource) | Skapa en[`ShaderProgram`](../shaderprogram) objekt |
| [CreateTextureUnit](../../aspose.threed.render/renderfactory/createtextureunit#createtextureunit)() | Skapa en 2D-strukturenhet som kan nås av shader. |
| abstract [CreateTextureUnit](../../aspose.threed.render/renderfactory/createtextureunit#createtextureunit_1)(TextureType) | Skapa en strukturenhet som kan nås av shader. |
| abstract [CreateUniformBuffer](../../aspose.threed.render/renderfactory/createuniformbuffer)(int) | Skapa en ny enhetlig buffert på GPU-sidan med förtilldelad storlek. |
| abstract [CreateVertexBuffer](../../aspose.threed.render/renderfactory/createvertexbuffer)(VertexDeclaration) | Skapa en[`IVertexBuffer`](../ivertexbuffer) instans för att lagra polygons vertexinformation. |

### Se även

* namnutrymme [Aspose.ThreeD.Render](../../aspose.threed.render)
* hopsättning [Aspose.3D](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.3D.dll -->

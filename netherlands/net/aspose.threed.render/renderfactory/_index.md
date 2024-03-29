---
title: RenderFactory
second_title: Aspose.3D voor .NET API-referentie
description: RenderFactory maakt alle bronnen aan die vertegenwoordigd zijn in de renderingpijplijn.
type: docs
weight: 2040
url: /nl/net/aspose.threed.render/renderfactory/
---
## RenderFactory class

RenderFactory maakt alle bronnen aan die vertegenwoordigd zijn in de renderingpijplijn.

```csharp
public abstract class RenderFactory
```

## methoden

| Naam | Beschrijving |
| --- | --- |
| abstract [CreateCubeRenderTexture](../../aspose.threed.render/renderfactory/createcuberendertexture/)(RenderParameters, int, int) | Een renderdoel maken bevat 1 kubus texture |
| abstract [CreateDescriptorSet](../../aspose.threed.render/renderfactory/createdescriptorset/)(ShaderProgram) | Maak de descriptorset voor het gespecificeerde shader-programma. |
| abstract [CreateIndexBuffer](../../aspose.threed.render/renderfactory/createindexbuffer/)() | Maak een[`IIndexBuffer`](../iindexbuffer/) instantie om de gezichtsinformatie van de polygoon op te slaan. |
| abstract [CreatePipeline](../../aspose.threed.render/renderfactory/createpipeline/)(ShaderProgram, RenderState, VertexDeclaration, DrawOperation) | Maak een vooraf geconfigureerde grafische pijplijn met vooraf geconfigureerde shader/render state/vertex-declaratie en tekenbewerkingen. |
| abstract [CreateRenderTexture](../../aspose.threed.render/renderfactory/createrendertexture/#createrendertexture)(RenderParameters, int, int) | Een renderdoel maken bevat 1 doel dat wordt weergegeven naar de textuur |
| abstract [CreateRenderTexture](../../aspose.threed.render/renderfactory/createrendertexture/#createrendertexture_1)(RenderParameters, int, int, int) | Maak een renderdoel dat rendert naar de texture |
| abstract [CreateRenderWindow](../../aspose.threed.render/renderfactory/createrenderwindow/)(RenderParameters, WindowHandle) | Maak een renderdoel dat wordt weergegeven in het oorspronkelijke venster. |
| abstract [CreateShaderProgram](../../aspose.threed.render/renderfactory/createshaderprogram/)(ShaderSource) | Maak een[`ShaderProgram`](../shaderprogram/) object |
| [CreateTextureUnit](../../aspose.threed.render/renderfactory/createtextureunit/#createtextureunit)() | Maak een 2D-textuureenheid die toegankelijk is voor arcering. |
| abstract [CreateTextureUnit](../../aspose.threed.render/renderfactory/createtextureunit/#createtextureunit_1)(TextureType) | Maak een structuureenheid die toegankelijk is voor arcering. |
| abstract [CreateUniformBuffer](../../aspose.threed.render/renderfactory/createuniformbuffer/)(int) | Maak een nieuwe uniforme buffer aan de GPU-zijde met een vooraf toegewezen grootte. |
| abstract [CreateVertexBuffer](../../aspose.threed.render/renderfactory/createvertexbuffer/)(VertexDeclaration) | Maak een[`IVertexBuffer`](../ivertexbuffer/) instantie om hoekpuntinformatie van polygoon op te slaan. |

### Zie ook

* naamruimte [Aspose.ThreeD.Render](../../aspose.threed.render/)
* montage [Aspose.3D](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.3D.dll -->

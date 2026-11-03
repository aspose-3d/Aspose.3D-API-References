---
title: "Klasse RenderFactory"
second_title: "Aspose.3D für .NET API-Referenz"
description: "Aspose.ThreeD.Render.RenderFactory Klasse. RenderFactory erstellt alle Ressourcen, die in der Rendering-Pipeline dargestellt werden."
type: docs
weight: 2280
url: /de/net/aspose.threed.render/renderfactory/
---
## RenderFactory class

RenderFactory erstellt alle Ressourcen, die in der Rendering-Pipeline dargestellt werden.

```csharp
public abstract class RenderFactory
```

## Methoden

| Name | Beschreibung |
| --- | --- |
| abstract [CreateCubeRenderTexture](../../aspose.threed.render/renderfactory/createcuberendertexture/)(RenderParameters, int, int) | Erstellt ein Renderziel, das 1 Würfeltextur enthält. |
| abstract [CreateDescriptorSet](../../aspose.threed.render/renderfactory/createdescriptorset/)(ShaderProgram) | Erstellt das Deskriptorset für das angegebene Shader-Programm. |
| abstract [CreateIndexBuffer](../../aspose.threed.render/renderfactory/createindexbuffer/)() | Erstellt eine [`IIndexBuffer`](../iindexbuffer/) Instanz, um die Flächeninformationen des Polygons zu speichern. |
| abstract [CreatePipeline](../../aspose.threed.render/renderfactory/createpipeline/)(ShaderProgram, RenderState, VertexDeclaration, DrawOperation) | Erstellt eine vorkonfigurierte Grafikpipeline mit vorkonfiguriertem Shader-/Renderzustand/Vertex-Deklaration und Zeichenoperationen. |
| abstract [CreateRenderTexture](../../aspose.threed.render/renderfactory/createrendertexture/#createrendertexture)(RenderParameters, int, int) | Erstellt ein Renderziel, das ein Ziel enthält, das in die Textur rendert. |
| abstract [CreateRenderTexture](../../aspose.threed.render/renderfactory/createrendertexture/#createrendertexture_1)(RenderParameters, int, int, int) | Erstellt ein Renderziel, das in die Textur rendert. |
| abstract [CreateRenderWindow](../../aspose.threed.render/renderfactory/createrenderwindow/)(RenderParameters, WindowHandle) | Erstellt ein Renderziel, das in das native Fenster rendert. |
| abstract [CreateShaderProgram](../../aspose.threed.render/renderfactory/createshaderprogram/)(ShaderSource) | Erstellt ein [`ShaderProgram`](../shaderprogram/) Objekt |
| [CreateTextureUnit](../../aspose.threed.render/renderfactory/createtextureunit/#createtextureunit)() | Erstellt eine 2D-Textureinheit, die vom Shader aus zugänglich ist. |
| abstract [CreateTextureUnit](../../aspose.threed.render/renderfactory/createtextureunit/#createtextureunit_1)(TextureType) | Erstelle eine Textureinheit, die vom Shader aus zugänglich ist. |
| abstract [CreateUniformBuffer](../../aspose.threed.render/renderfactory/createuniformbuffer/)(int) | Erstelle einen neuen Uniform-Puffer auf der GPU-Seite mit vorab zugewiesener Größe. |
| abstract [CreateVertexBuffer](../../aspose.threed.render/renderfactory/createvertexbuffer/)(VertexDeclaration) | Erstelle eine [`IVertexBuffer`](../ivertexbuffer/) Instanz, um die Scheitelpunktinformationen des Polygons zu speichern. |

### Siehe auch

* namespace [Aspose.ThreeD.Render](../../aspose.threed.render/)
* assembly [Aspose.3D](../../)



---
title: "Classe RenderFactory"
second_title: "Référence de l'API Aspose.3D pour .NET"
description: "Classe Aspose.ThreeD.Render.RenderFactory. RenderFactory crée toutes les ressources représentées dans le pipeline de rendu."
type: docs
weight: 2280
url: /fr/net/aspose.threed.render/renderfactory/
---
## RenderFactory class

RenderFactory crée toutes les ressources représentées dans le pipeline de rendu.

```csharp
public abstract class RenderFactory
```

## Méthodes

| Nom | Description |
| --- | --- |
| abstract [CreateCubeRenderTexture](../../aspose.threed.render/renderfactory/createcuberendertexture/)(RenderParameters, int, int) | Créez une cible de rendu contenant 1 texture cube. |
| abstract [CreateDescriptorSet](../../aspose.threed.render/renderfactory/createdescriptorset/)(ShaderProgram) | Créez l'ensemble de descripteurs pour le programme shader spécifié. |
| abstract [CreateIndexBuffer](../../aspose.threed.render/renderfactory/createindexbuffer/)() | Créez une instance [`IIndexBuffer`](../iindexbuffer/) pour stocker les informations des faces du polygone. |
| abstract [CreatePipeline](../../aspose.threed.render/renderfactory/createpipeline/)(ShaderProgram, RenderState, VertexDeclaration, DrawOperation) | Créez un pipeline graphique préconfiguré avec un shader/état de rendu/déclaration de sommet préconfigurés et des opérations de dessin. |
| abstract [CreateRenderTexture](../../aspose.threed.render/renderfactory/createrendertexture/#createrendertexture)(RenderParameters, int, int) | Créez une cible de rendu contenant 1 cible qui rend sur la texture. |
| abstract [CreateRenderTexture](../../aspose.threed.render/renderfactory/createrendertexture/#createrendertexture_1)(RenderParameters, int, int, int) | Créez une cible de rendu qui rend sur la texture. |
| abstract [CreateRenderWindow](../../aspose.threed.render/renderfactory/createrenderwindow/)(RenderParameters, WindowHandle) | Créez une cible de rendu qui rend sur la fenêtre native. |
| abstract [CreateShaderProgram](../../aspose.threed.render/renderfactory/createshaderprogram/)(ShaderSource) | Créez un objet [`ShaderProgram`](../shaderprogram/). |
| [CreateTextureUnit](../../aspose.threed.render/renderfactory/createtextureunit/#createtextureunit)() | Créez une unité de texture 2D qui peut être accédée par le shader. |
| abstract [CreateTextureUnit](../../aspose.threed.render/renderfactory/createtextureunit/#createtextureunit_1)(TextureType) | Créez une unité de texture qui peut être accédée par le shader. |
| abstract [CreateUniformBuffer](../../aspose.threed.render/renderfactory/createuniformbuffer/)(int) | Créez un nouveau tampon uniforme côté GPU avec une taille pré‑allouée. |
| abstract [CreateVertexBuffer](../../aspose.threed.render/renderfactory/createvertexbuffer/)(VertexDeclaration) | Créez une instance [`IVertexBuffer`](../ivertexbuffer/) pour stocker les informations des sommets du polygone. |

### Voir aussi

* namespace [Aspose.ThreeD.Render](../../aspose.threed.render/)
* assembly [Aspose.3D](../../)



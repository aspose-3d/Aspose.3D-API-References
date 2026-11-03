---
title: "Interface ICommandList"
second_title: "Référence de l'API Aspose.3D pour .NET"
description: "Aspose.ThreeD.Render.ICommandList interface. Encode une séquence de commandes qui seront envoyées au GPU pour le rendu"
type: docs
weight: 2030
url: /fr/net/aspose.threed.render/icommandlist/
---
## ICommandList interface

Encode une séquence de commandes qui seront envoyées au GPU pour le rendu.

```csharp
public interface ICommandList
```

## Méthodes

| Nom | Description |
| --- | --- |
| [BindDescriptorSet](../../aspose.threed.render/icommandlist/binddescriptorset/)(IDescriptorSet) | Lier le jeu de descripteurs au pipeline actuel |
| [BindIndexBuffer](../../aspose.threed.render/icommandlist/bindindexbuffer/)(IIndexBuffer) | Lier le tampon d'indices pour le rendu |
| [BindPipeline](../../aspose.threed.render/icommandlist/bindpipeline/)(IPipeline) | Lier l'instance du pipeline pour le rendu |
| [BindVertexBuffer](../../aspose.threed.render/icommandlist/bindvertexbuffer/)(IVertexBuffer) | Lier le tampon de sommets pour le rendu |
| [Draw](../../aspose.threed.render/icommandlist/draw/#draw)() | Dessiner sans tampon d'indices |
| [Draw](../../aspose.threed.render/icommandlist/draw/#draw_1)(int, int) | Dessiner sans tampon d'indices |
| [DrawIndex](../../aspose.threed.render/icommandlist/drawindex/#drawindex)() | Émettre un dessin indexé dans une liste de commandes |
| [DrawIndex](../../aspose.threed.render/icommandlist/drawindex/#drawindex_1)(int, int) | Émettre un dessin indexé dans une liste de commandes |
| [PushConstants](../../aspose.threed.render/icommandlist/pushconstants/#pushconstants)(ShaderStage, byte[]) | Pousser la constante vers le pipeline |
| [PushConstants](../../aspose.threed.render/icommandlist/pushconstants/#pushconstants_1)(ShaderStage, byte[], int) | Pousser la constante vers le pipeline |

### Voir aussi

* namespace [Aspose.ThreeD.Render](../../aspose.threed.render/)
* assembly [Aspose.3D](../../)



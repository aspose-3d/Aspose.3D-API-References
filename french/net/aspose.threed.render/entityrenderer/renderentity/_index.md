---
title: RenderEntity
second_title: Référence de l'API Aspose.3D pour .NET
description: Chaque tâche de rendu poussée vers leIRenderQueueaspose.threed.render/irenderqueue aura un appel RenderEntity correspondant pour effectuer le travail de rendu concret.
type: docs
weight: 70
url: /fr/net/aspose.threed.render/entityrenderer/renderentity/
---
## EntityRenderer.RenderEntity method

Chaque tâche de rendu poussée vers le[`IRenderQueue`](../../irenderqueue) aura un appel RenderEntity correspondant pour effectuer le travail de rendu concret.

```csharp
public virtual void RenderEntity(Renderer renderer, ICommandList commandList, Node node, 
    object renderableResource, int subEntity)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| renderer | Renderer | Le moteur de rendu |
| commandList | ICommandList | La commandList utilisée pour enregistrer les commandes de rendu |
| node | Node | Le même nœud qui est passé à PrepareRenderQueue de l'entité qui sera rendue |
| renderableResource | Object | L'objet personnalisé qui est passé à IRenderQueue pendant la PrepareRenderQueue |
| subEntity | Int32 | L'index de la sous-entité qui est passée à IRenderQueue |

### Voir également

* class [Renderer](../../renderer)
* interface [ICommandList](../../icommandlist)
* class [Node](../../../aspose.threed/node)
* class [EntityRenderer](../../entityrenderer)
* espace de noms [Aspose.ThreeD.Render](../../entityrenderer)
* Assemblée [Aspose.3D](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.3D.dll -->
---
title: "EntityRenderer.RenderEntity"
second_title: "Référence de l'API Aspose.3D pour .NET"
description: "Méthode EntityRenderer. Chaque tâche de rendu poussée dans l'IRenderQueue aura un appel RenderEntity correspondant pour exécuter le travail de rendu concret"
type: docs
weight: 70
url: /fr/net/aspose.threed.render/entityrenderer/renderentity/
---
## EntityRenderer.RenderEntity method

Chaque tâche de rendu poussée dans le [`IRenderQueue`](../../irenderqueue/) aura un appel RenderEntity correspondant pour exécuter le travail de rendu concret.

```csharp
public virtual void RenderEntity(Renderer renderer, ICommandList commandList, Node node, 
    object renderableResource, int subEntity)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| renderer | Renderer | Le renderer |
| commandList | ICommandList | La commandList utilisée pour enregistrer les commandes de rendu |
| nœud | Nœud | Le même nœud qui a été passé à PrepareRenderQueue de l'entité qui sera rendue |
| renderableResource | Objet | L'objet personnalisé qui a été passé à IRenderQueue pendant le PrepareRenderQueue |
| subEntity | Int32 | L'index de la sous‑entité qui a été passé à IRenderQueue |

### Voir aussi

* class [Renderer](../../renderer/)
* interface [ICommandList](../../icommandlist/)
* class [Node](../../../aspose.threed/node/)
* class [EntityRenderer](../)
* namespace [Aspose.ThreeD.Render](../../entityrenderer/)
* assembly [Aspose.3D](../../../)



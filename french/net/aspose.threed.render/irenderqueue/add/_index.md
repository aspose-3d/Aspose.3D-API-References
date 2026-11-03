---
title: "IRenderQueue.Add"
second_title: "Référence de l'API Aspose.3D pour .NET"
description: "Méthode IRenderQueue. Ajoute une tâche de rendu à la file d'attente de rendu"
type: docs
weight: 10
url: /fr/net/aspose.threed.render/irenderqueue/add/
---
## IRenderQueue.Add method

Ajoutez la tâche de rendu à la file d'attente de rendu.

```csharp
public void Add(RenderQueueGroupId groupId, IPipeline pipeline, object renderableResource, 
    int subEntity)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| groupId | RenderQueueGroupId | Quel groupe de la file d'attente contiendra la tâche de rendu |
| pipeline | IPipeline | L'instance du pipeline utilisée pour cette tâche de rendu |
| renderableResource | Object | Objet personnalisé qui sera envoyé à [`RenderEntity`](../../entityrenderer/renderentity/) |
| subEntity | Int32 | L'index des sous‑entités, utile lorsque l'entité se compose de plusieurs composants sous‑rendus. |

### Voir aussi

* enum [RenderQueueGroupId](../../renderqueuegroupid/)
* interface [IPipeline](../../ipipeline/)
* interface [IRenderQueue](../)
* namespace [Aspose.ThreeD.Render](../../irenderqueue/)
* assembly [Aspose.3D](../../../)



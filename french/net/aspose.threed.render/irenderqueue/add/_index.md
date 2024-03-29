---
title: Add
second_title: Référence de l'API Aspose.3D pour .NET
description: Ajouter une tâche de rendu à la file dattente de rendu.
type: docs
weight: 10
url: /fr/net/aspose.threed.render/irenderqueue/add/
---
## IRenderQueue.Add method

Ajouter une tâche de rendu à la file d'attente de rendu.

```csharp
public void Add(RenderQueueGroupId groupId, IPipeline pipeline, object renderableResource, 
    int subEntity)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| groupId | RenderQueueGroupId | Dans quel groupe de la file d'attente se trouvera la tâche de rendu |
| pipeline | IPipeline | L'instance de pipeline utilisée pour cette tâche de rendu |
| renderableResource | Object | Objet personnalisé qui sera envoyé à[`RenderEntity`](../../entityrenderer/renderentity) |
| subEntity | Int32 | L'index des sous-entités, utile lorsque l'entité est constituée de plusieurs sous-composants pouvant être rendus. |

### Voir également

* enum [RenderQueueGroupId](../../renderqueuegroupid)
* interface [IPipeline](../../ipipeline)
* interface [IRenderQueue](../../irenderqueue)
* espace de noms [Aspose.ThreeD.Render](../../irenderqueue)
* Assemblée [Aspose.3D](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.3D.dll -->

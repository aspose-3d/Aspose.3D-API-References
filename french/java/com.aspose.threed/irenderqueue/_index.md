---
title: "IRenderQueue"
second_title: "Référence d'API Aspose.3D pour Java"
description: "Le moteur de rendu d'entité utilise cette file d'attente pour gérer les tâches de rendu."
type: docs
weight: 248
url: /fr/java/com.aspose.threed/irenderqueue/
---
```
public interface IRenderQueue
```

Le moteur de rendu d'entité utilise cette file d'attente pour gérer les tâches de rendu.
## Méthodes

| Méthode | Description |
| --- | --- |
| [add(RenderQueueGroupId groupId, IPipeline pipeline, Object renderableResource, int subEntity)](#add-com.aspose.threed.RenderQueueGroupId-com.aspose.threed.IPipeline-java.lang.Object-int-) | Ajouter une tâche de rendu à la file d'attente de rendu. |
### add(RenderQueueGroupId groupId, IPipeline pipeline, Object renderableResource, int subEntity) {#add-com.aspose.threed.RenderQueueGroupId-com.aspose.threed.IPipeline-java.lang.Object-int-}
```
public abstract void add(RenderQueueGroupId groupId, IPipeline pipeline, Object renderableResource, int subEntity)
```


Ajouter une tâche de rendu à la file d'attente de rendu.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| groupId | [RenderQueueGroupId](../../com.aspose.threed/renderqueuegroupid) | Quel groupe de la file d'attente contiendra la tâche de rendu |
| pipeline | [IPipeline](../../com.aspose.threed/ipipeline) | L'instance du pipeline utilisée pour cette tâche de rendu |
| renderableResource | java.lang.Object | Objet personnalisé qui sera envoyé à [EntityRenderer](../../com.aspose.threed/entityrenderer) |
| subEntity | int | L'index des sous-entités, utile lorsque l'entité se compose de plusieurs composants rendables. |


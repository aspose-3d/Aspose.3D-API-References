---
title: IRenderQueue
second_title: Aspose.3D for Java API-referentie
description: Entity renderer gebruikt deze wachtrij om rendertaken te beheren.
type: docs
weight: 248
url: /nl/java/com.aspose.threed/irenderqueue/
---
```
public interface IRenderQueue
```

Entity renderer gebruikt deze wachtrij om rendertaken te beheren.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [add(RenderQueueGroupId groupId, IPipeline pipeline, Object renderableResource, int subEntity)](#add-com.aspose.threed.RenderQueueGroupId-com.aspose.threed.IPipeline-java.lang.Object-int-) | Voeg rendertaak toe aan de renderwachtrij. |
### add(RenderQueueGroupId groupId, IPipeline pipeline, Object renderableResource, int subEntity) {#add-com.aspose.threed.RenderQueueGroupId-com.aspose.threed.IPipeline-java.lang.Object-int-}
```
public abstract void add(RenderQueueGroupId groupId, IPipeline pipeline, Object renderableResource, int subEntity)
```


Voeg rendertaak toe aan de renderwachtrij.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| groupId | [RenderQueueGroupId](../../com.aspose.threed/renderqueuegroupid) | In welke groep van de wachtrij de rendertaak zal staan |
| pipeline | [IPipeline](../../com.aspose.threed/ipipeline) | De pipeline‑instantie die voor deze rendertaak wordt gebruikt |
| renderableResource | java.lang.Object | Aangepast object dat wordt verzonden naar [EntityRenderer](../../com.aspose.threed/entityrenderer) |
| subEntity | int | De index van sub‑entiteiten, nuttig wanneer de entiteit bestaat uit meer dan één sub‑renderbare component. |


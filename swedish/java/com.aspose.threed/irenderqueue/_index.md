---
title: IRenderQueue
second_title: Aspose.3D for Java API-referens
description: Entity renderer använder denna kö för att hantera renderingsuppgifter.
type: docs
weight: 248
url: /sv/java/com.aspose.threed/irenderqueue/
---
```
public interface IRenderQueue
```

Entity renderer använder denna kö för att hantera renderingsuppgifter.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [add(RenderQueueGroupId groupId, IPipeline pipeline, Object renderableResource, int subEntity)](#add-com.aspose.threed.RenderQueueGroupId-com.aspose.threed.IPipeline-java.lang.Object-int-) | Lägg till renderingsuppgift i renderingskön. |
### add(RenderQueueGroupId groupId, IPipeline pipeline, Object renderableResource, int subEntity) {#add-com.aspose.threed.RenderQueueGroupId-com.aspose.threed.IPipeline-java.lang.Object-int-}
```
public abstract void add(RenderQueueGroupId groupId, IPipeline pipeline, Object renderableResource, int subEntity)
```


Lägg till renderingsuppgift i renderingskön.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| groupId | [RenderQueueGroupId](../../com.aspose.threed/renderqueuegroupid) | Vilken grupp i kön renderingsuppgiften kommer att vara i |
| pipeline | [IPipeline](../../com.aspose.threed/ipipeline) | Pipeline‑instansen som används för denna renderingsuppgift |
| renderableResource | java.lang.Object | Anpassat objekt som kommer att skickas till [EntityRenderer](../../com.aspose.threed/entityrenderer) |
| subEntity | int | Indexet för subenheter, användbart när entiteten består av mer än en subrenderbar komponent. |


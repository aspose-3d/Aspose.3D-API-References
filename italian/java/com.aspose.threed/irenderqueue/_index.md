---
title: IRenderQueue
second_title: Aspose.3D for Java API Reference
description: Il renderer di entità utilizza questa coda per gestire i compiti di rendering.
type: docs
weight: 248
url: /it/java/com.aspose.threed/irenderqueue/
---
```
public interface IRenderQueue
```

Il renderer di entità utilizza questa coda per gestire i compiti di rendering.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [add(RenderQueueGroupId groupId, IPipeline pipeline, Object renderableResource, int subEntity)](#add-com.aspose.threed.RenderQueueGroupId-com.aspose.threed.IPipeline-java.lang.Object-int-) | Aggiungi il render task alla coda di rendering. |
### add(RenderQueueGroupId groupId, IPipeline pipeline, Object renderableResource, int subEntity) {#add-com.aspose.threed.RenderQueueGroupId-com.aspose.threed.IPipeline-java.lang.Object-int-}
```
public abstract void add(RenderQueueGroupId groupId, IPipeline pipeline, Object renderableResource, int subEntity)
```


Aggiungi il render task alla coda di rendering.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| groupId | [RenderQueueGroupId](../../com.aspose.threed/renderqueuegroupid) | Quale gruppo della coda conterrà il render task |
| pipeline | [IPipeline](../../com.aspose.threed/ipipeline) | L'istanza della pipeline utilizzata per questo render task |
| renderableResource | java.lang.Object | Oggetto personalizzato che sarà inviato a [EntityRenderer](../../com.aspose.threed/entityrenderer) |
| subEntity | int | L'indice delle sub entities, utile quando l'entità è composta da più componenti renderizzabili |


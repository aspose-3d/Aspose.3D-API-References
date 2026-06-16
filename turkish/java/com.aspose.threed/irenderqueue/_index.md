---
title: "IRenderQueue"
second_title: "Aspose.3D for Java API Referansı"
description: "Varlık renderlayıcı, render görevlerini yönetmek için bu kuyruğu kullanır."
type: docs
weight: 248
url: /tr/java/com.aspose.threed/irenderqueue/
---
```
public interface IRenderQueue
```

Varlık renderlayıcı, render görevlerini yönetmek için bu kuyruğu kullanır.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [add(RenderQueueGroupId groupId, IPipeline pipeline, Object renderableResource, int subEntity)](#add-com.aspose.threed.RenderQueueGroupId-com.aspose.threed.IPipeline-java.lang.Object-int-) | Render görevini render kuyruğuna ekle. |
### add(RenderQueueGroupId groupId, IPipeline pipeline, Object renderableResource, int subEntity) {#add-com.aspose.threed.RenderQueueGroupId-com.aspose.threed.IPipeline-java.lang.Object-int-}
```
public abstract void add(RenderQueueGroupId groupId, IPipeline pipeline, Object renderableResource, int subEntity)
```


Render görevini render kuyruğuna ekle.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| groupId | [RenderQueueGroupId](../../com.aspose.threed/renderqueuegroupid) | Render görevinin bulunacağı kuyruğun hangi grubu |
| pipeline | [IPipeline](../../com.aspose.threed/ipipeline) | Bu render görevi için kullanılan pipeline örneği |
| renderableResource | java.lang.Object | Gönderilecek özel nesne [EntityRenderer](../../com.aspose.threed/entityrenderer) |
| subEntity | int | Alt varlıkların indeksi, varlık birden fazla alt renderlanabilir bileşenden oluştuğunda faydalıdır. |


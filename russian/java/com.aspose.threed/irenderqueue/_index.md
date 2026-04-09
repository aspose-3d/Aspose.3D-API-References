---
title: IRenderQueue
second_title: Справочник API Aspose.3D для Java
description: Рендерер сущностей использует эту очередь для управления задачами рендеринга.
type: docs
weight: 248
url: /ru/java/com.aspose.threed/irenderqueue/
---
```
public interface IRenderQueue
```

Рендерер сущностей использует эту очередь для управления задачами рендеринга.
## Методы

| Метод | Описание |
| --- | --- |
| [add(RenderQueueGroupId groupId, IPipeline pipeline, Object renderableResource, int subEntity)](#add-com.aspose.threed.RenderQueueGroupId-com.aspose.threed.IPipeline-java.lang.Object-int-) | Добавить задачу рендеринга в очередь рендеринга. |
### add(RenderQueueGroupId groupId, IPipeline pipeline, Object renderableResource, int subEntity) {#add-com.aspose.threed.RenderQueueGroupId-com.aspose.threed.IPipeline-java.lang.Object-int-}
```
public abstract void add(RenderQueueGroupId groupId, IPipeline pipeline, Object renderableResource, int subEntity)
```


Добавить задачу рендеринга в очередь рендеринга.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| groupId | [RenderQueueGroupId](../../com.aspose.threed/renderqueuegroupid) | В какую группу очереди будет помещена задача рендеринга |
| pipeline | [IPipeline](../../com.aspose.threed/ipipeline) | Экземпляр конвейера, используемый для этой задачи рендеринга |
| renderableResource | java.lang.Object | Пользовательский объект, который будет отправлен в [EntityRenderer](../../com.aspose.threed/entityrenderer) |
| subEntity | int | Индекс под‑сущностей, полезный, когда объект состоит из более чем одного под‑рендерируемого компонента. |


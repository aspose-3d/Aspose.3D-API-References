---
title: "IRenderQueue.Add"
second_title: "Справочник API Aspose.3D для .NET"
description: "Метод IRenderQueue. Добавляет задачу рендеринга в очередь рендеринга."
type: docs
weight: 10
url: /ru/net/aspose.threed.render/irenderqueue/add/
---
## IRenderQueue.Add method

Добавьте задачу рендеринга в очередь рендеринга.

```csharp
public void Add(RenderQueueGroupId groupId, IPipeline pipeline, object renderableResource, 
    int subEntity)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| groupId | RenderQueueGroupId | В какой группе очереди будет находиться задача рендеринга. |
| конвейер | IPipeline | Экземпляр конвейера, используемый для этой задачи рендеринга |
| renderableResource | Object | Пользовательский объект, который будет отправлен в [`RenderEntity`](../../entityrenderer/renderentity/) |
| subEntity | Int32 | Индекс под-сущностей, полезный, когда сущность состоит более чем из одного подрендеримого компонента. |

### См. также

* enum [RenderQueueGroupId](../../renderqueuegroupid/)
* interface [IPipeline](../../ipipeline/)
* interface [IRenderQueue](../)
* namespace [Aspose.ThreeD.Render](../../irenderqueue/)
* assembly [Aspose.3D](../../../)



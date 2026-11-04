---
title: "EntityRenderer.RenderEntity"
second_title: "Справочник API Aspose.3D для .NET"
description: "Метод EntityRenderer. Каждая задача рендеринга, помещённая в IRenderQueue, будет иметь соответствующий вызов RenderEntity для выполнения конкретной задачи рендеринга"
type: docs
weight: 70
url: /ru/net/aspose.threed.render/entityrenderer/renderentity/
---
## EntityRenderer.RenderEntity method

Каждая задача рендеринга, помещённая в [`IRenderQueue`](../../irenderqueue/), будет иметь соответствующий вызов RenderEntity для выполнения конкретной задачи рендеринга.

```csharp
public virtual void RenderEntity(Renderer renderer, ICommandList commandList, Node node, 
    object renderableResource, int subEntity)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| renderer | Renderer | Рендерер |
| commandList | ICommandList | commandList, используемый для записи команд рендеринга |
| узел | Узел | Тот же узел, который передан в PrepareRenderQueue сущности, которая будет отрисована |
| renderableResource | Объект | Пользовательский объект, переданный в IRenderQueue во время PrepareRenderQueue |
| subEntity | Int32 | Индекс под‑сущности, переданной в IRenderQueue |

### См. также

* class [Renderer](../../renderer/)
* interface [ICommandList](../../icommandlist/)
* class [Node](../../../aspose.threed/node/)
* class [EntityRenderer](../)
* namespace [Aspose.ThreeD.Render](../../entityrenderer/)
* assembly [Aspose.3D](../../../)



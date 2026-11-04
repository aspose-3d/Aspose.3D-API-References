---
title: "Класс EntityRenderer"
second_title: "Справочник API Aspose.3D для .NET"
description: "Класс Aspose.ThreeD.Render.EntityRenderer. Наследуйте его для реализации рендеринга различных типов сущностей"
type: docs
weight: 1970
url: /ru/net/aspose.threed.render/entityrenderer/
---
## EntityRenderer class

Создайте подкласс, чтобы реализовать рендеринг для разных типов сущностей.

```csharp
public class EntityRenderer
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [EntityRenderer](entityrenderer/#constructor)(string) | Конструктор `EntityRenderer` |
| [EntityRenderer](entityrenderer/#constructor_1)(string, EntityRendererFeatures) | Конструктор `EntityRenderer` |

## Методы

| Имя | Описание |
| --- | --- |
| virtual [Dispose](../../aspose.threed.render/entityrenderer/dispose/)() | Рендерер сущностей освобождается, освобождайте общие ресурсы. |
| virtual [FrameBegin](../../aspose.threed.render/entityrenderer/framebegin/)(Renderer, IRenderQueue) | Начать рендеринг кадра |
| virtual [FrameEnd](../../aspose.threed.render/entityrenderer/frameend/)(Renderer, IRenderQueue) | Завершить рендеринг кадра |
| virtual [Initialize](../../aspose.threed.render/entityrenderer/initialize/)(Renderer) | Инициализировать рендерер сущностей |
| virtual [PrepareRenderQueue](../../aspose.threed.render/entityrenderer/preparerenderqueue/)(Renderer, IRenderQueue, Node, Entity) | Подготовить команды рендеринга для указанной пары узел/сущность. |
| virtual [RenderEntity](../../aspose.threed.render/entityrenderer/renderentity/)(Renderer, ICommandList, Node, object, int) | Каждая задача рендеринга, помещённая в [`IRenderQueue`](../irenderqueue/), будет иметь соответствующий вызов RenderEntity для выполнения конкретной задачи рендеринга. |
| virtual [ResetSceneCache](../../aspose.threed.render/entityrenderer/resetscenecache/)() | Сцена была изменена или удалена, необходимо освободить ресурсы рендеринга уровня сцены в этом случае. |

### См. также

* namespace [Aspose.ThreeD.Render](../../aspose.threed.render/)
* assembly [Aspose.3D](../../)



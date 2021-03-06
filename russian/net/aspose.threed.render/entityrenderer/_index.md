---
title: EntityRenderer
second_title: Справочник по Aspose.3D для .NET API
description: Подкласс этого класса для реализации рендеринга различных типов сущностей.
type: docs
weight: 1770
url: /ru/net/aspose.threed.render/entityrenderer/
---
## EntityRenderer class

Подкласс этого класса для реализации рендеринга различных типов сущностей.

```csharp
public class EntityRenderer
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [EntityRenderer](entityrenderer#constructor)(string) | Конструктор[`EntityRenderer`](../entityrenderer) |
| [EntityRenderer](entityrenderer#constructor_1)(string, EntityRendererFeatures) | Конструктор[`EntityRenderer`](../entityrenderer) |

## Методы

| Имя | Описание |
| --- | --- |
| virtual [Dispose](../../aspose.threed.render/entityrenderer/dispose)() | Рендерер сущностей удаляется, освободите общие ресурсы. |
| virtual [FrameBegin](../../aspose.threed.render/entityrenderer/framebegin)(Renderer, IRenderQueue) | Начать рендеринг кадра |
| virtual [FrameEnd](../../aspose.threed.render/entityrenderer/frameend)(Renderer, IRenderQueue) | Завершает рендеринг кадра |
| virtual [Initialize](../../aspose.threed.render/entityrenderer/initialize)(Renderer) | Инициализировать средство визуализации объектов |
| virtual [PrepareRenderQueue](../../aspose.threed.render/entityrenderer/preparerenderqueue)(Renderer, IRenderQueue, Node, Entity) | Подготовить команды рендеринга для указанной пары узел/сущность. |
| virtual [RenderEntity](../../aspose.threed.render/entityrenderer/renderentity)(Renderer, ICommandList, Node, object, int) | Каждая задача рендеринга, помещенная в[`IRenderQueue`](../irenderqueue), будет иметь соответствующий вызов RenderEntity для выполнения конкретной работы по рендерингу. |
| virtual [ResetSceneCache](../../aspose.threed.render/entityrenderer/resetscenecache)() | Сцена была изменена или удалена, необходимо разместить в ней ресурсы рендеринга на уровне сцены |

### Смотрите также

* пространство имен [Aspose.ThreeD.Render](../../aspose.threed.render)
* сборка [Aspose.3D](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.3D.dll -->

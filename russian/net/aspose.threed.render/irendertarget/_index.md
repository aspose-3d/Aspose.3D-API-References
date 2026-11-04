---
title: "Интерфейс IRenderTarget"
second_title: "Справочник API Aspose.3D для .NET"
description: "Интерфейс Aspose.ThreeD.Render.IRenderTarget. Базовый интерфейс цели рендеринга."
type: docs
weight: 2080
url: /ru/net/aspose.threed.render/irendertarget/
---
## IRenderTarget interface

Базовый интерфейс целевого рендеринга

```csharp
public interface IRenderTarget : IDisposable
```

## Свойства

| Имя | Описание |
| --- | --- |
| [Size](../../aspose.threed.render/irendertarget/size/) { get; set; } | Получает или задает размер цели рендеринга. |
| [Viewports](../../aspose.threed.render/irendertarget/viewports/) { get; } | Получает все области просмотра, связанные с этой целью рендеринга. |

## Методы

| Имя | Описание |
| --- | --- |
| [CreateViewport](../../aspose.threed.render/irendertarget/createviewport/#createviewport)(Camera) | Создаёт область просмотра в заданной перспективе камеры. |
| [CreateViewport](../../aspose.threed.render/irendertarget/createviewport/#createviewport_1)(Camera, RelativeRectangle) | Создаёт область просмотра с позицией/размером в заданной перспективе камеры. |
| [CreateViewport](../../aspose.threed.render/irendertarget/createviewport/#createviewport_2)(Camera, Vector3, RelativeRectangle) | Создаёт область просмотра с указанным цветом фона и позицией/размером в заданной перспективе камеры. |

### См. также

* namespace [Aspose.ThreeD.Render](../../aspose.threed.render/)
* assembly [Aspose.3D](../../)



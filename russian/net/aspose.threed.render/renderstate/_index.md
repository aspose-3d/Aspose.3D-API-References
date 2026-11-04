---
title: "Класс RenderState"
second_title: "Справочник API Aspose.3D для .NET"
description: "Класс Aspose.ThreeD.Render.RenderState. Состояние рендеринга для построения конвейера. Изменения, внесённые в состояние рендеринга, не повлияют на созданные экземпляры конвейера."
type: docs
weight: 2330
url: /ru/net/aspose.threed.render/renderstate/
---
## RenderState class

Состояние рендеринга для построения конвейера. Изменения, внесённые в состояние рендеринга, не повлияют на созданные экземпляры конвейера.

```csharp
public class RenderState : IComparable<RenderState>, IDisposable
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [RenderState](renderstate/)() | Конструктор `RenderState` |

## Свойства

| Имя | Описание |
| --- | --- |
| [Blend](../../aspose.threed.render/renderstate/blend/) { get; set; } | Включить или отключить смешивание фрагментов. |
| [BlendColor](../../aspose.threed.render/renderstate/blendcolor/) { get; set; } | Получает или задаёт цвет смешивания, используемый в ConstantColor |
| [CullFace](../../aspose.threed.render/renderstate/cullface/) { get; set; } | Включить или отключить отсечение граней |
| [CullFaceMode](../../aspose.threed.render/renderstate/cullfacemode/) { get; set; } | Получает или задаёт, какая грань будет отсеяна. |
| [DepthFunction](../../aspose.threed.render/renderstate/depthfunction/) { get; set; } | Получает или задаёт функцию сравнения, используемую в тесте глубины |
| [DepthMask](../../aspose.threed.render/renderstate/depthmask/) { get; set; } | Включить или отключить запись глубины. |
| [DepthTest](../../aspose.threed.render/renderstate/depthtest/) { get; set; } | Включить или отключить тест глубины. |
| [DestinationBlendFactor](../../aspose.threed.render/renderstate/destinationblendfactor/) { get; set; } | Получает или задаёт способ смешивания цвета. |
| [FrontFace](../../aspose.threed.render/renderstate/frontface/) { get; set; } | Получает или задаёт, какой порядок считается передней гранью. |
| [PolygonMode](../../aspose.threed.render/renderstate/polygonmode/) { get; set; } | Получает или задаёт режим рендеринга полигона. |
| [ScissorTest](../../aspose.threed.render/renderstate/scissortest/) { get; set; } | Включить или отключить тест ножниц |
| [SourceBlendFactor](../../aspose.threed.render/renderstate/sourceblendfactor/) { get; set; } | Получает или задаёт способ смешивания цвета. |
| [StencilBackFace](../../aspose.threed.render/renderstate/stencilbackface/) { get; } | Получает состояние трафарета для задней грани. |
| [StencilFrontFace](../../aspose.threed.render/renderstate/stencilfrontface/) { get; } | Получает состояние трафарета для передней грани. |
| [StencilMask](../../aspose.threed.render/renderstate/stencilmask/) { get; set; } | Получает или задаёт маску, которая И‑логически применяется к обоим — эталонному и сохранённому — значению трафарета при выполнении теста. |
| [StencilReference](../../aspose.threed.render/renderstate/stencilreference/) { get; set; } | Получает или задаёт эталонное значение для теста трафарета. |
| [StencilTest](../../aspose.threed.render/renderstate/stenciltest/) { get; set; } | Включить или отключить тест трафарета. |

## Методы

| Имя | Описание |
| --- | --- |
| [CompareTo](../../aspose.threed.render/renderstate/compareto/)(RenderState) | Сравнить состояние рендеринга с другим экземпляром |
| [Dispose](../../aspose.threed.render/renderstate/dispose/)() | Освободите `RenderState` и освободите все внутренние ресурсы. |
| override [Equals](../../aspose.threed.render/renderstate/equals/)(object) | Возвращает значение, указывающее, равен ли этот экземпляр указанному объекту. |
| override [GetHashCode](../../aspose.threed.render/renderstate/gethashcode/)() | Возвращает хеш-код этого экземпляра. |

### См. также

* namespace [Aspose.ThreeD.Render](../../aspose.threed.render/)
* assembly [Aspose.3D](../../)



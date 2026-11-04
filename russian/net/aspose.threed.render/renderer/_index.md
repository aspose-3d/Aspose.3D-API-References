---
title: "Класс Renderer"
second_title: "Справочник API Aspose.3D для .NET"
description: "Класс Aspose.ThreeD.Render.Renderer. Контекст, относящийся к рендереру"
type: docs
weight: 2340
url: /ru/net/aspose.threed.render/renderer/
---
## Renderer class

Контекст рендерера.

```csharp
public abstract class Renderer : IDisposable
```

## Свойства

| Имя | Описание |
| --- | --- |
| [AssetDirectories](../../aspose.threed.render/renderer/assetdirectories/) { get; } | Каталоги, содержащие внешние ресурсы |
| [EnableShadows](../../aspose.threed.render/renderer/enableshadows/) { get; set; } | Получает или задает, включены ли тени. |
| [FallbackEntityRenderer](../../aspose.threed.render/renderer/fallbackentityrenderer/) { get; set; } | Получает или задает резервный рендерер сущности, когда для сущности не определён специальный рендерер. |
| virtual [Frustum](../../aspose.threed.render/renderer/frustum/) { get; set; } | Получает или задает фрустум, используемый для предоставления матрицы просмотра. |
| virtual [Material](../../aspose.threed.render/renderer/material/) { get; set; } | Получает или задает материал, используемый для предоставления информации о материале, используемой шейдерами. |
| [Node](../../aspose.threed.render/renderer/node/) { get; set; } | Получает или задает экземпляр [`Node`](./node/), используемый для предоставления матрицы мирового преобразования. |
| [PostProcessings](../../aspose.threed.render/renderer/postprocessings/) { get; } | Активная цепочка постобработки |
| [PresetShaders](../../aspose.threed.render/renderer/presetshaders/) { get; set; } | Получает или задает предустановленный набор шейдеров |
| abstract [RenderFactory](../../aspose.threed.render/renderer/renderfactory/) { get; } | Получает фабрику для создания объектов, связанных с рендерингом. |
| [RenderStage](../../aspose.threed.render/renderer/renderstage/) { get; } | Получает текущий этап рендеринга. |
| [RenderTarget](../../aspose.threed.render/renderer/rendertarget/) { get; } | Укажите целевой объект рендеринга, на котором будут выполнены последующие операции рендеринга. |
| [Shader](../../aspose.threed.render/renderer/shader/) { get; set; } | Получает или задает экземпляр шейдера, используемый для рендеринга геометрии. |
| [ShaderSet](../../aspose.threed.render/renderer/shaderset/) { get; set; } | Получает или задает набор шейдеров, используемый для рендеринга сцены |
| [Variables](../../aspose.threed.render/renderer/variables/) { get; } | Доступ к внутренним переменным, используемым для рендеринга |

## Методы

| Имя | Описание |
| --- | --- |
| static [CreateRenderer](../../aspose.threed.render/renderer/createrenderer/)() | Создаёт новый `Renderer` с профилем по умолчанию. |
| virtual [ClearCache](../../aspose.threed.render/renderer/clearcache/)() | Вручную очистите кэш. Aspose.3D будет кэшировать некоторые объекты, такие как материалы/геометрии, во внутренние типы, совместимые с конвейером рендеринга. Это следует вызывать вручную, когда сцена претерпевает значительные изменения. |
| [Dispose](../../aspose.threed.render/renderer/dispose/)() | Освободите `Renderer` и все связанные ресурсы |
| abstract [Execute](../../aspose.threed.render/renderer/execute/)(PostProcessing, IRenderTarget) | Выполните постобработку на указанном целевом объекте рендеринга |
| [GetPostProcessing](../../aspose.threed.render/renderer/getpostprocessing/)(string) | Получает встроенный постпроцессор, поддерживаемый рендерером. |
| virtual [RegisterEntityRenderer](../../aspose.threed.render/renderer/registerentityrenderer/)(EntityRenderer) | Зарегистрируйте рендерер сущности для указанной сущности |
| virtual [Render](../../aspose.threed.render/renderer/render/)(IRenderTarget) | Отрендерите указанный объект |

### См. также

* namespace [Aspose.ThreeD.Render](../../aspose.threed.render/)
* assembly [Aspose.3D](../../)



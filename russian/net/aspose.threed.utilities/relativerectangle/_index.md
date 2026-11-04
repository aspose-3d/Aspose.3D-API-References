---
title: "Структура RelativeRectangle"
second_title: "Справочник API Aspose.3D для .NET"
description: "Aspose.ThreeD.Utilities.RelativeRectangle struct. Relative rectangle Формула преобразования относительного компонента в абсолютное значение: Scale * Reference Width + offset. Поэтому, если мы хотим представить абсолютное значение, оставьте все поля масштабирования нулевыми и используйте поля смещения вместо этого."
type: docs
weight: 2830
url: /ru/net/aspose.threed.utilities/relativerectangle/
---
## RelativeRectangle structure

Относительный прямоугольник Формула преобразования относительного компонента в абсолютное значение: Scale * (Reference Width) + offset. Поэтому, если мы хотим представить абсолютное значение, оставьте все поля масштаба равными нулю и используйте вместо этого поля смещения.

```csharp
public struct RelativeRectangle
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [RelativeRectangle](relativerectangle/)(int, int, int, int) | Создать `RelativeRectangle` |

## Свойства

| Имя | Описание |
| --- | --- |
| [OffsetHeight](../../aspose.threed.utilities/relativerectangle/offsetheight/) { get; set; } | Получает или задает смещение по высоте |
| [OffsetWidth](../../aspose.threed.utilities/relativerectangle/offsetwidth/) { get; set; } | Получает или задает смещение по ширине |
| [OffsetX](../../aspose.threed.utilities/relativerectangle/offsetx/) { get; set; } | Получает или задает смещение по координате X |
| [OffsetY](../../aspose.threed.utilities/relativerectangle/offsety/) { get; set; } | Получает или задает смещение по координате Y |
| [ScaleHeight](../../aspose.threed.utilities/relativerectangle/scaleheight/) { get; set; } | Относительная высота |
| [ScaleWidth](../../aspose.threed.utilities/relativerectangle/scalewidth/) { get; set; } | Относительная ширина |
| [ScaleX](../../aspose.threed.utilities/relativerectangle/scalex/) { get; set; } | Относительная координата X |
| [ScaleY](../../aspose.threed.utilities/relativerectangle/scaley/) { get; set; } | Относительная координата Y |

## Методы

| Имя | Описание |
| --- | --- |
| static [FromScale](../../aspose.threed.utilities/relativerectangle/fromscale/)(float, float, float, float) | Создать `RelativeRectangle` со всеми полями смещения, равными нулю, и полями масштабирования, заданными из переданных параметров. |
| [ToAbsolute](../../aspose.threed.utilities/relativerectangle/toabsolute/)(int, int, int, int) | Преобразовать относительный прямоугольник в абсолютный |
| override [ToString](../../aspose.threed.utilities/relativerectangle/tostring/)() | Преобразует значение этого экземпляра в строку. |

### См. также

* namespace [Aspose.ThreeD.Utilities](../../aspose.threed.utilities/)
* assembly [Aspose.3D](../../)



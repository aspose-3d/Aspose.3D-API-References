---
title: RelativeRectangle
second_title: Справочник по Aspose.3D для .NET API
description: Относительный прямоугольник Формула между относительным компонентом и абсолютным значением Масштаб  Эталонная ширина  смещение Поэтому если мы хотим чтобы оно представляло абсолютное значение оставьте все поля масштаба равными нулю и вместо этого используйте поля смещения.
type: docs
weight: 2600
url: /ru/net/aspose.threed.utilities/relativerectangle/
---
## RelativeRectangle structure

Относительный прямоугольник Формула между относительным компонентом и абсолютным значением: Масштаб * (Эталонная ширина) + смещение Поэтому, если мы хотим, чтобы оно представляло абсолютное значение, оставьте все поля масштаба равными нулю и вместо этого используйте поля смещения.

```csharp
public struct RelativeRectangle
```

## Характеристики

| Имя | Описание |
| --- | --- |
| [OffsetHeight](../../aspose.threed.utilities/relativerectangle/offsetheight) { get; set; } | Получает или задает смещение для height |
| [OffsetWidth](../../aspose.threed.utilities/relativerectangle/offsetwidth) { get; set; } | Получает или задает смещение для width |
| [OffsetX](../../aspose.threed.utilities/relativerectangle/offsetx) { get; set; } | Получает или задает смещение для координаты X |
| [OffsetY](../../aspose.threed.utilities/relativerectangle/offsety) { get; set; } | Получает или задает смещение для координаты Y |
| [ScaleHeight](../../aspose.threed.utilities/relativerectangle/scaleheight) { get; set; } | Относительная высота |
| [ScaleWidth](../../aspose.threed.utilities/relativerectangle/scalewidth) { get; set; } | Относительная ширина |
| [ScaleX](../../aspose.threed.utilities/relativerectangle/scalex) { get; set; } | Относительная координата X |
| [ScaleY](../../aspose.threed.utilities/relativerectangle/scaley) { get; set; } | Относительная координата Y |

## Методы

| Имя | Описание |
| --- | --- |
| static [FromScale](../../aspose.threed.utilities/relativerectangle/fromscale)(float, float, float, float) | Построить[`RelativeRectangle`](../relativerectangle) со всеми полями смещения нулями и полями масштаба из заданных параметров. |
| [ToAbsolute](../../aspose.threed.utilities/relativerectangle/toabsolute#toabsolute)(Rectangle) | Преобразование относительного прямоугольника в абсолютный прямоугольник |
| [ToAbsolute](../../aspose.threed.utilities/relativerectangle/toabsolute#toabsolute_1)(Size) | Преобразование относительного прямоугольника в абсолютный прямоугольник |
| override [ToString](../../aspose.threed.utilities/relativerectangle/tostring)() | Преобразует значение этого экземпляра вString. |

### Смотрите также

* пространство имен [Aspose.ThreeD.Utilities](../../aspose.threed.utilities)
* сборка [Aspose.3D](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.3D.dll -->

---
title: BoundingBox
second_title: Справочник по Aspose.3D для .NET API
description: Выровненная по оси ограничительная рамка
type: docs
weight: 2420
url: /ru/net/aspose.threed.utilities/boundingbox/
---
## BoundingBox structure

Выровненная по оси ограничительная рамка

```csharp
public struct BoundingBox
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [BoundingBox](boundingbox#constructor)(Vector3, Vector3) | Инициализировать конечную ограничивающую рамку с заданным минимальным и максимальным значением угла |
| [BoundingBox](boundingbox#constructor_1)(double, double, double, double, double, double) | Инициализировать конечную ограничивающую рамку с заданным минимальным и максимальным значением угла |

## Характеристики

| Имя | Описание |
| --- | --- |
| [Center](../../aspose.threed.utilities/boundingbox/center) { get; } | Центр ограничивающей рамки. |
| [Extent](../../aspose.threed.utilities/boundingbox/extent) { get; } | Получает размер ограничивающей рамки. |
| [Maximum](../../aspose.threed.utilities/boundingbox/maximum) { get; } | Максимальный угол ограничивающей рамки |
| [Minimum](../../aspose.threed.utilities/boundingbox/minimum) { get; } | Минимальный угол ограничивающей рамки |
| [Size](../../aspose.threed.utilities/boundingbox/size) { get; } | Размер ограничивающей рамки |

## Методы

| Имя | Описание |
| --- | --- |
| static [FromGeometry](../../aspose.threed.utilities/boundingbox/fromgeometry)(Geometry) | Построить ограничивающую рамку из заданной геометрии |
| override [Equals](../../aspose.threed.utilities/boundingbox/equals)(object) | Определяет, равны ли два объекта |
| override [GetHashCode](../../aspose.threed.utilities/boundingbox/gethashcode)() | Возвращает хэш-код для этого экземпляра |
| override [ToString](../../aspose.threed.utilities/boundingbox/tostring)() | Получает строковое представление ограничивающей рамки. |
| [operator *](../../aspose.threed.utilities/boundingbox/op_multiply) | Перегрузка оператора для Multiple |

## Поля

| Имя | Описание |
| --- | --- |
| static readonly [Infinite](../../aspose.threed.utilities/boundingbox/infinite) | Бесконечная ограничивающая рамка |
| static readonly [Null](../../aspose.threed.utilities/boundingbox/null) | Нулевой ограничивающий прямоугольник |

### Смотрите также

* пространство имен [Aspose.ThreeD.Utilities](../../aspose.threed.utilities)
* сборка [Aspose.3D](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.3D.dll -->

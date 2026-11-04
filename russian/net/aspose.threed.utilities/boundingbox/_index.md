---
title: "Структура BoundingBox"
second_title: "Справочник API Aspose.3D для .NET"
description: "Структура Aspose.ThreeD.Utilities.BoundingBox. Осиально-выравненный ограничивающий параллелепипед"
type: docs
weight: 2670
url: /ru/net/aspose.threed.utilities/boundingbox/
---
## BoundingBox structure

Осиально-выравненный ограничивающий прямоугольник

```csharp
public struct BoundingBox
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [BoundingBox](boundingbox/#constructor)(Vector3, Vector3) | Инициализировать конечный ограничивающий параллелепипед с заданными минимальным и максимальным углом |
| [BoundingBox](boundingbox/#constructor_1)(double, double, double, double, double, double) | Инициализировать конечный ограничивающий параллелепипед с заданными минимальным и максимальным углом |

## Свойства

| Имя | Описание |
| --- | --- |
| static [Infinite](../../aspose.threed.utilities/boundingbox/infinite/) { get; } | Бесконечный ограничивающий параллелепипед |
| static [Null](../../aspose.threed.utilities/boundingbox/null/) { get; } | Пустой ограничивающий параллелепипед |
| [Center](../../aspose.threed.utilities/boundingbox/center/) { get; } | Центр ограничивающего параллелепипеда. |
| [Extent](../../aspose.threed.utilities/boundingbox/extent/) { get; } | Получает размер ограничивающего параллелепипеда. |
| [Maximum](../../aspose.threed.utilities/boundingbox/maximum/) { get; } | Максимальный угол ограничивающего параллелепипеда |
| [Minimum](../../aspose.threed.utilities/boundingbox/minimum/) { get; } | Минимальный угол ограничивающего параллелепипеда |
| [Size](../../aspose.threed.utilities/boundingbox/size/) { get; } | Размер ограничивающего параллелепипеда |

## Методы

| Имя | Описание |
| --- | --- |
| static [FromGeometry](../../aspose.threed.utilities/boundingbox/fromgeometry/)(Geometry) | Создайте ограничивающий параллелепипед из заданной геометрии |
| [Contains](../../aspose.threed.utilities/boundingbox/contains/#contains)(BoundingBox) | Ограничивающий параллелепипед для проверки, находится ли он внутри текущего ограничивающего параллелепипеда. |
| [Contains](../../aspose.threed.utilities/boundingbox/contains/#contains_1)(Vector3) | Проверьте, находится ли точка p внутри ограничивающего параллелепипеда |
| override [Equals](../../aspose.threed.utilities/boundingbox/equals/)(object) | Определяет, равны ли два объекта |
| override [GetHashCode](../../aspose.threed.utilities/boundingbox/gethashcode/)() | Возвращает хеш‑код для этого экземпляра |
| [Merge](../../aspose.threed.utilities/boundingbox/merge/#merge)(BoundingBox) | Объединяет новый параллелепипед с текущим ограничивающим параллелепипедом. |
| [Merge](../../aspose.threed.utilities/boundingbox/merge/#merge_1)(Vector3) | Объедините текущий ограничивающий параллелепипед с заданной точкой |
| [Merge](../../aspose.threed.utilities/boundingbox/merge/#merge_2)(Vector4) | Объедините текущий ограничивающий параллелепипед с заданной точкой |
| [Merge](../../aspose.threed.utilities/boundingbox/merge/#merge_3)(double, double, double) | Объедините текущий ограничивающий параллелепипед с заданной точкой |
| [OverlapsWith](../../aspose.threed.utilities/boundingbox/overlapswith/)(BoundingBox) | Проверьте, пересекается ли текущий ограничивающий прямоугольник с указанным ограничивающим прямоугольником. |
| [Scale](../../aspose.threed.utilities/boundingbox/scale/)() | Вычисляет абсолютное наибольшее значение координаты любой содержащейся точки. |
| override [ToString](../../aspose.threed.utilities/boundingbox/tostring/)() | Получает строковое представление ограничивающего параллелепипеда. |
| [operator *](../../aspose.threed.utilities/boundingbox/op_multiply/) | Перегрузка оператора умножения, минимальный и максимальный угол нового ограничивающего прямоугольника будут трансформированы матрицей. |

## Примеры

Следующий код показывает, как получить ограничивающий прямоугольник из экземпляра Entity.

```csharp
var sphere = new Sphere();
var boundingBox = sphere.GetBoundingBox();
Console.WriteLine("Bounding box = " + boundingBox);
```

### См. также

* namespace [Aspose.ThreeD.Utilities](../../aspose.threed.utilities/)
* assembly [Aspose.3D](../../)



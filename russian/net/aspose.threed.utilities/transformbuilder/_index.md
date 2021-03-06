---
title: TransformBuilder
second_title: Справочник по Aspose.3D для .NET API
description: TransformBuilder./transformbuilderиспользуется для построения матрицы преобразования по цепочке преобразований.
type: docs
weight: 2630
url: /ru/net/aspose.threed.utilities/transformbuilder/
---
## TransformBuilder class

[`TransformBuilder`](../transformbuilder)используется для построения матрицы преобразования по цепочке преобразований.

```csharp
public class TransformBuilder
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [TransformBuilder](transformbuilder#constructor)(ComposeOrder) | Создать объект[`TransformBuilder`](../transformbuilder)с исходной матрицей преобразования идентичности и указанным порядком компоновки |
| [TransformBuilder](transformbuilder#constructor_1)(Matrix4, ComposeOrder) | Создать объект[`TransformBuilder`](../transformbuilder)с исходной матрицей преобразования и указанным порядком компоновки |

## Характеристики

| Имя | Описание |
| --- | --- |
| [ComposeOrder](../../aspose.threed.utilities/transformbuilder/composeorder) { get; set; } | Получает или задает порядок составления цепочки. |
| [Matrix](../../aspose.threed.utilities/transformbuilder/matrix) { get; set; } | Получает или устанавливает текущее значение матрицы |

## Методы

| Имя | Описание |
| --- | --- |
| [Append](../../aspose.threed.utilities/transformbuilder/append)(Matrix4) | Добавить новую матрицу преобразования в цепочку преобразования. |
| [Compose](../../aspose.threed.utilities/transformbuilder/compose)(Matrix4) | Добавить или добавить аргумент к внутренней матрице. |
| [Prepend](../../aspose.threed.utilities/transformbuilder/prepend)(Matrix4) | Добавить новую матрицу преобразования в цепочку преобразования. |
| [Rearrange](../../aspose.threed.utilities/transformbuilder/rearrange)(Axis, Axis, Axis) | Переставить компоновку оси. |
| [Reset](../../aspose.threed.utilities/transformbuilder/reset)() | Сбросить преобразование в единичную матрицу |
| [Rotate](../../aspose.threed.utilities/transformbuilder/rotate)(Quaternion) | Цепь поворота кватернионом |
| [RotateDegree](../../aspose.threed.utilities/transformbuilder/rotatedegree)(double, Vector3) | Цепь преобразования поворота в градусах |
| [RotateEulerDegree](../../aspose.threed.utilities/transformbuilder/rotateeulerdegree)(double, double, double) | Цепочка вращения на углы Эйлера в градусах |
| [RotateEulerRadian](../../aspose.threed.utilities/transformbuilder/rotateeulerradian#rotateeulerradian)(Vector3) | Цепочка поворотов на углы Эйлера в радианах |
| [RotateEulerRadian](../../aspose.threed.utilities/transformbuilder/rotateeulerradian#rotateeulerradian_1)(double, double, double) | Цепочка поворотов на углы Эйлера в радианах |
| [RotateRadian](../../aspose.threed.utilities/transformbuilder/rotateradian)(double, Vector3) | Цепь преобразования вращения в радианах |
| [Scale](../../aspose.threed.utilities/transformbuilder/scale#scale_1)(double) | Соединить матрицу преобразования масштабирования с компонентом, масштабированным с помощью s |
| [Scale](../../aspose.threed.utilities/transformbuilder/scale#scale)(Vector3) | Цепь масштабного преобразования |
| [Scale](../../aspose.threed.utilities/transformbuilder/scale#scale_2)(double, double, double) | Цепь матрицы преобразования масштабирования |
| [Translate](../../aspose.threed.utilities/transformbuilder/translate#translate)(Vector3) | Цепь трансформаций |
| [Translate](../../aspose.threed.utilities/transformbuilder/translate#translate_1)(double, double, double) | Цепочка трансформаций |

### Смотрите также

* пространство имен [Aspose.ThreeD.Utilities](../../aspose.threed.utilities)
* сборка [Aspose.3D](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.3D.dll -->

---
title: "Класс TransformBuilder"
second_title: "Справочник API Aspose.3D для .NET"
description: "Класс Aspose.ThreeD.Utilities.TransformBuilder. TransformBuilder используется для построения матрицы преобразования цепочкой трансформаций"
type: docs
weight: 2860
url: /ru/net/aspose.threed.utilities/transformbuilder/
---
## TransformBuilder class

`TransformBuilder` используется для построения матрицы преобразования цепочкой трансформаций.

```csharp
public class TransformBuilder
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [TransformBuilder](transformbuilder/#constructor)(ComposeOrder) | Создайте `TransformBuilder` с начальной единичной матрицей преобразования и указанным порядком композиции |
| [TransformBuilder](transformbuilder/#constructor_1)(Matrix4, ComposeOrder) | Создайте `TransformBuilder` с начальной матрицей преобразования и указанным порядком композиции |

## Свойства

| Имя | Описание |
| --- | --- |
| [ComposeOrder](../../aspose.threed.utilities/transformbuilder/composeorder/) { get; set; } | Получает или задает порядок композиции цепочки. |
| [Matrix](../../aspose.threed.utilities/transformbuilder/matrix/) { get; set; } | Получает или задает текущее значение матрицы |

## Методы

| Имя | Описание |
| --- | --- |
| [Append](../../aspose.threed.utilities/transformbuilder/append/)(Matrix4) | Добавьте новую матрицу преобразования в цепочку преобразований. |
| [Compose](../../aspose.threed.utilities/transformbuilder/compose/)(Matrix4) | Добавьте или вставьте аргумент во внутреннюю матрицу. |
| [Prepend](../../aspose.threed.utilities/transformbuilder/prepend/)(Matrix4) | Вставьте новую матрицу преобразования в начало цепочки преобразований. |
| [Rearrange](../../aspose.threed.utilities/transformbuilder/rearrange/)(Axis, Axis, Axis) | Перестройте расположение осей. |
| [Reset](../../aspose.threed.utilities/transformbuilder/reset/)() | Сбросьте преобразование к единичной матрице |
| [Rotate](../../aspose.threed.utilities/transformbuilder/rotate/)(Quaternion) | Добавьте вращение с помощью кватерниона |
| [RotateDegree](../../aspose.threed.utilities/transformbuilder/rotatedegree/#rotatedegree)(double, Vector3) | Добавьте вращение в градусах |
| [RotateDegree](../../aspose.threed.utilities/transformbuilder/rotatedegree/#rotatedegree_1)(Vector3, RotationOrder) | Добавить вращение с указанным порядком |
| [RotateEulerDegree](../../aspose.threed.utilities/transformbuilder/rotateeulerdegree/)(double, double, double) | Сцепить вращение по углам Эйлера в градусах |
| [RotateEulerRadian](../../aspose.threed.utilities/transformbuilder/rotateeulerradian/#rotateeulerradian)(Vector3) | Сцепить вращение по углам Эйлера в радианах |
| [RotateEulerRadian](../../aspose.threed.utilities/transformbuilder/rotateeulerradian/#rotateeulerradian_1)(double, double, double) | Сцепить вращение по углам Эйлера в радианах |
| [RotateRadian](../../aspose.threed.utilities/transformbuilder/rotateradian/#rotateradian)(double, Vector3) | Сцепить преобразование вращения в радианах |
| [RotateRadian](../../aspose.threed.utilities/transformbuilder/rotateradian/#rotateradian_1)(Vector3, RotationOrder) | Добавить вращение с указанным порядком |
| [Scale](../../aspose.threed.utilities/transformbuilder/scale/#scale_1)(double) | Сцепить матрицу масштабирующего преобразования, где компонент масштабирован на s |
| [Scale](../../aspose.threed.utilities/transformbuilder/scale/#scale)(Vector3) | Сцепить масштабирующее преобразование |
| [Scale](../../aspose.threed.utilities/transformbuilder/scale/#scale_2)(double, double, double) | Сцепить матрицу масштабирующего преобразования |
| [Translate](../../aspose.threed.utilities/transformbuilder/translate/#translate)(Vector3) | Сцепить преобразование переноса |
| [Translate](../../aspose.threed.utilities/transformbuilder/translate/#translate_1)(double, double, double) | Сцепить преобразование переноса |

## Примеры

Следующий код показывает, как создать матрицу с помощью набора операций

```csharp
TransformBuilder tb = new TransformBuilder();
tb.Translate(10, 20, 0);
tb.Scale(10, 10, 10);
tb.RotateEulerDegree(90, 0, 0);
Console.WriteLine($"Transform Matrix: {tb.Matrix}");
```

### См. также

* namespace [Aspose.ThreeD.Utilities](../../aspose.threed.utilities/)
* assembly [Aspose.3D](../../)



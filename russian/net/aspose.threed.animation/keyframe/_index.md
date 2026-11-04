---
title: "Класс KeyFrame"
second_title: "Справочник API Aspose.3D для .NET"
description: "Класс Aspose.ThreeD.Animation.KeyFrame. Ключевой кадр в основном определяется временем и значением; для некоторых типов интерполяции также используются касательная/натяжение/смещение/непрерывность при вычислении окончательного выборочного значения. Выборочные значения в позиции времени без ключевого кадра интерполируются ключевыми кадрами между предыдущим и следующим кадрами. Значения до/после первого/последнего ключевого кадра вычисляются классом Extrapolation."
type: docs
weight: 90
url: /ru/net/aspose.threed.animation/keyframe/
---
## KeyFrame class

Ключевой кадр в основном определяется временем и значением; для некоторых типов интерполяции также используются касательная/натяжение/смещение/непрерывность при вычислении окончательного выборочного значения. Выборочные значения в позиции времени без ключевого кадра интерполируются ключевыми кадрами между предыдущим и следующим кадрами. Значения до/после первого/последнего ключевого кадра вычисляются классом [`Extrapolation`](../extrapolation/).

```csharp
public class KeyFrame
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [KeyFrame](keyframe/)(KeyframeSequence, double) | Создать новый ключевой кадр на указанной кривой |

## Свойства

| Имя | Описание |
| --- | --- |
| [Bias](../../aspose.threed.animation/keyframe/bias/) { get; set; } | Получает или задает смещение, используемое в TCB‑сплайне |
| [Continuity](../../aspose.threed.animation/keyframe/continuity/) { get; set; } | Получает или задает непрерывность, используемую в TCB‑сплайне |
| [Flat](../../aspose.threed.animation/keyframe/flat/) { get; set; } | Получает или задает, является ли ключевой кадр плоским. Ключевой кадр должен быть плоским, если следующий или предыдущий кадр имеет то же значение. Плоский ключевой кадр имеет плоские касательные и фиксированную интерполяцию. |
| [IndependentTangent](../../aspose.threed.animation/keyframe/independenttangent/) { get; set; } | Получает или задает, являются ли выходные и последующие входные касательные независимыми. |
| [Interpolation](../../aspose.threed.animation/keyframe/interpolation/) { get; set; } | Получает или задает тип интерполяции ключа, list.data[index] определяет алгоритм вычисления выборочного значения. |
| [NextInTangent](../../aspose.threed.animation/keyframe/nextintangent/) { get; set; } | Получает или задает следующую входную (левую) касательную этого ключевого кадра. |
| [NextInWeight](../../aspose.threed.animation/keyframe/nextinweight/) { get; set; } | Получает или задает следующий входной (левый) вес этого ключевого кадра. |
| [OutTangent](../../aspose.threed.animation/keyframe/outtangent/) { get; set; } | Получает или задает выходную (правую) касательную этого ключевого кадра. |
| [OutWeight](../../aspose.threed.animation/keyframe/outweight/) { get; set; } | Получает или задает выходной (правый) вес этого ключевого кадра. |
| [StepMode](../../aspose.threed.animation/keyframe/stepmode/) { get; set; } | Получает или задает режим шага ключа. Если тип интерполяции — Constant, list.data[index] определяет, значение какого ключевого кадра будет использоваться при интерполяции. PreviousValue означает, что будет использовано значение левого ключевого кадра, а NextValue — значение следующего правого ключевого кадра. |
| [TangentWeightMode](../../aspose.threed.animation/keyframe/tangentweightmode/) { get; set; } | Получает или задает режим веса касательной ключа. Выходную касательную или следующую входную касательную можно настроить, выбрав правильный [`WeightedMode`](../weightedmode/). |
| [Tension](../../aspose.threed.animation/keyframe/tension/) { get; set; } | Получает или задает натяжение, используемое в TCB‑сплайне |
| [Time](../../aspose.threed.animation/keyframe/time/) { get; set; } | Получает или задает временную позицию ключевого кадра list.data[index], измеряемую в секундах. |
| [TimeIndependentTangent](../../aspose.threed.animation/keyframe/timeindependenttangent/) { get; set; } | Получает или задает, является ли касательная независимой от времени. |
| [Value](../../aspose.threed.animation/keyframe/value/) { get; set; } | Получает или задает значение ключевого кадра. |

## Методы

| Имя | Описание |
| --- | --- |
| override [ToString](../../aspose.threed.animation/keyframe/tostring/)() | Получает строковое представление ключевого кадра |

### См. также

* namespace [Aspose.ThreeD.Animation](../../aspose.threed.animation/)
* assembly [Aspose.3D](../../)



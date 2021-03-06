---
title: Aspose.ThreeD.Animation
second_title: Справочник по Aspose.3D для .NET API
description: Пространство имен анимации Aspose.3D все классы связанные с анимацией определены в этом пространстве имен
type: docs
weight: 20
url: /ru/net/aspose.threed.animation/
---
Пространство имен анимации Aspose.3D, все классы, связанные с анимацией, определены в этом пространстве имен

## Классы

| Учебный класс | Описание |
| --- | --- |
| [AnimationChannel](./animationchannel) | Канал сопоставляет поле компонента свойства с набором последовательностей ключевых кадров |
| [AnimationClip](./animationclip) | Анимационный клип представляет собой набор анимаций. В сцене может быть один или несколько анимационных клипов. |
| [AnimationNode](./animationnode) | Aspose.3D поддерживает иерархию анимации, каждая анимация может состоять из нескольких анимаций и определения ключевого кадра анимации. [`AnimationNode`](../aspose.threed.animation/animationnode)определяет преобразование значения свойства с течением времени, например, узел анимации можно использовать для управлять преобразованием узла или другими числовыми свойствами[`A3DObject`](../aspose.threed/a3dobject)объекта. |
| [BindPoint](./bindpoint) | A[`BindPoint`](../aspose.threed.animation/bindpoint)обычно создается на свойстве объекта, некоторые типы свойств содержат несколько полей компонентов (например, поле Vector3), [`BindPoint`](../aspose.threed.animation/bindpoint)создаст канал для каждого поля компонента и соединит поле с одним или несколькими экземплярами последовательности ключевых кадров. через каналы. |
| [Extrapolation](./extrapolation) | Экстраполяция определяет, что делать, когда выборочное значение выходит за пределы диапазона, определенного первым и последним ключевыми кадрами. |
| [KeyFrame](./keyframe) | Ключевой кадр в основном определяется временем и значением, для некоторых типов интерполяции касательная/натяжение/смещение/непрерывность также используются при вычислении конечного значения выборки. Выборочные значения во временной позиции не ключевого кадра интерполируются по ключевым кадрам между предыдущим и следующим ключевыми кадрами Значение до/после первого/последнего ключевого кадра вычисляются классом[`Extrapolation`](../aspose.threed.animation/extrapolation). |
| [KeyframeSequence](./keyframesequence) | Последовательность ключевых кадров, описывающая преобразование выборочного значения во времени. |
## перечисление

| перечисление | Описание |
| --- | --- |
| [ExtrapolationType](./extrapolationtype) | Тип экстраполяции. |
| [Interpolation](./interpolation) | Тип интерполяции ключевого кадра. |
| [StepMode](./stepmode) | Пошаговый режим интерполяции. |
| [WeightedMode](./weightedmode) | Взвешенный режим. |

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.3D.dll -->

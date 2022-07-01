---
title: AnimationChannel
second_title: Справочник по Aspose.3D для .NET API
description: Канал сопоставляет поле компонента свойства с набором последовательностей ключевых кадров
type: docs
weight: 20
url: /ru/net/aspose.threed.animation/animationchannel/
---
## AnimationChannel class

Канал сопоставляет поле компонента свойства с набором последовательностей ключевых кадров

```csharp
public class AnimationChannel : IEnumerable<KeyframeSequence>
```

## Характеристики

| Имя | Описание |
| --- | --- |
| [ComponentType](../../aspose.threed.animation/animationchannel/componenttype) { get; } | Получает тип поля компонента |
| [DefaultValue](../../aspose.threed.animation/animationchannel/defaultvalue) { get; set; } | Получает или задает значение по умолчанию для канала. Если к каналу не подключены последовательности ключевых кадров, во время оценки анимации будет использоваться значение по умолчанию. Реальный сценарий:Анимация анимирует только координату x узла, y и z не изменяются, тогда значение по умолчанию будет использоваться во время полной оценки перевода. |
| [KeyframeSequences](../../aspose.threed.animation/animationchannel/keyframesequences) { get; } | Получает все последовательности ключевых кадров внутри этого канала |
| [Name](../../aspose.threed.animation/animationchannel/name) { get; } | Получает имя канала |

## Методы

| Имя | Описание |
| --- | --- |
| [AddKeyframeSequence](../../aspose.threed.animation/animationchannel/addkeyframesequence)(KeyframeSequence) | Добавляет последовательность ключевых кадров в этот канал |
| [GetEnumerator](../../aspose.threed.animation/animationchannel/getenumerator)() | Получает перечислитель для прохождения всех последовательностей ключевых кадров внутри этого канала |

### Смотрите также

* class [KeyframeSequence](../keyframesequence)
* пространство имен [Aspose.ThreeD.Animation](../../aspose.threed.animation)
* сборка [Aspose.3D](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.3D.dll -->
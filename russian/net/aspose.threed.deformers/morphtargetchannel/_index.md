---
title: "Класс MorphTargetChannel"
second_title: "Справочник API Aspose.3D для .NET"
description: "Aspose.ThreeD.Deformers.MorphTargetChannel class. MorphTargetChannel используется MorphTargetDeformer для организации целевых геометрий. Некоторые форматы файлов, такие как FBX, поддерживают несколько каналов одновременно."
type: docs
weight: 220
url: /ru/net/aspose.threed.deformers/morphtargetchannel/
---
## MorphTargetChannel class

MorphTargetChannel используется [`MorphTargetDeformer`](../morphtargetdeformer/) для организации целевых геометрий. Некоторые форматы файлов, такие как FBX, поддерживают несколько каналов одновременно.

```csharp
public class MorphTargetChannel : A3DObject
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [MorphTargetChannel](morphtargetchannel/#constructor)() | Инициализирует новый экземпляр класса `MorphTargetChannel`. |
| [MorphTargetChannel](morphtargetchannel/#constructor_1)(string) | Инициализирует новый экземпляр класса `MorphTargetChannel`. |

## Свойства

| Имя | Описание |
| --- | --- |
| [ChannelWeight](../../aspose.threed.deformers/morphtargetchannel/channelweight/) { get; set; } | Получает или задает вес деформера этого канала. Вес находится в диапазоне от 0.0 до 1.0 |
| [Item](../../aspose.threed.deformers/morphtargetchannel/item/) { get; set; } |  |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | Получает или задает имя. |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | Получает коллекцию всех свойств. |
| [Targets](../../aspose.threed.deformers/morphtargetchannel/targets/) { get; } | Получает все цели, связанные с каналом. |
| [Weights](../../aspose.threed.deformers/morphtargetchannel/weights/) { get; } | Получает полные значения весов целевых геометрий. |

## Методы

| Имя | Описание |
| --- | --- |
| [FindProperty](../../aspose.threed/a3dobject/findproperty/)(string) | Находит свойство. Это может быть динамическое свойство (Созданное с помощью CreateDynamicProperty/SetProperty) или нативное свойство(Определяемое по его имени) |
| [GetProperty](../../aspose.threed/a3dobject/getproperty/)(string) | Получить значение указанного свойства |
| [GetWeight](../../aspose.threed.deformers/morphtargetchannel/getweight/)(Shape) | Получает вес для указанной цели; если цель не принадлежит этому каналу, возвращается значение по умолчанию 0. |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(Property) | Удаляет динамическое свойство. |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(string) | Удалить указанное свойство, определяемое по имени |
| [SetProperty](../../aspose.threed/a3dobject/setproperty/)(string, object) | Устанавливает значение указанного свойства |
| [SetWeight](../../aspose.threed.deformers/morphtargetchannel/setweight/)(Shape, double) | Устанавливает вес для указанной цели, значение по умолчанию — 1, диапазон должен быть от 0 до 1. |

## Поля

| Имя | Описание |
| --- | --- |
| const [DefaultWeight](../../aspose.threed.deformers/morphtargetchannel/defaultweight/) | Вес по умолчанию для морф-таргета. |

## Примечания

Вес находится в диапазоне от 0 до 1.0, а вес по умолчанию для таргета равен 0.0;

### См. также

* class [A3DObject](../../aspose.threed/a3dobject/)
* namespace [Aspose.ThreeD.Deformers](../../aspose.threed.deformers/)
* assembly [Aspose.3D](../../)



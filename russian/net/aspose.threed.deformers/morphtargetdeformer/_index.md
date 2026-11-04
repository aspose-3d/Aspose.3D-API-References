---
title: "Класс MorphTargetDeformer"
second_title: "Справочник API Aspose.3D для .NET"
description: "Класс Aspose.ThreeD.Deformers.MorphTargetDeformer. MorphTargetDeformer обеспечивает покоординатную анимацию. MorphTargetDeformer организует все таргеты через MorphTargetChannel, каждый канал может содержать несколько таргетов. Распространённое применение деформера морф-таргетов — применение выражений лица к персонажу. Подробнее можно узнать по адресу https//en.wikipedia.org/wiki/Morph_target_animation"
type: docs
weight: 230
url: /ru/net/aspose.threed.deformers/morphtargetdeformer/
---
## MorphTargetDeformer class

MorphTargetDeformer обеспечивает покоординатную анимацию. MorphTargetDeformer организует все таргеты через [`MorphTargetChannel`](../morphtargetchannel/), каждый канал может содержать несколько таргетов. Распространённое применение деформера морф-таргетов — применение выражений лица к персонажу. Подробнее можно узнать по адресу https://en.wikipedia.org/wiki/Morph_target_animation

```csharp
public class MorphTargetDeformer : Deformer
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [MorphTargetDeformer](morphtargetdeformer/#constructor)() | Инициализирует новый экземпляр класса `MorphTargetDeformer`. |
| [MorphTargetDeformer](morphtargetdeformer/#constructor_1)(string) | Инициализирует новый экземпляр класса `MorphTargetDeformer`. |

## Свойства

| Имя | Описание |
| --- | --- |
| [Channels](../../aspose.threed.deformers/morphtargetdeformer/channels/) { get; } | Получает все каналы, содержащиеся в этом деформере |
| [Item](../../aspose.threed.deformers/morphtargetdeformer/item/) { get; set; } |  |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | Получает или задает имя. |
| [Owner](../../aspose.threed.deformers/deformer/owner/) { get; } | Получает геометрию, которой принадлежит этот деформер |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | Получает коллекцию всех свойств. |

## Методы

| Имя | Описание |
| --- | --- |
| [FindProperty](../../aspose.threed/a3dobject/findproperty/)(string) | Находит свойство. Это может быть динамическое свойство (Созданное с помощью CreateDynamicProperty/SetProperty) или нативное свойство(Определяемое по его имени) |
| [GetProperty](../../aspose.threed/a3dobject/getproperty/)(string) | Получить значение указанного свойства |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(Property) | Удаляет динамическое свойство. |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(string) | Удалить указанное свойство, определяемое по имени |
| [SetProperty](../../aspose.threed/a3dobject/setproperty/)(string, object) | Устанавливает значение указанного свойства |

### См. также

* class [Deformer](../deformer/)
* namespace [Aspose.ThreeD.Deformers](../../aspose.threed.deformers/)
* assembly [Aspose.3D](../../)



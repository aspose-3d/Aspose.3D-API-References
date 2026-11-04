---
title: "Класс SkinDeformer"
second_title: "Справочник API Aspose.3D для .NET"
description: "Класс Aspose.ThreeD.Deformers.SkinDeformer. Деформер кожи содержит несколько костей; каждая кость смешивает часть геометрии с помощью весов контрольных точек."
type: docs
weight: 240
url: /ru/net/aspose.threed.deformers/skindeformer/
---
## SkinDeformer class

Skin деформер содержит несколько костей для работы, каждая кость смешивает часть геометрии по весам контрольных точек.

```csharp
public class SkinDeformer : Deformer
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [SkinDeformer](skindeformer/#constructor)() | Инициализирует новый экземпляр класса `SkinDeformer`. |
| [SkinDeformer](skindeformer/#constructor_1)(string) | Инициализирует новый экземпляр класса `SkinDeformer`. |

## Свойства

| Имя | Описание |
| --- | --- |
| [Bones](../../aspose.threed.deformers/skindeformer/bones/) { get; } | Получает все кости, содержащиеся в деформере кожи |
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



---
title: "Класс Deformer"
second_title: "Справочник API Aspose.3D для .NET"
description: "Класс Aspose.ThreeD.Deformers.Deformer. Базовый класс для SkinDeformer и MorphTargetDeformer"
type: docs
weight: 210
url: /ru/net/aspose.threed.deformers/deformer/
---
## Deformer class

Базовый класс для [`SkinDeformer`](../skindeformer/) и [`MorphTargetDeformer`](../morphtargetdeformer/)

```csharp
public abstract class Deformer : A3DObject
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [Deformer](deformer/)(string) | Инициализирует новый экземпляр класса `Deformer`. |

## Свойства

| Имя | Описание |
| --- | --- |
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

* class [A3DObject](../../aspose.threed/a3dobject/)
* namespace [Aspose.ThreeD.Deformers](../../aspose.threed.deformers/)
* assembly [Aspose.3D](../../)



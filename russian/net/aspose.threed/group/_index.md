---
title: "Класс Group"
second_title: "Справочник API Aspose.3D для .NET"
description: "Aspose.ThreeD.Group class. Группа представляет логические взаимосвязи узла Node"
type: docs
weight: 1570
url: /ru/net/aspose.threed/group/
---
## Group class

`Group` представляет логические взаимосвязи [`Node`](../node/).

```csharp
public class Group : A3DObject
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [Group](group/)(string) | Создать новый экземпляр `Group` |

## Свойства

| Имя | Описание |
| --- | --- |
| [Groups](../../aspose.threed/group/groups/) { get; } | Подгруппы |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | Получает или задает имя. |
| [Nodes](../../aspose.threed/group/nodes/) { get; } | Узлы в этой группе |
| [Parent](../../aspose.threed/group/parent/) { get; } | Родительская группа текущей группы |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | Получает коллекцию всех свойств. |

## Методы

| Имя | Описание |
| --- | --- |
| [FindProperty](../../aspose.threed/a3dobject/findproperty/)(string) | Находит свойство. Это может быть динамическое свойство (Созданное с помощью CreateDynamicProperty/SetProperty) или нативное свойство(Определяемое по его имени) |
| [GetProperty](../../aspose.threed/a3dobject/getproperty/)(string) | Получить значение указанного свойства |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(Property) | Удаляет динамическое свойство. |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(string) | Удалить указанное свойство, определяемое по имени |
| [SetProperty](../../aspose.threed/a3dobject/setproperty/)(string, object) | Устанавливает значение указанного свойства |
| override [ToString](../../aspose.threed/group/tostring/)() | Получает строковое представление `Group` |

### См. также

* class [A3DObject](../a3dobject/)
* namespace [Aspose.ThreeD](../../aspose.threed/)
* assembly [Aspose.3D](../../)



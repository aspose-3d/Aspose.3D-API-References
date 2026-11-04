---
title: "Класс Pose"
second_title: "Справочник API Aspose.3D для .NET"
description: "Класс Aspose.ThreeD.Pose. Поза используется для хранения матрицы преобразования, когда геометрия скинится. Поза представляет собой набор BonePose, каждый BonePose сохраняет конкретную информацию о преобразовании узла кости."
type: docs
weight: 1650
url: /ru/net/aspose.threed/pose/
---
## Pose class

Поза используется для хранения матрицы преобразования, когда геометрия скинится. Поза представляет собой набор [`BonePose`](../bonepose/), каждый [`BonePose`](../bonepose/) сохраняет конкретную информацию о преобразовании узла кости.

```csharp
public class Pose : A3DObject
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [Pose](pose/#constructor)() | Инициализирует новый экземпляр класса `Pose`. |
| [Pose](pose/#constructor_1)(string) | Инициализирует новый экземпляр класса `Pose`. |

## Свойства

| Имя | Описание |
| --- | --- |
| [BonePoses](../../aspose.threed/pose/boneposes/) { get; } | Получает все [`BonePose`](../bonepose/). |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | Получает или задает имя. |
| [PoseType](../../aspose.threed/pose/posetype/) { get; set; } | Получает или задает тип позы. |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | Получает коллекцию всех свойств. |

## Методы

| Имя | Описание |
| --- | --- |
| [AddBonePose](../../aspose.threed/pose/addbonepose/#addbonepose)(Node, Matrix4) | Сохраняет матрицу преобразования позы для указанного узла кости. Предполагается глобальная матрица преобразования. |
| [AddBonePose](../../aspose.threed/pose/addbonepose/#addbonepose_1)(Node, Matrix4, bool) | Сохраняет матрицу преобразования позы для указанного узла кости. |
| [FindProperty](../../aspose.threed/a3dobject/findproperty/)(string) | Находит свойство. Это может быть динамическое свойство (Созданное с помощью CreateDynamicProperty/SetProperty) или нативное свойство(Определяемое по его имени) |
| [GetProperty](../../aspose.threed/a3dobject/getproperty/)(string) | Получить значение указанного свойства |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(Property) | Удаляет динамическое свойство. |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(string) | Удалить указанное свойство, определяемое по имени |
| [SetProperty](../../aspose.threed/a3dobject/setproperty/)(string, object) | Устанавливает значение указанного свойства |

### См. также

* class [A3DObject](../a3dobject/)
* namespace [Aspose.ThreeD](../../aspose.threed/)
* assembly [Aspose.3D](../../)



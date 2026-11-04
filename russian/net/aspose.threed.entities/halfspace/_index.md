---
title: "Класс HalfSpace"
second_title: "Справочник API Aspose.3D для .NET"
description: "Класс Aspose.ThreeD.Entities.HalfSpace. HalfSpace представляет бесконечное пространство, разделённое плоскостью; это можно использовать с BooleanOperator"
type: docs
weight: 420
url: /ru/net/aspose.threed.entities/halfspace/
---
## HalfSpace class

`HalfSpace` представляет бесконечное пространство, разделённое плоскостью, это можно использовать с [`BooleanOperator`](../booleanoperator/)

```csharp
public class HalfSpace : Entity
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [HalfSpace](halfspace/#constructor)() | Создаёт новый экземпляр `HalfSpace` |
| [HalfSpace](halfspace/#constructor_1)(Vector3, Vector3) | Создаёт новый экземпляр `HalfSpace` с заданным вектором нормали и позицией на плоскости резака; |

## Свойства

| Имя | Описание |
| --- | --- |
| [Excluded](../../aspose.threed/entity/excluded/) { get; set; } | Получает или задает, следует ли исключать эту сущность при экспорте. |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | Получает или задает имя. |
| [Normal](../../aspose.threed.entities/halfspace/normal/) { get; set; } | Нормаль разделяющей плоскости, плоскость определяется как N * P + D = 0, где N — нормаль, а P — любая точка на плоскости. |
| [ParentNode](../../aspose.threed/entity/parentnode/) { get; set; } | Получает или задает первый родительский узел; если установлен первый родительский узел, эта сущность будет отсоединена от остальных родительских узлов. |
| [ParentNodes](../../aspose.threed/entity/parentnodes/) { get; } | Получает все родительские узлы, сущность может быть присоединена к нескольким родительским узлам для инстанцирования геометрии |
| [Position](../../aspose.threed.entities/halfspace/position/) { get; set; } | Любая точка на разделяющей плоскости, плоскость определяется как N * P + D = 0, где N — нормаль, а P — любая точка на плоскости. |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | Получает коллекцию всех свойств. |
| [Scene](../../aspose.threed/sceneobject/scene/) { get; } | Получает сцену, к которой принадлежит этот объект |

## Методы

| Имя | Описание |
| --- | --- |
| [FindProperty](../../aspose.threed/a3dobject/findproperty/)(string) | Находит свойство. Это может быть динамическое свойство (Созданное с помощью CreateDynamicProperty/SetProperty) или нативное свойство(Определяемое по его имени) |
| [GetBoundingBox](../../aspose.threed/entity/getboundingbox/)() | Получает ограничивающий параллелепипед текущей сущности в её системе координат объектного пространства. |
| virtual [GetEntityRendererKey](../../aspose.threed/entity/getentityrendererkey/)() | Получает ключ рендерера сущности, зарегистрированного в рендерере |
| [GetProperty](../../aspose.threed/a3dobject/getproperty/)(string) | Получить значение указанного свойства |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(Property) | Удаляет динамическое свойство. |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(string) | Удалить указанное свойство, определяемое по имени |
| [SetProperty](../../aspose.threed/a3dobject/setproperty/)(string, object) | Устанавливает значение указанного свойства |

### См. также

* class [Entity](../../aspose.threed/entity/)
* namespace [Aspose.ThreeD.Entities](../../aspose.threed.entities/)
* assembly [Aspose.3D](../../)



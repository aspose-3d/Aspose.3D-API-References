---
title: "Класс BooleanOperator"
second_title: "Справочник API Aspose.3D для .NET"
description: "Класс Aspose.ThreeD.Entities.BooleanOperator. Оператор Boolean позволяет выполнять булеву операцию над двумя экземплярами IMeshConvertible."
type: docs
weight: 280
url: /ru/net/aspose.threed.entities/booleanoperator/
---
## BooleanOperator class

Оператор Boolean позволяет выполнять булеву операцию над двумя экземплярами [`IMeshConvertible`](../imeshconvertible/).

```csharp
public class BooleanOperator : Entity, IMeshConvertible
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [BooleanOperator](booleanoperator/#constructor)() | Конструктор `BooleanOperator` |
| [BooleanOperator](booleanoperator/#constructor_1)(BooleanOperation, A3DObject, A3DObject) | Создаёт новый экземпляр `BooleanOperator` с двумя операндами |

## Свойства

| Имя | Описание |
| --- | --- |
| [Excluded](../../aspose.threed/entity/excluded/) { get; set; } | Получает или задает, следует ли исключать эту сущность при экспорте. |
| [First](../../aspose.threed.entities/booleanoperator/first/) { get; set; } | Первый операнд булевого оператора |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | Получает или задает имя. |
| [Operator](../../aspose.threed.entities/booleanoperator/operator/) { get; set; } | Булевый оператор, используемый в операции для создания результирующей сетки. |
| [ParentNode](../../aspose.threed/entity/parentnode/) { get; set; } | Получает или задает первый родительский узел; если установлен первый родительский узел, эта сущность будет отсоединена от остальных родительских узлов. |
| [ParentNodes](../../aspose.threed/entity/parentnodes/) { get; } | Получает все родительские узлы, сущность может быть присоединена к нескольким родительским узлам для инстанцирования геометрии |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | Получает коллекцию всех свойств. |
| [Scene](../../aspose.threed/sceneobject/scene/) { get; } | Получает сцену, к которой принадлежит этот объект |
| [Second](../../aspose.threed.entities/booleanoperator/second/) { get; set; } | Второй операнд булевого оператора |

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
| [ToMesh](../../aspose.threed.entities/booleanoperator/tomesh/)() | Выполнить булеву операцию над двумя операндами |

### См. также

* class [Entity](../../aspose.threed/entity/)
* interface [IMeshConvertible](../imeshconvertible/)
* namespace [Aspose.ThreeD.Entities](../../aspose.threed.entities/)
* assembly [Aspose.3D](../../)



---
title: Line
second_title: Справочник по Aspose.3D для .NET API
description: Ломаная линия  это путь определяемый набором точек сControlPoints./geometry/controlpointsи соединенныйSegments./line/segments что означает что это также может быть набор соединенных отрезков. Линия обычно представляет собой линейный объект что означает что ее нельзя использовать для представления кривой для представления кривой используетсяNurbsCurve./nurbscurve.
type: docs
weight: 420
url: /ru/net/aspose.threed.entities/line/
---
## Line class

Ломаная линия — это путь, определяемый набором точек с[`ControlPoints`](../geometry/controlpoints)и соединенный[`Segments`](./segments), что означает, что это также может быть набор соединенных отрезков. Линия обычно представляет собой линейный объект, что означает, что ее нельзя использовать для представления кривой, для представления кривой используется[`NurbsCurve`](../nurbscurve).

```csharp
public class Line : Curve
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [Line](line#constructor)() | Инициализирует новый экземпляр класса[`Line`](../line). |
| [Line](line#constructor_1)(string) | Инициализирует новый экземпляр класса[`Line`](../line). |

## Характеристики

| Имя | Описание |
| --- | --- |
| [Color](../../aspose.threed.entities/curve/color) { get; set; } | Получает или задает цвет линии, значение по умолчанию — белый (1, 1, 1) |
| [ControlPoints](../../aspose.threed.entities/line/controlpoints) { get; } | Получает все контрольные точки |
| [Excluded](../../aspose.threed/entity/excluded) { get; set; } | Получает или задает, следует ли исключить этот объект при экспорте. |
| virtual [Name](../../aspose.threed/a3dobject/name) { get; set; } | Получает или задает имя. |
| [ParentNode](../../aspose.threed/entity/parentnode) { get; set; } | Получает или устанавливает первый родительский узел, если установлен первый родительский узел, этот объект будет отсоединен от других родительских узлов. |
| [ParentNodes](../../aspose.threed/entity/parentnodes) { get; } | Получает все родительские узлы, сущность может быть присоединена к нескольким родительским узлам для создания экземпляров геометрии |
| [Properties](../../aspose.threed/a3dobject/properties) { get; } | Получает коллекцию всех свойств. |
| [Scene](../../aspose.threed/sceneobject/scene) { get; } | Получает сцену, которой принадлежит этот объект |
| [Segments](../../aspose.threed.entities/line/segments) { get; } | Получает сегменты линии |
| [Visible](../../aspose.threed.entities/line/visible) { get; set; } | Получает или задает, если геометрия видна |

## Методы

| Имя | Описание |
| --- | --- |
| static [FromPoints](../../aspose.threed.entities/line/frompoints)(params Vector3[]) | Создайте экземпляр[`Line`](../line)из набора точек. |
| [FindProperty](../../aspose.threed/a3dobject/findproperty)(string) | Находит свойство. Это может быть динамическое свойство (созданное CreateDynamicProperty/SetProperty) или родное свойство (идентифицированное по имени) |
| [GetBoundingBox](../../aspose.threed/entity/getboundingbox)() | Получает ограничивающую рамку текущего объекта в его системе координат объектного пространства. |
| override [GetEntityRendererKey](../../aspose.threed.entities/curve/getentityrendererkey)() | Получает ключ рендерера сущности, зарегистрированного в рендерере |
| [GetProperty](../../aspose.threed/a3dobject/getproperty)(string) | Получить значение указанного свойства |
| [MakeDefaultIndices](../../aspose.threed.entities/line/makedefaultindices)() | Сгенерировать последовательность 0,1,2,3....[`ControlPoints`](../geometry/controlpoints).Length -1 на[`Segments`](./segments)чтобы контрольные точки можно было использовать как одну линию |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty)(Property) | Удаляет динамическое свойство. |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty)(string) | Удалить указанное свойство, идентифицированное по имени |
| [SetProperty](../../aspose.threed/a3dobject/setproperty)(string, object) | Устанавливает значение указанного свойства |

### Смотрите также

* class [Curve](../curve)
* пространство имен [Aspose.ThreeD.Entities](../../aspose.threed.entities)
* сборка [Aspose.3D](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.3D.dll -->

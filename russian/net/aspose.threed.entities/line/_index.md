---
title: "Класс Line"
second_title: "Справочник API Aspose.3D для .NET"
description: "Класс Aspose.ThreeD.Entities.Line. Полилиния — это путь, определяемый набором точек с ControlPoints и соединённый Segments, что означает, что она также может быть набором соединённых отрезков линии. Линия обычно является линейным объектом, что означает, что её нельзя использовать для представления кривой; для представления кривой используется NurbsCurve."
type: docs
weight: 480
url: /ru/net/aspose.threed.entities/line/
---
## Line class

Полилиния — это путь, определяемый набором точек с [`ControlPoints`](../geometry/controlpoints/), и соединённый [`Segments`](./segments/), что означает, что она также может быть набором соединённых отрезков линии. Линия обычно является линейным объектом, что означает, что её нельзя использовать для представления кривой; для представления кривой используется [`NurbsCurve`](../nurbscurve/).

```csharp
public class Line : Curve
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [Line](line/#constructor)() | Инициализирует новый экземпляр класса `Line`. |
| [Line](line/#constructor_1)(string) | Инициализирует новый экземпляр класса `Line`. |

## Свойства

| Имя | Описание |
| --- | --- |
| [Color](../../aspose.threed.entities/curve/color/) { get; set; } | Получает или задает цвет линии, значение по умолчанию — белый (1, 1, 1) |
| [ControlPoints](../../aspose.threed.entities/line/controlpoints/) { get; } | Получает все контрольные точки |
| [Excluded](../../aspose.threed/entity/excluded/) { get; set; } | Получает или задает, следует ли исключать эту сущность при экспорте. |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | Получает или задает имя. |
| [ParentNode](../../aspose.threed/entity/parentnode/) { get; set; } | Получает или задает первый родительский узел; если установлен первый родительский узел, эта сущность будет отсоединена от остальных родительских узлов. |
| [ParentNodes](../../aspose.threed/entity/parentnodes/) { get; } | Получает все родительские узлы, сущность может быть присоединена к нескольким родительским узлам для инстанцирования геометрии |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | Получает коллекцию всех свойств. |
| [Scene](../../aspose.threed/sceneobject/scene/) { get; } | Получает сцену, к которой принадлежит этот объект |
| [Segments](../../aspose.threed.entities/line/segments/) { get; } | Получает сегменты линии. |
| [Visible](../../aspose.threed.entities/line/visible/) { get; set; } | Получает или задает, видима ли геометрия |

## Методы

| Имя | Описание |
| --- | --- |
| static [FromPoints](../../aspose.threed.entities/line/frompoints/)(params Vector3[]) | Создайте экземпляр `Line` из набора точек. |
| [FindProperty](../../aspose.threed/a3dobject/findproperty/)(string) | Находит свойство. Это может быть динамическое свойство (Созданное с помощью CreateDynamicProperty/SetProperty) или нативное свойство(Определяемое по его имени) |
| [GetBoundingBox](../../aspose.threed/entity/getboundingbox/)() | Получает ограничивающий параллелепипед текущей сущности в её системе координат объектного пространства. |
| override [GetEntityRendererKey](../../aspose.threed.entities/curve/getentityrendererkey/)() | Получает ключ рендерера сущности, зарегистрированного в рендерере |
| [GetProperty](../../aspose.threed/a3dobject/getproperty/)(string) | Получить значение указанного свойства |
| [MakeDefaultIndices](../../aspose.threed.entities/line/makedefaultindices/)() | Сгенерируйте последовательность 0,1,2,3....[`ControlPoints`](../geometry/controlpoints/).Length-1 до [`Segments`](./segments/), чтобы ControlPoints можно было использовать как одну линию |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(Property) | Удаляет динамическое свойство. |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(string) | Удалить указанное свойство, определяемое по имени |
| [SetProperty](../../aspose.threed/a3dobject/setproperty/)(string, object) | Устанавливает значение указанного свойства |

### См. также

* class [Curve](../curve/)
* namespace [Aspose.ThreeD.Entities](../../aspose.threed.entities/)
* assembly [Aspose.3D](../../)



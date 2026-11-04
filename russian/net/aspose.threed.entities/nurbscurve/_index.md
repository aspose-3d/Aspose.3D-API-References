---
title: "Класс NurbsCurve"
second_title: "Справочник API Aspose.3D для .NET"
description: "Класс Aspose.ThreeD.Entities.NurbsCurve. Кривая NURBS — это кривая, представленная NURBS Nonuniform rational basis spline. Кривая NURBS определяется её порядком, набором взвешенных контрольных точек и вектором узлов. Компонент w в контрольной точке используется как вес контрольной точки, независимо от того, является ли она двумерной или трехмерной."
type: docs
weight: 520
url: /ru/net/aspose.threed.entities/nurbscurve/
---
## NurbsCurve class

[NURBS curve](https://en.wikipedia.org/wiki/Non-uniform_rational_B-spline) is a curve represented by NURBS(Non-uniform rational basis spline), A NURBS curve is defined by its [`Order`](./order/), a set of weighted [`ControlPoints`](../geometry/controlpoints/) and a [`KnotVectors`](./knotvectors/) The w component in control point is used as control point's weight, whatever it is a TwoDimensional or ThreeDimensional

```csharp
public class NurbsCurve : Curve
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [NurbsCurve](nurbscurve/#constructor)() | Инициализирует новый экземпляр класса `NurbsCurve`. |
| [NurbsCurve](nurbscurve/#constructor_1)(string) | Инициализирует новый экземпляр класса `NurbsCurve`. |

## Свойства

| Имя | Описание |
| --- | --- |
| [Color](../../aspose.threed.entities/curve/color/) { get; set; } | Получает или задает цвет линии, значение по умолчанию — белый (1, 1, 1) |
| [ControlPoints](../../aspose.threed.entities/nurbscurve/controlpoints/) { get; } | Получает все контрольные точки |
| [CurveType](../../aspose.threed.entities/nurbscurve/curvetype/) { get; set; } | Получает или задает тип кривой. |
| [Degree](../../aspose.threed.entities/nurbscurve/degree/) { get; set; } | Получает или задает степень NURBS‑кривой, степень определяется как Порядок - 1 |
| [Dimension](../../aspose.threed.entities/nurbscurve/dimension/) { get; set; } | Получает или задает размерность кривой. |
| [Excluded](../../aspose.threed/entity/excluded/) { get; set; } | Получает или задает, следует ли исключать эту сущность при экспорте. |
| [KnotVectors](../../aspose.threed.entities/nurbscurve/knotvectors/) { get; } | Получает вектор узлов; это последовательность параметрических значений, определяющая, где и как контрольные точки влияют на NURBS‑кривую. |
| [Multiplicity](../../aspose.threed.entities/nurbscurve/multiplicity/) { get; } | Получает мультипликативность. |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | Получает или задает имя. |
| [Order](../../aspose.threed.entities/nurbscurve/order/) { get; set; } | Получает или задает порядок NURBS‑кривой; он определяет количество соседних контрольных точек, влияющих на любую точку кривой. |
| [ParentNode](../../aspose.threed/entity/parentnode/) { get; set; } | Получает или задает первый родительский узел; если установлен первый родительский узел, эта сущность будет отсоединена от остальных родительских узлов. |
| [ParentNodes](../../aspose.threed/entity/parentnodes/) { get; } | Получает все родительские узлы, сущность может быть присоединена к нескольким родительским узлам для инстанцирования геометрии |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | Получает коллекцию всех свойств. |
| [Rational](../../aspose.threed.entities/nurbscurve/rational/) { get; set; } | Получает или задает, является ли она рациональной; это значение указывает, является ли данный `NurbsCurve` рациональным сплайном или нерациональным сплайном. Нерациональный B‑сплайн является особым случаем рациональных B‑сплайнов. |
| [Scene](../../aspose.threed/sceneobject/scene/) { get; } | Получает сцену, к которой принадлежит этот объект |

## Методы

| Имя | Описание |
| --- | --- |
| [Evaluate](../../aspose.threed.entities/nurbscurve/evaluate/)(int) | Вычислить NURBS‑кривую |
| [EvaluateAt](../../aspose.threed.entities/nurbscurve/evaluateat/)(double) | Вычислить точку кривой в указанной позиции |
| [FindProperty](../../aspose.threed/a3dobject/findproperty/)(string) | Находит свойство. Это может быть динамическое свойство (Созданное с помощью CreateDynamicProperty/SetProperty) или нативное свойство(Определяемое по его имени) |
| [GetBoundingBox](../../aspose.threed/entity/getboundingbox/)() | Получает ограничивающий параллелепипед текущей сущности в её системе координат объектного пространства. |
| override [GetEntityRendererKey](../../aspose.threed.entities/curve/getentityrendererkey/)() | Получает ключ рендерера сущности, зарегистрированного в рендерере |
| [GetProperty](../../aspose.threed/a3dobject/getproperty/)(string) | Получить значение указанного свойства |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(Property) | Удаляет динамическое свойство. |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(string) | Удалить указанное свойство, определяемое по имени |
| [SetProperty](../../aspose.threed/a3dobject/setproperty/)(string, object) | Устанавливает значение указанного свойства |

### См. также

* class [Curve](../curve/)
* namespace [Aspose.ThreeD.Entities](../../aspose.threed.entities/)
* assembly [Aspose.3D](../../)



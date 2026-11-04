---
title: "Класс RectangleShape"
second_title: "Справочник API Aspose.3D для .NET"
description: "Класс Aspose.ThreeD.Profiles.RectangleShape. Прямоугольная форма, совместимая с IFC, со скругленными углами"
type: docs
weight: 1800
url: /ru/net/aspose.threed.profiles/rectangleshape/
---
## RectangleShape class

Прямоугольная форма, совместимая с IFC, со скруглёнными углами.

```csharp
public class RectangleShape : ParameterizedProfile
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [RectangleShape](rectangleshape/#constructor)() | Конструктор `RectangleShape` |
| [RectangleShape](rectangleshape/#constructor_1)(double, double) | Конструктор `RectangleShape` с указанными размерами по осям x и y. |

## Свойства

| Имя | Описание |
| --- | --- |
| [Excluded](../../aspose.threed/entity/excluded/) { get; set; } | Получает или задает, следует ли исключать эту сущность при экспорте. |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | Получает или задает имя. |
| [ParentNode](../../aspose.threed/entity/parentnode/) { get; set; } | Получает или задает первый родительский узел; если установлен первый родительский узел, эта сущность будет отсоединена от остальных родительских узлов. |
| [ParentNodes](../../aspose.threed/entity/parentnodes/) { get; } | Получает все родительские узлы, сущность может быть присоединена к нескольким родительским узлам для инстанцирования геометрии |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | Получает коллекцию всех свойств. |
| [RoundingRadius](../../aspose.threed.profiles/rectangleshape/roundingradius/) { get; set; } | Получает или задает радиус круглых дуг всех четырёх углов, измеряется в градусах. Значение по умолчанию — 0.0 |
| [Scene](../../aspose.threed/sceneobject/scene/) { get; } | Получает сцену, к которой принадлежит этот объект |
| [XDim](../../aspose.threed.profiles/rectangleshape/xdim/) { get; set; } | Получает или задает размер прямоугольника в направлении оси X. Значение по умолчанию — 2.0 |
| [YDim](../../aspose.threed.profiles/rectangleshape/ydim/) { get; set; } | Получает или задает размер прямоугольника в направлении оси Y. Значение по умолчанию — 2.0 |

## Методы

| Имя | Описание |
| --- | --- |
| [FindProperty](../../aspose.threed/a3dobject/findproperty/)(string) | Находит свойство. Это может быть динамическое свойство (Созданное с помощью CreateDynamicProperty/SetProperty) или нативное свойство(Определяемое по его имени) |
| [GetBoundingBox](../../aspose.threed/entity/getboundingbox/)() | Получает ограничивающий параллелепипед текущей сущности в её системе координат объектного пространства. |
| override [GetEntityRendererKey](../../aspose.threed.profiles/profile/getentityrendererkey/)() | Получает ключ рендерера сущности, зарегистрированного в рендерере |
| override [GetExtent](../../aspose.threed.profiles/rectangleshape/getextent/)() | Получает размеры в измерениях x и y. |
| [GetProperty](../../aspose.threed/a3dobject/getproperty/)(string) | Получить значение указанного свойства |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(Property) | Удаляет динамическое свойство. |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(string) | Удалить указанное свойство, определяемое по имени |
| [SetProperty](../../aspose.threed/a3dobject/setproperty/)(string, object) | Устанавливает значение указанного свойства |

### См. также

* class [ParameterizedProfile](../parameterizedprofile/)
* namespace [Aspose.ThreeD.Profiles](../../aspose.threed.profiles/)
* assembly [Aspose.3D](../../)



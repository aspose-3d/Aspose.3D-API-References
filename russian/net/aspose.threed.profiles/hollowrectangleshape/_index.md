---
title: "Класс HollowRectangleShape"
second_title: "Справочник API Aspose.3D для .NET"
description: "Класс Aspose.ThreeD.Profiles.HollowRectangleShape. Совместимая с IFC полая прямоугольная форма с закруглёнными внутренними и внешними углами"
type: docs
weight: 1750
url: /ru/net/aspose.threed.profiles/hollowrectangleshape/
---
## HollowRectangleShape class

Совместимый с IFC полый прямоугольный профиль с закруглёнными внутренними и внешними углами.

```csharp
public class HollowRectangleShape : RectangleShape
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [HollowRectangleShape](hollowrectangleshape/)() | Конструктор по умолчанию. |

## Свойства

| Имя | Описание |
| --- | --- |
| [Excluded](../../aspose.threed/entity/excluded/) { get; set; } | Получает или задает, следует ли исключать эту сущность при экспорте. |
| [InnerFilletRadius](../../aspose.threed.profiles/hollowrectangleshape/innerfilletradius/) { get; set; } | Внутренний радиус скругления внутреннего прямоугольника. |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | Получает или задает имя. |
| [ParentNode](../../aspose.threed/entity/parentnode/) { get; set; } | Получает или задает первый родительский узел; если установлен первый родительский узел, эта сущность будет отсоединена от остальных родительских узлов. |
| [ParentNodes](../../aspose.threed/entity/parentnodes/) { get; } | Получает все родительские узлы, сущность может быть присоединена к нескольким родительским узлам для инстанцирования геометрии |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | Получает коллекцию всех свойств. |
| [RoundingRadius](../../aspose.threed.profiles/rectangleshape/roundingradius/) { get; set; } | Получает или задает радиус круглых дуг всех четырёх углов, измеряется в градусах. Значение по умолчанию — 0.0 |
| [Scene](../../aspose.threed/sceneobject/scene/) { get; } | Получает сцену, к которой принадлежит этот объект |
| [WallThickness](../../aspose.threed.profiles/hollowrectangleshape/wallthickness/) { get; set; } | Толщина между границей прямоугольника и внутренним отверстием |
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

* class [RectangleShape](../rectangleshape/)
* namespace [Aspose.ThreeD.Profiles](../../aspose.threed.profiles/)
* assembly [Aspose.3D](../../)



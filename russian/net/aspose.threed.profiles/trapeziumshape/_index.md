---
title: "Класс TrapeziumShape"
second_title: "Справочник API Aspose.3D для .NET"
description: "Класс Aspose.ThreeD.Profiles.TrapeziumShape. Совместимая с IFC форма Trapezium, определяемая параметрами"
type: docs
weight: 1830
url: /ru/net/aspose.threed.profiles/trapeziumshape/
---
## TrapeziumShape class

Трапецеидальная форма, совместимая с IFC, определённая параметрами.

```csharp
public class TrapeziumShape : ParameterizedProfile
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [TrapeziumShape](trapeziumshape/)() | Конструктор `TrapeziumShape` |

## Свойства

| Имя | Описание |
| --- | --- |
| [BottomXDim](../../aspose.threed.profiles/trapeziumshape/bottomxdim/) { get; set; } | Получает или задает протяжённость нижней линии, измеренную вдоль оси x. |
| [Excluded](../../aspose.threed/entity/excluded/) { get; set; } | Получает или задает, следует ли исключать эту сущность при экспорте. |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | Получает или задает имя. |
| [ParentNode](../../aspose.threed/entity/parentnode/) { get; set; } | Получает или задает первый родительский узел; если установлен первый родительский узел, эта сущность будет отсоединена от остальных родительских узлов. |
| [ParentNodes](../../aspose.threed/entity/parentnodes/) { get; } | Получает все родительские узлы, сущность может быть присоединена к нескольким родительским узлам для инстанцирования геометрии |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | Получает коллекцию всех свойств. |
| [Scene](../../aspose.threed/sceneobject/scene/) { get; } | Получает сцену, к которой принадлежит этот объект |
| [TopXDim](../../aspose.threed.profiles/trapeziumshape/topxdim/) { get; set; } | Получает или задает протяжённость верхней линии, измеренную вдоль оси x. |
| [TopXOffset](../../aspose.threed.profiles/trapeziumshape/topxoffset/) { get; set; } | Получает или задает смещение от начала верхней линии до нижней линии. |
| [YDim](../../aspose.threed.profiles/trapeziumshape/ydim/) { get; set; } | Получает или задает расстояние между верхней и нижней линиями, измеренное вдоль оси y. |

## Методы

| Имя | Описание |
| --- | --- |
| [FindProperty](../../aspose.threed/a3dobject/findproperty/)(string) | Находит свойство. Это может быть динамическое свойство (Созданное с помощью CreateDynamicProperty/SetProperty) или нативное свойство(Определяемое по его имени) |
| [GetBoundingBox](../../aspose.threed/entity/getboundingbox/)() | Получает ограничивающий параллелепипед текущей сущности в её системе координат объектного пространства. |
| override [GetEntityRendererKey](../../aspose.threed.profiles/profile/getentityrendererkey/)() | Получает ключ рендерера сущности, зарегистрированного в рендерере |
| override [GetExtent](../../aspose.threed.profiles/trapeziumshape/getextent/)() | Получает размеры в измерениях x и y. |
| [GetProperty](../../aspose.threed/a3dobject/getproperty/)(string) | Получить значение указанного свойства |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(Property) | Удаляет динамическое свойство. |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(string) | Удалить указанное свойство, определяемое по имени |
| [SetProperty](../../aspose.threed/a3dobject/setproperty/)(string, object) | Устанавливает значение указанного свойства |

### См. также

* class [ParameterizedProfile](../parameterizedprofile/)
* namespace [Aspose.ThreeD.Profiles](../../aspose.threed.profiles/)
* assembly [Aspose.3D](../../)



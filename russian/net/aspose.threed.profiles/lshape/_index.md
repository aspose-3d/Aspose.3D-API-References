---
title: "Класс LShape"
second_title: "Справочник API Aspose.3D для .NET"
description: "Класс Aspose.ThreeD.Profiles.LShape. Совместимый с IFC профиль Lshape, определяемый параметрами"
type: docs
weight: 1760
url: /ru/net/aspose.threed.profiles/lshape/
---
## LShape class

Совместимый с IFC профиль L-образной формы, определяемый параметрами.

```csharp
public class LShape : ParameterizedProfile
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [LShape](lshape/)() | Конструктор `LShape` |

## Свойства

| Имя | Описание |
| --- | --- |
| [Depth](../../aspose.threed.profiles/lshape/depth/) { get; set; } | Получает или задает глубину профиля. |
| [EdgeRadius](../../aspose.threed.profiles/lshape/edgeradius/) { get; set; } | Получает или задает радиус кромки. |
| [Excluded](../../aspose.threed/entity/excluded/) { get; set; } | Получает или задает, следует ли исключать эту сущность при экспорте. |
| [FilletRadius](../../aspose.threed.profiles/lshape/filletradius/) { get; set; } | Получает или задает радиус скругления. |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | Получает или задает имя. |
| [ParentNode](../../aspose.threed/entity/parentnode/) { get; set; } | Получает или задает первый родительский узел; если установлен первый родительский узел, эта сущность будет отсоединена от остальных родительских узлов. |
| [ParentNodes](../../aspose.threed/entity/parentnodes/) { get; } | Получает все родительские узлы, сущность может быть присоединена к нескольким родительским узлам для инстанцирования геометрии |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | Получает коллекцию всех свойств. |
| [Scene](../../aspose.threed/sceneobject/scene/) { get; } | Получает сцену, к которой принадлежит этот объект |
| [Thickness](../../aspose.threed.profiles/lshape/thickness/) { get; set; } | Получает или задает толщину постоянной стенки. |
| [Width](../../aspose.threed.profiles/lshape/width/) { get; set; } | Получает или задает ширину профиля. |

## Методы

| Имя | Описание |
| --- | --- |
| [FindProperty](../../aspose.threed/a3dobject/findproperty/)(string) | Находит свойство. Это может быть динамическое свойство (Созданное с помощью CreateDynamicProperty/SetProperty) или нативное свойство(Определяемое по его имени) |
| [GetBoundingBox](../../aspose.threed/entity/getboundingbox/)() | Получает ограничивающий параллелепипед текущей сущности в её системе координат объектного пространства. |
| override [GetEntityRendererKey](../../aspose.threed.profiles/profile/getentityrendererkey/)() | Получает ключ рендерера сущности, зарегистрированного в рендерере |
| override [GetExtent](../../aspose.threed.profiles/lshape/getextent/)() | Получает размеры в измерениях x и y. |
| [GetProperty](../../aspose.threed/a3dobject/getproperty/)(string) | Получить значение указанного свойства |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(Property) | Удаляет динамическое свойство. |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(string) | Удалить указанное свойство, определяемое по имени |
| [SetProperty](../../aspose.threed/a3dobject/setproperty/)(string, object) | Устанавливает значение указанного свойства |

### См. также

* class [ParameterizedProfile](../parameterizedprofile/)
* namespace [Aspose.ThreeD.Profiles](../../aspose.threed.profiles/)
* assembly [Aspose.3D](../../)



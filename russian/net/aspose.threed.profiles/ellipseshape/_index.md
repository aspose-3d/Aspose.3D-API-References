---
title: EllipseShape
second_title: Справочник по Aspose.3D для .NET API
description: IFCсовместимая форма эллипса определяемая параметрами. Центральное положение профиля находится в центре ограничивающей рамки.
type: docs
weight: 1540
url: /ru/net/aspose.threed.profiles/ellipseshape/
---
## EllipseShape class

IFC-совместимая форма эллипса, определяемая параметрами. Центральное положение профиля находится в центре ограничивающей рамки.

```csharp
public class EllipseShape : ParameterizedProfile
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [EllipseShape](ellipseshape)() | Конструктор по умолчанию. |

## Характеристики

| Имя | Описание |
| --- | --- |
| [Excluded](../../aspose.threed/entity/excluded) { get; set; } | Получает или задает, следует ли исключить этот объект при экспорте. |
| virtual [Name](../../aspose.threed/a3dobject/name) { get; set; } | Получает или задает имя. |
| [ParentNode](../../aspose.threed/entity/parentnode) { get; set; } | Получает или задает первый родительский узел, если задан первый родительский узел, этот объект будет отсоединен от других родительских узлов. |
| [ParentNodes](../../aspose.threed/entity/parentnodes) { get; } | Получает все родительские узлы, сущность может быть присоединена к нескольким родительским узлам для экземпляра геометрии |
| [Properties](../../aspose.threed/a3dobject/properties) { get; } | Получает коллекцию всех свойств. |
| [Scene](../../aspose.threed/sceneobject/scene) { get; } | Получает сцену, которой принадлежит этот объект |
| [SemiAxis1](../../aspose.threed.profiles/ellipseshape/semiaxis1) { get; set; } | Получает или задает первый радиус эллипса, измеренный в направлении оси x. |
| [SemiAxis2](../../aspose.threed.profiles/ellipseshape/semiaxis2) { get; set; } | Получает или задает второй радиус эллипса, измеренный в направлении оси Y. |

## Методы

| Имя | Описание |
| --- | --- |
| [FindProperty](../../aspose.threed/a3dobject/findproperty)(string) | Находит свойство. Это может быть динамическое свойство (созданное CreateDynamicProperty/SetProperty) или родное свойство (идентифицированное по имени) |
| [GetBoundingBox](../../aspose.threed/entity/getboundingbox)() | Получает ограничивающую рамку текущего объекта в его системе координат объектного пространства. |
| override [GetEntityRendererKey](../../aspose.threed.profiles/profile/getentityrendererkey)() | Получает ключ средства визуализации объектов, зарегистрированного в средстве визуализации |
| override [GetExtent](../../aspose.threed.profiles/ellipseshape/getextent)() | Получает экстент в измерениях x и y. |
| [GetProperty](../../aspose.threed/a3dobject/getproperty)(string) | Получить значение указанного свойства |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty)(Property) | Удаляет динамическое свойство. |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty)(string) | Удалить указанное свойство с именем name |
| [SetProperty](../../aspose.threed/a3dobject/setproperty)(string, object) | Устанавливает значение указанного свойства |

### Смотрите также

* class [ParameterizedProfile](../parameterizedprofile)
* пространство имен [Aspose.ThreeD.Profiles](../../aspose.threed.profiles)
* сборка [Aspose.3D](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.3D.dll -->

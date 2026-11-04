---
title: "Класс EllipseShape"
second_title: "Справочник API Aspose.3D для .NET"
description: "Aspose.ThreeD.Profiles.EllipseShape класс. Совместимая с IFC эллиптическая форма, определяемая параметрами. Центр позиции профиля находится в центре ограничивающего прямоугольника"
type: docs
weight: 1710
url: /ru/net/aspose.threed.profiles/ellipseshape/
---
## EllipseShape class

Совместимый с IFC профиль эллиптической формы, определяемый параметрами. Центральное положение профиля находится в центре ограничивающего бокса.

```csharp
public class EllipseShape : ParameterizedProfile
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [EllipseShape](ellipseshape/)() | Конструктор по умолчанию. |

## Свойства

| Имя | Описание |
| --- | --- |
| [Excluded](../../aspose.threed/entity/excluded/) { get; set; } | Получает или задает, следует ли исключать эту сущность при экспорте. |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | Получает или задает имя. |
| [ParentNode](../../aspose.threed/entity/parentnode/) { get; set; } | Получает или задает первый родительский узел; если установлен первый родительский узел, эта сущность будет отсоединена от остальных родительских узлов. |
| [ParentNodes](../../aspose.threed/entity/parentnodes/) { get; } | Получает все родительские узлы, сущность может быть присоединена к нескольким родительским узлам для инстанцирования геометрии |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | Получает коллекцию всех свойств. |
| [Scene](../../aspose.threed/sceneobject/scene/) { get; } | Получает сцену, к которой принадлежит этот объект |
| [SemiAxis1](../../aspose.threed.profiles/ellipseshape/semiaxis1/) { get; set; } | Получает или задаёт первый радиус эллипса, измеряемый в направлении оси x. |
| [SemiAxis2](../../aspose.threed.profiles/ellipseshape/semiaxis2/) { get; set; } | Получает или задаёт второй радиус эллипса, измеряемый в направлении оси y. |

## Методы

| Имя | Описание |
| --- | --- |
| [FindProperty](../../aspose.threed/a3dobject/findproperty/)(string) | Находит свойство. Это может быть динамическое свойство (Созданное с помощью CreateDynamicProperty/SetProperty) или нативное свойство(Определяемое по его имени) |
| [GetBoundingBox](../../aspose.threed/entity/getboundingbox/)() | Получает ограничивающий параллелепипед текущей сущности в её системе координат объектного пространства. |
| override [GetEntityRendererKey](../../aspose.threed.profiles/profile/getentityrendererkey/)() | Получает ключ рендерера сущности, зарегистрированного в рендерере |
| override [GetExtent](../../aspose.threed.profiles/ellipseshape/getextent/)() | Получает размеры в измерениях x и y. |
| [GetProperty](../../aspose.threed/a3dobject/getproperty/)(string) | Получить значение указанного свойства |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(Property) | Удаляет динамическое свойство. |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(string) | Удалить указанное свойство, определяемое по имени |
| [SetProperty](../../aspose.threed/a3dobject/setproperty/)(string, object) | Устанавливает значение указанного свойства |

### См. также

* class [ParameterizedProfile](../parameterizedprofile/)
* namespace [Aspose.ThreeD.Profiles](../../aspose.threed.profiles/)
* assembly [Aspose.3D](../../)



---
title: "Класс HollowCircleShape"
second_title: "Справочник API Aspose.3D для .NET"
description: "Класс Aspose.ThreeD.Profiles.HollowCircleShape. Профиль полого круга, совместимый с IFC"
type: docs
weight: 1740
url: /ru/net/aspose.threed.profiles/hollowcircleshape/
---
## HollowCircleShape class

Совместимый с IFC полый круговой профиль.

```csharp
public class HollowCircleShape : CircleShape
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [HollowCircleShape](hollowcircleshape/)() | Конструктор по умолчанию. |

## Свойства

| Имя | Описание |
| --- | --- |
| [Excluded](../../aspose.threed/entity/excluded/) { get; set; } | Получает или задает, следует ли исключать эту сущность при экспорте. |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | Получает или задает имя. |
| [ParentNode](../../aspose.threed/entity/parentnode/) { get; set; } | Получает или задает первый родительский узел; если установлен первый родительский узел, эта сущность будет отсоединена от остальных родительских узлов. |
| [ParentNodes](../../aspose.threed/entity/parentnodes/) { get; } | Получает все родительские узлы, сущность может быть присоединена к нескольким родительским узлам для инстанцирования геометрии |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | Получает коллекцию всех свойств. |
| [Radius](../../aspose.threed.profiles/circleshape/radius/) { get; set; } | Получает или задает радиус круга. |
| [Scene](../../aspose.threed/sceneobject/scene/) { get; } | Получает сцену, к которой принадлежит этот объект |
| [WallThickness](../../aspose.threed.profiles/hollowcircleshape/wallthickness/) { get; set; } | Получает или задает разницу между внешним и внутренним радиусом. |

## Методы

| Имя | Описание |
| --- | --- |
| [FindProperty](../../aspose.threed/a3dobject/findproperty/)(string) | Находит свойство. Это может быть динамическое свойство (Созданное с помощью CreateDynamicProperty/SetProperty) или нативное свойство(Определяемое по его имени) |
| [GetBoundingBox](../../aspose.threed/entity/getboundingbox/)() | Получает ограничивающий параллелепипед текущей сущности в её системе координат объектного пространства. |
| override [GetEntityRendererKey](../../aspose.threed.profiles/profile/getentityrendererkey/)() | Получает ключ рендерера сущности, зарегистрированного в рендерере |
| override [GetExtent](../../aspose.threed.profiles/circleshape/getextent/)() | Получает размеры в измерениях x и y. |
| [GetProperty](../../aspose.threed/a3dobject/getproperty/)(string) | Получить значение указанного свойства |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(Property) | Удаляет динамическое свойство. |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(string) | Удалить указанное свойство, определяемое по имени |
| [SetProperty](../../aspose.threed/a3dobject/setproperty/)(string, object) | Устанавливает значение указанного свойства |

### См. также

* class [CircleShape](../circleshape/)
* namespace [Aspose.ThreeD.Profiles](../../aspose.threed.profiles/)
* assembly [Aspose.3D](../../)



---
title: "Класс Sphere"
second_title: "Справочник API Aspose.3D для .NET"
description: "Класс Aspose.ThreeD.Entities.Sphere. Параметрический шар"
type: docs
weight: 730
url: /ru/net/aspose.threed.entities/sphere/
---
## Sphere class

Параметризованная сфера.

```csharp
public class Sphere : Primitive
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [Sphere](sphere/#constructor)() | Создаёт новый экземпляр `Sphere` с радиусом по умолчанию 1. |
| [Sphere](sphere/#constructor_1)(double) | Создаёт новый экземпляр класса `Sphere` с указанным радиусом. |
| [Sphere](sphere/#constructor_2)(double, int, int) | Создаёт новый экземпляр класса `Sphere` с указанным радиусом, сегментами ширины и сегментами высоты. |
| [Sphere](sphere/#constructor_3)(string, double, int, int, double, double, double, double) | Создаёт новый экземпляр класса `Sphere`. |

## Свойства

| Имя | Описание |
| --- | --- |
| [CastShadows](../../aspose.threed.entities/primitive/castshadows/) { get; set; } | Получает или задает, может ли эта геометрия отбрасывать тень |
| [Excluded](../../aspose.threed/entity/excluded/) { get; set; } | Получает или задает, следует ли исключать эту сущность при экспорте. |
| [HeightSegments](../../aspose.threed.entities/sphere/heightsegments/) { get; set; } | Получает или задаёт сегменты высоты. |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | Получает или задает имя. |
| [ParentNode](../../aspose.threed/entity/parentnode/) { get; set; } | Получает или задает первый родительский узел; если установлен первый родительский узел, эта сущность будет отсоединена от остальных родительских узлов. |
| [ParentNodes](../../aspose.threed/entity/parentnodes/) { get; } | Получает все родительские узлы, сущность может быть присоединена к нескольким родительским узлам для инстанцирования геометрии |
| [PhiLength](../../aspose.threed.entities/sphere/philength/) { get; set; } | Получает или задаёт длину φ. |
| [PhiStart](../../aspose.threed.entities/sphere/phistart/) { get; set; } | Получает или задаёт начальное значение φ. |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | Получает коллекцию всех свойств. |
| [Radius](../../aspose.threed.entities/sphere/radius/) { get; set; } | Получает или задаёт радиус сферы. |
| [ReceiveShadows](../../aspose.threed.entities/primitive/receiveshadows/) { get; set; } | Получает или задает, может ли эта геометрия принимать тени. |
| [Scene](../../aspose.threed/sceneobject/scene/) { get; } | Получает сцену, к которой принадлежит этот объект |
| [ThetaLength](../../aspose.threed.entities/sphere/thetalength/) { get; set; } | Получает или задаёт длину θ. |
| [ThetaStart](../../aspose.threed.entities/sphere/thetastart/) { get; set; } | Получает или задаёт начальное значение θ. |
| [WidthSegments](../../aspose.threed.entities/sphere/widthsegments/) { get; set; } | Получает или задает сегменты ширины. |

## Методы

| Имя | Описание |
| --- | --- |
| [FindProperty](../../aspose.threed/a3dobject/findproperty/)(string) | Находит свойство. Это может быть динамическое свойство (Созданное с помощью CreateDynamicProperty/SetProperty) или нативное свойство(Определяемое по его имени) |
| [GetBoundingBox](../../aspose.threed/entity/getboundingbox/)() | Получает ограничивающий параллелепипед текущей сущности в её системе координат объектного пространства. |
| virtual [GetEntityRendererKey](../../aspose.threed/entity/getentityrendererkey/)() | Получает ключ рендерера сущности, зарегистрированного в рендерере |
| [GetProperty](../../aspose.threed/a3dobject/getproperty/)(string) | Получить значение указанного свойства |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(Property) | Удаляет динамическое свойство. |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(string) | Удалить указанное свойство, определяемое по имени |
| [SetProperty](../../aspose.threed/a3dobject/setproperty/)(string, object) | Устанавливает значение указанного свойства |
| override [ToMesh](../../aspose.threed.entities/sphere/tomesh/)() | Преобразовать текущий объект в сетку |

### См. также

* class [Primitive](../primitive/)
* namespace [Aspose.ThreeD.Entities](../../aspose.threed.entities/)
* assembly [Aspose.3D](../../)



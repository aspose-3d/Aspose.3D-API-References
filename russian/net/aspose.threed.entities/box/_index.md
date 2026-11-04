---
title: "Класс Box"
second_title: "Справочник API Aspose.3D для .NET"
description: "Aspose.ThreeD.Entities.Box класс. Box"
type: docs
weight: 290
url: /ru/net/aspose.threed.entities/box/
---
## Box class

Коробка.

```csharp
public class Box : Primitive
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [Box](box/#constructor)() | Инициализирует новый экземпляр класса `Box`. |
| [Box](box/#constructor_1)(double, double, double) | Инициализирует новый экземпляр класса `Box`. |
| [Box](box/#constructor_2)(string, double, double, double, int, int, int) | Инициализирует новый экземпляр класса `Box`. |

## Свойства

| Имя | Описание |
| --- | --- |
| [CastShadows](../../aspose.threed.entities/primitive/castshadows/) { get; set; } | Получает или задает, может ли эта геометрия отбрасывать тень |
| [Excluded](../../aspose.threed/entity/excluded/) { get; set; } | Получает или задает, следует ли исключать эту сущность при экспорте. |
| [Height](../../aspose.threed.entities/box/height/) { get; set; } | Получает или задает высоту коробки, выровненную по оси y. |
| [HeightSegments](../../aspose.threed.entities/box/heightsegments/) { get; set; } | Получает или задает сегменты высоты. |
| [Length](../../aspose.threed.entities/box/length/) { get; set; } | Получает или задает длину коробки, выровненную по оси z. |
| [LengthSegments](../../aspose.threed.entities/box/lengthsegments/) { get; set; } | Получает или задает сегменты длины. |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | Получает или задает имя. |
| [ParentNode](../../aspose.threed/entity/parentnode/) { get; set; } | Получает или задает первый родительский узел; если установлен первый родительский узел, эта сущность будет отсоединена от остальных родительских узлов. |
| [ParentNodes](../../aspose.threed/entity/parentnodes/) { get; } | Получает все родительские узлы, сущность может быть присоединена к нескольким родительским узлам для инстанцирования геометрии |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | Получает коллекцию всех свойств. |
| [ReceiveShadows](../../aspose.threed.entities/primitive/receiveshadows/) { get; set; } | Получает или задает, может ли эта геометрия принимать тени. |
| [Scene](../../aspose.threed/sceneobject/scene/) { get; } | Получает сцену, к которой принадлежит этот объект |
| [Width](../../aspose.threed.entities/box/width/) { get; set; } | Получает или задает ширину коробки, выровненную по оси x. |
| [WidthSegments](../../aspose.threed.entities/box/widthsegments/) { get; set; } | Получает или задает сегменты ширины |

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
| override [ToMesh](../../aspose.threed.entities/box/tomesh/)() | Преобразовать текущий объект в сетку |

### См. также

* class [Primitive](../primitive/)
* namespace [Aspose.ThreeD.Entities](../../aspose.threed.entities/)
* assembly [Aspose.3D](../../)



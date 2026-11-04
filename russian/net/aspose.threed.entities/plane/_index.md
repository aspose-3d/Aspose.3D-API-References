---
title: "Класс Plane"
second_title: "Справочник API Aspose.3D для .NET"
description: "Класс Aspose.ThreeD.Entities.Plane. Параметризованная плоскость"
type: docs
weight: 590
url: /ru/net/aspose.threed.entities/plane/
---
## Plane class

Параметрическая плоскость.

```csharp
public class Plane : Primitive
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [Plane](plane/#constructor)() | Инициализирует новый экземпляр `Plane` с размером по умолчанию 1×1. |
| [Plane](plane/#constructor_1)(double, double) | Инициализирует новый экземпляр `Plane`. |
| [Plane](plane/#constructor_2)(string, double, double, int, int) | Инициализирует новый экземпляр `Plane`. |

## Свойства

| Имя | Описание |
| --- | --- |
| [CastShadows](../../aspose.threed.entities/primitive/castshadows/) { get; set; } | Получает или задает, может ли эта геометрия отбрасывать тень |
| [Excluded](../../aspose.threed/entity/excluded/) { get; set; } | Получает или задает, следует ли исключать эту сущность при экспорте. |
| [Length](../../aspose.threed.entities/plane/length/) { get; set; } | Получает или задает длину плоскости. |
| [LengthSegments](../../aspose.threed.entities/plane/lengthsegments/) { get; set; } | Получает или задает сегменты длины. |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | Получает или задает имя. |
| [ParentNode](../../aspose.threed/entity/parentnode/) { get; set; } | Получает или задает первый родительский узел; если установлен первый родительский узел, эта сущность будет отсоединена от остальных родительских узлов. |
| [ParentNodes](../../aspose.threed/entity/parentnodes/) { get; } | Получает все родительские узлы, сущность может быть присоединена к нескольким родительским узлам для инстанцирования геометрии |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | Получает коллекцию всех свойств. |
| [ReceiveShadows](../../aspose.threed.entities/primitive/receiveshadows/) { get; set; } | Получает или задает, может ли эта геометрия принимать тени. |
| [Scene](../../aspose.threed/sceneobject/scene/) { get; } | Получает сцену, к которой принадлежит этот объект |
| [Up](../../aspose.threed.entities/plane/up/) { get; set; } | Получает или задает вектор «вверх» плоскости, значение по умолчанию (0, 1, 0); это влияет на генерацию плоскости. |
| [Width](../../aspose.threed.entities/plane/width/) { get; set; } | Получает или задает ширину плоскости. |
| [WidthSegments](../../aspose.threed.entities/plane/widthsegments/) { get; set; } | Получает или задает сегменты ширины. |

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
| override [ToMesh](../../aspose.threed.entities/plane/tomesh/)() | Преобразовать текущий объект в сетку |

### См. также

* class [Primitive](../primitive/)
* namespace [Aspose.ThreeD.Entities](../../aspose.threed.entities/)
* assembly [Aspose.3D](../../)



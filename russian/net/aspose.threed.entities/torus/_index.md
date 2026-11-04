---
title: "Класс Torus"
second_title: "Справочник API Aspose.3D для .NET"
description: "Класс Aspose.ThreeD.Entities.Torus. Параметризованный тор"
type: docs
weight: 770
url: /ru/net/aspose.threed.entities/torus/
---
## Torus class

Параметризованный тор.

```csharp
public class Torus : Primitive
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [Torus](torus/#constructor)() | Инициализирует новый экземпляр класса `Torus`. |
| [Torus](torus/#constructor_1)(double, double) | Инициализирует новый экземпляр класса `Torus`. |
| [Torus](torus/#constructor_2)(double, double, double) | Инициализирует новый экземпляр класса `Torus`. |
| [Torus](torus/#constructor_3)(string, double, double, int, int, double) | Инициализирует новый экземпляр класса `Torus`. |

## Свойства

| Имя | Описание |
| --- | --- |
| [Arc](../../aspose.threed.entities/torus/arc/) { get; set; } | Получает или задает дугу. |
| [CastShadows](../../aspose.threed.entities/primitive/castshadows/) { get; set; } | Получает или задает, может ли эта геометрия отбрасывать тень |
| [Excluded](../../aspose.threed/entity/excluded/) { get; set; } | Получает или задает, следует ли исключать эту сущность при экспорте. |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | Получает или задает имя. |
| [ParentNode](../../aspose.threed/entity/parentnode/) { get; set; } | Получает или задает первый родительский узел; если установлен первый родительский узел, эта сущность будет отсоединена от остальных родительских узлов. |
| [ParentNodes](../../aspose.threed/entity/parentnodes/) { get; } | Получает все родительские узлы, сущность может быть присоединена к нескольким родительским узлам для инстанцирования геометрии |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | Получает коллекцию всех свойств. |
| [RadialSegments](../../aspose.threed.entities/torus/radialsegments/) { get; set; } | Получает или задает радиальные сегменты. |
| [Radius](../../aspose.threed.entities/torus/radius/) { get; set; } | Получает или задает радиус тора. |
| [ReceiveShadows](../../aspose.threed.entities/primitive/receiveshadows/) { get; set; } | Получает или задает, может ли эта геометрия принимать тени. |
| [Scene](../../aspose.threed/sceneobject/scene/) { get; } | Получает сцену, к которой принадлежит этот объект |
| [Tube](../../aspose.threed.entities/torus/tube/) { get; set; } | Получает или задает радиус трубки. |
| [TubularSegments](../../aspose.threed.entities/torus/tubularsegments/) { get; set; } | Получает или задает сегменты трубки. |

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
| override [ToMesh](../../aspose.threed.entities/torus/tomesh/)() | Преобразовать текущий объект в сетку |

### См. также

* class [Primitive](../primitive/)
* namespace [Aspose.ThreeD.Entities](../../aspose.threed.entities/)
* assembly [Aspose.3D](../../)



---
title: "Класс RectangularTorus"
second_title: "Справочник API Aspose.3D для .NET"
description: "Класс Aspose.ThreeD.Entities.RectangularTorus. Параметрический прямоугольный тор"
type: docs
weight: 660
url: /ru/net/aspose.threed.entities/rectangulartorus/
---
## RectangularTorus class

Параметрический прямоугольный тор.

```csharp
public class RectangularTorus : Primitive
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [RectangularTorus](rectangulartorus/#constructor)() | Конструктор `RectangularTorus` |
| [RectangularTorus](rectangulartorus/#constructor_1)(string) | Конструктор `RectangularTorus` |

## Свойства

| Имя | Описание |
| --- | --- |
| [AngleStart](../../aspose.threed.entities/rectangulartorus/anglestart/) { get; set; } | Начальный угол дуги, измеряется в радианах. Значение по умолчанию — 0 |
| [Arc](../../aspose.threed.entities/rectangulartorus/arc/) { get; set; } | Полный угол дуги, измеряется в радианах. Значение по умолчанию — PI |
| [CastShadows](../../aspose.threed.entities/primitive/castshadows/) { get; set; } | Получает или задает, может ли эта геометрия отбрасывать тень |
| [Excluded](../../aspose.threed/entity/excluded/) { get; set; } | Получает или задает, следует ли исключать эту сущность при экспорте. |
| [Height](../../aspose.threed.entities/rectangulartorus/height/) { get; set; } | Высота прямоугольного тора. Значение по умолчанию — 20 |
| [InnerRadius](../../aspose.threed.entities/rectangulartorus/innerradius/) { get; set; } | Внутренний радиус прямоугольного тора. Значение по умолчанию — 17 |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | Получает или задает имя. |
| [OuterRadius](../../aspose.threed.entities/rectangulartorus/outerradius/) { get; set; } | Внешний радиус прямоугольного тора. Значение по умолчанию — 20 |
| [ParentNode](../../aspose.threed/entity/parentnode/) { get; set; } | Получает или задает первый родительский узел; если установлен первый родительский узел, эта сущность будет отсоединена от остальных родительских узлов. |
| [ParentNodes](../../aspose.threed/entity/parentnodes/) { get; } | Получает все родительские узлы, сущность может быть присоединена к нескольким родительским узлам для инстанцирования геометрии |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | Получает коллекцию всех свойств. |
| [RadialSegments](../../aspose.threed.entities/rectangulartorus/radialsegments/) { get; set; } | Радиальные сегменты, значение по умолчанию — 10 |
| [ReceiveShadows](../../aspose.threed.entities/primitive/receiveshadows/) { get; set; } | Получает или задает, может ли эта геометрия принимать тени. |
| [Scene](../../aspose.threed/sceneobject/scene/) { get; } | Получает сцену, к которой принадлежит этот объект |

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
| override [ToMesh](../../aspose.threed.entities/rectangulartorus/tomesh/)() | Преобразовать этот примитив в [`Mesh`](../mesh/) |

### См. также

* class [Primitive](../primitive/)
* namespace [Aspose.ThreeD.Entities](../../aspose.threed.entities/)
* assembly [Aspose.3D](../../)



---
title: Pyramid
second_title: Справочник по Aspose.3D для .NET API
description: Параметризованная пирамида.
type: docs
weight: 590
url: /ru/net/aspose.threed.entities/pyramid/
---
## Pyramid class

Параметризованная пирамида.

```csharp
public class Pyramid : Primitive
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [Pyramid](pyramid#constructor)() | Построить новый экземпляр пирамиды с площадью основания по умолчанию (10, 10) и высотой по умолчанию (5) |
| [Pyramid](pyramid#constructor_1)(double, double, double) | Построить новый экземпляр пирамиды с указанной нижней областью |
| [Pyramid](pyramid#constructor_2)(double, double, double, double, double) | Построить новый экземпляр пирамиды с указанной нижней и верхней площадями и высотой. |
| [Pyramid](pyramid#constructor_3)(string, double, double, double, double, double) | Построить новый экземпляр пирамиды с указанной нижней и верхней площадями и высотой. |

## Характеристики

| Имя | Описание |
| --- | --- |
| [BottomArea](../../aspose.threed.entities/pyramid/bottomarea) { get; set; } | Площадь нижней крышки |
| [BottomOffset](../../aspose.threed.entities/pyramid/bottomoffset) { get; set; } | Смещение нижних вершин |
| [CastShadows](../../aspose.threed.entities/primitive/castshadows) { get; set; } | Получает или устанавливает, может ли эта геометрия отбрасывать тень |
| [Excluded](../../aspose.threed/entity/excluded) { get; set; } | Получает или задает, следует ли исключить этот объект при экспорте. |
| [Height](../../aspose.threed.entities/pyramid/height) { get; set; } | Высота пирамиды |
| virtual [Name](../../aspose.threed/a3dobject/name) { get; set; } | Получает или задает имя. |
| [ParentNode](../../aspose.threed/entity/parentnode) { get; set; } | Получает или устанавливает первый родительский узел, если установлен первый родительский узел, этот объект будет отсоединен от других родительских узлов. |
| [ParentNodes](../../aspose.threed/entity/parentnodes) { get; } | Получает все родительские узлы, сущность может быть присоединена к нескольким родительским узлам для создания экземпляров геометрии |
| [Properties](../../aspose.threed/a3dobject/properties) { get; } | Получает коллекцию всех свойств. |
| [ReceiveShadows](../../aspose.threed.entities/primitive/receiveshadows) { get; set; } | Получает или задает, может ли эта геометрия получать тень. |
| [Scene](../../aspose.threed/sceneobject/scene) { get; } | Получает сцену, которой принадлежит этот объект |
| [TopArea](../../aspose.threed.entities/pyramid/toparea) { get; set; } | Площадь верхней крышки |

## Методы

| Имя | Описание |
| --- | --- |
| [FindProperty](../../aspose.threed/a3dobject/findproperty)(string) | Находит свойство. Это может быть динамическое свойство (созданное CreateDynamicProperty/SetProperty) или родное свойство (идентифицированное по имени) |
| [GetBoundingBox](../../aspose.threed/entity/getboundingbox)() | Получает ограничивающую рамку текущего объекта в его системе координат объектного пространства. |
| virtual [GetEntityRendererKey](../../aspose.threed/entity/getentityrendererkey)() | Получает ключ рендерера сущности, зарегистрированного в рендерере |
| [GetProperty](../../aspose.threed/a3dobject/getproperty)(string) | Получить значение указанного свойства |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty)(Property) | Удаляет динамическое свойство. |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty)(string) | Удалить указанное свойство, идентифицированное по имени |
| [SetProperty](../../aspose.threed/a3dobject/setproperty)(string, object) | Устанавливает значение указанного свойства |
| override [ToMesh](../../aspose.threed.entities/pyramid/tomesh)() | Конвертировать текущий объект в меш |

### Смотрите также

* class [Primitive](../primitive)
* пространство имен [Aspose.ThreeD.Entities](../../aspose.threed.entities)
* сборка [Aspose.3D](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.3D.dll -->
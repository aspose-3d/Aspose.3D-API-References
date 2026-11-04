---
title: "Класс TrimmedCurve"
second_title: "Справочник API Aspose.3D для .NET"
description: "Класс Aspose.ThreeD.Entities.TrimmedCurve. Ограниченная кривая, обрезающая базовую кривую с обеих сторон."
type: docs
weight: 810
url: /ru/net/aspose.threed.entities/trimmedcurve/
---
## TrimmedCurve class

Ограниченная кривая, обрезающая базовую кривую с обеих сторон.

```csharp
public class TrimmedCurve : Curve
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [TrimmedCurve](trimmedcurve/)() | Конструктор `TrimmedCurve` |

## Свойства

| Имя | Описание |
| --- | --- |
| [BasisCurve](../../aspose.threed.entities/trimmedcurve/basiscurve/) { get; set; } | Базовая кривая, подлежащая обрезке. |
| [Color](../../aspose.threed.entities/curve/color/) { get; set; } | Получает или задает цвет линии, значение по умолчанию — белый (1, 1, 1) |
| [Excluded](../../aspose.threed/entity/excluded/) { get; set; } | Получает или задает, следует ли исключать эту сущность при экспорте. |
| [First](../../aspose.threed.entities/trimmedcurve/first/) { get; set; } | Первая конечная точка для обрезки, может быть декартовой точкой или действительным параметром. |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | Получает или задает имя. |
| [ParentNode](../../aspose.threed/entity/parentnode/) { get; set; } | Получает или задает первый родительский узел; если установлен первый родительский узел, эта сущность будет отсоединена от остальных родительских узлов. |
| [ParentNodes](../../aspose.threed/entity/parentnodes/) { get; } | Получает все родительские узлы, сущность может быть присоединена к нескольким родительским узлам для инстанцирования геометрии |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | Получает коллекцию всех свойств. |
| [SameDirection](../../aspose.threed.entities/trimmedcurve/samedirection/) { get; set; } | Получает или задает, использует ли результат обрезки то же направление, что и базовая кривая. |
| [Scene](../../aspose.threed/sceneobject/scene/) { get; } | Получает сцену, к которой принадлежит этот объект |
| [Second](../../aspose.threed.entities/trimmedcurve/second/) { get; set; } | Вторая конечная точка для обрезки, может быть декартовой точкой или действительным параметром. |

## Методы

| Имя | Описание |
| --- | --- |
| [FindProperty](../../aspose.threed/a3dobject/findproperty/)(string) | Находит свойство. Это может быть динамическое свойство (Созданное с помощью CreateDynamicProperty/SetProperty) или нативное свойство(Определяемое по его имени) |
| [GetBoundingBox](../../aspose.threed/entity/getboundingbox/)() | Получает ограничивающий параллелепипед текущей сущности в её системе координат объектного пространства. |
| override [GetEntityRendererKey](../../aspose.threed.entities/curve/getentityrendererkey/)() | Получает ключ рендерера сущности, зарегистрированного в рендерере |
| [GetProperty](../../aspose.threed/a3dobject/getproperty/)(string) | Получить значение указанного свойства |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(Property) | Удаляет динамическое свойство. |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(string) | Удалить указанное свойство, определяемое по имени |
| [SetProperty](../../aspose.threed/a3dobject/setproperty/)(string, object) | Устанавливает значение указанного свойства |

### См. также

* class [Curve](../curve/)
* namespace [Aspose.ThreeD.Entities](../../aspose.threed.entities/)
* assembly [Aspose.3D](../../)



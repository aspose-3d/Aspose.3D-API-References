---
title: "Класс TransformedCurve"
second_title: "Справочник API Aspose.3D для .NET"
description: "Класс Aspose.ThreeD.Entities.TransformedCurve. TransformedCurve задает расположение кривой с помощью матрицы преобразования. Это позволяет выполнять преобразование внутри TrimmedCurve или CompositeCurve."
type: docs
weight: 780
url: /ru/net/aspose.threed.entities/transformedcurve/
---
## TransformedCurve class

Объект `TransformedCurve` задает расположение кривой с помощью матрицы преобразования. Это позволяет выполнять преобразование внутри [`TrimmedCurve`](../trimmedcurve/) или [`CompositeCurve`](../compositecurve/).

```csharp
public class TransformedCurve : Curve
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [TransformedCurve](transformedcurve/#constructor)() | Конструктор `TransformedCurve` |
| [TransformedCurve](transformedcurve/#constructor_1)(Curve, Matrix4) | Конструктор `TransformedCurve` |

## Свойства

| Имя | Описание |
| --- | --- |
| [BasisCurve](../../aspose.threed.entities/transformedcurve/basiscurve/) { get; set; } | Базовая кривая. |
| [Color](../../aspose.threed.entities/curve/color/) { get; set; } | Получает или задает цвет линии, значение по умолчанию — белый (1, 1, 1) |
| [Excluded](../../aspose.threed/entity/excluded/) { get; set; } | Получает или задает, следует ли исключать эту сущность при экспорте. |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | Получает или задает имя. |
| [ParentNode](../../aspose.threed/entity/parentnode/) { get; set; } | Получает или задает первый родительский узел; если установлен первый родительский узел, эта сущность будет отсоединена от остальных родительских узлов. |
| [ParentNodes](../../aspose.threed/entity/parentnodes/) { get; } | Получает все родительские узлы, сущность может быть присоединена к нескольким родительским узлам для инстанцирования геометрии |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | Получает коллекцию всех свойств. |
| [Scene](../../aspose.threed/sceneobject/scene/) { get; } | Получает сцену, к которой принадлежит этот объект |
| [TransformMatrix](../../aspose.threed.entities/transformedcurve/transformmatrix/) { get; set; } | Трансформационная матрица. |

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



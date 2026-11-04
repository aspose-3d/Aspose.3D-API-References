---
title: "Класс Pyramid"
second_title: "Справочник API Aspose.3D для .NET"
description: "Класс Aspose.ThreeD.Entities.Pyramid. Параметризованная пирамида"
type: docs
weight: 650
url: /ru/net/aspose.threed.entities/pyramid/
---
## Pyramid class

Параметрическая пирамида.

```csharp
public class Pyramid : Primitive
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [Pyramid](pyramid/#constructor)() | Создать новый экземпляр пирамиды с областью основания по умолчанию (10, 10) и высотой по умолчанию (5) |
| [Pyramid](pyramid/#constructor_1)(double, double, double) | Создать новый экземпляр пирамиды с указанной областью основания |
| [Pyramid](pyramid/#constructor_2)(double, double, double, double, double) | Создать новый экземпляр пирамиды с указанной областью основания, верхней областью и высотой. |
| [Pyramid](pyramid/#constructor_3)(string, double, double, double, double, double) | Создать новый экземпляр пирамиды с указанной областью основания, верхней областью и высотой. |

## Свойства

| Имя | Описание |
| --- | --- |
| [BottomArea](../../aspose.threed.entities/pyramid/bottomarea/) { get; set; } | Площадь нижней крышки |
| [BottomOffset](../../aspose.threed.entities/pyramid/bottomoffset/) { get; set; } | Смещение для нижних вершин |
| [CastShadows](../../aspose.threed.entities/primitive/castshadows/) { get; set; } | Получает или задает, может ли эта геометрия отбрасывать тень |
| [Excluded](../../aspose.threed/entity/excluded/) { get; set; } | Получает или задает, следует ли исключать эту сущность при экспорте. |
| [Height](../../aspose.threed.entities/pyramid/height/) { get; set; } | Высота пирамиды |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | Получает или задает имя. |
| [ParentNode](../../aspose.threed/entity/parentnode/) { get; set; } | Получает или задает первый родительский узел; если установлен первый родительский узел, эта сущность будет отсоединена от остальных родительских узлов. |
| [ParentNodes](../../aspose.threed/entity/parentnodes/) { get; } | Получает все родительские узлы, сущность может быть присоединена к нескольким родительским узлам для инстанцирования геометрии |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | Получает коллекцию всех свойств. |
| [ReceiveShadows](../../aspose.threed.entities/primitive/receiveshadows/) { get; set; } | Получает или задает, может ли эта геометрия принимать тени. |
| [Scene](../../aspose.threed/sceneobject/scene/) { get; } | Получает сцену, к которой принадлежит этот объект |
| [TopArea](../../aspose.threed.entities/pyramid/toparea/) { get; set; } | Площадь верхней крышки |

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
| override [ToMesh](../../aspose.threed.entities/pyramid/tomesh/)() | Преобразовать текущий объект в сетку |

### См. также

* class [Primitive](../primitive/)
* namespace [Aspose.ThreeD.Entities](../../aspose.threed.entities/)
* assembly [Aspose.3D](../../)



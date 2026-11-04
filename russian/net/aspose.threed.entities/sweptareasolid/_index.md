---
title: "Класс SweptAreaSolid"
second_title: "Справочник API Aspose.3D для .NET"
description: "Класс Aspose.ThreeD.Entities.SweptAreaSolid. SweptAreaSolid создает геометрию, вытягивая профиль вдоль директрисы"
type: docs
weight: 750
url: /ru/net/aspose.threed.entities/sweptareasolid/
---
## SweptAreaSolid class

Объект `SweptAreaSolid` создает геометрию, вытягивая профиль вдоль директивы.

```csharp
public class SweptAreaSolid : Entity, IMeshConvertible
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [SweptAreaSolid](sweptareasolid/)() | Конструктор по умолчанию. |

## Свойства

| Имя | Описание |
| --- | --- |
| [Directrix](../../aspose.threed.entities/sweptareasolid/directrix/) { get; set; } | Директива, вдоль которой происходит вытягивание области. |
| [EndPoint](../../aspose.threed.entities/sweptareasolid/endpoint/) { get; set; } | Конечная точка директивы. |
| [Excluded](../../aspose.threed/entity/excluded/) { get; set; } | Получает или задает, следует ли исключать эту сущность при экспорте. |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | Получает или задает имя. |
| [ParentNode](../../aspose.threed/entity/parentnode/) { get; set; } | Получает или задает первый родительский узел; если установлен первый родительский узел, эта сущность будет отсоединена от остальных родительских узлов. |
| [ParentNodes](../../aspose.threed/entity/parentnodes/) { get; } | Получает все родительские узлы, сущность может быть присоединена к нескольким родительским узлам для инстанцирования геометрии |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | Получает коллекцию всех свойств. |
| [Scene](../../aspose.threed/sceneobject/scene/) { get; } | Получает сцену, к которой принадлежит этот объект |
| [Shape](../../aspose.threed.entities/sweptareasolid/shape/) { get; set; } | Базовый профиль для построения геометрии. |
| [StartPoint](../../aspose.threed.entities/sweptareasolid/startpoint/) { get; set; } | Начальная точка директивы. |

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
| [ToMesh](../../aspose.threed.entities/sweptareasolid/tomesh/)() | Преобразовать текущий объект в сетку |

## Примеры

Следующий код показывает, как моделировать твердый объект, вытягивая C-образную форму по окружности.

```csharp
var directrix = new Circle(20);
var shape = new CShape();

var swept = new SweptAreaSolid()
{
  Shape = shape,
  Directrix = directrix,
  StartPoint = EndPoint.FromDegree(0),
  EndPoint = EndPoint.FromDegree(130)
};

var scene = new Scene();
scene.RootNode.CreateChildNode(swept);
scene.Save("swept.obj");
```

### См. также

* class [Entity](../../aspose.threed/entity/)
* interface [IMeshConvertible](../imeshconvertible/)
* namespace [Aspose.ThreeD.Entities](../../aspose.threed.entities/)
* assembly [Aspose.3D](../../)



---
title: "Класс LinearExtrusion"
second_title: "Справочник API Aspose.3D для .NET"
description: "Aspose.ThreeD.Entities.LinearExtrusion класс. Линейная экструзия принимает 2D‑форму в качестве входных данных и расширяет её в третьем измерении"
type: docs
weight: 490
url: /ru/net/aspose.threed.entities/linearextrusion/
---
## LinearExtrusion class

Линейная экструзия принимает 2D-форму в качестве входных данных и расширяет её в третьем измерении.

```csharp
public class LinearExtrusion : Entity, IMeshConvertible
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [LinearExtrusion](linearextrusion/#constructor)() | Конструктор экземпляра `LinearExtrusion`. |
| [LinearExtrusion](linearextrusion/#constructor_1)(Profile, double) | Конструктор экземпляра `LinearExtrusion`. |

## Свойства

| Имя | Описание |
| --- | --- |
| [Center](../../aspose.threed.entities/linearextrusion/center/) { get; set; } | Если это значение false, диапазон Z линейной экструзии будет от 0 до высоты, иначе диапазон будет от -height/2 до height/2. |
| [Direction](../../aspose.threed.entities/linearextrusion/direction/) { get; set; } | Направление экструзии, значение по умолчанию — (0, 0, 1) |
| [Excluded](../../aspose.threed/entity/excluded/) { get; set; } | Получает или задает, следует ли исключать эту сущность при экспорте. |
| [Height](../../aspose.threed.entities/linearextrusion/height/) { get; set; } | Высота экструдированной геометрии, значение по умолчанию — 1.0 |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | Получает или задает имя. |
| [ParentNode](../../aspose.threed/entity/parentnode/) { get; set; } | Получает или задает первый родительский узел; если установлен первый родительский узел, эта сущность будет отсоединена от остальных родительских узлов. |
| [ParentNodes](../../aspose.threed/entity/parentnodes/) { get; } | Получает все родительские узлы, сущность может быть присоединена к нескольким родительским узлам для инстанцирования геометрии |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | Получает коллекцию всех свойств. |
| [Scene](../../aspose.threed/sceneobject/scene/) { get; } | Получает сцену, к которой принадлежит этот объект |
| [Shape](../../aspose.threed.entities/linearextrusion/shape/) { get; set; } | Базовая форма для экструзии. |
| [Slices](../../aspose.threed.entities/linearextrusion/slices/) { get; set; } | Срезы скрученной экструдированной геометрии, значение по умолчанию — 1. |
| [Twist](../../aspose.threed.entities/linearextrusion/twist/) { get; set; } | Количество градусов, на которое форма экструдируется. |
| [TwistOffset](../../aspose.threed.entities/linearextrusion/twistoffset/) { get; set; } | Смещение, используемое при скручивании, значение по умолчанию — (0, 0, 0). |

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
| [ToMesh](../../aspose.threed.entities/linearextrusion/tomesh/)() | Преобразовать экструзию в сетку. |

## Примеры

Следующий код показывает, как использовать LinearExtrusion для экструзии формы в твердую модель.

```csharp
using Aspose.ThreeD;
using Aspose.ThreeD.Entities;
using Aspose.ThreeD.Utilities;
using Aspose.ThreeD.Profiles;

//Создать новую 3D‑сцену
Scene scene = new Scene();

// Инициализировать базовый профиль для экструдирования
var profile = new RectangleShape()
{
	RoundingRadius = 0.3
};

// Создать левый узел
var left = scene.RootNode.CreateChildNode();
left.CreateChildNode(new Box(0.01, 3, 3));

// Создать правый узел
var right = scene.RootNode.CreateChildNode();
right.CreateChildNode(new Box(0.01, 3, 3));
right.Transform.Translation = new Vector3(5, 0, 0);

//Выполнить линейную экструзию левого узла, используя свойства center и slices
left.CreateChildNode(new LinearExtrusion(profile, 10) { Center = false, Slices = 3, Twist = 20.0 });

// Выполнить линейную экструзию левого узла, используя свойства center и slices
right.CreateChildNode(new LinearExtrusion(profile, 10) { Center = true, Slices = 3, Twist = 90.0 });

scene
```

### См. также

* class [Entity](../../aspose.threed/entity/)
* interface [IMeshConvertible](../imeshconvertible/)
* namespace [Aspose.ThreeD.Entities](../../aspose.threed.entities/)
* assembly [Aspose.3D](../../)



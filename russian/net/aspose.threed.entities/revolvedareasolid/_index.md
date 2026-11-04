---
title: "Класс RevolvedAreaSolid"
second_title: "Справочник API Aspose.3D для .NET"
description: "Класс Aspose.ThreeD.Entities.RevolvedAreaSolid. Этот класс представляет твердый объект путем вращения поперечного сечения, заданного профилем, вокруг оси"
type: docs
weight: 680
url: /ru/net/aspose.threed.entities/revolvedareasolid/
---
## RevolvedAreaSolid class

Этот класс представляет твёрдую модель путем вращения поперечного сечения, заданного профилем, вокруг оси.

```csharp
public class RevolvedAreaSolid : Entity, IMeshConvertible
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [RevolvedAreaSolid](revolvedareasolid/)() | Конструктор по умолчанию. |

## Свойства

| Имя | Описание |
| --- | --- |
| [AngleEnd](../../aspose.threed.entities/revolvedareasolid/angleend/) { get; set; } | Получает или задает конечный угол вращения, измеряемый в радианах, значение по умолчанию — π. |
| [AngleStart](../../aspose.threed.entities/revolvedareasolid/anglestart/) { get; set; } | Получает или задает начальный угол вращения, измеряемый в радианах, значение по умолчанию — 0. |
| [Axis](../../aspose.threed.entities/revolvedareasolid/axis/) { get; set; } | Получает или задает направление оси, значение по умолчанию — (0, 1, 0). |
| [Excluded](../../aspose.threed/entity/excluded/) { get; set; } | Получает или задает, следует ли исключать эту сущность при экспорте. |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | Получает или задает имя. |
| [Origin](../../aspose.threed.entities/revolvedareasolid/origin/) { get; set; } | Получает или задает точку начала вращения, значение по умолчанию — (0, 0, 0). |
| [ParentNode](../../aspose.threed/entity/parentnode/) { get; set; } | Получает или задает первый родительский узел; если установлен первый родительский узел, эта сущность будет отсоединена от остальных родительских узлов. |
| [ParentNodes](../../aspose.threed/entity/parentnodes/) { get; } | Получает все родительские узлы, сущность может быть присоединена к нескольким родительским узлам для инстанцирования геометрии |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | Получает коллекцию всех свойств. |
| [Scene](../../aspose.threed/sceneobject/scene/) { get; } | Получает сцену, к которой принадлежит этот объект |
| [Shape](../../aspose.threed.entities/revolvedareasolid/shape/) { get; set; } | Получает или задает базовый профиль, используемый для вращения. |

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
| [ToMesh](../../aspose.threed.entities/revolvedareasolid/tomesh/)() | Преобразовать `RevolvedAreaSolid` в сетку. |

## Примеры

Следующий код показывает, как использовать RevolvedAreaSolid для вращения формы в твердую модель.

```csharp
using Aspose.ThreeD;
using Aspose.ThreeD.Entities;
using Aspose.ThreeD.Utilities;
using Aspose.ThreeD.Profiles;

//Создать новую 3D‑сцену
Scene scene = new Scene();

// Инициализировать базовый профиль для вращения
var profile = new RectangleShape()
{
    RoundingRadius = 0.3
};
//создать экземпляр RevolvedAreaSolid 
var revolved = new RevolvedAreaSolid()
{
  Shape = profile,
  Origin = new Vector3(1, 0, 0),
  AngleStart = 0,
  AngleEnd = Math.PI
};
scene.RootNode.CreateChildNode(revolved);

scene.Save("revolved.obj");
```

```csharp
//Создать новую 3D‑сцену
Scene scene = new Scene();

// Инициализировать базовый профиль для экструдирования
var profile = new RectangleShape();
profile.setRoundingRadius(0.3);

var revolved = new RevolvedAreaSolid();
revolved.setShape(profile);
revolved.setOrigin(new Vector3(1, 0, 0));
revolved.setAngleStart(0);
revolved.setAngleEnd(Math.PI);
scene.getRootNode().createChildNode(revolved);

scene.save("revolved.obj");
```

### См. также

* class [Entity](../../aspose.threed/entity/)
* interface [IMeshConvertible](../imeshconvertible/)
* namespace [Aspose.ThreeD.Entities](../../aspose.threed.entities/)
* assembly [Aspose.3D](../../)



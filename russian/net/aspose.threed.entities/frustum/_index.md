---
title: "Класс Frustum"
second_title: "Справочник API Aspose.3D для .NET"
description: "Класс Aspose.ThreeD.Entities.Frustum. Базовый класс для Camera и Light"
type: docs
weight: 400
url: /ru/net/aspose.threed.entities/frustum/
---
## Frustum class

Базовый класс для [`Camera`](../camera/) и [`Light`](../light/)

```csharp
public abstract class Frustum : Entity, IOrientable
```

## Свойства

| Имя | Описание |
| --- | --- |
| [Aspect](../../aspose.threed.entities/frustum/aspect/) { get; set; } | Получает или задает соотношение сторон усечения |
| [Direction](../../aspose.threed.entities/frustum/direction/) { get; set; } | Получает или задает направление, в котором смотрит камера. Изменения этого свойства также влияют на [`LookAt`](./lookat/) и [`Target`](./target/). |
| [Excluded](../../aspose.threed/entity/excluded/) { get; set; } | Получает или задает, следует ли исключать эту сущность при экспорте. |
| [FarPlane](../../aspose.threed.entities/frustum/farplane/) { get; set; } | Получает или задает расстояние до дальней плоскости усечения. |
| [LookAt](../../aspose.threed.entities/frustum/lookat/) { get; set; } | Получает или задает интересующую позицию, на которую смотрит камера. |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | Получает или задает имя. |
| [NearPlane](../../aspose.threed.entities/frustum/nearplane/) { get; set; } | Получает или задает расстояние до ближней плоскости усечения. |
| [OrthoHeight](../../aspose.threed.entities/frustum/orthoheight/) { get; set; } | Получает или задает высоту, когда усечение в ортографической проекции. |
| [ParentNode](../../aspose.threed/entity/parentnode/) { get; set; } | Получает или задает первый родительский узел; если установлен первый родительский узел, эта сущность будет отсоединена от остальных родительских узлов. |
| [ParentNodes](../../aspose.threed/entity/parentnodes/) { get; } | Получает все родительские узлы, сущность может быть присоединена к нескольким родительским узлам для инстанцирования геометрии |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | Получает коллекцию всех свойств. |
| [RotationMode](../../aspose.threed.entities/frustum/rotationmode/) { get; set; } | Получает или задает режим ориентации усечения. Это свойство работает только когда [`Target`](./target/) равно null. Если значение FixedTarget, направление всегда вычисляется свойством [`LookAt`](./lookat/). В противном случае [`LookAt`](./lookat/) всегда вычисляется на основе [`Direction`](./direction/). |
| [Scene](../../aspose.threed/sceneobject/scene/) { get; } | Получает сцену, к которой принадлежит этот объект |
| [Target](../../aspose.threed.entities/frustum/target/) { get; set; } | Получает или задает цель, на которую смотрит камера. Если пользователь поддерживает это свойство, оно должно предшествовать свойству [`LookAt`](./lookat/). |
| [Up](../../aspose.threed.entities/frustum/up/) { get; set; } | Получает или задает направление вверх камеры |

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

### См. также

* class [Entity](../../aspose.threed/entity/)
* interface [IOrientable](../iorientable/)
* namespace [Aspose.ThreeD.Entities](../../aspose.threed.entities/)
* assembly [Aspose.3D](../../)



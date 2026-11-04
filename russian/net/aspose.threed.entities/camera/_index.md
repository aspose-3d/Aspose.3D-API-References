---
title: "Класс Camera"
second_title: "Справочник API Aspose.3D для .NET"
description: "Класс Aspose.ThreeD.Entities.Camera. Камера описывает точку зрения наблюдателя, смотрящего на сцену"
type: docs
weight: 300
url: /ru/net/aspose.threed.entities/camera/
---
## Camera class

Камера описывает точку взгляда наблюдателя, смотрящего на сцену.

```csharp
public class Camera : Frustum
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [Camera](camera/#constructor)() | Инициализирует новый экземпляр класса `Camera`. |
| [Camera](camera/#constructor_1)(ProjectionType) | Инициализирует новый экземпляр класса `Camera`. |
| [Camera](camera/#constructor_2)(string) | Инициализирует новый экземпляр класса `Camera`. |
| [Camera](camera/#constructor_3)(string, ProjectionType) | Инициализирует новый экземпляр класса `Camera`. |

## Свойства

| Имя | Описание |
| --- | --- |
| [ApertureMode](../../aspose.threed.entities/camera/aperturemode/) { get; set; } | Получает или задает режим диафрагмы камеры |
| [Aspect](../../aspose.threed.entities/frustum/aspect/) { get; set; } | Получает или задает соотношение сторон усечения |
| [AspectRatio](../../aspose.threed.entities/camera/aspectratio/) { get; set; } | Получает или задает соотношение сторон плоскости просмотра. |
| [Direction](../../aspose.threed.entities/frustum/direction/) { get; set; } | Получает или задает направление, в котором смотрит камера. Изменения этого свойства также влияют на [`LookAt`](../frustum/lookat/) и [`Target`](../frustum/target/). |
| [Excluded](../../aspose.threed/entity/excluded/) { get; set; } | Получает или задает, следует ли исключать эту сущность при экспорте. |
| [FarPlane](../../aspose.threed.entities/frustum/farplane/) { get; set; } | Получает или задает расстояние до дальней плоскости усечения. |
| [FieldOfView](../../aspose.threed.entities/camera/fieldofview/) { get; set; } | Получает или задает угол обзора камеры в градусах, это свойство используется только когда ApertureMode установлен в Horizontal или Vertical |
| [FieldOfViewX](../../aspose.threed.entities/camera/fieldofviewx/) { get; set; } | Получает или задает горизонтальный угол обзора камеры в градусах, это свойство используется только когда ApertureMode установлен в HorizAndVert |
| [FieldOfViewY](../../aspose.threed.entities/camera/fieldofviewy/) { get; set; } | Получает или задает вертикальный угол обзора камеры в градусах, это свойство используется только когда ApertureMode установлен в HorizAndVert |
| [Height](../../aspose.threed.entities/camera/height/) { get; set; } | Получает или задает высоту плоскости просмотра в дюймах |
| [LookAt](../../aspose.threed.entities/frustum/lookat/) { get; set; } | Получает или задает интересующую позицию, на которую смотрит камера. |
| [Magnification](../../aspose.threed.entities/camera/magnification/) { get; set; } | Получает или задает увеличение, используемое в ортографической камере |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | Получает или задает имя. |
| [NearPlane](../../aspose.threed.entities/frustum/nearplane/) { get; set; } | Получает или задает расстояние до ближней плоскости усечения. |
| [OrthoHeight](../../aspose.threed.entities/frustum/orthoheight/) { get; set; } | Получает или задает высоту, когда усечение в ортографической проекции. |
| [ParentNode](../../aspose.threed/entity/parentnode/) { get; set; } | Получает или задает первый родительский узел; если установлен первый родительский узел, эта сущность будет отсоединена от остальных родительских узлов. |
| [ParentNodes](../../aspose.threed/entity/parentnodes/) { get; } | Получает все родительские узлы, сущность может быть присоединена к нескольким родительским узлам для инстанцирования геометрии |
| [ProjectionType](../../aspose.threed.entities/camera/projectiontype/) { get; set; } | Получает или задает тип проекции камеры. По умолчанию используется перспективная проекция |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | Получает коллекцию всех свойств. |
| [RotationMode](../../aspose.threed.entities/frustum/rotationmode/) { get; set; } | Получает или задает режим ориентации усечения. Это свойство работает только когда [`Target`](../frustum/target/) равен null. Если значение FixedTarget, направление всегда вычисляется свойством [`LookAt`](../frustum/lookat/). В противном случае [`LookAt`](../frustum/lookat/) всегда вычисляется по [`Direction`](../frustum/direction/). |
| [Scene](../../aspose.threed/sceneobject/scene/) { get; } | Получает сцену, к которой принадлежит этот объект |
| [Target](../../aspose.threed.entities/frustum/target/) { get; set; } | Получает или задает цель, на которую смотрит камера. Если пользователь поддерживает это свойство, оно должно быть установлено до свойства [`LookAt`](../frustum/lookat/). |
| [Up](../../aspose.threed.entities/frustum/up/) { get; set; } | Получает или задает направление вверх камеры |
| [Width](../../aspose.threed.entities/camera/width/) { get; set; } | Получает или задает ширину плоскости просмотра в дюймах |

## Методы

| Имя | Описание |
| --- | --- |
| [FindProperty](../../aspose.threed/a3dobject/findproperty/)(string) | Находит свойство. Это может быть динамическое свойство (Созданное с помощью CreateDynamicProperty/SetProperty) или нативное свойство(Определяемое по его имени) |
| [GetBoundingBox](../../aspose.threed/entity/getboundingbox/)() | Получает ограничивающий параллелепипед текущей сущности в её системе координат объектного пространства. |
| virtual [GetEntityRendererKey](../../aspose.threed/entity/getentityrendererkey/)() | Получает ключ рендерера сущности, зарегистрированного в рендерере |
| [GetProperty](../../aspose.threed/a3dobject/getproperty/)(string) | Получить значение указанного свойства |
| [MoveForward](../../aspose.threed.entities/camera/moveforward/)(double) | Переместите камеру вперёд в направлении её взгляда или к цели. |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(Property) | Удаляет динамическое свойство. |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(string) | Удалить указанное свойство, определяемое по имени |
| [SetProperty](../../aspose.threed/a3dobject/setproperty/)(string, object) | Устанавливает значение указанного свойства |

### См. также

* class [Frustum](../frustum/)
* namespace [Aspose.ThreeD.Entities](../../aspose.threed.entities/)
* assembly [Aspose.3D](../../)



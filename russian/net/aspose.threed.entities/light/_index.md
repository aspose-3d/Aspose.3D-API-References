---
title: "Класс Light"
second_title: "Справочник API Aspose.3D для .NET"
description: "Класс Aspose.ThreeD.Entities.Light. Свет освещает сцену"
type: docs
weight: 460
url: /ru/net/aspose.threed.entities/light/
---
## Light class

Свет освещает сцену.

Формула для расчёта общей затухаемости света: `A = ConstantAttenuation + (Dist * LinearAttenuation) + ((Dist^2) * QuadraticAttenuation)`

```csharp
public class Light : Frustum
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [Light](light/#constructor)() | Инициализирует новый экземпляр класса `Light`. |
| [Light](light/#constructor_1)(string) | Инициализирует новый экземпляр класса `Light`. |
| [Light](light/#constructor_2)(string, LightType) | Инициализирует новый экземпляр класса `Light`. |

## Свойства

| Имя | Описание |
| --- | --- |
| [Aspect](../../aspose.threed.entities/frustum/aspect/) { get; set; } | Получает или задает соотношение сторон усечения |
| [CastLight](../../aspose.threed.entities/light/castlight/) { get; set; } | Получает или задает, может ли текущий экземпляр света освещать другие объекты. |
| [CastShadows](../../aspose.threed.entities/light/castshadows/) { get; set; } | Получает или задает, может ли свет отбрасывать тени на другие объекты. |
| [Color](../../aspose.threed.entities/light/color/) { get; set; } | Получает или задает цвет света |
| [ConstantAttenuation](../../aspose.threed.entities/light/constantattenuation/) { get; set; } | Получает или задает постоянное затухание для расчёта общего затухания света |
| [Direction](../../aspose.threed.entities/frustum/direction/) { get; set; } | Получает или задает направление, в котором смотрит камера. Изменения этого свойства также влияют на [`LookAt`](../frustum/lookat/) и [`Target`](../frustum/target/). |
| [Excluded](../../aspose.threed/entity/excluded/) { get; set; } | Получает или задает, следует ли исключать эту сущность при экспорте. |
| [Falloff](../../aspose.threed.entities/light/falloff/) { get; set; } | Получает или задает угол конуса затухания (в градусах). |
| [FarPlane](../../aspose.threed.entities/frustum/farplane/) { get; set; } | Получает или задает расстояние до дальней плоскости усечения. |
| [HotSpot](../../aspose.threed.entities/light/hotspot/) { get; set; } | Получает или задает угол конуса горячей зоны (в градусах). |
| [Intensity](../../aspose.threed.entities/light/intensity/) { get; set; } | Получает или задает интенсивность света, значение по умолчанию — 100 |
| [LightType](../../aspose.threed.entities/light/lighttype/) { get; set; } | Получает или задает тип света |
| [LinearAttenuation](../../aspose.threed.entities/light/linearattenuation/) { get; set; } | Получает или задает линейное затухание для расчёта общего затухания света |
| [LookAt](../../aspose.threed.entities/frustum/lookat/) { get; set; } | Получает или задает интересующую позицию, на которую смотрит камера. |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | Получает или задает имя. |
| [NearPlane](../../aspose.threed.entities/frustum/nearplane/) { get; set; } | Получает или задает расстояние до ближней плоскости усечения. |
| [OrthoHeight](../../aspose.threed.entities/frustum/orthoheight/) { get; set; } | Получает или задает высоту, когда усечение в ортографической проекции. |
| [ParentNode](../../aspose.threed/entity/parentnode/) { get; set; } | Получает или задает первый родительский узел; если установлен первый родительский узел, эта сущность будет отсоединена от остальных родительских узлов. |
| [ParentNodes](../../aspose.threed/entity/parentnodes/) { get; } | Получает все родительские узлы, сущность может быть присоединена к нескольким родительским узлам для инстанцирования геометрии |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | Получает коллекцию всех свойств. |
| [QuadraticAttenuation](../../aspose.threed.entities/light/quadraticattenuation/) { get; set; } | Получает или задает квадратичное затухание для расчёта общего затухания света |
| [RotationMode](../../aspose.threed.entities/frustum/rotationmode/) { get; set; } | Получает или задает режим ориентации усечения. Это свойство работает только когда [`Target`](../frustum/target/) равен null. Если значение FixedTarget, направление всегда вычисляется свойством [`LookAt`](../frustum/lookat/). В противном случае [`LookAt`](../frustum/lookat/) всегда вычисляется по [`Direction`](../frustum/direction/). |
| [Scene](../../aspose.threed/sceneobject/scene/) { get; } | Получает сцену, к которой принадлежит этот объект |
| [ShadowColor](../../aspose.threed.entities/light/shadowcolor/) { get; set; } | Получает или задает цвет тени. |
| [Target](../../aspose.threed.entities/frustum/target/) { get; set; } | Получает или задает цель, на которую смотрит камера. Если пользователь поддерживает это свойство, оно должно быть установлено до свойства [`LookAt`](../frustum/lookat/). |
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

* class [Frustum](../frustum/)
* namespace [Aspose.ThreeD.Entities](../../aspose.threed.entities/)
* assembly [Aspose.3D](../../)



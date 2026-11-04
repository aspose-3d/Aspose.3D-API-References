---
title: "Класс Transform"
second_title: "Справочник API Aspose.3D для .NET"
description: "Класс Aspose.ThreeD.Transform. Трансформация содержит информацию, позволяющую получать доступ к объектам перемещения/масштабирования/вращения или матрице трансформации с минимальными затратами. Это используется локальной трансформацией."
type: docs
weight: 2650
url: /ru/net/aspose.threed/transform/
---
## Transform class

Трансформ содержит информацию, позволяющую получить доступ к перемещению/масштабированию/вращению объекта или к матрице преобразования с минимальными затратами. Это используется локальным трансформом.

```csharp
public class Transform : A3DObject
```

## Свойства

| Имя | Описание |
| --- | --- |
| [EulerAngles](../../aspose.threed/transform/eulerangles/) { get; set; } | Получает или задает вращение, представленное углами Эйлера, измеряемое в градусах |
| [GeometricRotation](../../aspose.threed/transform/geometricrotation/) { get; set; } | Получает или задает геометрическое вращение Эйлера (измеряется в градусах). Геометрическая трансформация влияет только на присоединённые сущности и не затрагивает дочерние узлы. При экспорте геометрической трансформации в типы файлов, которые её не поддерживают, она будет объединена как локальная трансформация. |
| [GeometricScaling](../../aspose.threed/transform/geometricscaling/) { get; set; } | Получает или задает геометрическое масштабирование. Геометрическая трансформация влияет только на присоединённые сущности и не затрагивает дочерние узлы. При экспорте геометрической трансформации в типы файлов, которые её не поддерживают, она будет объединена как локальная трансформация. |
| [GeometricTranslation](../../aspose.threed/transform/geometrictranslation/) { get; set; } | Получает или задает геометрический перенос. Геометрическая трансформация влияет только на присоединённые сущности и не затрагивает дочерние узлы. При экспорте геометрической трансформации в типы файлов, которые её не поддерживают, она будет объединена как локальная трансформация. |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | Получает или задает имя. |
| [PostRotation](../../aspose.threed/transform/postrotation/) { get; set; } | Получает или задает пост‑вращение, представленное в градусах |
| [PreRotation](../../aspose.threed/transform/prerotation/) { get; set; } | Получает или задает пре‑вращение, представленное в градусах |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | Получает коллекцию всех свойств. |
| [Rotation](../../aspose.threed/transform/rotation/) { get; set; } | Получает или задает вращение, представленное кватернионом. |
| [RotationOffset](../../aspose.threed/transform/rotationoffset/) { get; set; } | Получает или задает смещение вращения |
| [RotationPivot](../../aspose.threed/transform/rotationpivot/) { get; set; } | Получает или задает точку вращения |
| [Scaling](../../aspose.threed/transform/scaling/) { get; set; } | Получает или задает масштабирование |
| [ScalingOffset](../../aspose.threed/transform/scalingoffset/) { get; set; } | Получает или задает смещение масштабирования |
| [ScalingPivot](../../aspose.threed/transform/scalingpivot/) { get; set; } | Получает или задает точку масштабирования |
| [TransformMatrix](../../aspose.threed/transform/transformmatrix/) { get; set; } | Получает или задает матрицу трансформации. |
| [Translation](../../aspose.threed/transform/translation/) { get; set; } | Получает или задает перенос |

## Методы

| Имя | Описание |
| --- | --- |
| [FindProperty](../../aspose.threed/a3dobject/findproperty/)(string) | Находит свойство. Это может быть динамическое свойство (Созданное с помощью CreateDynamicProperty/SetProperty) или нативное свойство(Определяемое по его имени) |
| [GetProperty](../../aspose.threed/a3dobject/getproperty/)(string) | Получить значение указанного свойства |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(Property) | Удаляет динамическое свойство. |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(string) | Удалить указанное свойство, определяемое по имени |
| [SetEulerAngles](../../aspose.threed/transform/seteulerangles/)(double, double, double) | Устанавливает углы Эйлера в градусах текущей трансформации. |
| [SetGeometricRotation](../../aspose.threed/transform/setgeometricrotation/)(double, double, double) | Устанавливает геометрическое вращение Эйлера (измеряется в градусах). Геометрическая трансформация влияет только на присоединённые сущности и не затрагивает дочерние узлы. При экспорте геометрической трансформации в типы файлов, которые её не поддерживают, она будет объединена как локальная трансформация. |
| [SetGeometricScaling](../../aspose.threed/transform/setgeometricscaling/)(double, double, double) | Устанавливает геометрическое масштабирование. Геометрическая трансформация влияет только на присоединённые сущности и не затрагивает дочерние узлы. При экспорте геометрической трансформации в типы файлов, которые её не поддерживают, она будет объединена как локальная трансформация. |
| [SetGeometricTranslation](../../aspose.threed/transform/setgeometrictranslation/)(double, double, double) | Устанавливает геометрический перенос. Геометрическая трансформация влияет только на присоединённые сущности и не затрагивает дочерние узлы. При экспорте геометрической трансформации в типы файлов, которые её не поддерживают, она будет объединена как локальная трансформация. |
| [SetPostRotation](../../aspose.threed/transform/setpostrotation/)(double, double, double) | Устанавливает пост‑вращение, представленное в градусах |
| [SetPreRotation](../../aspose.threed/transform/setprerotation/)(double, double, double) | Устанавливает пре‑вращение, представленное в градусах |
| [SetProperty](../../aspose.threed/a3dobject/setproperty/)(string, object) | Устанавливает значение указанного свойства |
| [SetRotation](../../aspose.threed/transform/setrotation/)(double, double, double, double) | Устанавливает вращение (как компоненты кватерниона) текущей трансформации. |
| [SetScale](../../aspose.threed/transform/setscale/)(double, double, double) | Устанавливает масштаб текущего преобразования. |
| [SetTranslation](../../aspose.threed/transform/settranslation/)(double, double, double) | Устанавливает перемещение текущего преобразования. |

## Примеры

Следующий код показывает, как изменить преобразование узла:

```csharp
Scene scene = new Scene();
var boxNode = scene.RootNode.CreateChildNode(new Box());
//разместите коробку в (10, 0, 0)
boxNode.Transform.Translation = new Vector3(10, 0, 0);
```

### См. также

* class [A3DObject](../a3dobject/)
* namespace [Aspose.ThreeD](../../aspose.threed/)
* assembly [Aspose.3D](../../)



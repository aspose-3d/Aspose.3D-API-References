---
title: "Transform.GeometricRotation"
second_title: "Справочник API Aspose.3D для .NET"
description: "Свойство Transform. Получает или задает геометрический Euler rotation, измеренный в градусах. Геометрическое преобразование влияет только на прикрепленные сущности и оставляет дочерние узлы без изменений. Оно будет объединено как локальное преобразование при экспорте геометрического преобразования в типы файлов, которые его не поддерживают."
type: docs
weight: 20
url: /ru/net/aspose.threed/transform/geometricrotation/
---
## Transform.GeometricRotation property

Получает или задает геометрическое вращение Эйлера (измеряется в градусах). Геометрическая трансформация влияет только на присоединённые сущности и не затрагивает дочерние узлы. При экспорте геометрической трансформации в типы файлов, которые её не поддерживают, она будет объединена как локальная трансформация.

```csharp
public Vector3 GeometricRotation { get; set; }
```

## Примеры

```csharp
Node node = new Node();
node.getTransform().setGeometricRotation(new Vector3(90, 0, 0));
```

### См. также

* struct [Vector3](../../../aspose.threed.utilities/vector3/)
* class [Transform](../)
* namespace [Aspose.ThreeD](../../transform/)
* assembly [Aspose.3D](../../../)



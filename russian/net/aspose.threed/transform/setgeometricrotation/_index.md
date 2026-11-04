---
title: "Transform.SetGeometricRotation"
second_title: "Справочник API Aspose.3D для .NET"
description: "Метод Transform. Устанавливает геометрическое вращение Эйлера, измеряемое в градусах. Геометрическое преобразование влияет только на прикреплённые сущности и не затрагивает дочерние узлы. При экспорте геометрического преобразования в типы файлов, которые его не поддерживают, оно будет объединено как локальное преобразование."
type: docs
weight: 160
url: /ru/net/aspose.threed/transform/setgeometricrotation/
---
## Transform.SetGeometricRotation method

Устанавливает геометрическое вращение Эйлера (измеряется в градусах). Геометрическая трансформация влияет только на присоединённые сущности и не затрагивает дочерние узлы. При экспорте геометрической трансформации в типы файлов, которые её не поддерживают, она будет объединена как локальная трансформация.

```csharp
public Transform SetGeometricRotation(double rx, double ry, double rz)
```

## Примеры

```csharp
Node node = new Node();
node.Transform.SetGeometricRotation(90, 0, 0);
```

### См. также

* class [Transform](../)
* namespace [Aspose.ThreeD](../../transform/)
* assembly [Aspose.3D](../../../)



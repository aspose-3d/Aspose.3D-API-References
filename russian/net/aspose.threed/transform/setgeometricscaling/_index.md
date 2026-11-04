---
title: "Transform.SetGeometricScaling"
second_title: "Справочник API Aspose.3D для .NET"
description: "Метод Transform. Устанавливает геометрическое масштабирование. Геометрическое преобразование влияет только на прикреплённые сущности и не затрагивает дочерние узлы. При экспорте геометрического преобразования в типы файлов, которые его не поддерживают, оно будет объединено как локальное преобразование."
type: docs
weight: 170
url: /ru/net/aspose.threed/transform/setgeometricscaling/
---
## Transform.SetGeometricScaling method

Устанавливает геометрическое масштабирование. Геометрическая трансформация влияет только на присоединённые сущности и не затрагивает дочерние узлы. При экспорте геометрической трансформации в типы файлов, которые её не поддерживают, она будет объединена как локальная трансформация.

```csharp
public Transform SetGeometricScaling(double sx, double sy, double sz)
```

## Примеры

```csharp
Node node = new Node();
node.Transform.SetGeometricScaling(2, 2, 2);
```

### См. также

* class [Transform](../)
* namespace [Aspose.ThreeD](../../transform/)
* assembly [Aspose.3D](../../../)



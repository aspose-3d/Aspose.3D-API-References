---
title: "Transform.GeometricScaling"
second_title: "Справочник API Aspose.3D для .NET"
description: "Свойство Transform. Получает или задает геометрическое scaling. Геометрическое преобразование влияет только на прикрепленные сущности и оставляет дочерние узлы без изменений. Оно будет объединено как локальное преобразование при экспорте геометрического преобразования в типы файлов, которые его не поддерживают."
type: docs
weight: 30
url: /ru/net/aspose.threed/transform/geometricscaling/
---
## Transform.GeometricScaling property

Получает или задает геометрическое масштабирование. Геометрическая трансформация влияет только на присоединённые сущности и не затрагивает дочерние узлы. При экспорте геометрической трансформации в типы файлов, которые её не поддерживают, она будет объединена как локальная трансформация.

```csharp
public Vector3 GeometricScaling { get; set; }
```

## Примеры

```csharp
Node node = new Node();
node.Transform.GeometricScaling = new Vector3(2, 2, 2);
```

### См. также

* struct [Vector3](../../../aspose.threed.utilities/vector3/)
* class [Transform](../)
* namespace [Aspose.ThreeD](../../transform/)
* assembly [Aspose.3D](../../../)



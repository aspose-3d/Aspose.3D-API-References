---
title: "Transform.SetGeometricTranslation"
second_title: "Справочник API Aspose.3D для .NET"
description: "Метод Transform. Устанавливает геометрический translation. Геометрическое преобразование влияет только на прикрепленные сущности и оставляет дочерние узлы без изменений. Оно будет объединено как локальное преобразование при экспорте геометрического преобразования в типы файлов, которые его не поддерживают."
type: docs
weight: 180
url: /ru/net/aspose.threed/transform/setgeometrictranslation/
---
## Transform.SetGeometricTranslation method

Устанавливает геометрический перенос. Геометрическая трансформация влияет только на присоединённые сущности и не затрагивает дочерние узлы. При экспорте геометрической трансформации в типы файлов, которые её не поддерживают, она будет объединена как локальная трансформация.

```csharp
public Transform SetGeometricTranslation(double x, double y, double z)
```

## Примеры

```csharp
Node node = new Node();
node.Transform.SetGeometricTranslation(10, 0, 0);
```

### См. также

* class [Transform](../)
* namespace [Aspose.ThreeD](../../transform/)
* assembly [Aspose.3D](../../../)



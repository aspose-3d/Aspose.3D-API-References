---
title: "Transform.GeometricTranslation"
second_title: "Справочник API Aspose.3D для .NET"
description: "Свойство Transform. Возвращает или задает геометрический перенос. Геометрическое преобразование влияет только на прикреплённые сущности и не затрагивает дочерние узлы. При экспорте геометрического преобразования в типы файлов, которые его не поддерживают, оно будет объединено как локальное преобразование."
type: docs
weight: 40
url: /ru/net/aspose.threed/transform/geometrictranslation/
---
## Transform.GeometricTranslation property

Получает или задает геометрический перенос. Геометрическая трансформация влияет только на присоединённые сущности и не затрагивает дочерние узлы. При экспорте геометрической трансформации в типы файлов, которые её не поддерживают, она будет объединена как локальная трансформация.

```csharp
public Vector3 GeometricTranslation { get; set; }
```

## Примеры

```csharp
Node node = new Node();
node.Transform.GeometricTranslation = new Vector3(10, 0, 0);
```

### См. также

* struct [Vector3](../../../aspose.threed.utilities/vector3/)
* class [Transform](../)
* namespace [Aspose.ThreeD](../../transform/)
* assembly [Aspose.3D](../../../)



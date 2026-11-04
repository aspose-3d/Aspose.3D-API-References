---
title: "Entity.GetBoundingBox"
second_title: "Справочник API Aspose.3D для .NET"
description: "Entity метод. Получает ограничивающий прямоугольник текущего объекта в системе координат его объектного пространства"
type: docs
weight: 50
url: /ru/net/aspose.threed/entity/getboundingbox/
---
## Entity.GetBoundingBox method

Получает ограничивающий параллелепипед текущей сущности в её системе координат объектного пространства.

```csharp
public BoundingBox GetBoundingBox()
```

### Возвращаемое значение

ограничивающий прямоугольник текущего объекта в системе координат его объектного пространства.

## Примеры

Следующий код показывает, как вычислить ограничивающий прямоугольник фигуры

```csharp
Entity entity = new Sphere() { Radius = 10 };
var bbox = entity.GetBoundingBox();
Console.WriteLine($"The bounding box of the entity is {bbox.Minimum} ~ {bbox.Maximum}");
```

### См. также

* struct [BoundingBox](../../../aspose.threed.utilities/boundingbox/)
* class [Entity](../)
* namespace [Aspose.ThreeD](../../entity/)
* assembly [Aspose.3D](../../../)



---
title: "BoundingBox.FromGeometry"
second_title: "Справочник API Aspose.3D для .NET"
description: "Метод BoundingBox. Создаёт ограничивающий прямоугольник из заданной геометрии"
type: docs
weight: 40
url: /ru/net/aspose.threed.utilities/boundingbox/fromgeometry/
---
## BoundingBox.FromGeometry method

Создайте ограничивающий параллелепипед из заданной геометрии

```csharp
public static BoundingBox FromGeometry(Geometry geometry)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| геометрия | Geometry | Геометрия для вычисления ограничивающего прямоугольника |

### Возвращаемое значение

Ограничивающий прямоугольник заданной геометрии

## Примеры

Следующий код показывает, как построить ограничивающий прямоугольник из экземпляра геометрии.

```csharp
var sphere = (new Sphere()).ToMesh();
var boundingBox = BoundingBox.FromGeometry(sphere);
Console.WriteLine("Bounding box = " + boundingBox);
```

### См. также

* class [Geometry](../../../aspose.threed.entities/geometry/)
* struct [BoundingBox](../)
* namespace [Aspose.ThreeD.Utilities](../../boundingbox/)
* assembly [Aspose.3D](../../../)



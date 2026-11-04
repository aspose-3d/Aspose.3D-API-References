---
title: "BoundingBox.OverlapsWith"
second_title: "Справочник API Aspose.3D для .NET"
description: "Метод BoundingBox. Проверяет, пересекается ли текущий ограничивающий прямоугольник с указанным ограничивающим прямоугольником"
type: docs
weight: 140
url: /ru/net/aspose.threed.utilities/boundingbox/overlapswith/
---
## BoundingBox.OverlapsWith method

Проверьте, пересекается ли текущий ограничивающий прямоугольник с указанным ограничивающим прямоугольником.

```csharp
public bool OverlapsWith(BoundingBox box)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| коробка | BoundingBox | Другой ограничивающий прямоугольник для проверки |

### Возвращаемое значение

True, если текущий ограничивающий прямоугольник пересекается с заданным.

## Примеры

Следующий код показывает, как проверить, пересекаются ли два ограничивающих прямоугольника друг с другом.

```csharp
var boundingBox = new BoundingBox(0, 0, 0, 10, 10, 10);
var bbox2 = new BoundingBox(1, 1, 1, 11, 11, 11);
Console.WriteLine("Bounding box overlaps = " + boundingBox.OverlapsWith(bbox2));
```

### См. также

* struct [BoundingBox](../)
* namespace [Aspose.ThreeD.Utilities](../../boundingbox/)
* assembly [Aspose.3D](../../../)



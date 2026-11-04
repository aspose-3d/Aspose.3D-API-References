---
title: "BoundingBox.Contains"
second_title: "Справочник API Aspose.3D для .NET"
description: "Метод BoundingBox. Проверяет, находится ли точка p внутри ограничивающего прямоугольника"
type: docs
weight: 100
url: /ru/net/aspose.threed.utilities/boundingbox/contains/
---
## Contains(Vector3) {#contains_1}

Проверьте, находится ли точка p внутри ограничивающего параллелепипеда

```csharp
public bool Contains(Vector3 p)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| p | Vector3 | Точка для проверки |

### Возвращаемое значение

True, если точка находится внутри ограничивающего прямоугольника

## Примеры

Следующий код показывает, как проверить, находится ли точка внутри ограничивающего прямоугольника.

```csharp
var boundingBox = new BoundingBox(0, 0, 0, 10, 10, 10);
var pt = new Vector3(4, 4, 4);
Console.WriteLine("Bounding box overlaps = " + boundingBox.Contains(pt));
```

### См. также

* struct [Vector3](../../vector3/)
* struct [BoundingBox](../)
* namespace [Aspose.ThreeD.Utilities](../../boundingbox/)
* assembly [Aspose.3D](../../../)

---

## Contains(BoundingBox) {#contains}

Ограничивающий параллелепипед для проверки, находится ли он внутри текущего ограничивающего параллелепипеда.

```csharp
public bool Contains(BoundingBox bbox)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| bbox | BoundingBox |  |

### См. также

* struct [BoundingBox](../)
* namespace [Aspose.ThreeD.Utilities](../../boundingbox/)
* assembly [Aspose.3D](../../../)



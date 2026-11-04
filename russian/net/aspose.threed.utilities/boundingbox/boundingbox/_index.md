---
title: "BoundingBox.BoundingBox"
second_title: "Справочник API Aspose.3D для .NET"
description: "Конструктор BoundingBox. Инициализирует конечный ограничивающий прямоугольник с заданными минимальными и максимальными углами"
type: docs
weight: 10
url: /ru/net/aspose.threed.utilities/boundingbox/boundingbox/
---
## BoundingBox(Vector3, Vector3) {#constructor}

Инициализировать конечный ограничивающий параллелепипед с заданными минимальным и максимальным углом

```csharp
public BoundingBox(Vector3 minimum, Vector3 maximum)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| minimum | Vector3 | Минимальный угол |
| maximum | Vector3 | Максимальный угол |

## Примеры

Следующий код показывает, как построить ограничивающий прямоугольник из минимального и максимального углов.

```csharp
var minimum = new Vector3(0, 0, 0);
var maximum = new Vector3(10, 10, 10);
var boundingBox = new BoundingBox(minimum, maximum);
Console.WriteLine("Bounding box = " + boundingBox);
```

### См. также

* struct [Vector3](../../vector3/)
* struct [BoundingBox](../)
* namespace [Aspose.ThreeD.Utilities](../../boundingbox/)
* assembly [Aspose.3D](../../../)

---

## BoundingBox(double, double, double, double, double, double) {#constructor_1}

Инициализировать конечный ограничивающий параллелепипед с заданными минимальным и максимальным углом

```csharp
public BoundingBox(double minX, double minY, double minZ, double maxX, double maxY, double maxZ)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| minX | Double | X минимального угла |
| minY | Double | Y минимального угла |
| minZ | Double | Z минимального угла |
| maxX | Double | X максимального угла |
| maxY | Double | Y максимального угла |
| maxZ | Double | Z максимального угла |

## Примеры

Следующий код показывает, как построить ограничивающий прямоугольник из минимального и максимального углов.

```csharp
var boundingBox = new BoundingBox(0, 0, 0, 10, 10, 10);
Console.WriteLine("Bounding box = " + boundingBox);
```

### См. также

* struct [BoundingBox](../)
* namespace [Aspose.ThreeD.Utilities](../../boundingbox/)
* assembly [Aspose.3D](../../../)



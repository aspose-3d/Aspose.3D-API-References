---
title: "BoundingBox.Merge"
second_title: "Справочник API Aspose.3D для .NET"
description: "Метод BoundingBox. Объединить текущий ограничивающий прямоугольник с заданной точкой"
type: docs
weight: 130
url: /ru/net/aspose.threed.utilities/boundingbox/merge/
---
## Merge(Vector4) {#merge_2}

Объедините текущий ограничивающий параллелепипед с заданной точкой

```csharp
public void Merge(Vector4 pt)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| pt | Vector4 | Точка, которую нужно объединить с ограничивающим прямоугольником |

## Примеры

Следующий код показывает, как объединить точку с ограничивающим прямоугольником.

```csharp
var boundingBox = BoundingBox.Null;
boundingBox.Merge(new Vector4(1, 10, -1));
Console.WriteLine("Bounding box = " + boundingBox);
```

### См. также

* struct [Vector4](../../vector4/)
* struct [BoundingBox](../)
* namespace [Aspose.ThreeD.Utilities](../../boundingbox/)
* assembly [Aspose.3D](../../../)

---

## Merge(Vector3) {#merge_1}

Объедините текущий ограничивающий параллелепипед с заданной точкой

```csharp
public void Merge(Vector3 pt)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| pt | Vector3 | Точка, которую нужно объединить с ограничивающим прямоугольником |

## Примеры

Следующий код показывает, как объединить точку с ограничивающим прямоугольником.

```csharp
var boundingBox = BoundingBox.Null;
boundingBox.Merge(new Vector3(1, 10, -1));
Console.WriteLine("Bounding box = " + boundingBox);
```

### См. также

* struct [Vector3](../../vector3/)
* struct [BoundingBox](../)
* namespace [Aspose.ThreeD.Utilities](../../boundingbox/)
* assembly [Aspose.3D](../../../)

---

## Merge(double, double, double) {#merge_3}

Объедините текущий ограничивающий параллелепипед с заданной точкой

```csharp
public void Merge(double x, double y, double z)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| x | Double | Точка, которую нужно объединить с ограничивающим прямоугольником |
| y | Double | Точка, которую нужно объединить с ограничивающим прямоугольником |
| z | Double | Точка, которую нужно объединить с ограничивающим прямоугольником |

## Примеры

Следующий код показывает, как объединить точку с ограничивающим прямоугольником.

```csharp
var boundingBox = BoundingBox.Null;
boundingBox.Merge(1, 10, -1);
Console.WriteLine("Bounding box = " + boundingBox);
```

### См. также

* struct [BoundingBox](../)
* namespace [Aspose.ThreeD.Utilities](../../boundingbox/)
* assembly [Aspose.3D](../../../)

---

## Merge(BoundingBox) {#merge}

Объединяет новый параллелепипед с текущим ограничивающим параллелепипедом.

```csharp
public void Merge(BoundingBox bb)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| bb | BoundingBox | Ограничивающий прямоугольник для объединения |

### См. также

* struct [BoundingBox](../)
* namespace [Aspose.ThreeD.Utilities](../../boundingbox/)
* assembly [Aspose.3D](../../../)



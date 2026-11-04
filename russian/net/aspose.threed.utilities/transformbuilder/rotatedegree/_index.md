---
title: "TransformBuilder.RotateDegree"
second_title: "Справочник API Aspose.3D для .NET"
description: "Метод TransformBuilder. Последовательное применение вращения в градусах"
type: docs
weight: 100
url: /ru/net/aspose.threed.utilities/transformbuilder/rotatedegree/
---
## RotateDegree(double, Vector3) {#rotatedegree}

Добавьте вращение в градусах

```csharp
public TransformBuilder RotateDegree(double angle, Vector3 axis)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| угол | Double | Угол поворота в градусах |
| ось | Vector3 | Ось вращения |

## Примеры

```csharp
TransformBuilder tb = new TransformBuilder();
tb.RotateDegree(90, Vector3.YAxis);
Console.WriteLine($"Transform Matrix: {tb.Matrix}");
```

### См. также

* struct [Vector3](../../vector3/)
* class [TransformBuilder](../)
* namespace [Aspose.ThreeD.Utilities](../../transformbuilder/)
* assembly [Aspose.3D](../../../)

---

## RotateDegree(Vector3, RotationOrder) {#rotatedegree_1}

Добавить вращение с указанным порядком

```csharp
public void RotateDegree(Vector3 rot, RotationOrder order)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| rot | Vector3 | Вращение в градусах |
| порядок | RotationOrder |  |

### См. также

* struct [Vector3](../../vector3/)
* enum [RotationOrder](../../rotationorder/)
* class [TransformBuilder](../)
* namespace [Aspose.ThreeD.Utilities](../../transformbuilder/)
* assembly [Aspose.3D](../../../)



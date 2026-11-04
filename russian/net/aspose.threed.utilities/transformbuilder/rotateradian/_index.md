---
title: "TransformBuilder.RotateRadian"
second_title: "Справочник API Aspose.3D для .NET"
description: "Метод TransformBuilder. Последовательное применение вращения в радианах"
type: docs
weight: 130
url: /ru/net/aspose.threed.utilities/transformbuilder/rotateradian/
---
## RotateRadian(double, Vector3) {#rotateradian}

Сцепить преобразование вращения в радианах

```csharp
public TransformBuilder RotateRadian(double angle, Vector3 axis)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| угол | Double | Угол вращения в радианах |
| ось | Vector3 | Ось вращения |

## Примеры

```csharp
TransformBuilder tb = new TransformBuilder();
tb.RotateRadian(Math.PI, Vector3.YAxis);
Console.WriteLine($"Transform Matrix: {tb.Matrix}");
```

### См. также

* struct [Vector3](../../vector3/)
* class [TransformBuilder](../)
* namespace [Aspose.ThreeD.Utilities](../../transformbuilder/)
* assembly [Aspose.3D](../../../)

---

## RotateRadian(Vector3, RotationOrder) {#rotateradian_1}

Добавить вращение с указанным порядком

```csharp
public void RotateRadian(Vector3 rot, RotationOrder order)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| rot | Vector3 | Вращение в радианах |
| порядок | RotationOrder |  |

## Примеры

```csharp
TransformBuilder tb = new TransformBuilder();
tb.RotateRadian(new Vector3(0.3, 0.4, 0.1), RotationOrder.YZX);
Console.WriteLine($"Transform Matrix: {tb.Matrix}");
```

### См. также

* struct [Vector3](../../vector3/)
* enum [RotationOrder](../../rotationorder/)
* class [TransformBuilder](../)
* namespace [Aspose.ThreeD.Utilities](../../transformbuilder/)
* assembly [Aspose.3D](../../../)



---
title: "TransformBuilder.RotateEulerRadian"
second_title: "مرجع واجهة برمجة تطبيقات Aspose.3D لـ .NET"
description: "طريقة TransformBuilder. ربط دوران بزوايا أويلر بالراديان"
type: docs
weight: 120
url: /ar/net/aspose.threed.utilities/transformbuilder/rotateeulerradian/
---
## RotateEulerRadian(double, double, double) {#rotateeulerradian_1}

ربط دوران بزوايا أويلر بالراديان

```csharp
public TransformBuilder RotateEulerRadian(double x, double y, double z)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| x | مضاعف |  |
| y | مضاعف |  |
| z | مضاعف |  |

## أمثلة

```csharp
TransformBuilder tb = new TransformBuilder();
tb.RotateEulerRadian(0, Math.PI, 0);
Console.WriteLine($"Transform Matrix: {tb.Matrix}");
```

### انظر أيضًا

* class [TransformBuilder](../)
* namespace [Aspose.ThreeD.Utilities](../../transformbuilder/)
* assembly [Aspose.3D](../../../)

---

## RotateEulerRadian(Vector3) {#rotateeulerradian}

ربط دوران بزوايا أويلر بالراديان

```csharp
public TransformBuilder RotateEulerRadian(Vector3 r)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| r | Vector3 |  |

## أمثلة

```csharp
TransformBuilder tb = new TransformBuilder();
tb.RotateEulerRadian(new Vector3(0, Math.PI, 0));
Console.WriteLine($"Transform Matrix: {tb.Matrix}");
```

### انظر أيضًا

* struct [Vector3](../../vector3/)
* class [TransformBuilder](../)
* namespace [Aspose.ThreeD.Utilities](../../transformbuilder/)
* assembly [Aspose.3D](../../../)



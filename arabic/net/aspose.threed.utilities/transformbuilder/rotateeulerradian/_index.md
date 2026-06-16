---
title: "TransformBuilder.RotateEulerRadian"
second_title: "مرجع Aspose.3D for .NET API"
description: "طريقة TransformBuilder. ربط دوران بزوايا أويلر بالراديان"
type: docs
weight: 120
url: /ar/net/aspose.threed.utilities/transformbuilder/rotateeulerradian/
---
## RotateEulerRadian(double, double, double) {#rotateeulerradian_1}

سلسلة دوران باستخدام زوايا أويلر بالراديان

```csharp
public TransformBuilder RotateEulerRadian(double x, double y, double z)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| x | Double |  |
| y | Double |  |
| z | Double |  |

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

سلسلة دوران باستخدام زوايا أويلر بالراديان

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



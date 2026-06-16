---
title: "TransformBuilder.RotateRadian"
second_title: "مرجع Aspose.3D for .NET API"
description: "طريقة TransformBuilder. ربط تحويل تدوير بالراديان"
type: docs
weight: 130
url: /ar/net/aspose.threed.utilities/transformbuilder/rotateradian/
---
## RotateRadian(double, Vector3) {#rotateradian}

سلسلة تحويل دوران بالراديان

```csharp
public TransformBuilder RotateRadian(double angle, Vector3 axis)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| زاوية | Double | الزاوية للتدوير بالراديان |
| محور | Vector3 | المحور للتدوير |

## أمثلة

```csharp
TransformBuilder tb = new TransformBuilder();
tb.RotateRadian(Math.PI, Vector3.YAxis);
Console.WriteLine($"Transform Matrix: {tb.Matrix}");
```

### انظر أيضًا

* struct [Vector3](../../vector3/)
* class [TransformBuilder](../)
* namespace [Aspose.ThreeD.Utilities](../../transformbuilder/)
* assembly [Aspose.3D](../../../)

---

## RotateRadian(Vector3, RotationOrder) {#rotateradian_1}

إلحاق دوران بترتيب محدد

```csharp
public void RotateRadian(Vector3 rot, RotationOrder order)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| rot | Vector3 | دوران بالراديان |
| ترتيب | RotationOrder |  |

## أمثلة

```csharp
TransformBuilder tb = new TransformBuilder();
tb.RotateRadian(new Vector3(0.3, 0.4, 0.1), RotationOrder.YZX);
Console.WriteLine($"Transform Matrix: {tb.Matrix}");
```

### انظر أيضًا

* struct [Vector3](../../vector3/)
* enum [RotationOrder](../../rotationorder/)
* class [TransformBuilder](../)
* namespace [Aspose.ThreeD.Utilities](../../transformbuilder/)
* assembly [Aspose.3D](../../../)



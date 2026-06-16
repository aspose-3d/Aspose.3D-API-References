---
title: "TransformBuilder.RotateDegree"
second_title: "مرجع Aspose.3D for .NET API"
description: "طريقة TransformBuilder. ربط تحويل دوران بالدرجة"
type: docs
weight: 100
url: /ar/net/aspose.threed.utilities/transformbuilder/rotatedegree/
---
## RotateDegree(double, Vector3) {#rotatedegree}

سلسلة تحويل دوران بالدرجات

```csharp
public TransformBuilder RotateDegree(double angle, Vector3 axis)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| زاوية | Double | الزاوية لتدوير بالدرجة |
| محور | Vector3 | المحور للتدوير |

## أمثلة

```csharp
TransformBuilder tb = new TransformBuilder();
tb.RotateDegree(90, Vector3.YAxis);
Console.WriteLine($"Transform Matrix: {tb.Matrix}");
```

### انظر أيضًا

* struct [Vector3](../../vector3/)
* class [TransformBuilder](../)
* namespace [Aspose.ThreeD.Utilities](../../transformbuilder/)
* assembly [Aspose.3D](../../../)

---

## RotateDegree(Vector3, RotationOrder) {#rotatedegree_1}

إلحاق دوران بترتيب محدد

```csharp
public void RotateDegree(Vector3 rot, RotationOrder order)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| rot | Vector3 | الدوران بالدرجات |
| ترتيب | RotationOrder |  |

### انظر أيضًا

* struct [Vector3](../../vector3/)
* enum [RotationOrder](../../rotationorder/)
* class [TransformBuilder](../)
* namespace [Aspose.ThreeD.Utilities](../../transformbuilder/)
* assembly [Aspose.3D](../../../)



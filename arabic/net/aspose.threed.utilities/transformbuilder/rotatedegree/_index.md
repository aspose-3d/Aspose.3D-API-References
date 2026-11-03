---
title: "TransformBuilder.RotateDegree"
second_title: "مرجع واجهة برمجة تطبيقات Aspose.3D لـ .NET"
description: "طريقة TransformBuilder. سلسلة تحويل دوران بالدرجة"
type: docs
weight: 100
url: /ar/net/aspose.threed.utilities/transformbuilder/rotatedegree/
---
## RotateDegree(double, Vector3) {#rotatedegree}

ربط تحويل دوران بالدرجة

```csharp
public TransformBuilder RotateDegree(double angle, Vector3 axis)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| زاوية | مضاعف | الزاوية للدوران بالدرجة |
| محور | Vector3 | المحور للدوران |

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

إلحاق دوران بالترتيب المحدد

```csharp
public void RotateDegree(Vector3 rot, RotationOrder order)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| rot | Vector3 | الدوران بالدرجات |
| order | RotationOrder |  |

### انظر أيضًا

* struct [Vector3](../../vector3/)
* enum [RotationOrder](../../rotationorder/)
* class [TransformBuilder](../)
* namespace [Aspose.ThreeD.Utilities](../../transformbuilder/)
* assembly [Aspose.3D](../../../)



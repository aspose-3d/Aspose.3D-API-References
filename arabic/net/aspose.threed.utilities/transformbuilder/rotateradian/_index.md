---
title: "TransformBuilder.RotateRadian"
second_title: "مرجع واجهة برمجة تطبيقات Aspose.3D لـ .NET"
description: "طريقة TransformBuilder. سلسلة تحويل دوران بالراديان"
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
| زاوية | مضاعف | الزاوية للدوران بالراديان |
| محور | Vector3 | المحور للدوران |

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

إلحاق دوران بالترتيب المحدد

```csharp
public void RotateRadian(Vector3 rot, RotationOrder order)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| rot | Vector3 | الدوران بالراديان |
| order | RotationOrder |  |

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



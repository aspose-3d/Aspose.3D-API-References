---
title: "TransformBuilder.Scale"
second_title: "مرجع واجهة برمجة تطبيقات Aspose.3D لـ .NET"
description: "طريقة TransformBuilder. سلسلة مصفوفة تحويل قياس مع مكوّن مقاس بـ s"
type: docs
weight: 140
url: /ar/net/aspose.threed.utilities/transformbuilder/scale/
---
## Scale(double) {#scale_1}

سلسلة مصفوفة تحويل قياس مع مكوّن مقاس بـ s

```csharp
public TransformBuilder Scale(double s)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| s | مضاعف |  |

## أمثلة

```csharp
TransformBuilder tb = new TransformBuilder();
tb.Scale(10);
Console.WriteLine($"Transform Matrix: {tb.Matrix}");
```

### انظر أيضًا

* class [TransformBuilder](../)
* namespace [Aspose.ThreeD.Utilities](../../transformbuilder/)
* assembly [Aspose.3D](../../../)

---

## Scale(double, double, double) {#scale_2}

سلسلة مصفوفة تحويل قياس

```csharp
public TransformBuilder Scale(double x, double y, double z)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| x | مضاعف |  |
| y | مضاعف |  |
| z | مضاعف |  |

## أمثلة

```csharp
TransformBuilder tb = new TransformBuilder();
tb.Scale(10, 10, 10);
Console.WriteLine($"Transform Matrix: {tb.Matrix}");
```

### انظر أيضًا

* class [TransformBuilder](../)
* namespace [Aspose.ThreeD.Utilities](../../transformbuilder/)
* assembly [Aspose.3D](../../../)

---

## Scale(Vector3) {#scale}

سلسلة تحويل قياس

```csharp
public TransformBuilder Scale(Vector3 s)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| s | Vector3 |  |

## أمثلة

```csharp
TransformBuilder tb = new TransformBuilder();
tb.Scale(new Vector3(10, 10, 10));
Console.WriteLine($"Transform Matrix: {tb.Matrix}");
```

### انظر أيضًا

* struct [Vector3](../../vector3/)
* class [TransformBuilder](../)
* namespace [Aspose.ThreeD.Utilities](../../transformbuilder/)
* assembly [Aspose.3D](../../../)



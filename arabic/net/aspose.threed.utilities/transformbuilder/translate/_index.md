---
title: "TransformBuilder.Translate"
second_title: "مرجع واجهة برمجة تطبيقات Aspose.3D لـ .NET"
description: "طريقة TransformBuilder. ربط تحويل إزاحة"
type: docs
weight: 150
url: /ar/net/aspose.threed.utilities/transformbuilder/translate/
---
## Translate(double, double, double) {#translate_1}

ربط تحويل إزاحة

```csharp
public TransformBuilder Translate(double tx, double ty, double tz)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| tx | مضاعف |  |
| ty | مضاعف |  |
| tz | مضاعف |  |

## أمثلة

```csharp
TransformBuilder tb = new TransformBuilder();
tb.Translate(0, 10, 0);
Console.WriteLine($"Transform Matrix: {tb.Matrix}");
```

### انظر أيضًا

* class [TransformBuilder](../)
* namespace [Aspose.ThreeD.Utilities](../../transformbuilder/)
* assembly [Aspose.3D](../../../)

---

## Translate(Vector3) {#translate}

ربط تحويل إزاحة

```csharp
public TransformBuilder Translate(Vector3 v)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| v | Vector3 |  |

## أمثلة

```csharp
TransformBuilder tb = new TransformBuilder();
tb.Translate(new Vector3(0, 10, 0));
Console.WriteLine($"Transform Matrix: {tb.Matrix}");
```

### انظر أيضًا

* struct [Vector3](../../vector3/)
* class [TransformBuilder](../)
* namespace [Aspose.ThreeD.Utilities](../../transformbuilder/)
* assembly [Aspose.3D](../../../)



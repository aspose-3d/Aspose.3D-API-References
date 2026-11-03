---
title: "TransformBuilder.Rotate"
second_title: "مرجع واجهة برمجة تطبيقات Aspose.3D لـ .NET"
description: "طريقة TransformBuilder. سلسلة دوران بواسطة رباعية"
type: docs
weight: 90
url: /ar/net/aspose.threed.utilities/transformbuilder/rotate/
---
## TransformBuilder.Rotate method

سلسلة دوران بواسطة رباعية

```csharp
public TransformBuilder Rotate(Quaternion q)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| q | كواتيرنيون |  |

## أمثلة

```csharp
TransformBuilder tb = new TransformBuilder();
tb.Rotate(Quaternion.FromEulerAngle(0, Math.PI, 0));
Console.WriteLine($"Transform Matrix: {tb.Matrix}");
```

### انظر أيضًا

* struct [Quaternion](../../quaternion/)
* class [TransformBuilder](../)
* namespace [Aspose.ThreeD.Utilities](../../transformbuilder/)
* assembly [Aspose.3D](../../../)



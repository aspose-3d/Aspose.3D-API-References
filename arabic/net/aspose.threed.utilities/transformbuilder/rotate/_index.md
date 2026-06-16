---
title: "TransformBuilder.Rotate"
second_title: "مرجع Aspose.3D for .NET API"
description: "طريقة TransformBuilder. ربط تدوير بواسطة كواترنيون"
type: docs
weight: 90
url: /ar/net/aspose.threed.utilities/transformbuilder/rotate/
---
## TransformBuilder.Rotate method

سلسلة دوران باستخدام رباعية

```csharp
public TransformBuilder Rotate(Quaternion q)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| q | كواترنيون |  |

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



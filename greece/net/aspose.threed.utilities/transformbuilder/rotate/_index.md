---
title: "TransformBuilder.Rotate"
second_title: "Αναφορά API Aspose.3D για .NET"
description: "TransformBuilder μέθοδος. Συνδέστε μια περιστροφή με ένα quaternion"
type: docs
weight: 90
url: /el/net/aspose.threed.utilities/transformbuilder/rotate/
---
## TransformBuilder.Rotate method

Αλυσίδα περιστροφής με quaternion

```csharp
public TransformBuilder Rotate(Quaternion q)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| q | Τεταρτοπλέγμα |  |

## Παραδείγματα

```csharp
TransformBuilder tb = new TransformBuilder();
tb.Rotate(Quaternion.FromEulerAngle(0, Math.PI, 0));
Console.WriteLine($"Transform Matrix: {tb.Matrix}");
```

### Δείτε επίσης

* struct [Quaternion](../../quaternion/)
* class [TransformBuilder](../)
* namespace [Aspose.ThreeD.Utilities](../../transformbuilder/)
* assembly [Aspose.3D](../../../)



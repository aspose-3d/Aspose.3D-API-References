---
title: "TransformBuilder.RotateDegree"
second_title: "Αναφορά API Aspose.3D για .NET"
description: "TransformBuilder μέθοδος. Συνδέστε έναν μετασχηματισμό περιστροφής σε μοίρες"
type: docs
weight: 100
url: /el/net/aspose.threed.utilities/transformbuilder/rotatedegree/
---
## RotateDegree(double, Vector3) {#rotatedegree}

Αλυσίδα περιστροφής σε μοίρες

```csharp
public TransformBuilder RotateDegree(double angle, Vector3 axis)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| γωνία | Διπλό | Η γωνία περιστροφής σε μοίρες |
| άξονας | Vector3 | Ο άξονας περιστροφής |

## Παραδείγματα

```csharp
TransformBuilder tb = new TransformBuilder();
tb.RotateDegree(90, Vector3.YAxis);
Console.WriteLine($"Transform Matrix: {tb.Matrix}");
```

### Δείτε επίσης

* struct [Vector3](../../vector3/)
* class [TransformBuilder](../)
* namespace [Aspose.ThreeD.Utilities](../../transformbuilder/)
* assembly [Aspose.3D](../../../)

---

## RotateDegree(Vector3, RotationOrder) {#rotatedegree_1}

Προσθήκη περιστροφής με καθορισμένη σειρά

```csharp
public void RotateDegree(Vector3 rot, RotationOrder order)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| rot | Vector3 | Περιστροφή σε μοίρες |
| σειρά | RotationOrder |  |

### Δείτε επίσης

* struct [Vector3](../../vector3/)
* enum [RotationOrder](../../rotationorder/)
* class [TransformBuilder](../)
* namespace [Aspose.ThreeD.Utilities](../../transformbuilder/)
* assembly [Aspose.3D](../../../)



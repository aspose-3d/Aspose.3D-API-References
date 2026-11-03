---
title: "TransformBuilder.RotateRadian"
second_title: "Αναφορά API Aspose.3D για .NET"
description: "TransformBuilder μέθοδος. Συνδέστε έναν μετασχηματισμό περιστροφής σε ακτίνια"
type: docs
weight: 130
url: /el/net/aspose.threed.utilities/transformbuilder/rotateradian/
---
## RotateRadian(double, Vector3) {#rotateradian}

Αλυσίδα μετασχηματισμού περιστροφής σε ακτίνια

```csharp
public TransformBuilder RotateRadian(double angle, Vector3 axis)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| γωνία | Διπλό | Η γωνία περιστροφής σε ακτίνια |
| άξονας | Vector3 | Ο άξονας περιστροφής |

## Παραδείγματα

```csharp
TransformBuilder tb = new TransformBuilder();
tb.RotateRadian(Math.PI, Vector3.YAxis);
Console.WriteLine($"Transform Matrix: {tb.Matrix}");
```

### Δείτε επίσης

* struct [Vector3](../../vector3/)
* class [TransformBuilder](../)
* namespace [Aspose.ThreeD.Utilities](../../transformbuilder/)
* assembly [Aspose.3D](../../../)

---

## RotateRadian(Vector3, RotationOrder) {#rotateradian_1}

Προσθήκη περιστροφής με καθορισμένη σειρά

```csharp
public void RotateRadian(Vector3 rot, RotationOrder order)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| rot | Vector3 | Περιστροφή σε ακτίνια |
| σειρά | RotationOrder |  |

## Παραδείγματα

```csharp
TransformBuilder tb = new TransformBuilder();
tb.RotateRadian(new Vector3(0.3, 0.4, 0.1), RotationOrder.YZX);
Console.WriteLine($"Transform Matrix: {tb.Matrix}");
```

### Δείτε επίσης

* struct [Vector3](../../vector3/)
* enum [RotationOrder](../../rotationorder/)
* class [TransformBuilder](../)
* namespace [Aspose.ThreeD.Utilities](../../transformbuilder/)
* assembly [Aspose.3D](../../../)



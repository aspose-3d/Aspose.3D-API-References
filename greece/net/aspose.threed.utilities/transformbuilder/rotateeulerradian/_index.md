---
title: "TransformBuilder.RotateEulerRadian"
second_title: "Αναφορά API Aspose.3D για .NET"
description: "Μέθοδος TransformBuilder. Συνδέστε μια περιστροφή με γωνίες Euler σε ακτίνια"
type: docs
weight: 120
url: /el/net/aspose.threed.utilities/transformbuilder/rotateeulerradian/
---
## RotateEulerRadian(double, double, double) {#rotateeulerradian_1}

Αλυσίδα περιστροφής με γωνίες Euler σε ακτίνια

```csharp
public TransformBuilder RotateEulerRadian(double x, double y, double z)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| x | Διπλό |  |
| y | Διπλό |  |
| z | Διπλό |  |

## Παραδείγματα

```csharp
TransformBuilder tb = new TransformBuilder();
tb.RotateEulerRadian(0, Math.PI, 0);
Console.WriteLine($"Transform Matrix: {tb.Matrix}");
```

### Δείτε επίσης

* class [TransformBuilder](../)
* namespace [Aspose.ThreeD.Utilities](../../transformbuilder/)
* assembly [Aspose.3D](../../../)

---

## RotateEulerRadian(Vector3) {#rotateeulerradian}

Αλυσίδα περιστροφής με γωνίες Euler σε ακτίνια

```csharp
public TransformBuilder RotateEulerRadian(Vector3 r)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| r | Vector3 |  |

## Παραδείγματα

```csharp
TransformBuilder tb = new TransformBuilder();
tb.RotateEulerRadian(new Vector3(0, Math.PI, 0));
Console.WriteLine($"Transform Matrix: {tb.Matrix}");
```

### Δείτε επίσης

* struct [Vector3](../../vector3/)
* class [TransformBuilder](../)
* namespace [Aspose.ThreeD.Utilities](../../transformbuilder/)
* assembly [Aspose.3D](../../../)



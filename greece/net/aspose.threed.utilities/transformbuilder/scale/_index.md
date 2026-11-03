---
title: "TransformBuilder.Scale"
second_title: "Αναφορά API Aspose.3D για .NET"
description: "TransformBuilder μέθοδος. Συνδέστε έναν πίνακα κλιμάκωσης με ένα στοιχείο κλιμακωμένο κατά s"
type: docs
weight: 140
url: /el/net/aspose.threed.utilities/transformbuilder/scale/
---
## Scale(double) {#scale_1}

Αλυσίδα πίνακα μετασχηματισμού κλιμάκωσης με ένα στοιχείο κλιμακωμένο κατά s

```csharp
public TransformBuilder Scale(double s)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| s | Διπλό |  |

## Παραδείγματα

```csharp
TransformBuilder tb = new TransformBuilder();
tb.Scale(10);
Console.WriteLine($"Transform Matrix: {tb.Matrix}");
```

### Δείτε επίσης

* class [TransformBuilder](../)
* namespace [Aspose.ThreeD.Utilities](../../transformbuilder/)
* assembly [Aspose.3D](../../../)

---

## Scale(double, double, double) {#scale_2}

Αλυσίδα πίνακα μετασχηματισμού κλιμάκωσης

```csharp
public TransformBuilder Scale(double x, double y, double z)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| x | Διπλό |  |
| y | Διπλό |  |
| z | Διπλό |  |

## Παραδείγματα

```csharp
TransformBuilder tb = new TransformBuilder();
tb.Scale(10, 10, 10);
Console.WriteLine($"Transform Matrix: {tb.Matrix}");
```

### Δείτε επίσης

* class [TransformBuilder](../)
* namespace [Aspose.ThreeD.Utilities](../../transformbuilder/)
* assembly [Aspose.3D](../../../)

---

## Scale(Vector3) {#scale}

Αλυσίδα μετασχηματισμού κλίμακας

```csharp
public TransformBuilder Scale(Vector3 s)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| s | Vector3 |  |

## Παραδείγματα

```csharp
TransformBuilder tb = new TransformBuilder();
tb.Scale(new Vector3(10, 10, 10));
Console.WriteLine($"Transform Matrix: {tb.Matrix}");
```

### Δείτε επίσης

* struct [Vector3](../../vector3/)
* class [TransformBuilder](../)
* namespace [Aspose.ThreeD.Utilities](../../transformbuilder/)
* assembly [Aspose.3D](../../../)



---
title: "TransformBuilder.Translate"
second_title: "Αναφορά API Aspose.3D για .NET"
description: "Μέθοδος TransformBuilder. Συνδέστε έναν μετασχηματισμό μετάφρασης"
type: docs
weight: 150
url: /el/net/aspose.threed.utilities/transformbuilder/translate/
---
## Translate(double, double, double) {#translate_1}

Αλυσίδα μετασχηματισμού μετάφρασης

```csharp
public TransformBuilder Translate(double tx, double ty, double tz)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| tx | Διπλό |  |
| ty | Διπλό |  |
| tz | Διπλό |  |

## Παραδείγματα

```csharp
TransformBuilder tb = new TransformBuilder();
tb.Translate(0, 10, 0);
Console.WriteLine($"Transform Matrix: {tb.Matrix}");
```

### Δείτε επίσης

* class [TransformBuilder](../)
* namespace [Aspose.ThreeD.Utilities](../../transformbuilder/)
* assembly [Aspose.3D](../../../)

---

## Translate(Vector3) {#translate}

Αλυσίδα μετασχηματισμού μετάφρασης

```csharp
public TransformBuilder Translate(Vector3 v)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| v | Vector3 |  |

## Παραδείγματα

```csharp
TransformBuilder tb = new TransformBuilder();
tb.Translate(new Vector3(0, 10, 0));
Console.WriteLine($"Transform Matrix: {tb.Matrix}");
```

### Δείτε επίσης

* struct [Vector3](../../vector3/)
* class [TransformBuilder](../)
* namespace [Aspose.ThreeD.Utilities](../../transformbuilder/)
* assembly [Aspose.3D](../../../)



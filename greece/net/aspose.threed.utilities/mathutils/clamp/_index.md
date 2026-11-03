---
title: "MathUtils.Clamp"
second_title: "Αναφορά API Aspose.3D για .NET"
description: "Μέθοδος MathUtils. Περιορίζει την τιμή στο εύρος ελάχιστο μέγιστο"
type: docs
weight: 20
url: /el/net/aspose.threed.utilities/mathutils/clamp/
---
## MathUtils.Clamp method

Περιορίζει την τιμή στο εύρος [min, max]

```csharp
public static double Clamp(double val, double min, double max)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| val | Διπλό | Τιμή προς περιορισμό. |
| min | Διπλό | Ελάχιστη τιμή. |
| max | Διπλό | Μέγιστη τιμή. |

### Τιμή επιστροφής

Η τιμή μεταξύ [min, max]

## Παραδείγματα

```csharp
var val = 195;
//Περιορίζει την τιμή στο [0, 100]
var clampedValue = MathUtils.Clamp(val, 0, 100);
//Αυτό θα εμφανίσει 100
Console.WriteLine($"Value = {val}");
```

### Δείτε επίσης

* class [MathUtils](../)
* namespace [Aspose.ThreeD.Utilities](../../mathutils/)
* assembly [Aspose.3D](../../../)



---
title: "MathUtils.Clamp"
second_title: "Aspose.3D für .NET API-Referenz"
description: "MathUtils-Methode. Wert auf den Bereich min max begrenzen."
type: docs
weight: 20
url: /de/net/aspose.threed.utilities/mathutils/clamp/
---
## MathUtils.Clamp method

Begrenze den Wert auf den Bereich [min, max]

```csharp
public static double Clamp(double val, double min, double max)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| val | Double | Wert zum Begrenzen. |
| min | Double | Minimaler Wert. |
| max | Double | Maximaler Wert. |

### Rückgabewert

Der Wert zwischen [min, max]

## Beispiele

```csharp
var val = 195;
//Wert auf [0, 100] begrenzen
var clampedValue = MathUtils.Clamp(val, 0, 100);
//Dies gibt 100 aus
Console.WriteLine($"Value = {val}");
```

### Siehe auch

* class [MathUtils](../)
* namespace [Aspose.ThreeD.Utilities](../../mathutils/)
* assembly [Aspose.3D](../../../)



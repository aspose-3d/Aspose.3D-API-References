---
title: "MathUtils.Clamp"
second_title: "Référence de l'API Aspose.3D pour .NET"
description: "Méthode MathUtils. Limite la valeur à la plage min max"
type: docs
weight: 20
url: /fr/net/aspose.threed.utilities/mathutils/clamp/
---
## MathUtils.Clamp method

Limite la valeur à la plage [min, max]

```csharp
public static double Clamp(double val, double min, double max)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| val | Double | Valeur à limiter. |
| min | Double | Valeur minimale. |
| max | Double | Valeur maximale. |

### Valeur de retour

La valeur entre [min, max]

## Exemples

```csharp
var val = 195;
//Limiter la valeur à [0, 100]
var clampedValue = MathUtils.Clamp(val, 0, 100);
//Cela affichera 100
Console.WriteLine($"Value = {val}");
```

### Voir aussi

* class [MathUtils](../)
* namespace [Aspose.ThreeD.Utilities](../../mathutils/)
* assembly [Aspose.3D](../../../)



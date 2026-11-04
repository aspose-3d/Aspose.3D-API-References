---
title: "MathUtils.Clamp"
second_title: "Referencia de la API de Aspose.3D para .NET"
description: "Método MathUtils. Limita el valor al rango min max"
type: docs
weight: 20
url: /es/net/aspose.threed.utilities/mathutils/clamp/
---
## MathUtils.Clamp method

Limita el valor al rango [min, max]

```csharp
public static double Clamp(double val, double min, double max)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| val | Doble | Valor a limitar. |
| min | Doble | Valor mínimo. |
| max | Doble | Valor máximo. |

### Valor de retorno

El valor entre [min, max]

## Ejemplos

```csharp
var val = 195;
//Limita el valor a [0, 100]
var clampedValue = MathUtils.Clamp(val, 0, 100);
//Esto producirá 100
Console.WriteLine($"Value = {val}");
```

### Ver también

* class [MathUtils](../)
* namespace [Aspose.ThreeD.Utilities](../../mathutils/)
* assembly [Aspose.3D](../../../)



---
title: "TransformBuilder.RotateEulerDegree"
second_title: "Referencia de la API de Aspose.3D para .NET"
description: "Método TransformBuilder. Encadena una rotación mediante ángulos de Euler en grados"
type: docs
weight: 110
url: /es/net/aspose.threed.utilities/transformbuilder/rotateeulerdegree/
---
## TransformBuilder.RotateEulerDegree method

Encadenar una rotación por ángulos de Euler en grados

```csharp
public TransformBuilder RotateEulerDegree(double degX, double degY, double degZ)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| degX | Doble |  |
| degY | Doble |  |
| degZ | Doble |  |

## Ejemplos

```csharp
TransformBuilder tb = new TransformBuilder();
tb.RotateEulerDegree(0, 90, 0);
Console.WriteLine($"Transform Matrix: {tb.Matrix}");
```

### Ver también

* class [TransformBuilder](../)
* namespace [Aspose.ThreeD.Utilities](../../transformbuilder/)
* assembly [Aspose.3D](../../../)



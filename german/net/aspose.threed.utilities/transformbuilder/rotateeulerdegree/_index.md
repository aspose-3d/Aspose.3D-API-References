---
title: "TransformBuilder.RotateEulerDegree"
second_title: "Aspose.3D für .NET API-Referenz"
description: "TransformBuilder-Methode. Kette eine Rotation um Euler-Winkel in Grad."
type: docs
weight: 110
url: /de/net/aspose.threed.utilities/transformbuilder/rotateeulerdegree/
---
## TransformBuilder.RotateEulerDegree method

Verkette eine Rotation mittels Euler-Winkeln in Grad.

```csharp
public TransformBuilder RotateEulerDegree(double degX, double degY, double degZ)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| degX | Double |  |
| degY | Double |  |
| degZ | Double |  |

## Beispiele

```csharp
TransformBuilder tb = new TransformBuilder();
tb.RotateEulerDegree(0, 90, 0);
Console.WriteLine($"Transform Matrix: {tb.Matrix}");
```

### Siehe auch

* class [TransformBuilder](../)
* namespace [Aspose.ThreeD.Utilities](../../transformbuilder/)
* assembly [Aspose.3D](../../../)



---
title: "TransformBuilder.Rotate"
second_title: "Aspose.3D für .NET API-Referenz"
description: "TransformBuilder-Methode. Kette eine Rotation mittels Quaternion."
type: docs
weight: 90
url: /de/net/aspose.threed.utilities/transformbuilder/rotate/
---
## TransformBuilder.Rotate method

Verkette eine Rotation mittels Quaternion.

```csharp
public TransformBuilder Rotate(Quaternion q)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| q | Quaternion |  |

## Beispiele

```csharp
TransformBuilder tb = new TransformBuilder();
tb.Rotate(Quaternion.FromEulerAngle(0, Math.PI, 0));
Console.WriteLine($"Transform Matrix: {tb.Matrix}");
```

### Siehe auch

* struct [Quaternion](../../quaternion/)
* class [TransformBuilder](../)
* namespace [Aspose.ThreeD.Utilities](../../transformbuilder/)
* assembly [Aspose.3D](../../../)



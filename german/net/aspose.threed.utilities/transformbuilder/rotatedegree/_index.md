---
title: "TransformBuilder.RotateDegree"
second_title: "Aspose.3D für .NET API-Referenz"
description: "TransformBuilder-Methode. Ketten Sie eine Rotations-Transformation in Grad"
type: docs
weight: 100
url: /de/net/aspose.threed.utilities/transformbuilder/rotatedegree/
---
## RotateDegree(double, Vector3) {#rotatedegree}

Verkette eine Rotations-Transformation in Grad.

```csharp
public TransformBuilder RotateDegree(double angle, Vector3 axis)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Winkel | Double | Der Winkel zum Rotieren in Grad |
| Achse | Vector3 | Die Achse zum Rotieren |

## Beispiele

```csharp
TransformBuilder tb = new TransformBuilder();
tb.RotateDegree(90, Vector3.YAxis);
Console.WriteLine($"Transform Matrix: {tb.Matrix}");
```

### Siehe auch

* struct [Vector3](../../vector3/)
* class [TransformBuilder](../)
* namespace [Aspose.ThreeD.Utilities](../../transformbuilder/)
* assembly [Aspose.3D](../../../)

---

## RotateDegree(Vector3, RotationOrder) {#rotatedegree_1}

Füge eine Rotation mit angegebener Reihenfolge hinzu.

```csharp
public void RotateDegree(Vector3 rot, RotationOrder order)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| rot | Vector3 | Rotation in Grad |
| order | RotationOrder |  |

### Siehe auch

* struct [Vector3](../../vector3/)
* enum [RotationOrder](../../rotationorder/)
* class [TransformBuilder](../)
* namespace [Aspose.ThreeD.Utilities](../../transformbuilder/)
* assembly [Aspose.3D](../../../)



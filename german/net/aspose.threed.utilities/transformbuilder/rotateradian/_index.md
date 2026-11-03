---
title: "TransformBuilder.RotateRadian"
second_title: "Aspose.3D für .NET API-Referenz"
description: "TransformBuilder-Methode. Ketten Sie eine Rotations-Transformation im Radianten"
type: docs
weight: 130
url: /de/net/aspose.threed.utilities/transformbuilder/rotateradian/
---
## RotateRadian(double, Vector3) {#rotateradian}

Verkette eine Rotations-Transformation in Bogenmaß.

```csharp
public TransformBuilder RotateRadian(double angle, Vector3 axis)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Winkel | Double | Der Winkel zum Rotieren im Radianten |
| Achse | Vector3 | Die Achse zum Rotieren |

## Beispiele

```csharp
TransformBuilder tb = new TransformBuilder();
tb.RotateRadian(Math.PI, Vector3.YAxis);
Console.WriteLine($"Transform Matrix: {tb.Matrix}");
```

### Siehe auch

* struct [Vector3](../../vector3/)
* class [TransformBuilder](../)
* namespace [Aspose.ThreeD.Utilities](../../transformbuilder/)
* assembly [Aspose.3D](../../../)

---

## RotateRadian(Vector3, RotationOrder) {#rotateradian_1}

Füge eine Rotation mit angegebener Reihenfolge hinzu.

```csharp
public void RotateRadian(Vector3 rot, RotationOrder order)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| rot | Vector3 | Rotation im Bogenmaß |
| order | RotationOrder |  |

## Beispiele

```csharp
TransformBuilder tb = new TransformBuilder();
tb.RotateRadian(new Vector3(0.3, 0.4, 0.1), RotationOrder.YZX);
Console.WriteLine($"Transform Matrix: {tb.Matrix}");
```

### Siehe auch

* struct [Vector3](../../vector3/)
* enum [RotationOrder](../../rotationorder/)
* class [TransformBuilder](../)
* namespace [Aspose.ThreeD.Utilities](../../transformbuilder/)
* assembly [Aspose.3D](../../../)



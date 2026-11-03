---
title: "TransformBuilder.RotateEulerRadian"
second_title: "Aspose.3D für .NET API-Referenz"
description: "TransformBuilder-Methode. Verkette eine Rotation um Euler-Winkel im Bogenmaß"
type: docs
weight: 120
url: /de/net/aspose.threed.utilities/transformbuilder/rotateeulerradian/
---
## RotateEulerRadian(double, double, double) {#rotateeulerradian_1}

Verkette eine Rotation mittels Euler-Winkeln in Bogenmaß.

```csharp
public TransformBuilder RotateEulerRadian(double x, double y, double z)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| x | Double |  |
| y | Double |  |
| z | Double |  |

## Beispiele

```csharp
TransformBuilder tb = new TransformBuilder();
tb.RotateEulerRadian(0, Math.PI, 0);
Console.WriteLine($"Transform Matrix: {tb.Matrix}");
```

### Siehe auch

* class [TransformBuilder](../)
* namespace [Aspose.ThreeD.Utilities](../../transformbuilder/)
* assembly [Aspose.3D](../../../)

---

## RotateEulerRadian(Vector3) {#rotateeulerradian}

Verkette eine Rotation mittels Euler-Winkeln in Bogenmaß.

```csharp
public TransformBuilder RotateEulerRadian(Vector3 r)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| r | Vector3 |  |

## Beispiele

```csharp
TransformBuilder tb = new TransformBuilder();
tb.RotateEulerRadian(new Vector3(0, Math.PI, 0));
Console.WriteLine($"Transform Matrix: {tb.Matrix}");
```

### Siehe auch

* struct [Vector3](../../vector3/)
* class [TransformBuilder](../)
* namespace [Aspose.ThreeD.Utilities](../../transformbuilder/)
* assembly [Aspose.3D](../../../)



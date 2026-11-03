---
title: "Matrix4.Rotate"
second_title: "Aspose.3D für .NET API-Referenz"
description: "Matrix4-Methode. Erstellt eine Rotationsmatrix anhand des Rotationswinkels und der Achse"
type: docs
weight: 30
url: /de/net/aspose.threed.utilities/matrix4/rotate/
---
## Rotate(double, Vector3) {#rotate_1}

Erstelle eine Rotationsmatrix anhand des Rotationswinkels und der Achse

```csharp
public static Matrix4 Rotate(double angle, Vector3 axis)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Winkel | Double | Rotationswinkel in Radiant |
| Achse | Vector3 | Rotationsachse |

## Beispiele

Der folgende Code zeigt, wie man eine Matrix für eine Rotationsoperation erstellt.

```csharp
var t = Matrix4.Rotate(Math.PI, new Vector3(0, 1, 0));
var pos = new Vector3(1, 1, 10);
Console.WriteLine($"Transformed: {t * pos}");
```

### Siehe auch

* struct [Vector3](../../vector3/)
* struct [Matrix4](../)
* namespace [Aspose.ThreeD.Utilities](../../matrix4/)
* assembly [Aspose.3D](../../../)

---

## Rotate(Quaternion) {#rotate}

Erstelle eine Rotationsmatrix aus einem Quaternion

```csharp
public static Matrix4 Rotate(Quaternion q)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| q | Quaternion | Rotations-Quaternion |

## Beispiele

Der folgende Code zeigt, wie man eine Matrix für eine Rotationsoperation erstellt.

```csharp
var t = Matrix4.Rotate(Quaternion.FromAngleAxis(Math.PI, Vector3.YAxis));
var pos = new Vector3(1, 1, 10);
Console.WriteLine($"Transformed: {t * pos}");
```

### Siehe auch

* struct [Quaternion](../../quaternion/)
* struct [Matrix4](../)
* namespace [Aspose.ThreeD.Utilities](../../matrix4/)
* assembly [Aspose.3D](../../../)



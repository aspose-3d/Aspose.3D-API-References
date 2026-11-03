---
title: "Matrix4.RotateFromEuler"
second_title: "Aspose.3D für .NET API-Referenz"
description: "Matrix4-Methode. Erstellt eine Rotationsmatrix aus einem Euler-Winkel"
type: docs
weight: 40
url: /de/net/aspose.threed.utilities/matrix4/rotatefromeuler/
---
## RotateFromEuler(Vector3) {#rotatefromeuler}

Erstelle eine Rotationsmatrix aus einem Euler-Winkel

```csharp
public static Matrix4 RotateFromEuler(Vector3 eul)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| eul | Vector3 | Rotation im Bogenmaß |

## Beispiele

Der folgende Code zeigt, wie man eine Matrix für eine Rotationsoperation erstellt.

```csharp
var t = Matrix4.RotateFromEuler(new Vector3(0, Math.PI, 0));
var pos = new Vector3(1, 1, 10);
Console.WriteLine($"Transformed: {t * pos}");
```

### Siehe auch

* struct [Vector3](../../vector3/)
* struct [Matrix4](../)
* namespace [Aspose.ThreeD.Utilities](../../matrix4/)
* assembly [Aspose.3D](../../../)

---

## RotateFromEuler(double, double, double) {#rotatefromeuler_1}

Erstelle eine Rotationsmatrix aus einem Euler-Winkel

```csharp
public static Matrix4 RotateFromEuler(double rx, double ry, double rz)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| rx | Double | Rotation um die x-Achse im Bogenmaß |
| ry | Double | Rotation um die y-Achse im Bogenmaß |
| rz | Double | Rotation um die z-Achse in Radiant |

## Beispiele

Der folgende Code zeigt, wie man eine Matrix für eine Rotationsoperation erstellt.

```csharp
var t = Matrix4.RotateFromEuler(0, Math.PI, 0);
var pos = new Vector3(1, 1, 10);
Console.WriteLine($"Transformed: {t * pos}");
```

### Siehe auch

* struct [Matrix4](../)
* namespace [Aspose.ThreeD.Utilities](../../matrix4/)
* assembly [Aspose.3D](../../../)



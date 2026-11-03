---
title: "Klasse GlobalTransform"
second_title: "Aspose.3D für .NET API-Referenz"
description: "Aspose.ThreeD.GlobalTransform Klasse. Globale Transformation ist ähnlich wie Transform, aber sie ist unveränderlich, während sie die endgültig ausgewertete Transformation darstellt. Ein rechtshändiges Koordinatensystem wird bei der Auswertung der globalen Transformation verwendet"
type: docs
weight: 1560
url: /de/net/aspose.threed/globaltransform/
---
## GlobalTransform class

Globale Transformation ist ähnlich wie [`Transform`](../transform/), aber sie ist unveränderlich, während sie die endgültig ausgewertete Transformation darstellt. Ein rechtshändiges Koordinatensystem wird bei der Auswertung der globalen Transformation verwendet

```csharp
public class GlobalTransform
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [EulerAngles](../../aspose.threed/globaltransform/eulerangles/) { get; } | Liest die Rotation, dargestellt in Euler-Winkeln, gemessen in Grad |
| [Rotation](../../aspose.threed/globaltransform/rotation/) { get; } | Liest die Rotation, dargestellt als Quaternion. |
| [Scale](../../aspose.threed/globaltransform/scale/) { get; } | Liest die Skalierung |
| [TransformMatrix](../../aspose.threed/globaltransform/transformmatrix/) { get; } | Liest die Transformationsmatrix. |
| [Translation](../../aspose.threed/globaltransform/translation/) { get; } | Liest die Translation |

## Beispiele

Der folgende Code zeigt, wie man die globale Transformation eines Knotens liest

```csharp
Scene scene = new Scene();
var boxNode = scene.RootNode.CreateChildNode(new Box());
//Platziere die Box bei (10, 0, 0)
boxNode.Transform.Translation = new Vector3(10, 0, 0);
var global = boxNode.GlobalTransform;
Console.WriteLine($"The box's position in world coordinate is {global.Translation}");
```

### Siehe auch

* namespace [Aspose.ThreeD](../../aspose.threed/)
* assembly [Aspose.3D](../../)



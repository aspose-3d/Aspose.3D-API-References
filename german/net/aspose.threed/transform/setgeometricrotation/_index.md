---
title: "Transform.SetGeometricRotation"
second_title: "Aspose.3D für .NET API-Referenz"
description: "Transform-Methode. Setzt die geometrische Euler-Rotation, gemessen in Grad. Geometrische Transformation wirkt nur auf die angehängten Entitäten und lässt die Kindknoten unbeeinflusst. Sie wird als lokale Transformation zusammengeführt, wenn Sie die geometrische Transformation in Dateitypen exportieren, die sie nicht unterstützen."
type: docs
weight: 160
url: /de/net/aspose.threed/transform/setgeometricrotation/
---
## Transform.SetGeometricRotation method

Setzt die geometrische Euler‑Rotation (gemessen in Grad). Geometrische Transformation wirkt sich nur auf die angehängten Entitäten aus und lässt die Kindknoten unverändert. Sie wird als lokale Transformation zusammengeführt, wenn Sie die geometrische Transformation in Dateitypen exportieren, die sie nicht unterstützen.

```csharp
public Transform SetGeometricRotation(double rx, double ry, double rz)
```

## Beispiele

```csharp
Node node = new Node();
node.Transform.SetGeometricRotation(90, 0, 0);
```

### Siehe auch

* class [Transform](../)
* namespace [Aspose.ThreeD](../../transform/)
* assembly [Aspose.3D](../../../)



---
title: "Transform.GeometricRotation"
second_title: "Aspose.3D für .NET API-Referenz"
description: "Transform-Eigenschaft. Liest oder schreibt die geometrische Euler-Rotation, gemessen in Grad. Geometrische Transformation wirkt nur auf die angehängten Entitäten und lässt die Kindknoten unbeeinflusst. Sie wird als lokale Transformation zusammengeführt, wenn Sie die geometrische Transformation in Dateitypen exportieren, die sie nicht unterstützen."
type: docs
weight: 20
url: /de/net/aspose.threed/transform/geometricrotation/
---
## Transform.GeometricRotation property

Liest oder setzt die geometrische Euler-Rotation (gemessen in Grad). Geometrische Transformation wirkt sich nur auf die angehängten Entitäten aus und lässt die Kindknoten unverändert. Sie wird als lokale Transformation zusammengeführt, wenn Sie die geometrische Transformation in Dateitypen exportieren, die sie nicht unterstützen.

```csharp
public Vector3 GeometricRotation { get; set; }
```

## Beispiele

```csharp
Node node = new Node();
node.getTransform().setGeometricRotation(new Vector3(90, 0, 0));
```

### Siehe auch

* struct [Vector3](../../../aspose.threed.utilities/vector3/)
* class [Transform](../)
* namespace [Aspose.ThreeD](../../transform/)
* assembly [Aspose.3D](../../../)



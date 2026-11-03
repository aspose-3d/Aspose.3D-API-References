---
title: "Transform.SetGeometricScaling"
second_title: "Aspose.3D für .NET API-Referenz"
description: "Transform-Methode. Setzt die geometrische Skalierung. Geometrische Transformation wirkt nur auf die angehängten Entitäten und lässt die Kindknoten unbeeinflusst. Sie wird als lokale Transformation zusammengeführt, wenn Sie die geometrische Transformation in Dateitypen exportieren, die sie nicht unterstützen."
type: docs
weight: 170
url: /de/net/aspose.threed/transform/setgeometricscaling/
---
## Transform.SetGeometricScaling method

Setzt die geometrische Skalierung. Geometrische Transformation wirkt sich nur auf die angehängten Entitäten aus und lässt die Kindknoten unverändert. Sie wird als lokale Transformation zusammengeführt, wenn Sie die geometrische Transformation in Dateitypen exportieren, die sie nicht unterstützen.

```csharp
public Transform SetGeometricScaling(double sx, double sy, double sz)
```

## Beispiele

```csharp
Node node = new Node();
node.Transform.SetGeometricScaling(2, 2, 2);
```

### Siehe auch

* class [Transform](../)
* namespace [Aspose.ThreeD](../../transform/)
* assembly [Aspose.3D](../../../)



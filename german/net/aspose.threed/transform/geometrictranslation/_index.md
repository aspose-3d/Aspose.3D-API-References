---
title: "Transform.GeometricTranslation"
second_title: "Aspose.3D für .NET API-Referenz"
description: "Transform-Eigenschaft. Liest oder setzt die geometrische Translation. Geometrische Transformation wirkt nur auf die angehängten Entitäten und lässt die Kindknoten unbeeinflusst. Sie wird als lokale Transformation zusammengeführt, wenn Sie die geometrische Transformation in Dateitypen exportieren, die sie nicht unterstützen."
type: docs
weight: 40
url: /de/net/aspose.threed/transform/geometrictranslation/
---
## Transform.GeometricTranslation property

Liest oder setzt die geometrische Translation. Geometrische Transformation wirkt sich nur auf die angehängten Entitäten aus und lässt die Kindknoten unverändert. Sie wird als lokale Transformation zusammengeführt, wenn Sie die geometrische Transformation in Dateitypen exportieren, die sie nicht unterstützen.

```csharp
public Vector3 GeometricTranslation { get; set; }
```

## Beispiele

```csharp
Node node = new Node();
node.Transform.GeometricTranslation = new Vector3(10, 0, 0);
```

### Siehe auch

* struct [Vector3](../../../aspose.threed.utilities/vector3/)
* class [Transform](../)
* namespace [Aspose.ThreeD](../../transform/)
* assembly [Aspose.3D](../../../)



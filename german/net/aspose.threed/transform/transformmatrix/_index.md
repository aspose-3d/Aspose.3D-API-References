---
title: "Transform.TransformMatrix"
second_title: "Aspose.3D für .NET API-Referenz"
description: "Transform-Eigenschaft. Liest oder setzt die Transformationsmatrix"
type: docs
weight: 130
url: /de/net/aspose.threed/transform/transformmatrix/
---
## Transform.TransformMatrix property

Liest oder setzt die Transformationsmatrix.

```csharp
public Matrix4 TransformMatrix { get; set; }
```

## Hinweise

Durch Zuweisung hier werden die [`Translation`](../translation/), [`Scaling`](../scaling/) und [`Rotation`](../rotation/) zurückgesetzt, die [`GeometricRotation`](../geometricrotation/), [`GeometricScaling`](../geometricscaling/) und [`GeometricTranslation`](../geometrictranslation/) bleiben unverändert.

## Beispiele

```csharp
Node node = new Node();
node.Transform.TransformMatrix = Matrix4.Identity;
```

### Siehe auch

* struct [Matrix4](../../../aspose.threed.utilities/matrix4/)
* class [Transform](../)
* namespace [Aspose.ThreeD](../../transform/)
* assembly [Aspose.3D](../../../)



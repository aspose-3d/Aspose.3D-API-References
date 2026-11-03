---
title: "Transform.TransformMatrix"
second_title: "Αναφορά API Aspose.3D για .NET"
description: "Ιδιότητα Transform. Λαμβάνει ή ορίζει τον πίνακα μετασχηματισμού"
type: docs
weight: 130
url: /el/net/aspose.threed/transform/transformmatrix/
---
## Transform.TransformMatrix property

Λαμβάνει ή ορίζει τον πίνακα μετασχηματισμού.

```csharp
public Matrix4 TransformMatrix { get; set; }
```

## Παρατηρήσεις

Η εκχώρηση σε αυτό θα επαναφέρει το [`Translation`](../translation/), το [`Scaling`](../scaling/) και το [`Rotation`](../rotation/), ενώ το [`GeometricRotation`](../geometricrotation/), το [`GeometricScaling`](../geometricscaling/) και το [`GeometricTranslation`](../geometrictranslation/) δεν θα επηρεαστούν.

## Παραδείγματα

```csharp
Node node = new Node();
node.Transform.TransformMatrix = Matrix4.Identity;
```

### Δείτε επίσης

* struct [Matrix4](../../../aspose.threed.utilities/matrix4/)
* class [Transform](../)
* namespace [Aspose.ThreeD](../../transform/)
* assembly [Aspose.3D](../../../)



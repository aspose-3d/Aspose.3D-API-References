---
title: "Transform.TransformMatrix"
second_title: "Référence de l'API Aspose.3D pour .NET"
description: "Propriété Transform. Obtient ou définit la matrice de transformation"
type: docs
weight: 130
url: /fr/net/aspose.threed/transform/transformmatrix/
---
## Transform.TransformMatrix property

Obtient ou définit la matrice de transformation.

```csharp
public Matrix4 TransformMatrix { get; set; }
```

## Remarques

L'affectation sur cet objet réinitialisera les [`Translation`](../translation/), [`Scaling`](../scaling/) et [`Rotation`](../rotation/), les [`GeometricRotation`](../geometricrotation/), [`GeometricScaling`](../geometricscaling/) et [`GeometricTranslation`](../geometrictranslation/) ne seront pas affectés.

## Exemples

```csharp
Node node = new Node();
node.Transform.TransformMatrix = Matrix4.Identity;
```

### Voir aussi

* struct [Matrix4](../../../aspose.threed.utilities/matrix4/)
* class [Transform](../)
* namespace [Aspose.ThreeD](../../transform/)
* assembly [Aspose.3D](../../../)



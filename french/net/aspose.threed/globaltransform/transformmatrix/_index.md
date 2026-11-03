---
title: "GlobalTransform.TransformMatrix"
second_title: "Référence de l'API Aspose.3D pour .NET"
description: "Propriété GlobalTransform. Obtient la matrice de transformation"
type: docs
weight: 40
url: /fr/net/aspose.threed/globaltransform/transformmatrix/
---
## GlobalTransform.TransformMatrix property

Obtient la matrice de transformation.

```csharp
public Matrix4 TransformMatrix { get; }
```

## Exemples

```csharp
Scene scene = Scene.FromFile("test.fbx");
var tr = scene.RootNode.GlobalTransform;
Console.WriteLine($"Matrix = {tr.TransformMatrix}");
```

### Voir aussi

* struct [Matrix4](../../../aspose.threed.utilities/matrix4/)
* class [GlobalTransform](../)
* namespace [Aspose.ThreeD](../../globaltransform/)
* assembly [Aspose.3D](../../../)



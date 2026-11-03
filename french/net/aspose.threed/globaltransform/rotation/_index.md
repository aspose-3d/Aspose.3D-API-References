---
title: "GlobalTransform.Rotation"
second_title: "Référence de l'API Aspose.3D pour .NET"
description: "Propriété GlobalTransform. Obtient la rotation représentée sous forme de quaternion"
type: docs
weight: 20
url: /fr/net/aspose.threed/globaltransform/rotation/
---
## GlobalTransform.Rotation property

Obtient la rotation représentée en quaternion.

```csharp
public Quaternion Rotation { get; }
```

## Exemples

```csharp
Scene scene = Scene.FromFile("test.fbx");
var tr = scene.RootNode.GlobalTransform;
Console.WriteLine($"Rotation = {tr.Rotation}");
```

### Voir aussi

* struct [Quaternion](../../../aspose.threed.utilities/quaternion/)
* class [GlobalTransform](../)
* namespace [Aspose.ThreeD](../../globaltransform/)
* assembly [Aspose.3D](../../../)



---
title: "GlobalTransform.Scale"
second_title: "Référence de l'API Aspose.3D pour .NET"
description: "Propriété GlobalTransform. Obtient l'échelle"
type: docs
weight: 30
url: /fr/net/aspose.threed/globaltransform/scale/
---
## GlobalTransform.Scale property

Obtient l'échelle

```csharp
public Vector3 Scale { get; }
```

## Exemples

```csharp
Scene scene = Scene.FromFile("test.fbx");
var tr = scene.RootNode.GlobalTransform;
Console.WriteLine($"Scale = {tr.Scale}");
```

### Voir aussi

* struct [Vector3](../../../aspose.threed.utilities/vector3/)
* class [GlobalTransform](../)
* namespace [Aspose.ThreeD](../../globaltransform/)
* assembly [Aspose.3D](../../../)



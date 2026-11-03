---
title: "GlobalTransform.Translation"
second_title: "Référence de l'API Aspose.3D pour .NET"
description: "Propriété GlobalTransform. Obtient la translation"
type: docs
weight: 50
url: /fr/net/aspose.threed/globaltransform/translation/
---
## GlobalTransform.Translation property

Obtient la translation

```csharp
public Vector3 Translation { get; }
```

## Exemples

```csharp
Scene scene = Scene.FromFile("test.fbx");
var tr = scene.RootNode.GlobalTransform;
Console.WriteLine($"Translation = {tr.Translation}");
```

### Voir aussi

* struct [Vector3](../../../aspose.threed.utilities/vector3/)
* class [GlobalTransform](../)
* namespace [Aspose.ThreeD](../../globaltransform/)
* assembly [Aspose.3D](../../../)



---
title: "GlobalTransform.Scale"
second_title: "Αναφορά API Aspose.3D για .NET"
description: "Ιδιότητα GlobalTransform. Επιστρέφει την κλίμακα"
type: docs
weight: 30
url: /el/net/aspose.threed/globaltransform/scale/
---
## GlobalTransform.Scale property

Λαμβάνει την κλίμακα

```csharp
public Vector3 Scale { get; }
```

## Παραδείγματα

```csharp
Scene scene = Scene.FromFile("test.fbx");
var tr = scene.RootNode.GlobalTransform;
Console.WriteLine($"Scale = {tr.Scale}");
```

### Δείτε επίσης

* struct [Vector3](../../../aspose.threed.utilities/vector3/)
* class [GlobalTransform](../)
* namespace [Aspose.ThreeD](../../globaltransform/)
* assembly [Aspose.3D](../../../)



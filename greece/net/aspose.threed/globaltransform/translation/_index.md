---
title: "GlobalTransform.Translation"
second_title: "Αναφορά API Aspose.3D για .NET"
description: "Ιδιότητα GlobalTransform. Λαμβάνει τη μετάφραση"
type: docs
weight: 50
url: /el/net/aspose.threed/globaltransform/translation/
---
## GlobalTransform.Translation property

Λαμβάνει τη μετάφραση

```csharp
public Vector3 Translation { get; }
```

## Παραδείγματα

```csharp
Scene scene = Scene.FromFile("test.fbx");
var tr = scene.RootNode.GlobalTransform;
Console.WriteLine($"Translation = {tr.Translation}");
```

### Δείτε επίσης

* struct [Vector3](../../../aspose.threed.utilities/vector3/)
* class [GlobalTransform](../)
* namespace [Aspose.ThreeD](../../globaltransform/)
* assembly [Aspose.3D](../../../)



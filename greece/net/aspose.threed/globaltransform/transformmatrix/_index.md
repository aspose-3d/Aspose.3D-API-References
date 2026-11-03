---
title: "GlobalTransform.TransformMatrix"
second_title: "Αναφορά API Aspose.3D για .NET"
description: "Ιδιότητα GlobalTransform. Επιστρέφει τον πίνακα μετασχηματισμού"
type: docs
weight: 40
url: /el/net/aspose.threed/globaltransform/transformmatrix/
---
## GlobalTransform.TransformMatrix property

Λαμβάνει τον πίνακα μετασχηματισμού.

```csharp
public Matrix4 TransformMatrix { get; }
```

## Παραδείγματα

```csharp
Scene scene = Scene.FromFile("test.fbx");
var tr = scene.RootNode.GlobalTransform;
Console.WriteLine($"Matrix = {tr.TransformMatrix}");
```

### Δείτε επίσης

* struct [Matrix4](../../../aspose.threed.utilities/matrix4/)
* class [GlobalTransform](../)
* namespace [Aspose.ThreeD](../../globaltransform/)
* assembly [Aspose.3D](../../../)



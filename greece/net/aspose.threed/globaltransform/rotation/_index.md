---
title: "GlobalTransform.Rotation"
second_title: "Αναφορά API Aspose.3D για .NET"
description: "Ιδιότητα GlobalTransform. Λαμβάνει την περιστροφή που αναπαρίσταται σε quaternion"
type: docs
weight: 20
url: /el/net/aspose.threed/globaltransform/rotation/
---
## GlobalTransform.Rotation property

Λαμβάνει την περιστροφή που εκφράζεται σε quaternion.

```csharp
public Quaternion Rotation { get; }
```

## Παραδείγματα

```csharp
Scene scene = Scene.FromFile("test.fbx");
var tr = scene.RootNode.GlobalTransform;
Console.WriteLine($"Rotation = {tr.Rotation}");
```

### Δείτε επίσης

* struct [Quaternion](../../../aspose.threed.utilities/quaternion/)
* class [GlobalTransform](../)
* namespace [Aspose.ThreeD](../../globaltransform/)
* assembly [Aspose.3D](../../../)



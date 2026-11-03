---
title: "GlobalTransform.EulerAngles"
second_title: "Αναφορά API Aspose.3D για .NET"
description: "Ιδιότητα GlobalTransform. Λαμβάνει την περιστροφή που αναπαρίσταται σε γωνίες Euler μετρημένες σε μοίρες"
type: docs
weight: 10
url: /el/net/aspose.threed/globaltransform/eulerangles/
---
## GlobalTransform.EulerAngles property

Λαμβάνει την περιστροφή που εκφράζεται σε γωνίες Euler, μετρημένες σε μοίρες

```csharp
public Vector3 EulerAngles { get; }
```

## Παραδείγματα

```csharp
Scene scene = Scene.FromFile("test.fbx");
var tr = scene.RootNode.GlobalTransform;
Console.WriteLine($"EulerAngles = {tr.EulerAngles}");
```

### Δείτε επίσης

* struct [Vector3](../../../aspose.threed.utilities/vector3/)
* class [GlobalTransform](../)
* namespace [Aspose.ThreeD](../../globaltransform/)
* assembly [Aspose.3D](../../../)



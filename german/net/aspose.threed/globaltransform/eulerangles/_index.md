---
title: "GlobalTransform.EulerAngles"
second_title: "Aspose.3D für .NET API-Referenz"
description: "GlobalTransform-Eigenschaft. Liest die Rotation, dargestellt in Euler-Winkeln gemessen in Grad"
type: docs
weight: 10
url: /de/net/aspose.threed/globaltransform/eulerangles/
---
## GlobalTransform.EulerAngles property

Liest die Rotation, dargestellt in Euler-Winkeln, gemessen in Grad

```csharp
public Vector3 EulerAngles { get; }
```

## Beispiele

```csharp
Scene scene = Scene.FromFile("test.fbx");
var tr = scene.RootNode.GlobalTransform;
Console.WriteLine($"EulerAngles = {tr.EulerAngles}");
```

### Siehe auch

* struct [Vector3](../../../aspose.threed.utilities/vector3/)
* class [GlobalTransform](../)
* namespace [Aspose.ThreeD](../../globaltransform/)
* assembly [Aspose.3D](../../../)



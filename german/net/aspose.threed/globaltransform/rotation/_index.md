---
title: "GlobalTransform.Rotation"
second_title: "Aspose.3D für .NET API-Referenz"
description: "GlobalTransform-Eigenschaft. Liest die Rotation, dargestellt als Quaternion"
type: docs
weight: 20
url: /de/net/aspose.threed/globaltransform/rotation/
---
## GlobalTransform.Rotation property

Liest die Rotation, dargestellt als Quaternion.

```csharp
public Quaternion Rotation { get; }
```

## Beispiele

```csharp
Scene scene = Scene.FromFile("test.fbx");
var tr = scene.RootNode.GlobalTransform;
Console.WriteLine($"Rotation = {tr.Rotation}");
```

### Siehe auch

* struct [Quaternion](../../../aspose.threed.utilities/quaternion/)
* class [GlobalTransform](../)
* namespace [Aspose.ThreeD](../../globaltransform/)
* assembly [Aspose.3D](../../../)



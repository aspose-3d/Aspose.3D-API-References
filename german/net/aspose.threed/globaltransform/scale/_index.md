---
title: "GlobalTransform.Scale"
second_title: "Aspose.3D für .NET API-Referenz"
description: "GlobalTransform-Eigenschaft. Liest die Skalierung"
type: docs
weight: 30
url: /de/net/aspose.threed/globaltransform/scale/
---
## GlobalTransform.Scale property

Liest die Skalierung

```csharp
public Vector3 Scale { get; }
```

## Beispiele

```csharp
Scene scene = Scene.FromFile("test.fbx");
var tr = scene.RootNode.GlobalTransform;
Console.WriteLine($"Scale = {tr.Scale}");
```

### Siehe auch

* struct [Vector3](../../../aspose.threed.utilities/vector3/)
* class [GlobalTransform](../)
* namespace [Aspose.ThreeD](../../globaltransform/)
* assembly [Aspose.3D](../../../)



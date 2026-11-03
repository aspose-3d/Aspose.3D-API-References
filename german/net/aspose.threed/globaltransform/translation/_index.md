---
title: "GlobalTransform.Translation"
second_title: "Aspose.3D für .NET API-Referenz"
description: "GlobalTransform-Eigenschaft. Liest die Verschiebung"
type: docs
weight: 50
url: /de/net/aspose.threed/globaltransform/translation/
---
## GlobalTransform.Translation property

Liest die Translation

```csharp
public Vector3 Translation { get; }
```

## Beispiele

```csharp
Scene scene = Scene.FromFile("test.fbx");
var tr = scene.RootNode.GlobalTransform;
Console.WriteLine($"Translation = {tr.Translation}");
```

### Siehe auch

* struct [Vector3](../../../aspose.threed.utilities/vector3/)
* class [GlobalTransform](../)
* namespace [Aspose.ThreeD](../../globaltransform/)
* assembly [Aspose.3D](../../../)



---
title: "GlobalTransform.TransformMatrix"
second_title: "Aspose.3D für .NET API-Referenz"
description: "GlobalTransform-Eigenschaft. Liest die Transformationsmatrix"
type: docs
weight: 40
url: /de/net/aspose.threed/globaltransform/transformmatrix/
---
## GlobalTransform.TransformMatrix property

Liest die Transformationsmatrix.

```csharp
public Matrix4 TransformMatrix { get; }
```

## Beispiele

```csharp
Scene scene = Scene.FromFile("test.fbx");
var tr = scene.RootNode.GlobalTransform;
Console.WriteLine($"Matrix = {tr.TransformMatrix}");
```

### Siehe auch

* struct [Matrix4](../../../aspose.threed.utilities/matrix4/)
* class [GlobalTransform](../)
* namespace [Aspose.ThreeD](../../globaltransform/)
* assembly [Aspose.3D](../../../)



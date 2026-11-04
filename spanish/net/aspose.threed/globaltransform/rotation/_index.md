---
title: "GlobalTransform.Rotation"
second_title: "Referencia de la API de Aspose.3D para .NET"
description: "Propiedad GlobalTransform. Obtiene la rotación representada en cuaternión"
type: docs
weight: 20
url: /es/net/aspose.threed/globaltransform/rotation/
---
## GlobalTransform.Rotation property

Obtiene la rotación representada en cuaternión.

```csharp
public Quaternion Rotation { get; }
```

## Ejemplos

```csharp
Scene scene = Scene.FromFile("test.fbx");
var tr = scene.RootNode.GlobalTransform;
Console.WriteLine($"Rotation = {tr.Rotation}");
```

### Ver también

* struct [Quaternion](../../../aspose.threed.utilities/quaternion/)
* class [GlobalTransform](../)
* namespace [Aspose.ThreeD](../../globaltransform/)
* assembly [Aspose.3D](../../../)



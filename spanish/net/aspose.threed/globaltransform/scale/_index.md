---
title: "GlobalTransform.Scale"
second_title: "Referencia de la API de Aspose.3D para .NET"
description: "Propiedad GlobalTransform. Obtiene la escala"
type: docs
weight: 30
url: /es/net/aspose.threed/globaltransform/scale/
---
## GlobalTransform.Scale property

Obtiene la escala

```csharp
public Vector3 Scale { get; }
```

## Ejemplos

```csharp
Scene scene = Scene.FromFile("test.fbx");
var tr = scene.RootNode.GlobalTransform;
Console.WriteLine($"Scale = {tr.Scale}");
```

### Ver también

* struct [Vector3](../../../aspose.threed.utilities/vector3/)
* class [GlobalTransform](../)
* namespace [Aspose.ThreeD](../../globaltransform/)
* assembly [Aspose.3D](../../../)



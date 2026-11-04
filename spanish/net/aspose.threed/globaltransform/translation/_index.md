---
title: "GlobalTransform.Translation"
second_title: "Referencia de la API de Aspose.3D para .NET"
description: "Propiedad GlobalTransform. Obtiene la traslación"
type: docs
weight: 50
url: /es/net/aspose.threed/globaltransform/translation/
---
## GlobalTransform.Translation property

Obtiene la traslación

```csharp
public Vector3 Translation { get; }
```

## Ejemplos

```csharp
Scene scene = Scene.FromFile("test.fbx");
var tr = scene.RootNode.GlobalTransform;
Console.WriteLine($"Translation = {tr.Translation}");
```

### Ver también

* struct [Vector3](../../../aspose.threed.utilities/vector3/)
* class [GlobalTransform](../)
* namespace [Aspose.ThreeD](../../globaltransform/)
* assembly [Aspose.3D](../../../)



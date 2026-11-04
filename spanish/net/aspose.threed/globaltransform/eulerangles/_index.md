---
title: "GlobalTransform.EulerAngles"
second_title: "Referencia de la API de Aspose.3D para .NET"
description: "Propiedad GlobalTransform. Obtiene la rotación representada en ángulos de Euler medidos en grados"
type: docs
weight: 10
url: /es/net/aspose.threed/globaltransform/eulerangles/
---
## GlobalTransform.EulerAngles property

Obtiene la rotación representada en ángulos de Euler, medida en grados

```csharp
public Vector3 EulerAngles { get; }
```

## Ejemplos

```csharp
Scene scene = Scene.FromFile("test.fbx");
var tr = scene.RootNode.GlobalTransform;
Console.WriteLine($"EulerAngles = {tr.EulerAngles}");
```

### Ver también

* struct [Vector3](../../../aspose.threed.utilities/vector3/)
* class [GlobalTransform](../)
* namespace [Aspose.ThreeD](../../globaltransform/)
* assembly [Aspose.3D](../../../)



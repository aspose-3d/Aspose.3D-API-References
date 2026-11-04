---
title: "GlobalTransform.TransformMatrix"
second_title: "Referencia de la API de Aspose.3D para .NET"
description: "Propiedad GlobalTransform. Obtiene la matriz de transformación"
type: docs
weight: 40
url: /es/net/aspose.threed/globaltransform/transformmatrix/
---
## GlobalTransform.TransformMatrix property

Obtiene la matriz de transformación.

```csharp
public Matrix4 TransformMatrix { get; }
```

## Ejemplos

```csharp
Scene scene = Scene.FromFile("test.fbx");
var tr = scene.RootNode.GlobalTransform;
Console.WriteLine($"Matrix = {tr.TransformMatrix}");
```

### Ver también

* struct [Matrix4](../../../aspose.threed.utilities/matrix4/)
* class [GlobalTransform](../)
* namespace [Aspose.ThreeD](../../globaltransform/)
* assembly [Aspose.3D](../../../)



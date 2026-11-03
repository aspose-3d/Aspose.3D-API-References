---
title: "GlobalTransform.EulerAngles"
second_title: "Référence de l'API Aspose.3D pour .NET"
description: "Propriété GlobalTransform. Obtient la rotation représentée en angles d'Euler mesurés en degrés"
type: docs
weight: 10
url: /fr/net/aspose.threed/globaltransform/eulerangles/
---
## GlobalTransform.EulerAngles property

Obtient la rotation représentée en angles d'Euler, mesurée en degrés

```csharp
public Vector3 EulerAngles { get; }
```

## Exemples

```csharp
Scene scene = Scene.FromFile("test.fbx");
var tr = scene.RootNode.GlobalTransform;
Console.WriteLine($"EulerAngles = {tr.EulerAngles}");
```

### Voir aussi

* struct [Vector3](../../../aspose.threed.utilities/vector3/)
* class [GlobalTransform](../)
* namespace [Aspose.ThreeD](../../globaltransform/)
* assembly [Aspose.3D](../../../)



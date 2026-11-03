---
title: "GlobalTransform.Scale"
second_title: "Aspose.3D के लिए .NET API संदर्भ"
description: "GlobalTransform प्रॉपर्टी। स्केल प्राप्त करता है"
type: docs
weight: 30
url: /hi/net/aspose.threed/globaltransform/scale/
---
## GlobalTransform.Scale property

स्केल प्राप्त करता है

```csharp
public Vector3 Scale { get; }
```

## उदाहरण

```csharp
Scene scene = Scene.FromFile("test.fbx");
var tr = scene.RootNode.GlobalTransform;
Console.WriteLine($"Scale = {tr.Scale}");
```

### देखें भी

* struct [Vector3](../../../aspose.threed.utilities/vector3/)
* class [GlobalTransform](../)
* namespace [Aspose.ThreeD](../../globaltransform/)
* assembly [Aspose.3D](../../../)



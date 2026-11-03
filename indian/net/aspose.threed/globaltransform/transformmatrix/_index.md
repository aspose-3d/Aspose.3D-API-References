---
title: "GlobalTransform.TransformMatrix"
second_title: "Aspose.3D के लिए .NET API संदर्भ"
description: "GlobalTransform प्रॉपर्टी। ट्रांसफ़ॉर्म मैट्रिक्स प्राप्त करता है"
type: docs
weight: 40
url: /hi/net/aspose.threed/globaltransform/transformmatrix/
---
## GlobalTransform.TransformMatrix property

ट्रांसफ़ॉर्म मैट्रिक्स प्राप्त करता है।

```csharp
public Matrix4 TransformMatrix { get; }
```

## उदाहरण

```csharp
Scene scene = Scene.FromFile("test.fbx");
var tr = scene.RootNode.GlobalTransform;
Console.WriteLine($"Matrix = {tr.TransformMatrix}");
```

### देखें भी

* struct [Matrix4](../../../aspose.threed.utilities/matrix4/)
* class [GlobalTransform](../)
* namespace [Aspose.ThreeD](../../globaltransform/)
* assembly [Aspose.3D](../../../)



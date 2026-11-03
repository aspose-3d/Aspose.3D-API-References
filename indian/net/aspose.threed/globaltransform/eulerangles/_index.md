---
title: "GlobalTransform.EulerAngles"
second_title: "Aspose.3D के लिए .NET API संदर्भ"
description: "GlobalTransform प्रॉपर्टी। डिग्री में मापे गए यूलेर कोणों में दर्शाए गए रोटेशन को प्राप्त करता है"
type: docs
weight: 10
url: /hi/net/aspose.threed/globaltransform/eulerangles/
---
## GlobalTransform.EulerAngles property

Euler कोणों में दर्शाए गए घूर्णन को प्राप्त करता है, डिग्री में मापा गया

```csharp
public Vector3 EulerAngles { get; }
```

## उदाहरण

```csharp
Scene scene = Scene.FromFile("test.fbx");
var tr = scene.RootNode.GlobalTransform;
Console.WriteLine($"EulerAngles = {tr.EulerAngles}");
```

### देखें भी

* struct [Vector3](../../../aspose.threed.utilities/vector3/)
* class [GlobalTransform](../)
* namespace [Aspose.ThreeD](../../globaltransform/)
* assembly [Aspose.3D](../../../)



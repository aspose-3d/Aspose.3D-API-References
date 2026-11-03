---
title: "GlobalTransform.Rotation"
second_title: "Aspose.3D के लिए .NET API संदर्भ"
description: "GlobalTransform प्रॉपर्टी। क्वाटरनियन में दर्शाए गए रोटेशन को प्राप्त करता है"
type: docs
weight: 20
url: /hi/net/aspose.threed/globaltransform/rotation/
---
## GlobalTransform.Rotation property

क्वाटरनियन में दर्शाए गए घूर्णन को प्राप्त करता है।

```csharp
public Quaternion Rotation { get; }
```

## उदाहरण

```csharp
Scene scene = Scene.FromFile("test.fbx");
var tr = scene.RootNode.GlobalTransform;
Console.WriteLine($"Rotation = {tr.Rotation}");
```

### देखें भी

* struct [Quaternion](../../../aspose.threed.utilities/quaternion/)
* class [GlobalTransform](../)
* namespace [Aspose.ThreeD](../../globaltransform/)
* assembly [Aspose.3D](../../../)



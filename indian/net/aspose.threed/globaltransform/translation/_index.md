---
title: "GlobalTransform.Translation"
second_title: "Aspose.3D के लिए .NET API संदर्भ"
description: "GlobalTransform प्रॉपर्टी। ट्रांसलेशन प्राप्त करता है"
type: docs
weight: 50
url: /hi/net/aspose.threed/globaltransform/translation/
---
## GlobalTransform.Translation property

अनुवाद प्राप्त करता है

```csharp
public Vector3 Translation { get; }
```

## उदाहरण

```csharp
Scene scene = Scene.FromFile("test.fbx");
var tr = scene.RootNode.GlobalTransform;
Console.WriteLine($"Translation = {tr.Translation}");
```

### देखें भी

* struct [Vector3](../../../aspose.threed.utilities/vector3/)
* class [GlobalTransform](../)
* namespace [Aspose.ThreeD](../../globaltransform/)
* assembly [Aspose.3D](../../../)



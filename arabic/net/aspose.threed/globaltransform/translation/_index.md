---
title: "GlobalTransform.Translation"
second_title: "مرجع Aspose.3D for .NET API"
description: "خاصية GlobalTransform. تحصل على الإزاحة"
type: docs
weight: 50
url: /ar/net/aspose.threed/globaltransform/translation/
---
## GlobalTransform.Translation property

يحصل على الإزاحة

```csharp
public Vector3 Translation { get; }
```

## أمثلة

```csharp
Scene scene = Scene.FromFile("test.fbx");
var tr = scene.RootNode.GlobalTransform;
Console.WriteLine($"Translation = {tr.Translation}");
```

### انظر أيضًا

* struct [Vector3](../../../aspose.threed.utilities/vector3/)
* class [GlobalTransform](../)
* namespace [Aspose.ThreeD](../../globaltransform/)
* assembly [Aspose.3D](../../../)



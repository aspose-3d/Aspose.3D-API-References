---
title: "GlobalTransform.Scale"
second_title: "مرجع Aspose.3D for .NET API"
description: "خاصية GlobalTransform. تحصل على المقياس"
type: docs
weight: 30
url: /ar/net/aspose.threed/globaltransform/scale/
---
## GlobalTransform.Scale property

يحصل على المقياس

```csharp
public Vector3 Scale { get; }
```

## أمثلة

```csharp
Scene scene = Scene.FromFile("test.fbx");
var tr = scene.RootNode.GlobalTransform;
Console.WriteLine($"Scale = {tr.Scale}");
```

### انظر أيضًا

* struct [Vector3](../../../aspose.threed.utilities/vector3/)
* class [GlobalTransform](../)
* namespace [Aspose.ThreeD](../../globaltransform/)
* assembly [Aspose.3D](../../../)



---
title: "GlobalTransform.TransformMatrix"
second_title: "مرجع Aspose.3D for .NET API"
description: "خاصية GlobalTransform. تحصل على مصفوفة التحويل"
type: docs
weight: 40
url: /ar/net/aspose.threed/globaltransform/transformmatrix/
---
## GlobalTransform.TransformMatrix property

يحصل على مصفوفة التحويل.

```csharp
public Matrix4 TransformMatrix { get; }
```

## أمثلة

```csharp
Scene scene = Scene.FromFile("test.fbx");
var tr = scene.RootNode.GlobalTransform;
Console.WriteLine($"Matrix = {tr.TransformMatrix}");
```

### انظر أيضًا

* struct [Matrix4](../../../aspose.threed.utilities/matrix4/)
* class [GlobalTransform](../)
* namespace [Aspose.ThreeD](../../globaltransform/)
* assembly [Aspose.3D](../../../)



---
title: "GlobalTransform.Rotation"
second_title: "مرجع Aspose.3D for .NET API"
description: "خاصية GlobalTransform. تحصل على الدوران الممثل بالكوaternion"
type: docs
weight: 20
url: /ar/net/aspose.threed/globaltransform/rotation/
---
## GlobalTransform.Rotation property

الحصول على الدوران الممثّل بالـ quaternion.

```csharp
public Quaternion Rotation { get; }
```

## أمثلة

```csharp
Scene scene = Scene.FromFile("test.fbx");
var tr = scene.RootNode.GlobalTransform;
Console.WriteLine($"Rotation = {tr.Rotation}");
```

### انظر أيضًا

* struct [Quaternion](../../../aspose.threed.utilities/quaternion/)
* class [GlobalTransform](../)
* namespace [Aspose.ThreeD](../../globaltransform/)
* assembly [Aspose.3D](../../../)



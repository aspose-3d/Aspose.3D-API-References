---
title: "GlobalTransform.Rotation"
second_title: "مرجع واجهة برمجة تطبيقات Aspose.3D لـ .NET"
description: "GlobalTransform خاصية. يحصل على الدوران الممثل بالكوaternion"
type: docs
weight: 20
url: /ar/net/aspose.threed/globaltransform/rotation/
---
## GlobalTransform.Rotation property

يحصل على الدوران الممثل بالكوaternion.

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



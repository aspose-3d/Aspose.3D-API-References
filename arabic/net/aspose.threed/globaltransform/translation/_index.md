---
title: "GlobalTransform.Translation"
second_title: "مرجع واجهة برمجة تطبيقات Aspose.3D لـ .NET"
description: "GlobalTransform property. يحصل على الترجمة"
type: docs
weight: 50
url: /ar/net/aspose.threed/globaltransform/translation/
---
## GlobalTransform.Translation property

يحصل على الترجمة

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



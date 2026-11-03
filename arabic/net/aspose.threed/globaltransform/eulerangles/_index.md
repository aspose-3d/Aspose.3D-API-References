---
title: "GlobalTransform.EulerAngles"
second_title: "مرجع واجهة برمجة تطبيقات Aspose.3D لـ .NET"
description: "GlobalTransform property. يحصل على الدوران الممثّل بزايا أويلر مقاسة بالدرجة"
type: docs
weight: 10
url: /ar/net/aspose.threed/globaltransform/eulerangles/
---
## GlobalTransform.EulerAngles property

يحصل على الدوران الممثل بزايا أويلر، مقاسًا بالدرجة

```csharp
public Vector3 EulerAngles { get; }
```

## أمثلة

```csharp
Scene scene = Scene.FromFile("test.fbx");
var tr = scene.RootNode.GlobalTransform;
Console.WriteLine($"EulerAngles = {tr.EulerAngles}");
```

### انظر أيضًا

* struct [Vector3](../../../aspose.threed.utilities/vector3/)
* class [GlobalTransform](../)
* namespace [Aspose.ThreeD](../../globaltransform/)
* assembly [Aspose.3D](../../../)



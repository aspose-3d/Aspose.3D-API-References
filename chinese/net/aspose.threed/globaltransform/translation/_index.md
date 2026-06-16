---
title: "GlobalTransform.Translation"
second_title: "Aspose.3D for .NET API 参考"
description: "GlobalTransform 属性。获取平移"
type: docs
weight: 50
url: /zh/net/aspose.threed/globaltransform/translation/
---
## GlobalTransform.Translation property

获取平移

```csharp
public Vector3 Translation { get; }
```

## 示例

```csharp
Scene scene = Scene.FromFile("test.fbx");
var tr = scene.RootNode.GlobalTransform;
Console.WriteLine($"Translation = {tr.Translation}");
```

### 另请参见

* struct [Vector3](../../../aspose.threed.utilities/vector3/)
* class [GlobalTransform](../)
* namespace [Aspose.ThreeD](../../globaltransform/)
* assembly [Aspose.3D](../../../)



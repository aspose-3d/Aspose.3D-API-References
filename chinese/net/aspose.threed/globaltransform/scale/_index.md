---
title: "GlobalTransform.Scale"
second_title: "Aspose.3D for .NET API 参考"
description: "GlobalTransform 属性。获取缩放"
type: docs
weight: 30
url: /zh/net/aspose.threed/globaltransform/scale/
---
## GlobalTransform.Scale property

获取缩放

```csharp
public Vector3 Scale { get; }
```

## 示例

```csharp
Scene scene = Scene.FromFile("test.fbx");
var tr = scene.RootNode.GlobalTransform;
Console.WriteLine($"Scale = {tr.Scale}");
```

### 另请参见

* struct [Vector3](../../../aspose.threed.utilities/vector3/)
* class [GlobalTransform](../)
* namespace [Aspose.ThreeD](../../globaltransform/)
* assembly [Aspose.3D](../../../)



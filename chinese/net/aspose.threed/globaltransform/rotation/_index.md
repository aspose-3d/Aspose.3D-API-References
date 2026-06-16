---
title: "GlobalTransform.Rotation"
second_title: "Aspose.3D for .NET API 参考"
description: "GlobalTransform 属性。获取以四元数表示的旋转"
type: docs
weight: 20
url: /zh/net/aspose.threed/globaltransform/rotation/
---
## GlobalTransform.Rotation property

获取以四元数表示的旋转。

```csharp
public Quaternion Rotation { get; }
```

## 示例

```csharp
Scene scene = Scene.FromFile("test.fbx");
var tr = scene.RootNode.GlobalTransform;
Console.WriteLine($"Rotation = {tr.Rotation}");
```

### 另请参见

* struct [Quaternion](../../../aspose.threed.utilities/quaternion/)
* class [GlobalTransform](../)
* namespace [Aspose.ThreeD](../../globaltransform/)
* assembly [Aspose.3D](../../../)



---
title: "GlobalTransform.TransformMatrix"
second_title: "Aspose.3D for .NET API 参考"
description: "GlobalTransform 属性。获取变换矩阵"
type: docs
weight: 40
url: /zh/net/aspose.threed/globaltransform/transformmatrix/
---
## GlobalTransform.TransformMatrix property

获取变换矩阵。

```csharp
public Matrix4 TransformMatrix { get; }
```

## 示例

```csharp
Scene scene = Scene.FromFile("test.fbx");
var tr = scene.RootNode.GlobalTransform;
Console.WriteLine($"Matrix = {tr.TransformMatrix}");
```

### 另请参见

* struct [Matrix4](../../../aspose.threed.utilities/matrix4/)
* class [GlobalTransform](../)
* namespace [Aspose.ThreeD](../../globaltransform/)
* assembly [Aspose.3D](../../../)



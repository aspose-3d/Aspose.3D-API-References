---
title: "GlobalTransform.EulerAngles"
second_title: "Aspose.3D for .NET API 参考"
description: "GlobalTransform 属性。获取以度为单位表示的欧拉角旋转"
type: docs
weight: 10
url: /zh/net/aspose.threed/globaltransform/eulerangles/
---
## GlobalTransform.EulerAngles property

获取以欧拉角表示的旋转，单位为度

```csharp
public Vector3 EulerAngles { get; }
```

## 示例

```csharp
Scene scene = Scene.FromFile("test.fbx");
var tr = scene.RootNode.GlobalTransform;
Console.WriteLine($"EulerAngles = {tr.EulerAngles}");
```

### 另请参见

* struct [Vector3](../../../aspose.threed.utilities/vector3/)
* class [GlobalTransform](../)
* namespace [Aspose.ThreeD](../../globaltransform/)
* assembly [Aspose.3D](../../../)



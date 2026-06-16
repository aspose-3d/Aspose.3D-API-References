---
title: "Transform.SetGeometricRotation"
second_title: "Aspose.3D for .NET API 参考"
description: "Transform 方法。设置以度为单位的几何欧拉旋转。几何变换仅影响附加的实体，而不影响子节点。当您将几何变换导出到不支持该变换的文件类型时，它将合并为局部变换。"
type: docs
weight: 160
url: /zh/net/aspose.threed/transform/setgeometricrotation/
---
## Transform.SetGeometricRotation method

设置几何欧拉旋转（以度为单位）。几何变换仅影响附加的实体，而不影响子节点。当您将几何变换导出到不支持该变换的文件类型时，它将合并为局部变换。

```csharp
public Transform SetGeometricRotation(double rx, double ry, double rz)
```

## 示例

```csharp
Node node = new Node();
node.Transform.SetGeometricRotation(90, 0, 0);
```

### 另请参见

* class [Transform](../)
* namespace [Aspose.ThreeD](../../transform/)
* assembly [Aspose.3D](../../../)



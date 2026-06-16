---
title: "Transform.SetGeometricScaling"
second_title: "Aspose.3D for .NET API 参考"
description: "Transform 方法。设置几何缩放。几何变换仅影响附加的实体，而不影响子节点。当您将几何变换导出到不支持该变换的文件类型时，它将合并为局部变换。"
type: docs
weight: 170
url: /zh/net/aspose.threed/transform/setgeometricscaling/
---
## Transform.SetGeometricScaling method

设置几何缩放。几何变换仅影响附加的实体，而不影响子节点。当您将几何变换导出到不支持该变换的文件类型时，它将合并为局部变换。

```csharp
public Transform SetGeometricScaling(double sx, double sy, double sz)
```

## 示例

```csharp
Node node = new Node();
node.Transform.SetGeometricScaling(2, 2, 2);
```

### 另请参见

* class [Transform](../)
* namespace [Aspose.ThreeD](../../transform/)
* assembly [Aspose.3D](../../../)



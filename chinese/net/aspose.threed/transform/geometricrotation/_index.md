---
title: "Transform.GeometricRotation"
second_title: "Aspose.3D for .NET API 参考"
description: "Transform 属性。获取或设置几何欧拉旋转，单位为度。几何变换仅影响附加的实体，并且不影响子节点。当导出几何变换到不支持此功能的文件类型时，它将合并为局部变换"
type: docs
weight: 20
url: /zh/net/aspose.threed/transform/geometricrotation/
---
## Transform.GeometricRotation property

获取或设置几何欧拉旋转（以度为单位）。几何变换仅影响附加的实体，而不影响子节点。当您将几何变换导出到不支持该变换的文件类型时，它将合并为局部变换。

```csharp
public Vector3 GeometricRotation { get; set; }
```

## 示例

```csharp
Node node = new Node();
node.getTransform().setGeometricRotation(new Vector3(90, 0, 0));
```

### 另请参见

* struct [Vector3](../../../aspose.threed.utilities/vector3/)
* class [Transform](../)
* namespace [Aspose.ThreeD](../../transform/)
* assembly [Aspose.3D](../../../)



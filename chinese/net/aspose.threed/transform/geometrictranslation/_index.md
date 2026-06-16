---
title: "Transform.GeometricTranslation"
second_title: "Aspose.3D for .NET API 参考"
description: "Transform 属性。获取或设置几何平移。几何变换仅影响附加的实体，而不影响子节点。当您将几何变换导出到不支持该变换的文件类型时，它将合并为局部变换。"
type: docs
weight: 40
url: /zh/net/aspose.threed/transform/geometrictranslation/
---
## Transform.GeometricTranslation property

获取或设置几何平移。几何变换仅影响附加的实体，而不影响子节点。当您将几何变换导出到不支持该变换的文件类型时，它将合并为局部变换。

```csharp
public Vector3 GeometricTranslation { get; set; }
```

## 示例

```csharp
Node node = new Node();
node.Transform.GeometricTranslation = new Vector3(10, 0, 0);
```

### 另请参见

* struct [Vector3](../../../aspose.threed.utilities/vector3/)
* class [Transform](../)
* namespace [Aspose.ThreeD](../../transform/)
* assembly [Aspose.3D](../../../)



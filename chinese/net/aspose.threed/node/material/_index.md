---
title: "Node.Material"
second_title: "Aspose.3D for .NET API 参考"
description: "Node 属性。获取或设置与此节点关联的第一个材质，设置后将清除其他材质"
type: docs
weight: 80
url: /zh/net/aspose.threed/node/material/
---
## Node.Material property

获取或设置与此节点关联的第一个材质，如果设置，将清除其他材质。

```csharp
public Material Material { get; set; }
```

### Property Value

该材质。

## 示例

```csharp
Scene scene = new Scene();
var node = scene.RootNode.CreateChildNode(new Box());
node.Material = new LambertMaterial();
```

### 另请参见

* class [Material](../../../aspose.threed.shading/material/)
* class [Node](../)
* namespace [Aspose.ThreeD](../../node/)
* assembly [Aspose.3D](../../../)



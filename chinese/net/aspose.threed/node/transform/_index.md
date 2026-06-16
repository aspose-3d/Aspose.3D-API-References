---
title: "Node.Transform"
second_title: "Aspose.3D for .NET API 参考"
description: "Node 属性。获取局部变换"
type: docs
weight: 120
url: /zh/net/aspose.threed/node/transform/
---
## Node.Transform property

获取局部变换。

```csharp
public Transform Transform { get; }
```

### Property Value

变换。

## 示例

以下代码展示了如何更改节点的变换：

```csharp
Scene scene = new Scene();
var boxNode = scene.RootNode.CreateChildNode(new Box());
//将盒子放置在 (10, 0, 0) 处
boxNode.Transform.Translation = new Vector3(10, 0, 0);
```

### 另请参见

* class [Transform](../../transform/)
* class [Node](../)
* namespace [Aspose.ThreeD](../../node/)
* assembly [Aspose.3D](../../../)



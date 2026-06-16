---
title: "Scene.RootNode"
second_title: "Aspose.3D for .NET API 参考"
description: "Scene 属性。获取场景的根节点"
type: docs
weight: 90
url: /zh/net/aspose.threed/scene/rootnode/
---
## Scene.RootNode property

获取场景的根节点。

```csharp
public Node RootNode { get; }
```

### Property Value

根节点。

## 示例

以下代码演示如何创建一个节点，并将 Box 实体附加到根节点。

```csharp
Scene scene = new Scene();
scene.RootNode.CreateChildNode(new Box());
scene.Save("box.stl");
```

### 另请参见

* class [Node](../../node/)
* class [Scene](../)
* namespace [Aspose.ThreeD](../../scene/)
* assembly [Aspose.3D](../../../)



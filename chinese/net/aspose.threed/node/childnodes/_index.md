---
title: "Node.ChildNodes"
second_title: "Aspose.3D for .NET API 参考"
description: "Node 属性。获取子节点"
type: docs
weight: 30
url: /zh/net/aspose.threed/node/childnodes/
---
## Node.ChildNodes property

获取子节点。

```csharp
public IList<Node> ChildNodes { get; }
```

### Property Value

这些节点。

## 示例

以下代码演示如何枚举根节点的子节点

```csharp
Scene scene = Scene.FromFile("test.fbx");
foreach(var child in scene.RootNode.ChildNodes)
{
    //执行你的业务
}
```

### 另请参见

* class [Node](../)
* namespace [Aspose.ThreeD](../../node/)
* assembly [Aspose.3D](../../../)



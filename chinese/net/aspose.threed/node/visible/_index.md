---
title: "Node.Visible"
second_title: "Aspose.3D for .NET API 参考"
description: "Node 属性。获取或设置以显示节点"
type: docs
weight: 130
url: /zh/net/aspose.threed/node/visible/
---
## Node.Visible property

获取或设置以显示节点

```csharp
public bool Visible { get; set; }
```

## 示例

以下代码展示了如何创建一个不可见的节点

```csharp
Scene scene = new Scene();
Node node = scene.RootNode.CreateChildNode("test-node", new Box());
node.Visible = false;
scene.Save("output.fbx");
```

### 另请参见

* class [Node](../)
* namespace [Aspose.ThreeD](../../node/)
* assembly [Aspose.3D](../../../)



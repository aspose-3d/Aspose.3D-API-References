---
title: "Node.AddChildNode"
second_title: "Aspose.3D for .NET API 参考"
description: "Node 方法。向此节点添加子节点"
type: docs
weight: 150
url: /zh/net/aspose.threed/node/addchildnode/
---
## Node.AddChildNode method

向此节点添加子节点

```csharp
public void AddChildNode(Node node)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 节点 | 节点 | 要附加的子节点 |

## 示例

以下代码展示了如何从场景中获取所有网格

```csharp
Scene scene = Scene.FromFile("input.fbx");
var newNode = new Node();
//手动添加新节点
scene.RootNode.AddChildNode(newNode);
```

### 另请参见

* class [Node](../)
* namespace [Aspose.ThreeD](../../node/)
* assembly [Aspose.3D](../../../)



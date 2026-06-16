---
title: "Node.Accept"
second_title: "Aspose.3D for .NET API 参考"
description: "Node 方法。遍历所有子节点（包括当前节点），并使用该节点调用访问者。访问者可以通过返回 false 来中断遍历"
type: docs
weight: 140
url: /zh/net/aspose.threed/node/accept/
---
## Node.Accept method

遍历所有子后代节点（包括当前节点），并将访问者调用于该节点。访问者可以通过返回 false 来中断遍历。

```csharp
public bool Accept(NodeVisitor visitor)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 访问者 | NodeVisitor | 访问节点的 Visitor 回调 |

### 返回值

true 表示访问者已中断遍历。

## 示例

以下代码展示了如何从场景中获取所有网格

```csharp
Scene scene = Scene.FromFile("input.fbx");
List<Mesh> meshes = new List<Mesh>();
scene.RootNode.Accept((node) =>
{
    if(node.Entity is Mesh)
        meshes.Add((Mesh)node.Entity);
    //继续搜索
    return true;
});
```

### 另请参见

* delegate [NodeVisitor](../../nodevisitor/)
* class [Node](../)
* namespace [Aspose.ThreeD](../../node/)
* assembly [Aspose.3D](../../../)



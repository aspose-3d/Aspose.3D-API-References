---
title: "Node.Entity"
second_title: "Aspose.3D for .NET API 参考"
description: "Node 属性。获取或设置附加到此节点的第一个实体，设置时会清除其他实体"
type: docs
weight: 50
url: /zh/net/aspose.threed/node/entity/
---
## Node.Entity property

获取或设置附加到此节点的第一个实体，如果设置，将清除其他实体。

```csharp
public Entity Entity { get; set; }
```

### Property Value

节点实体。

## 示例

以下代码展示了如何在根节点下创建新的子节点

```csharp
Scene scene = new Scene();
Node node = scene.RootNode.CreateChildNode("new node");
node.Entity = new Box();
scene.Save("output.fbx");
```

### 另请参见

* class [Entity](../../entity/)
* class [Node](../)
* namespace [Aspose.ThreeD](../../node/)
* assembly [Aspose.3D](../../../)



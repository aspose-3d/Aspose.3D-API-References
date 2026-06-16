---
title: "Node.GlobalTransform"
second_title: "Aspose.3D for .NET API 参考"
description: "Node 属性。获取全局变换"
type: docs
weight: 70
url: /zh/net/aspose.threed/node/globaltransform/
---
## Node.GlobalTransform property

获取全局变换。

```csharp
public GlobalTransform GlobalTransform { get; }
```

### Property Value

全局变换。

## 示例

以下代码展示了如何读取节点的全局变换

```csharp
Scene scene = new Scene();
var boxNode = scene.RootNode.CreateChildNode(new Box());
//将盒子放置在 (10, 0, 0) 处
boxNode.Transform.Translation = new Vector3(10, 0, 0);
var global = boxNode.GlobalTransform;
Console.WriteLine($"The box's position in world coordinate is {global.Translation}");
```

### 另请参见

* class [GlobalTransform](../../globaltransform/)
* class [Node](../)
* namespace [Aspose.ThreeD](../../node/)
* assembly [Aspose.3D](../../../)



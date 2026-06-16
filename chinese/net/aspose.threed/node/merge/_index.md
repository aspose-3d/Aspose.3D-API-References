---
title: "Node.Merge"
second_title: "Aspose.3D for .NET API 参考"
description: "Node 方法。分离节点下的所有内容并将其附加到当前节点"
type: docs
weight: 220
url: /zh/net/aspose.threed/node/merge/
---
## Node.Merge method

分离节点下的所有内容并将其附加到当前节点。

```csharp
public void Merge(Node node)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 节点 | 节点 |  |

## 示例

以下代码展示了如何将两个 3D 文件合并为一个文件

```csharp
Scene scene1 = Scene.FromFile("scene1.fbx");
Scene scene2 = Scene.FromFile("scene2.fbx");
scene1.RootNode.Merge(scene2.RootNode);
scene1.Save("merged.fbx");
```

### 另请参见

* class [Node](../)
* namespace [Aspose.ThreeD](../../node/)
* assembly [Aspose.3D](../../../)



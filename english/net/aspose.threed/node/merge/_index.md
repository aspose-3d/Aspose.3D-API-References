---
title: Node.Merge
second_title: Aspose.3D for .NET API Reference
description: Node method. Detach everything under the node and attach them to current node
type: docs
weight: 220
url: /net/aspose.threed/node/merge/
---
## Node.Merge method

Detach everything under the node and attach them to current node.

```csharp
public void Merge(Node node)
```

| Parameter | Type | Description |
| --- | --- | --- |
| node | Node |  |

## Examples

The following code shows how to merge two 3D files into one file

```csharp
Scene scene1 = Scene.FromFile("scene1.fbx");
Scene scene2 = Scene.FromFile("scene2.fbx");
scene1.RootNode.Merge(scene2.RootNode);
scene1.Save("merged.fbx");
```

### See Also

* class [Node](../)
* namespace [Aspose.ThreeD](../../node/)
* assembly [Aspose.3D](../../../)



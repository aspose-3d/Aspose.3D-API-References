---
title: Node.Excluded
second_title: Aspose.3D for .NET API Reference
description: Node property. Gets or sets whether to exclude this node and all child nodes/entities during exporting
type: docs
weight: 60
url: /net/aspose.threed/node/excluded/
---
## Node.Excluded property

Gets or sets whether to exclude this node and all child nodes/entities during exporting.

```csharp
public bool Excluded { get; set; }
```

## Examples

The following code shows how to exclude specified node from exporting

```csharp
Scene scene = new Scene();
scene.RootNode.CreateChildNode("excluded", new Box()).Excluded = true;
scene.RootNode.CreateChildNode("not excluded", new Box());
scene.Save("output.usdz");
```

### See Also

* class [Node](../)
* namespace [Aspose.ThreeD](../../node/)
* assembly [Aspose.3D](../../../)



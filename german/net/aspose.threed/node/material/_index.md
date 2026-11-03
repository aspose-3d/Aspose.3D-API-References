---
title: "Node.Material"
second_title: "Aspose.3D für .NET API-Referenz"
description: "Node-Eigenschaft. Liest oder schreibt das erste mit diesem Node verbundene Material; beim Setzen werden andere Materialien gelöscht."
type: docs
weight: 80
url: /de/net/aspose.threed/node/material/
---
## Node.Material property

Liefert oder setzt das erste Material, das diesem Node zugeordnet ist; beim Setzen werden andere Materialien gelöscht.

```csharp
public Material Material { get; set; }
```

### Property Value

Das Material.

## Beispiele

```csharp
Scene scene = new Scene();
var node = scene.RootNode.CreateChildNode(new Box());
node.Material = new LambertMaterial();
```

### Siehe auch

* class [Material](../../../aspose.threed.shading/material/)
* class [Node](../)
* namespace [Aspose.ThreeD](../../node/)
* assembly [Aspose.3D](../../../)



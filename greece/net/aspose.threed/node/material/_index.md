---
title: "Node.Material"
second_title: "Αναφορά API Aspose.3D για .NET"
description: "Ιδιότητα Node. Λαμβάνει ή ορίζει το πρώτο υλικό που σχετίζεται με αυτόν τον κόμβο· αν οριστεί, θα καθαρίσει τα άλλα υλικά"
type: docs
weight: 80
url: /el/net/aspose.threed/node/material/
---
## Node.Material property

Λαμβάνει ή ορίζει το πρώτο υλικό που σχετίζεται με αυτόν τον κόμβο· εάν οριστεί, θα καθαρίσει τα άλλα υλικά.

```csharp
public Material Material { get; set; }
```

### Property Value

Το υλικό.

## Παραδείγματα

```csharp
Scene scene = new Scene();
var node = scene.RootNode.CreateChildNode(new Box());
node.Material = new LambertMaterial();
```

### Δείτε επίσης

* class [Material](../../../aspose.threed.shading/material/)
* class [Node](../)
* namespace [Aspose.ThreeD](../../node/)
* assembly [Aspose.3D](../../../)



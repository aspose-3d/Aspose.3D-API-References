---
title: "Node.Material"
second_title: "Référence de l'API Aspose.3D pour .NET"
description: "Propriété Node. Obtient ou définit le premier matériau associé à ce node ; si défini, les autres matériaux seront supprimés"
type: docs
weight: 80
url: /fr/net/aspose.threed/node/material/
---
## Node.Material property

Obtient ou définit le premier matériau associé à ce nœud, si défini, les autres matériaux seront supprimés

```csharp
public Material Material { get; set; }
```

### Property Value

Le matériau.

## Exemples

```csharp
Scene scene = new Scene();
var node = scene.RootNode.CreateChildNode(new Box());
node.Material = new LambertMaterial();
```

### Voir aussi

* class [Material](../../../aspose.threed.shading/material/)
* class [Node](../)
* namespace [Aspose.ThreeD](../../node/)
* assembly [Aspose.3D](../../../)



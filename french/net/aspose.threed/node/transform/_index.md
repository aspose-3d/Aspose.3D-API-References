---
title: "Node.Transform"
second_title: "Référence de l'API Aspose.3D pour .NET"
description: "Propriété Node. Obtient la transformation locale."
type: docs
weight: 120
url: /fr/net/aspose.threed/node/transform/
---
## Node.Transform property

Obtient la transformation locale.

```csharp
public Transform Transform { get; }
```

### Property Value

La transformation.

## Exemples

Le code suivant montre comment modifier la transformation du nœud :

```csharp
Scene scene = new Scene();
var boxNode = scene.RootNode.CreateChildNode(new Box());
//placez la boîte à (10, 0, 0)
boxNode.Transform.Translation = new Vector3(10, 0, 0);
```

### Voir aussi

* class [Transform](../../transform/)
* class [Node](../)
* namespace [Aspose.ThreeD](../../node/)
* assembly [Aspose.3D](../../../)



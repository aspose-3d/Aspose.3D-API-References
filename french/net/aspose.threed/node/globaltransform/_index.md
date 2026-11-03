---
title: "Node.GlobalTransform"
second_title: "Référence de l'API Aspose.3D pour .NET"
description: "Propriété Node. Obtient la transformation globale"
type: docs
weight: 70
url: /fr/net/aspose.threed/node/globaltransform/
---
## Node.GlobalTransform property

Obtient la transformation globale.

```csharp
public GlobalTransform GlobalTransform { get; }
```

### Property Value

La transformation globale.

## Exemples

Le code suivant montre comment lire la transformation globale du nœud

```csharp
Scene scene = new Scene();
var boxNode = scene.RootNode.CreateChildNode(new Box());
//placez la boîte à (10, 0, 0)
boxNode.Transform.Translation = new Vector3(10, 0, 0);
var global = boxNode.GlobalTransform;
Console.WriteLine($"The box's position in world coordinate is {global.Translation}");
```

### Voir aussi

* class [GlobalTransform](../../globaltransform/)
* class [Node](../)
* namespace [Aspose.ThreeD](../../node/)
* assembly [Aspose.3D](../../../)



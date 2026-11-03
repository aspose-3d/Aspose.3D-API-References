---
title: "Node.ChildNodes"
second_title: "Référence de l'API Aspose.3D pour .NET"
description: "Propriété Node. Obtient les nœuds enfants"
type: docs
weight: 30
url: /fr/net/aspose.threed/node/childnodes/
---
## Node.ChildNodes property

Obtient les nœuds enfants.

```csharp
public IList<Node> ChildNodes { get; }
```

### Property Value

Les nœuds.

## Exemples

Le code suivant montre comment énumérer le nœud enfant du nœud racine

```csharp
Scene scene = Scene.FromFile("test.fbx");
foreach(var child in scene.RootNode.ChildNodes)
{
    //faites votre travail
}
```

### Voir aussi

* class [Node](../)
* namespace [Aspose.ThreeD](../../node/)
* assembly [Aspose.3D](../../../)



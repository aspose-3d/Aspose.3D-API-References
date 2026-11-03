---
title: "Node.Entity"
second_title: "Référence de l'API Aspose.3D pour .NET"
description: "Propriété Node. Obtient ou définit la première entité attachée à ce nœud ; si définie, les autres entités seront supprimées."
type: docs
weight: 50
url: /fr/net/aspose.threed/node/entity/
---
## Node.Entity property

Obtient ou définit la première entité attachée à ce nœud, si définie, les autres entités seront supprimées.

```csharp
public Entity Entity { get; set; }
```

### Property Value

L'entité du nœud.

## Exemples

Le code suivant montre comment créer un nouveau nœud enfant sous le nœud racine.

```csharp
Scene scene = new Scene();
Node node = scene.RootNode.CreateChildNode("new node");
node.Entity = new Box();
scene.Save("output.fbx");
```

### Voir aussi

* class [Entity](../../entity/)
* class [Node](../)
* namespace [Aspose.ThreeD](../../node/)
* assembly [Aspose.3D](../../../)



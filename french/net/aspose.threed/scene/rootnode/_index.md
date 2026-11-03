---
title: "Scene.RootNode"
second_title: "Référence de l'API Aspose.3D pour .NET"
description: "Propriété Scene. Obtient le node racine de la scène"
type: docs
weight: 90
url: /fr/net/aspose.threed/scene/rootnode/
---
## Scene.RootNode property

Récupère le nœud racine de la scène.

```csharp
public Node RootNode { get; }
```

### Property Value

Le nœud racine.

## Exemples

Le code suivant montre comment créer un nœud avec l'entité Box attachée au nœud racine.

```csharp
Scene scene = new Scene();
scene.RootNode.CreateChildNode(new Box());
scene.Save("box.stl");
```

### Voir aussi

* class [Node](../../node/)
* class [Scene](../)
* namespace [Aspose.ThreeD](../../scene/)
* assembly [Aspose.3D](../../../)



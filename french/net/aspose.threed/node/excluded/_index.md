---
title: "Node.Excluded"
second_title: "Référence de l'API Aspose.3D pour .NET"
description: "Propriété Node. Obtient ou définit si ce node doit être exclu ainsi que tous les nœuds enfants et entités lors de l'exportation"
type: docs
weight: 60
url: /fr/net/aspose.threed/node/excluded/
---
## Node.Excluded property

Obtient ou définit s'il faut exclure ce nœud et tous les nœuds/entités enfants lors de l'exportation.

```csharp
public bool Excluded { get; set; }
```

## Exemples

Le code suivant montre comment exclure le node spécifié lors de l'exportation

```csharp
Scene scene = new Scene();
scene.RootNode.CreateChildNode("excluded", new Box()).Excluded = true;
scene.RootNode.CreateChildNode("not excluded", new Box());
scene.Save("output.usdz");
```

### Voir aussi

* class [Node](../)
* namespace [Aspose.ThreeD](../../node/)
* assembly [Aspose.3D](../../../)



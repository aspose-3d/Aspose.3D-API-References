---
title: "Node.Accept"
second_title: "Référence de l'API Aspose.3D pour .NET"
description: "Méthode Node. Parcourt tous les nœuds descendants, y compris le nœud actuel, et appelle le visiteur avec le nœud. Le visiteur peut interrompre le parcours en renvoyant false"
type: docs
weight: 140
url: /fr/net/aspose.threed/node/accept/
---
## Node.Accept method

Parcourt tous les nœuds descendants (y compris le nœud actuel) et appelle le visiteur avec le nœud. Le visiteur peut interrompre le parcours en retournant false

```csharp
public bool Accept(NodeVisitor visitor)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| visiteur | NodeVisitor | Rappel du visiteur pour visiter le nœud |

### Valeur de retour

true signifie que le visiteur a interrompu le parcours.

## Exemples

Le code suivant montre comment obtenir tous les maillages d'une scène

```csharp
Scene scene = Scene.FromFile("input.fbx");
List<Mesh> meshes = new List<Mesh>();
scene.RootNode.Accept((node) =>
{
    if(node.Entity is Mesh)
        meshes.Add((Mesh)node.Entity);
    //continuer la recherche
    return true;
});
```

### Voir aussi

* delegate [NodeVisitor](../../nodevisitor/)
* class [Node](../)
* namespace [Aspose.ThreeD](../../node/)
* assembly [Aspose.3D](../../../)



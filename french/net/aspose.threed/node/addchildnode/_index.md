---
title: "Node.AddChildNode"
second_title: "Référence de l'API Aspose.3D pour .NET"
description: "Méthode Node. Ajoute un nœud enfant à ce nœud"
type: docs
weight: 150
url: /fr/net/aspose.threed/node/addchildnode/
---
## Node.AddChildNode method

Ajouter un nœud enfant à ce nœud

```csharp
public void AddChildNode(Node node)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| nœud | Nœud | Le nœud enfant à attacher |

## Exemples

Le code suivant montre comment obtenir tous les maillages d'une scène

```csharp
Scene scene = Scene.FromFile("input.fbx");
var newNode = new Node();
//ajoutez un nouveau nœud manuellement
scene.RootNode.AddChildNode(newNode);
```

### Voir aussi

* class [Node](../)
* namespace [Aspose.ThreeD](../../node/)
* assembly [Aspose.3D](../../../)



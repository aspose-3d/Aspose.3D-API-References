---
title: "Node.Merge"
second_title: "Référence de l'API Aspose.3D pour .NET"
description: "Méthode Node. Détache tout ce qui se trouve sous le node et les attache au node actuel"
type: docs
weight: 220
url: /fr/net/aspose.threed/node/merge/
---
## Node.Merge method

Détacher tout ce qui se trouve sous le nœud et les attacher au nœud actuel.

```csharp
public void Merge(Node node)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| nœud | Nœud |  |

## Exemples

Le code suivant montre comment fusionner deux fichiers 3D en un seul fichier

```csharp
Scene scene1 = Scene.FromFile("scene1.fbx");
Scene scene2 = Scene.FromFile("scene2.fbx");
scene1.RootNode.Merge(scene2.RootNode);
scene1.Save("merged.fbx");
```

### Voir aussi

* class [Node](../)
* namespace [Aspose.ThreeD](../../node/)
* assembly [Aspose.3D](../../../)



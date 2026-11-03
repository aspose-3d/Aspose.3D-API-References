---
title: "Node.Visible"
second_title: "Référence de l'API Aspose.3D pour .NET"
description: "Propriété Node. Obtient ou définit l'affichage du node"
type: docs
weight: 130
url: /fr/net/aspose.threed/node/visible/
---
## Node.Visible property

Obtient ou définit l'affichage du nœud

```csharp
public bool Visible { get; set; }
```

## Exemples

Le code suivant montre comment créer un node invisible

```csharp
Scene scene = new Scene();
Node node = scene.RootNode.CreateChildNode("test-node", new Box());
node.Visible = false;
scene.Save("output.fbx");
```

### Voir aussi

* class [Node](../)
* namespace [Aspose.ThreeD](../../node/)
* assembly [Aspose.3D](../../../)



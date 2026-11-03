---
title: "Node.ChildNodes"
second_title: "Aspose.3D für .NET API-Referenz"
description: "Node-Eigenschaft. Gibt die Kindknoten zurück"
type: docs
weight: 30
url: /de/net/aspose.threed/node/childnodes/
---
## Node.ChildNodes property

Liefert die untergeordneten Nodes.

```csharp
public IList<Node> ChildNodes { get; }
```

### Property Value

Die Knoten.

## Beispiele

Der folgende Code zeigt, wie man Kindknoten des Wurzelknotens enumeriert.

```csharp
Scene scene = Scene.FromFile("test.fbx");
foreach(var child in scene.RootNode.ChildNodes)
{
    //Erledige deine Aufgaben.
}
```

### Siehe auch

* class [Node](../)
* namespace [Aspose.ThreeD](../../node/)
* assembly [Aspose.3D](../../../)



---
title: "Node.Accept"
second_title: "Aspose.3D für .NET API-Referenz"
description: "Node-Methode. Durchläuft alle Nachfolgerknoten einschließlich des aktuellen Knotens und ruft den Besucher mit dem Knoten auf. Der Besucher kann den Durchlauf abbrechen, indem er false zurückgibt."
type: docs
weight: 140
url: /de/net/aspose.threed/node/accept/
---
## Node.Accept method

Durchläuft alle Nachfolger-Nodes (einschließlich des aktuellen Nodes) und ruft den Besucher mit dem Node auf. Der Besucher kann den Durchlauf abbrechen, indem er false zurückgibt.

```csharp
public bool Accept(NodeVisitor visitor)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Besucher | NodeVisitor | Besucher-Callback, um den Knoten zu besuchen |

### Rückgabewert

true bedeutet, dass der Besucher den Durchlauf unterbrochen hat.

## Beispiele

Der folgende Code zeigt, wie man alle Meshes aus einer Szene erhält.

```csharp
Scene scene = Scene.FromFile("input.fbx");
List<Mesh> meshes = new List<Mesh>();
scene.RootNode.Accept((node) =>
{
    if(node.Entity is Mesh)
        meshes.Add((Mesh)node.Entity);
    //Suche fortsetzen
    return true;
});
```

### Siehe auch

* delegate [NodeVisitor](../../nodevisitor/)
* class [Node](../)
* namespace [Aspose.ThreeD](../../node/)
* assembly [Aspose.3D](../../../)



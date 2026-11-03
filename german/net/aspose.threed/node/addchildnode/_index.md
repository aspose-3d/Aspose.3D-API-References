---
title: "Node.AddChildNode"
second_title: "Aspose.3D für .NET API-Referenz"
description: "Node-Methode. Fügt diesem Knoten einen Kindknoten hinzu."
type: docs
weight: 150
url: /de/net/aspose.threed/node/addchildnode/
---
## Node.AddChildNode method

Fügt diesem Node einen untergeordneten Node hinzu.

```csharp
public void AddChildNode(Node node)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Knoten | Knoten | Der anzuhängende Kindknoten |

## Beispiele

Der folgende Code zeigt, wie man alle Meshes aus einer Szene erhält.

```csharp
Scene scene = Scene.FromFile("input.fbx");
var newNode = new Node();
//einen neuen Knoten manuell hinzufügen
scene.RootNode.AddChildNode(newNode);
```

### Siehe auch

* class [Node](../)
* namespace [Aspose.ThreeD](../../node/)
* assembly [Aspose.3D](../../../)



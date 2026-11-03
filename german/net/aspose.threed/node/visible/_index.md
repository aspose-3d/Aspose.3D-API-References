---
title: "Node.Visible"
second_title: "Aspose.3D für .NET API-Referenz"
description: "Node-Eigenschaft. Liest oder schreibt, ob der Node angezeigt wird."
type: docs
weight: 130
url: /de/net/aspose.threed/node/visible/
---
## Node.Visible property

Liefert oder setzt die Sichtbarkeit des Nodes.

```csharp
public bool Visible { get; set; }
```

## Beispiele

Der folgende Code zeigt, wie man einen unsichtbaren Node erstellt.

```csharp
Scene scene = new Scene();
Node node = scene.RootNode.CreateChildNode("test-node", new Box());
node.Visible = false;
scene.Save("output.fbx");
```

### Siehe auch

* class [Node](../)
* namespace [Aspose.ThreeD](../../node/)
* assembly [Aspose.3D](../../../)



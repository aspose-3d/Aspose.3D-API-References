---
title: "Node.Excluded"
second_title: "Aspose.3D für .NET API-Referenz"
description: "Node-Eigenschaft. Liest oder schreibt, ob dieser Node und alle untergeordneten Nodes/Entitäten beim Export ausgeschlossen werden."
type: docs
weight: 60
url: /de/net/aspose.threed/node/excluded/
---
## Node.Excluded property

Liefert oder setzt, ob dieser Node und alle untergeordneten Nodes/Entitäten beim Export ausgeschlossen werden sollen.

```csharp
public bool Excluded { get; set; }
```

## Beispiele

Der folgende Code zeigt, wie man einen angegebenen Node vom Export ausschließt.

```csharp
Scene scene = new Scene();
scene.RootNode.CreateChildNode("excluded", new Box()).Excluded = true;
scene.RootNode.CreateChildNode("not excluded", new Box());
scene.Save("output.usdz");
```

### Siehe auch

* class [Node](../)
* namespace [Aspose.ThreeD](../../node/)
* assembly [Aspose.3D](../../../)



---
title: "Scene.RootNode"
second_title: "Aspose.3D für .NET API-Referenz"
description: "Scene-Eigenschaft. Gibt den RootNode der Szene zurück"
type: docs
weight: 90
url: /de/net/aspose.threed/scene/rootnode/
---
## Scene.RootNode property

Gibt den Root‑Knoten der Szene zurück.

```csharp
public Node RootNode { get; }
```

### Property Value

Der Root-Knoten.

## Beispiele

Der folgende Code zeigt, wie man einen Knoten mit einer Box-Entität erstellt, die am Root-Knoten angehängt ist.

```csharp
Scene scene = new Scene();
scene.RootNode.CreateChildNode(new Box());
scene.Save("box.stl");
```

### Siehe auch

* class [Node](../../node/)
* class [Scene](../)
* namespace [Aspose.ThreeD](../../scene/)
* assembly [Aspose.3D](../../../)



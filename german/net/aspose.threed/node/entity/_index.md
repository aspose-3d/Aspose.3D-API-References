---
title: "Node.Entity"
second_title: "Aspose.3D für .NET API-Referenz"
description: "Node-Eigenschaft. Gibt die erste an diesen Knoten angehängte Entität zurück oder setzt sie; beim Setzen werden andere Entitäten gelöscht."
type: docs
weight: 50
url: /de/net/aspose.threed/node/entity/
---
## Node.Entity property

Liefert oder setzt die erste an diesen Node angehängte Entität; beim Setzen werden andere Entitäten gelöscht.

```csharp
public Entity Entity { get; set; }
```

### Property Value

Die Knotenentität.

## Beispiele

Der folgende Code zeigt, wie man einen neuen Kindknoten unter dem Wurzelknoten erstellt.

```csharp
Scene scene = new Scene();
Node node = scene.RootNode.CreateChildNode("new node");
node.Entity = new Box();
scene.Save("output.fbx");
```

### Siehe auch

* class [Entity](../../entity/)
* class [Node](../)
* namespace [Aspose.ThreeD](../../node/)
* assembly [Aspose.3D](../../../)



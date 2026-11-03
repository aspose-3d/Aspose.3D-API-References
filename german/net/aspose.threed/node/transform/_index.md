---
title: "Node.Transform"
second_title: "Aspose.3D für .NET API-Referenz"
description: "Node-Eigenschaft. Gibt die lokale Transformation zurück."
type: docs
weight: 120
url: /de/net/aspose.threed/node/transform/
---
## Node.Transform property

Liefert die lokale Transformation.

```csharp
public Transform Transform { get; }
```

### Property Value

Die Transformation.

## Beispiele

Der folgende Code zeigt, wie man die Transformation des Knotens ändert:

```csharp
Scene scene = new Scene();
var boxNode = scene.RootNode.CreateChildNode(new Box());
//Platziere die Box bei (10, 0, 0)
boxNode.Transform.Translation = new Vector3(10, 0, 0);
```

### Siehe auch

* class [Transform](../../transform/)
* class [Node](../)
* namespace [Aspose.ThreeD](../../node/)
* assembly [Aspose.3D](../../../)



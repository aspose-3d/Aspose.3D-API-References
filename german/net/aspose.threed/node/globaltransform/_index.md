---
title: "Node.GlobalTransform"
second_title: "Aspose.3D für .NET API-Referenz"
description: "Node-Eigenschaft. Gibt die globale Transformation zurück"
type: docs
weight: 70
url: /de/net/aspose.threed/node/globaltransform/
---
## Node.GlobalTransform property

Liefert die globale Transformation.

```csharp
public GlobalTransform GlobalTransform { get; }
```

### Property Value

Die globale Transformation.

## Beispiele

Der folgende Code zeigt, wie man die globale Transformation eines Knotens liest

```csharp
Scene scene = new Scene();
var boxNode = scene.RootNode.CreateChildNode(new Box());
//Platziere die Box bei (10, 0, 0)
boxNode.Transform.Translation = new Vector3(10, 0, 0);
var global = boxNode.GlobalTransform;
Console.WriteLine($"The box's position in world coordinate is {global.Translation}");
```

### Siehe auch

* class [GlobalTransform](../../globaltransform/)
* class [Node](../)
* namespace [Aspose.ThreeD](../../node/)
* assembly [Aspose.3D](../../../)



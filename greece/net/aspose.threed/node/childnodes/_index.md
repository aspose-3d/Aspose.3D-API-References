---
title: "Node.ChildNodes"
second_title: "Αναφορά API Aspose.3D για .NET"
description: "Ιδιότητα Node. Λαμβάνει τους θυγατρικούς κόμβους"
type: docs
weight: 30
url: /el/net/aspose.threed/node/childnodes/
---
## Node.ChildNodes property

Λαμβάνει τους κόμβους-παιδιά.

```csharp
public IList<Node> ChildNodes { get; }
```

### Property Value

Οι κόμβοι.

## Παραδείγματα

Ο παρακάτω κώδικας δείχνει πώς να απαριθμήσετε τον θυγατρικό κόμβο του ριζικού κόμβου

```csharp
Scene scene = Scene.FromFile("test.fbx");
foreach(var child in scene.RootNode.ChildNodes)
{
    //κάντε τη δουλειά σας
}
```

### Δείτε επίσης

* class [Node](../)
* namespace [Aspose.ThreeD](../../node/)
* assembly [Aspose.3D](../../../)



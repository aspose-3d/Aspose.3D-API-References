---
title: "Scene.RootNode"
second_title: "Αναφορά API Aspose.3D για .NET"
description: "Ιδιότητα Scene. Λαμβάνει τον ριζικό κόμβο της σκηνής"
type: docs
weight: 90
url: /el/net/aspose.threed/scene/rootnode/
---
## Scene.RootNode property

Λαμβάνει τον ριζικό κόμβο της σκηνής.

```csharp
public Node RootNode { get; }
```

### Property Value

Ο ριζικός κόμβος.

## Παραδείγματα

Ο παρακάτω κώδικας δείχνει πώς να δημιουργήσετε έναν κόμβο με οντότητα Box προσαρτημένη στον ριζικό κόμβο.

```csharp
Scene scene = new Scene();
scene.RootNode.CreateChildNode(new Box());
scene.Save("box.stl");
```

### Δείτε επίσης

* class [Node](../../node/)
* class [Scene](../)
* namespace [Aspose.ThreeD](../../scene/)
* assembly [Aspose.3D](../../../)



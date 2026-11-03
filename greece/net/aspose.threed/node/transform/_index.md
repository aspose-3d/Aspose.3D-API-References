---
title: "Node.Transform"
second_title: "Αναφορά API Aspose.3D για .NET"
description: "Ιδιότητα Node. Λαμβάνει τον τοπικό μετασχηματισμό."
type: docs
weight: 120
url: /el/net/aspose.threed/node/transform/
---
## Node.Transform property

Λαμβάνει τον τοπικό μετασχηματισμό.

```csharp
public Transform Transform { get; }
```

### Property Value

Ο μετασχηματισμός.

## Παραδείγματα

Ο παρακάτω κώδικας δείχνει πώς να αλλάξετε τον μετασχηματισμό του κόμβου:

```csharp
Scene scene = new Scene();
var boxNode = scene.RootNode.CreateChildNode(new Box());
//Τοποθετήστε το κουτί στο (10, 0, 0)
boxNode.Transform.Translation = new Vector3(10, 0, 0);
```

### Δείτε επίσης

* class [Transform](../../transform/)
* class [Node](../)
* namespace [Aspose.ThreeD](../../node/)
* assembly [Aspose.3D](../../../)



---
title: "Node.GlobalTransform"
second_title: "Αναφορά API Aspose.3D για .NET"
description: "Ιδιότητα Node. Λαμβάνει τον παγκόσμιο μετασχηματισμό"
type: docs
weight: 70
url: /el/net/aspose.threed/node/globaltransform/
---
## Node.GlobalTransform property

Λαμβάνει τον παγκόσμιο μετασχηματισμό.

```csharp
public GlobalTransform GlobalTransform { get; }
```

### Property Value

Ο παγκόσμιος μετασχηματισμός.

## Παραδείγματα

Ο παρακάτω κώδικας δείχνει πώς να διαβάσετε τον παγκόσμιο μετασχηματισμό του κόμβου

```csharp
Scene scene = new Scene();
var boxNode = scene.RootNode.CreateChildNode(new Box());
//Τοποθετήστε το κουτί στο (10, 0, 0)
boxNode.Transform.Translation = new Vector3(10, 0, 0);
var global = boxNode.GlobalTransform;
Console.WriteLine($"The box's position in world coordinate is {global.Translation}");
```

### Δείτε επίσης

* class [GlobalTransform](../../globaltransform/)
* class [Node](../)
* namespace [Aspose.ThreeD](../../node/)
* assembly [Aspose.3D](../../../)



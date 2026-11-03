---
title: "Node.Entity"
second_title: "Αναφορά API Aspose.3D για .NET"
description: "Ιδιότητα Node. Λαμβάνει ή ορίζει την πρώτη οντότητα που είναι συνδεδεμένη σε αυτόν τον κόμβο· εάν ορίζεται, θα καθαρίσει τις άλλες οντότητες."
type: docs
weight: 50
url: /el/net/aspose.threed/node/entity/
---
## Node.Entity property

Λαμβάνει ή ορίζει την πρώτη οντότητα που είναι συνδεδεμένη με αυτόν τον κόμβο· εάν οριστεί, θα καθαρίσει τις άλλες οντότητες.

```csharp
public Entity Entity { get; set; }
```

### Property Value

Η οντότητα του κόμβου.

## Παραδείγματα

Ο παρακάτω κώδικας δείχνει πώς να δημιουργήσετε έναν νέο υποκόμβο κάτω από τον ριζικό κόμβο.

```csharp
Scene scene = new Scene();
Node node = scene.RootNode.CreateChildNode("new node");
node.Entity = new Box();
scene.Save("output.fbx");
```

### Δείτε επίσης

* class [Entity](../../entity/)
* class [Node](../)
* namespace [Aspose.ThreeD](../../node/)
* assembly [Aspose.3D](../../../)



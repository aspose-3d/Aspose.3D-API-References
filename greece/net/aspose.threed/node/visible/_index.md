---
title: "Node.Visible"
second_title: "Αναφορά API Aspose.3D για .NET"
description: "Ιδιότητα Node. Λαμβάνει ή ορίζει την εμφάνιση του κόμβου"
type: docs
weight: 130
url: /el/net/aspose.threed/node/visible/
---
## Node.Visible property

Λαμβάνει ή ορίζει για να εμφανίσει τον κόμβο

```csharp
public bool Visible { get; set; }
```

## Παραδείγματα

Ο παρακάτω κώδικας δείχνει πώς να δημιουργήσετε έναν αόρατο κόμβο

```csharp
Scene scene = new Scene();
Node node = scene.RootNode.CreateChildNode("test-node", new Box());
node.Visible = false;
scene.Save("output.fbx");
```

### Δείτε επίσης

* class [Node](../)
* namespace [Aspose.ThreeD](../../node/)
* assembly [Aspose.3D](../../../)



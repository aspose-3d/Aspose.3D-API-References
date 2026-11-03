---
title: "Node.Excluded"
second_title: "Αναφορά API Aspose.3D για .NET"
description: "Ιδιότητα Node. Λαμβάνει ή ορίζει αν θα αποκλειστεί αυτός ο κόμβος και όλοι οι υποκόμβοι/οντότητες κατά την εξαγωγή"
type: docs
weight: 60
url: /el/net/aspose.threed/node/excluded/
---
## Node.Excluded property

Λαμβάνει ή ορίζει εάν θα εξαλειφθεί αυτός ο κόμβος και όλοι οι κόμβοι/οντότητες-παιδιά κατά την εξαγωγή.

```csharp
public bool Excluded { get; set; }
```

## Παραδείγματα

Ο παρακάτω κώδικας δείχνει πώς να αποκλείσετε τον καθορισμένο κόμβο από την εξαγωγή

```csharp
Scene scene = new Scene();
scene.RootNode.CreateChildNode("excluded", new Box()).Excluded = true;
scene.RootNode.CreateChildNode("not excluded", new Box());
scene.Save("output.usdz");
```

### Δείτε επίσης

* class [Node](../)
* namespace [Aspose.ThreeD](../../node/)
* assembly [Aspose.3D](../../../)



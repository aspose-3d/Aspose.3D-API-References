---
title: "Node.AddChildNode"
second_title: "Αναφορά API Aspose.3D για .NET"
description: "Μέθοδος Node. Προσθέτει έναν υποκόμβο σε αυτόν τον κόμβο"
type: docs
weight: 150
url: /el/net/aspose.threed/node/addchildnode/
---
## Node.AddChildNode method

Προσθέτει έναν υποκόμβο σε αυτόν τον κόμβο

```csharp
public void AddChildNode(Node node)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| κόμβος | Κόμβος | Ο υποκόμβος που θα προσαρτηθεί |

## Παραδείγματα

Ο παρακάτω κώδικας δείχνει πώς να λάβετε όλα τα πλέγματα από μια σκηνή

```csharp
Scene scene = Scene.FromFile("input.fbx");
var newNode = new Node();
//προσθέστε έναν νέο κόμβο χειροκίνητα
scene.RootNode.AddChildNode(newNode);
```

### Δείτε επίσης

* class [Node](../)
* namespace [Aspose.ThreeD](../../node/)
* assembly [Aspose.3D](../../../)



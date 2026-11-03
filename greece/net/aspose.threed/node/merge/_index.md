---
title: "Node.Merge"
second_title: "Αναφορά API Aspose.3D για .NET"
description: "Μέθοδος Node. Αποσυνδέει όλα κάτω από τον κόμβο και τα συνδέει στον τρέχοντα κόμβο"
type: docs
weight: 220
url: /el/net/aspose.threed/node/merge/
---
## Node.Merge method

Αποσυνδέει όλα τα στοιχεία κάτω από τον κόμβο και τα συνδέει στον τρέχοντα κόμβο.

```csharp
public void Merge(Node node)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| κόμβος | Κόμβος |  |

## Παραδείγματα

Ο παρακάτω κώδικας δείχνει πώς να συγχωνεύσετε δύο αρχεία 3D σε ένα αρχείο

```csharp
Scene scene1 = Scene.FromFile("scene1.fbx");
Scene scene2 = Scene.FromFile("scene2.fbx");
scene1.RootNode.Merge(scene2.RootNode);
scene1.Save("merged.fbx");
```

### Δείτε επίσης

* class [Node](../)
* namespace [Aspose.ThreeD](../../node/)
* assembly [Aspose.3D](../../../)



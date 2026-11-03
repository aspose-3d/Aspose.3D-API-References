---
title: "Node.GetChild"
second_title: "Αναφορά API Aspose.3D για .NET"
description: "Μέθοδος Node. Λαμβάνει τον θυγατρικό κόμβο στο καθορισμένο δείκτη"
type: docs
weight: 200
url: /el/net/aspose.threed/node/getchild/
---
## GetChild(int) {#getchild}

Λαμβάνει τον υποκόμβο στο καθορισμένο δείκτη.

```csharp
public Node GetChild(int index)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| δείκτης | Int32 | Δείκτης. |

### Τιμή επιστροφής

Το παιδί.

## Παραδείγματα

Ο παρακάτω κώδικας δείχνει πώς να λάβετε έναν κόμβο παιδί σε συγκεκριμένο δείκτη.

```csharp
Scene scene = Scene.FromFile("input.fbx");
var node = scene.RootNode.GetChild(0);
Console.WriteLine($"The first node of the file is {node.Name}");
```

### Δείτε επίσης

* class [Node](../)
* namespace [Aspose.ThreeD](../../node/)
* assembly [Aspose.3D](../../../)

---

## GetChild(string) {#getchild_1}

Λαμβάνει τον υποκόμβο με το καθορισμένο όνομα

```csharp
public Node GetChild(string nodeName)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| nodeName | String | Το όνομα του παιδιού προς εύρεση. |

### Τιμή επιστροφής

Το παιδί.

## Παραδείγματα

Ο παρακάτω κώδικας δείχνει πώς να λάβετε έναν κόμβο παιδί με συγκεκριμένο όνομα

```csharp
Scene scene = Scene.FromFile("input.fbx");
var node = scene.RootNode.GetChild("box");
Console.WriteLine($"The box node's translation is {node.Transform.Translation}");
```

### Δείτε επίσης

* class [Node](../)
* namespace [Aspose.ThreeD](../../node/)
* assembly [Aspose.3D](../../../)



---
title: "Node.SelectObjects"
second_title: "Αναφορά API Aspose.3D για .NET"
description: "Μέθοδος Node. Επιλέγει πολλαπλά αντικείμενα κάτω από τον τρέχοντα κόμβο χρησιμοποιώντας σύνταξη ερωτήματος τύπου XPath."
type: docs
weight: 230
url: /el/net/aspose.threed/node/selectobjects/
---
## Node.SelectObjects method

Επιλέγει πολλαπλά αντικείμενα κάτω από τον τρέχοντα κόμβο χρησιμοποιώντας σύνταξη ερωτήματος παρόμοια με XPath.

```csharp
public List<object> SelectObjects(string path)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| path | String | Το ερώτημα τύπου XPath-like |

### Τιμή επιστροφής

Πολλά αντικείμενα ταιριάζουν με το ερώτημα τύπου XPath.

### Εξαιρέσεις

| εξαίρεση | συνθήκη |
| --- | --- |
| [ParseException](../../../aspose.threed.utilities/parseexception/) | Θα εκτοξευθεί η εξαίρεση ParseException εάν η διαδρομή περιέχει εσφαλμένο ερώτημα. |

## Παραδείγματα

Επιλέξτε έναν μοναδικό κόμβο χρησιμοποιώντας έκφραση τύπου XPath-like

```csharp
//Δημιουργήστε μια σκηνή για δοκιμή
Scene s = new Scene();
var a = s.RootNode.CreateChildNode("a");
a.CreateChildNode("a1");
a.CreateChildNode("a2");
s.RootNode.CreateChildNode("b");
var c = s.RootNode.CreateChildNode("c");
c.CreateChildNode("c1").AddEntity(new Camera("cam"));
c.CreateChildNode("c2").AddEntity(new Light("light"));
//Επιλέξτε αντικείμενα που έχουν τύπο Camera ή όνομα 'light', ανεξάρτητα από τη θέση τους.
var objects = s.RootNode.SelectObjects("//*[(@Type = 'Camera') or (@Name = 'light')]");
```

### Δείτε επίσης

* class [Node](../)
* namespace [Aspose.ThreeD](../../node/)
* assembly [Aspose.3D](../../../)



---
title: "Node.SelectSingleObject"
second_title: "Αναφορά API Aspose.3D για .NET"
description: "Μέθοδος Node. Επιλέξτε ένα μοναδικό αντικείμενο κάτω από τον τρέχοντα κόμβο χρησιμοποιώντας σύνταξη ερωτήματος τύπου XPathlike"
type: docs
weight: 240
url: /el/net/aspose.threed/node/selectsingleobject/
---
## Node.SelectSingleObject method

Επιλέγει ένα μόνο αντικείμενο κάτω από τον τρέχοντα κόμβο χρησιμοποιώντας σύνταξη ερωτήματος παρόμοια με XPath.

```csharp
public object SelectSingleObject(string path)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| path | String | Το ερώτημα τύπου XPath-like |

### Τιμή επιστροφής

Αντικείμενο που εντοπίστηκε από το ερώτημα τύπου XPath-like.

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
//Επιλέξτε ένα μοναδικό αντικείμενο κάμερας κάτω από τους κόμβους παιδί του κόμβου με όνομα 'c' κάτω από τον ριζικό κόμβο
var c1 = s.RootNode.SelectSingleObject("/c/*/<Camera>");
// Επιλέξτε τον κόμβο με όνομα 'a1' κάτω από τον ριζικό κόμβο, ακόμη και αν το 'a1' δεν είναι άμεσα παιδί του
var obj = s.RootNode.SelectSingleObject("a1");
//Επιλέξτε τον ίδιο τον κόμβο, καθώς το '/' επιλέγεται άμεσα στον ριζικό κόμβο, έτσι ο ριζικός κόμβος επιλέγεται.
obj = s.RootNode.SelectSingleObject("/");
```

### Δείτε επίσης

* class [Node](../)
* namespace [Aspose.ThreeD](../../node/)
* assembly [Aspose.3D](../../../)



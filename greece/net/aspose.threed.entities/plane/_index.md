---
title: "Κλάση Plane"
second_title: "Αναφορά API Aspose.3D για .NET"
description: "Κλάση Aspose.ThreeD.Entities.Plane. Παραμετροποιημένο επίπεδο"
type: docs
weight: 590
url: /el/net/aspose.threed.entities/plane/
---
## Plane class

Παραμετρικώς ορισμένο επίπεδο.

```csharp
public class Plane : Primitive
```

## Κατασκευαστές

| Όνομα | Περιγραφή |
| --- | --- |
| [Plane](plane/#constructor)() | Αρχικοποιεί μια νέα παρουσία του `Plane` με προεπιλεγμένο μέγεθος 1x1. |
| [Plane](plane/#constructor_1)(double, double) | Αρχικοποιεί μια νέα παρουσία του `Plane`. |
| [Plane](plane/#constructor_2)(string, double, double, int, int) | Αρχικοποιεί μια νέα παρουσία του `Plane`. |

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| [CastShadows](../../aspose.threed.entities/primitive/castshadows/) { get; set; } | Λαμβάνει ή ορίζει αν αυτή η γεωμετρία μπορεί να ρίξει σκιά |
| [Excluded](../../aspose.threed/entity/excluded/) { get; set; } | Λαμβάνει ή ορίζει αν αυτή η οντότητα θα εξαιρεθεί κατά την εξαγωγή. |
| [Length](../../aspose.threed.entities/plane/length/) { get; set; } | Λαμβάνει ή ορίζει το μήκος του επιπέδου. |
| [LengthSegments](../../aspose.threed.entities/plane/lengthsegments/) { get; set; } | Λαμβάνει ή ορίζει τα τμήματα μήκους. |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | Λαμβάνει ή ορίζει το όνομα. |
| [ParentNode](../../aspose.threed/entity/parentnode/) { get; set; } | Λαμβάνει ή ορίζει τον πρώτο γονικό κόμβο· εάν οριστεί ο πρώτος γονικός κόμβος, αυτή η οντότητα θα αποσυνδεθεί από άλλους γονικούς κόμβους. |
| [ParentNodes](../../aspose.threed/entity/parentnodes/) { get; } | Λαμβάνει όλους τους γονικούς κόμβους, μια οντότητα μπορεί να προσαρτηθεί σε πολλούς γονικούς κόμβους για δημιουργία γεωμετρίας μέσω αντιγραφών |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | Λαμβάνει τη συλλογή όλων των ιδιοτήτων. |
| [ReceiveShadows](../../aspose.threed.entities/primitive/receiveshadows/) { get; set; } | Λαμβάνει ή ορίζει αν αυτή η γεωμετρία μπορεί να λαμβάνει σκιά. |
| [Scene](../../aspose.threed/sceneobject/scene/) { get; } | Λαμβάνει τη σκηνή στην οποία ανήκει αυτό το αντικείμενο |
| [Up](../../aspose.threed.entities/plane/up/) { get; set; } | Λαμβάνει ή ορίζει το διάνυσμα άνω του επιπέδου, η προεπιλεγμένη τιμή είναι (0, 1, 0), αυτό επηρεάζει τη δημιουργία του επιπέδου |
| [Width](../../aspose.threed.entities/plane/width/) { get; set; } | Λαμβάνει ή ορίζει το πλάτος του επιπέδου. |
| [WidthSegments](../../aspose.threed.entities/plane/widthsegments/) { get; set; } | Λαμβάνει ή ορίζει τα τμήματα πλάτους. |

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| [FindProperty](../../aspose.threed/a3dobject/findproperty/)(string) | Βρίσκει την ιδιότητα. Μπορεί να είναι δυναμική ιδιότητα (Δημιουργείται από CreateDynamicProperty/SetProperty) ή εγγενής ιδιότητα (Αναγνωρίζεται με το όνομά της) |
| [GetBoundingBox](../../aspose.threed/entity/getboundingbox/)() | Λαμβάνει το πλαίσιο περιβάλλοντος της τρέχουσας οντότητας στο σύστημα συντεταγμένων του χώρου αντικειμένου της. |
| virtual [GetEntityRendererKey](../../aspose.threed/entity/getentityrendererkey/)() | Λαμβάνει το κλειδί του αποτυπωτή οντότητας που είναι καταχωρημένο στον renderer |
| [GetProperty](../../aspose.threed/a3dobject/getproperty/)(string) | Λάβετε την τιμή της καθορισμένης ιδιότητας |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(Property) | Αφαιρεί μια δυναμική ιδιότητα. |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(string) | Αφαιρέστε την καθορισμένη ιδιότητα που προσδιορίζεται με το όνομα |
| [SetProperty](../../aspose.threed/a3dobject/setproperty/)(string, object) | Ορίζει την τιμή της καθορισμένης ιδιότητας |
| override [ToMesh](../../aspose.threed.entities/plane/tomesh/)() | Μετατρέψτε το τρέχον αντικείμενο σε πλέγμα |

### Δείτε επίσης

* class [Primitive](../primitive/)
* namespace [Aspose.ThreeD.Entities](../../aspose.threed.entities/)
* assembly [Aspose.3D](../../)



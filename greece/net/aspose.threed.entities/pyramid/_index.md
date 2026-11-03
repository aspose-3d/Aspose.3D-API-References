---
title: "Κλάση Pyramid"
second_title: "Αναφορά API Aspose.3D για .NET"
description: "Aspose.ThreeD.Entities.Pyramid class. Παραμετρική πυραμίδα"
type: docs
weight: 650
url: /el/net/aspose.threed.entities/pyramid/
---
## Pyramid class

Παραμετρική πυραμίδα.

```csharp
public class Pyramid : Primitive
```

## Κατασκευαστές

| Όνομα | Περιγραφή |
| --- | --- |
| [Pyramid](pyramid/#constructor)() | Δημιουργήστε ένα νέο αντικείμενο πυραμίδας με προεπιλεγμένη περιοχή βάσης (10, 10) και προεπιλεγμένο ύψος (5) |
| [Pyramid](pyramid/#constructor_1)(double, double, double) | Δημιουργήστε ένα νέο αντικείμενο πυραμίδας με καθορισμένη περιοχή βάσης |
| [Pyramid](pyramid/#constructor_2)(double, double, double, double, double) | Δημιουργήστε ένα νέο αντικείμενο πυραμίδας με καθορισμένη περιοχή βάσης, περιοχή κορυφής και ύψος. |
| [Pyramid](pyramid/#constructor_3)(string, double, double, double, double, double) | Δημιουργήστε ένα νέο αντικείμενο πυραμίδας με καθορισμένη περιοχή βάσης, περιοχή κορυφής και ύψος. |

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| [BottomArea](../../aspose.threed.entities/pyramid/bottomarea/) { get; set; } | Επιφάνεια της κάτω κάπας |
| [BottomOffset](../../aspose.threed.entities/pyramid/bottomoffset/) { get; set; } | Μετατόπιση για τα κάτω κορυφαία σημεία |
| [CastShadows](../../aspose.threed.entities/primitive/castshadows/) { get; set; } | Λαμβάνει ή ορίζει αν αυτή η γεωμετρία μπορεί να ρίξει σκιά |
| [Excluded](../../aspose.threed/entity/excluded/) { get; set; } | Λαμβάνει ή ορίζει αν αυτή η οντότητα θα εξαιρεθεί κατά την εξαγωγή. |
| [Height](../../aspose.threed.entities/pyramid/height/) { get; set; } | Ύψος της πυραμίδας |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | Λαμβάνει ή ορίζει το όνομα. |
| [ParentNode](../../aspose.threed/entity/parentnode/) { get; set; } | Λαμβάνει ή ορίζει τον πρώτο γονικό κόμβο· εάν οριστεί ο πρώτος γονικός κόμβος, αυτή η οντότητα θα αποσυνδεθεί από άλλους γονικούς κόμβους. |
| [ParentNodes](../../aspose.threed/entity/parentnodes/) { get; } | Λαμβάνει όλους τους γονικούς κόμβους, μια οντότητα μπορεί να προσαρτηθεί σε πολλούς γονικούς κόμβους για δημιουργία γεωμετρίας μέσω αντιγραφών |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | Λαμβάνει τη συλλογή όλων των ιδιοτήτων. |
| [ReceiveShadows](../../aspose.threed.entities/primitive/receiveshadows/) { get; set; } | Λαμβάνει ή ορίζει αν αυτή η γεωμετρία μπορεί να λαμβάνει σκιά. |
| [Scene](../../aspose.threed/sceneobject/scene/) { get; } | Λαμβάνει τη σκηνή στην οποία ανήκει αυτό το αντικείμενο |
| [TopArea](../../aspose.threed.entities/pyramid/toparea/) { get; set; } | Επιφάνεια της πάνω κάπας |

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
| override [ToMesh](../../aspose.threed.entities/pyramid/tomesh/)() | Μετατρέψτε το τρέχον αντικείμενο σε πλέγμα |

### Δείτε επίσης

* class [Primitive](../primitive/)
* namespace [Aspose.ThreeD.Entities](../../aspose.threed.entities/)
* assembly [Aspose.3D](../../)



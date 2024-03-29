---
title: Pyramid
second_title: Aspose.3D για Αναφορά API .NET
description: Παραμετροποιημένη πυραμίδα.
type: docs
weight: 590
url: /el/net/aspose.threed.entities/pyramid/
---
## Pyramid class

Παραμετροποιημένη πυραμίδα.

```csharp
public class Pyramid : Primitive
```

## Κατασκευαστές

| Ονομα | Περιγραφή |
| --- | --- |
| [Pyramid](pyramid/#constructor)() | Κατασκευάστε μια νέα παρουσία πυραμίδας με προεπιλεγμένη κάτω περιοχή (10, 10) και προεπιλεγμένο ύψος (5) |
| [Pyramid](pyramid/#constructor_1)(double, double, double) | Κατασκευάστε μια νέα παρουσία πυραμίδας με καθορισμένη κάτω περιοχή |
| [Pyramid](pyramid/#constructor_2)(double, double, double, double, double) | Κατασκευάστε μια νέα παρουσία πυραμίδας με καθορισμένη περιοχή κάτω και πάνω περιοχή και ύψος. |
| [Pyramid](pyramid/#constructor_3)(string, double, double, double, double, double) | Κατασκευάστε μια νέα παρουσία πυραμίδας με καθορισμένη περιοχή κάτω και πάνω περιοχή και ύψος. |

## Ιδιότητες

| Ονομα | Περιγραφή |
| --- | --- |
| [BottomArea](../../aspose.threed.entities/pyramid/bottomarea/) { get; set; } | Περιοχή του κάτω καπακιού |
| [BottomOffset](../../aspose.threed.entities/pyramid/bottomoffset/) { get; set; } | Μετατόπιση για κάτω κορυφές |
| [CastShadows](../../aspose.threed.entities/primitive/castshadows/) { get; set; } | Λαμβάνει ή ορίζει εάν αυτή η γεωμετρία μπορεί να δημιουργήσει σκιά |
| [Excluded](../../aspose.threed/entity/excluded/) { get; set; } | Λαμβάνει ή ορίζει εάν θα εξαιρεθεί αυτή η οντότητα κατά την εξαγωγή. |
| [Height](../../aspose.threed.entities/pyramid/height/) { get; set; } | Ύψος της πυραμίδας |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | Παίρνει ή ορίζει το όνομα. |
| [ParentNode](../../aspose.threed/entity/parentnode/) { get; set; } | Λαμβάνει ή ορίζει τον πρώτο γονικό κόμβο, εάν οριστεί ο πρώτος γονικός κόμβος, αυτή η οντότητα θα αποσπαστεί από άλλους γονικούς κόμβους. |
| [ParentNodes](../../aspose.threed/entity/parentnodes/) { get; } | Λαμβάνει όλους τους γονικούς κόμβους, μια οντότητα μπορεί να προσαρτηθεί σε πολλούς γονικούς κόμβους για γεωμετρία instancing |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | Λαμβάνει τη συλλογή όλων των ιδιοτήτων. |
| [ReceiveShadows](../../aspose.threed.entities/primitive/receiveshadows/) { get; set; } | Λαμβάνει ή ορίζει εάν αυτή η γεωμετρία μπορεί να λάβει σκιά. |
| [Scene](../../aspose.threed/sceneobject/scene/) { get; } | Λαμβάνει τη σκηνή ότι αυτό το αντικείμενο ανήκει στο |
| [TopArea](../../aspose.threed.entities/pyramid/toparea/) { get; set; } | Περιοχή του άνω καπακιού |

## Μέθοδοι

| Ονομα | Περιγραφή |
| --- | --- |
| [FindProperty](../../aspose.threed/a3dobject/findproperty/)(string) | Βρίσκει την ιδιότητα. Μπορεί να είναι μια δυναμική ιδιότητα (Δημιουργήθηκε από CreateDynamicProperty/SetProperty) ή εγγενής ιδιότητα (Αναγνωρίζεται από το όνομά της) |
| [GetBoundingBox](../../aspose.threed/entity/getboundingbox/)() | Λαμβάνει το πλαίσιο οριοθέτησης της τρέχουσας οντότητας στο σύστημα συντεταγμένων του χώρου αντικειμένου. |
| virtual [GetEntityRendererKey](../../aspose.threed/entity/getentityrendererkey/)() | Παίρνει το κλειδί του προγράμματος απόδοσης οντοτήτων που είναι καταχωρημένο στο πρόγραμμα απόδοσης |
| [GetProperty](../../aspose.threed/a3dobject/getproperty/)(string) | Λάβετε την τιμή της καθορισμένης ιδιότητας |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(Property) | Καταργεί μια δυναμική ιδιότητα. |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(string) | Καταργήστε την καθορισμένη ιδιότητα που προσδιορίζεται με όνομα |
| [SetProperty](../../aspose.threed/a3dobject/setproperty/)(string, object) | Ορίζει την τιμή της καθορισμένης ιδιότητας |
| override [ToMesh](../../aspose.threed.entities/pyramid/tomesh/)() | Μετατροπή τρέχοντος αντικειμένου σε mesh |

### Δείτε επίσης

* class [Primitive](../primitive/)
* χώρος ονομάτων [Aspose.ThreeD.Entities](../../aspose.threed.entities/)
* συνέλευση [Aspose.3D](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.3D.dll -->

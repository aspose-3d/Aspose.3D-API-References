---
title: "Κλάση BooleanOperator"
second_title: "Αναφορά API Aspose.3D για .NET"
description: "Κλάση Aspose.ThreeD.Entities.BooleanOperator. Ο τελεστής Boolean σας επιτρέπει να εφαρμόσετε λογική πράξη σε δύο στιγμές IMeshConvertible."
type: docs
weight: 280
url: /el/net/aspose.threed.entities/booleanoperator/
---
## BooleanOperator class

Ο τελεστής Boolean σας επιτρέπει να εφαρμόσετε λογική πράξη σε δύο στιγμές [`IMeshConvertible`](../imeshconvertible/).

```csharp
public class BooleanOperator : Entity, IMeshConvertible
```

## Κατασκευαστές

| Όνομα | Περιγραφή |
| --- | --- |
| [BooleanOperator](booleanoperator/#constructor)() | Κατασκευαστής του `BooleanOperator` |
| [BooleanOperator](booleanoperator/#constructor_1)(BooleanOperation, A3DObject, A3DObject) | Δημιουργεί μια νέα παρουσία του `BooleanOperator` με δύο τελεστές. |

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| [Excluded](../../aspose.threed/entity/excluded/) { get; set; } | Λαμβάνει ή ορίζει αν αυτή η οντότητα θα εξαιρεθεί κατά την εξαγωγή. |
| [First](../../aspose.threed.entities/booleanoperator/first/) { get; set; } | Ο πρώτος τελεστής του Boolean. |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | Λαμβάνει ή ορίζει το όνομα. |
| [Operator](../../aspose.threed.entities/booleanoperator/operator/) { get; set; } | Ο τελεστής Boolean που χρησιμοποιείται στην πράξη για τη δημιουργία του τελικού πλέγματος. |
| [ParentNode](../../aspose.threed/entity/parentnode/) { get; set; } | Λαμβάνει ή ορίζει τον πρώτο γονικό κόμβο· εάν οριστεί ο πρώτος γονικός κόμβος, αυτή η οντότητα θα αποσυνδεθεί από άλλους γονικούς κόμβους. |
| [ParentNodes](../../aspose.threed/entity/parentnodes/) { get; } | Λαμβάνει όλους τους γονικούς κόμβους, μια οντότητα μπορεί να προσαρτηθεί σε πολλούς γονικούς κόμβους για δημιουργία γεωμετρίας μέσω αντιγραφών |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | Λαμβάνει τη συλλογή όλων των ιδιοτήτων. |
| [Scene](../../aspose.threed/sceneobject/scene/) { get; } | Λαμβάνει τη σκηνή στην οποία ανήκει αυτό το αντικείμενο |
| [Second](../../aspose.threed.entities/booleanoperator/second/) { get; set; } | Ο δεύτερος τελεστής του Boolean. |

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
| [ToMesh](../../aspose.threed.entities/booleanoperator/tomesh/)() | Εκτελέστε τη λογική πράξη σε δύο τελεστές |

### Δείτε επίσης

* class [Entity](../../aspose.threed/entity/)
* interface [IMeshConvertible](../imeshconvertible/)
* namespace [Aspose.ThreeD.Entities](../../aspose.threed.entities/)
* assembly [Aspose.3D](../../)



---
title: "Κλάση HalfSpace"
second_title: "Αναφορά API Aspose.3D για .NET"
description: "Κλάση Aspose.ThreeD.Entities.HalfSpace. Το HalfSpace αντιπροσωπεύει έναν άπειρο χώρο που χωρίζεται από ένα επίπεδο· αυτό μπορεί να χρησιμοποιηθεί με BooleanOperator."
type: docs
weight: 420
url: /el/net/aspose.threed.entities/halfspace/
---
## HalfSpace class

`HalfSpace` αντιπροσωπεύει έναν άπειρο χώρο που χωρίζεται από ένα επίπεδο, αυτό μπορεί να χρησιμοποιηθεί με [`BooleanOperator`](../booleanoperator/).

```csharp
public class HalfSpace : Entity
```

## Κατασκευαστές

| Όνομα | Περιγραφή |
| --- | --- |
| [HalfSpace](halfspace/#constructor)() | Δημιουργεί ένα νέο στιγμιότυπο του `HalfSpace` |
| [HalfSpace](halfspace/#constructor_1)(Vector3, Vector3) | Δημιουργεί ένα νέο στιγμιότυπο του `HalfSpace` με δεδομένο διάνυσμα κανονικής και θέση στο επίπεδο κοπής; |

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| [Excluded](../../aspose.threed/entity/excluded/) { get; set; } | Λαμβάνει ή ορίζει αν αυτή η οντότητα θα εξαιρεθεί κατά την εξαγωγή. |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | Λαμβάνει ή ορίζει το όνομα. |
| [Normal](../../aspose.threed.entities/halfspace/normal/) { get; set; } | Η κανονική του διαχωριστικού επιπέδου, το επίπεδο ορίζεται ως N * P + D = 0 όπου N είναι η Κανονική και P είναι οποιοδήποτε σημείο στο επίπεδο. |
| [ParentNode](../../aspose.threed/entity/parentnode/) { get; set; } | Λαμβάνει ή ορίζει τον πρώτο γονικό κόμβο· εάν οριστεί ο πρώτος γονικός κόμβος, αυτή η οντότητα θα αποσυνδεθεί από άλλους γονικούς κόμβους. |
| [ParentNodes](../../aspose.threed/entity/parentnodes/) { get; } | Λαμβάνει όλους τους γονικούς κόμβους, μια οντότητα μπορεί να προσαρτηθεί σε πολλούς γονικούς κόμβους για δημιουργία γεωμετρίας μέσω αντιγραφών |
| [Position](../../aspose.threed.entities/halfspace/position/) { get; set; } | Το οποιοδήποτε σημείο στο διαχωριστικό επίπεδο, το επίπεδο ορίζεται ως N * P + D = 0 όπου N είναι η Κανονική και P είναι οποιοδήποτε σημείο στο επίπεδο. |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | Λαμβάνει τη συλλογή όλων των ιδιοτήτων. |
| [Scene](../../aspose.threed/sceneobject/scene/) { get; } | Λαμβάνει τη σκηνή στην οποία ανήκει αυτό το αντικείμενο |

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

### Δείτε επίσης

* class [Entity](../../aspose.threed/entity/)
* namespace [Aspose.ThreeD.Entities](../../aspose.threed.entities/)
* assembly [Aspose.3D](../../)



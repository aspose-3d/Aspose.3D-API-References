---
title: "Κλάση TrimmedCurve"
second_title: "Αναφορά API Aspose.3D για .NET"
description: "Aspose.ThreeD.Entities.TrimmedCurve κλάση. Μια περιορισμένη καμπύλη που κόβει την βασική καμπύλη και στα δύο άκρα."
type: docs
weight: 810
url: /el/net/aspose.threed.entities/trimmedcurve/
---
## TrimmedCurve class

Μια περιορισμένη καμπύλη που περικόπτει την βασική καμπύλη και στα δύο άκρα.

```csharp
public class TrimmedCurve : Curve
```

## Κατασκευαστές

| Όνομα | Περιγραφή |
| --- | --- |
| [TrimmedCurve](trimmedcurve/)() | Κατασκευαστής του `TrimmedCurve` |

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| [BasisCurve](../../aspose.threed.entities/trimmedcurve/basiscurve/) { get; set; } | Η βασική καμπύλη που θα κοπεί. |
| [Color](../../aspose.threed.entities/curve/color/) { get; set; } | Λαμβάνει ή ορίζει το χρώμα της γραμμής, η προεπιλεγμένη τιμή είναι λευκό (1, 1, 1) |
| [Excluded](../../aspose.threed/entity/excluded/) { get; set; } | Λαμβάνει ή ορίζει αν αυτή η οντότητα θα εξαιρεθεί κατά την εξαγωγή. |
| [First](../../aspose.threed.entities/trimmedcurve/first/) { get; set; } | Το πρώτο σημείο τέλους για κοπή, μπορεί να είναι καρτεσιανό σημείο ή πραγματική παράμετρος. |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | Λαμβάνει ή ορίζει το όνομα. |
| [ParentNode](../../aspose.threed/entity/parentnode/) { get; set; } | Λαμβάνει ή ορίζει τον πρώτο γονικό κόμβο· εάν οριστεί ο πρώτος γονικός κόμβος, αυτή η οντότητα θα αποσυνδεθεί από άλλους γονικούς κόμβους. |
| [ParentNodes](../../aspose.threed/entity/parentnodes/) { get; } | Λαμβάνει όλους τους γονικούς κόμβους, μια οντότητα μπορεί να προσαρτηθεί σε πολλούς γονικούς κόμβους για δημιουργία γεωμετρίας μέσω αντιγραφών |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | Λαμβάνει τη συλλογή όλων των ιδιοτήτων. |
| [SameDirection](../../aspose.threed.entities/trimmedcurve/samedirection/) { get; set; } | Λαμβάνει ή ορίζει εάν το αποτέλεσμα της κοπής χρησιμοποιεί την ίδια κατεύθυνση της βασικής καμπύλης. |
| [Scene](../../aspose.threed/sceneobject/scene/) { get; } | Λαμβάνει τη σκηνή στην οποία ανήκει αυτό το αντικείμενο |
| [Second](../../aspose.threed.entities/trimmedcurve/second/) { get; set; } | Το δεύτερο σημείο τέλους για κοπή, μπορεί να είναι καρτεσιανό σημείο ή πραγματική παράμετρος. |

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| [FindProperty](../../aspose.threed/a3dobject/findproperty/)(string) | Βρίσκει την ιδιότητα. Μπορεί να είναι δυναμική ιδιότητα (Δημιουργείται από CreateDynamicProperty/SetProperty) ή εγγενής ιδιότητα (Αναγνωρίζεται με το όνομά της) |
| [GetBoundingBox](../../aspose.threed/entity/getboundingbox/)() | Λαμβάνει το πλαίσιο περιβάλλοντος της τρέχουσας οντότητας στο σύστημα συντεταγμένων του χώρου αντικειμένου της. |
| override [GetEntityRendererKey](../../aspose.threed.entities/curve/getentityrendererkey/)() | Λαμβάνει το κλειδί του αποτυπωτή οντότητας που είναι καταχωρημένο στον renderer |
| [GetProperty](../../aspose.threed/a3dobject/getproperty/)(string) | Λάβετε την τιμή της καθορισμένης ιδιότητας |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(Property) | Αφαιρεί μια δυναμική ιδιότητα. |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(string) | Αφαιρέστε την καθορισμένη ιδιότητα που προσδιορίζεται με το όνομα |
| [SetProperty](../../aspose.threed/a3dobject/setproperty/)(string, object) | Ορίζει την τιμή της καθορισμένης ιδιότητας |

### Δείτε επίσης

* class [Curve](../curve/)
* namespace [Aspose.ThreeD.Entities](../../aspose.threed.entities/)
* assembly [Aspose.3D](../../)



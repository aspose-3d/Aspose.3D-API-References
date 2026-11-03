---
title: "Κλάση TransformedCurve"
second_title: "Αναφορά API Aspose.3D για .NET"
description: "Aspose.ThreeD.Entities.TransformedCurve κλάση. Ένα TransformedCurve δίνει σε μια καμπύλη μια θέση χρησιμοποιώντας έναν πίνακα μετασχηματισμού. Αυτό επιτρέπει την εκτέλεση ενός μετασχηματισμού μέσα σε ένα TrimmedCurve ή CompositeCurve."
type: docs
weight: 780
url: /el/net/aspose.threed.entities/transformedcurve/
---
## TransformedCurve class

Ένα `TransformedCurve` δίνει σε μια καμπύλη μια θέση χρησιμοποιώντας έναν πίνακα μετασχηματισμού. Αυτό επιτρέπει την εκτέλεση ενός μετασχηματισμού μέσα σε ένα [`TrimmedCurve`](../trimmedcurve/) ή [`CompositeCurve`](../compositecurve/).

```csharp
public class TransformedCurve : Curve
```

## Κατασκευαστές

| Όνομα | Περιγραφή |
| --- | --- |
| [TransformedCurve](transformedcurve/#constructor)() | Ο κατασκευαστής του `TransformedCurve` |
| [TransformedCurve](transformedcurve/#constructor_1)(Curve, Matrix4) | Ο κατασκευαστής του `TransformedCurve` |

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| [BasisCurve](../../aspose.threed.entities/transformedcurve/basiscurve/) { get; set; } | Η βασική καμπύλη. |
| [Color](../../aspose.threed.entities/curve/color/) { get; set; } | Λαμβάνει ή ορίζει το χρώμα της γραμμής, η προεπιλεγμένη τιμή είναι λευκό (1, 1, 1) |
| [Excluded](../../aspose.threed/entity/excluded/) { get; set; } | Λαμβάνει ή ορίζει αν αυτή η οντότητα θα εξαιρεθεί κατά την εξαγωγή. |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | Λαμβάνει ή ορίζει το όνομα. |
| [ParentNode](../../aspose.threed/entity/parentnode/) { get; set; } | Λαμβάνει ή ορίζει τον πρώτο γονικό κόμβο· εάν οριστεί ο πρώτος γονικός κόμβος, αυτή η οντότητα θα αποσυνδεθεί από άλλους γονικούς κόμβους. |
| [ParentNodes](../../aspose.threed/entity/parentnodes/) { get; } | Λαμβάνει όλους τους γονικούς κόμβους, μια οντότητα μπορεί να προσαρτηθεί σε πολλούς γονικούς κόμβους για δημιουργία γεωμετρίας μέσω αντιγραφών |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | Λαμβάνει τη συλλογή όλων των ιδιοτήτων. |
| [Scene](../../aspose.threed/sceneobject/scene/) { get; } | Λαμβάνει τη σκηνή στην οποία ανήκει αυτό το αντικείμενο |
| [TransformMatrix](../../aspose.threed.entities/transformedcurve/transformmatrix/) { get; set; } | Ο πίνακας μετασχηματισμού. |

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



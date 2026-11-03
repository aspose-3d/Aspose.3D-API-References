---
title: "Κλάση ArbitraryProfile"
second_title: "Αναφορά API Aspose.3D για .NET"
description: "Aspose.ThreeD.Profiles.ArbitraryProfile κλάση. Αυτή η κλάση σας επιτρέπει να δημιουργήσετε ένα 2D προφίλ απευθείας από αυθαίρετη καμπύλη"
type: docs
weight: 1670
url: /el/net/aspose.threed.profiles/arbitraryprofile/
---
## ArbitraryProfile class

Αυτή η κλάση σας επιτρέπει να δημιουργήσετε ένα προφίλ 2D απευθείας από αυθαίρετη καμπύλη.

```csharp
public class ArbitraryProfile : Profile
```

## Κατασκευαστές

| Όνομα | Περιγραφή |
| --- | --- |
| [ArbitraryProfile](arbitraryprofile/#constructor)() | Κατασκευαστής του `ArbitraryProfile` |
| [ArbitraryProfile](arbitraryprofile/#constructor_1)(Curve) | Κατασκευαστής του `ArbitraryProfile` με αρχική καμπύλη. |

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| [Curve](../../aspose.threed.profiles/arbitraryprofile/curve/) { get; set; } | Η Καμπύλη που χρησιμοποιείται για τη δημιουργία του προφίλ |
| [Excluded](../../aspose.threed/entity/excluded/) { get; set; } | Λαμβάνει ή ορίζει αν αυτή η οντότητα θα εξαιρεθεί κατά την εξαγωγή. |
| [Holes](../../aspose.threed.profiles/arbitraryprofile/holes/) { get; } | Οι τρύπες του προφίλ, επίσης αναπαριστώνται ως καμπύλη |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | Λαμβάνει ή ορίζει το όνομα. |
| [ParentNode](../../aspose.threed/entity/parentnode/) { get; set; } | Λαμβάνει ή ορίζει τον πρώτο γονικό κόμβο· εάν οριστεί ο πρώτος γονικός κόμβος, αυτή η οντότητα θα αποσυνδεθεί από άλλους γονικούς κόμβους. |
| [ParentNodes](../../aspose.threed/entity/parentnodes/) { get; } | Λαμβάνει όλους τους γονικούς κόμβους, μια οντότητα μπορεί να προσαρτηθεί σε πολλούς γονικούς κόμβους για δημιουργία γεωμετρίας μέσω αντιγραφών |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | Λαμβάνει τη συλλογή όλων των ιδιοτήτων. |
| [Scene](../../aspose.threed/sceneobject/scene/) { get; } | Λαμβάνει τη σκηνή στην οποία ανήκει αυτό το αντικείμενο |

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| [FindProperty](../../aspose.threed/a3dobject/findproperty/)(string) | Βρίσκει την ιδιότητα. Μπορεί να είναι δυναμική ιδιότητα (Δημιουργείται από CreateDynamicProperty/SetProperty) ή εγγενής ιδιότητα (Αναγνωρίζεται με το όνομά της) |
| [GetBoundingBox](../../aspose.threed/entity/getboundingbox/)() | Λαμβάνει το πλαίσιο περιβάλλοντος της τρέχουσας οντότητας στο σύστημα συντεταγμένων του χώρου αντικειμένου της. |
| override [GetEntityRendererKey](../../aspose.threed.profiles/profile/getentityrendererkey/)() | Λαμβάνει το κλειδί του αποτυπωτή οντότητας που είναι καταχωρημένο στον renderer |
| [GetProperty](../../aspose.threed/a3dobject/getproperty/)(string) | Λάβετε την τιμή της καθορισμένης ιδιότητας |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(Property) | Αφαιρεί μια δυναμική ιδιότητα. |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(string) | Αφαιρέστε την καθορισμένη ιδιότητα που προσδιορίζεται με το όνομα |
| [SetProperty](../../aspose.threed/a3dobject/setproperty/)(string, object) | Ορίζει την τιμή της καθορισμένης ιδιότητας |

### Δείτε επίσης

* class [Profile](../profile/)
* namespace [Aspose.ThreeD.Profiles](../../aspose.threed.profiles/)
* assembly [Aspose.3D](../../)



---
title: "Κλάση TrapeziumShape"
second_title: "Αναφορά API Aspose.3D για .NET"
description: "Aspose.ThreeD.Profiles.TrapeziumShape κλάση. Συμβατό με IFC σχήμα Trapezium που ορίζεται από παραμέτρους"
type: docs
weight: 1830
url: /el/net/aspose.threed.profiles/trapeziumshape/
---
## TrapeziumShape class

Συμβατό με IFC σχήμα τραπεζίου ορισμένο από παραμέτρους.

```csharp
public class TrapeziumShape : ParameterizedProfile
```

## Κατασκευαστές

| Όνομα | Περιγραφή |
| --- | --- |
| [TrapeziumShape](trapeziumshape/)() | Κατασκευαστής του `TrapeziumShape` |

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| [BottomXDim](../../aspose.threed.profiles/trapeziumshape/bottomxdim/) { get; set; } | Λαμβάνει ή ορίζει το εύρος της κάτω γραμμής μετρημένο κατά τον άξονα x. |
| [Excluded](../../aspose.threed/entity/excluded/) { get; set; } | Λαμβάνει ή ορίζει αν αυτή η οντότητα θα εξαιρεθεί κατά την εξαγωγή. |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | Λαμβάνει ή ορίζει το όνομα. |
| [ParentNode](../../aspose.threed/entity/parentnode/) { get; set; } | Λαμβάνει ή ορίζει τον πρώτο γονικό κόμβο· εάν οριστεί ο πρώτος γονικός κόμβος, αυτή η οντότητα θα αποσυνδεθεί από άλλους γονικούς κόμβους. |
| [ParentNodes](../../aspose.threed/entity/parentnodes/) { get; } | Λαμβάνει όλους τους γονικούς κόμβους, μια οντότητα μπορεί να προσαρτηθεί σε πολλούς γονικούς κόμβους για δημιουργία γεωμετρίας μέσω αντιγραφών |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | Λαμβάνει τη συλλογή όλων των ιδιοτήτων. |
| [Scene](../../aspose.threed/sceneobject/scene/) { get; } | Λαμβάνει τη σκηνή στην οποία ανήκει αυτό το αντικείμενο |
| [TopXDim](../../aspose.threed.profiles/trapeziumshape/topxdim/) { get; set; } | Λαμβάνει ή ορίζει το εύρος της πάνω γραμμής μετρημένο κατά τον άξονα x. |
| [TopXOffset](../../aspose.threed.profiles/trapeziumshape/topxoffset/) { get; set; } | Λαμβάνει ή ορίζει τη μετατόπιση από την αρχή της πάνω γραμμής στην κάτω γραμμή. |
| [YDim](../../aspose.threed.profiles/trapeziumshape/ydim/) { get; set; } | Λαμβάνει ή ορίζει την απόσταση μεταξύ της πάνω και της κάτω γραμμής μετρημένη κατά τον άξονα y. |

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| [FindProperty](../../aspose.threed/a3dobject/findproperty/)(string) | Βρίσκει την ιδιότητα. Μπορεί να είναι δυναμική ιδιότητα (Δημιουργείται από CreateDynamicProperty/SetProperty) ή εγγενής ιδιότητα (Αναγνωρίζεται με το όνομά της) |
| [GetBoundingBox](../../aspose.threed/entity/getboundingbox/)() | Λαμβάνει το πλαίσιο περιβάλλοντος της τρέχουσας οντότητας στο σύστημα συντεταγμένων του χώρου αντικειμένου της. |
| override [GetEntityRendererKey](../../aspose.threed.profiles/profile/getentityrendererkey/)() | Λαμβάνει το κλειδί του αποτυπωτή οντότητας που είναι καταχωρημένο στον renderer |
| override [GetExtent](../../aspose.threed.profiles/trapeziumshape/getextent/)() | Λαμβάνει την έκταση στις διαστάσεις x και y. |
| [GetProperty](../../aspose.threed/a3dobject/getproperty/)(string) | Λάβετε την τιμή της καθορισμένης ιδιότητας |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(Property) | Αφαιρεί μια δυναμική ιδιότητα. |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(string) | Αφαιρέστε την καθορισμένη ιδιότητα που προσδιορίζεται με το όνομα |
| [SetProperty](../../aspose.threed/a3dobject/setproperty/)(string, object) | Ορίζει την τιμή της καθορισμένης ιδιότητας |

### Δείτε επίσης

* class [ParameterizedProfile](../parameterizedprofile/)
* namespace [Aspose.ThreeD.Profiles](../../aspose.threed.profiles/)
* assembly [Aspose.3D](../../)



---
title: "Κλάση TShape"
second_title: "Αναφορά API Aspose.3D για .NET"
description: "Κλάση Aspose.ThreeD.Profiles.TShape. Συμβατό με IFC σχήμα T που ορίζεται από παραμέτρους."
type: docs
weight: 1810
url: /el/net/aspose.threed.profiles/tshape/
---
## TShape class

Συμβατό με IFC σχήμα T ορισμένο από παραμέτρους.

```csharp
public class TShape : ParameterizedProfile
```

## Κατασκευαστές

| Όνομα | Περιγραφή |
| --- | --- |
| [TShape](tshape/)() | Κατασκευαστής του `TShape` |

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| [Depth](../../aspose.threed.profiles/tshape/depth/) { get; set; } | Λαμβάνει ή ορίζει το μήκος του πλέγματος. |
| [Excluded](../../aspose.threed/entity/excluded/) { get; set; } | Λαμβάνει ή ορίζει αν αυτή η οντότητα θα εξαιρεθεί κατά την εξαγωγή. |
| [FilletRadius](../../aspose.threed.profiles/tshape/filletradius/) { get; set; } | Λαμβάνει ή ορίζει την ακτίνα στρογγυλοποίησης μεταξύ πλέγματος και πλάτης. |
| [FlangeEdgeRadius](../../aspose.threed.profiles/tshape/flangeedgeradius/) { get; set; } | Λαμβάνει ή ορίζει την ακτίνα της άκρης της πλάτης. |
| [FlangeThickness](../../aspose.threed.profiles/tshape/flangethickness/) { get; set; } | Λαμβάνει ή ορίζει το πάχος τοιχώματος της πλάτης. |
| [FlangeWidth](../../aspose.threed.profiles/tshape/flangewidth/) { get; set; } | Λαμβάνει ή ορίζει το μήκος της πλάτης. |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | Λαμβάνει ή ορίζει το όνομα. |
| [ParentNode](../../aspose.threed/entity/parentnode/) { get; set; } | Λαμβάνει ή ορίζει τον πρώτο γονικό κόμβο· εάν οριστεί ο πρώτος γονικός κόμβος, αυτή η οντότητα θα αποσυνδεθεί από άλλους γονικούς κόμβους. |
| [ParentNodes](../../aspose.threed/entity/parentnodes/) { get; } | Λαμβάνει όλους τους γονικούς κόμβους, μια οντότητα μπορεί να προσαρτηθεί σε πολλούς γονικούς κόμβους για δημιουργία γεωμετρίας μέσω αντιγραφών |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | Λαμβάνει τη συλλογή όλων των ιδιοτήτων. |
| [Scene](../../aspose.threed/sceneobject/scene/) { get; } | Λαμβάνει τη σκηνή στην οποία ανήκει αυτό το αντικείμενο |
| [WebEdgeRadius](../../aspose.threed.profiles/tshape/webedgeradius/) { get; set; } | Λαμβάνει ή ορίζει την ακτίνα της άκρης του πλέγματος. |
| [WebThickness](../../aspose.threed.profiles/tshape/webthickness/) { get; set; } | Λαμβάνει ή ορίζει το πάχος τοιχώματος του πλέγματος. |

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| [FindProperty](../../aspose.threed/a3dobject/findproperty/)(string) | Βρίσκει την ιδιότητα. Μπορεί να είναι δυναμική ιδιότητα (Δημιουργείται από CreateDynamicProperty/SetProperty) ή εγγενής ιδιότητα (Αναγνωρίζεται με το όνομά της) |
| [GetBoundingBox](../../aspose.threed/entity/getboundingbox/)() | Λαμβάνει το πλαίσιο περιβάλλοντος της τρέχουσας οντότητας στο σύστημα συντεταγμένων του χώρου αντικειμένου της. |
| override [GetEntityRendererKey](../../aspose.threed.profiles/profile/getentityrendererkey/)() | Λαμβάνει το κλειδί του αποτυπωτή οντότητας που είναι καταχωρημένο στον renderer |
| override [GetExtent](../../aspose.threed.profiles/tshape/getextent/)() | Λαμβάνει την έκταση στις διαστάσεις x και y. |
| [GetProperty](../../aspose.threed/a3dobject/getproperty/)(string) | Λάβετε την τιμή της καθορισμένης ιδιότητας |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(Property) | Αφαιρεί μια δυναμική ιδιότητα. |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(string) | Αφαιρέστε την καθορισμένη ιδιότητα που προσδιορίζεται με το όνομα |
| [SetProperty](../../aspose.threed/a3dobject/setproperty/)(string, object) | Ορίζει την τιμή της καθορισμένης ιδιότητας |

### Δείτε επίσης

* class [ParameterizedProfile](../parameterizedprofile/)
* namespace [Aspose.ThreeD.Profiles](../../aspose.threed.profiles/)
* assembly [Aspose.3D](../../)



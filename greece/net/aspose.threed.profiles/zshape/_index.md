---
title: "Κλάση ZShape"
second_title: "Αναφορά API Aspose.3D για .NET"
description: "Aspose.ThreeD.Profiles.ZShape κλάση. Συμβατό με IFC προφίλ Zshape ορισμένο από παραμέτρους"
type: docs
weight: 1850
url: /el/net/aspose.threed.profiles/zshape/
---
## ZShape class

Συμβατό με IFC προφίλ σχήματος Z ορισμένο από παραμέτρους.

```csharp
public class ZShape : ParameterizedProfile
```

## Κατασκευαστές

| Όνομα | Περιγραφή |
| --- | --- |
| [ZShape](zshape/)() | Κατασκευαστής του `ZShape` |

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| [Depth](../../aspose.threed.profiles/zshape/depth/) { get; set; } | Λαμβάνει ή ορίζει το μήκος του web. |
| [EdgeRadius](../../aspose.threed.profiles/zshape/edgeradius/) { get; set; } | Λαμβάνει ή ορίζει την ακτίνα της άκρης του flange. |
| [Excluded](../../aspose.threed/entity/excluded/) { get; set; } | Λαμβάνει ή ορίζει αν αυτή η οντότητα θα εξαιρεθεί κατά την εξαγωγή. |
| [FilletRadius](../../aspose.threed.profiles/zshape/filletradius/) { get; set; } | Λαμβάνει ή ορίζει την ακτίνα του fillet μεταξύ flange και web. |
| [FlangeThickness](../../aspose.threed.profiles/zshape/flangethickness/) { get; set; } | Λαμβάνει ή ορίζει το πάχος του flange. |
| [FlangeWidth](../../aspose.threed.profiles/zshape/flangewidth/) { get; set; } | Λαμβάνει ή ορίζει το μήκος του flange. |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | Λαμβάνει ή ορίζει το όνομα. |
| [ParentNode](../../aspose.threed/entity/parentnode/) { get; set; } | Λαμβάνει ή ορίζει τον πρώτο γονικό κόμβο· εάν οριστεί ο πρώτος γονικός κόμβος, αυτή η οντότητα θα αποσυνδεθεί από άλλους γονικούς κόμβους. |
| [ParentNodes](../../aspose.threed/entity/parentnodes/) { get; } | Λαμβάνει όλους τους γονικούς κόμβους, μια οντότητα μπορεί να προσαρτηθεί σε πολλούς γονικούς κόμβους για δημιουργία γεωμετρίας μέσω αντιγραφών |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | Λαμβάνει τη συλλογή όλων των ιδιοτήτων. |
| [Scene](../../aspose.threed/sceneobject/scene/) { get; } | Λαμβάνει τη σκηνή στην οποία ανήκει αυτό το αντικείμενο |
| [WebThickness](../../aspose.threed.profiles/zshape/webthickness/) { get; set; } | Λαμβάνει ή ορίζει το πάχος του τοίχου. |

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| [FindProperty](../../aspose.threed/a3dobject/findproperty/)(string) | Βρίσκει την ιδιότητα. Μπορεί να είναι δυναμική ιδιότητα (Δημιουργείται από CreateDynamicProperty/SetProperty) ή εγγενής ιδιότητα (Αναγνωρίζεται με το όνομά της) |
| [GetBoundingBox](../../aspose.threed/entity/getboundingbox/)() | Λαμβάνει το πλαίσιο περιβάλλοντος της τρέχουσας οντότητας στο σύστημα συντεταγμένων του χώρου αντικειμένου της. |
| override [GetEntityRendererKey](../../aspose.threed.profiles/profile/getentityrendererkey/)() | Λαμβάνει το κλειδί του αποτυπωτή οντότητας που είναι καταχωρημένο στον renderer |
| override [GetExtent](../../aspose.threed.profiles/zshape/getextent/)() | Λαμβάνει την έκταση στις διαστάσεις x και y. |
| [GetProperty](../../aspose.threed/a3dobject/getproperty/)(string) | Λάβετε την τιμή της καθορισμένης ιδιότητας |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(Property) | Αφαιρεί μια δυναμική ιδιότητα. |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(string) | Αφαιρέστε την καθορισμένη ιδιότητα που προσδιορίζεται με το όνομα |
| [SetProperty](../../aspose.threed/a3dobject/setproperty/)(string, object) | Ορίζει την τιμή της καθορισμένης ιδιότητας |

### Δείτε επίσης

* class [ParameterizedProfile](../parameterizedprofile/)
* namespace [Aspose.ThreeD.Profiles](../../aspose.threed.profiles/)
* assembly [Aspose.3D](../../)



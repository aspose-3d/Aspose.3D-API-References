---
title: "Κλάση HShape"
second_title: "Αναφορά API Aspose.3D για .NET"
description: "Aspose.ThreeD.Profiles.HShape κλάση. Το HShape παρέχει τις καθοριστικές παραμέτρους ενός σχήματος H ή I"
type: docs
weight: 1730
url: /el/net/aspose.threed.profiles/hshape/
---
## HShape class

Το `HShape` παρέχει τις καθοριστικές παραμέτρους ενός σχήματος 'H' ή 'I'.

```csharp
public class HShape : ParameterizedProfile
```

## Κατασκευαστές

| Όνομα | Περιγραφή |
| --- | --- |
| [HShape](hshape/)() | Κατασκευαστής του `HShape` |

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| [BottomFlangeEdgeRadius](../../aspose.threed.profiles/hshape/bottomflangeedgeradius/) { get; set; } | Λαμβάνει ή ορίζει την ακτίνα των άνω άκρων του κάτω φλάντζου. |
| [BottomFlangeFilletRadius](../../aspose.threed.profiles/hshape/bottomflangefilletradius/) { get; set; } | Λαμβάνει ή ορίζει την ακτίνα του στρογγυλοποίησης μεταξύ του web και της κάτω πλευράς. |
| [BottomFlangeThickness](../../aspose.threed.profiles/hshape/bottomflangethickness/) { get; set; } | Λαμβάνει ή ορίζει το πάχος της πλευράς του σχήματος H. |
| [BottomFlangeWidth](../../aspose.threed.profiles/hshape/bottomflangewidth/) { get; set; } | Λαμβάνει ή ορίζει το εύρος του πλάτους. |
| [Excluded](../../aspose.threed/entity/excluded/) { get; set; } | Λαμβάνει ή ορίζει αν αυτή η οντότητα θα εξαιρεθεί κατά την εξαγωγή. |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | Λαμβάνει ή ορίζει το όνομα. |
| [OverallDepth](../../aspose.threed.profiles/hshape/overalldepth/) { get; set; } | Λαμβάνει ή ορίζει το εύρος του βάθους. |
| [ParentNode](../../aspose.threed/entity/parentnode/) { get; set; } | Λαμβάνει ή ορίζει τον πρώτο γονικό κόμβο· εάν οριστεί ο πρώτος γονικός κόμβος, αυτή η οντότητα θα αποσυνδεθεί από άλλους γονικούς κόμβους. |
| [ParentNodes](../../aspose.threed/entity/parentnodes/) { get; } | Λαμβάνει όλους τους γονικούς κόμβους, μια οντότητα μπορεί να προσαρτηθεί σε πολλούς γονικούς κόμβους για δημιουργία γεωμετρίας μέσω αντιγραφών |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | Λαμβάνει τη συλλογή όλων των ιδιοτήτων. |
| [Scene](../../aspose.threed/sceneobject/scene/) { get; } | Λαμβάνει τη σκηνή στην οποία ανήκει αυτό το αντικείμενο |
| [TopFlangeEdgeRadius](../../aspose.threed.profiles/hshape/topflangeedgeradius/) { get; set; } | Λαμβάνει ή ορίζει την ακτίνα των κατώτερων άκρων της άνω πλευράς. |
| [TopFlangeFilletRadius](../../aspose.threed.profiles/hshape/topflangefilletradius/) { get; set; } | Λαμβάνει ή ορίζει την ακτίνα του στρογγυλοποίησης μεταξύ του web και της άνω πλευράς. |
| [TopFlangeThickness](../../aspose.threed.profiles/hshape/topflangethickness/) { get; set; } | Λαμβάνει ή ορίζει το πάχος της άνω πλευράς. |
| [TopFlangeWidth](../../aspose.threed.profiles/hshape/topflangewidth/) { get; set; } | Λαμβάνει ή ορίζει το πλάτος της άνω πλευράς. |
| [WebThickness](../../aspose.threed.profiles/hshape/webthickness/) { get; set; } | Λαμβάνει ή ορίζει το πάχος του web του σχήματος H. |

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| [FindProperty](../../aspose.threed/a3dobject/findproperty/)(string) | Βρίσκει την ιδιότητα. Μπορεί να είναι δυναμική ιδιότητα (Δημιουργείται από CreateDynamicProperty/SetProperty) ή εγγενής ιδιότητα (Αναγνωρίζεται με το όνομά της) |
| [GetBoundingBox](../../aspose.threed/entity/getboundingbox/)() | Λαμβάνει το πλαίσιο περιβάλλοντος της τρέχουσας οντότητας στο σύστημα συντεταγμένων του χώρου αντικειμένου της. |
| override [GetEntityRendererKey](../../aspose.threed.profiles/profile/getentityrendererkey/)() | Λαμβάνει το κλειδί του αποτυπωτή οντότητας που είναι καταχωρημένο στον renderer |
| override [GetExtent](../../aspose.threed.profiles/hshape/getextent/)() | Λαμβάνει την έκταση στις διαστάσεις x και y. |
| [GetProperty](../../aspose.threed/a3dobject/getproperty/)(string) | Λάβετε την τιμή της καθορισμένης ιδιότητας |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(Property) | Αφαιρεί μια δυναμική ιδιότητα. |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(string) | Αφαιρέστε την καθορισμένη ιδιότητα που προσδιορίζεται με το όνομα |
| [SetProperty](../../aspose.threed/a3dobject/setproperty/)(string, object) | Ορίζει την τιμή της καθορισμένης ιδιότητας |

### Δείτε επίσης

* class [ParameterizedProfile](../parameterizedprofile/)
* namespace [Aspose.ThreeD.Profiles](../../aspose.threed.profiles/)
* assembly [Aspose.3D](../../)



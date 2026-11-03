---
title: "Κλάση HollowRectangleShape"
second_title: "Αναφορά API Aspose.3D για .NET"
description: "Κλάση Aspose.ThreeD.Profiles.HollowRectangleShape. Συμβατό με IFC κενό ορθογώνιο σχήμα με στρογγυλεμένες εσωτερικές/εξωτερικές γωνίες."
type: docs
weight: 1750
url: /el/net/aspose.threed.profiles/hollowrectangleshape/
---
## HollowRectangleShape class

Σχήμα κενού ορθογωνίου συμβατό με IFC με στρογγυλεμένες εσωτερικές/εξωτερικές γωνίες.

```csharp
public class HollowRectangleShape : RectangleShape
```

## Κατασκευαστές

| Όνομα | Περιγραφή |
| --- | --- |
| [HollowRectangleShape](hollowrectangleshape/)() | Ο προεπιλεγμένος κατασκευαστής. |

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| [Excluded](../../aspose.threed/entity/excluded/) { get; set; } | Λαμβάνει ή ορίζει αν αυτή η οντότητα θα εξαιρεθεί κατά την εξαγωγή. |
| [InnerFilletRadius](../../aspose.threed.profiles/hollowrectangleshape/innerfilletradius/) { get; set; } | Η εσωτερική ακτίνα στρογγυλοποίησης του εσωτερικού ορθογωνίου. |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | Λαμβάνει ή ορίζει το όνομα. |
| [ParentNode](../../aspose.threed/entity/parentnode/) { get; set; } | Λαμβάνει ή ορίζει τον πρώτο γονικό κόμβο· εάν οριστεί ο πρώτος γονικός κόμβος, αυτή η οντότητα θα αποσυνδεθεί από άλλους γονικούς κόμβους. |
| [ParentNodes](../../aspose.threed/entity/parentnodes/) { get; } | Λαμβάνει όλους τους γονικούς κόμβους, μια οντότητα μπορεί να προσαρτηθεί σε πολλούς γονικούς κόμβους για δημιουργία γεωμετρίας μέσω αντιγραφών |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | Λαμβάνει τη συλλογή όλων των ιδιοτήτων. |
| [RoundingRadius](../../aspose.threed.profiles/rectangleshape/roundingradius/) { get; set; } | Λαμβάνει ή ορίζει την ακτίνα των κυκλικών τόξων των τεσσάρων γωνιών, μετρημένη σε μοίρες. Η προεπιλεγμένη τιμή είναι 0,0. |
| [Scene](../../aspose.threed/sceneobject/scene/) { get; } | Λαμβάνει τη σκηνή στην οποία ανήκει αυτό το αντικείμενο |
| [WallThickness](../../aspose.threed.profiles/hollowrectangleshape/wallthickness/) { get; set; } | Το πάχος μεταξύ του περιγράμματος του ορθογωνίου και της εσωτερικής τρύπας. |
| [XDim](../../aspose.threed.profiles/rectangleshape/xdim/) { get; set; } | Λαμβάνει ή ορίζει το μέγεθος του ορθογωνίου στην κατεύθυνση του άξονα x. Η προεπιλεγμένη τιμή είναι 2,0. |
| [YDim](../../aspose.threed.profiles/rectangleshape/ydim/) { get; set; } | Λαμβάνει ή ορίζει το μέγεθος του ορθογωνίου στην κατεύθυνση του άξονα y. Η προεπιλεγμένη τιμή είναι 2,0. |

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| [FindProperty](../../aspose.threed/a3dobject/findproperty/)(string) | Βρίσκει την ιδιότητα. Μπορεί να είναι δυναμική ιδιότητα (Δημιουργείται από CreateDynamicProperty/SetProperty) ή εγγενής ιδιότητα (Αναγνωρίζεται με το όνομά της) |
| [GetBoundingBox](../../aspose.threed/entity/getboundingbox/)() | Λαμβάνει το πλαίσιο περιβάλλοντος της τρέχουσας οντότητας στο σύστημα συντεταγμένων του χώρου αντικειμένου της. |
| override [GetEntityRendererKey](../../aspose.threed.profiles/profile/getentityrendererkey/)() | Λαμβάνει το κλειδί του αποτυπωτή οντότητας που είναι καταχωρημένο στον renderer |
| override [GetExtent](../../aspose.threed.profiles/rectangleshape/getextent/)() | Λαμβάνει την έκταση στις διαστάσεις x και y. |
| [GetProperty](../../aspose.threed/a3dobject/getproperty/)(string) | Λάβετε την τιμή της καθορισμένης ιδιότητας |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(Property) | Αφαιρεί μια δυναμική ιδιότητα. |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(string) | Αφαιρέστε την καθορισμένη ιδιότητα που προσδιορίζεται με το όνομα |
| [SetProperty](../../aspose.threed/a3dobject/setproperty/)(string, object) | Ορίζει την τιμή της καθορισμένης ιδιότητας |

### Δείτε επίσης

* class [RectangleShape](../rectangleshape/)
* namespace [Aspose.ThreeD.Profiles](../../aspose.threed.profiles/)
* assembly [Aspose.3D](../../)



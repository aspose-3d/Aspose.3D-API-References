---
title: "Κλάση RectangularTorus"
second_title: "Αναφορά API Aspose.3D για .NET"
description: "Κλάση Aspose.ThreeD.Entities.RectangularTorus. Παραμετρικός ορθογώνιος δακτύλιος"
type: docs
weight: 660
url: /el/net/aspose.threed.entities/rectangulartorus/
---
## RectangularTorus class

Παραμετρικός ορθογώνιος δακτύλιος.

```csharp
public class RectangularTorus : Primitive
```

## Κατασκευαστές

| Όνομα | Περιγραφή |
| --- | --- |
| [RectangularTorus](rectangulartorus/#constructor)() | Κατασκευαστής του `RectangularTorus` |
| [RectangularTorus](rectangulartorus/#constructor_1)(string) | Κατασκευαστής του `RectangularTorus` |

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| [AngleStart](../../aspose.threed.entities/rectangulartorus/anglestart/) { get; set; } | Η αρχική γωνία του τόξου, μετρημένη σε ακτίνια. Η προεπιλεγμένη τιμή είναι 0 |
| [Arc](../../aspose.threed.entities/rectangulartorus/arc/) { get; set; } | Η συνολική γωνία του τόξου, μετρημένη σε ακτίνια. Η προεπιλεγμένη τιμή είναι PI |
| [CastShadows](../../aspose.threed.entities/primitive/castshadows/) { get; set; } | Λαμβάνει ή ορίζει αν αυτή η γεωμετρία μπορεί να ρίξει σκιά |
| [Excluded](../../aspose.threed/entity/excluded/) { get; set; } | Λαμβάνει ή ορίζει αν αυτή η οντότητα θα εξαιρεθεί κατά την εξαγωγή. |
| [Height](../../aspose.threed.entities/rectangulartorus/height/) { get; set; } | Το ύψος του ορθογώνιου δακτυλίου. Η προεπιλεγμένη τιμή είναι 20 |
| [InnerRadius](../../aspose.threed.entities/rectangulartorus/innerradius/) { get; set; } | Η εσωτερική ακτίνα του ορθογώνιου δακτυλίου. Η προεπιλεγμένη τιμή είναι 17 |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | Λαμβάνει ή ορίζει το όνομα. |
| [OuterRadius](../../aspose.threed.entities/rectangulartorus/outerradius/) { get; set; } | Η εξωτερική ακτίνα του ορθογώνιου δακτυλίου. Η προεπιλεγμένη τιμή είναι 20 |
| [ParentNode](../../aspose.threed/entity/parentnode/) { get; set; } | Λαμβάνει ή ορίζει τον πρώτο γονικό κόμβο· εάν οριστεί ο πρώτος γονικός κόμβος, αυτή η οντότητα θα αποσυνδεθεί από άλλους γονικούς κόμβους. |
| [ParentNodes](../../aspose.threed/entity/parentnodes/) { get; } | Λαμβάνει όλους τους γονικούς κόμβους, μια οντότητα μπορεί να προσαρτηθεί σε πολλούς γονικούς κόμβους για δημιουργία γεωμετρίας μέσω αντιγραφών |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | Λαμβάνει τη συλλογή όλων των ιδιοτήτων. |
| [RadialSegments](../../aspose.threed.entities/rectangulartorus/radialsegments/) { get; set; } | Τα ακτινικά τμήματα, η προεπιλεγμένη τιμή είναι 10 |
| [ReceiveShadows](../../aspose.threed.entities/primitive/receiveshadows/) { get; set; } | Λαμβάνει ή ορίζει αν αυτή η γεωμετρία μπορεί να λαμβάνει σκιά. |
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
| override [ToMesh](../../aspose.threed.entities/rectangulartorus/tomesh/)() | Μετατρέψτε αυτό το πρωτότυπο σε [`Mesh`](../mesh/) |

### Δείτε επίσης

* class [Primitive](../primitive/)
* namespace [Aspose.ThreeD.Entities](../../aspose.threed.entities/)
* assembly [Aspose.3D](../../)



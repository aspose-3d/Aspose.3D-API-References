---
title: "Κλάση Sphere"
second_title: "Αναφορά API Aspose.3D για .NET"
description: "Κλάση Aspose.ThreeD.Entities.Sphere. Παραμετρική σφαίρα"
type: docs
weight: 730
url: /el/net/aspose.threed.entities/sphere/
---
## Sphere class

Παραμετροποιημένη σφαίρα.

```csharp
public class Sphere : Primitive
```

## Κατασκευαστές

| Όνομα | Περιγραφή |
| --- | --- |
| [Sphere](sphere/#constructor)() | Αρχικοποιεί ένα νέο αντικείμενο της `Sphere` με προεπιλεγμένη ακτίνα 1. |
| [Sphere](sphere/#constructor_1)(double) | Αρχικοποιεί ένα νέο αντικείμενο της κλάσης `Sphere` με καθορισμένη ακτίνα. |
| [Sphere](sphere/#constructor_2)(double, int, int) | Αρχικοποιεί ένα νέο αντικείμενο της κλάσης `Sphere` με καθορισμένη ακτίνα, τμήματα πλάτους και τμήματα ύψους. |
| [Sphere](sphere/#constructor_3)(string, double, int, int, double, double, double, double) | Αρχικοποιεί ένα νέο αντικείμενο της κλάσης `Sphere`. |

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| [CastShadows](../../aspose.threed.entities/primitive/castshadows/) { get; set; } | Λαμβάνει ή ορίζει αν αυτή η γεωμετρία μπορεί να ρίξει σκιά |
| [Excluded](../../aspose.threed/entity/excluded/) { get; set; } | Λαμβάνει ή ορίζει αν αυτή η οντότητα θα εξαιρεθεί κατά την εξαγωγή. |
| [HeightSegments](../../aspose.threed.entities/sphere/heightsegments/) { get; set; } | Λαμβάνει ή ορίζει τα τμήματα ύψους. |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | Λαμβάνει ή ορίζει το όνομα. |
| [ParentNode](../../aspose.threed/entity/parentnode/) { get; set; } | Λαμβάνει ή ορίζει τον πρώτο γονικό κόμβο· εάν οριστεί ο πρώτος γονικός κόμβος, αυτή η οντότητα θα αποσυνδεθεί από άλλους γονικούς κόμβους. |
| [ParentNodes](../../aspose.threed/entity/parentnodes/) { get; } | Λαμβάνει όλους τους γονικούς κόμβους, μια οντότητα μπορεί να προσαρτηθεί σε πολλούς γονικούς κόμβους για δημιουργία γεωμετρίας μέσω αντιγραφών |
| [PhiLength](../../aspose.threed.entities/sphere/philength/) { get; set; } | Λαμβάνει ή ορίζει το μήκος του phi. |
| [PhiStart](../../aspose.threed.entities/sphere/phistart/) { get; set; } | Λαμβάνει ή ορίζει την έναρξη του phi. |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | Λαμβάνει τη συλλογή όλων των ιδιοτήτων. |
| [Radius](../../aspose.threed.entities/sphere/radius/) { get; set; } | Λαμβάνει ή ορίζει την ακτίνα της σφαίρας. |
| [ReceiveShadows](../../aspose.threed.entities/primitive/receiveshadows/) { get; set; } | Λαμβάνει ή ορίζει αν αυτή η γεωμετρία μπορεί να λαμβάνει σκιά. |
| [Scene](../../aspose.threed/sceneobject/scene/) { get; } | Λαμβάνει τη σκηνή στην οποία ανήκει αυτό το αντικείμενο |
| [ThetaLength](../../aspose.threed.entities/sphere/thetalength/) { get; set; } | Λαμβάνει ή ορίζει το μήκος του theta. |
| [ThetaStart](../../aspose.threed.entities/sphere/thetastart/) { get; set; } | Λαμβάνει ή ορίζει την έναρξη του theta. |
| [WidthSegments](../../aspose.threed.entities/sphere/widthsegments/) { get; set; } | Λαμβάνει ή ορίζει τα τμήματα πλάτους. |

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
| override [ToMesh](../../aspose.threed.entities/sphere/tomesh/)() | Μετατρέψτε το τρέχον αντικείμενο σε πλέγμα |

### Δείτε επίσης

* class [Primitive](../primitive/)
* namespace [Aspose.ThreeD.Entities](../../aspose.threed.entities/)
* assembly [Aspose.3D](../../)



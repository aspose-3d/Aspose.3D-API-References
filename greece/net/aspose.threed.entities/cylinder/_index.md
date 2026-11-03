---
title: "Κλάση Cylinder"
second_title: "Αναφορά API Aspose.3D για .NET"
description: "Κλάση Aspose.ThreeD.Entities.Cylinder. Παραμετρικός κύλινδρος. Μπορεί επίσης να χρησιμοποιηθεί για την αναπαράσταση του κώνου όταν μία από τις τιμές radiusTop/radiusBottom είναι μηδέν."
type: docs
weight: 360
url: /el/net/aspose.threed.entities/cylinder/
---
## Cylinder class

Παραμετρικός Κύλινδρος. Μπορεί επίσης να χρησιμοποιηθεί για την αναπαράσταση του κώνου όταν ένα από τα radiusTop/radiusBottom είναι μηδέν.

```csharp
public class Cylinder : Primitive
```

## Κατασκευαστές

| Όνομα | Περιγραφή |
| --- | --- |
| [Cylinder](cylinder/#constructor)() | Αρχικοποιεί μια νέα παρουσία της κλάσης `Cylinder`. |
| [Cylinder](cylinder/#constructor_1)(double, double) | Αρχικοποιεί μια νέα παρουσία της κλάσης `Cylinder`. |
| [Cylinder](cylinder/#constructor_2)(double, double, double) | Αρχικοποιεί μια νέα παρουσία της κλάσης `Cylinder`. |
| [Cylinder](cylinder/#constructor_3)(double, double, double, int, int, bool) | Αρχικοποιεί μια νέα παρουσία της κλάσης `Cylinder`. |
| [Cylinder](cylinder/#constructor_4)(string, double, double, double, int, int, bool, double, double) | Αρχικοποιεί μια νέα παρουσία της κλάσης `Cylinder`. |

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| [CastShadows](../../aspose.threed.entities/primitive/castshadows/) { get; set; } | Λαμβάνει ή ορίζει αν αυτή η γεωμετρία μπορεί να ρίξει σκιά |
| [Excluded](../../aspose.threed/entity/excluded/) { get; set; } | Λαμβάνει ή ορίζει αν αυτή η οντότητα θα εξαιρεθεί κατά την εξαγωγή. |
| [GenerateFanCylinder](../../aspose.threed.entities/cylinder/generatefancylinder/) { get; set; } | Λαμβάνει ή ορίζει αν θα δημιουργηθεί κύλινδρος τύπου fan όταν το ThetaLength είναι μικρότερο από 2*PI· διαφορετικά το μοντέλο δεν θα κοπεί. |
| [Height](../../aspose.threed.entities/cylinder/height/) { get; set; } | Λαμβάνει ή ορίζει το ύψος του κυλίνδρου. |
| [HeightSegments](../../aspose.threed.entities/cylinder/heightsegments/) { get; set; } | Λαμβάνει ή ορίζει τα τμήματα ύψους. |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | Λαμβάνει ή ορίζει το όνομα. |
| [OffsetBottom](../../aspose.threed.entities/cylinder/offsetbottom/) { get; set; } | Λαμβάνει ή ορίζει τη μετατόπιση μετασχηματισμού των κορυφών της κάτω πλευράς. |
| [OffsetTop](../../aspose.threed.entities/cylinder/offsettop/) { get; set; } | Λαμβάνει ή ορίζει τη μετατόπιση μετασχηματισμού των κορυφών της άνω πλευράς. |
| [OpenEnded](../../aspose.threed.entities/cylinder/openended/) { get; set; } | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν αυτό το `Cylinder` είναι ανοιχτό στο άκρο. Η προεπιλεγμένη τιμή είναι false. |
| [ParentNode](../../aspose.threed/entity/parentnode/) { get; set; } | Λαμβάνει ή ορίζει τον πρώτο γονικό κόμβο· εάν οριστεί ο πρώτος γονικός κόμβος, αυτή η οντότητα θα αποσυνδεθεί από άλλους γονικούς κόμβους. |
| [ParentNodes](../../aspose.threed/entity/parentnodes/) { get; } | Λαμβάνει όλους τους γονικούς κόμβους, μια οντότητα μπορεί να προσαρτηθεί σε πολλούς γονικούς κόμβους για δημιουργία γεωμετρίας μέσω αντιγραφών |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | Λαμβάνει τη συλλογή όλων των ιδιοτήτων. |
| [RadialSegments](../../aspose.threed.entities/cylinder/radialsegments/) { get; set; } | Λαμβάνει ή ορίζει τα ακτινικά τμήματα. |
| [RadiusBottom](../../aspose.threed.entities/cylinder/radiusbottom/) { get; set; } | Λαμβάνει ή ορίζει την ακτίνα του κάτω καπάκιου του κυλίνδρου. |
| [RadiusTop](../../aspose.threed.entities/cylinder/radiustop/) { get; set; } | Λαμβάνει ή ορίζει την ακτίνα του πάνω καπάκιου του κυλίνδρου. |
| [ReceiveShadows](../../aspose.threed.entities/primitive/receiveshadows/) { get; set; } | Λαμβάνει ή ορίζει αν αυτή η γεωμετρία μπορεί να λαμβάνει σκιά. |
| [Scene](../../aspose.threed/sceneobject/scene/) { get; } | Λαμβάνει τη σκηνή στην οποία ανήκει αυτό το αντικείμενο |
| [ShearBottom](../../aspose.threed.entities/cylinder/shearbottom/) { get; set; } | Λαμβάνει ή ορίζει τη μετασχηματιστική παραμόρφωση της κάτω πλευράς, το διάνυσμα αποθηκεύει την τιμή παραμόρφωσης (x-άξονας, z-άξονας) που μετράται σε ακτίνια, η προεπιλεγμένη τιμή είναι (0, 0). |
| [ShearTop](../../aspose.threed.entities/cylinder/sheartop/) { get; set; } | Λαμβάνει ή ορίζει τη μετασχηματιστική παραμόρφωση της πάνω πλευράς, το διάνυσμα αποθηκεύει την τιμή παραμόρφωσης (x-άξονας, z-άξονας) που μετράται σε ακτίνια, η προεπιλεγμένη τιμή είναι (0, 0). |
| [ThetaLength](../../aspose.threed.entities/cylinder/thetalength/) { get; set; } | Λαμβάνει ή ορίζει το μήκος του θ. Η προεπιλεγμένη τιμή είναι 2π. |
| [ThetaStart](../../aspose.threed.entities/cylinder/thetastart/) { get; set; } | Λαμβάνει ή ορίζει την αρχή του θ. Η προεπιλεγμένη τιμή είναι 0. |

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
| override [ToMesh](../../aspose.threed.entities/cylinder/tomesh/)() | Μετατρέψτε το τρέχον αντικείμενο σε πλέγμα |

### Δείτε επίσης

* class [Primitive](../primitive/)
* namespace [Aspose.ThreeD.Entities](../../aspose.threed.entities/)
* assembly [Aspose.3D](../../)



---
title: "Κλάση RevolvedAreaSolid"
second_title: "Αναφορά API Aspose.3D για .NET"
description: "Η κλάση Aspose.ThreeD.Entities.RevolvedAreaSolid. Αυτή η κλάση αντιπροσωπεύει ένα στερεό μοντέλο περιστρέφοντας μια διατομή που παρέχεται από ένα προφίλ γύρω από έναν άξονα."
type: docs
weight: 680
url: /el/net/aspose.threed.entities/revolvedareasolid/
---
## RevolvedAreaSolid class

Αυτή η κλάση αντιπροσωπεύει ένα στερεό μοντέλο περιστρέφοντας μια διατομή που παρέχεται από ένα προφίλ γύρω από έναν άξονα.

```csharp
public class RevolvedAreaSolid : Entity, IMeshConvertible
```

## Κατασκευαστές

| Όνομα | Περιγραφή |
| --- | --- |
| [RevolvedAreaSolid](revolvedareasolid/)() | Ο προεπιλεγμένος κατασκευαστής. |

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| [AngleEnd](../../aspose.threed.entities/revolvedareasolid/angleend/) { get; set; } | Λαμβάνει ή ορίζει τη γωνία λήξης της διαδικασίας περιστροφής, μετρημένη σε ακτίνια, η προεπιλεγμένη τιμή είναι το π. |
| [AngleStart](../../aspose.threed.entities/revolvedareasolid/anglestart/) { get; set; } | Λαμβάνει ή ορίζει τη γωνία εκκίνησης της διαδικασίας περιστροφής, μετρημένη σε ακτίνια, η προεπιλεγμένη τιμή είναι 0. |
| [Axis](../../aspose.threed.entities/revolvedareasolid/axis/) { get; set; } | Λαμβάνει ή ορίζει την κατεύθυνση του άξονα, η προεπιλεγμένη τιμή είναι (0, 1, 0). |
| [Excluded](../../aspose.threed/entity/excluded/) { get; set; } | Λαμβάνει ή ορίζει αν αυτή η οντότητα θα εξαιρεθεί κατά την εξαγωγή. |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | Λαμβάνει ή ορίζει το όνομα. |
| [Origin](../../aspose.threed.entities/revolvedareasolid/origin/) { get; set; } | Λαμβάνει ή ορίζει το σημείο προέλευσης της περιστροφής, η προεπιλεγμένη τιμή είναι (0, 0, 0). |
| [ParentNode](../../aspose.threed/entity/parentnode/) { get; set; } | Λαμβάνει ή ορίζει τον πρώτο γονικό κόμβο· εάν οριστεί ο πρώτος γονικός κόμβος, αυτή η οντότητα θα αποσυνδεθεί από άλλους γονικούς κόμβους. |
| [ParentNodes](../../aspose.threed/entity/parentnodes/) { get; } | Λαμβάνει όλους τους γονικούς κόμβους, μια οντότητα μπορεί να προσαρτηθεί σε πολλούς γονικούς κόμβους για δημιουργία γεωμετρίας μέσω αντιγραφών |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | Λαμβάνει τη συλλογή όλων των ιδιοτήτων. |
| [Scene](../../aspose.threed/sceneobject/scene/) { get; } | Λαμβάνει τη σκηνή στην οποία ανήκει αυτό το αντικείμενο |
| [Shape](../../aspose.threed.entities/revolvedareasolid/shape/) { get; set; } | Λαμβάνει ή ορίζει το βασικό προφίλ που χρησιμοποιείται για την περιστροφή. |

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
| [ToMesh](../../aspose.threed.entities/revolvedareasolid/tomesh/)() | Μετατρέψτε το `RevolvedAreaSolid` σε πλέγμα. |

## Παραδείγματα

Ο παρακάτω κώδικας δείχνει πώς να χρησιμοποιήσετε το RevolvedAreaSolid για να περιστρέψετε ένα σχήμα σε ένα στερεό μοντέλο.

```csharp
using Aspose.ThreeD;
using Aspose.ThreeD.Entities;
using Aspose.ThreeD.Utilities;
using Aspose.ThreeD.Profiles;

//Δημιουργήστε μια νέα σκηνή 3D
Scene scene = new Scene();

// Αρχικοποιήστε το βασικό προφίλ που θα περιστραφεί
var profile = new RectangleShape()
{
    RoundingRadius = 0.3
};
//δημιουργήστε ένα αντικείμενο RevolvedAreaSolid
var revolved = new RevolvedAreaSolid()
{
  Shape = profile,
  Origin = new Vector3(1, 0, 0),
  AngleStart = 0,
  AngleEnd = Math.PI
};
scene.RootNode.CreateChildNode(revolved);

scene.Save("revolved.obj");
```

```csharp
//Δημιουργήστε μια νέα σκηνή 3D
Scene scene = new Scene();

// Αρχικοποιήστε το βασικό προφίλ που θα εξωθηθεί
var profile = new RectangleShape();
profile.setRoundingRadius(0.3);

var revolved = new RevolvedAreaSolid();
revolved.setShape(profile);
revolved.setOrigin(new Vector3(1, 0, 0));
revolved.setAngleStart(0);
revolved.setAngleEnd(Math.PI);
scene.getRootNode().createChildNode(revolved);

scene.save("revolved.obj");
```

### Δείτε επίσης

* class [Entity](../../aspose.threed/entity/)
* interface [IMeshConvertible](../imeshconvertible/)
* namespace [Aspose.ThreeD.Entities](../../aspose.threed.entities/)
* assembly [Aspose.3D](../../)



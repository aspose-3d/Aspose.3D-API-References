---
title: "Κλάση LinearExtrusion"
second_title: "Αναφορά API Aspose.3D για .NET"
description: "Aspose.ThreeD.Entities.LinearExtrusion κλάση. Η γραμμική εξώθηση λαμβάνει ένα σχήμα 2D ως είσοδο και επεκτείνει το σχήμα στην τρίτη διάσταση"
type: docs
weight: 490
url: /el/net/aspose.threed.entities/linearextrusion/
---
## LinearExtrusion class

Η γραμμική εξώθηση λαμβάνει ένα 2D σχήμα ως είσοδο και επεκτείνει το σχήμα στην τρίτη διάσταση.

```csharp
public class LinearExtrusion : Entity, IMeshConvertible
```

## Κατασκευαστές

| Όνομα | Περιγραφή |
| --- | --- |
| [LinearExtrusion](linearextrusion/#constructor)() | Κατασκευαστής της εμφάνισης `LinearExtrusion`. |
| [LinearExtrusion](linearextrusion/#constructor_1)(Profile, double) | Κατασκευαστής της εμφάνισης `LinearExtrusion`. |

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| [Center](../../aspose.threed.entities/linearextrusion/center/) { get; set; } | Εάν αυτή η τιμή είναι ψευδής, το εύρος Z της γραμμικής εξώθησης είναι από 0 έως το ύψος, διαφορετικά το εύρος είναι από -height/2 έως height/2. |
| [Direction](../../aspose.threed.entities/linearextrusion/direction/) { get; set; } | Η κατεύθυνση της εξώθησης, η προεπιλεγμένη τιμή είναι (0, 0, 1) |
| [Excluded](../../aspose.threed/entity/excluded/) { get; set; } | Λαμβάνει ή ορίζει αν αυτή η οντότητα θα εξαιρεθεί κατά την εξαγωγή. |
| [Height](../../aspose.threed.entities/linearextrusion/height/) { get; set; } | Το ύψος της εξωθημένης γεωμετρίας, η προεπιλεγμένη τιμή είναι 1.0 |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | Λαμβάνει ή ορίζει το όνομα. |
| [ParentNode](../../aspose.threed/entity/parentnode/) { get; set; } | Λαμβάνει ή ορίζει τον πρώτο γονικό κόμβο· εάν οριστεί ο πρώτος γονικός κόμβος, αυτή η οντότητα θα αποσυνδεθεί από άλλους γονικούς κόμβους. |
| [ParentNodes](../../aspose.threed/entity/parentnodes/) { get; } | Λαμβάνει όλους τους γονικούς κόμβους, μια οντότητα μπορεί να προσαρτηθεί σε πολλούς γονικούς κόμβους για δημιουργία γεωμετρίας μέσω αντιγραφών |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | Λαμβάνει τη συλλογή όλων των ιδιοτήτων. |
| [Scene](../../aspose.threed/sceneobject/scene/) { get; } | Λαμβάνει τη σκηνή στην οποία ανήκει αυτό το αντικείμενο |
| [Shape](../../aspose.threed.entities/linearextrusion/shape/) { get; set; } | Το βασικό σχήμα που θα εξωθηθεί. |
| [Slices](../../aspose.threed.entities/linearextrusion/slices/) { get; set; } | Οι φέτες της στριμωγμένης εξωθημένης γεωμετρίας, η προεπιλεγμένη τιμή είναι 1. |
| [Twist](../../aspose.threed.entities/linearextrusion/twist/) { get; set; } | Ο αριθμός των μοιρών μέσω των οποίων το σχήμα εξωθείται. |
| [TwistOffset](../../aspose.threed.entities/linearextrusion/twistoffset/) { get; set; } | Η μετατόπιση που χρησιμοποιείται στην στρίψη, η προεπιλεγμένη τιμή είναι (0, 0, 0). |

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
| [ToMesh](../../aspose.threed.entities/linearextrusion/tomesh/)() | Μετατρέψτε την εξώθηση σε πλέγμα. |

## Παραδείγματα

Ο παρακάτω κώδικας δείχνει πώς να χρησιμοποιήσετε το LinearExtrusion για να εξωθήσετε ένα σχήμα σε ένα στερεό μοντέλο.

```csharp
using Aspose.ThreeD;
using Aspose.ThreeD.Entities;
using Aspose.ThreeD.Utilities;
using Aspose.ThreeD.Profiles;

//Δημιουργήστε μια νέα σκηνή 3D
Scene scene = new Scene();

// Αρχικοποιήστε το βασικό προφίλ που θα εξωθηθεί
var profile = new RectangleShape()
{
	RoundingRadius = 0.3
};

// Δημιουργήστε αριστερό κόμβο
var left = scene.RootNode.CreateChildNode();
left.CreateChildNode(new Box(0.01, 3, 3));

// Δημιουργήστε δεξιό κόμβο
var right = scene.RootNode.CreateChildNode();
right.CreateChildNode(new Box(0.01, 3, 3));
right.Transform.Translation = new Vector3(5, 0, 0);

//Εκτελέστε γραμμική εξώθηση στον αριστερό κόμβο χρησιμοποιώντας τις ιδιότητες center και slices
left.CreateChildNode(new LinearExtrusion(profile, 10) { Center = false, Slices = 3, Twist = 20.0 });

// Εκτελέστε γραμμική εξώθηση στον αριστερό κόμβο χρησιμοποιώντας τις ιδιότητες center και slices
right.CreateChildNode(new LinearExtrusion(profile, 10) { Center = true, Slices = 3, Twist = 90.0 });

scene
```

### Δείτε επίσης

* class [Entity](../../aspose.threed/entity/)
* interface [IMeshConvertible](../imeshconvertible/)
* namespace [Aspose.ThreeD.Entities](../../aspose.threed.entities/)
* assembly [Aspose.3D](../../)



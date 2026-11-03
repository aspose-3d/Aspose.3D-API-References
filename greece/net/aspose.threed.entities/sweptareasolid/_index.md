---
title: "Κλάση SweptAreaSolid"
second_title: "Αναφορά API Aspose.3D για .NET"
description: "Κλάση Aspose.ThreeD.Entities.SweptAreaSolid. Ένα SweptAreaSolid δημιουργεί γεωμετρία σαρώντας ένα προφίλ κατά μήκος μιας directrix"
type: docs
weight: 750
url: /el/net/aspose.threed.entities/sweptareasolid/
---
## SweptAreaSolid class

Ένα `SweptAreaSolid` δημιουργεί μια γεωμετρία σαρώντας ένα προφίλ κατά μήκος μιας διευθεσίας.

```csharp
public class SweptAreaSolid : Entity, IMeshConvertible
```

## Κατασκευαστές

| Όνομα | Περιγραφή |
| --- | --- |
| [SweptAreaSolid](sweptareasolid/)() | Ο προεπιλεγμένος κατασκευαστής. |

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| [Directrix](../../aspose.threed.entities/sweptareasolid/directrix/) { get; set; } | Η διευθεσία με την οποία σαρώνεται η περιοχή σάρωσης. |
| [EndPoint](../../aspose.threed.entities/sweptareasolid/endpoint/) { get; set; } | Το σημείο τέλους της διευθεσίας. |
| [Excluded](../../aspose.threed/entity/excluded/) { get; set; } | Λαμβάνει ή ορίζει αν αυτή η οντότητα θα εξαιρεθεί κατά την εξαγωγή. |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | Λαμβάνει ή ορίζει το όνομα. |
| [ParentNode](../../aspose.threed/entity/parentnode/) { get; set; } | Λαμβάνει ή ορίζει τον πρώτο γονικό κόμβο· εάν οριστεί ο πρώτος γονικός κόμβος, αυτή η οντότητα θα αποσυνδεθεί από άλλους γονικούς κόμβους. |
| [ParentNodes](../../aspose.threed/entity/parentnodes/) { get; } | Λαμβάνει όλους τους γονικούς κόμβους, μια οντότητα μπορεί να προσαρτηθεί σε πολλούς γονικούς κόμβους για δημιουργία γεωμετρίας μέσω αντιγραφών |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | Λαμβάνει τη συλλογή όλων των ιδιοτήτων. |
| [Scene](../../aspose.threed/sceneobject/scene/) { get; } | Λαμβάνει τη σκηνή στην οποία ανήκει αυτό το αντικείμενο |
| [Shape](../../aspose.threed.entities/sweptareasolid/shape/) { get; set; } | Το βασικό προφίλ για τη δημιουργία της γεωμετρίας. |
| [StartPoint](../../aspose.threed.entities/sweptareasolid/startpoint/) { get; set; } | Το σημείο εκκίνησης της διευθεσίας. |

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
| [ToMesh](../../aspose.threed.entities/sweptareasolid/tomesh/)() | Μετατρέψτε το τρέχον αντικείμενο σε πλέγμα |

## Παραδείγματα

Ο παρακάτω κώδικας δείχνει πώς να μοντελοποιήσετε μια στερεή οντότητα σαρώντας ένα σχήμα C πάνω σε κύκλο.

```csharp
var directrix = new Circle(20);
var shape = new CShape();

var swept = new SweptAreaSolid()
{
  Shape = shape,
  Directrix = directrix,
  StartPoint = EndPoint.FromDegree(0),
  EndPoint = EndPoint.FromDegree(130)
};

var scene = new Scene();
scene.RootNode.CreateChildNode(swept);
scene.Save("swept.obj");
```

### Δείτε επίσης

* class [Entity](../../aspose.threed/entity/)
* interface [IMeshConvertible](../imeshconvertible/)
* namespace [Aspose.ThreeD.Entities](../../aspose.threed.entities/)
* assembly [Aspose.3D](../../)



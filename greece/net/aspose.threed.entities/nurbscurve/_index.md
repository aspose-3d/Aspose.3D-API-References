---
title: "Κλάση NurbsCurve"
second_title: "Αναφορά API Aspose.3D για .NET"
description: "Aspose.ThreeD.Entities.NurbsCurve class. Η καμπύλη NURBS είναι μια καμπύλη που αναπαρίσταται από NURBSNonuniform rational basis spline. Μια καμπύλη NURBS ορίζεται από τη σειρά της, ένα σύνολο βαρυμένων ControlPoints και KnotVectors. Το συστατικό w στο control point χρησιμοποιείται ως βάρος των control points, είτε είναι Δι-Διαστατική είτε Τρι-Διαστατική."
type: docs
weight: 520
url: /el/net/aspose.threed.entities/nurbscurve/
---
## NurbsCurve class

[NURBS curve](https://en.wikipedia.org/wiki/Non-uniform_rational_B-spline) is a curve represented by NURBS(Non-uniform rational basis spline), A NURBS curve is defined by its [`Order`](./order/), a set of weighted [`ControlPoints`](../geometry/controlpoints/) and a [`KnotVectors`](./knotvectors/) The w component in control point is used as control point's weight, whatever it is a TwoDimensional or ThreeDimensional

```csharp
public class NurbsCurve : Curve
```

## Κατασκευαστές

| Όνομα | Περιγραφή |
| --- | --- |
| [NurbsCurve](nurbscurve/#constructor)() | Αρχικοποιεί μια νέα παρουσία της κλάσης `NurbsCurve`. |
| [NurbsCurve](nurbscurve/#constructor_1)(string) | Αρχικοποιεί μια νέα παρουσία της κλάσης `NurbsCurve`. |

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| [Color](../../aspose.threed.entities/curve/color/) { get; set; } | Λαμβάνει ή ορίζει το χρώμα της γραμμής, η προεπιλεγμένη τιμή είναι λευκό (1, 1, 1) |
| [ControlPoints](../../aspose.threed.entities/nurbscurve/controlpoints/) { get; } | Λαμβάνει όλα τα σημεία ελέγχου |
| [CurveType](../../aspose.threed.entities/nurbscurve/curvetype/) { get; set; } | Λαμβάνει ή ορίζει τον τύπο της καμπύλης. |
| [Degree](../../aspose.threed.entities/nurbscurve/degree/) { get; set; } | Λαμβάνει ή ορίζει το βαθμό μιας καμπύλης NURBS, ο βαθμός ορίζεται ως Τάξη - 1 |
| [Dimension](../../aspose.threed.entities/nurbscurve/dimension/) { get; set; } | Λαμβάνει ή ορίζει τη διάσταση της καμπύλης. |
| [Excluded](../../aspose.threed/entity/excluded/) { get; set; } | Λαμβάνει ή ορίζει αν αυτή η οντότητα θα εξαιρεθεί κατά την εξαγωγή. |
| [KnotVectors](../../aspose.threed.entities/nurbscurve/knotvectors/) { get; } | Λαμβάνει το διάνυσμα κόμπων, είναι μια ακολουθία τιμών παραμέτρων που καθορίζει πού και πώς τα σημεία ελέγχου επηρεάζουν την καμπύλη NURBS. |
| [Multiplicity](../../aspose.threed.entities/nurbscurve/multiplicity/) { get; } | Λαμβάνει την πολλαπλότητα. |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | Λαμβάνει ή ορίζει το όνομα. |
| [Order](../../aspose.threed.entities/nurbscurve/order/) { get; set; } | Λαμβάνει ή ορίζει την τάξη μιας καμπύλης NURBS, καθορίζει τον αριθμό των κοντινών σημείων ελέγχου που επηρεάζουν οποιοδήποτε σημείο της καμπύλης. |
| [ParentNode](../../aspose.threed/entity/parentnode/) { get; set; } | Λαμβάνει ή ορίζει τον πρώτο γονικό κόμβο· εάν οριστεί ο πρώτος γονικός κόμβος, αυτή η οντότητα θα αποσυνδεθεί από άλλους γονικούς κόμβους. |
| [ParentNodes](../../aspose.threed/entity/parentnodes/) { get; } | Λαμβάνει όλους τους γονικούς κόμβους, μια οντότητα μπορεί να προσαρτηθεί σε πολλούς γονικούς κόμβους για δημιουργία γεωμετρίας μέσω αντιγραφών |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | Λαμβάνει τη συλλογή όλων των ιδιοτήτων. |
| [Rational](../../aspose.threed.entities/nurbscurve/rational/) { get; set; } | Λαμβάνει ή ορίζει αν είναι ρητή, αυτή η τιμή υποδεικνύει αν αυτή η `NurbsCurve` είναι ρητή spline ή μη ρητή spline. Η μη ρητή B-spline είναι μια ειδική περίπτωση των ρητών B-splines. |
| [Scene](../../aspose.threed/sceneobject/scene/) { get; } | Λαμβάνει τη σκηνή στην οποία ανήκει αυτό το αντικείμενο |

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| [Evaluate](../../aspose.threed.entities/nurbscurve/evaluate/)(int) | Αξιολογήστε την καμπύλη NURBS |
| [EvaluateAt](../../aspose.threed.entities/nurbscurve/evaluateat/)(double) | Αξιολογήστε το σημείο της καμπύλης στη συγκεκριμένη θέση |
| [FindProperty](../../aspose.threed/a3dobject/findproperty/)(string) | Βρίσκει την ιδιότητα. Μπορεί να είναι δυναμική ιδιότητα (Δημιουργείται από CreateDynamicProperty/SetProperty) ή εγγενής ιδιότητα (Αναγνωρίζεται με το όνομά της) |
| [GetBoundingBox](../../aspose.threed/entity/getboundingbox/)() | Λαμβάνει το πλαίσιο περιβάλλοντος της τρέχουσας οντότητας στο σύστημα συντεταγμένων του χώρου αντικειμένου της. |
| override [GetEntityRendererKey](../../aspose.threed.entities/curve/getentityrendererkey/)() | Λαμβάνει το κλειδί του αποτυπωτή οντότητας που είναι καταχωρημένο στον renderer |
| [GetProperty](../../aspose.threed/a3dobject/getproperty/)(string) | Λάβετε την τιμή της καθορισμένης ιδιότητας |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(Property) | Αφαιρεί μια δυναμική ιδιότητα. |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(string) | Αφαιρέστε την καθορισμένη ιδιότητα που προσδιορίζεται με το όνομα |
| [SetProperty](../../aspose.threed/a3dobject/setproperty/)(string, object) | Ορίζει την τιμή της καθορισμένης ιδιότητας |

### Δείτε επίσης

* class [Curve](../curve/)
* namespace [Aspose.ThreeD.Entities](../../aspose.threed.entities/)
* assembly [Aspose.3D](../../)



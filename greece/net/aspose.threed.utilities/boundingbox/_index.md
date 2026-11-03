---
title: "Δομή BoundingBox"
second_title: "Αναφορά API Aspose.3D για .NET"
description: "Δομή Aspose.ThreeD.Utilities.BoundingBox. Το πλαίσιο περιβλήματος ευθυγραμμισμένο στον άξονα."
type: docs
weight: 2670
url: /el/net/aspose.threed.utilities/boundingbox/
---
## BoundingBox structure

Το πλαίσιο οριοθέτησης ευθυγραμμισμένο με άξονες

```csharp
public struct BoundingBox
```

## Κατασκευαστές

| Όνομα | Περιγραφή |
| --- | --- |
| [BoundingBox](boundingbox/#constructor)(Vector3, Vector3) | Αρχικοποιήστε ένα πεπερασμένο πλαίσιο περιορισμού με δεδομένες ελάχιστες και μέγιστες γωνίες |
| [BoundingBox](boundingbox/#constructor_1)(double, double, double, double, double, double) | Αρχικοποιήστε ένα πεπερασμένο πλαίσιο περιορισμού με δεδομένες ελάχιστες και μέγιστες γωνίες |

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| static [Infinite](../../aspose.threed.utilities/boundingbox/infinite/) { get; } | Το άπειρο πλαίσιο περιορισμού |
| static [Null](../../aspose.threed.utilities/boundingbox/null/) { get; } | Το μηδενικό πλαίσιο περιορισμού |
| [Center](../../aspose.threed.utilities/boundingbox/center/) { get; } | Το κέντρο του πλαισίου περιβλήματος. |
| [Extent](../../aspose.threed.utilities/boundingbox/extent/) { get; } | Λαμβάνει το εύρος του πλαισίου περιορισμού. |
| [Maximum](../../aspose.threed.utilities/boundingbox/maximum/) { get; } | Η μέγιστη γωνία του πλαισίου περιορισμού |
| [Minimum](../../aspose.threed.utilities/boundingbox/minimum/) { get; } | Η ελάχιστη γωνία του πλαισίου περιορισμού |
| [Size](../../aspose.threed.utilities/boundingbox/size/) { get; } | Το μέγεθος του πλαισίου περιβλήματος |

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| static [FromGeometry](../../aspose.threed.utilities/boundingbox/fromgeometry/)(Geometry) | Δημιουργήστε ένα πλαίσιο περιβλήματος από τη δεδομένη γεωμετρία |
| [Contains](../../aspose.threed.utilities/boundingbox/contains/#contains)(BoundingBox) | Το πλαίσιο περιβλήματος για να ελέγξει αν βρίσκεται μέσα στο τρέχον πλαίσιο περιβλήματος. |
| [Contains](../../aspose.threed.utilities/boundingbox/contains/#contains_1)(Vector3) | Ελέγξτε αν το σημείο p βρίσκεται μέσα στο πλαίσιο περιβλήματος |
| override [Equals](../../aspose.threed.utilities/boundingbox/equals/)(object) | Καθορίζει αν δύο αντικείμενα είναι ίσα |
| override [GetHashCode](../../aspose.threed.utilities/boundingbox/gethashcode/)() | Επιστρέφει τον κωδικό κατακερματισμού για αυτήν την παρουσία. |
| [Merge](../../aspose.threed.utilities/boundingbox/merge/#merge)(BoundingBox) | Συγχωνεύει το νέο πλαίσιο στο τρέχον πλαίσιο περιορισμού. |
| [Merge](../../aspose.threed.utilities/boundingbox/merge/#merge_1)(Vector3) | Συγχωνεύστε το τρέχον πλαίσιο περιβλήματος με το δεδομένο σημείο |
| [Merge](../../aspose.threed.utilities/boundingbox/merge/#merge_2)(Vector4) | Συγχωνεύστε το τρέχον πλαίσιο περιβλήματος με το δεδομένο σημείο |
| [Merge](../../aspose.threed.utilities/boundingbox/merge/#merge_3)(double, double, double) | Συγχωνεύστε το τρέχον πλαίσιο περιβλήματος με το δεδομένο σημείο |
| [OverlapsWith](../../aspose.threed.utilities/boundingbox/overlapswith/)(BoundingBox) | Ελέγξτε αν το τρέχον πλαίσιο περιγράμματος επικαλύπτεται με το καθορισμένο πλαίσιο περιγράμματος. |
| [Scale](../../aspose.threed.utilities/boundingbox/scale/)() | Υπολογίζει την απόλυτη μεγαλύτερη τιμή συντεταγμένης οποιουδήποτε περιεχόμενου σημείου. |
| override [ToString](../../aspose.threed.utilities/boundingbox/tostring/)() | Λαμβάνει την αναπαράσταση συμβολοσειράς του πλαισίου περιορισμού. |
| [operator *](../../aspose.threed.utilities/boundingbox/op_multiply/) | Υπερφόρτωση τελεστή για πολλαπλασιασμό, η ελάχιστη και η μέγιστη γωνία του νέου πλαισίου περιγράμματος θα μετατραπούν από τον πίνακα. |

## Παραδείγματα

Ο παρακάτω κώδικας δείχνει πώς να λάβετε ένα πλαίσιο περιγράμματος από μια παρουσία Entity.

```csharp
var sphere = new Sphere();
var boundingBox = sphere.GetBoundingBox();
Console.WriteLine("Bounding box = " + boundingBox);
```

### Δείτε επίσης

* namespace [Aspose.ThreeD.Utilities](../../aspose.threed.utilities/)
* assembly [Aspose.3D](../../)



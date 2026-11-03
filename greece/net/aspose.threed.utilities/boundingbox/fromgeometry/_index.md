---
title: "BoundingBox.FromGeometry"
second_title: "Αναφορά API Aspose.3D για .NET"
description: "Μέθοδος BoundingBox. Δημιουργεί ένα bounding box από τη δοσμένη γεωμετρία"
type: docs
weight: 40
url: /el/net/aspose.threed.utilities/boundingbox/fromgeometry/
---
## BoundingBox.FromGeometry method

Δημιουργήστε ένα πλαίσιο περιβλήματος από τη δεδομένη γεωμετρία

```csharp
public static BoundingBox FromGeometry(Geometry geometry)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| γεωμετρία | Γεωμετρία | Η γεωμετρία για τον υπολογισμό του πλαισίου περιβάλλοντος |

### Τιμή επιστροφής

Το πλαίσιο περιβάλλοντος της δοσμένης γεωμετρίας

## Παραδείγματα

Ο παρακάτω κώδικας δείχνει πώς να κατασκευάσετε ένα πλαίσιο περιβάλλοντος από μια παρουσία γεωμετρίας.

```csharp
var sphere = (new Sphere()).ToMesh();
var boundingBox = BoundingBox.FromGeometry(sphere);
Console.WriteLine("Bounding box = " + boundingBox);
```

### Δείτε επίσης

* class [Geometry](../../../aspose.threed.entities/geometry/)
* struct [BoundingBox](../)
* namespace [Aspose.ThreeD.Utilities](../../boundingbox/)
* assembly [Aspose.3D](../../../)



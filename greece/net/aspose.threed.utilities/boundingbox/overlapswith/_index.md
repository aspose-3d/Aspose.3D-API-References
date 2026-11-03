---
title: "BoundingBox.OverlapsWith"
second_title: "Αναφορά API Aspose.3D για .NET"
description: "BoundingBox μέθοδος. Ελέγχει αν το τρέχον πλαίσιο περιγράμματος επικαλύπτεται με το καθορισμένο πλαίσιο περιγράμματος"
type: docs
weight: 140
url: /el/net/aspose.threed.utilities/boundingbox/overlapswith/
---
## BoundingBox.OverlapsWith method

Ελέγξτε αν το τρέχον πλαίσιο περιγράμματος επικαλύπτεται με το καθορισμένο πλαίσιο περιγράμματος.

```csharp
public bool OverlapsWith(BoundingBox box)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| πλαίσιο | BoundingBox | Το άλλο πλαίσιο περιγράμματος για δοκιμή |

### Τιμή επιστροφής

Αληθές εάν το τρέχον πλαίσιο περιγράμματος επικαλύπτεται με το δοσμένο.

## Παραδείγματα

Ο παρακάτω κώδικας δείχνει πώς να ελέγξετε αν δύο πλαίσια περιγράμματος επικαλύπτονται μεταξύ τους.

```csharp
var boundingBox = new BoundingBox(0, 0, 0, 10, 10, 10);
var bbox2 = new BoundingBox(1, 1, 1, 11, 11, 11);
Console.WriteLine("Bounding box overlaps = " + boundingBox.OverlapsWith(bbox2));
```

### Δείτε επίσης

* struct [BoundingBox](../)
* namespace [Aspose.ThreeD.Utilities](../../boundingbox/)
* assembly [Aspose.3D](../../../)



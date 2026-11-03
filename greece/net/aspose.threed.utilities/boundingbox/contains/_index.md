---
title: "BoundingBox.Contains"
second_title: "Αναφορά API Aspose.3D για .NET"
description: "BoundingBox μέθοδος. Ελέγχει αν το σημείο p βρίσκεται μέσα στο πλαίσιο περιγράμματος"
type: docs
weight: 100
url: /el/net/aspose.threed.utilities/boundingbox/contains/
---
## Contains(Vector3) {#contains_1}

Ελέγξτε αν το σημείο p βρίσκεται μέσα στο πλαίσιο περιβλήματος

```csharp
public bool Contains(Vector3 p)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| p | Vector3 | Το σημείο για δοκιμή |

### Τιμή επιστροφής

Αληθές εάν το σημείο βρίσκεται μέσα στο πλαίσιο περιγράμματος

## Παραδείγματα

Ο παρακάτω κώδικας δείχνει πώς να ελέγξετε αν ένα σημείο βρίσκεται μέσα στο πλαίσιο περιγράμματος.

```csharp
var boundingBox = new BoundingBox(0, 0, 0, 10, 10, 10);
var pt = new Vector3(4, 4, 4);
Console.WriteLine("Bounding box overlaps = " + boundingBox.Contains(pt));
```

### Δείτε επίσης

* struct [Vector3](../../vector3/)
* struct [BoundingBox](../)
* namespace [Aspose.ThreeD.Utilities](../../boundingbox/)
* assembly [Aspose.3D](../../../)

---

## Contains(BoundingBox) {#contains}

Το πλαίσιο περιβλήματος για να ελέγξει αν βρίσκεται μέσα στο τρέχον πλαίσιο περιβλήματος.

```csharp
public bool Contains(BoundingBox bbox)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| bbox | BoundingBox |  |

### Δείτε επίσης

* struct [BoundingBox](../)
* namespace [Aspose.ThreeD.Utilities](../../boundingbox/)
* assembly [Aspose.3D](../../../)



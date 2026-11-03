---
title: "BoundingBox.BoundingBox"
second_title: "Αναφορά API Aspose.3D για .NET"
description: "Κατασκευαστής BoundingBox. Αρχικοποιήστε ένα πεπερασμένο πλαίσιο περιβάλλοντος με δεδομένες ελάχιστες και μέγιστες γωνίες"
type: docs
weight: 10
url: /el/net/aspose.threed.utilities/boundingbox/boundingbox/
---
## BoundingBox(Vector3, Vector3) {#constructor}

Αρχικοποιήστε ένα πεπερασμένο πλαίσιο περιορισμού με δεδομένες ελάχιστες και μέγιστες γωνίες

```csharp
public BoundingBox(Vector3 minimum, Vector3 maximum)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| ελάχιστο | Vector3 | Η ελάχιστη γωνία |
| μέγιστο | Vector3 | Η μέγιστη γωνία |

## Παραδείγματα

Ο παρακάτω κώδικας δείχνει πώς να κατασκευάσετε ένα πλαίσιο περιβάλλοντος από τις ελάχιστες και τις μέγιστες γωνίες.

```csharp
var minimum = new Vector3(0, 0, 0);
var maximum = new Vector3(10, 10, 10);
var boundingBox = new BoundingBox(minimum, maximum);
Console.WriteLine("Bounding box = " + boundingBox);
```

### Δείτε επίσης

* struct [Vector3](../../vector3/)
* struct [BoundingBox](../)
* namespace [Aspose.ThreeD.Utilities](../../boundingbox/)
* assembly [Aspose.3D](../../../)

---

## BoundingBox(double, double, double, double, double, double) {#constructor_1}

Αρχικοποιήστε ένα πεπερασμένο πλαίσιο περιορισμού με δεδομένες ελάχιστες και μέγιστες γωνίες

```csharp
public BoundingBox(double minX, double minY, double minZ, double maxX, double maxY, double maxZ)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| minX | Διπλό | Το X της ελάχιστης γωνίας |
| minY | Διπλό | Το Y της ελάχιστης γωνίας |
| minZ | Διπλό | Το Z της ελάχιστης γωνίας |
| maxX | Διπλό | Το X της μέγιστης γωνίας |
| maxY | Διπλό | Το Y της μέγιστης γωνίας |
| maxZ | Διπλό | Το Z της μέγιστης γωνίας |

## Παραδείγματα

Ο παρακάτω κώδικας δείχνει πώς να κατασκευάσετε ένα πλαίσιο περιβάλλοντος από τις ελάχιστες και τις μέγιστες γωνίες.

```csharp
var boundingBox = new BoundingBox(0, 0, 0, 10, 10, 10);
Console.WriteLine("Bounding box = " + boundingBox);
```

### Δείτε επίσης

* struct [BoundingBox](../)
* namespace [Aspose.ThreeD.Utilities](../../boundingbox/)
* assembly [Aspose.3D](../../../)



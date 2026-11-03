---
title: "BoundingBox.Merge"
second_title: "Αναφορά API Aspose.3D για .NET"
description: "Μέθοδος BoundingBox. Συγχώνευση τρέχοντος πλαισίου περιορισμού με το δοσμένο σημείο"
type: docs
weight: 130
url: /el/net/aspose.threed.utilities/boundingbox/merge/
---
## Merge(Vector4) {#merge_2}

Συγχωνεύστε το τρέχον πλαίσιο περιβλήματος με το δεδομένο σημείο

```csharp
public void Merge(Vector4 pt)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| pt | Vector4 | Το σημείο που θα συγχωνευτεί στο πλαίσιο περιορισμού |

## Παραδείγματα

Ο παρακάτω κώδικας δείχνει πώς να συγχωνεύσετε ένα σημείο στο πλαίσιο περιορισμού.

```csharp
var boundingBox = BoundingBox.Null;
boundingBox.Merge(new Vector4(1, 10, -1));
Console.WriteLine("Bounding box = " + boundingBox);
```

### Δείτε επίσης

* struct [Vector4](../../vector4/)
* struct [BoundingBox](../)
* namespace [Aspose.ThreeD.Utilities](../../boundingbox/)
* assembly [Aspose.3D](../../../)

---

## Merge(Vector3) {#merge_1}

Συγχωνεύστε το τρέχον πλαίσιο περιβλήματος με το δεδομένο σημείο

```csharp
public void Merge(Vector3 pt)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| pt | Vector3 | Το σημείο που θα συγχωνευτεί στο πλαίσιο περιορισμού |

## Παραδείγματα

Ο παρακάτω κώδικας δείχνει πώς να συγχωνεύσετε ένα σημείο στο πλαίσιο περιορισμού.

```csharp
var boundingBox = BoundingBox.Null;
boundingBox.Merge(new Vector3(1, 10, -1));
Console.WriteLine("Bounding box = " + boundingBox);
```

### Δείτε επίσης

* struct [Vector3](../../vector3/)
* struct [BoundingBox](../)
* namespace [Aspose.ThreeD.Utilities](../../boundingbox/)
* assembly [Aspose.3D](../../../)

---

## Merge(double, double, double) {#merge_3}

Συγχωνεύστε το τρέχον πλαίσιο περιβλήματος με το δεδομένο σημείο

```csharp
public void Merge(double x, double y, double z)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| x | Διπλό | Το σημείο που θα συγχωνευτεί στο πλαίσιο περιορισμού |
| y | Διπλό | Το σημείο που θα συγχωνευτεί στο πλαίσιο περιορισμού |
| z | Διπλό | Το σημείο που θα συγχωνευτεί στο πλαίσιο περιορισμού |

## Παραδείγματα

Ο παρακάτω κώδικας δείχνει πώς να συγχωνεύσετε ένα σημείο στο πλαίσιο περιορισμού.

```csharp
var boundingBox = BoundingBox.Null;
boundingBox.Merge(1, 10, -1);
Console.WriteLine("Bounding box = " + boundingBox);
```

### Δείτε επίσης

* struct [BoundingBox](../)
* namespace [Aspose.ThreeD.Utilities](../../boundingbox/)
* assembly [Aspose.3D](../../../)

---

## Merge(BoundingBox) {#merge}

Συγχωνεύει το νέο πλαίσιο στο τρέχον πλαίσιο περιορισμού.

```csharp
public void Merge(BoundingBox bb)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| bb | BoundingBox | Το πλαίσιο περιγράμματος για συγχώνευση |

### Δείτε επίσης

* struct [BoundingBox](../)
* namespace [Aspose.ThreeD.Utilities](../../boundingbox/)
* assembly [Aspose.3D](../../../)



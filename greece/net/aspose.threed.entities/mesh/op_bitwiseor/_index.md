---
title: "Mesh.op_BitwiseOr"
second_title: "Αναφορά API Aspose.3D για .NET"
description: "Μέθοδος Mesh. Υπολογίζει την ένωση δύο πλεγμάτων"
type: docs
weight: 140
url: /el/net/aspose.threed.entities/mesh/op_bitwiseor/
---
## Mesh BitwiseOr operator

Υπολογίζει την ένωση δύο πλεγμάτων

```csharp
public static Mesh operator |(Mesh a, Mesh b)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| a | Πλέγμα | Πρώτο πλέγμα |
| b | Πλέγμα | Δεύτερο πλέγμα |

### Τιμή επιστροφής

Πλέγμα αποτελέσματος

## Παραδείγματα

Ο παρακάτω κώδικας δείχνει πώς να ενώσετε δύο πλέγματα σε ένα πλέγμα:

```csharp
var box1 = new Box(10, 10, 1).ToMesh();
var box2 = new Box(1, 1, 10).ToMesh();
var merged = box1 | box2;
```

### Δείτε επίσης

* class [Mesh](../)
* namespace [Aspose.ThreeD.Entities](../../mesh/)
* assembly [Aspose.3D](../../../)



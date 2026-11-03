---
title: "Mesh.op_BitwiseAnd"
second_title: "Αναφορά API Aspose.3D για .NET"
description: "Mesh method. Υπολογίζει τη τομή δύο πλεγμάτων"
type: docs
weight: 130
url: /el/net/aspose.threed.entities/mesh/op_bitwiseand/
---
## Mesh BitwiseAnd operator

Υπολογίζει την τομή δύο πλεγμάτων

```csharp
public static Mesh operator &(Mesh a, Mesh b)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| a | Πλέγμα | Πρώτο πλέγμα |
| b | Πλέγμα | Δεύτερο πλέγμα |

### Τιμή επιστροφής

Πλέγμα αποτελέσματος

## Παραδείγματα

Ο παρακάτω κώδικας δείχνει πώς να υπολογίσετε τη διαφορά δύο πλεγμάτων:

```csharp
var box1 = new Box(10, 10, 1).ToMesh();
var box2 = new Box(1, 1, 10).ToMesh();
Mesh merged = box1 & box2;
```

### Δείτε επίσης

* class [Mesh](../)
* namespace [Aspose.ThreeD.Entities](../../mesh/)
* assembly [Aspose.3D](../../../)



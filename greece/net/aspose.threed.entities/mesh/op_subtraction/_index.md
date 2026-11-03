---
title: "Mesh.op_Subtraction"
second_title: "Αναφορά API Aspose.3D για .NET"
description: "Mesh method. Υπολογίζει τη διαφορά δύο πλεγμάτων"
type: docs
weight: 150
url: /el/net/aspose.threed.entities/mesh/op_subtraction/
---
## Mesh Subtraction operator

Υπολογίστε τη διαφορά μεταξύ δύο πλεγμάτων

```csharp
public static Mesh operator -(Mesh a, Mesh b)
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
Mesh merged = box1 - box2;
```

### Δείτε επίσης

* class [Mesh](../)
* namespace [Aspose.ThreeD.Entities](../../mesh/)
* assembly [Aspose.3D](../../../)



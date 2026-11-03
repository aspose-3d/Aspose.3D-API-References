---
title: "Transform.SetGeometricRotation"
second_title: "Αναφορά API Aspose.3D για .NET"
description: "Μέθοδος Transform. Ορίζει την γεωμετρική περιστροφή Euler που μετράται σε μοίρες. Η γεωμετρική μετασχηματισμός επηρεάζει μόνο τις συνδεδεμένες οντότητες και αφήνει τους υποκόμβους αμετάβλητους. Θα συγχωνευτεί ως τοπικός μετασχηματισμός όταν εξάγετε τη γεωμετρική μετασχηματισμό σε τύπους αρχείων που δεν το υποστηρίζουν."
type: docs
weight: 160
url: /el/net/aspose.threed/transform/setgeometricrotation/
---
## Transform.SetGeometricRotation method

Ορίζει τη γεωμετρική περιστροφή Euler (μετρημένη σε μοίρες). Η Geometric transformation επηρεάζει μόνο τις συνδεδεμένες οντότητες και αφήνει τους θυγατρικούς κόμβους αμετάβλητους. Θα συγχωνευτεί ως local transformation όταν εξάγετε τη Geometric transformation σε τύπους αρχείων που δεν το υποστηρίζουν.

```csharp
public Transform SetGeometricRotation(double rx, double ry, double rz)
```

## Παραδείγματα

```csharp
Node node = new Node();
node.Transform.SetGeometricRotation(90, 0, 0);
```

### Δείτε επίσης

* class [Transform](../)
* namespace [Aspose.ThreeD](../../transform/)
* assembly [Aspose.3D](../../../)



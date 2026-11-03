---
title: "Transform.GeometricRotation"
second_title: "Αναφορά API Aspose.3D για .NET"
description: "Transform ιδιότητα. Λαμβάνει ή ορίζει την γεωμετρική περιστροφή Euler που μετράται σε μοίρες. Η γεωμετρική μετασχηματισμός επηρεάζει μόνο τις συνδεδεμένες οντότητες και αφήνει αμετάβλητους τους κόμβους-παιδιά. Θα συγχωνευτεί ως τοπικός μετασχηματισμός όταν εξάγετε τη γεωμετρική μετασχηματισμό σε τύπους αρχείων που δεν την υποστηρίζουν."
type: docs
weight: 20
url: /el/net/aspose.threed/transform/geometricrotation/
---
## Transform.GeometricRotation property

Λαμβάνει ή ορίζει την γεωμετρική περιστροφή Euler (μετρημένη σε μοίρες). Η Geometric transformation επηρεάζει μόνο τις συνδεδεμένες οντότητες και αφήνει τους θυγατρικούς κόμβους αμετάβλητους. Θα συγχωνευτεί ως local transformation όταν εξάγετε τη Geometric transformation σε τύπους αρχείων που δεν το υποστηρίζουν.

```csharp
public Vector3 GeometricRotation { get; set; }
```

## Παραδείγματα

```csharp
Node node = new Node();
node.getTransform().setGeometricRotation(new Vector3(90, 0, 0));
```

### Δείτε επίσης

* struct [Vector3](../../../aspose.threed.utilities/vector3/)
* class [Transform](../)
* namespace [Aspose.ThreeD](../../transform/)
* assembly [Aspose.3D](../../../)



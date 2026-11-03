---
title: "Transform.GeometricScaling"
second_title: "Αναφορά API Aspose.3D για .NET"
description: "Transform ιδιότητα. Λαμβάνει ή ορίζει τη γεωμετρική κλίμακα. Η γεωμετρική μετασχηματισμός επηρεάζει μόνο τις συνδεδεμένες οντότητες και αφήνει αμετάβλητους τους κόμβους-παιδιά. Θα συγχωνευτεί ως τοπικός μετασχηματισμός όταν εξάγετε τη γεωμετρική μετασχηματισμό σε τύπους αρχείων που δεν την υποστηρίζουν."
type: docs
weight: 30
url: /el/net/aspose.threed/transform/geometricscaling/
---
## Transform.GeometricScaling property

Λαμβάνει ή ορίζει τη γεωμετρική κλιμάκωση. Η Geometric transformation επηρεάζει μόνο τις συνδεδεμένες οντότητες και αφήνει τους θυγατρικούς κόμβους αμετάβλητους. Θα συγχωνευτεί ως local transformation όταν εξάγετε τη Geometric transformation σε τύπους αρχείων που δεν το υποστηρίζουν.

```csharp
public Vector3 GeometricScaling { get; set; }
```

## Παραδείγματα

```csharp
Node node = new Node();
node.Transform.GeometricScaling = new Vector3(2, 2, 2);
```

### Δείτε επίσης

* struct [Vector3](../../../aspose.threed.utilities/vector3/)
* class [Transform](../)
* namespace [Aspose.ThreeD](../../transform/)
* assembly [Aspose.3D](../../../)



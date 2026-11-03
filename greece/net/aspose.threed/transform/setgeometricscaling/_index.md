---
title: "Transform.SetGeometricScaling"
second_title: "Αναφορά API Aspose.3D για .NET"
description: "Μέθοδος Transform. Ορίζει τη γεωμετρική κλιμάκωση. Η γεωμετρική μετασχηματισμός επηρεάζει μόνο τις συνδεδεμένες οντότητες και αφήνει τους υποκόμβους αμετάβλητους. Θα συγχωνευτεί ως τοπικός μετασχηματισμός όταν εξάγετε τη γεωμετρική μετασχηματισμό σε τύπους αρχείων που δεν το υποστηρίζουν."
type: docs
weight: 170
url: /el/net/aspose.threed/transform/setgeometricscaling/
---
## Transform.SetGeometricScaling method

Ορίζει τη γεωμετρική κλιμάκωση. Η Geometric transformation επηρεάζει μόνο τις συνδεδεμένες οντότητες και αφήνει τους θυγατρικούς κόμβους αμετάβλητους. Θα συγχωνευτεί ως local transformation όταν εξάγετε τη Geometric transformation σε τύπους αρχείων που δεν το υποστηρίζουν.

```csharp
public Transform SetGeometricScaling(double sx, double sy, double sz)
```

## Παραδείγματα

```csharp
Node node = new Node();
node.Transform.SetGeometricScaling(2, 2, 2);
```

### Δείτε επίσης

* class [Transform](../)
* namespace [Aspose.ThreeD](../../transform/)
* assembly [Aspose.3D](../../../)



---
title: "Transform.SetGeometricTranslation"
second_title: "Αναφορά API Aspose.3D για .NET"
description: "Transform μέθοδος. Ορίζει τη γεωμετρική μετάφραση. Η γεωμετρική μετασχηματισμός επηρεάζει μόνο τις συνδεδεμένες οντότητες και αφήνει αμετάβλητους τους κόμβους-παιδιά. Θα συγχωνευτεί ως τοπικός μετασχηματισμός όταν εξάγετε τη γεωμετρική μετασχηματισμό σε τύπους αρχείων που δεν την υποστηρίζουν."
type: docs
weight: 180
url: /el/net/aspose.threed/transform/setgeometrictranslation/
---
## Transform.SetGeometricTranslation method

Ορίζει τη γεωμετρική μετάφραση. Η Geometric transformation επηρεάζει μόνο τις συνδεδεμένες οντότητες και αφήνει τους θυγατρικούς κόμβους αμετάβλητους. Θα συγχωνευτεί ως local transformation όταν εξάγετε τη Geometric transformation σε τύπους αρχείων που δεν το υποστηρίζουν.

```csharp
public Transform SetGeometricTranslation(double x, double y, double z)
```

## Παραδείγματα

```csharp
Node node = new Node();
node.Transform.SetGeometricTranslation(10, 0, 0);
```

### Δείτε επίσης

* class [Transform](../)
* namespace [Aspose.ThreeD](../../transform/)
* assembly [Aspose.3D](../../../)



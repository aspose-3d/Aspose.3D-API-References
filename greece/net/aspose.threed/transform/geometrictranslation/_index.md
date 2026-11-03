---
title: "Transform.GeometricTranslation"
second_title: "Αναφορά API Aspose.3D για .NET"
description: "Ιδιότητα Transform. Λαμβάνει ή ορίζει τη γεωμετρική μετάφραση. Η γεωμετρική μετασχηματισμός επηρεάζει μόνο τις συνδεδεμένες οντότητες και αφήνει τους υποκόμβους αμετάβλητους. Θα συγχωνευτεί ως τοπικός μετασχηματισμός όταν εξάγετε τη γεωμετρική μετασχηματισμό σε τύπους αρχείων που δεν το υποστηρίζουν."
type: docs
weight: 40
url: /el/net/aspose.threed/transform/geometrictranslation/
---
## Transform.GeometricTranslation property

Λαμβάνει ή ορίζει τη γεωμετρική μετάφραση. Η Geometric transformation επηρεάζει μόνο τις συνδεδεμένες οντότητες και αφήνει τους θυγατρικούς κόμβους αμετάβλητους. Θα συγχωνευτεί ως local transformation όταν εξάγετε τη Geometric transformation σε τύπους αρχείων που δεν το υποστηρίζουν.

```csharp
public Vector3 GeometricTranslation { get; set; }
```

## Παραδείγματα

```csharp
Node node = new Node();
node.Transform.GeometricTranslation = new Vector3(10, 0, 0);
```

### Δείτε επίσης

* struct [Vector3](../../../aspose.threed.utilities/vector3/)
* class [Transform](../)
* namespace [Aspose.ThreeD](../../transform/)
* assembly [Aspose.3D](../../../)



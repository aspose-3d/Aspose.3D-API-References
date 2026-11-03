---
title: "Κλάση GlobalTransform"
second_title: "Αναφορά API Aspose.3D για .NET"
description: "Aspose.ThreeD.GlobalTransform κλάση. Η γενική μετασχηματισμός είναι παρόμοια με το Transform, αλλά είναι αμετάβλητη ενώ αντιπροσωπεύει τον τελικό αξιολογημένο μετασχηματισμό. Χρησιμοποιείται δεξιόστροφο σύστημα συντεταγμένων κατά την αξιολόγηση του γενικού μετασχηματισμού."
type: docs
weight: 1560
url: /el/net/aspose.threed/globaltransform/
---
## GlobalTransform class

Ο γενικός μετασχηματισμός είναι παρόμοιος με [`Transform`](../transform/) αλλά είναι αμετάβλητος ενώ αντιπροσωπεύει τον τελικό αξιολογημένο μετασχηματισμό. Το δεξιόστροφο σύστημα συντεταγμένων χρησιμοποιείται κατά την αξιολόγηση του γενικού μετασχηματισμού.

```csharp
public class GlobalTransform
```

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| [EulerAngles](../../aspose.threed/globaltransform/eulerangles/) { get; } | Λαμβάνει την περιστροφή που εκφράζεται σε γωνίες Euler, μετρημένες σε μοίρες |
| [Rotation](../../aspose.threed/globaltransform/rotation/) { get; } | Λαμβάνει την περιστροφή που εκφράζεται σε quaternion. |
| [Scale](../../aspose.threed/globaltransform/scale/) { get; } | Λαμβάνει την κλίμακα |
| [TransformMatrix](../../aspose.threed/globaltransform/transformmatrix/) { get; } | Λαμβάνει τον πίνακα μετασχηματισμού. |
| [Translation](../../aspose.threed/globaltransform/translation/) { get; } | Λαμβάνει τη μετάφραση |

## Παραδείγματα

Ο παρακάτω κώδικας δείχνει πώς να διαβάσετε τον παγκόσμιο μετασχηματισμό του κόμβου

```csharp
Scene scene = new Scene();
var boxNode = scene.RootNode.CreateChildNode(new Box());
//Τοποθετήστε το κουτί στο (10, 0, 0)
boxNode.Transform.Translation = new Vector3(10, 0, 0);
var global = boxNode.GlobalTransform;
Console.WriteLine($"The box's position in world coordinate is {global.Translation}");
```

### Δείτε επίσης

* namespace [Aspose.ThreeD](../../aspose.threed/)
* assembly [Aspose.3D](../../)



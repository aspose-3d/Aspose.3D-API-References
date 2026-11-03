---
title: "Node.EvaluateGlobalTransform"
second_title: "Αναφορά API Aspose.3D για .NET"
description: "Μέθοδος Node. Αξιολογήστε τη γενική μετασχηματισμό, συμπεριλαμβανομένου ή όχι του γεωμετρικού μετασχηματισμού"
type: docs
weight: 180
url: /el/net/aspose.threed/node/evaluateglobaltransform/
---
## Node.EvaluateGlobalTransform method

Αξιολογεί τη γενική μετασχηματισμό, συμπεριλαμβάνοντας ή όχι τον γεωμετρικό μετασχηματισμό.

```csharp
public Matrix4 EvaluateGlobalTransform(bool withGeometricTransform)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| withGeometricTransform | Boolean | Εάν απαιτείται ο γεωμετρικός μετασχηματισμός. |

### Τιμή επιστροφής

Ο παγκόσμιος πίνακας μετασχηματισμού.

## Παραδείγματα

Ο παρακάτω κώδικας δείχνει πώς να διαβάσετε τον παγκόσμιο πίνακα μετασχηματισμού του κόμβου.

```csharp
Scene scene = new Scene();
var boxNode = scene.RootNode.CreateChildNode(new Box());
//Τοποθετήστε το κουτί στο (10, 0, 0)
boxNode.Transform.Translation = new Vector3(10, 0, 0);
Matrix4 mat = boxNode.EvaluateGlobalTransform(true);
Console.WriteLine($"The box's global transform matrix is {mat}");
```

### Δείτε επίσης

* struct [Matrix4](../../../aspose.threed.utilities/matrix4/)
* class [Node](../)
* namespace [Aspose.ThreeD](../../node/)
* assembly [Aspose.3D](../../../)



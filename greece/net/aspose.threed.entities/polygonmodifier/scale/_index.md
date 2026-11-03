---
title: "PolygonModifier.Scale"
second_title: "Αναφορά API Aspose.3D για .NET"
description: "PolygonModifier method. Κλιμακώστε όλα τα γεωμετρικά σχήματα. Κλιμακώστε τα σημεία ελέγχου, όχι τον πίνακα μετασχηματισμού σε αυτή τη σκηνή."
type: docs
weight: 60
url: /el/net/aspose.threed.entities/polygonmodifier/scale/
---
## Scale(Scene, Vector3) {#scale}

Κλιμακώστε όλες τις γεωμετρίες (Κλιμακώστε τα σημεία ελέγχου, όχι τον πίνακα μετασχηματισμού) σε αυτή τη σκηνή

```csharp
public static Scene Scale(Scene scene, Vector3 scale)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| σκηνή | Σκηνή | Η σκηνή προς κλιμάκωση |
| κλίμακα | Vector3 | Ο συντελεστής κλίμακας |

## Παραδείγματα

Ο παρακάτω κώδικας δείχνει πώς να κλιμακώσετε όλα τα γεωμετρικά σχήματα στη σκηνή κατά 10 φορές.

```csharp
//Φορτώστε ένα αρχείο δοκιμής για κλιμάκωση
var scene = Scene.FromFile("input.fbx");
//κλιμακώστε όλα τα γεωμετρικά σχήματα 10 φορές.
PolygonModifier.Scale(scene, new Vector3(10, 10, 10));
scene.Save("test.obj");
```

### Δείτε επίσης

* class [Scene](../../../aspose.threed/scene/)
* struct [Vector3](../../../aspose.threed.utilities/vector3/)
* class [PolygonModifier](../)
* namespace [Aspose.ThreeD.Entities](../../polygonmodifier/)
* assembly [Aspose.3D](../../../)

---

## Scale(Node, Vector3) {#scale_1}

Κλιμακώστε όλες τις γεωμετρίες (Κλιμακώστε τα σημεία ελέγχου, όχι τον πίνακα μετασχηματισμού) σε αυτόν τον κόμβο

```csharp
public static void Scale(Node node, Vector3 scale)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| κόμβος | Κόμβος | Ο κόμβος προς κλιμάκωση |
| κλίμακα | Vector3 | Ο συντελεστής κλίμακας |

## Παραδείγματα

Ο παρακάτω κώδικας δείχνει πώς να κλιμακώσετε όλα τα γεωμετρικά σχήματα στη σκηνή κατά 10 φορές.

```csharp
//Φορτώστε ένα αρχείο δοκιμής για κλιμάκωση
var scene = Scene.FromFile("input.fbx");
//κλιμακώστε όλα τα γεωμετρικά σχήματα 10 φορές.
PolygonModifier.Scale(scene.RootNode, new Vector3(10, 10, 10));
scene.Save("test.obj");
```

### Δείτε επίσης

* class [Node](../../../aspose.threed/node/)
* struct [Vector3](../../../aspose.threed.utilities/vector3/)
* class [PolygonModifier](../)
* namespace [Aspose.ThreeD.Entities](../../polygonmodifier/)
* assembly [Aspose.3D](../../../)



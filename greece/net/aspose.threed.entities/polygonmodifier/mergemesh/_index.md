---
title: "PolygonModifier.MergeMesh"
second_title: "Αναφορά API Aspose.3D για .NET"
description: "PolygonModifier method. Μετατρέψτε ολόκληρη τη σκηνή σε ένα ενιαίο μετασχηματισμένο πλέγμα. Τα στοιχεία κορυφής όπως οι κανονικές/συντεταγμένες υφής δεν υποστηρίζονται ακόμη."
type: docs
weight: 50
url: /el/net/aspose.threed.entities/polygonmodifier/mergemesh/
---
## MergeMesh(Scene) {#mergemesh_1}

Μετατρέψτε ολόκληρη τη σκηνή σε ένα μόνο μετασχηματισμένο πλέγμα. Τα στοιχεία κορυφής όπως normal/συντεταγμένες υφής δεν υποστηρίζονται ακόμη.

```csharp
public static Mesh MergeMesh(Scene scene)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| σκηνή | Σκηνή | Η σκηνή προς συγχώνευση |

### Τιμή επιστροφής

Το συγχωνευμένο πλέγμα

## Παραδείγματα

Ο παρακάτω κώδικας δείχνει πώς να συγχωνεύσετε όλα τα αντικείμενα από μια σκηνή σε ένα ενιαίο mesh.

```csharp
//Το αρχείο εισόδου μπορεί να περιέχει πολλαπλά αντικείμενα
var scene = Scene.FromFile("input.fbx");
//τώρα συγχωνεύστε τα σε ένα ενιαίο πλέγμα
Mesh merged = PolygonModifier.MergeMesh(scene);
//στη συνέχεια αποθηκεύουμε το σε ένα αρχείο με μόνο ένα πλέγμα
var newScene = new Scene(merged);
newScene.Save("test.obj");
```

### Δείτε επίσης

* class [Mesh](../../mesh/)
* class [Scene](../../../aspose.threed/scene/)
* class [PolygonModifier](../)
* namespace [Aspose.ThreeD.Entities](../../polygonmodifier/)
* assembly [Aspose.3D](../../../)

---

## MergeMesh(IList&lt;Node&gt;) {#mergemesh_2}

```csharp
public static Mesh MergeMesh(IList<Node> nodes)
```

### Δείτε επίσης

* class [Mesh](../../mesh/)
* class [Node](../../../aspose.threed/node/)
* class [PolygonModifier](../)
* namespace [Aspose.ThreeD.Entities](../../polygonmodifier/)
* assembly [Aspose.3D](../../../)

---

## MergeMesh(Node) {#mergemesh}

Μετατρέψτε ολόκληρο τον κόμβο σε ένα μόνο μετασχηματισμένο πλέγμα. Τα στοιχεία κορυφής όπως normal/συντεταγμένες υφής δεν υποστηρίζονται ακόμη.

```csharp
public static Mesh MergeMesh(Node node)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| κόμβος | Κόμβος | Ο κόμβος για συγχώνευση |

### Τιμή επιστροφής

Συγχωνευμένο πλέγμα

## Παραδείγματα

Ο παρακάτω κώδικας δείχνει πώς να συγχωνεύσετε όλα τα αντικείμενα από τους κόμβους σε ένα ενιαίο πλέγμα.

```csharp
//Το αρχείο εισόδου μπορεί να περιέχει πολλαπλά αντικείμενα
var scene = Scene.FromFile("input.fbx");
//τώρα συγχωνεύστε τα σε ένα ενιαίο πλέγμα
Mesh merged = PolygonModifier.MergeMesh(scene.RootNode);
//στη συνέχεια αποθηκεύουμε το σε ένα αρχείο με μόνο ένα πλέγμα
var newScene = new Scene(merged);
newScene.Save("test.obj");
```

### Δείτε επίσης

* class [Mesh](../../mesh/)
* class [Node](../../../aspose.threed/node/)
* class [PolygonModifier](../)
* namespace [Aspose.ThreeD.Entities](../../polygonmodifier/)
* assembly [Aspose.3D](../../../)



---
title: "PolygonModifier.SplitMesh"
second_title: "Αναφορά API Aspose.3D για .NET"
description: "Μέθοδος PolygonModifier. Διαχωρίστε το mesh σε submeshes με το VertexElementMaterial. Κάθε submesh θα χρησιμοποιεί μόνο ένα υλικό. Εκτελέστε το διαχωρισμό του mesh σε έναν κόμβο."
type: docs
weight: 70
url: /el/net/aspose.threed.entities/polygonmodifier/splitmesh/
---
## SplitMesh(Node, SplitMeshPolicy, bool, bool) {#splitmesh_1}

Διαχωρίστε το mesh σε sub-meshes με το [`VertexElementMaterial`](../../vertexelementmaterial/). Κάθε sub-mesh θα χρησιμοποιεί μόνο ένα υλικό. Εκτελέστε το διαχωρισμό του mesh σε έναν κόμβο.

```csharp
public static void SplitMesh(Node node, SplitMeshPolicy policy, bool createChildNodes = false, 
    bool removeOldMesh = true)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| κόμβος | Κόμβος |  |
| πολιτική | SplitMeshPolicy |  |
| createChildNodes | Boolean | Δημιουργήστε κόμβους-παιδιά για κάθε υπο-πλέγμα. |
| removeOldMesh | Boolean | Αφαιρέστε το παλιό πλέγμα μετά το διαχωρισμό, εάν αυτή η παράμετρος είναι ψευδής, τα παλιά και τα νέα πλέγματα θα συνυπάρχουν. |

## Παραδείγματα

Ο παρακάτω κώδικας δείχνει πώς να χωρίσετε ένα κουτί σε υπο-πλέγματα χρησιμοποιώντας δείκτες υλικού.

```csharp
// Δημιουργήστε ένα πλέγμα κουτιού (Ένα κουτί αποτελείται από 6 επίπεδα)
Mesh box = (new Box()).ToMesh();
// Δημιουργήστε ένα στοιχείο υλικού σε αυτό το πλέγμα
VertexElementMaterial mat = (VertexElementMaterial)box.CreateElement(VertexElementType.Material, MappingMode.Polygon, ReferenceMode.Index);
// Και καθορίστε διαφορετικό δείκτη υλικού για κάθε επίπεδο
mat.Indices.AddRange(new int[] { 0, 1, 2, 3, 4, 5 });
// Τώρα χωρίστε το σε 6 υπο-πλέγματα, καθορίσαμε 6 διαφορετικά υλικά σε κάθε επίπεδο, κάθε επίπεδο θα γίνει υπο-πλέγμα.
// Χρησιμοποιήσαμε την πολιτική CloneData, κάθε επίπεδο θα έχει τις ίδιες πληροφορίες σημείου ελέγχου ή πληροφορίες στοιχείου κορυφής βασισμένες σε σημεία ελέγχου.
Mesh[] planes = PolygonModifier.SplitMesh(box, SplitMeshPolicy.CloneData);

// Τώρα χωρίστε το σε 2 υπο-πλέγματα, το πρώτο πλέγμα θα περιέχει τα επίπεδα 0/1/2, και το δεύτερο πλέγμα θα περιέχει τα επίπεδα 3/4/5.
mat.Indices.Clear();
mat.Indices.AddRange(new int[] { 0, 0, 0, 1, 1, 1 });
// Χρησιμοποιήσαμε την πολιτική CompactData, κάθε επίπεδο θα έχει τις δικές του πληροφορίες σημείου ελέγχου ή πληροφορίες στοιχείου κορυφής βασισμένες σε σημεία ελέγχου.
planes = PolygonModifier.SplitMesh(box, SplitMeshPolicy.CompactData);
```

### Δείτε επίσης

* class [Node](../../../aspose.threed/node/)
* enum [SplitMeshPolicy](../../splitmeshpolicy/)
* class [PolygonModifier](../)
* namespace [Aspose.ThreeD.Entities](../../polygonmodifier/)
* assembly [Aspose.3D](../../../)

---

## SplitMesh(Scene, SplitMeshPolicy, bool) {#splitmesh_2}

Διαχωρίστε το πλέγμα σε υπο-πλέγματα με χρήση του [`VertexElementMaterial`](../../vertexelementmaterial/). Κάθε υπο-πλέγμα θα χρησιμοποιεί μόνο ένα υλικό. Εκτελέστε το διαχωρισμό του πλέγματος σε όλους τους κόμβους της σκηνής.

```csharp
public static void SplitMesh(Scene scene, SplitMeshPolicy policy, bool removeOldMesh = true)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| σκηνή | Σκηνή |  |
| πολιτική | SplitMeshPolicy |  |
| removeOldMesh | Boolean |  |

## Παραδείγματα

Ο παρακάτω κώδικας δείχνει πώς να χωρίσετε ένα κουτί σε υπο-πλέγματα χρησιμοποιώντας δείκτες υλικού.

```csharp
// Δημιουργήστε ένα πλέγμα κουτιού (Ένα κουτί αποτελείται από 6 επίπεδα)
Mesh box = (new Box()).ToMesh();
// Δημιουργήστε ένα στοιχείο υλικού σε αυτό το πλέγμα
VertexElementMaterial mat = (VertexElementMaterial)box.CreateElement(VertexElementType.Material, MappingMode.Polygon, ReferenceMode.Index);
// Και καθορίστε διαφορετικό δείκτη υλικού για κάθε επίπεδο
mat.Indices.AddRange(new int[] { 0, 1, 2, 3, 4, 5 });
// Τώρα χωρίστε το σε 6 υπο-πλέγματα, καθορίσαμε 6 διαφορετικά υλικά σε κάθε επίπεδο, κάθε επίπεδο θα γίνει υπο-πλέγμα.
// Χρησιμοποιήσαμε την πολιτική CloneData, κάθε επίπεδο θα έχει τις ίδιες πληροφορίες σημείου ελέγχου ή πληροφορίες στοιχείου κορυφής βασισμένες σε σημεία ελέγχου.
Mesh[] planes = PolygonModifier.SplitMesh(box, SplitMeshPolicy.CloneData);

// Τώρα χωρίστε το σε 2 υπο-πλέγματα, το πρώτο πλέγμα θα περιέχει τα επίπεδα 0/1/2, και το δεύτερο πλέγμα θα περιέχει τα επίπεδα 3/4/5.
mat.Indices.Clear();
mat.Indices.AddRange(new int[] { 0, 0, 0, 1, 1, 1 });
// Χρησιμοποιήσαμε την πολιτική CompactData, κάθε επίπεδο θα έχει τις δικές του πληροφορίες σημείου ελέγχου ή πληροφορίες στοιχείου κορυφής βασισμένες σε σημεία ελέγχου.
planes = PolygonModifier.SplitMesh(box, SplitMeshPolicy.CompactData);
```

### Δείτε επίσης

* class [Scene](../../../aspose.threed/scene/)
* enum [SplitMeshPolicy](../../splitmeshpolicy/)
* class [PolygonModifier](../)
* namespace [Aspose.ThreeD.Entities](../../polygonmodifier/)
* assembly [Aspose.3D](../../../)

---

## SplitMesh(Mesh, SplitMeshPolicy) {#splitmesh}

Διαχωρίστε το πλέγμα σε υπο-πλέγματα με χρήση του [`VertexElementMaterial`](../../vertexelementmaterial/). Κάθε υπο-πλέγμα θα χρησιμοποιεί μόνο ένα υλικό. Το αρχικό πλέγμα δεν θα αλλάξει.

```csharp
public static Mesh[] SplitMesh(Mesh mesh, SplitMeshPolicy policy)
```

### Τιμή επιστροφής

Νέα χωρισμένα πλέγματα

## Παραδείγματα

Ο παρακάτω κώδικας δείχνει πώς να χωρίσετε ένα κουτί σε υπο-πλέγματα χρησιμοποιώντας δείκτες υλικού.

```csharp
// Δημιουργήστε ένα πλέγμα κουτιού (Ένα κουτί αποτελείται από 6 επίπεδα)
Mesh box = (new Box()).ToMesh();
// Δημιουργήστε ένα στοιχείο υλικού σε αυτό το πλέγμα
VertexElementMaterial mat = (VertexElementMaterial)box.CreateElement(VertexElementType.Material, MappingMode.Polygon, ReferenceMode.Index);
// Και καθορίστε διαφορετικό δείκτη υλικού για κάθε επίπεδο
mat.Indices.AddRange(new int[] { 0, 1, 2, 3, 4, 5 });
// Τώρα χωρίστε το σε 6 υπο-πλέγματα, καθορίσαμε 6 διαφορετικά υλικά σε κάθε επίπεδο, κάθε επίπεδο θα γίνει υπο-πλέγμα.
// Χρησιμοποιήσαμε την πολιτική CloneData, κάθε επίπεδο θα έχει τις ίδιες πληροφορίες σημείου ελέγχου ή πληροφορίες στοιχείου κορυφής βασισμένες σε σημεία ελέγχου.
Mesh[] planes = PolygonModifier.SplitMesh(box, SplitMeshPolicy.CloneData);

// Τώρα χωρίστε το σε 2 υπο-πλέγματα, το πρώτο πλέγμα θα περιέχει τα επίπεδα 0/1/2, και το δεύτερο πλέγμα θα περιέχει τα επίπεδα 3/4/5.
mat.Indices.Clear();
mat.Indices.AddRange(new int[] { 0, 0, 0, 1, 1, 1 });
// Χρησιμοποιήσαμε την πολιτική CompactData, κάθε επίπεδο θα έχει τις δικές του πληροφορίες σημείου ελέγχου ή πληροφορίες στοιχείου κορυφής βασισμένες σε σημεία ελέγχου.
planes = PolygonModifier.SplitMesh(box, SplitMeshPolicy.CompactData);
```

### Δείτε επίσης

* class [Mesh](../../mesh/)
* enum [SplitMeshPolicy](../../splitmeshpolicy/)
* class [PolygonModifier](../)
* namespace [Aspose.ThreeD.Entities](../../polygonmodifier/)
* assembly [Aspose.3D](../../../)



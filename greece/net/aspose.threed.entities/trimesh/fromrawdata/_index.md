---
title: "TriMesh.FromRawData"
second_title: "Αναφορά API Aspose.3D για .NET"
description: "Μέθοδος TriMesh. Δημιουργία TriMesh από ακατέργαστα δεδομένα"
type: docs
weight: 40
url: /el/net/aspose.threed.entities/trimesh/fromrawdata/
---
## TriMesh.FromRawData method

Δημιουργήστε TriMesh από ακατέργαστα δεδομένα

```csharp
public static TriMesh FromRawData(VertexDeclaration vd, byte[] vertices, int[] indices, 
    bool generateVertexMapping)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| vd | VertexDeclaration | Δήλωση Vertex, πρέπει να περιέχει τουλάχιστον ένα πεδίο. |
| κορυφές | Byte[] | Τα δεδομένα εισόδου της κορυφής, το ελάχιστο μήκος των κορυφών πρέπει να είναι μεγαλύτερο ή ίσο με το μέγεθος της vertex declaration |
| indices | Int32[] | Οι δείκτες τριγώνων |
| generateVertexMapping | Boolean | Δημιουργήστε [`Vertex`](../../../aspose.threed.utilities/vertex/) για κάθε κορυφή, κάτι που δεν είναι απαραίτητο μόνο για σειριοποίηση/αποσειριοποίηση. |

### Τιμή επιστροφής

Η [`TriMesh`](../) παρουσία που περιέχει τον πίνακα byte εισόδου.

## Παρατηρήσεις

Το επιστρεφόμενο TriMesh δεν θα αντιγράψει τον πίνακα byte εισόδου για απόδοση, οι εξωτερικές αλλαγές στον πίνακα θα αντικατοπτρίζονται σε αυτήν την παρουσία.

## Παραδείγματα

Ο παρακάτω κώδικας δείχνει πώς να δημιουργήσετε ένα TriMesh από ακατέργαστα bytes, κάτι που είναι χρήσιμο όταν δημιουργείτε τη δική σας μορφή 3D.

```csharp
var indices = new int[] { 0,  1,  2 };
var vertices = new byte[]{
    0, 0, 0, 191,
    0, 0, 0, 0,
    0, 0, 0, 191,
    0, 0, 0, 191,
    0, 0, 0, 0,
    0, 0, 0, 63,
    0, 0, 0, 63,
    0, 0, 0, 0,
    0, 0, 0, 63
};
VertexDeclaration vd = new VertexDeclaration();
vd.AddField(VertexFieldDataType.FVector3, VertexFieldSemantic.Position);
var triMesh = TriMesh.FromRawData(vd, vertices, indices, true);
```

### Δείτε επίσης

* class [VertexDeclaration](../../../aspose.threed.utilities/vertexdeclaration/)
* class [TriMesh](../)
* namespace [Aspose.ThreeD.Entities](../../trimesh/)
* assembly [Aspose.3D](../../../)



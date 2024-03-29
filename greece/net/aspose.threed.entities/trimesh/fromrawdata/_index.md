---
title: FromRawData
second_title: Aspose.3D για Αναφορά API .NET
description: Δημιουργία TriMesh από ακατέργαστα δεδομένα
type: docs
weight: 40
url: /el/net/aspose.threed.entities/trimesh/fromrawdata/
---
## TriMesh.FromRawData method

Δημιουργία TriMesh από ακατέργαστα δεδομένα

```csharp
public static TriMesh FromRawData(VertexDeclaration vd, byte[] vertices, int[] indices, 
    bool generateVertexMapping)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| vd | VertexDeclaration | Η δήλωση κορυφής, πρέπει να περιέχει τουλάχιστον ένα πεδίο. |
| vertices | Byte[] | Τα δεδομένα κορυφής εισόδου, το ελάχιστο μήκος των κορυφών πρέπει να είναι μεγαλύτερο ή ίσο με το μέγεθος της δήλωσης κορυφής |
| indices | Int32[] | Οι δείκτες του τριγώνου |
| generateVertexMapping | Boolean | Παράγω[`Vertex`](../../../aspose.threed.utilities/vertex/) για κάθε κορυφή, κάτι που δεν είναι απαραίτητο για απλή σειριοποίηση/αποσειριοποίηση. |

### Επιστρεφόμενη Αξία

ο[`TriMesh`](../) παράδειγμα που ενθυλακώνει τον πίνακα byte εισόδου.

### Παρατηρήσεις

Το επιστρεφόμενο TriMesh δεν θα αντιγράψει τον πίνακα byte εισόδου για απόδοση, οι εξωτερικές αλλαγές στον πίνακα θα αντικατοπτρίζονται σε αυτήν την περίπτωση.

### Δείτε επίσης

* class [VertexDeclaration](../../../aspose.threed.utilities/vertexdeclaration/)
* class [TriMesh](../)
* χώρος ονομάτων [Aspose.ThreeD.Entities](../../trimesh/)
* συνέλευση [Aspose.3D](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.3D.dll -->

---
title: "TriMesh.LoadVerticesFromBytes"
second_title: "Αναφορά API Aspose.3D για .NET"
description: "TriMesh μέθοδος. Φορτώστε vertices από bytes, το μήκος των bytes πρέπει να είναι ακέραιο πολλαπλάσιο του μεγέθους του vertex"
type: docs
weight: 160
url: /el/net/aspose.threed.entities/trimesh/loadverticesfrombytes/
---
## TriMesh.LoadVerticesFromBytes method

Φορτώστε κορυφές από bytes, το μήκος των bytes πρέπει να είναι ακέραιο πολλαπλάσιο του μεγέθους της κορυφής.

```csharp
public void LoadVerticesFromBytes(byte[] verticesInBytes)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| verticesInBytes | Byte[] |  |

### Εξαιρέσεις

| εξαίρεση | συνθήκη |
| --- | --- |
| ArgumentNullException |  |
| ArgumentException |  |

## Παραδείγματα

Ο παρακάτω κώδικας δείχνει πώς να δημιουργήσετε ένα κενό TriMesh και να φορτώσετε χειροκίνητα vertices από ακατέργαστα bytes.

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
//Δημιουργήστε ένα κενό TriMesh με καθορισμένη δήλωση vertex
var triMesh = new TriMesh("", vd);
//Φορτώστε vertices απευθείας από bytes
triMesh.LoadVerticesFromBytes(vertices);
triMesh.AddTriangle(0, 1, 2);
```

```csharp
int[] indices = new int[] { 0,  1,  2 };
byte[] vertices = new byte[]{
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
vd.addField(VertexFieldDataType.F_VECTOR3, VertexFieldSemantic.POSITION);
//Δημιουργήστε ένα κενό TriMesh με καθορισμένη δήλωση vertex
var triMesh = new TriMesh("", vd);
//Φορτώστε vertices απευθείας από bytes
triMesh.loadVerticesFromBytes(vertices);
triMesh.addTriangle(0, 1, 2);
```

### Δείτε επίσης

* class [TriMesh](../)
* namespace [Aspose.ThreeD.Entities](../../trimesh/)
* assembly [Aspose.3D](../../../)



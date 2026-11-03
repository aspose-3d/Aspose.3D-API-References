---
title: "TriMesh.FromMesh"
second_title: "Αναφορά API Aspose.3D για .NET"
description: "Μέθοδος TriMesh. Δημιουργήστε ένα TriMesh από το δοσμένο αντικείμενο πλέγμα με την δοσμένη διάταξη κορυφής"
type: docs
weight: 30
url: /el/net/aspose.threed.entities/trimesh/frommesh/
---
## FromMesh(VertexDeclaration, Mesh) {#frommesh_1}

Δημιουργήστε ένα TriMesh από το δοσμένο αντικείμενο πλέγματος με τη δοσμένη διάταξη κορυφών.

```csharp
public static TriMesh FromMesh(VertexDeclaration declaration, Mesh mesh)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| δήλωση | VertexDeclaration | Ορισμός τύπου του Vertex, ή διάταξη μνήμης |
| πλέγμα | Πλέγμα | Πηγαίο πλέγμα |

### Τιμή επιστροφής

Παράδειγμα του TriMesh που μετατράπηκε από το πλέγμα εισόδου με την καθορισμένη διάταξη μνήμης του vertex

## Παραδείγματα

Ο παρακάτω κώδικας δείχνει πώς να δημιουργήσετε ένα TriMesh με προσαρμοσμένη διάταξη μνήμης και να το εξάγετε σε αρχείο.

```csharp
//Ορίστε μια δήλωση κορυφής ως {FVector3 Position; FVector3 Normal; FVector2 UV}
VertexDeclaration vd = new VertexDeclaration();
vd.AddField(VertexFieldDataType.FVector3, VertexFieldSemantic.Position);
vd.AddField(VertexFieldDataType.FVector3, VertexFieldSemantic.Normal);
vd.AddField(VertexFieldDataType.FVector2, VertexFieldSemantic.UV);
//Μετατρέψτε ένα πλέγμα σε tri-mesh χρησιμοποιώντας την καθορισμένη διάταξη μνήμης
var mesh = (new Sphere()).ToMesh();
var triMesh = TriMesh.FromMesh(vd, mesh);
//Αποθηκεύστε το σε ρεύμα, 115 κορυφές * 32 bytes ανά κορυφή
using (var stream = new FileStream("output.bin", FileMode.Create))
{
    triMesh.WriteVerticesTo(stream);
    //Αποθηκεύστε τους δείκτες ως ushort σε ρεύμα, 504 δείκτες * 2 bytes ανά δείκτη
    triMesh.Write16bIndicesTo(stream);
}
```

### Δείτε επίσης

* class [VertexDeclaration](../../../aspose.threed.utilities/vertexdeclaration/)
* class [Mesh](../../mesh/)
* class [TriMesh](../)
* namespace [Aspose.ThreeD.Entities](../../trimesh/)
* assembly [Aspose.3D](../../../)

---

## FromMesh(Mesh, bool) {#frommesh}

Δημιουργήστε ένα TriMesh από το δοσμένο αντικείμενο πλέγματος, η δήλωση κορυφών βασίζεται στη δομή του εισερχόμενου πλέγματος.

```csharp
public static TriMesh FromMesh(Mesh mesh, bool useFloat = true)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| πλέγμα | Πλέγμα |  |
| useFloat | Boolean | Χρησιμοποιήστε τύπο float αντί για τύπο double για κάθε στοιχείο του vertex. |

### Τιμή επιστροφής

Το [`TriMesh`](../) που δημιουργήθηκε από το δοσμένο [`Mesh`](../../mesh/)

## Παραδείγματα

Ο παρακάτω κώδικας δείχνει πώς να δημιουργήσετε ένα TriMesh με προσαρμοσμένη διάταξη μνήμης και να το εξάγετε σε αρχείο.

```csharp
//Ορίστε μια δήλωση κορυφής ως {FVector3 Position; FVector3 Normal; FVector2 UV}
VertexDeclaration vd = new VertexDeclaration();
vd.AddField(VertexFieldDataType.FVector3, VertexFieldSemantic.Position);
vd.AddField(VertexFieldDataType.FVector3, VertexFieldSemantic.Normal);
vd.AddField(VertexFieldDataType.FVector2, VertexFieldSemantic.UV);
//Μετατρέψτε ένα πλέγμα σε tri-mesh χρησιμοποιώντας την καθορισμένη διάταξη μνήμης
var mesh = (new Sphere()).ToMesh();
var triMesh = TriMesh.FromMesh(vd, mesh);
//Αποθηκεύστε το σε ρεύμα, 115 κορυφές * 32 bytes ανά κορυφή
using (var stream = new FileStream("output.bin", FileMode.Create))
{
    triMesh.WriteVerticesTo(stream);
    //Αποθηκεύστε τους δείκτες ως ushort σε ρεύμα, 504 δείκτες * 2 bytes ανά δείκτη
    triMesh.Write16bIndicesTo(stream);
}
```

### Δείτε επίσης

* class [Mesh](../../mesh/)
* class [TriMesh](../)
* namespace [Aspose.ThreeD.Entities](../../trimesh/)
* assembly [Aspose.3D](../../../)



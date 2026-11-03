---
title: "TriMesh.CopyFrom"
second_title: "Αναφορά API Aspose.3D για .NET"
description: "TriMesh μέθοδος. Αντιγράψτε το TriMesh από την είσοδο με νέα διάταξη κορυφών"
type: docs
weight: 20
url: /el/net/aspose.threed.entities/trimesh/copyfrom/
---
## TriMesh.CopyFrom method

Αντιγράψτε το [`TriMesh`](../) από την είσοδο με νέα διάταξη κορυφών

```csharp
public static TriMesh CopyFrom(TriMesh input, VertexDeclaration vd)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| είσοδος | TriMesh | Το TriMesh εισόδου για αντιγραφή |
| vd | VertexDeclaration | Η νέα δήλωση κορυφής του εξαγώμενου TriMesh |

### Τιμή επιστροφής

Μια νέα παρουσία του TriMesh με νέα δήλωση κορυφής.

## Παραδείγματα

```csharp
//Ορίστε μια δήλωση κορυφής ως {FVector3 Position; FVector3 Normal; FVector2 UV}
VertexDeclaration vd = new VertexDeclaration();
vd.AddField(VertexFieldDataType.FVector3, VertexFieldSemantic.Position);
vd.AddField(VertexFieldDataType.FVector3, VertexFieldSemantic.Normal);
vd.AddField(VertexFieldDataType.FVector2, VertexFieldSemantic.UV);
//Μετατρέψτε ένα πλέγμα σε TriMesh, η διάταξη προκύπτει αυτόματα από το πλέγμα εισόδου
var oldTriMesh = TriMesh.FromMesh((new Sphere()).ToMesh());
//Τώρα δημιουργήστε ένα νέο TriMesh από το παλιό TriMesh, χρησιμοποιώντας ρητή διάταξη μνήμης που ορίζεται από το vd
var newTriMesh = TriMesh.CopyFrom(oldTriMesh, vd);
```

### Δείτε επίσης

* class [VertexDeclaration](../../../aspose.threed.utilities/vertexdeclaration/)
* class [TriMesh](../)
* namespace [Aspose.ThreeD.Entities](../../trimesh/)
* assembly [Aspose.3D](../../../)



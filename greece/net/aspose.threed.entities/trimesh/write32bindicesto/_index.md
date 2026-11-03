---
title: "TriMesh.Write32bIndicesTo"
second_title: "Αναφορά API Aspose.3D για .NET"
description: "Μέθοδος TriMesh. Γράψτε τα δεδομένα δεικτών ως 32-bit ακέραιο στη ροή"
type: docs
weight: 280
url: /el/net/aspose.threed.entities/trimesh/write32bindicesto/
---
## TriMesh.Write32bIndicesTo method

Γράψτε τα δεδομένα δεικτών ως 32-bit ακέραιο στο ρεύμα.

```csharp
public void Write32bIndicesTo(Stream stream)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| stream | Stream |  |

## Παραδείγματα

```csharp
//Μετατρέψτε ένα πλέγμα σε TriMesh, η διάταξη προκύπτει αυτόματα από το πλέγμα εισόδου
var triMesh = TriMesh.FromMesh(new Sphere().ToMesh());
//Αποθηκεύστε το σε ρεύμα, 115 κορυφές * 32 bytes ανά κορυφή
var stream = new MemoryStream();
triMesh.WriteVerticesTo(stream);
//Αποθηκεύστε τους δείκτες ως ushort σε ρεύμα, 504 δείκτες * 2 bytes ανά δείκτη
triMesh.Write32bIndicesTo(stream);
```

### Δείτε επίσης

* class [TriMesh](../)
* namespace [Aspose.ThreeD.Entities](../../trimesh/)
* assembly [Aspose.3D](../../../)



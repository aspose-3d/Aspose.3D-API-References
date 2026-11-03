---
title: "TriMesh.WriteVerticesTo"
second_title: "Αναφορά API Aspose.3D για .NET"
description: "Μέθοδος TriMesh. Γράψτε τα δεδομένα κορυφών στη συγκεκριμένη ροή"
type: docs
weight: 290
url: /el/net/aspose.threed.entities/trimesh/writeverticesto/
---
## TriMesh.WriteVerticesTo method

Γράψτε τα δεδομένα κορυφών στο καθορισμένο ρεύμα.

```csharp
public void WriteVerticesTo(Stream stream)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| stream | Stream | Η ροή στην οποία θα γραφτούν τα δεδομένα κορυφών |

## Παραδείγματα

```csharp
//Μετατρέψτε ένα πλέγμα σε TriMesh, η διάταξη προκύπτει αυτόματα από το πλέγμα εισόδου
var triMesh = TriMesh.FromMesh(new Sphere().ToMesh());
//Αποθηκεύστε το σε ρεύμα, 115 κορυφές * 32 bytes ανά κορυφή
var stream = new MemoryStream();
triMesh.WriteVerticesTo(stream);
//Αποθηκεύστε τους δείκτες ως ushort σε ρεύμα, 504 δείκτες * 2 bytes ανά δείκτη
triMesh.Write16bIndicesTo(stream);
```

### Δείτε επίσης

* class [TriMesh](../)
* namespace [Aspose.ThreeD.Entities](../../trimesh/)
* assembly [Aspose.3D](../../../)



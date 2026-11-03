---
title: "Κλάση PolygonModifier"
second_title: "Αναφορά API Aspose.3D για .NET"
description: "Aspose.ThreeD.Entities.PolygonModifier κλάση. Εργαλεία για την τροποποίηση πολυγώνων"
type: docs
weight: 620
url: /el/net/aspose.threed.entities/polygonmodifier/
---
## PolygonModifier class

Εργαλεία για την τροποποίηση πολύγωνων.

```csharp
public class PolygonModifier
```

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| static [ApplyTransform](../../aspose.threed.entities/polygonmodifier/applytransform/)(Node, Matrix4) | Εφαρμόστε τον πίνακα μετασχηματισμού στα σημεία ελέγχου όλων των γεωμετριών |
| static [BuildTangentBinormal](../../aspose.threed.entities/polygonmodifier/buildtangentbinormal/#buildtangentbinormal)(Mesh) | Αυτό θα δημιουργήσει εφαπτομένη και binormal στο πλέγμα. Απαιτείται το Normal· εάν το normal δεν υπάρχει στο πλέγμα, θα δημιουργηθεί επίσης το δεδομένο normal από τη θέση. Απαιτείται επίσης το UV· θα προκληθεί εξαίρεση εάν δεν βρεθεί UV. |
| static [BuildTangentBinormal](../../aspose.threed.entities/polygonmodifier/buildtangentbinormal/#buildtangentbinormal_1)(Scene) | Αυτό θα δημιουργήσει εφαπτομένη και binormal σε όλα τα πλέγματα της σκηνής. Απαιτείται το Normal· εάν το normal δεν υπάρχει στο πλέγμα, θα δημιουργηθεί επίσης το δεδομένο normal από τη θέση. Απαιτείται επίσης το UV· το πλέγμα θα αγνοηθεί εάν δεν οριστεί UV. |
| static [GenerateNormal](../../aspose.threed.entities/polygonmodifier/generatenormal/)(Mesh) | Δημιουργήστε δεδομένα normal από τον ορισμό του Mesh |
| static [GenerateUV](../../aspose.threed.entities/polygonmodifier/generateuv/#generateuv)(Mesh) | Δημιουργήστε δεδομένα UV από το δοσμένο πλέγμα εισόδου |
| static [GenerateUV](../../aspose.threed.entities/polygonmodifier/generateuv/#generateuv_1)(Mesh, VertexElementNormal) | Δημιουργήστε δεδομένα UV από το δοσμένο πλέγμα εισόδου και τα καθορισμένα δεδομένα normal. |
| static [MergeMesh](../../aspose.threed.entities/polygonmodifier/mergemesh/#mergemesh_2)(IList&lt;Node&gt;) |  |
| static [MergeMesh](../../aspose.threed.entities/polygonmodifier/mergemesh/#mergemesh)(Node) | Μετατρέψτε ολόκληρο τον κόμβο σε ένα μόνο μετασχηματισμένο πλέγμα. Τα στοιχεία κορυφής όπως normal/συντεταγμένες υφής δεν υποστηρίζονται ακόμη. |
| static [MergeMesh](../../aspose.threed.entities/polygonmodifier/mergemesh/#mergemesh_1)(Scene) | Μετατρέψτε ολόκληρη τη σκηνή σε ένα μόνο μετασχηματισμένο πλέγμα. Τα στοιχεία κορυφής όπως normal/συντεταγμένες υφής δεν υποστηρίζονται ακόμη. |
| static [Scale](../../aspose.threed.entities/polygonmodifier/scale/#scale_1)(Node, Vector3) | Κλιμακώστε όλες τις γεωμετρίες (Κλιμακώστε τα σημεία ελέγχου, όχι τον πίνακα μετασχηματισμού) σε αυτόν τον κόμβο |
| static [Scale](../../aspose.threed.entities/polygonmodifier/scale/#scale)(Scene, Vector3) | Κλιμακώστε όλες τις γεωμετρίες (Κλιμακώστε τα σημεία ελέγχου, όχι τον πίνακα μετασχηματισμού) σε αυτή τη σκηνή |
| static [SplitMesh](../../aspose.threed.entities/polygonmodifier/splitmesh/#splitmesh)(Mesh, SplitMeshPolicy) | Διαιρέστε το πλέγμα σε υπο-πλέγματα με βάση το [`VertexElementMaterial`](../vertexelementmaterial/). Κάθε υπο-πλέγμα θα χρησιμοποιεί μόνο ένα υλικό. Το αρχικό πλέγμα δεν θα αλλάξει. |
| static [SplitMesh](../../aspose.threed.entities/polygonmodifier/splitmesh/#splitmesh_2)(Scene, SplitMeshPolicy, bool) | Διαιρέστε το πλέγμα σε υπο-πλέγματα με βάση το [`VertexElementMaterial`](../vertexelementmaterial/). Κάθε υπο-πλέγμα θα χρησιμοποιεί μόνο ένα υλικό. Εκτελέστε τη διάσπαση του πλέγματος σε όλους τους κόμβους της σκηνής. |
| static [SplitMesh](../../aspose.threed.entities/polygonmodifier/splitmesh/#splitmesh_1)(Node, SplitMeshPolicy, bool, bool) | Διαιρέστε το πλέγμα σε υπο-πλέγματα με βάση το [`VertexElementMaterial`](../vertexelementmaterial/). Κάθε υπο-πλέγμα θα χρησιμοποιεί μόνο ένα υλικό. Εκτελέστε τη διάσπαση του πλέγματος σε έναν κόμβο. |
| static [Triangulate](../../aspose.threed.entities/polygonmodifier/triangulate/#triangulate_1)(IList&lt;Vector4&gt;) |  |
| static [Triangulate](../../aspose.threed.entities/polygonmodifier/triangulate/#triangulate)(Mesh) | Μετατρέψτε ένα πλέγμα βασισμένο σε πολύγωνα σε πλήρες τριγωνικό πλέγμα. |
| static [Triangulate](../../aspose.threed.entities/polygonmodifier/triangulate/#triangulate_5)(Scene) | Μετατρέψτε όλα τα πλέγματα βασισμένα σε πολύγωνα σε πλήρη τριγωνικά πλέγματα. |
| static [Triangulate](../../aspose.threed.entities/polygonmodifier/triangulate/#triangulate_3)(IList&lt;Vector4&gt;, IList&lt;int[]&gt;) |  |
| static [Triangulate](../../aspose.threed.entities/polygonmodifier/triangulate/#triangulate_2)(IList&lt;Vector4&gt;, int[]) |  |
| static [Triangulate](../../aspose.threed.entities/polygonmodifier/triangulate/#triangulate_4)(IList&lt;Vector4&gt;, IList&lt;int[]&gt;, bool, out Vector3[]) |  |

### Δείτε επίσης

* namespace [Aspose.ThreeD.Entities](../../aspose.threed.entities/)
* assembly [Aspose.3D](../../)



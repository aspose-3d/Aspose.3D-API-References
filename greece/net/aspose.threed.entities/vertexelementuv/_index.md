---
title: "Κλάση VertexElementUV"
second_title: "Αναφορά API Aspose.3D για .NET"
description: "Aspose.ThreeD.Entities.VertexElementUV κλάση. Ορίζει τις συντεταγμένες UV για καθορισμένα στοιχεία. Μια γεωμετρία μπορεί να έχει πολλαπλά στοιχεία VertexElementUV και το καθένα έχει διαφορετικούς TextureMappings"
type: docs
weight: 960
url: /el/net/aspose.threed.entities/vertexelementuv/
---
## VertexElementUV class

Ορίζει τις συντεταγμένες UV για καθορισμένα στοιχεία. Μια γεωμετρία μπορεί να έχει πολλαπλά στοιχεία `VertexElementUV`, και το καθένα έχει διαφορετικό [`TextureMapping`](../texturemapping/)s.

```csharp
public class VertexElementUV : VertexElementVector4
```

## Κατασκευαστές

| Όνομα | Περιγραφή |
| --- | --- |
| [VertexElementUV](vertexelementuv/#constructor)() | Αρχικοποιεί μια νέα εμφάνιση της κλάσης `VertexElementUV`. Ο προεπιλεγμένος τύπος αντιστοίχισης υφής είναι Diffuse |
| [VertexElementUV](vertexelementuv/#constructor_1)(TextureMapping) | Αρχικοποιεί μια νέα εμφάνιση της κλάσης `VertexElementUV`. |

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| [Data](../../aspose.threed.entities/vertexelementvector4/data/) { get; } | Λαμβάνει τα δεδομένα κορυφής |
| [Indices](../../aspose.threed.entities/vertexelement/indices/) { get; } | Λαμβάνει τα δεδομένα δεικτών |
| [MappingMode](../../aspose.threed.entities/vertexelement/mappingmode/) { get; set; } | Λαμβάνει ή ορίζει πώς χαρτογραφείται το στοιχείο. |
| [Name](../../aspose.threed.entities/vertexelement/name/) { get; set; } | Λαμβάνει ή ορίζει το όνομα. |
| [ReferenceMode](../../aspose.threed.entities/vertexelement/referencemode/) { get; set; } | Λαμβάνει ή ορίζει πώς αναφέρεται το στοιχείο. |
| [VertexElementType](../../aspose.threed.entities/vertexelement/vertexelementtype/) { get; } | Λαμβάνει τον τύπο του [`VertexElement`](../vertexelement/) |

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| [AddData](../../aspose.threed.entities/vertexelementuv/adddata/#adddata)(IEnumerable&lt;Vector2&gt;) |  |
| [AddData](../../aspose.threed.entities/vertexelementuv/adddata/#adddata_1)(IEnumerable&lt;Vector3&gt;) |  |
| override [Clear](../../aspose.threed.entities/vertexelementvector4/clear/)() | Αφαιρεί όλα τα στοιχεία από τους άμεσους και τους πίνακες δεικτών. |
| [CopyTo](../../aspose.threed.entities/vertexelementvector4/copyto/)(VertexElementVector4) | Αντιγράφει δεδομένα στο καθορισμένο στοιχείο |
| [SetData](../../aspose.threed.entities/vertexelementvector4/setdata/)(Vector4[]) | Φορτώνει δεδομένα |
| [SetIndices](../../aspose.threed.entities/vertexelement/setindices/)(int[]) | Φορτώνει δείκτες |
| override [ToString](../../aspose.threed.entities/vertexelement/tostring/)() | Αναπαράσταση συμβολοσειράς του στοιχείου κορυφής. |

### Δείτε επίσης

* class [VertexElementVector4](../vertexelementvector4/)
* namespace [Aspose.ThreeD.Entities](../../aspose.threed.entities/)
* assembly [Aspose.3D](../../)



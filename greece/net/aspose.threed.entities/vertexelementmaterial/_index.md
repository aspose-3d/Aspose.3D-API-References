---
title: "Κλάση VertexElementMaterial"
second_title: "Αναφορά API Aspose.3D για .NET"
description: "Κλάση Aspose.ThreeD.Entities.VertexElementMaterial. Ορίζει δείκτη υλικού για καθορισμένα στοιχεία. Ένας κόμβος μπορεί να έχει πολλαπλά υλικά· το VertexElementMaterial χρησιμοποιείται για την απόδοση διαφορετικών τμημάτων της γεωμετρίας σε διαφορετικά υλικά"
type: docs
weight: 880
url: /el/net/aspose.threed.entities/vertexelementmaterial/
---
## VertexElementMaterial class

Ορίζει δείκτη υλικού για καθορισμένα στοιχεία. Ένας κόμβος μπορεί να έχει πολλαπλά υλικά, το `VertexElementMaterial` χρησιμοποιείται για την απόδοση διαφορετικών τμημάτων της γεωμετρίας σε διαφορετικά υλικά.

```csharp
public class VertexElementMaterial : VertexElement
```

## Κατασκευαστές

| Όνομα | Περιγραφή |
| --- | --- |
| [VertexElementMaterial](vertexelementmaterial/)() | Αρχικοποιεί ένα νέο στιγμιότυπο της κλάσης `VertexElementMaterial`. |

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| [Indices](../../aspose.threed.entities/vertexelement/indices/) { get; } | Λαμβάνει τα δεδομένα δεικτών |
| [MappingMode](../../aspose.threed.entities/vertexelement/mappingmode/) { get; set; } | Λαμβάνει ή ορίζει πώς χαρτογραφείται το στοιχείο. |
| [Name](../../aspose.threed.entities/vertexelement/name/) { get; set; } | Λαμβάνει ή ορίζει το όνομα. |
| [ReferenceMode](../../aspose.threed.entities/vertexelement/referencemode/) { get; set; } | Λαμβάνει ή ορίζει πώς αναφέρεται το στοιχείο. |
| [VertexElementType](../../aspose.threed.entities/vertexelement/vertexelementtype/) { get; } | Λαμβάνει τον τύπο του [`VertexElement`](../vertexelement/) |

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| override [Clear](../../aspose.threed.entities/vertexelementmaterial/clear/)() | Αφαιρεί όλα τα στοιχεία από τους άμεσους και τους πίνακες δεικτών. |
| [SetIndices](../../aspose.threed.entities/vertexelement/setindices/)(int[]) | Φορτώνει δείκτες |
| override [ToString](../../aspose.threed.entities/vertexelement/tostring/)() | Αναπαράσταση συμβολοσειράς του στοιχείου κορυφής. |

## Παραδείγματα

Ο παρακάτω κώδικας δείχνει πώς να αναθέσετε διαφορετικό υλικό σε διαφορετική πλευρά ενός κουτιού.

```csharp
// Δημιουργήστε ένα πλέγμα κουτιού (Ένα κουτί αποτελείται από 6 επίπεδα)
Mesh box = (new Box()).ToMesh();
// Δημιουργήστε ένα στοιχείο υλικού σε αυτό το πλέγμα
VertexElementMaterial mat = (VertexElementMaterial)box.CreateElement(VertexElementType.Material, MappingMode.Polygon, ReferenceMode.Index);
// Και καθορίστε διαφορετικό δείκτη υλικού για κάθε επίπεδο
mat.Indices.AddRange(new int[] { 0, 1, 2, 3, 4, 5 });
```

### Δείτε επίσης

* class [VertexElement](../vertexelement/)
* namespace [Aspose.ThreeD.Entities](../../aspose.threed.entities/)
* assembly [Aspose.3D](../../)



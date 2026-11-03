---
title: "Geometry.CreateElement"
second_title: "Αναφορά API Aspose.3D για .NET"
description: "Μέθοδος Geometry. Δημιουργεί ένα στοιχείο κορυφής με τον καθορισμένο τύπο και το προσθέτει στη γεωμετρία"
type: docs
weight: 90
url: /el/net/aspose.threed.entities/geometry/createelement/
---
## CreateElement(VertexElementType) {#createelement}

Δημιουργεί ένα στοιχείο κορυφής με καθορισμένο τύπο και το προσθέτει στη γεωμετρία.

```csharp
public VertexElement CreateElement(VertexElementType type)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τύπος | VertexElementType | Τύπος στοιχείου κορυφής |

### Τιμή επιστροφής

Δημιουργήθηκε το στοιχείο.

## Παρατηρήσεις

Εάν ο τύπος είναι UV, ένα [`VertexElementUV`](../../vertexelementuv/) με τύπο χαρτογράφησης υφής σε Diffuse θα δημιουργηθεί.

### Δείτε επίσης

* class [VertexElement](../../vertexelement/)
* enum [VertexElementType](../../vertexelementtype/)
* class [Geometry](../)
* namespace [Aspose.ThreeD.Entities](../../geometry/)
* assembly [Aspose.3D](../../../)

---

## CreateElement(VertexElementType, MappingMode, ReferenceMode) {#createelement_1}

Δημιουργεί ένα στοιχείο κορυφής με καθορισμένο τύπο και το προσθέτει στη γεωμετρία.

```csharp
public VertexElement CreateElement(VertexElementType type, MappingMode mappingMode, 
    ReferenceMode referenceMode)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τύπος | VertexElementType | Τύπος στοιχείου κορυφής |
| mappingMode | MappingMode | Προεπιλεγμένη λειτουργία χαρτογράφησης |
| referenceMode | ReferenceMode | Προεπιλεγμένη λειτουργία αναφοράς |

### Τιμή επιστροφής

Δημιουργήθηκε το στοιχείο.

## Παρατηρήσεις

Εάν ο τύπος είναι UV, ένα [`VertexElementUV`](../../vertexelementuv/) με τύπο χαρτογράφησης υφής σε Diffuse θα δημιουργηθεί.

### Δείτε επίσης

* class [VertexElement](../../vertexelement/)
* enum [VertexElementType](../../vertexelementtype/)
* enum [MappingMode](../../mappingmode/)
* enum [ReferenceMode](../../referencemode/)
* class [Geometry](../)
* namespace [Aspose.ThreeD.Entities](../../geometry/)
* assembly [Aspose.3D](../../../)



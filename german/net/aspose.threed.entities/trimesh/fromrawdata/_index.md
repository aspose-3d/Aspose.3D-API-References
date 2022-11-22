---
title: FromRawData
second_title: Aspose.3D für .NET-API-Referenz
description: TriMesh aus Rohdaten erstellen
type: docs
weight: 40
url: /de/net/aspose.threed.entities/trimesh/fromrawdata/
---
## TriMesh.FromRawData method

TriMesh aus Rohdaten erstellen

```csharp
public static TriMesh FromRawData(VertexDeclaration vd, byte[] vertices, int[] indices, 
    bool generateVertexMapping)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| vd | VertexDeclaration | Vertex-Deklaration, muss mindestens ein Feld enthalten. |
| vertices | Byte[] | Die eingegebenen Scheitelpunktdaten, die Mindestlänge der Scheitelpunkte muss größer oder gleich der Größe der Scheitelpunktdeklaration sein |
| indices | Int32[] | Die Dreiecksindizes |
| generateVertexMapping | Boolean | Generieren[`Vertex`](../../../aspose.threed.utilities/vertex) für jeden Scheitelpunkt, was nicht nur für die Serialisierung/Deserialisierung erforderlich ist. |

### Rückgabewert

Das[`TriMesh`](../../trimesh) Instanz, die das Eingabe-Byte-Array gekapselt hat.

### Bemerkungen

Das zurückgegebene TriMesh kopiert das Eingabe-Byte-Array nicht aus Leistungsgründen, externe Änderungen am Array werden in dieser Instanz widergespiegelt.

### Siehe auch

* class [VertexDeclaration](../../../aspose.threed.utilities/vertexdeclaration)
* class [TriMesh](../../trimesh)
* namensraum [Aspose.ThreeD.Entities](../../trimesh)
* Montage [Aspose.3D](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.3D.dll -->
---
title: "TriMesh.FromRawData"
second_title: "Aspose.3D für .NET API-Referenz"
description: "TriMesh-Methode. Erstellt ein TriMesh aus Rohdaten"
type: docs
weight: 40
url: /de/net/aspose.threed.entities/trimesh/fromrawdata/
---
## TriMesh.FromRawData method

Erstelle ein TriMesh aus Rohdaten

```csharp
public static TriMesh FromRawData(VertexDeclaration vd, byte[] vertices, int[] indices, 
    bool generateVertexMapping)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| vd | VertexDeclaration | Vertex-Deklaration, muss mindestens ein Feld enthalten. |
| vertices | Byte[] | Die Eingabe-Vertex-Daten, die minimale Länge der Vertices muss größer oder gleich der Größe von vertex declaration sein |
| indices | Int32[] | Die Dreiecksindizes |
| generateVertexMapping | Boolean | Erstelle [`Vertex`](../../../aspose.threed.utilities/vertex/) für jeden Vertex, was nur für Serialisierung/Deserialisierung nicht erforderlich ist. |

### Rückgabewert

Die [`TriMesh`](../)-Instanz, die das Eingabe-Byte-Array gekapselt hat.

## Hinweise

Das zurückgegebene TriMesh kopiert das Eingabe-Byte-Array aus Leistungsgründen nicht; externe Änderungen am Array werden in dieser Instanz reflektiert.

## Beispiele

Der folgende Code zeigt, wie man ein TriMesh aus Rohbytes konstruiert; das ist nützlich, wenn man sein eigenes 3D-Format erstellt

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
var triMesh = TriMesh.FromRawData(vd, vertices, indices, true);
```

### Siehe auch

* class [VertexDeclaration](../../../aspose.threed.utilities/vertexdeclaration/)
* class [TriMesh](../)
* namespace [Aspose.ThreeD.Entities](../../trimesh/)
* assembly [Aspose.3D](../../../)



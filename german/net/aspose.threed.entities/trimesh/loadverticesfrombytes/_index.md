---
title: "TriMesh.LoadVerticesFromBytes"
second_title: "Aspose.3D für .NET API-Referenz"
description: "TriMesh-Methode. Laden von Scheitelpunkten aus Bytes; die Länge der Bytes muss ein ganzzahliges Vielfaches der Vertexgröße sein."
type: docs
weight: 160
url: /de/net/aspose.threed.entities/trimesh/loadverticesfrombytes/
---
## TriMesh.LoadVerticesFromBytes method

Lade Scheitelpunkte aus Bytes, die Länge der Bytes muss ein ganzzahliges Vielfaches der Scheitelpunktgröße sein.

```csharp
public void LoadVerticesFromBytes(byte[] verticesInBytes)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| verticesInBytes | Byte[] |  |

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| ArgumentNullException |  |
| ArgumentException |  |

## Beispiele

Der folgende Code zeigt, wie man ein leeres TriMesh erstellt und Vertex-Daten manuell aus Rohbytes lädt.

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
//Erstelle ein leeres TriMesh mit einer angegebenen Vertex-Deklaration
var triMesh = new TriMesh("", vd);
//Lade Vertex-Daten direkt aus Bytes
triMesh.LoadVerticesFromBytes(vertices);
triMesh.AddTriangle(0, 1, 2);
```

```csharp
int[] indices = new int[] { 0,  1,  2 };
byte[] vertices = new byte[]{
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
vd.addField(VertexFieldDataType.F_VECTOR3, VertexFieldSemantic.POSITION);
//Erstelle ein leeres TriMesh mit einer angegebenen Vertex-Deklaration
var triMesh = new TriMesh("", vd);
//Lade Vertex-Daten direkt aus Bytes
triMesh.loadVerticesFromBytes(vertices);
triMesh.addTriangle(0, 1, 2);
```

### Siehe auch

* class [TriMesh](../)
* namespace [Aspose.ThreeD.Entities](../../trimesh/)
* assembly [Aspose.3D](../../../)



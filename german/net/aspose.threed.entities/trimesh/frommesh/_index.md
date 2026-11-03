---
title: "TriMesh.FromMesh"
second_title: "Aspose.3D für .NET API-Referenz"
description: "TriMesh-Methode. Erstelle ein TriMesh aus einem angegebenen Mesh-Objekt mit dem angegebenen Vertex-Layout"
type: docs
weight: 30
url: /de/net/aspose.threed.entities/trimesh/frommesh/
---
## FromMesh(VertexDeclaration, Mesh) {#frommesh_1}

Erstelle ein TriMesh aus dem angegebenen Mesh-Objekt mit dem angegebenen Scheitelpunkt-Layout.

```csharp
public static TriMesh FromMesh(VertexDeclaration declaration, Mesh mesh)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Deklaration | VertexDeclaration | Typdefinition von Vertex oder Speicherlayout |
| Mesh | Mesh | Quell-Mesh |

### Rückgabewert

Instanz von TriMesh, konvertiert vom Eingabe-Mesh mit dem angegebenen Speicherlayout des Vertex

## Beispiele

Der folgende Code zeigt, wie man ein TriMesh mit benutzerdefiniertem Speicherlayout erstellt und es in eine Datei exportiert.

```csharp
//Definiere eine Scheitelpunktdeklaration als {FVector3 Position; FVector3 Normal; FVector2 UV}
VertexDeclaration vd = new VertexDeclaration();
vd.AddField(VertexFieldDataType.FVector3, VertexFieldSemantic.Position);
vd.AddField(VertexFieldDataType.FVector3, VertexFieldSemantic.Normal);
vd.AddField(VertexFieldDataType.FVector2, VertexFieldSemantic.UV);
//Konvertiere ein Mesh zu Tri-Mesh unter Verwendung des angegebenen Speicherlayouts
var mesh = (new Sphere()).ToMesh();
var triMesh = TriMesh.FromMesh(vd, mesh);
//Speichere es in einen Stream, 115 Scheitelpunkte * 32 Bytes pro Scheitelpunkt
using (var stream = new FileStream("output.bin", FileMode.Create))
{
    triMesh.WriteVerticesTo(stream);
    //Speichere Indizes als ushort in den Stream, 504 Indizes * 2 Bytes pro Index
    triMesh.Write16bIndicesTo(stream);
}
```

### Siehe auch

* class [VertexDeclaration](../../../aspose.threed.utilities/vertexdeclaration/)
* class [Mesh](../../mesh/)
* class [TriMesh](../)
* namespace [Aspose.ThreeD.Entities](../../trimesh/)
* assembly [Aspose.3D](../../../)

---

## FromMesh(Mesh, bool) {#frommesh}

Erstelle ein TriMesh aus dem angegebenen Mesh-Objekt, die Scheitelpunktdeklaration basiert auf der Struktur des Eingabemeshs.

```csharp
public static TriMesh FromMesh(Mesh mesh, bool useFloat = true)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Mesh | Mesh |  |
| useFloat | Boolean | Verwenden Sie den Float-Typ anstelle des Double-Typs für jede Komponente des Vertex-Elements. |

### Rückgabewert

Das [`TriMesh`](../) erzeugt aus dem angegebenen [`Mesh`](../../mesh/)

## Beispiele

Der folgende Code zeigt, wie man ein TriMesh mit benutzerdefiniertem Speicherlayout erstellt und es in eine Datei exportiert.

```csharp
//Definiere eine Scheitelpunktdeklaration als {FVector3 Position; FVector3 Normal; FVector2 UV}
VertexDeclaration vd = new VertexDeclaration();
vd.AddField(VertexFieldDataType.FVector3, VertexFieldSemantic.Position);
vd.AddField(VertexFieldDataType.FVector3, VertexFieldSemantic.Normal);
vd.AddField(VertexFieldDataType.FVector2, VertexFieldSemantic.UV);
//Konvertiere ein Mesh zu Tri-Mesh unter Verwendung des angegebenen Speicherlayouts
var mesh = (new Sphere()).ToMesh();
var triMesh = TriMesh.FromMesh(vd, mesh);
//Speichere es in einen Stream, 115 Scheitelpunkte * 32 Bytes pro Scheitelpunkt
using (var stream = new FileStream("output.bin", FileMode.Create))
{
    triMesh.WriteVerticesTo(stream);
    //Speichere Indizes als ushort in den Stream, 504 Indizes * 2 Bytes pro Index
    triMesh.Write16bIndicesTo(stream);
}
```

### Siehe auch

* class [Mesh](../../mesh/)
* class [TriMesh](../)
* namespace [Aspose.ThreeD.Entities](../../trimesh/)
* assembly [Aspose.3D](../../../)



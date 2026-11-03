---
title: "TriMesh.CopyFrom"
second_title: "Aspose.3D für .NET API-Referenz"
description: "TriMesh-Methode. Kopiert das TriMesh aus der Eingabe mit neuem Vertex-Layout"
type: docs
weight: 20
url: /de/net/aspose.threed.entities/trimesh/copyfrom/
---
## TriMesh.CopyFrom method

Kopiere das [`TriMesh`](../) aus der Eingabe mit neuem Vertex-Layout

```csharp
public static TriMesh CopyFrom(TriMesh input, VertexDeclaration vd)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Eingabe | TriMesh | Das Eingabe‑TriMesh zum Kopieren |
| vd | VertexDeclaration | Die neue Vertex-Deklaration des Ausgabe‑TriMesh |

### Rückgabewert

Eine neue TriMesh-Instanz mit neuer Vertex-Deklaration.

## Beispiele

```csharp
//Definiere eine Scheitelpunktdeklaration als {FVector3 Position; FVector3 Normal; FVector2 UV}
VertexDeclaration vd = new VertexDeclaration();
vd.AddField(VertexFieldDataType.FVector3, VertexFieldSemantic.Position);
vd.AddField(VertexFieldDataType.FVector3, VertexFieldSemantic.Normal);
vd.AddField(VertexFieldDataType.FVector2, VertexFieldSemantic.UV);
//Konvertiere ein Mesh zu TriMesh, das Layout wird automatisch aus dem Eingabe‑Mesh abgeleitet
var oldTriMesh = TriMesh.FromMesh((new Sphere()).ToMesh());
//Jetzt erstelle ein neues TriMesh aus einem alten TriMesh, unter Verwendung des expliziten Speicherlayouts, das durch vd definiert ist
var newTriMesh = TriMesh.CopyFrom(oldTriMesh, vd);
```

### Siehe auch

* class [VertexDeclaration](../../../aspose.threed.utilities/vertexdeclaration/)
* class [TriMesh](../)
* namespace [Aspose.ThreeD.Entities](../../trimesh/)
* assembly [Aspose.3D](../../../)



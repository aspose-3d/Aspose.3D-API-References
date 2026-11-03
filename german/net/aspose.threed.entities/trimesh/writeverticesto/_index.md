---
title: "TriMesh.WriteVerticesTo"
second_title: "Aspose.3D für .NET API-Referenz"
description: "TriMesh-Methode. Schreibt Vertex-Daten in den angegebenen Stream"
type: docs
weight: 290
url: /de/net/aspose.threed.entities/trimesh/writeverticesto/
---
## TriMesh.WriteVerticesTo method

Schreibe die Scheitelpunktdaten in den angegebenen Stream

```csharp
public void WriteVerticesTo(Stream stream)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Stream | Stream | Der Stream, in den die Vertex-Daten geschrieben werden |

## Beispiele

```csharp
//Konvertiere ein Mesh zu TriMesh, das Layout wird automatisch aus dem Eingabe‑Mesh abgeleitet
var triMesh = TriMesh.FromMesh(new Sphere().ToMesh());
//Speichere es in einen Stream, 115 Scheitelpunkte * 32 Bytes pro Scheitelpunkt
var stream = new MemoryStream();
triMesh.WriteVerticesTo(stream);
//Speichere Indizes als ushort in den Stream, 504 Indizes * 2 Bytes pro Index
triMesh.Write16bIndicesTo(stream);
```

### Siehe auch

* class [TriMesh](../)
* namespace [Aspose.ThreeD.Entities](../../trimesh/)
* assembly [Aspose.3D](../../../)



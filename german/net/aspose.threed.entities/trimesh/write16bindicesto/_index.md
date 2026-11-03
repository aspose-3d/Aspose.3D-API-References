---
title: "TriMesh.Write16bIndicesTo"
second_title: "Aspose.3D für .NET API-Referenz"
description: "TriMesh-Methode. Schreibe die Indexdaten als 16‑Bit‑Integer in den Stream"
type: docs
weight: 270
url: /de/net/aspose.threed.entities/trimesh/write16bindicesto/
---
## TriMesh.Write16bIndicesTo method

Schreibe die Indexdaten als 16‑Bit‑Integer in den Stream

```csharp
public void Write16bIndicesTo(Stream stream)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Stream | Stream |  |

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



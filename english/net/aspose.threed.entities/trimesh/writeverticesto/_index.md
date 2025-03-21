---
title: TriMesh.WriteVerticesTo
second_title: Aspose.3D for .NET API Reference
description: TriMesh method. Write vertices data to the specified stream
type: docs
weight: 290
url: /net/aspose.threed.entities/trimesh/writeverticesto/
---
## TriMesh.WriteVerticesTo method

Write vertices data to the specified stream

```csharp
public void WriteVerticesTo(Stream stream)
```

| Parameter | Type | Description |
| --- | --- | --- |
| stream | Stream | The stream that the vertices data will be written to |

## Examples

```csharp
//convert a mesh to TriMesh, the layout is automatically inferred from input mesh
var triMesh = TriMesh.FromMesh(new Sphere().ToMesh());
//save it to a stream, 115 vertices * 32bytes per vertex
var stream = new MemoryStream();
triMesh.WriteVerticesTo(stream);
//save indices as ushort to stream, 504 indices * 2 bytes per index
triMesh.Write16bIndicesTo(stream);
```

### See Also

* class [TriMesh](../)
* namespace [Aspose.ThreeD.Entities](../../trimesh/)
* assembly [Aspose.3D](../../../)



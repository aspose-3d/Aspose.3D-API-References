---
title: TriMesh.Write16bIndicesTo
second_title: Aspose.3D for .NET API Reference
description: TriMesh method. Write the indices data as 16bit integer to the stream
type: docs
weight: 270
url: /net/aspose.threed.entities/trimesh/write16bindicesto/
---
## TriMesh.Write16bIndicesTo method

Write the indices data as 16bit integer to the stream

```csharp
public void Write16bIndicesTo(Stream stream)
```

| Parameter | Type | Description |
| --- | --- | --- |
| stream | Stream |  |

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


